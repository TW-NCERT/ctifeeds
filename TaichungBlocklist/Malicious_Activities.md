## Taichung Blacklist

The Education Bureau of Taichung City Hall

### Malicious Activities

A public blocklist of IP addresses suspected in malicious activities on-line.

#### IP Address
>
* Website
 - `https://www.tc.edu.tw/net/netflow/lkout/recent/30`
* Source
 - `https://www.tc.edu.tw/net/netflow/lkout/recent/30`
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
  "time":{
    "source":"2016-05-18T01:33:43+00:00",
    "observation":"2016-07-07T14:46:02+00:00"
  },
  "raw":"PHRkPjE8L3RkPjx0ZD48aW1nIHNyYz0iL2ltYWdlcy9mbGFncy9qcC5naWYiIGFsdD0iIj48c3BhbiBzdHlsZT0iY29sb3I6IGJsYWNrOyI+MTA2LjE4NC4yLjI5PC9zcGFuPjwvdGQ+PHRkPlNTSCBBdHRhY2s8L3RkPgogICAgICAgIDx0ZD7miYvli5XoqK3lrpo8L3RkPjx0ZD4yMDE2LTA1LTE4IDA5OjMzOjQzPC90ZD48dGQ+NTAuNTc8L3RkPgogICAgICAgIDx0ZCBzdHlsZT0iY29sb3I6cmVkOyI+5bCB6Y6WPC90ZD48L3RyPiAgICAgICAg",
  "event_description":{
    "text":"SSH Attack"
  },
  "classification":{
    "type":"unknown"
  },
  "source":{
    "ip":"106.184.2.29"
  },
  "feed":{
    "accuracy":100.0,
    "name":"Taichung",
    "url":"https://www.tc.edu.tw/net/netflow/lkout/recent/30"
  }
}
```

There's only IP information in https://www.openbl.org/lists/date_all.txt
It looks like:

	序	限制IP	限制型態	流量	起限時間	距日	管理
	1	106.184.2.29	SSH Attack	手動設定	2016-05-18 09:33:43	104.27	封鎖
	2	91.201.236.155	SSH Attack	手動設定	2016-05-18 09:33:04	104.27	封鎖
	3	91.201.236.158	SSH Attack	手動設定	2016-05-18 09:32:46	104.27	封鎖