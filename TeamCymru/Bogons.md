## Team Cymru

Team Cymru Research NFP is an Illinois non-profit and a US Federal 501(c)3
organization. 

### The Bogon Reference

A bogon prefix is a route that should never appear in the Internet routing
table. A packet routed over the public Internet (not including over VPNs or
other tunnels) should never have a source address in a bogon range. These are
commonly found as the source addresses of DDoS attacks.

#### IP Address
>
* Website
 - `https://www.team-cymru.org/bogon-reference.html`
* Source
 - `https://www.team-cymru.org/Services/Bogons/fullbogons-ipv4.txt`
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
  "feed":{
    "accuracy":100.0,
    "url":"https://www.team-cymru.org/Services/Bogons/fullbogons-ipv4.txt",
    "name":"Cymru"
  },
  "classification":{
    "type":"blacklist"
  },
  "source":{
    "network":"0.0.0.0/8"
  },
  "time":{
    "observation":"2016-07-07T11:40:52+00:00",
    "source":"2016-07-07T08:50:01+00:00"
  },
  "raw":"MC4wLjAuMC84"
}
```

There's only IP information in https://www.team-cymru.org/Services/Bogons/fullbogons-ipv4.txt
It looks like:

	# last updated 1472532602 (Tue Aug 30 04:50:02 2016 GMT)
	0.0.0.0/8
	2.56.0.0/14
	5.8.248.0/21
