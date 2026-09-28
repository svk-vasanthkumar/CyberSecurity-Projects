# Privacy & Data Security

## What This Domain Covers

Privacy & Data Security focuses on protecting information confidentiality and preventing unauthorized data exposure. This includes data loss prevention, steganography, covert channels, and privacy-preserving communication.

## Cybersecurity Skills Covered

- Data Loss Prevention (DLP) across files, databases, and network traffic
- PII, credential, financial, and PHI detection with confidence scoring
- Steganography across image, audio, QR, text, and PDF carriers
- Encrypted envelope design (Argon2id, AEAD, compression, integrity)
- Covert channel analysis and steganalytical awareness
- Compliance framework mapping (HIPAA, PCI-DSS, GDPR, CCPA)

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [steganography-multi-tool](./steganography-multi-tool) | Go, Cobra, Bubbletea | Multi-format steganography tool hiding encrypted messages in images, audio, QR codes, text, and PDFs |
| [dlp-scanner](./dlp-scanner) | Python, Typer, Rich | Data Loss Prevention scanner for files, databases, and network traffic with compliance framework mapping |

## Secondary Domains Represented

- **Cryptography & Data Protection** — steganography-multi-tool encrypts payloads with Argon2id and ChaCha20-Poly1305 before embedding
- **Secrets & Sensitive Data Security** — dlp-scanner detects exposed credentials, API keys, and sensitive patterns
