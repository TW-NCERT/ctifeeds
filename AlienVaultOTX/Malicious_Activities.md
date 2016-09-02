## Alien Vault OTX (Open Threat Exchange)

AlienVault OTX provides open access to a global community of threat researchers
and security professionals.

### Malicious Activities

At the heart of Open Threat Exchange is the pulse, an investigation of an online
threat. Pulses describe any type of online threat including malware, fraud
campaigns, and even state sponsored hacking.

#### Security Events
>
* Website
 - `https://otx.alienvault.com/`
* Source
 - `None`
* Data
 - URL, Domain Name, IP Address, etc.
* Format
 - Not Available
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No API KEY

##### Sample Output of IntelMQ

```javascript
{
  "raw": "eyJfaWQiOiAiNTc3MzAwODY3NjFiODIwMTNhYjc4MjkzIiwgImNyZWF0ZWQiOiAiMjAxNi0wNi0yOFQyMjo1NjowNi4zNjUiLCAiZGVzY3JpcHRpb24iOiAiIiwgImluZGljYXRvciI6ICJib3g0MDg0Lm5ldCIsICJ0eXBlIjogImRvbWFpbiJ9",
  "time": {
    "source": "2016-06-28T22:56:06+00:00",
    "observation": "2016-07-07T08:27:18+00:00"
  },
  "feed": {
    "name": "AlienVault OTX",
    "accuracy": 100
  },
  "classification": {
    "type": "blacklist"
  },
  "extra": "{\"author\": \"AlienVault\", \"pulse\": \"Prince of Persia \\u2013 Game Over\"}",
  "comment": "Unit 42 published a blog at the beginning of May titled \u201cPrince of Persia,\u201d in which we described the discovery of a decade-long campaign using a formerly unknown malware family, Infy, that targeted government and industry interests worldwide.\nSubsequent to the publishing of this article, through cooperation with the parties responsible for the C2 domains, Unit 42 researchers successfully gained control of multiple C2 domains. This disabled the attacker\u2019s access to their victims in this campaign, provided further insight into the targets currently victimized in this operation, and enabled the notification of affected parties.",
  "source": {
    "fqdn": "box4084.net"
  }
}
```