# Lab 03 — Phishing Triage Playbook

## Objective

Create a repeatable process for evaluating suspicious emails.

SY0-701 objective alignment: 2.1 Threat vectors, 4.2 Detection and analysis

## Prerequisites

- Sample phishing and benign emails in a sandbox mailbox
- Access to approved reputation sources
- Isolated analysis workflow

## Step-by-Step Procedure

1. Intake:
   - Record reporter, message time, and mailbox context.
2. Header review:
   - Check sender domain, reply-to mismatch, and authentication results.
3. URL handling:
   - Extract links without clicking directly.
   - Analyze destination domain age/reputation and URL structure.
4. Attachment analysis:
   - Hash file and check reputation.
   - Flag risky file types and macro-enabled documents.
5. Classification:
   - Benign, suspicious, or malicious.
6. Response:
   - Quarantine/purge message if needed.
   - Notify users and create SOC case note.

## Validation Checkpoints

- At least three IOCs extracted and documented
- Disposition includes clear evidence-based rationale
- Recommended next actions are operationally safe

## Tasks

1. Capture sender, subject, and header indicators.
2. Extract and inspect URLs safely.
3. Hash attachments and check reputation in approved sources.
4. Determine disposition: malicious, suspicious, or benign.
5. Document response action and user communication guidance.

## Troubleshooting Tips

- Unclear verdict: request additional telemetry from endpoint or proxy logs.
- Conflicting signals: prioritize indicators tied to attacker infrastructure.
- Excessive time per case: standardize checklist and evidence template.

## Deliverable

- One-page triage checklist
- Sample IOC report format

## Reflection Prompt

What single indicator most influenced your final verdict, and why?

---

Previous: [Lab 02](Lab_02_Vulnerability_Management_Cycle.md) | Next: [Lab 04](Lab_04_Incident_Response_Tabletop.md)
