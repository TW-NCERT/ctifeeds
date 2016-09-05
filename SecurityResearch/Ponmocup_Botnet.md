## Security Research

Security Research is run by a security researcher.

### Ponmocup Botnet

This list contains ponmocup malware redirection domains and infected
web-servers.

#### Domain Name
>
* Website
 - `http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt`
* Source
 - `http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt`
* Data
 - URL, Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Website not found.

##### Sample Output of IntelMQ

```javascript
{
  "time":{
    "observation":"2016-07-07T12:48:53+00:00"
  },
  "source":{
    "fqdn":"-sso.anbtr.com"
  },
  "raw":"MTI3LjAuMC4xCS1zc28uYW5idHIuY29t",
  "classification":{
    "type":"blacklist"
  },
  "feed":{
    "accuracy":100.0,
    "url":"http://hosts-file.net/download/hosts.txt",
    "name":"HpHosts"
  }
}
```

There's only Url information in  in http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt. It looks like:

    # 
    # this list of ponmocup malware redirection domains and infected web-servers is maintained by 
    # email:   toms.security.stuff -at- gmail.com
    # twitter: @c_APT_ure
    # blog:    http://c-apt-ure.blogspot.com/
    #
    # full log file:
    # http://security-research.dyndns.org/pub/botnet/ponmocup/ponmocup-finder/ponmocup-infected-domains-latest.txt
    #
    # format:
    # ponmocup-malware-IP ponmocup-malware-domain ponmocup-malware-URI-path ponmocup-htaccess-infected-domain
    # 
    # last updated: Mon Aug 29 00:43:24 PDT 2016
    #
    / 41018.pballgames.com http://41018.pballgames.com/url www.hummel-print.biz
    / 52910.clickbanksite.org http://52910.clickbanksite.org/url infobunda.com
    / 53604.azdiscus.com http://53604.azdiscus.com/url www.rdm.hr
    / 59341.p-balls.com http://59341.p-balls.com/url meteomaastricht.nl
