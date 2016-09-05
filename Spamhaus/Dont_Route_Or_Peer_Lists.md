## Spamhaus

The Spamhaus DROP (Don't Route Or Peer) lists are advisory "drop all traffic"
lists, consisting of netblocks that are "hijacked" or leased by professional
spam or cyber-crime operations (used for dissemination of malware, trojan
downloaders, botnet controllers).

### Don't Route Or Peer Lists

DROP will only include netblocks allocated directly by an established Regional
Internet Registry (RIR) or National Internet Registry (NIR) such as ARIN, RIPE,
AFRINIC, APNIC, LACNIC or KRNIC or direct RIR allocations.

#### IP Address
>
* Website
 - `https://www.spamhaus.org/drop/`
* Source
 - `https://www.spamhaus.org/drop/drop.txt`
* Data
 - Net Block
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
  "event_description":{
    "text":"has malicious code redirecting to malicious host"
  },
  "time":{
    "observation":"2016-07-07T12:18:38+00:00",
    "source":"2016-07-07T07:44:04+00:00"
  },
  "raw":"LyAyODU2MC5wb2xpdGNhbG5ld3MuY29tIGh0dHA6Ly8yODU2MC5wb2xpdGNhbG5ld3MuY29tL3VybCBtLmtmYy5mcg==",
  "feed":{
    "url":"http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt",
    "accuracy":100.0,
    "name":"DynDNS ponmocup Domains"
  },
  "source":{
    "url":"http://28560.politcalnews.com/url",
    "fqdn":"28560.politcalnews.com"
  },
  "destination":{
    "fqdn":"m.kfc.fr"
  },
  "classification":{
    "type":"malware"
  }
}
```

There's only IP information in https://www.spamhaus.org/drop/drop.txt
It looks like:

	; Spamhaus DROP List 2016/08/30 - (c) 2016 The Spamhaus Project
	; https://www.spamhaus.org/drop/drop.txt
	; Last-Modified: Tue, 30 Aug 2016 05:17:00 GMT
	; Expires: Tue, 30 Aug 2016 09:03:35 GMT
	1.4.0.0/17 ; SBL256893
	1.10.16.0/20 ; SBL256894
	1.32.128.0/18 ; SBL286275