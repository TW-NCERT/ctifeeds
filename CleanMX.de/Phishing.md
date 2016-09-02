## CleanMX.de

PhishWatch Watching adress changes of Phishing Url's

### Phishing

This database consists of Phishing URI, collected and verified since Oct 2006.
Some of them may be already closed, but are still recognized as fraud by firefox
and opera also offending domain names are honored by SURBL.

#### URL
>
* Website
 - `http://support.clean-mx.de/clean-mx/phishing.php`
* Source
 - `http://support.clean-mx.de/clean-mx/xmlphishing?response=alive&format=csv&domain=`
* Data
 - URL, Domain Name, IP Address, ASN, Country Code, Contact Mail, etc.
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Drop a mail to mailto:"abuse@clean-mx.de" get data

##### Sample Output of IntelMQ

```javascript
{
  "source": {
    "url": "http:\/\/1stbrowser.com\/landingdirect\/personalisation\/pt-BR?refid=2150&popup=1&aff_id=87&offer_id=805&intent=1&trafficsourceid=1&aff_sub=016282590036939875664&source=016282590",
    "abuse_contact": "abuse@cdnetworks.com",
    "geolocation": {
      "cc": "GB"
    },
    "ip": "151.249.94.68",
    "fqdn": "1stbrowser.com"
  },
  "time": {
    "source": "2016-07-07T10:13:37+00:00",
    "observation": "2016-07-07T10:49:10+00:00"
  },
  "classification": {
    "type": "phishing"
  },
  "raw": "bGFzdHRpbWUsbGluZSxuczIsdXJsLGlwLGlkLGRkZXNjcixzb3VyY2UsZmlyc3R0aW1lLGluZXRudW0sbnM1LHBoaXNodGFuayxyZWNlbnQsbnMzLGRvbWFpbixuczEsbnM0LHJldmlldyxuZXRuYW1lLGVtYWlsLHZpcnVzbmFtZSxyZXNwb25zZSxjb3VudHJ5",
  "feed": {
    "accuracy": 100,
    "url": "http:\/\/support.clean-mx.de\/clean-mx\/xmlphishing?response=alive&format=csv&domain=",
    "name": "CleanMX"
  }
}
```