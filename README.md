Cyber Threat Intelligence Feeds (CTIFeeds)
==========================================
@(Information Security)[resource, links, security]

----------

[TOC]

----------

Open Source Intelligence
========================

## Abuse.ch 

A swiss guy fighting Cybercrime.

### [Feodo Botnet][1] 

Feodo (also known as Cridex or Bugat) is a Trojan used to commit ebanking fraud 
and steal sensitive information from the victims computer, 
such as credit card details or credentials. 

At the moment, Feodo Tracker is tracking four versions of Feodo, 
and they are labeled by Feodo Tracker as:

* Version A: Hosted on compromised webservers running an nginx proxy on port 8080 TCP forwarding all botnet traffic to a tier 2 proxy node. Botnet traffic usually directly hits these hosts on port 8080 TCP without using a domain name.
* Version B: Hosted on servers rented and operated by cybercriminals for the exclusive purpose of hosting a Feodo botnet controller. Usually taking advantage of a domain name within ccTLD .ru. Botnet traffic usually hits these domain names using port 80 TCP.
* Version C: Successor of Feodo, completely different code. Hosted on the same botnet infrastructure as Version A (compromised webservers, nginx on port 8080 TCP or port 7779 TCP, no domain names) but using a different URL structure. This Version is also known as Geodo and Emotet.
* Version D: Successor of Cridex. This version is also known as Dridex

#### Domain Blacklist
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

#### IP Blacklist
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

### [Palevo Worm][2]

#### Domain Blacklist
>
* Website
 - `https://palevotracker.abuse.ch/`
* Source
 - `https://palevotracker.abuse.ch/blocklists.php?download=domainblocklist`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Palevo Tracker has been discontinued.

#### IP Blacklist
>
* Website
 - `https://palevotracker.abuse.ch/`
* Source
 - `https://palevotracker.abuse.ch/blocklists.php?download=ipblocklist`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Palevo Tracker has been discontinued.

### [Zeus Botnet][3]

#### Domain Blacklist
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

#### IP Blacklist
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


## Alien Vault

### [Miscellaneous][4]

#### IP Blacklist
>
* Website
 - `https://www.alienvault.com/`
* Source
 - `https://reputation.alienvault.com/reputation.data`
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


## Arbor

### [Distributed SSH Brute Force Attacks][5]

#### IP Blacklist
>
* Website
 - `https://atlas.arbor.net/`
* Source
 - `http://atlas-public.ec2.arbor.net/public/ssh_attackers`
* Data
 - IP Address
* Format
 - XML
* API/Token
 - None
* Status
 - Error
* Comments
 - 403 Forbidden


## Blocklist.de

### [Attacks on the service Apache][6]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/apache.txt`
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

### [REG-Bots, IRC-Bots or BadBots (Spamming)][7]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/bots.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### [Brute-Force Website Logins][8]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/bruteforcelogin.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### [Attacks on the service FTP][9]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/ftp.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### [Attacks on the service IMAP, SASL, POP3][10]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/imap.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### [IRC Botnet][11]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/ircbot.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No present data.

### [Attacks on the service Mail, Postfix][12]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/mail.txt`
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

### [Brute-Force SIP-, VOIP- or Asterisk-Server Logins Attacks][13]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/sip.txt`
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

### [Attacks on the service SSH][14]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/ssh.txt`
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

### [All IPs which are older then 2 month and have more then 5,000 attacks (Strong IPs).][15]

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/strongips.txt`
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


## The CINS Score

### [The CI Army List][16]

#### IP Blacklist
>
* Website
 - `http://cinsscore.com/`
* Source
 - `http://cinsscore.com/list/ci-badguys.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - NCCST IP address can not access the link.


## CleanMX.de

### [Various Malware][17]

#### Events
>
* Website
 - `http://support.clean-mx.de/clean-mx/viruses.php`
* Source
 - `http://support.clean-mx.de/clean-mx/xmlviruses?response=alive&format=csv&domain=`
* Data
 - URL, Domain Name, IP Address, ASN, Country Code, Contact Mail, etc.
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### [Phishing][18]

#### Events
>
* Website
 - `http://support.clean-mx.com/clean-mx/phishing.php`
* Source
 - `http://support.clean-mx.de/clean-mx/xmlphishing?response=alive&format=csv&domain=`
* Data
 - URL, Domain Name, IP Address, ASN, Country Code, Contact Mail, etc.
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Team Cymru

### [Bogons IP List][19]

#### IP Blacklist
>
* Website
 - `https://www.team-cymru.org/bogon-reference.html`
* Source
 - `https://www.team-cymru.org/Services/Bogons/fullbogons-ipv4.txt`
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


## DShield: Internet Storm Center

### [AS Report][20]

#### IP Blacklist
>
* Website
 - `https://www.dshield.org/`
* Source
 - `https://www.dshield.org/asdetailsascii.html?as=4782`
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

### [Top 20 attacking class C][21]

#### IP Blacklist
>
* Website
 - `https://www.dshield.org/`
* Source
 - `https://www.dshield.org/block.txt`
* Data
 - Net Block
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### [Suspicious Domains][22]

#### Domain Blacklist
>
* Website
 - `https://www.dshield.org/suspicious_domains.html`
* Source
 - `https://www.dshield.org/feeds/suspiciousdomains_High.txt`
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


## Danger.rulez.sk

### [Brute Force Attack (Firewall)][23]

#### IP Blacklist
>
* Website
 - `http://danger.rulez.sk/`
* Source
 - `http://danger.rulez.sk/projects/bruteforceblocker/blist.php`
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


## Dragon Research Group

### [SSH Brute Force Attack][24]

#### IP Blacklist
>
* Website
 - `https://dragonresearchgroup.org/insight/`
* Source
 - `https://dragonresearchgroup.org/insight/sshpwauth.txt`
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

### [VNC Brute Force Attack][25]

#### IP Blacklist
>
* Website
 - `https://dragonresearchgroup.org/insight/`
* Source
 - `https://dragonresearchgroup.org/insight/vncprobe.txt`
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


## Security Research

### [Ponmocup Botnet][26]

#### Domain Blacklist
>
* Website
 - `http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt`
* Source
 - `http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt`
* Data
 - URL, Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Malwarebytes hpHosts

### [Miscellaneous][27]

#### Domain Blacklist
>
* Website
 - `https://www.hosts-file.net/`
* Source
 - `http://hosts-file.net/download/hosts.txt`
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


## Malc0de

### [Various Malware][28]

#### Domain Blacklist
>
* Website
 - `http://malc0de.com/bl/`
* Source
 - `http://malc0de.com/bl/BOOT`
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

#### IP Blacklist
>
* Website
 - `http://malc0de.com/bl/`
* Source
 - `https://malc0de.com/bl/IP_Blacklist.txt`
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


## Malware Domain List

### [Miscellaneous][29]

#### Domain Blacklist
>
* Website
 - `http://www.malwaredomainlist.com/`
* Source
 - `http://www.malwaredomainlist.com/updatescsv.php`
* Data
 - Domain Name
* Format
 - CSV
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Malware Domains

### [Miscellaneous][30]

#### Domain Blacklist
>
* Website
 - `http://www.malwaredomains.com/`
* Source
 - `http://mirror2.malwaredomains.com/files/domains.txt`
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


## Malware Group

### [Unknown][31]

#### Domain Blacklist
>
* Website
 - `http://www.malwaregroup.com/`
* Source
 - `http://www.malwaregroup.com/domains`
* Data
 - Domain Name
* Format
 - Not Available
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available

#### IP Blacklist
>
* Website
 - `http://www.malwaregroup.com/`
* Source
 - `http://www.malwaregroup.com/ipaddresses`
* Data
 - IP Address
* Format
 - Not Available
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available

### [Proxy][32]

#### IP Blacklist
>
* Website
 - `http://www.malwaregroup.com/`
* Source
 - `http://www.malwaregroup.com/proxies`
* Data
 - IP Address
* Format
 - Not Aavailable
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available


## OpenBL.org

### [Abuse Reporting and Blacklisting][33]

#### IP Blacklist
>
* Website
 - `https://www.openbl.org/`
* Source
 - `https://www.openbl.org/lists/date_all.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available


## OpenPhish

### [Phishing][34]

#### Domain Blacklist
>
* Website
 - `https://www.openphish.com/`
* Source
 - `https://www.openphish.com/feed.txt`
* Data
 - URL
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## Spamhaus

### [Don't Route Or Peer Lists][35]

#### IP Blacklist
>
* Website
 - `https://www.spamhaus.org/drop/`
* Source
 - `https://www.spamhaus.org/drop/drop.txt`
* Data
 - Net Block
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## Taichung C&C List

### [Miscellaneous][36]

#### IP Blacklist
>
* Website
 - `https://www.tc.edu.tw/net/netflow/lkout/recent/30`
* Source
 - `https://www.tc.edu.tw/net/netflow/lkout/recent/30`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## Turris Greylist

### [Scanning Attack][37]

#### IP Blacklist
>
* Website
 - `https://www.turris.cz/en/greylist`
* Source
 - `https://www.turris.cz/greylist-data/greylist-latest.csv`
* Data
 - IP Address
* Format
 - CSV
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## URLVir

### [Various Malware][38]

#### Domain Blacklist
>
* Website
 - `http://www.urlvir.com/`
* Source
 - `http://www.urlvir.com/export-hosts/`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available

#### IP Blacklist
>
* Website
 - `http://www.urlvir.com/`
* Source
 - `http://www.urlvir.com/export-ip-addresses/`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## VXVault

### [Various Malware][39]

#### Domain Blacklist
>
* Website
 - `http://vxvault.net/`
* Source
 - `http://vxvault.net/URL_List.php`
* Data
 - URL
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


Community or Closed Source Intelligence
=======================================


## Alien Vault OTX (Open Threat Exchange)

### [Miscellaneous][40]

#### Events
>
* Website
 - `https://otx.alienvault.com/`
* Source
 - `None`
* Data
 - URL, Domain Name, IP Address, etc.
* Format
 - Not Available
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No comment


## Autoshun shunlist

### [Miscellaneous][41]

#### IP Blacklist
>
* Website
 - `https://www.autoshun.org/`
* Source
 - `https://www.autoshun.org/download/?api_key=< API KEY >&format=csv`
* Data
 - IP Address
* Format
 - CSV
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - URL Changed


## Blueliv

### [Miscellaneous][42]

#### Events
>
* Website
 - `https://community.blueliv.com/`
* Source
 - `None`
* Data
 - Domain Name, IP Address, etc.
* Format
 - CSV
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - URL Changed


## Bitsight

### [Unknown][43]

#### Events
>
* Website
 - `https://www.bitsighttech.com/`
* Source
 - `http://alerts.bitsighttech.com:8080/stream?key=< api >`
* Data
 - Not Available
* Format
 - Not available
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - No API Key


## DGArchive

### [Various Malware][44]

#### Domain Blacklist
>
* Website
 - `https://dgarchive.caad.fkie.fraunhofer.de/site/`
* Source
 - `None`
* Data
 - Domain Name
* Format
 - JSON
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No comment


## Malware Patrol

### [Miscellaneous][45]

#### Domain Blacklist
>
* Website
 - `https://dgarchive.caad.fkie.fraunhofer.de/site/`
* Source
 - `https://lists.malwarepatrol.net/cgi/getfile?receipt=< API KEY >&product=8&list=dansguardian`
* Data
 - URL, Domain Name, IP Address
* Format
 - Text
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - Parsing Error


## Phistank

### [Phishing][46]

#### Domain Blacklist
>
* Website
 - `https://www.phishtank.com`
* Source
 - `https://data.phishtank.com/data/< API KEY >/online-valid.csv`
* Data
 - URL
* Format
 - CSV
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No comment


## n6stomp

### [Unknown][47]

#### Events
>
* Website
 - `http://n6.cert.pl/`
* Source
 - `None`
* Data
 - Not Available
* Format
 - Not available
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - No API Key


## Spamhaus CERT Insight Portal

### [Unknown][48]

#### Events
>
* Website
 - `https://www.spamhaus.org/`
* Source
 - `None`
* Data
 - IP Address
* Format
 - Not available
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - No API Key


[1]: ./Abuse.ch/Feodo_Botnet.md
[2]: ./Abuse.ch/Palevo_Worm.md
[3]: ./Abuse.ch/Zeus_Botnet.md
[4]: ./AlienVault/Miscellaneous.md
[5]: ./ArborNetworks/Distributed_SSH_Brute_Force_Attacks.md
[6]: ./Blocklist.de/Attacks_on_the_service_Apache.md
[7]: ./Blocklist.de/REG-Bots_IRC-Bots_or_BadBots_Spamming.md
[8]: ./Blocklist.de/Brute-Force_Website_Logins.md
[9]: ./Blocklist.de/Attacks_on_the_service_FTP.md
[10]: ./Blocklist.de/Attacks_on_the_service_IMAP_SASL_POP3.md
[11]: ./Blocklist.de/IRC_Botnet.md
[12]: ./Blocklist.de/Attacks_on_the_service_Mail_Postfix.md
[13]: ./Blocklist.de/Brute-Force_SIP_VOIP_or_Asterisk-Server_Logins_Attacks.md
[14]: ./Blocklist.de/Attacks_on_the_service_SSH.md
[15]: ./Blocklist.de/Strong_IPs.md
[16]: ./CINSscore/The_CI_Army_List.md
[17]: ./CleanMX.de/Various_Malware.md
[18]: ./CleanMX.de/Phishing.md
[19]: ./TeamCymru/Bogons_IP_List.md
[20]: ./DShield/AS_Report.md
[21]: ./DShield/Top_20_attacking_class_C.md
[22]: ./DShield/Suspicious_Domains.md
[23]: ./Danger.rulez.sk/Brute_Force_Attack_Firewall.md
[24]: ./DragonResearchGroup/SSH_Brute_Force_Attack.md
[25]: ./DragonResearchGroup/VNC_Brute_Force_Attack.md
[26]: ./SecurityResearch/Ponmocup_Botnet.md
[27]: ./MalwarebyteshpHosts/Miscellaneous.md
[28]: ./Malc0de/Various_Malware.md
[29]: ./Malware_Domain_List/Miscellaneous.md
[30]: ./Malware_Domains/Miscellaneous.md
[31]: ./Malware_Group/Unknown.md
[32]: ./Malware_Group/Proxy.md
[33]: ./OpenBL.org/Abuse_Reporting_and_Blacklisting.md
[34]: ./OpenPhish/Phishing.md
[35]: ./Spamhaus/Dont_Route_Or_Peer_Lists.md
[36]: ./TaichungC2List/Miscellaneous.md
[37]: ./TurrisGreylist/Scanning_Attack.md
[38]: ./URLVir/Various_Malware.md
[39]: ./VXVault/Various_Malware.md
[40]: ./AlienVaultOTX/Miscellaneous.md
[41]: ./Autoshunshunlist/Miscellaneous.md
[42]: ./Blueliv/Miscellaneous.md
[43]: ./Bitsight/Unknown.md
[44]: ./DGArchive/Various_Malware.md
[45]: ./MalwarePatrol/Miscellaneous.md
[46]: ./Phistank/Phishing.md
[47]: ./n6stomp/Unknown.md
[48]: ./SpamhausCERTInsightPortal/Unknown.md
