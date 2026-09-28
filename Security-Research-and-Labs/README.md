# Security Research & Security Labs

## What This Domain Covers

Security Research & Security Labs focuses on offensive and defensive security research in controlled, educational environments. This includes C2 framework development, reverse proxy security research, exploit simulation, and proof-of-concept tooling for authorized testing.

## Cybersecurity Skills Covered

- Command and Control (C2) protocol design and MITRE ATT&CK mapping
- Operator dashboard and beacon lifecycle management
- Reverse proxy architecture and TLS termination research
- Authorized penetration testing platform design
- Exploit simulation and controlled demonstration environments
- Legal and ethical boundaries of security research

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [c2-beacon](./c2-beacon) | Python, FastAPI, React, WebSockets | Command and Control beacon and server with XOR-encoded WebSocket protocol and 10 MITRE ATT&CK mapped commands |
| [haskell-reverse-proxy](./haskell-reverse-proxy) | Haskell | Next-generation reverse proxy research project (in progress) |

## Important Notice

> **LAB / AUTHORIZED SECURITY TESTING ONLY**
>
> Projects in this domain are designed for security research, education, and authorized penetration testing. Do not deploy c2-beacon or similar tools against systems you do not own or have explicit written permission to test.

## Secondary Domains Represented

- **Malware & Endpoint Security** — c2-beacon includes keylogging, screenshot, and persistence commands mapped to MITRE ATT&CK
- **Binary Analysis & Reverse Engineering** — haskell-reverse-proxy involves low-level network protocol handling and performance-critical systems programming
