## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Strong IPs

All IPs which are older then 2 month and have more then 5.000 attacks.

#### IP Address
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

##### Sample Output of IntelMQ

```javascript
{
  "time": {
    "observation": "2016-07-07T09:34:52+00:00"
  },
  "event_description": {
    "text": "IP reported as having run attacks in last 2 months"
  },
  "classification": {
    "type": "blacklist"
  },
  "source": {
    "ip": "188.143.232.24"
  },
  "raw": "MTg4LjE0My4yMzIuMjQ=",
  "feed": {
    "name": "BlockList.de",
    "accuracy": 100,
    "url": "https:\/\/lists.blocklist.de\/lists\/strongips.txt"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/strongips.txt
It looks like:

	112.85.218.11
	116.31.116.25
	116.31.116.34