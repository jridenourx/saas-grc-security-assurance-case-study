# Third-Party Risk Management Lifecycle Procedure

> **SIMULATION NOTICE:** This procedure describes a proposed process for Northstar Cloud Solutions, a fictional SaaS company. The timelines, responsibilities, and thresholds are proposed internal rules for this case study, not universal regulatory requirements.

## 1. Purpose

This procedure defines how Northstar Cloud Solutions identifies, evaluates, approves, monitors, reassesses, and offboards third-party service providers.

The objective is to ensure that vendor risk is evaluated consistently and that decisions remain traceable throughout the vendor relationship.

## 2. Scope

This procedure applies to third parties that provide services to Northstar or may access, process, store, transmit, or support information or systems relevant to the company.

The level of due diligence and monitoring should reflect the vendor's inherent risk, service criticality, data exposure, access permissions, and other relevant factors.

## 3. Roles and Responsibilities

| Role                                             | Responsibilities                                                                                                               |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| Business Owner                                   | Defines the business need, confirms service requirements, participates in risk decisions, and oversees the vendor relationship |
| Procurement                                      | Coordinates onboarding and commercial processes and maintains relevant vendor records                                          |
| GRC                                              | Coordinates risk tiering, due diligence, evidence review, risk tracking, and reassessment                                      |
| Security / IT                                    | Reviews technical safeguards, access, integrations, and relevant security evidence                                             |
| Legal / Privacy                                  | Reviews contractual, privacy, data-handling, and notification requirements where applicable                                    |
| Executive Management or Delegated Risk Authority | Reviews escalated risks and approves risk acceptance within delegated authority                                                |
| Vendor Contact                                   | Supplies requested information, answers due diligence questions, and supports remediation discussions                          |

These responsibilities are proposed for the fictional organization. Specific role assignments should be confirmed before the procedure is implemented in a real organization.

## 4. Vendor Lifecycle

The lifecycle consists of seven stages:

1. Identification and intake.
2. Inherent-risk assessment.
3. Due diligence and evidence review.
4. Approval and contracting.
5. Ongoing monitoring.
6. Periodic or event-driven reassessment.
7. Offboarding and access termination.

The process should be proportionate to the risk and should preserve a documented record of material decisions.

## 5. Stage 1 — Identification and Intake

Before a new vendor is engaged, the business owner should document:

* Vendor name and service.
* Business purpose.
* Proposed business owner.
* Data the vendor may access or process.
* Required integrations and system permissions.
* Business criticality and dependency.
* Expected contract duration.
* Relevant subcontractors or subprocessors, where known.

GRC or the designated vendor risk function should assign a vendor ID and create an inventory record.

**Required output:** Vendor inventory entry and documented service scope.

**Escalation:** Incomplete information concerning sensitive data, privileged access, or a critical business dependency should be resolved before proceeding with approval.

## 6. Stage 2 — Inherent-Risk Assessment

Assess the vendor using the methodology documented in `vendor-risk-assessment-matrix.md`.

The proposed scoring model considers:

* Data sensitivity — 30%.
* System access and integration — 25%.
* Business criticality — 25%.
* External dependency or concentration — 20%.

Each factor receives a score from 1 to 5. The weighted score determines a preliminary inherent-risk tier.

| Tier     | Proposed Weighted Score |
| -------- | ----------------------: |
| Low      |               1.00–2.00 |
| Moderate |               2.01–3.50 |
| High     |               3.51–5.00 |

These thresholds are proposed internal choices for this simulation.

The assessment should also consider escalation overrides documented in the methodology. A critical exposure should not be downgraded simply because the arithmetic score falls below a tier threshold.

**Required output:** Documented inherent-risk score, tier, rationale, and any escalation decision.

## 7. Stage 3 — Due Diligence and Evidence Review

The depth of due diligence should reflect the vendor's inherent-risk tier and the nature of its service.

### Low-Risk Vendors

Typical review activities may include:

* Confirmation of service scope.
* Review of relevant security commitments.
* Identification of material data access or dependency concerns.
* Documentation of any required follow-up.

### Moderate-Risk Vendors

Typical review activities may include:

* Completion of the relevant security questionnaire.
* Review of access and data-protection practices.
* Review of incident response and retention arrangements.
* Evaluation of relevant supporting evidence.
* Documentation of material gaps and proposed treatment.

### High-Risk Vendors

Typical review activities may include:

* More detailed security due diligence.
* Review of relevant independent assurance.
* Evaluation of privileged access, logging, recovery, and incident response.
* Confirmation of shared security responsibilities.
* Review of material contractual security requirements.
* Escalation of unresolved material risks.

These are proposed baseline review expectations. Additional procedures may be necessary depending on the service and its risks.

### Evidence Review

For material questionnaire responses, the assessor should determine whether the available evidence is relevant, reliable, complete, and sufficiently current for the assessment purpose.

A missing artifact is an evidence gap. It does not automatically establish that the associated control has failed.

**Required output:** Updated evidence register, completed assessment workpapers, documented exceptions, and risk treatment recommendations where warranted.

## 8. Stage 4 — Approval and Contracting

Before onboarding is approved:

1. Confirm that the service scope is documented.
2. Confirm that the inherent-risk assessment is complete.
3. Review material due diligence results.
4. Document unresolved issues and proposed treatment.
5. Confirm that the appropriate business owner has reviewed the assessment.
6. Escalate material risks to the designated approval authority.
7. Confirm that applicable contractual requirements have been reviewed.

Depending on the service and risk, contractual provisions may address:

* Security responsibilities.
* Data handling and permitted use.
* Incident notification.
* Confidentiality.
* Subprocessor management.
* Evidence or assurance requests.
* Data return and deletion.
* Termination and transition requirements.

GRC should not independently approve risks outside its delegated authority.

**Required output:** Documented onboarding decision, required approvals, contractual review status, and outstanding conditions.

## 9. Stage 5 — Ongoing Monitoring

Vendor oversight should continue after onboarding.

Potential monitoring activities include:

* Tracking outstanding remediation actions.
* Reviewing material security notifications.
* Monitoring relevant assurance-report updates.
* Reviewing service or integration changes.
* Tracking contractual commitments.
* Reviewing material incidents or service disruptions.
* Confirming that vendor records and business ownership remain current.

Monitoring should be proportionate to risk. A critical infrastructure provider may require more frequent and detailed oversight than a low-impact service with no access to sensitive information.

**Required output:** Updated vendor record, monitoring notes, and escalations where necessary.

## 10. Stage 6 — Periodic and Event-Driven Reassessment

### Proposed Reassessment Schedule

The following schedule is a proposed internal standard for this simulation.

| Inherent-Risk Tier | Proposed Maximum Interval Between Full Reviews |
| ------------------ | ---------------------------------------------- |
| High               | 12 months                                      |
| Moderate           | 18 months                                      |
| Low                | 24 months                                      |

These intervals are illustrative and should be adjusted to the organization's risk appetite, service requirements, contractual obligations, and applicable requirements.

A reassessment should occur sooner when a material event changes the risk.

### Reassessment Triggers

Triggers may include:

* A material security incident.
* A significant change in service scope.
* New access to sensitive information.
* Introduction of privileged access or a new integration.
* A material change in subcontractors or subprocessors.
* A significant change in business dependency.
* Expired, withdrawn, or materially qualified assurance.
* A major unresolved finding or overdue remediation.
* A change in applicable contractual or regulatory requirements.

### Reassessment Procedure

1. Confirm the current service scope and business owner.
2. Review the previous assessment and open actions.
3. Reevaluate inherent risk if circumstances have changed.
4. Request updated due diligence responses and relevant evidence.
5. Review material changes in controls, incidents, and assurance.
6. Reassess risks and document any new findings.
7. Determine whether the vendor's risk tier or approval conditions should change.
8. Record the reassessment decision and next review date.

**Required output:** Updated assessment, documented rationale, and an assigned next review date.

## 11. Risk Treatment and Escalation

When a material risk is identified, GRC should document the issue and coordinate the appropriate response.

Possible treatments include:

* **Mitigate:** Reduce the exposure through corrective action or additional safeguards.
* **Avoid:** Stop or decline the activity that creates the exposure.
* **Transfer or share:** Allocate specified aspects of risk through contractual or other arrangements, recognizing that accountability may still remain with Northstar.
* **Accept:** Obtain documented approval from an authorized risk owner.

Risk acceptance should include the rationale, remaining exposure, approving authority, any required compensating measures, and a review or expiration date.

A vendor should not be treated as approved merely because due diligence has been completed.

## 12. Stage 7 — Vendor Offboarding

When a vendor relationship ends, the business owner and relevant support functions should coordinate offboarding.

Activities should include, as applicable:

1. Confirm the termination date and business owner.
2. Revoke vendor accounts, credentials, and integration access.
3. Disable or remove unnecessary service connections.
4. Recover or transfer company assets and records.
5. Confirm data return or deletion requirements.
6. Obtain deletion confirmation where required and available.
7. Review outstanding incidents, findings, and contractual obligations.
8. Update the vendor inventory and record the offboarding date.

The organization should retain appropriate assessment and contractual records according to its retention requirements.

**Required output:** Documented offboarding checklist, access-removal evidence, data disposition record where applicable, and updated vendor inventory status.

## 13. Records and Traceability

The lifecycle should maintain consistent links between:

* Vendor inventory records.
* Risk assessments and tiering decisions.
* Questionnaire responses.
* Evidence records.
* Risk register entries.
* Findings and remediation actions.
* Approval and risk acceptance records.
* Reassessment and offboarding documentation.

Use the established IDs, including `VND`, `RSK`, `EVD`, `FND`, and `ACT`, to maintain traceability.

## 14. Exceptions and Procedure Review

Exceptions to this procedure should be documented with:

* The requirement being excepted.
* The reason for the exception.
* The associated risk.
* The proposed compensating measures, if any.
* The approving authority.
* The expiration or review date.

The procedure should be reviewed periodically and when material changes occur in the vendor environment, risk methodology, or applicable requirements.

## 15. Simulation Disclaimer

This procedure is a proposed internal process for a fictional SaaS organization. Its scoring thresholds, reassessment intervals, roles, and approval requirements are illustrative rather than universal standards.

It does not establish that a real organization has implemented this process or meets any particular compliance requirement.
