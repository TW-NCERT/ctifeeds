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

There's only IP information in https://www.spamhaus.org/drop/drop.txt
It looks like:

	; Spamhaus DROP List 2016/08/30 - (c) 2016 The Spamhaus Project
	; https://www.spamhaus.org/drop/drop.txt
	; Last-Modified: Tue, 30 Aug 2016 05:17:00 GMT
	; Expires: Tue, 30 Aug 2016 09:03:35 GMT
	1.4.0.0/17 ; SBL256893
	1.10.16.0/20 ; SBL256894
	1.32.128.0/18 ; SBL286275