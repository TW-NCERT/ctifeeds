## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Attacks on the service SSH

All IP addresses which have been reported within the last 48 hours as having run
attacks on the service SSH.

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

##### Sample Output of IntelMQ

```javascript
{
  "source": {
    "ip": "1.235.197.132"
  },
  "feed": {
    "url": "https:\/\/lists.blocklist.de\/lists\/ssh.txt",
    "name": "BlockList.de",
    "accuracy": 100
  },
  "event_description": {
    "text": "IP reported as having run attacks on the service SSH"
  },
  "time": {
    "observation": "2016-07-07T09:32:19+00:00"
  },
  "raw": "MS4yMzUuMTk3LjEzMg==",
  "classification": {
    "type": "ids alert"
  },
  "protocol": {
    "application": "ssh"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/ssh.txt
It looks like:

	1.119.3.74
	1.163.186.117
	1.52.96.45