# Cryptography & Data Protection

## What This Domain Covers

Cryptography & Data Protection focuses on the mathematical and implementation foundations of securing information. This includes encryption, hashing, key management, encoding analysis, and secure communication protocols.

## Cybersecurity Skills Covered

- Symmetric and asymmetric encryption (AES, RSA, ECDSA)
- Key derivation functions (Argon2id, PBKDF2)
- Authenticated encryption and integrity checking (AEAD, GCM)
- Hash algorithm identification and strength testing
- Secure key storage and Hardware Security Module (HSM) emulation
- Encoding/decoding and obfuscation analysis for security testing

## Projects in This Domain

| Project | Technologies | Description |
|---------|-------------|-------------|
| [base64-tool](./base64-tool) | Python, Rich | Multi-format encoding/decoding CLI with recursive layer detection for WAF bypass analysis |
| [caesar-cipher](./caesar-cipher) | Python, Rich | Caesar cipher encryption, decryption, and brute-force cracking with frequency analysis |
| [hash-cracker](./hash-cracker) | C++23, mmap | Multi-threaded hash cracking with dictionary, brute-force, and rule-based mutation attacks |
| [hash-identifier](./hash-identifier) | Python | Identify ~30 hash formats by prefix, length, and character set |
| [encrypted-p2p-chat](./encrypted-p2p-chat) | Python, FastAPI, SolidJS | End-to-end encrypted P2P chat using Signal Protocol (Double Ratchet + X3DH) and WebAuthn |
| [hsm-emulator](./hsm-emulator) | Zig, PKCS#11 | Software HSM emulator compiling to a real Cryptoki shared object with encrypted-at-rest key storage |

## Secondary Domains Represented

- **Identity, Authentication & Access Management** — encrypted-p2p-chat implements WebAuthn/Passkey authentication
- **Privacy & Data Security** — base64-tool and caesar-cipher analyze obfuscation patterns used in data exfiltration
