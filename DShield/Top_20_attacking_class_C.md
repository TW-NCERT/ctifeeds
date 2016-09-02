## DShield: Internet Storm Center

The ISC provides a free analysis and warning service to thousands of Internet
users and organizations, and is actively working with Internet Service Providers
to fight back against the most malicious attackers.

### Top 20 attacking class C

This list summarizes the top 20 attacking class C (/24) subnets over the last
three days. The number of 'attacks' indicates the number of targets reporting
scans from this subnet.

#### IP Address
>
* Website
 - `https://www.dshield.org/`
* Source
 - `https://www.dshield.org/block.txt`
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

#### Sample Output of IntelMQ

```javascript
{
  "feed": {
    "url": "https://www.dshield.org/block.txt",
    "accuracy": 100.0,
    "name": "DShield"
  },
  "extra": "{\"attacks\": 3049, \"network_name\": \"IUnet S.p.A.\"}",
  "time": {
    "source": "2016-07-07T12:38:15+00:00",
    "observation": "2016-07-07T12:04:18+00:00"
  },
  "source": {
    "abuse_contact": "l.cerbai@iunet.it",
    "geolocation": {
      "cc": "IT"
    },
    "network": "164.132.54.0/24"
  },
  "raw": "MTY0LjEzMi41NC4wCTE2NC4xMzIuNTQuMjU1CTI0CTMwNDkJSVVuZXQgUy5wLkEuCUlUCWwuY2VyYmFpQGl1bmV0Lml0",
  "classification": {
    "type": "blacklist"
  }
}
```

---

There's not only IP information in https://www.dshield.org/block.txt, but also more information like:

* Number of targets scanned
* Name of Network
* Country
* Contact email address

It looks like:

	#   DShield.org Recommended Block List 
	#    (c) 2007 DShield.org
	#   some rights reserved. Details http://creativecommons.org/licenses/by-nc-sa/2.5/
	#   use on your own risk. No warranties implied.
	#   primary URL: http://feeds.dshield.org/block.txt
	#     PGP Sign.: http://feeds.dshield.org/block.txt.asc
	#
	#   comments: info@dshield.org
	#    updated: Tue Aug 30 07:11:21 2016 UTC
	#   
	#    This list summarizes the top 20 attacking class C (/24) subnets
	#   over the last three days. The number of 'attacks' indicates the 
	#   number of targets reporting scans from this subnet.
	#
	#
	#    Columns (tab delimited):
	#
	#    (1) start of netblock  
	#    (2) end of netblock
	#    (3) subnet (/24 for class C)
	#    (4) number of targets scanned
	#    (5) name of Network 
	#    (6) Country
	#    (7) contact email address
	#
	#    If a range is assigned to multiple users, the first one is listed. 
	#     
	Start	End	Netblock	Attacks	Name	Country	email
	124.232.156.0	124.232.156.255	24	6286	CHINANET-BACKBONE No.31,Jin-rong Street	CN	lzl@public.yc.nx.cn
	209.126.136.0	209.126.136.255	24	2769	California Regional Internet, Inc.	US	abuse@cari.net
	116.31.116.0	116.31.116.255	24	993	CHINANET-BACKBONE No.31,Jin-rong Street	CN	bad userid (abuse_gdnoc)bad userid (abuse_gdnoc)bad userid (abuse_gdnoc)IPMASTER is not for spam complaint,please send spam complaint to abuse_gdnoc@189.cn
	# END
	#
	#  finished list generation: Tue Aug 30 07:11:22 2016 UTC