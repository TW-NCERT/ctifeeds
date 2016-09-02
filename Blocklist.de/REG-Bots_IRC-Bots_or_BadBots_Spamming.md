## Blocklist.de

www.blocklist.de is a free and voluntary service provided by a
Fraud/Abuse-specialist, whose servers are often attacked via SSH-, Mail-Login-,
FTP-, Webserver- and other services.
The mission is to report any and all attacks to the respective abuse departments
of the infected PCs/servers, to ensure that the responsible provider can inform
their customer about the infection and disable the attacker.

### REG-Bots, IRC-Bots or BadBots (Spamming)

ll IP addresses which have been reported within the last 48 hours as having run
attacks attacks on the RFI-Attacks, REG-Bots, IRC-Bots or BadBots (BadBots = he
has posted a Spam-Comment on a open Forum or Wiki).

#### IP Address
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

##### Sample Output of IntelMQ

```javascript
{
  "event_description": {
    "text": "IP reported as having spammed on IRC, open forums, wikis or registration forms."
  },
  "classification": {
    "type": "spam"
  },
  "source": {
    "ip": "1.161.142.231"
  },
  "raw": "MS4xNjEuMTQyLjIzMQ==",
  "feed": {
    "accuracy": 100,
    "name": "BlockList.de",
    "url": "https:\/\/lists.blocklist.de\/lists\/bots.txt"
  },
  "time": {
    "observation": "2016-07-07T08:58:19+00:00"
  }
}
```

----

There's only IP information in https://lists.blocklist.de/lists/bots.txt
It looks like:

	1.161.154.222
	1.179.183.27
	1.28.135.97