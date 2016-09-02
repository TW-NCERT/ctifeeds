## Dragon Research Group

The Dragon Research Group (DRG) is a volunteer research organization dedicated
to further understanding of online criminality and to provide actionable
intelligence for the benefit of the entire Internet community.

### VNC Brute Force Attack

VNC Probe Report

#### IP Address
>
* Website
 - `https://dragonresearchgroup.org/insight/`
* Source
 - `https://dragonresearchgroup.org/insight/vncprobe.txt`
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
  "feed": {
    "url": "https://dragonresearchgroup.org/insight/vncprobe.txt",
    "accuracy": 100.0,
    "name": "Dragon Research Group"
  },
  "time": {
    "source": "2016-05-17T05:09:34+00:00",
    "observation": "2016-07-07T12:50:59+00:00"
  },
  "protocol": {
    "transport": "tcp",
    "application": "vnc"
  },
  "source": {
    "as_name": "HINET Data Communication Busin",
    "ip": "1.170.51.152",
    "asn": 3462
  },
  "raw": "MzQ2MiAgICAgICAgIHwgIEhJTkVUIERhdGEgQ29tbXVuaWNhdGlvbiBCdXNpbiAgfCAgICAgMS4xNzAuNTEuMTUyICB8ICAyMDE2LTA1LTE3IDA1OjA5OjM0ICB8ICB2bmNwcm9iZQ==",
  "classification": {
    "type": "brute-force"
  }
}
```
