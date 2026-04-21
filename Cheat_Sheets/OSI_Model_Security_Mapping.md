# Cheat Sheet: OSI Model Security Mapping

## Layer-by-Layer Threat and Control View

| Layer | Name         | Common Attacks               | Defensive Controls                   |
| ----- | ------------ | ---------------------------- | ------------------------------------ |
| 7     | Application  | SQLi, XSS, command injection | WAF, secure coding, input validation |
| 6     | Presentation | SSL stripping, weak ciphers  | TLS enforcement, cipher hardening    |
| 5     | Session      | Session hijacking            | Secure cookies, token rotation       |
| 4     | Transport    | SYN flood, port scanning     | Stateful firewall, rate limiting     |
| 3     | Network      | IP spoofing, routing attacks | ACLs, anti-spoofing, segmentation    |
| 2     | Data Link    | ARP poisoning, MAC flooding  | Port security, DHCP snooping, DAI    |
| 1     | Physical     | Wire tapping, jamming, theft | Locks, surveillance, shielding       |

## Exam Use

- Troubleshooting: Map symptom to likely layer.
- Architecture: Place control at the right layer.
- Threat analysis: Identify where detection should occur.

---

Cross-reference: [Domain 3.1](../Domain_3_Security_Architecture/3.1_Secure_Infrastructure_Design.md)
