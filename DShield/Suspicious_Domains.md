## DShield: Internet Storm Center

The ISC provides a free analysis and warning service to thousands of Internet
users and organizations, and is actively working with Internet Service Providers
to fight back against the most malicious attackers.

### Suspicious Domains

There are many suspicious domains on the internet. In an effort to identify
them, as well as false positives, we have assembled weighted lists based on
tracking and malware lists from different sources. ISC is collecting and
categorizing various lists associated with a certain level of sensitivity.

#### Domain Name
>
* Website
 - `https://www.dshield.org/suspicious_domains.html`
* Source
 - `https://www.dshield.org/feeds/suspiciousdomains_High.txt`
* Data
 - Domain Name
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
  "feed": {
    "name": "DShield",
    "url": "https://www.dshield.org/feeds/suspiciousdomains_High.txt",
    "accuracy": 100.0
  },
  "classification": {
    "type": "malware"
  },
  "source": {
    "fqdn": "000007.ru"
  },
  "raw": "MDAwMDA3LnJ1CQ==",
  "time": {
    "source": "2016-07-07T04:10:24+00:00",
    "observation": "2016-07-07T12:06:13+00:00"
  }
}
```

----
There's only Domain information in  in https://www.dshield.org/feeds/suspiciousdomains_High.txt. It looks like:

    #
    #   DShield.org Suspicious Domain List
    #    (c) 2016 DShield.org
    #   some rights reserved. Details http://creativecommons.org/licenses/by-nc-sa/2.5/
    #   use on your own risk. No warranties implied.
    #   primary URL: http://www.dshield.org/feeds/suspiciousdomains_High.txt
    #
    #   comments: info@dshield.org
    #    updated: Mon Aug 29 04:09:47 2016 UTC
    #   
    #    This list consists of High Level Sensitivity website URLs
    #     Columns (tab delimited):
    #
    #      (1) site
    #
    Site
    pmenboeqhyrpvomq.azwsxe.top
    rbwubtpsyokqn.info
    swfqg.in
    fnjyygovdjyemga.xyz
    #
    # STATISTICS
    #
    # Total In Database: 37981
    # Total In Report:   135
    # Percent of Total:  0.36 %
    #
    # END
    #
    #  finished list generation: Mon Aug 29 04:09:47 2016 UTC
