---
description: How to park a new domains
---

# Parking options

* park via ns records
* park via a record

## Parking via NS records

Wildcardparking provides full dns support so parking with NS records is the recommended way to use the service.

* [ ] Go to Domains page on your account to see your unique NS names.
* [ ] Visit your registrar site to assign this NS names to desired domains
* [ ] Upload a list of domains you are parking to our site\*

After DNS records are properly set our system will recognize your domains and you will be able to control them from our platform.

{% hint style="info" %}
"\*" -Manual upload is only necessary if you have no dedicated ip address. \(All free accounts start without dedicated IP\)

NS records change may require up to 48 hours to fully have effect.
{% endhint %}

## Parking via A record

You can easily park you domain by forwarding an A record to you servers as well, but this way of parking may require an additional confirmation via TXT record.

* [ ] Go to you Domains page to see your IP address and TXT key phrase 
* [ ] Add required A and TXT records with your current DNS provider
* [ ] Upload a list of domains you are parking to our site\*

{% hint style="info" %}
"\*" -Manual upload and TXT confirmation are only necessary if you have no dedicated ip address. \(All free accounts start without dedicated IP\)

If you choose to park via A records, you will have to adapt your dns yourself settings manually to use such features as email forwarding.
{% endhint %}

