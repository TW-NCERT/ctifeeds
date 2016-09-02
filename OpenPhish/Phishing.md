## OpenPhish

OpenPhish launched in June 2014 as a result of a three-year research project on
phishing detection. The research yielded a set of autonomous algorithms for
detecting zero-day phishing sites. These algorithms form a self-contained kernel
that can tell whether a given URL is a phish or not. Essentially, OpenPhish is
the algorithmic kernel complemented with data extraction and analysis
functionalities for generating various feeds.

### Phishing

OpenPhish uses proprietary Artificial Intelligence algorithms to automatically
identify zero-day phishing sites and provide comprehensive, actionable,
real-time threat intelligence.

#### URL
>
* Website
 - `https://www.openphish.com/`
* Source
 - `https://www.openphish.com/feed.txt`
* Data
 - URL
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

#### Sample Output of IntelMQ

```javascript
{
  "time": {
    "observation": "2016-07-07T14:06:16+00:00"
  },
  "classification": {
    "type": "phishing"
  },
  "source": {
    "url": "http://2ztc3.sunucubilisim.net/cartasi/"
  },
  "raw": "aHR0cDovLzJ6dGMzLnN1bnVjdWJpbGlzaW0ubmV0L2NhcnRhc2kv",
  "feed": {
    "name": "OpenPhish",
    "accuracy": 100.0,
    "url": "https://www.openphish.com/feed.txt"
  }
}
```

----

There's only Url information in  in https://www.openphish.com/feed.txt.
It looks like:

    http://www.boushehr-ems.ir/apple/clients/
    http://www.boushehr-ems.ir/apple/clients/initiate.php
    http://www.maxmunus.com/images/demo/slider/alibaba/
    http://www.hermes-cargo.com/Docssecured/
    http://www.japcolor.com.ar/login.jsp.htm
    http://www.senaranews.com/libraries/simplepie/idn/done/auth/view/share/
    http://www.pomaranczowapomoc.pl/xmlpr/db/box/
    http://nlsmail.nottslawsoc.org/ap/servic/home/service/costumer/information/check/af09d63c1874c89d929de3a4b98123fe/index/web/a2d01ec0e86accddfd5277a9f87cc4bd/information.php
    http://nlsmail.nottslawsoc.org/ap/servic/home/service/costumer/information/check/af09d63c1874c89d929de3a4b98123fe/index/web/a2d01ec0e86accddfd5277a9f87cc4bd/confirmed.php

But there's more information in https://www.openphish.com/:

* Targeted Brand    