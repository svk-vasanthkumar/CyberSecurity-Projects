# Binary Analysis & Reverse Engineering

## What This Domain Covers

Binary Analysis & Reverse Engineering focuses on examining compiled software without source code. This includes static analysis, disassembly, control flow reconstruction, YARA scanning, entropy analysis, and interactive reverse-engineering education.

## Cybersecurity Skills Covered

- Multi-format binary parsing (ELF, PE, Mach-O)
- x86/x86_64 disassembly and annotation
- Control flow graph generation and cross-reference analysis
- YARA rule authoring and malware/packer detection
- Shannon entropy analysis for packed or encrypted sections
- Interactive reverse-engineering with solve-then-reveal pedagogy

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [binary-analysis-tool](./binary-analysis-tool) | Rust, Axum, React, goblin, iced-x86, yara-x | Static binary analysis engine with multi-format parsing, YARA scanning, disassembly, and MITRE ATT&CK threat scoring |
| [rveng](./rveng) | Python, FastAPI, React, capstone | Interactive reverse-engineering learning platform with ELF parsing, x86-64 disassembly, PLT resolution, and challenge grading |

## Secondary Domains Represented

- **Malware & Endpoint Security** — binary-analysis-tool scores binaries for malware, packers, and suspicious crypto patterns
- **Security Research & Security Labs** — rveng is a research-grade platform for teaching reverse engineering without executing binaries
