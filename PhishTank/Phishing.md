## PhishTank

PhishTank is a free community site where anyone can submit, verify, track and
share phishing data.

### Phishing

Phishing is a fraudulent attempt, usually made through email, to steal your
personal information. The best way to protect yourself from phishing is to learn
how to recognize a phish.

#### URL
>
* Website
 - `https://www.phishtank.com`
* Source
 - `https://data.phishtank.com/data/< API KEY >/online-valid.csv`
* Data
 - URL
* Format
 - CSV
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No API Key

##### Sample Output of IntelMQ

```javascript
{
  "source": {
    "url": "http://ow.ly/YDN26"
  },
  "time": {
    "observation": "2016-07-07T14:15:22+00:00",
    "source": "2016-07-07T11:26:05+00:00"
  },
  "event_description": {
    "url": "http://www.phishtank.com/phish_detail.php?phish_id=4278837",
    "target": "DHL"
  },
  "feed": {
    "url": "https://data.phishtank.com/data/00625bb72461632c0e7d494baba9b3524e439c672c4deab6f09a617b2fa887f8/online-valid.csv",
    "name": "Phishtank",
    "accuracy": 100.0
  },
  "classification": {
    "type": "phishing"
  },
  "raw": "NDI3ODgzNyxodHRwOi8vb3cubHkvWUROMjYsaHR0cDovL3d3dy5waGlzaHRhbmsuY29tL3BoaXNoX2RldGFpbC5waHA/cGhpc2hfaWQ9NDI3ODgzNywyMDE2LTA3LTA3VDExOjI2OjA1KzAwOjAwLHllcywyMDE2LTA3LTA3VDEzOjMyOjU1KzAwOjAwLHllcyxESEw="
}
```
