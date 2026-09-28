# Linux & Operating System Security

## What This Domain Covers

Linux & Operating System Security focuses on securing host operating systems through hardening, compliance auditing, and runtime monitoring. This includes CIS benchmark assessment, syscall tracing, persistence detection, and kernel-level observability.

## Cybersecurity Skills Covered

- CIS Benchmark compliance auditing (filesystem, services, network, SSH, logging)
- Baseline comparison and regression detection
- eBPF-based syscall monitoring and MITRE ATT&CK detection rules
- Linux persistence mechanism scanning (systemd, cron, SSH, LD_PRELOAD, kernel modules)
- Heuristic detection of encoded payloads and download-and-execute chains
- Severity scoring and structured JSON reporting

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [linux-cis-hardening-auditor](./linux-cis-hardening-auditor) | Bash | CIS Benchmark compliance auditor for Linux with 104 controls, scored reporting, and remediation guidance |
| [linux-ebpf-security-tracer](./linux-ebpf-security-tracer) | Python, C (eBPF) | Real-time syscall tracing tool using eBPF for security observability with 10 MITRE ATT&CK detection rules |
| [systemd-persistence-scanner](./systemd-persistence-scanner) | Go | Linux persistence mechanism scanner detecting backdoors across 12+ categories with MITRE ATT&CK mapping |

## Secondary Domains Represented

- **SOC, SIEM & Security Monitoring** — linux-ebpf-security-tracer streams correlated events suitable for SIEM ingestion
- **Malware & Endpoint Security** — systemd-persistence-scanner detects persistence techniques used by malware and APTs
