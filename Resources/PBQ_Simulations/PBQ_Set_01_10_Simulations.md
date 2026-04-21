# PBQ Set 01 - 10 Security+ Simulations

Each simulation includes objective focus, prompt, expected action, and rubric.

## PBQ 1 - Suspicious Login Burst

Objective focus: 4.2, 4.1
Prompt: SIEM shows 30 failed logins then one success for a privileged account from unusual region.
Expected action: Validate compromise, scope account use, contain account, start incident timeline.
Rubric:

- Detection and triage logic (0-2)
- Containment choice (0-2)
- Documentation completeness (0-2)

## PBQ 2 - ACL Hardening

Objective focus: 3.1, 2.3
Prompt: Given permissive ACL entries, choose least-privilege rule set preserving required app flow.
Expected action: Remove broad any/any rules; allow only required source, destination, port, protocol.
Rubric:

- Correct rule minimization (0-2)
- Business continuity preserved (0-2)
- Security rationale (0-2)

## PBQ 3 - Vulnerability Prioritization

Objective focus: 2.2, 2.3
Prompt: Rank five findings with mixed CVSS, exposure, and asset criticality.
Expected action: Prioritize internet-facing critical business systems first.
Rubric:

- Prioritization order (0-2)
- Use of business context (0-2)
- Remediation plan quality (0-2)

## PBQ 4 - Phishing Triage

Objective focus: 2.1, 4.2
Prompt: Analyze suspicious email headers, URL, and attachment hash indicators.
Expected action: Extract IOCs, classify risk, contain affected mailbox/endpoints if needed.
Rubric:

- IOC extraction accuracy (0-2)
- Disposition quality (0-2)
- Response communication (0-2)

## PBQ 5 - Certificate Trust Failure

Objective focus: 1.3
Prompt: Client rejects service cert after key compromise event.
Expected action: Revoke compromised cert, validate OCSP/CRL checks, reissue cert properly.
Rubric:

- Revocation logic (0-2)
- PKI workflow correctness (0-2)
- Service restoration safety (0-2)

## PBQ 6 - IAM Role Cleanup

Objective focus: 4.3, 5.2
Prompt: Review three roles with excessive permissions and shared admin account usage.
Expected action: Remove over-privileged rights, enforce unique IDs, require MFA.
Rubric:

- Least privilege improvements (0-2)
- Accountability improvements (0-2)
- Operational viability (0-2)

## PBQ 7 - Incident Phase Ordering

Objective focus: 4.1
Prompt: Sort mixed response actions into NIST lifecycle phases.
Expected action: Correctly map tasks to Preparation, Detection/Analysis, Containment, Eradication/Recovery, Lessons Learned.
Rubric:

- Phase mapping accuracy (0-2)
- Sequence quality (0-2)
- Explanation quality (0-2)

## PBQ 8 - Backup and DR Tradeoff

Objective focus: 3.3, 5.1
Prompt: Choose backup strategy and DR target for strict RTO and moderate RPO.
Expected action: Select strategy aligning fastest restore with acceptable data loss.
Rubric:

- RTO/RPO interpretation (0-2)
- Backup choice fit (0-2)
- Cost-risk reasoning (0-2)

## PBQ 9 - Automation Guardrails

Objective focus: 4.4
Prompt: Improve a SOAR playbook causing false positive account lockouts.
Expected action: Add confidence thresholds, secondary validation, human approval for high impact.
Rubric:

- Guardrail design (0-2)
- False positive reduction strategy (0-2)
- Auditability improvements (0-2)

## PBQ 10 - Vendor Risk Review

Objective focus: 5.3, 5.1
Prompt: Assess third-party contract missing security clauses.
Expected action: Add breach SLA, right-to-audit, data retention, subprocessor transparency.
Rubric:

- Clause selection quality (0-2)
- Risk reasoning (0-2)
- Governance alignment (0-2)

## Self-Scoring Summary Template

| PBQ | Score (0-6) | Weak Area | Remediation File |
| --- | ----------- | --------- | ---------------- |
| 1   |             |           |                  |
| 2   |             |           |                  |
| 3   |             |           |                  |
| 4   |             |           |                  |
| 5   |             |           |                  |
| 6   |             |           |                  |
| 7   |             |           |                  |
| 8   |             |           |                  |
| 9   |             |           |                  |
| 10  |             |           |                  |

Back to [PBQ Simulations](README.md)
