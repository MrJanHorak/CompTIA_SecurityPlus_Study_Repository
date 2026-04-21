# Domain 2 Scenario Bank (Threats, Vulnerabilities, and Mitigations)

1. A finance user reports a fake invoice email from a known vendor domain with slight spelling changes. What attack type is most likely?
   Answer: Spear phishing with domain spoofing/typosquatting.
   Rationale: Targeted lure with impersonation indicators.

2. A scanner reports critical vulnerabilities on a decommissioned host. What is the best first action?
   Answer: Validate asset inventory status and confirm host scope.
   Rationale: Avoid wasting remediation on stale assets/false scope.

3. A vulnerability has CVSS 6.5 on a public-facing payment API. Another has CVSS 8.8 on an internal lab VM. Which gets priority?
   Answer: Public-facing payment API issue.
   Rationale: Business exposure and attack surface can outweigh score alone.

4. A service account starts launching interactive PowerShell sessions. What does this indicate?
   Answer: Possible credential compromise or misuse.
   Rationale: Service accounts should not perform interactive admin behavior.

5. A team patched a critical CVE but did not rescan. What step is missing?
   Answer: Verification/rescan.
   Rationale: Closure must be validated, not assumed.

6. Users receive MFA fatigue prompts repeatedly. What attack is likely?
   Answer: MFA prompt bombing.
   Rationale: Repeated prompts aim to force user approval.

7. Endpoint controls block unknown executables, but attackers still execute native system tools for recon. What technique is this?
   Answer: Living-off-the-land.
   Rationale: Abuse of legitimate binaries bypasses simplistic allow/deny controls.

8. Which mitigation best limits lateral movement after one endpoint compromise?
   Answer: Network segmentation and strict east-west controls.
   Rationale: Segmentation contains spread.

9. A new vendor update introduced malware into internal systems. What category best describes this?
   Answer: Supply chain compromise.
   Rationale: Trusted third-party channel used as attack vector.

10. Which output best demonstrates vulnerability management maturity over time?
    Answer: Declining critical open findings and improved remediation SLA adherence.
    Rationale: Trend-based metrics show program effectiveness.

11. A host repeatedly reaches known malicious domains but endpoint scan is clean. What should happen next?
    Answer: Isolate host and perform deeper behavioral analysis.
    Rationale: Network IOC evidence can precede malware signature detection.

12. Which mitigation best addresses credential stuffing risk?
    Answer: MFA with rate limiting and anomaly detection.
    Rationale: Stuffing relies on password reuse and automated attempts.

13. What is the best first step after discovering externally exposed RDP on critical systems?
    Answer: Restrict access immediately and enforce secure remote access controls.
    Rationale: Reduce active attack surface first.

14. Why can vulnerability scans miss real risk?
    Answer: Misconfiguration, blind spots, and context-free scoring.
    Rationale: Findings require validation with asset and business context.

15. A vulnerability has no patch yet. Which response is most appropriate?
    Answer: Apply compensating controls and monitor exploitation indicators.
    Rationale: Mitigate exposure while awaiting permanent fix.

16. Which control helps prevent macro-based malware execution?
    Answer: Macro restrictions and application control policy.
    Rationale: Limits common initial execution path.

17. Why is asset inventory foundational to vulnerability management?
    Answer: You cannot secure or scan unknown assets.
    Rationale: Discovery quality determines program coverage.

18. A finding exists on a legacy system that cannot be patched. What governance action is required?
    Answer: Document risk acceptance with compensating controls and review date.
    Rationale: Unpatched risk needs formal ownership and monitoring.

19. Which scenario most indicates insider threat rather than external phishing?
    Answer: Legitimate user account exfiltrating unusual internal data volume.
    Rationale: Authenticated misuse pattern suggests insider activity.

20. What is the strongest remediation evidence?
    Answer: Verified closure in rescan plus monitoring stability.
    Rationale: Both scan and telemetry should show reduced risk.

21. Which attack is best reduced by immutable backups and segmentation?
    Answer: Ransomware impact propagation.
    Rationale: Limits spread and supports reliable recovery.

22. A CVE is critical but exploitability is low in your environment. What should influence final priority?
    Answer: Exposure path and compensating controls.
    Rationale: Practical exploitability matters in real risk decisions.

23. What improves scan quality in enterprise environments?
    Answer: Credentialed scans with accurate asset tagging.
    Rationale: Deeper host visibility and context-aware prioritization.

24. Which indicator is common in command-and-control activity?
    Answer: Periodic outbound beacons to rare domains.
    Rationale: C2 often uses recurring communication patterns.

25. Why is patching alone insufficient as a strategy?
    Answer: Configuration weaknesses and identity abuse can remain.
    Rationale: Security requires layered controls beyond patching.

26. What is the best action when a scanner plugin appears to produce false positives?
    Answer: Validate manually and tune scanner policy.
    Rationale: Accuracy improves when noisy checks are verified and adjusted.

27. Which mitigation best addresses lateral movement by compromised credentials?
    Answer: MFA, segmented access paths, and privileged session controls.
    Rationale: Reduces credential replay value and movement range.

28. Which result indicates hardening success on endpoints?
    Answer: Reduced attack surface and blocked unauthorized execution attempts.
    Rationale: Hardening should constrain exploitable behaviors.

29. A user enables local admin on all endpoints for convenience. Which risk rises most?
    Answer: Privilege escalation and malware spread.
    Rationale: Broad admin rights increase blast radius.

30. What should be updated after major remediation campaign completion?
    Answer: Baselines, runbooks, and risk register.
    Rationale: Program documentation must reflect current security state.

Back to [Question Banks](README.md)
