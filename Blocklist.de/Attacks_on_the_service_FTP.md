## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Attacks on the service FTP

All IP addresses which have been reported within the last 48 hours for attacks
on the Service FTP.

#### IP Address
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

##### Sample Output of IntelMQ

```javascript
{
  "protocol": {
    "application": "ftp"
  },
  "event_description": {
    "text": "IP reported as having run attacks on the service FTP"
  },
  "time": {
    "observation": "2016-07-07T09:02:44+00:00"
  },
  "raw": "MS4xODAuMjQzLjEzMQ==",
  "source": {
    "ip": "1.180.243.131"
  },
  "classification": {
    "type": "ids alert"
  },
  "feed": {
    "accuracy": 100,
    "name": "BlockList.de",
    "url": "https:\/\/lists.blocklist.de\/lists\/ftp.txt"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/ftp.txt
It looks like:

	101.200.204.27
	101.200.208.208
	101.200.87.177