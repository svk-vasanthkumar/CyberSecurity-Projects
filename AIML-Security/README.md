# AI & Machine Learning Security

## What This Domain Covers

AI & Machine Learning Security focuses on securing AI/ML systems and using AI/ML to enhance cybersecurity. This includes prompt injection defense, ML-based anomaly detection, model integrity, and adversarial robustness.

## Cybersecurity Skills Covered

- Prompt injection detection and LLM output filtering
- Provenance fencing and nonce-based context isolation
- Tool authorization and taint propagation for AI agents
- ML ensemble threat detection (autoencoders, random forests, isolation forests)
- ONNX model export and CPU-optimized inference
- Real-time WebSocket alerting for AI-classified threats

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [ai-threat-detection](./ai-threat-detection) | Python, FastAPI, PyTorch, ONNX Runtime, React | AI-powered threat detection engine analyzing nginx logs using a 3-model ML ensemble |
| [prompt-injection-firewall](./prompt-injection-firewall) | Python, FastAPI, React | Prompt injection firewall with five enforcement layers including nonce fencing, tool authorization, and egress secret matching |

## Secondary Domains Represented

- **SOC, SIEM & Security Monitoring** — ai-threat-detection dispatches alerts to SIEM backends and integrates with log correlation pipelines
- **Web & API Security** — prompt-injection-firewall ships an OpenAI-compatible proxy for protecting LLM-backed APIs
