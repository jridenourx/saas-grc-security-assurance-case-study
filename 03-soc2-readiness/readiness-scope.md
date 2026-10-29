# SOC 2 Readiness Assessment Scope

> **SIMULATION NOTICE:** This document defines the proposed scope of a readiness assessment for Northstar Cloud Solutions, a fictional SaaS provider. It does not represent an independent SOC 2 examination or an issued SOC 2 report.

## 1. Purpose

This document establishes the boundaries, assumptions, assessment criteria, and exclusions for the simulated SOC 2 readiness assessment.

The objective is to determine whether the defined service has an appropriately documented control environment, identify evidence gaps and potential control weaknesses, and establish remediation priorities before a hypothetical independent examination.

## 2. Organization and Service Overview

| Field               | Description                                                                            |
| ------------------- | -------------------------------------------------------------------------------------- |
| Organization        | Northstar Cloud Solutions                                                              |
| Business Model      | Business-to-business software as a service (SaaS)                                      |
| Service             | Subscription-based platform for customer business records                              |
| Hosting Environment | Amazon Web Services (AWS)                                                              |
| Data Categories     | Customer business records, customer account information, and application activity logs |
| Assessment Type     | Simulated SOC 2 readiness assessment                                                   |
| Primary Criterion   | Security                                                                               |
| Assessment Status   | Planned / In Progress as project work is completed                                     |

Northstar and its operating environment are fictional. The project will use documented scenario assumptions and synthetic evidence rather than claim access to an actual production environment.

## 3. Assessment Objectives

The assessment will:

1. Define the system and service boundaries.
2. Identify relevant security risks and control objectives.
3. Establish a control matrix with assigned owners and evidence requirements.
4. Evaluate whether selected controls are appropriately designed.
5. Identify evidence gaps and potential operating deficiencies.
6. Document findings, remediation actions, and closure criteria.
7. Produce a readiness summary that distinguishes demonstrated results from unresolved questions.

## 4. Assessment Criteria

### 4.1 Security Trust Services Criterion

Security is the baseline criterion because the scenario focuses on protecting the SaaS service and customer information against unauthorized access and other security threats.

The assessment will consider relevant Trust Services Criteria from the applicable AICPA framework, including areas related to:

* Control environment and governance.
* Communication and information.
* Risk assessment.
* Monitoring activities.
* Control activities.
* Logical and physical access.
* System operations.
* Change management.
* Risk mitigation.

The final control mapping should identify the specific applicable criteria and explain why each control is relevant. Broad category names are not a substitute for mapping individual controls to the appropriate criteria.

### 4.2 Additional Criteria

Additional Trust Services Categories will not be included automatically.

* **Availability:** Consider only if Northstar's commitments to customers and the service's availability objectives justify including it.
* **Confidentiality:** Consider if Northstar has defined commitments to protect information designated as confidential beyond the baseline security requirements.
* **Processing Integrity:** Consider if customers rely on the completeness, validity, accuracy, or timeliness of specific processing outcomes.
* **Privacy:** Consider if the scope includes applicable privacy commitments and personal-information practices that warrant evaluation against the relevant criteria.

For this initial case study, the baseline scope is **Security only**. Additional criteria may be added later if the scenario establishes a clear business rationale and sufficient assessment scope.

## 5. System Boundaries

The proposed system boundary includes the components and processes necessary to provide and support the Northstar SaaS service.

| Component                       | Proposed Scope                                            | Assessment Considerations                                                                    |
| ------------------------------- | --------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| SaaS application                | In scope                                                  | Application access, security configuration, and relevant application controls                |
| AWS-hosted infrastructure       | In scope                                                  | Infrastructure responsibilities, identity management, logging, and relevant cloud safeguards |
| Identity and access management  | In scope                                                  | User provisioning, privileged access, MFA, and access reviews                                |
| Security logging and monitoring | In scope                                                  | Event coverage, protection, retention, and monitoring                                        |
| Change management               | In scope                                                  | Change approval, testing, and deployment permissions                                         |
| Incident response               | In scope                                                  | Incident identification, escalation, response, and lessons learned                           |
| Backup and recovery             | In scope for security and relevant operational safeguards | Backup access, protection, and evidence supporting recovery requirements                     |
| Vendor management               | In scope                                                  | Risk assessment and oversight of relevant external providers                                 |
| Customer assurance              | In scope as a supporting process                          | Accuracy and approval of security representations                                            |

The table defines proposed assessment boundaries. It does not establish that every listed component or process exists or has been verified.

## 6. External Service Providers

The assessment will consider relevant external service providers and the division of security responsibilities between Northstar and those providers.

| Vendor ID | Fictional Provider      | Service                   | Assessment Focus                                                  |
| --------- | ----------------------- | ------------------------- | ----------------------------------------------------------------- |
| VND-001   | Northstar Cloud Hosting | Cloud infrastructure      | Shared responsibilities, privileged access, logging, and recovery |
| VND-002   | SignalBridge Support    | Customer support platform | Customer data access, permissions, and subprocessors              |
| VND-003   | MetricForge Analytics   | Product analytics         | Data minimization, integration permissions, and data lifecycle    |

These providers are fictional scenario elements. Their assessments support the readiness exercise but do not establish the effectiveness of Northstar's own controls.

Third-party assurance may inform the assessment of relevant service-provider dependencies, but it does not automatically demonstrate that Northstar has implemented its own responsibilities.

## 7. Data Within Scope

| Data Category                | Description                                              | Relevant Considerations                                         |
| ---------------------------- | -------------------------------------------------------- | --------------------------------------------------------------- |
| Customer business records    | Records stored or maintained by customers in the service | Access restrictions, confidentiality, and appropriate use       |
| Customer account information | Account identifiers and business contact information     | Access control and protection against inappropriate disclosure  |
| Application activity logs    | Events generated by users and application components     | Logging coverage, integrity, retention, and access restrictions |
| Internal operational records | Records used to administer and support the service       | Appropriate access, retention, and protection                   |

Detailed data flows, classifications, retention requirements, and system locations must be documented or identified as evidence gaps during the assessment.

## 8. Control Assessment Approach

Each selected control will be evaluated using documented criteria and appropriate evidence.

The assessment will distinguish between:

**Control design:** Whether the stated control is appropriately designed to address the identified risk.

**Implementation:** Whether evidence demonstrates that the control has been put in place.

**Operating effectiveness:** Whether evidence demonstrates that the control operated as intended over a defined period, where that assessment is relevant and supported.

**Evidence gap:** Whether available evidence is insufficient to support a conclusion.

**Control deficiency:** Whether the available evidence supports a conclusion that a control is absent, inadequately designed, or not operating as required.

The assessment will not treat missing evidence as automatic proof of control failure. It will document the uncertainty, identify the evidence needed, and determine whether further investigation is appropriate.

## 9. Assessment Period and Evidence

Because this is a simulated readiness exercise, the assessment period will be defined for each workpaper rather than represented as a real operational reporting period.

Synthetic evidence may include:

* Policy and procedure documents.
* Access-control matrices.
* Configuration summaries.
* Evidence registers.
* Sample change records.
* Logging and monitoring examples.
* Vendor assessment records.
* Remediation and review records.

All synthetic evidence must be labeled clearly. Where the project does not establish that a control operates over time, the assessment must not claim operating effectiveness.

## 10. Out of Scope

The following activities are excluded:

* An independent SOC 2 examination.
* Issuance of a SOC 2 Type I or Type II report.
* A claim of SOC 2 certification or compliance.
* A complete production AWS security assessment.
* Penetration testing of a real system.
* A legal determination of compliance.
* Assessment of unrelated business systems.
* Claims about actual customer data, incidents, or vendor performance.

## 11. Assumptions and Limitations

The assessment relies on a fictional SaaS scenario and synthetic evidence created for the portfolio project.

Where implementation details, system configurations, or operating records are not available in the scenario, those limitations will be documented.

Control mappings and assessment procedures will be aligned to relevant criteria and guidance, but they will not be represented as a complete or authoritative mapping of every requirement in the AICPA framework.

## 12. Deliverables

The readiness workstream will produce:

1. Readiness scope and assumptions.
2. Control matrix.
3. Evidence request register.
4. Control testing plan and workpapers.
5. Findings and remediation tracker.
6. Readiness summary and management recommendations.

## 13. Completion Criteria

The simulated readiness assessment will be considered complete when:

* The system boundary and selected criteria are documented.
* Relevant controls have assigned owners and evidence requirements.
* Assessment procedures and evidence limitations are recorded.
* Findings are supported by traceable evidence.
* Remediation actions have owners and closure criteria.
* The readiness summary accurately describes the results and remaining gaps.
* All limitations concerning the simulation and independent examination status are clearly stated.

## 14. Simulation Disclaimer

This scope defines a learning exercise for a fictional SaaS provider. It does not establish that Northstar Cloud Solutions is SOC 2 compliant, has completed an independent examination, or has received a SOC 2 report.
