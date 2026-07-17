# MakeNewMedia Communications – Geofeed Repository

This repository contains the public geofeed and supporting operational data published by MakeNewMedia Communications GmbH.

## Public Geofeed

Self-published geofeed according to:

- RFC 8805 – *A Format for Self-Published IP Geolocation Feeds*
- RFC 9632 – *Finding and Using Geofeed Data*

**Geofeed URL**

https://geo.makenewmedia.com/geofeeds.csv

---

# EU Sanctions Media Filter

This repository also maintains an Adblock-compatible domain filter for online media services subject to European Union restrictive measures.

The filter is intended for operational use with DNS resolvers, firewalls, secure web gateways, proxies, content filtering systems and similar network security infrastructure.

## Filter File

https://raw.githubusercontent.com/mnmcom/geofeeds/main/eu_filter_ru_sanctions.txt

## Legal Basis

The filter reflects the domains published by the Austrian regulatory authority (RTR/KommAustria) pursuant to:

- § 64 Abs. 3a AMD-G (Austria)
- Article 2f of Council Regulation (EU) No. 833/2014
- Council Regulation (EU) 2026/506 (20th EU sanctions package), amending Regulation (EU) No. 833/2014

Official publication:

https://www.rtr.at/Paragraf_64_3a_AMD-G

## Filter Format

The filter uses standard Adblock-compatible domain rules.

Example:

```text
||example.com^
```

This rule matches:

- `example.com`
- `www.example.com`
- `*.example.com`

## Verification

| Item | Value |
| :--- | :---- |
| Last verified | 2026-07-17 |
| Source | RTR / KommAustria |
| Legal status | Council Regulation (EU) 2026/506 (20th sanctions package) |

## Disclaimer

This repository provides an operational mirror of the domains published by RTR/KommAustria.

The RTR publication remains the authoritative source.

Following Council Regulation (EU) 2026/506, restrictions may also apply to mirror sites, successor services and comparable organisations intended to circumvent EU sanctions. Consequently, the published domain list is not necessarily exhaustive and may be updated by RTR without changes to this repository.

Users of this repository are responsible for ensuring compliance with applicable European Union and national legislation and should regularly verify the filter against the official RTR publication.

No warranty is given regarding completeness, accuracy or continued availability of the listed domains.

---

# References

- RFC 8805 – *A Format for Self-Published IP Geolocation Feeds*  
  https://www.rfc-editor.org/rfc/rfc8805

- RFC 9632 – *Finding and Using Geofeed Data*  
  https://www.rfc-editor.org/rfc/rfc9632

- Council Regulation (EU) No. 833/2014  
  https://eur-lex.europa.eu/eli/reg/2014/833

- Council Regulation (EU) 2026/506 (20th sanctions package)  
  https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202600506

- RTR / KommAustria – § 64 Abs. 3a AMD-G  
  https://www.rtr.at/Paragraf_64_3a_AMD-G

---

# License

Unless stated otherwise, the contents of this repository are provided **"AS IS"**, without warranty of any kind, express or implied.

Use of the provided data remains the sole responsibility of the operator. Compliance with applicable laws and regulations must be assessed by each user independently.
