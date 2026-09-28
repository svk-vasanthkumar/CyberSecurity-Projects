# Project Inventory

| Project | Primary Domain | Secondary Domain(s) | Difficulty | Technologies | Description |
|---------|---------------|---------------------|------------|--------------|-------------|
| base64-tool | Cryptography & Data Protection | Privacy & Data Security | Beginner | Python, Rich | Multi-format encoding/decoding CLI with recursive layer detection for WAF bypass analysis |
| c2-beacon | Security Research & Labs | Malware & Endpoint Security | Beginner | Python, FastAPI, React, WebSockets | Command and Control beacon with XOR-encoded WebSocket protocol and 10 MITRE ATT&CK commands |
| caesar-cipher | Cryptography & Data Protection | — | Beginner | Python, Rich | Caesar cipher encryption, decryption, and brute-force cracking with frequency analysis |
| canary-token-generator | Deception, Honeypots & Defensive Security | Cyber Threat Intelligence | Beginner | Go, React, PostgreSQL, Redis | Self-hosted honeytoken generator with 7 token types, Telegram/webhook alerts, and GeoIP enrichment |
| deserialization-gadget-lab | Application Security | Binary Analysis & Reverse Engineering | Beginner | Ruby, Sinatra, Rack | Ruby object-deserialization security lab with safe/unsafe readers, gadget scanner, and CVE reproduction |
| dns-lookup | Network Security | — | Beginner | Python, Rich | Professional DNS query CLI with reverse lookups, WHOIS integration, and batch processing |
| firewall-rule-engine | Network Security | — | Beginner | V | Firewall rule parser, conflict detector, optimizer, and hardened ruleset generator for iptables/nftables |
| hash-cracker | Cryptography & Data Protection | Vulnerability Assessment & Penetration Testing | Beginner | C++23, mmap | Multi-threaded hash cracking with dictionary, brute-force, and rule-based mutation attacks |
| hash-identifier | Cryptography & Data Protection | — | Beginner | Python | Identify ~30 hash formats by prefix, length, and character set |
| http-headers-scanner | Web & API Security | — | Beginner | Python, httpx, Rich | Grades HTTP security headers A through F using a weighted-rubric model |
| keylogger | Malware & Endpoint Security | Security Research & Labs | Beginner | Python, pynput, mss | Educational keylogger demonstrating input capture, window tracking, and C2 delivery for security research |
| linux-cis-hardening-auditor | Linux & Operating System Security | Vulnerability Assessment & Penetration Testing | Beginner | Bash | CIS Benchmark compliance auditor for Linux with 104 controls, scored reporting, and remediation guidance |
| linux-ebpf-security-tracer | Linux & Operating System Security | SOC, SIEM & Security Monitoring | Beginner | Python, C (eBPF) | Real-time syscall tracing tool using eBPF with 10 MITRE ATT&CK detection rules |
| network-traffic-analyzer | Network Security | Digital Forensics & Incident Response | Beginner | Python (Scapy), C++ (libpcap) | Dual-implementation packet capture tool with real-time protocol parsing and statistics |
| password-manager | Identity, Authentication & Access Management | Cryptography & Data Protection | Beginner | Python, Argon2id, AES-256-GCM | Encrypted CLI password manager with atomic writes, master password rotation, and secure generation |
| prompt-injection-firewall | AI & Machine Learning Security | Application Security | Beginner | Python, FastAPI, React | Prompt injection firewall with five enforcement layers including nonce fencing and tool authorization |
| simple-port-scanner | Network Security | Vulnerability Assessment & Penetration Testing | Beginner | C++20, Boost.Asio | Asynchronous TCP port scanner for high-concurrency network reconnaissance |
| simple-vulnerability-scanner | Vulnerability Assessment & Penetration Testing | DevSecOps & Software Supply Chain Security | Beginner | Go, OSV.dev | Fast Python dependency updater and vulnerability scanner with OSV.dev integration |
| steganography-multi-tool | Privacy & Data Security | Cryptography & Data Protection | Beginner | Go, Cobra, Bubbletea | Multi-format steganography tool hiding encrypted messages in images, audio, QR, text, and PDFs |
| systemd-persistence-scanner | Linux & Operating System Security | Malware & Endpoint Security | Beginner | Go | Linux persistence mechanism scanner detecting backdoors across 12+ categories with MITRE ATT&CK mapping |
| api-security-scanner | Web & API Security | — | Intermediate | Python, FastAPI, React | Full-stack API vulnerability scanner targeting the OWASP API Security Top 10 |
| binary-analysis-tool | Binary Analysis & Reverse Engineering | Malware & Endpoint Security | Intermediate | Rust, Axum, React, goblin, iced-x86, yara-x | Static binary analysis engine with multi-format parsing, YARA scanning, and threat scoring |
| credential-enumeration | Secrets & Sensitive Data Security | Linux & Operating System Security | Intermediate | Nim | Post-access credential exposure detection for Linux home directories across 7 categories |
| credential-rotation-enforcer | Identity, Authentication & Access Management | Secrets & Sensitive Data Security | Intermediate | Crystal, PostgreSQL, Telegram | Credential rotation enforcer with compile-time policy DSL and tamper-evident audit log |
| dlp-scanner | Privacy & Data Security | Secrets & Sensitive Data Security | Intermediate | Python, Typer, Rich | Data Loss Prevention scanner for files, databases, and network traffic with compliance mapping |
| docker-security-audit | Container & Kubernetes Security | DevSecOps & Software Supply Chain Security | Intermediate | Go | Docker security audit CLI checking against CIS Docker Benchmark v1.6.0 |
| ja3-ja4-tls-fingerprinting | Network Security | Cyber Threat Intelligence | Intermediate | Rust | Passive TLS fingerprinting sensor computing JA3/JA4 and matching against threat intelligence feeds |
| sbom-generator-vulnerability-matcher | DevSecOps & Software Supply Chain Security | Vulnerability Assessment & Penetration Testing | Intermediate | Go, Cobra, SQLite | SBOM generator and vulnerability matcher producing SPDX 2.3 and CycloneDX 1.5 documents |
| secrets-scanner | Secrets & Sensitive Data Security | — | Intermediate | Go | Secrets scanner for codebases and git history with 150 detection rules and HIBP integration |
| security-news-scraper | Cyber Threat Intelligence | SOC, SIEM & Security Monitoring | Intermediate | Go, SQLite, Bubbletea | Keyless security-news and CVE intelligence engine with clustering, enrichment, and ranking |
| siem-dashboard | SOC, SIEM & Security Monitoring | — | Intermediate | Python, Flask, React, MongoDB, Redis | Full-stack SIEM dashboard with real-time log correlation and MITRE ATT&CK attack simulation |
| ai-threat-detection | AI & Machine Learning Security | SOC, SIEM & Security Monitoring | Advanced | Python, FastAPI, PyTorch, ONNX Runtime, React | AI-powered threat detection engine using a 3-model ML ensemble on nginx access logs |
| api-rate-limiter | Web & API Security | Security Automation & Orchestration | Advanced | Python, FastAPI | Enterprise rate limiting library using HTTP 420 with multiple algorithms and Redis support |
| bug-bounty-platform | Vulnerability Assessment & Penetration Testing | Application Security | Advanced | Python, FastAPI, React, PostgreSQL | Production-ready bug bounty platform with CVSS scoring and report triage workflows |
| encrypted-p2p-chat | Cryptography & Data Protection | Identity, Authentication & Access Management | Advanced | Python, FastAPI, SolidJS | End-to-end encrypted P2P chat using Signal Protocol and WebAuthn/Passkey authentication |
| haskell-reverse-proxy | Security Research & Labs | Binary Analysis & Reverse Engineering | Advanced | Haskell | Next-generation reverse proxy research project (in progress) |
| honeypot-network | Deception, Honeypots & Defensive Security | Cyber Threat Intelligence | Advanced | Go, React, PostgreSQL | Multi-protocol honeypot network simulating 6 services and mapping 27 MITRE ATT&CK techniques |
| hsm-emulator | Cryptography & Data Protection | Identity, Authentication & Access Management | Advanced | Zig, PKCS#11 | Software HSM emulator compiling to a real Cryptoki shared object with encrypted-at-rest key storage |
| monitor-the-situation-dashboard | SOC, SIEM & Security Monitoring | Cyber Threat Intelligence | Advanced | Go, React, PostgreSQL, WebSocket | Operator-grade situational awareness dashboard fusing 11 live feeds into a 3D-globe SOC view |
| rveng | Binary Analysis & Reverse Engineering | Security Research & Labs | Advanced | Python, FastAPI, React, capstone | Interactive reverse-engineering learning platform with ELF parsing and solve-then-reveal grading |
| zero-day-vulnerability-scanner | Vulnerability Assessment & Penetration Testing | Binary Analysis & Reverse Engineering | Advanced | Rust, AFL++ | Memory-corruption scanner for C/C++ parsers with automated harness generation and crash triage |
| zig-stateless-scanner | Network Security | Vulnerability Assessment & Penetration Testing | Advanced | Zig | Stateless, line-rate mass TCP/UDP port scanner with SipHash cookies and cyclic-group permutation |
