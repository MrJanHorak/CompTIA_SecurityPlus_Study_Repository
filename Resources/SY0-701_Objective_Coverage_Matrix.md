# SY0-701 Objective Coverage Matrix

Use this file as the master tracker to verify complete coverage and identify weak areas.

Status legend:

- Complete: Objective has explanation, examples, and recall checks
- Partial: Objective exists but needs deeper examples or scenarios
- Missing: Objective not yet covered

## Domain 1.0 - General Security Concepts (12%)

| Objective                            | Coverage File                                                                 | Status  | Notes                                                |
| ------------------------------------ | ----------------------------------------------------------------------------- | ------- | ---------------------------------------------------- |
| 1.1 Security Fundamentals            | ../Domain_1_General_Security_Concepts/1.1_Security_Fundamentals.md            | Partial | Expand with more scenario comparisons                |
| 1.2 Security Controls and Frameworks | ../Domain_1_General_Security_Concepts/1.2_Security_Controls_and_Frameworks.md | Partial | Add mapping examples by business context             |
| 1.3 Cryptography and PKI             | ../Domain_1_General_Security_Concepts/1.3_Cryptography_and_PKI.md             | Partial | Add protocol negotiation and cert lifecycle examples |

## Domain 2.0 - Threats, Vulnerabilities, and Mitigations (22%)

| Objective                                   | Coverage File                                                                                      | Status  | Notes                                     |
| ------------------------------------------- | -------------------------------------------------------------------------------------------------- | ------- | ----------------------------------------- |
| 2.1 Threat Actors and Attack Vectors        | ../Domain_2_Threats_Vulnerabilities_and_Mitigations/2.1_Threat_Actors_and_Attack_Vectors.md        | Partial | Add ATT&CK-oriented mapping examples      |
| 2.2 Vulnerability Management and Assessment | ../Domain_2_Threats_Vulnerabilities_and_Mitigations/2.2_Vulnerability_Management_and_Assessment.md | Partial | Add more prioritization case studies      |
| 2.3 Mitigation and Hardening                | ../Domain_2_Threats_Vulnerabilities_and_Mitigations/2.3_Mitigation_and_Hardening.md                | Partial | Add baseline templates and exception flow |

## Domain 3.0 - Security Architecture (18%)

| Objective                                | Coverage File                                                                 | Status  | Notes                                      |
| ---------------------------------------- | ----------------------------------------------------------------------------- | ------- | ------------------------------------------ |
| 3.1 Secure Infrastructure Design         | ../Domain_3_Security_Architecture/3.1_Secure_Infrastructure_Design.md         | Partial | Add cloud-native architecture tradeoffs    |
| 3.2 Secure Data and Application Concepts | ../Domain_3_Security_Architecture/3.2_Secure_Data_and_Application_Concepts.md | Partial | Add SDLC security checkpoints and examples |
| 3.3 Resilience and Recovery              | ../Domain_3_Security_Architecture/3.3_Resilience_and_Recovery.md              | Partial | Add DR tabletop scenario walkthrough       |

## Domain 4.0 - Security Operations (28%)

| Objective                               | Coverage File                                                            | Status  | Notes                                   |
| --------------------------------------- | ------------------------------------------------------------------------ | ------- | --------------------------------------- |
| 4.1 Incident Response and Handling      | ../Domain_4_Security_Operations/4.1_Incident_Response_and_Handling.md    | Partial | Add legal/regulatory trigger scenarios  |
| 4.2 Monitoring, Detection, and Analysis | ../Domain_4_Security_Operations/4.2_Monitoring_Detection_and_Analysis.md | Partial | Add deeper log interpretation drills    |
| 4.3 IAM and Operational Security        | ../Domain_4_Security_Operations/4.3_IAM_and_Operational_Security.md      | Partial | Add lifecycle diagrams and edge cases   |
| 4.4 Automation and Orchestration        | ../Domain_4_Security_Operations/4.4_Automation_and_Orchestration.md      | Partial | Add rollback and failure-mode playbooks |

## Domain 5.0 - Security Program Management and Oversight (20%)

| Objective                                   | Coverage File                                                                                       | Status  | Notes                            |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------- | ------- | -------------------------------- |
| 5.1 Governance, Risk, and Compliance        | ../Domain_5_Security_Program_Management_and_Oversight/5.1_Governance_Risk_and_Compliance.md         | Partial | Add audit evidence examples      |
| 5.2 Security Program and Policy Management  | ../Domain_5_Security_Program_Management_and_Oversight/5.2_Security_Program_and_Policy_Management.md | Partial | Add KPI interpretation scenarios |
| 5.3 Third-Party Risk and Security Awareness | ../Domain_5_Security_Program_Management_and_Oversight/5.3_Third_Party_and_Awareness.md              | Partial | Add contract language examples   |

## Target Completion Plan

- Milestone 1: Convert all Partial rows to Complete by adding worked scenarios
- Milestone 2: Map every question bank item to objective IDs
- Milestone 3: Track mock exam misses back to matrix rows for remediation

Back to [Resources](Recommended_Resources.md)
