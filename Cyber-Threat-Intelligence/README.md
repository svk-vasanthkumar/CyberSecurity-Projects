# Cyber Threat Intelligence

## What This Domain Covers

Cyber Threat Intelligence focuses on collecting, analyzing, and disseminating information about threats, adversaries, and vulnerabilities. This includes CVE enrichment, threat feed aggregation, news clustering, and intelligence-driven alerting.

## Cybersecurity Skills Covered

- RSS/Atom feed ingestion and fail-soft parsing
- CVE enrichment from authoritative sources (CISA KEV, EPSS, NVD)
- Connected-component clustering and cross-outlet velocity scoring
- Deterministic ranking models for signal prioritization
- IOC extraction and STIX 2.1 export
- Watch daemons and webhook-based alerting

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [security-news-scraper](./security-news-scraper) | Go, SQLite, Bubbletea | Keyless security-news and CVE intelligence engine that clusters stories, enriches CVEs, and ranks by what matters |

## Secondary Domains Represented

- **SOC, SIEM & Security Monitoring** — security-news-scraper outputs can feed SIEM dashboards and threat intelligence platforms
- **Network Security** — ja3-ja4-tls-fingerprinting (in Network Security) provides passive TLS intelligence used in threat detection
