# Identity, Authentication & Access Management

## What This Domain Covers

Identity, Authentication & Access Management (IAM) focuses on verifying user identity, managing credentials, and enforcing access policies. This includes password storage, multi-factor authentication, session management, and secret lifecycle automation.

## Cybersecurity Skills Covered

- Secure password storage with Argon2id and AES-256-GCM
- Credential rotation and secrets management across providers
- Atomic and concurrent-safe vault operations
- WebAuthn/Passkey and FIDO2 authentication flows
- Session management and token rotation
- Policy-enforced access control and RBAC

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [password-manager](./password-manager) | Python, Argon2id, AES-256-GCM | Encrypted CLI password manager with atomic writes, master password rotation, and secure password generation |
| [credential-rotation-enforcer](./credential-rotation-enforcer) | Crystal, PostgreSQL, Telegram | Credential rotation enforcer with compile-time policy DSL, tamper-evident audit log, and multi-provider rotators |

## Secondary Domains Represented

- **Cryptography & Data Protection** — password-manager and credential-rotation-enforcer both rely on AEAD encryption, Argon2id KDF, and HMAC-based integrity
