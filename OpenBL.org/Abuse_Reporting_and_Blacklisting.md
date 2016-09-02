## OpenBL.org

The OpenBL.org project (formerly known as the SSH blacklist) is about detecting,
logging and reporting various types of internet abuse.

### Abuse Reporting and Blacklisting

Currently our hosts monitor ports 21 (FTP), 22 (SSH), 23 (TELNET), 25 (SMTP),
110(POP3), 143 (IMAP), 587 (Submission), 993 (IMAPS) and 995 (POP3S) for
bruteforce login attacks as well as scans on ports 80 (HTTP) and 443 (HTTPS) for
vulnerable installations of phpMyAdmin and other web applications.

#### IP Address
>
* Website
 - `https://www.openbl.org/`
* Source
 - `https://www.openbl.org/lists/date_all.txt`
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
  "classification": {
    "type": "blacklist"
  },
  "source": {
    "ip": "121.18.238.29"
  },
  "raw": "MTIxLjE4LjIzOC4yOQkxNDY3OTAyMjI1",
  "feed": {
    "name": "OpenBL",
    "url": "https://www.openbl.org/lists/date_all.txt",
    "accuracy": 100.0
  },
  "time": {
    "observation": "2016-07-07T14:01:47+00:00",
    "source": "2016-07-07T14:37:05+00:00"
  }
}
```

----

There's only IP information in https://www.openbl.org/lists/date_all.txt
It looks like:

	# openbl.org/lists/date_all.txt
	# Tue Aug 30 07:52:27 2016 UTC
	#
	# source ip	date
	91.224.160.184	1472542163
	77.243.183.61	1472542093
	210.30.128.25	1472542086