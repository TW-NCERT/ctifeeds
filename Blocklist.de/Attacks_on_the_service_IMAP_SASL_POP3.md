## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Attacks on the service IMAP, SASL, POP3

All IP addresses which have been reported within the last 48 hours for attacks
on the Service imap, sasl, pop3.....

#### IP Address
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

##### Sample Output of IntelMQ

```javascript
{
  "event_description": {
    "text": "IP reported as having run attacks on the service IMAP, SASL, POP3"
  },
  "raw": "MS4xMzIuOTYuMjI=",
  "feed": {
    "name": "BlockList.de",
    "url": "https:\/\/lists.blocklist.de\/lists\/imap.txt",
    "accuracy": 100
  },
  "protocol": {
    "application": "imap"
  },
  "classification": {
    "type": "ids alert"
  },
  "source": {
    "ip": "1.132.96.22"
  },
  "time": {
    "observation": "2016-07-07T09:19:12+00:00"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/imap.txt
It looks like:

	1.129.96.138
	1.129.96.247
	1.144.97.126