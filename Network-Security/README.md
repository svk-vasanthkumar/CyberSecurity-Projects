# Network Security

## What This Domain Covers

Network Security focuses on protecting the integrity, confidentiality, and availability of data as it traverses network infrastructure. This includes reconnaissance, traffic analysis, protocol inspection, firewall management, and network-level attack detection.

## Cybersecurity Skills Covered

- Packet capture and deep packet inspection
- Port scanning and service enumeration
- DNS reconnaissance and analysis
- TLS/SSL fingerprinting and inspection
- Firewall rule engineering and conflict detection
- Network traffic baselining and anomaly detection
- Raw socket programming and network protocol parsing

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [dns-lookup](./dns-lookup) | Python, Rich | Professional DNS query CLI with reverse lookups, WHOIS integration, and JSON export |
| [firewall-rule-engine](./firewall-rule-engine) | V | Firewall rule parser, conflict detector, optimizer, and hardened ruleset generator for iptables and nftables |
| [network-traffic-analyzer](./network-traffic-analyzer) | Python (Scapy, Rich), C++ (libpcap, FTXUI) | Dual-implementation packet capture tool with real-time protocol parsing and statistics |
| [simple-port-scanner](./simple-port-scanner) | C++20, Boost.Asio | Asynchronous TCP port scanner for high-concurrency network reconnaissance |
| [ja3-ja4-tls-fingerprinting](./ja3-ja4-tls-fingerprinting) | Rust | Passive TLS fingerprinting sensor computing JA3, JA4, JA4S, JA4H, JA4X, and JA4T fingerprints |
| [zig-stateless-scanner](./zig-stateless-scanner) | Zig | Stateless, line-rate mass TCP/UDP port scanner with SipHash cookies and cyclic-group permutation |

## Secondary Domains Represented

- **Cyber Threat Intelligence** — ja3-ja4-tls-fingerprinting matches fingerprints against threat intelligence feeds and detects TLS stack anomalies
- **Digital Forensics & Incident Response** — network-traffic-analyzer captures packets suitable for forensic analysis
