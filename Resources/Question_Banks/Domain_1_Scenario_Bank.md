# Domain 1 Scenario Bank (General Security Concepts)

## Questions with Rationales

1. A manager asks for one control that prevents unauthorized access and one that detects abuse after access is granted. What should you recommend first?
   Answer: Preventive control such as MFA and detective control such as SIEM alerting on abnormal access patterns.
   Rationale: This pairs pre-event prevention with post-event detection.

2. A team uses passwords only and frequently shares service credentials. Which principle is most violated?
   Answer: Least privilege and accountability.
   Rationale: Shared credentials break traceability and over-permission raises risk.

3. A system owner asks whether hashing can replace encryption for stored customer records. Is that correct?
   Answer: No.
   Rationale: Hashing is one-way and supports integrity, not confidentiality.

4. A certificate is valid but should no longer be trusted due to key compromise. What mechanism should systems check?
   Answer: OCSP or CRL.
   Rationale: Revocation status invalidates previously issued certs.

5. A security architect proposes RSA for full-disk encryption of a large data store. Why is this suboptimal?
   Answer: Asymmetric algorithms are computationally expensive for bulk encryption.
   Rationale: Symmetric encryption is used for data-at-rest speed and efficiency.

6. Which document type should define mandatory password length and complexity requirements?
   Answer: Standard.
   Rationale: Policies define intent; standards define mandatory specifics.

7. A team adds camera signage but no actual monitoring. Which control category best fits signage?
   Answer: Deterrent control.
   Rationale: It discourages behavior but does not directly prevent or detect strongly.

8. Which CIA component is primarily impacted by unauthorized data modification?
   Answer: Integrity.
   Rationale: Modification undermines trustworthiness of data.

9. A user denies sending a signed transaction. Which security property addresses this dispute?
   Answer: Non-repudiation.
   Rationale: Digital signatures provide proof of origin and action.

10. During design, leadership asks for controls that still work if one fails. Which approach best matches?
    Answer: Defense in depth.
    Rationale: Layered controls reduce single-point control failure risk.

11. A breach scenario asks for the first document to check for mandatory control requirements. Which is correct?
    Answer: Standard.
    Rationale: Standards define mandatory technical requirements.

12. An answer option says "improve security culture" while another specifies MFA rollout. Which is usually stronger in an exam scenario?
    Answer: MFA rollout.
    Rationale: Concrete control action beats vague strategic wording.

13. If two controls appear equal, which tie-breaker is strongest?
    Answer: Verifiable risk reduction with audit evidence.
    Rationale: Measurable and defensible outcomes are preferred.

14. A question asks which principle limits blast radius after initial compromise. What is best?
    Answer: Least privilege.
    Rationale: Smaller permissions reduce attacker movement options.

15. Which choice most directly supports non-repudiation in transactions?
    Answer: Digital signatures.
    Rationale: Signature binding to sender identity prevents denial claims.

16. Which control category includes onboarding and offboarding procedures?
    Answer: Administrative controls.
    Rationale: Process and governance controls are administrative.

17. What is the best immediate integrity check after suspected file tampering?
    Answer: Compare known-good hash values.
    Rationale: Hash mismatch signals unauthorized modification.

18. Which answer best reflects confidentiality protection for stored data?
    Answer: Encryption at rest with key management.
    Rationale: Confidentiality at rest requires cryptographic protection and key control.

19. A question asks to discourage unauthorized physical entry without direct blocking. Which control fits?
    Answer: Deterrent control.
    Rationale: Deterrent influences behavior but does not guarantee prevention.

20. Which statement best separates authentication and authorization?
    Answer: Authentication proves identity; authorization grants allowed actions.
    Rationale: Identity proof and permissions are distinct processes.

21. Why is defense in depth stronger than single-control design?
    Answer: It tolerates partial control failure.
    Rationale: Layered controls reduce single-point dependence.

22. Which is the best policy lifecycle action after repeated exceptions?
    Answer: Policy review and standard refinement.
    Rationale: Frequent exceptions indicate policy-design mismatch.

23. A prompt asks for trust verification before granting access each session. Which model fits?
    Answer: Zero Trust principles.
    Rationale: Continuous verification is core Zero Trust behavior.

24. Which option improves accountability in privileged operations?
    Answer: Unique admin accounts and audit logging.
    Rationale: Shared credentials destroy user-level traceability.

25. Which property is primarily preserved by backups?
    Answer: Availability.
    Rationale: Backups support recovery and service restoration.

26. Which answer best addresses authenticity of received messages?
    Answer: Signature validation with trusted certificate chain.
    Rationale: Validated signatures prove message origin.

27. Which is a strong corrective control example?
    Answer: Restore from clean backup after malware eradication.
    Rationale: Corrective controls return systems to safe state.

28. A question asks for risk reduction with minimal operational disruption. Which strategy is preferred?
    Answer: Phased control rollout with verification checkpoints.
    Rationale: Reduces change risk while improving security.

29. What is most likely to appear as a distractor in foundation questions?
    Answer: Broad strategic statements with no implementable action.
    Rationale: Security+ favors actionable control decisions.

30. Which output best proves control effectiveness over time?
    Answer: Trend metrics with documented improvement.
    Rationale: Sustained measurable outcomes validate control maturity.

Back to [Question Banks](README.md)
