# Secrets & Sensitive Data Security

## What This Domain Covers

Secrets & Sensitive Data Security focuses on discovering, classifying, and protecting credentials and sensitive information. This includes secret scanning in code and git history, credential exposure detection, and data loss prevention.

## Cybersecurity Skills Covered

- Pattern-based secret detection (150+ rules for AWS, GitHub, GCP, Azure, etc.)
- Shannon entropy analysis for high-randomness string identification
- Git history scanning across branches and depth ranges
- HIBP breach verification via k-anonymity protocol
- Credential exposure detection across Linux home directories
- Confidence scoring with checksum validation and context keyword proximity

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [secrets-scanner](./secrets-scanner) | Go | Secrets scanner for codebases and git repositories with 150 detection rules, entropy analysis, and HIBP integration |
| [credential-enumeration](./credential-enumeration) | Nim | Post-access credential exposure detection for Linux home directories across 7 categories |
| [dlp-scanner](./dlp-scanner) | Python, Typer, Rich | Data Loss Prevention scanner for files, databases, and network traffic with compliance framework mapping |

## Secondary Domains Represented

- **Privacy & Data Security** — dlp-scanner maps findings to HIPAA, PCI-DSS, GDPR, CCPA, SOX, GLBA, and FERPA
- **Linux & Operating System Security** — credential-enumeration audits Linux filesystems for exposed credentials
