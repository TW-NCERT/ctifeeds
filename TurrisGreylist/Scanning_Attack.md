## Turris Greylist

Project Turris is a service helping to protect its user's home network with the
help of a special router.

### Scanning Attack

 A list of addresses that have tried to obtain information about services on the
 Turris router or tried to gain access to them.

#### IP Address 
>
* Website
 - `https://www.turris.cz/en/greylist`
* Source
 - `https://www.turris.cz/greylist-data/greylist-latest.csv`
* Data
 - IP Address
* Format
 - CSV
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

##### Sample Output of IntelMQ

```javascript
{
  "classification":{
    "type":"scanner"
  },
  "time":{
    "observation":"2016-07-07T14:53:37+00:00"
  },
  "raw":"MS4xMS40NS41LEtSLG5ldGlzLDE4MzEz",
  "feed":{
    "url":"https://www.turris.cz/greylist-data/greylist-latest.csv",
    "name":"Turris Greylist",
    "accuracy":100.0
  },
  "event_description":{
    "text":"netis"
  },
  "source":{
    "ip":"1.11.45.5"
  }
}
```

There's not only IP information in https://www.turris.cz/greylist-data/greylist-latest.csv, but also more information like:

* Country
* Tags
* ASN

It looks like:

	Address,Country,Tags,ASN
	1.9.165.178,MY,"samba,torrent",4788
	1.23.82.242,IN,databases,45528
	1.25.224.180,CN,databases,4837
