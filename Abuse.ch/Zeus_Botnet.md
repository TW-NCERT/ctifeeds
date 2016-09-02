## Abuse.ch

A swiss guy fighting Cybercrime.

### Zeus Botnet

ZeuS (also known as Zbot / WSNPoem) is a crimeware kit, which steals credentials
from various online services like social networks, online banking accounts, ftp
accounts, email accounts and other (phishing). The web admin panel can be bought
for 700$ (source: RSA Security 4/21/2008) and the exe builder for 4'000$
(source: Prevx 3/15/2009).

The crimeware kit contains the following modules:
* A web interface to administrate and control the botnet (ZeuS Admin Panel)
* A tool to create the trojan binaries and encrypt the config file (called exe
builder)

Normaly, a ZeuS host consists of three componets / URIs:
* a config file (mostly with filextension \*.bin)
* a binary file which contains the newest version of the ZeuS trojan
* a dropzone (mostly a php file)

Some features of ZeuS are:

* Capture credentails out of HTTP-, HTTPS-, FTP- and POP3-traffic or out of the
  bot's protected storage (PStore).
* Group the infected clients into different botnets
* Integrated SOCKS-Proxy
* Web form to search the captured credentials
* Encrypted config file
* Function to kill the Operating System

Currently there are two versions of the ZeuS config file out there:

**Version 1**

Config file is scrambled (not encrypted!). If you know the algorithm, you can
descramble ALL config files which are v1. There is already a plublic tool
available to descramble v1 config files.

**Version 2**

Config file is encrypted. Each ZeuS installation has its own key defined by the
botnet master to decrypt the config file . If you have the ZeuS binary, it is
possible to extract the key in order to decrypt associated v2 config files. No
public tool available.

#### Domain Name
>
* Website
 - `https://zeustracker.abuse.ch/`
* Source
 - `https://zeustracker.abuse.ch/blocklist.php?download=baddomains`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

##### Sample Output of IntelMQ

```javascript
{
  "time": {
    "observation": "2016-07-07T08:13:55+00:00"
  },
  "classification": {
    "type": "c&c"
  },
  "feed": {
    "name": "Abuse.ch",
    "accuracy": 100,
    "url": "https:\/\/zeustracker.abuse.ch\/blocklist.php?download=baddomains"
  },
  "malware": {
    "name": "zeus"
  },
  "raw": "MHgueC5nZw==",
  "source": {
    "fqdn": "0x.x.gg"
  }
}
```

#### IP Address
>
* Website
 - `https://zeustracker.abuse.ch/`
* Source
 - `https://zeustracker.abuse.ch/blocklist.php?download=badips`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

##### Sample Output of IntelMQ

```javascript
{
  "malware": {
    "name": "zeus"
  },
  "raw": "MTAxLjAuODkuMw==",
  "source": {
    "ip": "101.0.89.3"
  },
  "classification": {
    "type": "c&c"
  },
  "time": {
    "observation": "2016-07-07T08:16:17+00:00"
  },
  "feed": {
    "name": "Abuse.ch",
    "accuracy": 100,
    "url": "https:\/\/zeustracker.abuse.ch\/blocklist.php?download=badips"
  }
}
```

----

There's only Domain information in  in https://zeustracker.abuse.ch/blocklist.php?download=baddomains. It looks like:

    ############################################################################
    # abuse.ch ZeuS domain blocklist "BadDomains" (excluding hijacked sites)   #
    #                                                                          #
    # For questions please refer to https://zeustracker.abuse.ch/blocklist.php #
    ############################################################################

    1st.technology
    arvision.com.co
    atmape.ru
    bestdove.in.ua

There's only IP information in https://zeustracker.abuse.ch/blocklist.php?download=badips.
It looks like:

    #############################################################################################
    # abuse.ch ZeuS IP blocklist "BadIPs" (excluding hijacked sites and free hosting providers) #
    #                                                                                           #
    # For questions please refer to https://zeustracker.abuse.ch/blocklist.php                  #
    #############################################################################################

    101.0.89.3
    101.200.81.187

But there's more information in https://zeustracker.abuse.ch/blocklist.php

* Compromised URL
* Snort rule
* Iptables rule
* Blocklist for Windows(Hostfile)
* Blocklist for Unix(Hosts.deny)