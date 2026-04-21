# Lab 05 — IAM and Least Privilege

## Objective

Apply least-privilege principles and verify access control hygiene.

SY0-701 objective alignment: 4.3 IAM and Operational Security, 5.2 Program Management

## Prerequisites

- Three sample business roles (for example: HR, Finance, IT Admin)
- Access policy editor in lab environment
- MFA-capable identity platform

## Step-by-Step Procedure

1. Build role catalog:
   - Define required systems and operations per role.
2. Baseline review:
   - Identify over-privileged permissions and shared accounts.
3. Implement controls:
   - Enforce MFA for privileged and remote roles.
   - Remove standing admin rights where possible.
   - Add just-in-time elevation workflow for admin tasks.
4. Access review simulation:
   - Run quarterly-style review for one role.
   - Document revoked, retained, and exception permissions.

## Validation Checkpoints

- No shared admin account usage remains
- Every role has a documented business justification
- Exceptions include owner, reason, and expiry date

## Tasks

1. Define three role-based access profiles for a small organization.
2. Enforce MFA for privileged and remote access roles.
3. Identify and remove one excessive permission per role.
4. Configure a periodic access review checklist.

## Troubleshooting Tips

- Over-removal risk: validate critical workflows with business owner before finalizing.
- MFA friction complaints: apply conditional access tuning without removing strong auth.
- Review fatigue: automate evidence collection for recurring audits.

## Deliverable

- Role matrix (role -> allowed resources -> justification)
- Access review report with remediation actions

## Reflection Prompt

Which permission removal produced the highest risk reduction with lowest operational impact?

---

Previous: [Lab 04](Lab_04_Incident_Response_Tabletop.md) | Back to [Labs Overview](README.md)
