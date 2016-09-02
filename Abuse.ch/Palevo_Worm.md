## Abuse.ch

A swiss guy fighting Cybercrime.

### Palevo Worm

Palevo is a worm that spreads using instant messaging, P2P networks and
removable drives (like USB sticks). It is being sold in underground forums like
ZeuS. The worm (also known as Rimecud, Butterfly bot and Pilleuz) made big press
in 2010. For more information about Palevo you can take a look at the Palevo
readme [file][1].

[1]: https://palevotracker.abuse.ch/downloads/palevo_v130_readme.txt

#### Domain Name
>
* Website
 - `https://palevotracker.abuse.ch/`
* Source
 - `https://palevotracker.abuse.ch/blocklists.php?download=domainblocklist`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Palevo Tracker has been discontinued.

##### Sample Output of IntelMQ

```javascript
{
  "raw": "YXJ0YS5yb21haWwzYXJuZXN0LmluZm8=",
  "classification": {
    "type": "c&c"
  },
  "source": {
    "fqdn": "arta.romail3arnest.info"
  },
  "time": {
    "observation": "2016-07-07T08:09:47+00:00"
  },
  "feed": {
    "url": "https:\/\/palevotracker.abuse.ch\/blocklists.php?download=domainblocklist",
    "name": "Abuse.ch",
    "accuracy": 100
  },
  "malware": {
    "name": "palevo"
  }
}

```

#### IP Address
>
* Website
 - `https://palevotracker.abuse.ch/`
* Source
 - `https://palevotracker.abuse.ch/blocklists.php?download=ipblocklist`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Palevo Tracker has been discontinued.

##### Sample Output of IntelMQ

```javascript
{
  "malware": {
    "name": "palevo"
  },
  "source": {
    "ip": "103.51.144.193"
  },
  "time": {
    "observation": "2016-07-07T08:11:44+00:00"
  },
  "raw": "MTAzLjUxLjE0NC4xOTM=",
  "classification": {
    "type": "c&c"
  },
  "feed": {
    "accuracy": 100,
    "url": "https:\/\/palevotracker.abuse.ch\/blocklists.php?download=ipblocklist",
    "name": "Abuse.ch"
  }
}
```

----

This project is not continued. We plan to remove this intelligence feed in the
future.
