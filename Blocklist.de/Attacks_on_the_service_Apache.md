## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Attacks on the service Apache

All IP addresses which have been reported within the last 48 hours as having run
attacks on the service Apache, Apache-DDOS, RFI-Attacks.

#### IP Address
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

##### Sample Output of IntelMQ

```javascript
{
  "source": {
    "ip": "1.34.139.38"
  },
  "time": {
    "observation": "2016-07-07T08:46:43+00:00"
  },
  "event_description": {
    "text": "IP reported as having run attacks on the service Apache, Apache-DDoS, RFI-Attacks"
  },
  "classification": {
    "type": "ids alert"
  },
  "raw": "MS4zNC4xMzkuMzg=",
  "feed": {
    "name": "BlockList.de",
    "accuracy": 100,
    "url": "https:\/\/lists.blocklist.de\/lists\/apache.txt"
  },
  "protocol": {
    "application": "http"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/apache.txt
It looks like:

	1.180.52.83
	1.189.169.145
	1.212.90.147
