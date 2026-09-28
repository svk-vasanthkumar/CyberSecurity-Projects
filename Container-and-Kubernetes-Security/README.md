# Container & Kubernetes Security

## What This Domain Covers

Container & Kubernetes Security focuses on securing containerized workloads and orchestration platforms. This includes image auditing, runtime configuration assessment, benchmark compliance, and infrastructure-as-code validation.

## Cybersecurity Skills Covered

- CIS Docker Benchmark compliance scanning
- Container runtime misconfiguration detection (privileged mode, capabilities, sockets)
- Dockerfile and Compose file security auditing
- AppArmor/seccomp profile validation
- Resource limit and user namespace verification
- CI/CD integration with SARIF and JUnit output

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [docker-security-audit](./docker-security-audit) | Go | Docker security audit CLI checking containers, images, and Dockerfiles against CIS Docker Benchmark v1.6.0 |

## Secondary Domains Represented

- **DevSecOps & Software Supply Chain Security** — docker-security-audit integrates into CI/CD pipelines as a policy gate
