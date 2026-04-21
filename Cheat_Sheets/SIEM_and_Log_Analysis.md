# Cheat Sheet: SIEM and Log Analysis

## Log Analysis Sequence

1. Confirm alert relevance
2. Determine impacted entities
3. Validate timeline and sequence
4. Enrich with threat intelligence and asset context
5. Decide: close, monitor, escalate, or contain

## Common High-Signal Indicators

| Indicator                           | Why It Matters                         |
| ----------------------------------- | -------------------------------------- |
| Multiple failed logins then success | Brute force/password spray pattern     |
| New admin account creation          | Privilege escalation possibility       |
| Service account interactive login   | Potential credential misuse            |
| Rare process spawning PowerShell    | Potential living-off-the-land behavior |
| Large outbound transfer             | Potential exfiltration                 |

## SOC Documentation Standard

- What was observed
- Why it matters
- What action was taken
- What evidence supports the decision

---

Cross-reference: [Domain 4.2](../Domain_4_Security_Operations/4.2_Monitoring_Detection_and_Analysis.md)
