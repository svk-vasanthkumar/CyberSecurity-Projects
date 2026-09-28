# SOC, SIEM & Security Monitoring

## What This Domain Covers

SOC, SIEM & Security Monitoring focuses on centralized log collection, event correlation, alerting, and real-time situational awareness. This includes security information and event management, attack playbook simulation, and multi-feed threat intelligence dashboards.

## Cybersecurity Skills Covered

- Real-time log ingestion and event correlation
- Threshold, sequence, and aggregation rule engines
- MITRE ATT&CK attack scenario simulation
- Alert lifecycle management (triage, investigation, resolution)
- Multi-source threat intelligence fusion
- WebSocket-driven live alert streaming and visualization

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [siem-dashboard](./siem-dashboard) | Python, Flask, React, MongoDB, Redis | Full-stack SIEM dashboard with real-time log correlation, MITRE ATT&CK playbooks, and attack simulation engine |
| [monitor-the-situation-dashboard](./monitor-the-situation-dashboard) | Go, React, PostgreSQL, WebSocket | Operator-grade situational awareness dashboard fusing 11 live cyber, world, and finance feeds into a 3D-globe SOC view |

## Secondary Domains Represented

- **Cyber Threat Intelligence** — monitor-the-situation-dashboard aggregates CISA KEV, NVD/EPSS, ransomware.live, and DShield feeds
- **AI & Machine Learning Security** — siem-dashboard can integrate ML-based anomaly detection for log correlation
