# Domain 4 Scenario Bank (Security Operations)

1. SOC receives alert: multiple failed logins then successful admin login from unusual region. First action?
   Answer: Validate account compromise and begin containment.
   Rationale: High-confidence account takeover pattern.

2. During incident response, system owner asks to delay isolation to preserve uptime. What should guide decision?
   Answer: Severity, business impact, and approved IR policy.
   Rationale: Balance containment urgency with critical operations.

3. Which evidence should be collected first from a live compromised host?
   Answer: Volatile data where appropriate (running processes, active connections).
   Rationale: Volatile artifacts are lost after shutdown/reboot.

4. A SIEM rule triggers too often with low-quality alerts. What should be tuned first?
   Answer: Detection logic and enrichment criteria.
   Rationale: Reduce false positives while preserving detection fidelity.

5. Which IAM action best reduces privilege abuse risk?
   Answer: Just-in-time privileged access with approval workflow.
   Rationale: Limits standing admin exposure.

6. A playbook auto-disables accounts based on one weak signal and causes business outage. What failed?
   Answer: Automation guardrails and human approval thresholds.
   Rationale: High-impact actions need confidence checks.

7. What documentation is required when closing an alert as benign?
   Answer: Evidence, rationale, and closure decision path.
   Rationale: Auditability and repeatability.

8. Which metric indicates SOC response speed improvement?
   Answer: Lower MTTR over comparable incident types.
   Rationale: Direct response efficiency measure.

9. A known IOC appears in proxy logs on three hosts. What is the next best step?
   Answer: Scope affected assets and isolate impacted systems.
   Rationale: Contain spread before full eradication.

10. What is the most valuable output of lessons learned?
    Answer: Actionable control improvements with owners and deadlines.
    Rationale: Converts incident into measurable risk reduction.

11. A detection rule triggers on every admin login and floods analysts. What should be changed first?
    Answer: Add context-based filtering and enrichment.
    Rationale: Improve precision before scaling response actions.

12. Which action is most appropriate after identifying likely compromised endpoint credentials?
    Answer: Reset credentials and investigate scope of credential use.
    Rationale: Credential abuse may affect multiple systems.

13. Why is an incident timeline essential?
    Answer: It supports root-cause reconstruction and defensible reporting.
    Rationale: Sequence evidence is critical for lessons learned and audits.

14. Which data source often confirms suspicious outbound C2 behavior?
    Answer: Proxy/DNS/firewall egress logs.
    Rationale: C2 commonly appears in outbound network telemetry.

15. What should happen before automatic account disablement in high-impact environments?
    Answer: Confidence threshold check and/or human approval gate.
    Rationale: Prevents false-positive business outages.

16. Which IAM control most reduces standing privileged risk?
    Answer: Just-in-time elevation with session auditing.
    Rationale: Limits always-on admin exposure.

17. What is a common chain-of-custody mistake?
    Answer: Untracked evidence handling transfers.
    Rationale: Weak custody records undermine legal defensibility.

18. Which metric pairing best reflects SOC quality improvement?
    Answer: Lower MTTR and lower false-positive rate.
    Rationale: Faster and more accurate operations.

19. Why should SIEM alerts be mapped to asset criticality?
    Answer: Prioritization should reflect business impact, not volume alone.
    Rationale: Critical assets demand faster response.

20. During containment, why avoid immediate full system wipe in all cases?
    Answer: It may destroy forensic evidence and delay root-cause understanding.
    Rationale: Evidence preservation matters.

21. Which operational artifact should be updated after a major incident?
    Answer: Playbooks and escalation runbooks.
    Rationale: Institutional learning must be embedded in response processes.

22. What best differentiates monitoring from detection?
    Answer: Monitoring collects/observes; detection identifies suspicious patterns.
    Rationale: Detection is analysis-driven outcome of monitoring telemetry.

23. Which event pattern often indicates password spraying rather than brute force single-account attacks?
    Answer: Few attempts across many accounts.
    Rationale: Spraying avoids lockouts by distributing attempts.

24. What is the safest immediate step when ransomware encryption is active on one host?
    Answer: Isolate affected host from network.
    Rationale: Containment limits propagation.

25. Which practice improves alert closure quality?
    Answer: Required evidence fields and closure rationale template.
    Rationale: Standardized documentation reduces analyst inconsistency.

26. Why are baseline behavior profiles useful?
    Answer: They improve anomaly detection confidence.
    Rationale: Deviations are interpreted relative to known-normal behavior.

27. Which control best protects privileged access during emergencies?
    Answer: Controlled break-glass accounts with logging and post-use review.
    Rationale: Emergency access should still remain auditable.

28. A SOC team automates IOC enrichment but not ticket creation. What capability is still missing?
    Answer: Full orchestration across workflow tools.
    Rationale: Enrichment alone does not complete response workflow integration.

29. Which response sequencing is most defensible?
    Answer: Validate -> scope -> contain -> eradicate -> recover -> review.
    Rationale: Aligns with established incident response lifecycle.

30. What should trigger escalation from analyst to incident commander?
    Answer: Confirmed high-severity compromise or business-critical impact.
    Rationale: Leadership coordination is required for major incidents.

Back to [Question Banks](README.md)
