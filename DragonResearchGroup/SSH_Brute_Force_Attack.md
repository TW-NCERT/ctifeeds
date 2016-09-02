## Dragon Research Group

The Dragon Research Group (DRG) is a volunteer research organization dedicated
to further understanding of online criminality and to provide actionable
intelligence for the benefit of the entire Internet community.

### SSH Brute Force Attack

SSH Password Authentication Report

#### IP Address
>
* Website
 - `https://dragonresearchgroup.org/insight/`
* Source
 - `https://dragonresearchgroup.org/insight/sshpwauth.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Data didn't update, and stoped on 2016-05-18.

#### Sample Output of IntelMQ

```javascript
{
  "time": {
    "source": "2016-05-17T06:39:10+00:00",
    "observation": "2016-07-07T12:13:43+00:00"
  },
  "feed": {
    "accuracy": 100.0,
    "name": "Dragon Research Group",
    "url": "https://dragonresearchgroup.org/insight/sshpwauth.txt"
  },
  "source": {
    "ip": "185.130.5.56"
  },
  "classification": {
    "type": "brute-force"
  },
  "destination": {
    "port": 22
  },
  "raw": "TkEgICAgICAgICAgIHwgIE5BICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgfCAgICAgMTg1LjEzMC41LjU2ICB8ICAyMDE2LTA1LTE3IDA2OjM5OjEwICB8ICBzc2hwd2F1dGg=",
  "protocol": {
    "application": "ssh",
    "transport": "tcp"
  }
}
```
