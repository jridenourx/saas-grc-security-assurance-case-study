# SOC 2 Readiness Control Matrix

> **SIMULATION NOTICE:** This matrix defines proposed controls for Northstar Cloud Solutions, a fictional SaaS provider. Control descriptions, ownership assignments, evidence requirements, and assessment statuses are part of a portfolio exercise. They do not establish that any real organization has implemented these controls.

## 1. Purpose

The control matrix establishes a consistent structure for evaluating selected security controls within the simulated SOC 2 readiness assessment.

It connects control objectives to responsible owners, supporting evidence, assessment procedures, identified risks, and customer assurance requirements.

The matrix will be used to coordinate evidence collection, perform readiness testing, document deficiencies, and track remediation.

## 2. Control Assessment Status

| Status                    | Definition                                                                                                         |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Not Assessed              | No documented assessment has been completed.                                                                       |
| Planned                   | The assessment procedure has been defined but not performed.                                                       |
| In Progress               | Assessment work is underway.                                                                                       |
| Evidence Gap              | Available evidence is insufficient to support a conclusion.                                                        |
| Design Deficiency         | Evidence supports a conclusion that the control is inadequately designed.                                          |
| Implementation Deficiency | Evidence supports a conclusion that the control was not implemented as intended.                                   |
| Operating Deficiency      | Evidence supports a conclusion that an implemented control did not operate as required during the assessed period. |
| Effective Within Scope    | The available evidence supports the control conclusion within the defined assessment scope and period.             |

An assessment status must reflect completed work and supporting evidence. It must not be assigned based solely on the presence of a control description in this matrix.

## 3. Control Ownership

The roles below are proposed for the fictional organization.

| Role                                | General Responsibility                                                                       |
| ----------------------------------- | -------------------------------------------------------------------------------------------- |
| Executive Management                | Governance, oversight, and delegated risk acceptance                                         |
| GRC                                 | Control documentation, evidence coordination, assessment tracking, and remediation oversight |
| Security / IT                       | Access management, security configuration, logging, and security operations                  |
| Engineering                         | Application security, change management, deployment controls, and technical remediation      |
| Human Resources / People Operations | Personnel lifecycle activities, where applicable                                             |
| Legal / Privacy                     | Contractual, privacy, and data-handling requirements                                         |
| Business Owner                      | Business requirements, service oversight, and assigned risk decisions                        |

The control owner is accountable for maintaining the control and supplying relevant evidence. The assessor evaluates the evidence and should not automatically treat the owner's assertion as sufficient proof.

## 4. Control Matrix

### CTRL-001 — Security Governance and Policy Management

| Attribute              | Details                                                                                                                                                               |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-001                                                                                                                                                              |
| Control Objective      | Establish documented security responsibilities and approved security policies appropriate to the service.                                                             |
| Proposed Owner         | Security / IT                                                                                                                                                         |
| Supporting Functions   | GRC, Executive Management                                                                                                                                             |
| Risk Addressed         | Unclear security responsibilities and inconsistent security practices                                                                                                 |
| Customer Questionnaire | CQA-001, CQA-002, CQA-004                                                                                                                                             |
| Evidence Required      | Approved security policies, policy review records, assigned responsibilities, and documented approvals                                                                |
| Planned Test           | Inspect policy approval and review records. Confirm that relevant responsibilities are assigned and that the documented requirements cover the defined service scope. |
| Expected Frequency     | At least annually and following material changes, subject to the proposed policy                                                                                      |
| Current Status         | Not Assessed                                                                                                                                                          |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                         |

### CTRL-002 — Risk Assessment and Treatment

| Attribute              | Details                                                                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-002                                                                                                                                                                      |
| Control Objective      | Identify, assess, assign, and track material security risks affecting the service.                                                                                            |
| Proposed Owner         | GRC                                                                                                                                                                           |
| Supporting Functions   | Security / IT, Engineering, Business Owners                                                                                                                                   |
| Risk Addressed         | Security risks remaining unidentified or untreated                                                                                                                            |
| Customer Questionnaire | CQA-003, CQA-005                                                                                                                                                              |
| Evidence Required      | Approved risk methodology, risk register, risk ownership records, treatment plans, and review history                                                                         |
| Planned Test           | Inspect the methodology and a sample of risk records. Verify that ratings have documented rationale, owners are assigned, and treatment or acceptance decisions are recorded. |
| Expected Frequency     | Periodic review and following material changes                                                                                                                                |
| Current Status         | Not Assessed                                                                                                                                                                  |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                 |

### CTRL-003 — User Access Provisioning and Removal

| Attribute              | Details                                                                                                                                                                                                    |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-003                                                                                                                                                                                                   |
| Control Objective      | Ensure user access is authorized, appropriate to business need, and removed or modified when no longer required.                                                                                           |
| Proposed Owner         | Security / IT                                                                                                                                                                                              |
| Supporting Functions   | Human Resources / People Operations, Business Owners                                                                                                                                                       |
| Risk Addressed         | Unauthorized access resulting from inappropriate or outdated permissions                                                                                                                                   |
| Customer Questionnaire | CQA-006, CQA-009                                                                                                                                                                                           |
| Evidence Required      | Access-control procedure, approved access requests, user inventory, role assignments, and access-removal records                                                                                           |
| Planned Test           | Select synthetic access records and compare requested access with approval and assigned permissions. Review a sample of termination or role-change records for evidence of access modification or removal. |
| Expected Frequency     | At onboarding, role changes, and termination; periodic review as defined by policy                                                                                                                         |
| Current Status         | Not Assessed                                                                                                                                                                                               |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                                              |

### CTRL-004 — Privileged Access and Least Privilege

| Attribute              | Details                                                                                                                                                                             |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-004                                                                                                                                                                            |
| Control Objective      | Restrict privileged permissions to authorized personnel and documented administrative requirements.                                                                                 |
| Proposed Owner         | Security / IT                                                                                                                                                                       |
| Supporting Functions   | Engineering                                                                                                                                                                         |
| Risk Addressed         | Excessive permissions or inappropriate administrative access                                                                                                                        |
| Customer Questionnaire | CQA-006, CQA-008, CQA-010                                                                                                                                                           |
| Evidence Required      | Privileged account inventory, approved role matrix, permission assignments, access reviews, and exception approvals                                                                 |
| Planned Test           | Compare privileged permissions with documented business requirements. Inspect access-review evidence and verify that identified exceptions have appropriate approval and treatment. |
| Expected Frequency     | Periodic review and following material access changes                                                                                                                               |
| Current Status         | Not Assessed                                                                                                                                                                        |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                       |

### CTRL-005 — Multifactor Authentication

| Attribute              | Details                                                                                                                                                                     |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-005                                                                                                                                                                    |
| Control Objective      | Enforce multifactor authentication for the defined accounts and access paths that require it.                                                                               |
| Proposed Owner         | Security / IT                                                                                                                                                               |
| Supporting Functions   | Engineering                                                                                                                                                                 |
| Risk Addressed         | Unauthorized access resulting from compromised credentials                                                                                                                  |
| Customer Questionnaire | CQA-007                                                                                                                                                                     |
| Evidence Required      | Authentication standard, system and account scope, MFA configuration evidence, coverage records, and exception approvals                                                    |
| Planned Test           | Identify applicable systems and account categories. Inspect configuration evidence and compare actual settings with the documented MFA requirements. Review any exceptions. |
| Expected Frequency     | Periodic review and following material authentication changes                                                                                                               |
| Current Status         | Not Assessed                                                                                                                                                                |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                               |

### CTRL-006 — Security Logging and Monitoring

| Attribute              | Details                                                                                                                                                                                                             |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-006                                                                                                                                                                                                            |
| Control Objective      | Generate and monitor relevant security events for systems within the defined scope.                                                                                                                                 |
| Proposed Owner         | Security / IT                                                                                                                                                                                                       |
| Supporting Functions   | Engineering                                                                                                                                                                                                         |
| Risk Addressed         | Security events going undetected because of insufficient logging or monitoring                                                                                                                                      |
| Customer Questionnaire | CQA-017, CQA-019, CQA-020                                                                                                                                                                                           |
| Evidence Required      | Logging standard, system coverage inventory, configuration evidence, alerting rules, review records, and retention settings                                                                                         |
| Planned Test           | Compare the system inventory with required logging coverage. Inspect selected configuration evidence and sample records to determine whether required events are captured and monitoring activities are documented. |
| Expected Frequency     | Ongoing monitoring with periodic control review                                                                                                                                                                     |
| Current Status         | Not Assessed                                                                                                                                                                                                        |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                                                       |

### CTRL-007 — Protection and Retention of Security Logs

| Attribute              | Details                                                                                                                                      |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-007                                                                                                                                     |
| Control Objective      | Restrict unauthorized access to security logs and maintain them according to defined retention requirements.                                 |
| Proposed Owner         | Security / IT                                                                                                                                |
| Supporting Functions   | Engineering                                                                                                                                  |
| Risk Addressed         | Loss, unauthorized modification, or premature deletion of relevant security records                                                          |
| Customer Questionnaire | CQA-018, CQA-020                                                                                                                             |
| Evidence Required      | Log access permissions, retention requirements, relevant configuration settings, and documented exceptions                                   |
| Planned Test           | Inspect permissions governing access to security logs. Compare configured retention with documented requirements and investigate exceptions. |
| Expected Frequency     | Periodic review and following material logging changes                                                                                       |
| Current Status         | Not Assessed                                                                                                                                 |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                |

### CTRL-008 — Incident Response

| Attribute              | Details                                                                                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-008                                                                                                                                       |
| Control Objective      | Establish responsibilities and procedures for identifying, escalating, responding to, and learning from security incidents.                    |
| Proposed Owner         | Security / IT                                                                                                                                  |
| Supporting Functions   | Engineering, Legal / Privacy, Executive Management                                                                                             |
| Risk Addressed         | Delayed or ineffective response to security incidents                                                                                          |
| Customer Questionnaire | CQA-021, CQA-022, CQA-023                                                                                                                      |
| Evidence Required      | Incident response plan, assigned responsibilities, escalation procedures, exercise records, and tracked improvements                           |
| Planned Test           | Inspect the approved plan and responsibilities. If exercise records exist, review the exercise scope, results, and tracked corrective actions. |
| Expected Frequency     | Periodic review and exercise according to the proposed plan                                                                                    |
| Current Status         | Not Assessed                                                                                                                                   |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                  |

### CTRL-009 — Customer Incident Notification

| Attribute              | Details                                                                                                                                                    |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-009                                                                                                                                                   |
| Control Objective      | Identify and fulfill applicable customer incident notification obligations.                                                                                |
| Proposed Owner         | Legal / Privacy                                                                                                                                            |
| Supporting Functions   | Security / IT, Customer Success                                                                                                                            |
| Risk Addressed         | Failure to meet applicable notification commitments                                                                                                        |
| Customer Questionnaire | CQA-024                                                                                                                                                    |
| Evidence Required      | Relevant contractual provisions, approved notification procedures, assigned responsibilities, and notification records where applicable                    |
| Planned Test           | Identify applicable notification obligations and compare them with documented procedures and responsibilities. Review appropriate records where available. |
| Expected Frequency     | Periodic review and following material contractual or legal changes                                                                                        |
| Current Status         | Not Assessed                                                                                                                                               |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                              |

### CTRL-010 — Data Handling, Retention, and Deletion

| Attribute              | Details                                                                                                                                                                                                     |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-010                                                                                                                                                                                                    |
| Control Objective      | Define and implement appropriate requirements for customer data handling, retention, and deletion.                                                                                                          |
| Proposed Owner         | Security / IT                                                                                                                                                                                               |
| Supporting Functions   | Engineering, Legal / Privacy, Business Owners                                                                                                                                                               |
| Risk Addressed         | Unnecessary retention, inappropriate disclosure, or failure to dispose of information appropriately                                                                                                         |
| Customer Questionnaire | CQA-011, CQA-012, CQA-013, CQA-014, CQA-015                                                                                                                                                                 |
| Evidence Required      | Data inventory, data-flow documentation, handling requirements, retention schedule, deletion procedure, and relevant test evidence                                                                          |
| Planned Test           | Compare documented data flows with the defined scope. Inspect retention requirements and sample relevant configuration or test evidence. Identify systems and copies not covered by the available evidence. |
| Expected Frequency     | Periodic review and following material data-flow or retention changes                                                                                                                                       |
| Current Status         | Not Assessed                                                                                                                                                                                                |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                                               |

### CTRL-011 — Vulnerability Management

| Attribute              | Details                                                                                                                                                                               |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-011                                                                                                                                                                              |
| Control Objective      | Identify, assess, prioritize, and remediate vulnerabilities affecting systems within scope.                                                                                           |
| Proposed Owner         | Security / IT                                                                                                                                                                         |
| Supporting Functions   | Engineering                                                                                                                                                                           |
| Risk Addressed         | Known vulnerabilities remaining untreated and exposing the service to exploitation                                                                                                    |
| Customer Questionnaire | CQA-027                                                                                                                                                                               |
| Evidence Required      | Vulnerability management procedure, relevant assessment results, prioritization criteria, remediation records, and validation evidence                                                |
| Planned Test           | Inspect the procedure and a sample of synthetic vulnerability records. Compare severity, assigned ownership, treatment status, and closure evidence with the documented requirements. |
| Expected Frequency     | According to the documented vulnerability assessment and remediation schedule                                                                                                         |
| Current Status         | Not Assessed                                                                                                                                                                          |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                         |

### CTRL-012 — Change Management

| Attribute              | Details                                                                                                                                                     |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-012                                                                                                                                                    |
| Control Objective      | Ensure relevant system changes are reviewed, tested, authorized, and documented before implementation.                                                      |
| Proposed Owner         | Engineering                                                                                                                                                 |
| Supporting Functions   | Security / IT                                                                                                                                               |
| Risk Addressed         | Unauthorized or inadequately tested changes introducing security weaknesses                                                                                 |
| Customer Questionnaire | CQA-028                                                                                                                                                     |
| Evidence Required      | Change-management procedure, approved change records, testing results, deployment approvals, and exception records                                          |
| Planned Test           | Select synthetic change records and inspect evidence of authorization, testing, approval, and implementation. Investigate exceptions and emergency changes. |
| Expected Frequency     | For each applicable change, with periodic process review                                                                                                    |
| Current Status         | Not Assessed                                                                                                                                                |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                               |

### CTRL-013 — Secure Development and Deployment Access

| Attribute              | Details                                                                                                                                                                                               |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-013                                                                                                                                                                                              |
| Control Objective      | Apply defined security requirements during development and restrict production deployment permissions to authorized personnel.                                                                        |
| Proposed Owner         | Engineering                                                                                                                                                                                           |
| Supporting Functions   | Security / IT                                                                                                                                                                                         |
| Risk Addressed         | Security weaknesses introduced through development or unauthorized deployment                                                                                                                         |
| Customer Questionnaire | CQA-029, CQA-030                                                                                                                                                                                      |
| Evidence Required      | Secure development standard, relevant security testing records, deployment permissions, approval records, and access-review evidence                                                                  |
| Planned Test           | Inspect the documented development requirements and selected synthetic release records. Compare deployment permissions with approved responsibilities and review available security testing evidence. |
| Expected Frequency     | For applicable releases and according to the documented development process                                                                                                                           |
| Current Status         | Not Assessed                                                                                                                                                                                          |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                                         |

### CTRL-014 — Third-Party Risk Management

| Attribute              | Details                                                                                                                                                                  |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Control ID             | CTRL-014                                                                                                                                                                 |
| Control Objective      | Assess, monitor, and manage risks arising from third-party service providers relevant to the service.                                                                    |
| Proposed Owner         | GRC                                                                                                                                                                      |
| Supporting Functions   | Procurement, Security / IT, Business Owners                                                                                                                              |
| Risk Addressed         | External service-provider weaknesses affecting customer information or service operations                                                                                |
| Customer Questionnaire | CQA-031, CQA-032, CQA-033, CQA-034                                                                                                                                       |
| Evidence Required      | Vendor inventory, risk-tiering methodology, due diligence records, supporting evidence, findings, remediation tracking, and reassessment records                         |
| Planned Test           | Inspect the vendor inventory and risk methodology. Review selected vendor assessments for documented rationale, evidence references, findings, ownership, and follow-up. |
| Expected Frequency     | Risk-based reassessment and following material vendor changes                                                                                                            |
| Current Status         | Not Assessed                                                                                                                                                             |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                            |

### CTRL-015 — Customer Security Assurance and Control Evidence

| Attribute              | Details                                                                                                                                                                                |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Control ID             | CTRL-015                                                                                                                                                                               |
| Control Objective      | Ensure external security representations are accurate, appropriately supported, reviewed, and approved before release.                                                                 |
| Proposed Owner         | GRC                                                                                                                                                                                    |
| Supporting Functions   | Customer Success / Sales, Security / IT, Engineering, Legal / Privacy                                                                                                                  |
| Risk Addressed         | Inaccurate or unsupported security claims made to customers                                                                                                                            |
| Customer Questionnaire | CQA-035, CQA-036, CQA-037, CQA-038, CQA-039, CQA-040                                                                                                                                   |
| Evidence Required      | Questionnaire workflow, response library, evidence references, reviewer decisions, approval records, and submitted questionnaires                                                      |
| Planned Test           | Inspect a sample of synthetic questionnaire responses. Trace material claims to supporting evidence and verify that the required review, approval, and retention steps are documented. |
| Expected Frequency     | For each customer questionnaire, with periodic process review                                                                                                                          |
| Current Status         | Not Assessed                                                                                                                                                                           |
| Finding Reference      | To be assigned if a deficiency is established                                                                                                                                          |

## 5. Cross-Project Traceability

The control matrix uses the following identifiers to connect the SOC 2 readiness workstream with the rest of the portfolio.

| Record Type            | Identifier Format | Purpose                                  |
| ---------------------- | ----------------- | ---------------------------------------- |
| Vendor                 | VND-001           | Identify a service provider              |
| Risk                   | RSK-001           | Identify a documented risk               |
| Control                | CTRL-001          | Identify a control objective             |
| Evidence               | EVD-001           | Identify a supporting evidence artifact  |
| Customer Questionnaire | CQA-001           | Identify a customer security question    |
| Finding                | FND-001           | Identify a documented assessment finding |
| Action                 | ACT-001           | Identify a remediation action            |

Use existing IDs where applicable. Do not assign a new identifier to a record that already has one.

A control can address multiple risks, and a single risk can be addressed by multiple controls. The relationship should be documented rather than assumed.

## 6. Framework Mapping

The controls are designed around security governance and operational safeguards relevant to the simulated SOC 2 Security scope.

The next mapping step is to connect each control to the specific applicable AICPA Trust Services Criteria and document the rationale.

The mapping should be verified against the applicable framework source before it is treated as complete. Do not infer that a control satisfies an entire criterion merely because its subject matter appears related.

Additional reference frameworks, such as NIST SP 800-53 Rev. 5, may be used as supporting guidance where appropriate. They should not be presented as interchangeable with the AICPA Trust Services Criteria.

## 7. Assessment Requirements

Before a control is assigned an effectiveness conclusion, the assessor should document:

* The control objective and assessment scope.
* The applicable assessment criteria.
* The control owner.
* The evidence reviewed.
* The procedures performed.
* The results and exceptions identified.
* The conclusion and supporting rationale.
* Any associated findings and remediation actions.

Where operating effectiveness is assessed, the workpaper must identify the relevant period and explain how the evidence supports the conclusion over that period.

A policy or design description alone is not sufficient to establish that a control operated effectively.

## 8. Matrix Maintenance

The control matrix should be updated when:

* The system scope changes.
* A control is added, removed, or materially redesigned.
* Ownership changes.
* New evidence identifies a deficiency.
* A remediation action is completed and validated.
* Framework mapping is revised.
* A material risk changes the required control coverage.

Material updates should preserve traceability to existing evidence, risks, findings, and remediation records.

## 9. Simulation Disclaimer

This matrix is a proposed control inventory for a fictional SaaS provider. It does not establish that the listed controls are implemented, effective, or independently audited.

The assessment status of each control must be determined from the evidence and testing completed during the portfolio exercise.
