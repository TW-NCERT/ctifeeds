## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Attacks on the service Mail, Postfix

All IP addresses which have been reported within the last 48 hours as having run
attacks on the service Mail, Postfix.

#### IP Address
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

##### Sample Output of IntelMQ

```javascript
{
  "classification": {
    "type": "ids alert"
  },
  "event_description": {
    "text": "IP reported as having run attacks on the service Mail, Postfix"
  },
  "time": {
    "observation": "2016-07-07T09:23:25+00:00"
  },
  "raw": "MS4xMzIuOTYuMjI=",
  "source": {
    "ip": "1.132.96.22"
  },
  "feed": {
    "name": "BlockList.de",
    "accuracy": 100,
    "url": "https:\/\/lists.blocklist.de\/lists\/mail.txt"
  },
  "protocol": {
    "application": "smtp"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/mail.txt
It looks like:

	1.126.40.9
	1.129.28.145
	1.129.28.246