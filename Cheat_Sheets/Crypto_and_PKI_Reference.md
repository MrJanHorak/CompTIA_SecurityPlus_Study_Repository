# Cheat Sheet: Crypto and PKI Reference

## Algorithm Quick Reference

| Category       | Examples               | Security Note                          |
| -------------- | ---------------------- | -------------------------------------- |
| Symmetric      | AES                    | Fast for bulk encryption               |
| Asymmetric     | RSA, ECC               | Key exchange and signatures            |
| Hashing        | SHA-256, SHA-3         | Integrity and password storage support |
| Key stretching | bcrypt, PBKDF2, Argon2 | Slow hashes for password resistance    |

## PKI Components

| Component | Purpose                           |
| --------- | --------------------------------- |
| CA        | Issues certificates               |
| RA        | Performs identity validation      |
| CRL       | Lists revoked certificates        |
| OCSP      | Real-time revocation status check |
| CSR       | Certificate signing request       |

## Common Mistakes

- Confusing encryption with hashing
- Using deprecated protocols/ciphers
- Ignoring certificate expiration and revocation checks

---

Cross-reference: [Domain 1.3](../Domain_1_General_Security_Concepts/1.3_Cryptography_and_PKI.md)
