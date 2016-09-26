## Abuse.ch

A swiss guy fighting Cybercrime.

### Feodo Botnet

Feodo (also known as Cridex or Bugat) is a Trojan used to commit ebanking fraud
and steal sensitive information from the victims computer,
such as credit card details or credentials.

At the moment, Feodo Tracker is tracking four versions of Feodo,
and they are labeled by Feodo Tracker as:

* Version A: Hosted on compromised webservers running an nginx proxy on port
  8080 TCP forwarding all botnet traffic to a tier 2 proxy node. Botnet traffic
  usually directly hits these hosts on port 8080 TCP without using a domain
  name.
* Version B: Hosted on servers rented and operated by cybercriminals for the
  exclusive purpose of hosting a Feodo botnet controller. Usually taking
  advantage of a domain name within ccTLD .ru. Botnet traffic usually hits these
  domain names using port 80 TCP.
* Version C: Successor of Feodo, completely different code. Hosted on the same
  botnet infrastructure as Version A (compromised webservers, nginx on port 8080
  TCP or port 7779 TCP, no domain names) but using a different URL structure.
  This Version is also known as Geodo and Emotet.
* Version D: Successor of Cridex. This version is also known as Dridex

#### Domain Name
>
* Website
 - `https://feodotracker.abuse.ch/`
* Source
 - `https://feodotracker.abuse.ch/blocklist/?download=domainblocklist`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No present data.

##### Sample Output of IntelMQ

```javascript
{
  null
}
```

#### IP Address
>
* Website
 - `https://feodotracker.abuse.ch/`
* Source
 - `https://feodotracker.abuse.ch/blocklist/?download=ipblocklist`
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
    "name": "cridex"
  },
  "classification": {
    "type": "c&c"
  },
  "time": {
    "source": "2016-07-07T07:58:29+00:00",
    "observation": "2016-07-07T07:58:29+00:00"
  },
  "raw": "MS4xNzguMTc5LjIxNw==",
  "feed": {
    "url": "https:\/\/feodotracker.abuse.ch\/blocklist\/?download=ipblocklist",
    "accuracy": 100,
    "name": "Abuse.ch"
  },
  "source": {
    "ip": "1.178.179.217"
  }
}
```

----

There's only Domain information in
https://zeustracker.abuse.ch/blocklist.php?download=baddomains. It looks like:


    ##########################################################################
    # Feodo Domain Blocklist                                                 #
    # Generated on 2016-09-26 07:43:48 UTC                                   #
    #                                                                        #
    # For questions please refer to https://feodotracker.abuse.ch/blocklist/ #
    ##########################################################################
    # START
    # END (0 entries)

But the domain information is empty.

----

There's only IP information in  in 
https://feodotracker.abuse.ch/blocklist/?download=ipblocklist. It looks like:


    ##########################################################################
    # Feodo IP Blocklist                                                     #
    # Generated on 2016-08-05 02:39:17 UTC                                   #
    #                                                                        #
    # For questions please refer to https://feodotracker.abuse.ch/blocklist/ #
    ##########################################################################
    # START
    1.178.179.217
    1.179.170.7
    # END (683 entries)


But there's more information in https://feodotracker.abuse.ch/?sort=lastseen :

* Firstseen (UTC)
* Version of Feodo
* Feodo C&C (IP)
* Status
* SBL (Spamhaus Block List)
* ASN
* Country
* Lastseen (UTC)
