# MakeNewMedia Communications – Geofeed Repository

This repository contains the public geofeed and supporting data published by MakeNewMedia Communications GmbH.

## Public Geofeed

Self-published geofeed according to:

- RFC 8805 – *A Format for Self-Published IP Geolocation Feeds*
- RFC 9632 – *Geofeed Discovery*

**Geofeed URL**

https://geo.makenewmedia.com/geofeeds.csv

---

## EU Sanctions Media Filter

This repository also maintains an Adblock-compatible domain filter for online media services that are subject to EU restrictive measures.

The list is intended for operational use by DNS resolvers, firewalls, proxies and content filtering systems.

### Filter File

https://raw.githubusercontent.com/mnmcom/geofeeds/main/eu_filter_ru_sanctions.txt

### Legal Basis

The filter reflects the domains published by the Austrian regulatory authority (RTR/KommAustria) in connection with:

- § 64 Abs. 3a AMD-G (Austria)
- Article 2f of Council Regulation (EU) No. 833/2014

Official source:

https://www.rtr.at/Paragraf_64_3a_AMD-G

### Filter Format

The file uses standard Adblock-compatible domain rules.

Example:

```text
||example.com^
```

This syntax matches:

- example.com
- www.example.com
- any.subdomain.example.com

### Verification

| Item | Value |
|------|-------|
| Last verified | 2026-07-17 |
| RTR source revision | 2025-04-08 |

### Disclaimer

This repository mirrors the domains published by RTR/KommAustria for operational purposes.

The RTR publication remains the authoritative source. The published domain list is not exhaustive and may change without notice. Operators should regularly compare the filter against the official RTR publication and applicable EU legislation.

---

## Repository Structure

```text
.
├── README.md
├── geofeeds.csv
└── eu_filter_ru_sanctions.txt
```

---

## References

- RFC 8805 – https://www.rfc-editor.org/rfc/rfc8805
- RFC 9632 – https://www.rfc-editor.org/rfc/rfc9632
- RTR – https://www.rtr.at/Paragraf_64_3a_AMD-G

---

## License

Unless stated otherwise, the contents of this repository are provided without warranty. Users are responsible for ensuring compliance with all applicable laws and regulations when using the published data.
