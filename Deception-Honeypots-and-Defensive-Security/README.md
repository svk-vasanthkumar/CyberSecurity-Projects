# Deception, Honeypots & Defensive Security

## What This Domain Covers

Deception, Honeypots & Defensive Security focuses on active defense through deception technology. This includes honeytoken generation, multi-protocol honeypot networks, attacker behavior capture, and threat intelligence extraction from compromised systems.

## Cybersecurity Skills Covered

- Honeytoken minting across web bugs, documents, configs, and protocol decoys
- Multi-protocol honeypot emulation (SSH, HTTP, FTP, SMB, MySQL, Redis)
- Attacker interaction capture and tool fingerprinting
- IOC extraction with confidence scoring and deduplication
- MITRE ATT&CK technique mapping from attacker behavior
- STIX 2.1 export and firewall blocklist generation

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [canary-token-generator](./canary-token-generator) | Go, React, PostgreSQL, Redis | Self-hosted honeytoken generator minting seven types of tripwire artifacts with Telegram/webhook alerts |
| [honeypot-network](./honeypot-network) | Go, React, PostgreSQL | Multi-protocol honeypot network simulating 6 services, mapping 27 MITRE ATT&CK techniques, and exporting IOCs |

## Secondary Domains Represented

- **SOC, SIEM & Security Monitoring** — honeypot-network streams real-time events via WebSocket to a dashboard
- **Cyber Threat Intelligence** — both projects extract and export IOCs, STIX bundles, and attacker intelligence
