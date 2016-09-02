## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### Brute-Force Website Logins

All IPs which attacks Joomlas, Wordpress and other Web-Logins with Brute-Force
Logins.

#### IP Address
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

##### Sample Output of IntelMQ

```javascript
{
  "time": {
    "observation": "2016-07-07T09:00:34+00:00"
  },
  "classification": {
    "type": "brute-force"
  },
  "feed": {
    "url": "https:\/\/lists.blocklist.de\/lists\/bruteforcelogin.txt",
    "name": "BlockList.de",
    "accuracy": 100
  },
  "raw": "MS41NC4yMTIuMjM1",
  "event_description": {
    "text": "IP reported as having run attacks on Joomlas, Wordpress and other Web-Logins with Brute-Force Logins"
  },
  "source": {
    "ip": "1.54.212.235"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/bruteforcelogin.txt
It looks like:

	103.17.48.3
	103.18.4.235
	103.25.203.71