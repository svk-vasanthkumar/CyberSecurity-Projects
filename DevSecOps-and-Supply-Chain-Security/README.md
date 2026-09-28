# DevSecOps & Software Supply Chain Security

## What This Domain Covers

DevSecOps & Software Supply Chain Security focuses on integrating security into the development lifecycle and protecting the software supply chain. This includes dependency scanning, SBOM generation, vulnerability policy gates, and secure build pipelines.

## Cybersecurity Skills Covered

- Multi-ecosystem dependency graph construction
- SBOM generation in SPDX 2.3 and CycloneDX 1.5 formats
- Vulnerability matching against OSV and NVD databases
- CI/CD policy gates with severity thresholds
- Software composition analysis (SCA)
- Cache-backed response optimization for large-scale scans

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [sbom-generator-vulnerability-matcher](./sbom-generator-vulnerability-matcher) | Go, Cobra, SQLite | SBOM generator and vulnerability matcher for Go, Node.js, and Python projects |

## Secondary Domains Represented

- **Vulnerability Assessment & Penetration Testing** — sbom-generator-vulnerability-matcher cross-references dependencies against OSV/NVD to surface known CVEs
