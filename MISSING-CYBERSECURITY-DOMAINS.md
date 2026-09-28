# Missing Cybersecurity Domains

This document identifies cybersecurity domains with no or very weak project coverage in the current collection, along with recommended project ideas to round out the portfolio.

## Domains with No Coverage

### 1. Email & Phishing Security

**Current Coverage:** None

**Why It Matters:** Email remains the top attack vector for initial access. Phishing, Business Email Compromise (BEC), and email-borne malware account for a majority of breaches. Understanding email security headers, spoofing prevention, and phishing simulation is essential for defensive security.

**Recommended Project Idea:** Phishing email analyzer and SPF/DKIM/DMARC validator. Parse raw email headers, validate SPF/DKIM/DMARC alignment, detect spoofing indicators, and score emails on a phishing risk scale. Include a phishing template generator for authorized security awareness training.

**Suggested Technology Stack:** Python (email parsing, DNS lookups), FastAPI (optional web UI), React (optional dashboard)

### 2. Wireless Security

**Current Coverage:** None

**Why It Matters:** Wireless networks (Wi-Fi, Bluetooth, Zigbee, NFC) introduce unique attack surfaces. Evil twin attacks, WPA2/WPA3 handshake capture, deauthentication frames, and BLE spoofing are active research areas. Wireless forensics is also critical for incident response.

**Recommended Project Idea:** Wi-Fi security auditor that captures WPA2/WPA3 handshakes, runs deauthentication detection, maps nearby SSIDs, and validates encryption configurations. Include a Bluetooth Low Energy (BLE) scanner for device enumeration and GATT service inspection.

**Suggested Technology Stack:** Python (Scapy, pylibpcap), C (for monitor mode), React (optional dashboard)

### 3. IoT & Embedded Security

**Current Coverage:** None

**Why It Matters:** IoT devices often ship with hardcoded credentials, unpatched firmware, and insecure communication. With billions of devices deployed, IoT compromise is a growing concern for both consumer and industrial environments.

**Recommended Project Idea:** IoT firmware analyzer that extracts filesystems from firmware images, identifies hardcoded credentials, detects outdated libraries, and maps findings to CWE. Include a protocol fuzzer for common IoT protocols (MQTT, CoAP, Zigbee).

**Suggested Technology Stack:** Python (binwalk, cryptography), Go (protocol fuzzer), React (optional dashboard)

### 4. Cloud Security

**Current Coverage:** None

**Why It Matters:** Cloud misconfigurations are the leading cause of data breaches in cloud-native environments. IAM policy analysis, storage bucket auditing, and workload identity management are critical skills for modern security teams.

**Recommended Project Idea:** Cloud configuration auditor that scans AWS S3 buckets, IAM policies, and security groups for public exposure, overprivileged roles, and missing encryption. Support multi-cloud (AWS, GCP, Azure) with a policy-as-code engine.

**Suggested Technology Stack:** Go or Python (AWS SDK, GCP SDK), Terraform parser, SQLite for state

### 5. Mobile Security

**Current Coverage:** None

**Why It Matters:** Mobile applications handle sensitive data and run on devices with limited user control. Insecure data storage, weak cryptography, and improper platform usage are common mobile vulnerabilities.

**Recommended Project Idea:** Android APK static analyzer that extracts manifest permissions, identifies hardcoded secrets, detects insecure crypto usage, and maps findings to OWASP Mobile Top 10. Include an iOS IPA analyzer for binary analysis and jailbreak detection bypasses.

**Suggested Technology Stack:** Python (androguard, mobsf), React (optional dashboard), SQLite

### 6. Blockchain & Web3 Security

**Current Coverage:** None

**Why It Matters:** Smart contract vulnerabilities have led to billions in stolen funds. Reentrancy, integer overflow, and access control flaws in DeFi protocols require specialized auditing skills.

**Recommended Project Idea:** Smart contract static analyzer for Solidity that detects reentrancy, unchecked low-level calls, and access control issues. Include a DeFi protocol simulator for testing exploit scenarios in a sandbox.

**Suggested Technology Stack:** Python (slither-analyzer integration), Go (EVM bytecode analysis), React (optional dashboard)

### 7. Security Automation & Orchestration

**Current Coverage:** None

**Why It Matters:** Security teams are overwhelmed by alert volume. Automation, playbook orchestration, and SOAR (Security Orchestration, Automation and Response) are essential for scaling defenses.

**Recommended Project Idea:** Playbook-based security orchestrator that ingests alerts from multiple sources, runs conditional logic, executes response actions (block IP, disable account, isolate host), and tracks case status. Include a YAML-based playbook editor.

**Suggested Technology Stack:** Python (FastAPI, Celery), Redis (task queue), PostgreSQL (state), React (playbook editor)

### 8. Digital Forensics & Incident Response

**Current Coverage:** Very weak (only secondary coverage from network-traffic-analyzer)

**Why It Matters:** DFIR is critical for breach investigation, evidence preservation, and root cause analysis. Memory forensics, timeline analysis, and artifact parsing are high-demand skills.

**Recommended Project Idea:** Disk image forensic parser that extracts file system artifacts, browser history, prefetch files, and event logs. Include a timeline generator and a memory dump analyzer for process enumeration and injected code detection.

**Suggested Technology Stack:** Python (construct, volatility3), C (performance-critical parsing), SQLite (timeline storage)

## Domains with Weak Coverage

### Memory Forensics

**Current Coverage:** None standalone; partially implied by binary-analysis-tool and linux-ebpf-security-tracer

**Why It Matters:** Memory forensics is essential for detecting fileless malware, rootkits, and in-memory code injection. Volatility and Rekall are standard tools, but building a lightweight memory analyzer teaches process Hollowing detection, DLL injection spotting, and rootkit identification.

**Recommended Project Idea:** Lightweight memory forensics framework that parses Windows or Linux memory dumps, enumerates processes, detects hidden modules, and identifies injected code. Focus on one platform deeply rather than both shallowly.

**Suggested Technology Stack:** Python (construct, volatility3 plugins), C (fast parser)

### Zero Trust Architecture

**Current Coverage:** None standalone; partially covered by identity and network projects

**Why It Matters:** Zero Trust ("never trust, always verify") is the modern security paradigm. Identity-based access, microsegmentation, and continuous verification are replacing perimeter-based models.

**Recommended Project Idea:** Zero Trust network access (ZTNA) proxy that enforces identity-based access policies, implements device posture checks, and mTLS-based service-to-service authentication with SPIFFE/SPIRE integration.

**Suggested Technology Stack:** Go or Rust (Envoy proxy integration), PostgreSQL (policy store), React (admin dashboard)

### LLM / AI Security

**Current Coverage:** Moderate (prompt-injection-firewall covers LLM-specific attacks)

**Why It Matters:** Beyond prompt injection, AI security includes model stealing, training data poisoning, adversarial examples, and AI supply chain integrity. As AI adoption grows, these attack vectors become critical.

**Recommended Project Idea:** AI supply chain scanner that verifies model provenance, detects fine-tuning artifacts, tests for adversarial robustness against common evasion techniques, and audits model cards for bias and safety metadata.

**Suggested Technology Stack:** Python (PyTorch, transformers), ONNX Runtime, React (dashboard)
