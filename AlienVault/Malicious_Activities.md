## Alien Vault

AlienVault is a developer of commercial and open source solutions to manage
cyber attacks, including the Open Threat Exchange, the world's largest
crowd-sourced computer-security platform with more than 26,000 participants
in 140 countries that share more than one million potential threats daily.

### Malicious Activities

Alienvault IP Reputation Database

#### IP Address
>
* Website
 - `https://www.alienvault.com/`
* Source
 - `https://reputation.alienvault.com/reputation.data`
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
  null
}
```

----

There's not only IP information in https://reputation.alienvault.com/reputation.data
It looks like:

	46.4.123.15#4#2#Malicious Host#DE##51.0,9.0#3
	222.136.71.19#3#2#Scanning Host#CN#Zhengzhou#34.6836013794,113.532501221#11
	116.117.253.243#3#2#Scanning Host#CN#Baotou#40.6521987915,109.82219696#11

There's more information in https://reputation.alienvault.com
* [reputation.generic] [1]
* [reputation.snort] [2]
* [reputation.iptables] [3]
* [reputation.squid] [4]
* [reputation.unix] [5]

[1]: https://reputation.alienvault.com/reputation.generic
[2]: https://reputation.alienvault.com/reputation.snort
[3]: https://reputation.alienvault.com/reputation.iptables
[4]: https://reputation.alienvault.com/reputation.squid
[5]: https://reputation.alienvault.com/reputation.unix