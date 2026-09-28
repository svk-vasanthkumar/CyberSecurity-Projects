# Application Security

## What This Domain Covers

Application Security focuses on securing software applications from design through deployment. This includes secure coding practices, vulnerability classes like injection and deserialization, gadget chain analysis, and runtime protection mechanisms.

## Cybersecurity Skills Covered

- Object deserialization vulnerability analysis (Marshal, YAML, pickle)
- Gadget chain identification and payload construction
- Allowlist-based boundary detection and runtime guards
- Secure deserialization practices and TracePoint-based veto mechanisms
- CVE reproduction and controlled exploit demonstration
- Defense-in-depth strategy evaluation

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [deserialization-gadget-lab](./deserialization-gadget-lab) | Ruby, Sinatra, Rack | Ruby object-deserialization security lab with safe/unsafe readers, gadget scanner, payload builder, and vulnerable target |

## Secondary Domains Represented

- **Binary Analysis & Reverse Engineering** — deserialization-gadget-lab requires understanding compiled Ruby method dispatch and object graph reconstruction
