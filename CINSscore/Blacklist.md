## The CINS Score

CINS is an IP reputation database that provides an accurate and timely score for
any IP address in the world.

### The CI Army List

CI Army is a way for our company to give back to the community by sharing
valuable threat intelligence harvested from our CINS system. The CI Army list is
a subset of the CINS Active Threat Intelligence ruleset, and consists of IP
addresses that meet two basic criteria: 1) The IP's recent Rogue Packet score
factor is very poor, and 2) The InfoSec community has not yet identified the IP
as malicious.

#### IP Address
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
 - No comment

##### Sample Output of IntelMQ

```javascript
{
  "source": {
    "ip": "1.63.153.99"
  },
  "time": {
    "observation": "2016-07-12T04:25:31+00:00"
  },
  "feed": {
    "accuracy": 100,
    "url": "http:\/\/cinsscore.com\/list\/ci-badguys.txt",
    "name": "CI Army"
  },
  "raw": "MS42My4xNTMuOTk=",
  "classification": {
    "type": "blacklist"
  }
}
```

----

There's only IP information in http://cinsscore.com/list/ci-badguys.txt
It looks like:

	1.52.183.130
	1.160.43.42
	1.162.168.77
