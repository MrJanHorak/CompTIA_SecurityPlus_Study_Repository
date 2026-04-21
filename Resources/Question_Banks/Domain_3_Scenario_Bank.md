# Domain 3 Scenario Bank (Security Architecture)

1. A company wants remote users to access apps without broad network reachability. Which model best fits?
   Answer: ZTNA.
   Rationale: App-specific, context-aware access over full-network VPN exposure.

2. Internet-facing web app sits on same subnet as internal database servers. What is the first architecture fix?
   Answer: Segment into DMZ and protected internal network tiers.
   Rationale: Reduces blast radius and direct pivot risk.

3. A critical app must stay available during a single data center outage. What design requirement applies?
   Answer: Geographic redundancy/failover.
   Rationale: Single-site dependency violates availability goals.

4. Team stores API keys in source code repository. Which control is most urgent?
   Answer: Secret management with key rotation.
   Rationale: Hardcoded secrets create persistent exposure.

5. Which control best protects data in transit between services?
   Answer: TLS with validated certificates.
   Rationale: Provides confidentiality and integrity during transfer.

6. Why might differential backups be chosen over incremental backups?
   Answer: Faster restore time.
   Rationale: Restore uses full plus latest differential, not long chain.

7. A design includes one firewall and no internal segmentation. Which principle is weakly implemented?
   Answer: Defense in depth.
   Rationale: Single perimeter control is insufficient.

8. Which metric is violated if maximum tolerable downtime is 2 hours but service returns in 5?
   Answer: RTO.
   Rationale: Recovery duration exceeded objective.

9. An app needs protection from SQL injection and XSS with minimal code changes. Which control is immediately helpful?
   Answer: WAF.
   Rationale: Provides virtual patching and request filtering.

10. Why is shared responsibility important in cloud architecture questions?
    Answer: Security duties differ by service model.
    Rationale: Misunderstanding responsibility leads to control gaps.

11. A design requires public app access while protecting core systems. Which pattern is best?
    Answer: Tiered architecture with DMZ and internal segmentation.
    Rationale: Separates exposure layers and reduces pivot risk.

12. Which architecture choice best supports least privilege for administrators?
    Answer: Bastion/jump host with audited privileged sessions.
    Rationale: Centralizes and monitors high-risk administrative access.

13. Why is microsegmentation effective in breach scenarios?
    Answer: It constrains east-west traffic between workloads.
    Rationale: Limits attacker lateral movement.

14. Which design decision most improves resilience to regional cloud outage?
    Answer: Multi-region deployment with tested failover.
    Rationale: Single-region dependency is a major availability risk.

15. Which control best protects secrets used by CI/CD pipelines?
    Answer: Centralized secret vault with rotation policies.
    Rationale: Reduces hardcoded and long-lived secret exposure.

16. What is a common distractor in architecture questions?
    Answer: Highest-security option that breaks business availability requirements.
    Rationale: Security+ expects balanced risk and operability decisions.

17. Which data state is most vulnerable to memory scraping attacks?
    Answer: Data in use.
    Rationale: Data is actively processed in memory at that time.

18. Why should architecture include centralized logging requirements?
    Answer: Detection and response depend on consistent telemetry.
    Rationale: Operational visibility is a design requirement, not an afterthought.

19. Which design choice most directly reduces single point of failure?
    Answer: Redundant components with health-checked failover.
    Rationale: Availability depends on graceful component substitution.

20. When choosing backup strategy, which requirement drives type selection most?
    Answer: RTO/RPO constraints.
    Rationale: Recovery objectives determine acceptable backup/restore tradeoffs.

21. A team wants faster restore at cost of larger backup sizes. Which type fits?
    Answer: Differential backups.
    Rationale: Faster restore chain than incremental.

22. Which control best protects APIs from automated abuse?
    Answer: Strong auth plus rate limiting and input validation.
    Rationale: Reduces unauthorized and abusive request patterns.

23. What is the role of a WAF in secure architecture?
    Answer: Layer 7 filtering and virtual patching.
    Rationale: Helps block common web attacks without immediate code change.

24. Why should architecture diagrams include trust boundaries?
    Answer: They define where control enforcement changes.
    Rationale: Clear boundaries guide policy and segmentation decisions.

25. Which model best reflects zero trust architecture behavior?
    Answer: Continuous verification with context-aware policy checks.
    Rationale: Access decisions are dynamic, not one-time perimeter checks.

26. Which cloud control responsibility usually remains with customer across models?
    Answer: Identity and access governance.
    Rationale: Access policy and account hygiene remain customer obligations.

27. Why is immutable backup storage valuable in ransomware scenarios?
    Answer: Prevents tampering/encryption of recovery data.
    Rationale: Ensures restore integrity under active attacker conditions.

28. Which architectural choice best limits developer access to production secrets?
    Answer: Role-segregated secret access with approval workflows.
    Rationale: Enforces least privilege and separation of duties.

29. A resilience design restores service quickly but loses 24 hours of data. Which metric likely failed?
    Answer: RPO.
    Rationale: Data loss window exceeded objective.

30. Which output best validates architecture decisions post-implementation?
    Answer: Tested controls with measurable security and recovery outcomes.
    Rationale: Architecture quality is proven through verification exercises.

Back to [Question Banks](README.md)
