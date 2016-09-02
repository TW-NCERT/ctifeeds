## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Brute-Force SIP-, VOIP- or Asterisk-Server Logins Attacks

All IP addresses that tried to login in a SIP-, VOIP- or Asterisk-Server and are
inclueded in the IPs-List from http://www.infiltrated.net/ (Twitter).

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

##### Sample Output of IntelMQ

```javascript
{
  "time": {
    "observation": "2016-07-07T09:30:40+00:00"
  },
  "feed": {
    "url": "https:\/\/lists.blocklist.de\/lists\/sip.txt",
    "name": "BlockList.de",
    "accuracy": 100
  },
  "raw": "MTA5LjIzNC4zNy41OA==",
  "event_description": {
    "text": "IP reported as having run attacks on the service SIP, VOIP, Asterisk"
  },
  "source": {
    "ip": "109.234.37.58"
  },
  "protocol": {
    "application": "sip"
  },
  "classification": {
    "type": "ids alert"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/sip.txt
It looks like:

	103.59.129.142
	104.245.100.99
	109.228.102.144