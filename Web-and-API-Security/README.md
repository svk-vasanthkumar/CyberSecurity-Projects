# Web & API Security

## What This Domain Covers

Web & API Security focuses on protecting web applications, APIs, and the HTTP protocol layer from exploitation. This includes security header analysis, API vulnerability scanning, input validation, rate limiting, and OWASP Top 10 defense.

## Cybersecurity Skills Covered

- HTTP security header auditing and grading
- REST API vulnerability discovery (OWASP API Security Top 10)
- SQL injection, XSS, IDOR, and authentication bypass detection
- Rate limiting and DoS mitigation strategies
- API authentication and session management testing
- Web application firewall (WAF) rule evaluation

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [http-headers-scanner](./http-headers-scanner) | Python, httpx, Rich | Grades HTTP security headers A through F using a weighted-rubric model |
| [api-security-scanner](./api-security-scanner) | Python, FastAPI, React | Full-stack API vulnerability scanner targeting the OWASP API Security Top 10 |
| [api-rate-limiter](./api-rate-limiter) | Python, FastAPI | Enterprise rate limiting library using HTTP 420 with sliding window, token bucket, and fixed window algorithms |

## Secondary Domains Represented

- **Security Automation & Orchestration** — api-rate-limiter automates request throttling and policy enforcement
