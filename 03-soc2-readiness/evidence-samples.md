# Synthetic SOC 2 Assessment Evidence Samples

## 1. Purpose

This document contains fictional evidence samples for the Northstar Cloud Solutions SOC 2 readiness case study.

The samples demonstrate how a GRC analyst evaluates documentation, access records, security configurations, monitoring records, and operational procedures against defined controls.

> **SIMULATION NOTICE:** Northstar Cloud Solutions is fictional. All records in this document are synthetic artifacts created for this portfolio. They were not collected from a real company, AWS account, employee population, or independent audit.

The samples provide starting points for assessment and follow-up. They do not, by themselves, establish that a control is effective or ineffective.

## 2. Evidence Evaluation Principles

For each sample, the assessor should determine:

* What the evidence actually demonstrates.
* Which control objective it relates to.
* Whether the evidence is complete and relevant to the assessment period.
* Whether the source and authenticity can be established within the simulation.
* Whether additional evidence is required.
* Whether the evidence supports the control, identifies a potential exception, or remains inconclusive.

A policy demonstrates documented intent; it does not independently demonstrate that a process operates effectively.

A configuration snapshot demonstrates a configuration at a particular point in time; it does not necessarily prove that the configuration was maintained throughout an assessment period.

A missing record may indicate an evidence gap, but does not by itself prove that an underlying activity never occurred.

All preliminary assessments below are based only on the fictional samples described in this document.

---

## 3. Evidence Sample EVD-008: Access Review Records

**Control reference:** CTRL-004 — Privileged Access and Least Privilege
**Evidence ID:** EVD-008
**Evidence type:** Synthetic access review record
**System:** Northstar production application
**Assessment period:** Illustrative quarterly review

### Sample record

| Field                                  | Synthetic value              |
| -------------------------------------- | ---------------------------- |
| Review ID                              | ACCESS-REVIEW-2026-Q3        |
| Review period                          | July 1–September 30, 2026    |
| Review population                      | 24 application user accounts |
| Reviewer                               | Application Owner            |
| Review date                            | October 5, 2026              |
| Accounts reviewed                      | 24                           |
| Accounts with documented decisions     | 22                           |
| Accounts awaiting documented decisions | 2                            |
| Approval record                        | Partial                      |
| Follow-up evidence                     | Not provided                 |

### Assessor notes

The sample indicates that a review record exists for 24 accounts, but only 22 have documented decisions.

The available sample does not establish whether the remaining accounts were reviewed through another documented process. It also does not establish whether inappropriate or excessive access exists.

Because this sample is being used to assess privileged access and least privilege, additional evidence is needed to determine whether the population includes privileged accounts, whether permissions were appropriate, and whether exceptions were addressed.

### Follow-up requests

* Obtain the complete review record and reviewer decisions.
* Identify the roles and permissions assigned to the reviewed accounts.
* Determine whether any accounts have privileged access.
* Investigate why two accounts lack documented decisions.
* Obtain evidence of follow-up on any access concerns.
* Compare permissions with the approved role-permission matrix.
* Confirm that the review population is complete.

### Preliminary assessment

**Status:** Inconclusive pending follow-up.

The incomplete decisions warrant investigation, but the sample alone does not prove that the least-privilege control failed.

---

## 4. Evidence Sample EVD-010: Multifactor Authentication Configuration

**Control reference:** CTRL-005 — Multifactor Authentication
**Evidence ID:** EVD-010
**Evidence type:** Synthetic identity configuration summary
**System:** Northstar workforce identity provider

### Sample record

| Field                               | Synthetic value |
| ----------------------------------- | --------------- |
| Snapshot date                       | October 6, 2026 |
| Workforce accounts                  | 32              |
| Accounts covered by the MFA policy  | 30              |
| Accounts with documented exclusions | 2               |
| Exclusion approvals                 | Not provided    |
| Privileged account breakdown        | Not provided    |
| Configuration history               | Not provided    |

### Assessor notes

The sample indicates that the MFA policy covers 30 of 32 workforce accounts. It does not explain the two exclusions or establish whether privileged accounts are among them.

The sample alone cannot establish whether the exclusions are justified, whether other authentication safeguards apply, or whether MFA was consistently enforced throughout the assessment period.

### Follow-up requests

* Obtain the complete workforce account population and MFA configuration.
* Identify both excluded accounts and their business justifications.
* Determine whether either excluded account has privileged access.
* Obtain approval and expiration records for any exceptions.
* Review applicable authentication requirements.
* Inspect relevant configuration and sign-in evidence.
* Determine whether the configuration was maintained throughout the assessment period.

### Preliminary assessment

**Status:** Potential exception requiring investigation.

The exclusions require further evaluation. Do not conclude that MFA is ineffective across the environment based solely on this summary.

---

## 5. Evidence Sample EVD-012: Cloud Security Logging Configuration

**Control reference:** CTRL-006 — Security Logging and Monitoring
**Evidence ID:** EVD-012
**Evidence type:** Synthetic cloud logging configuration summary
**Environment:** Fictional AWS production account

### Sample record

| Field                            | Synthetic value               |
| -------------------------------- | ----------------------------- |
| Snapshot date                    | October 7, 2026               |
| Production account               | PROD-001                      |
| CloudTrail status                | Enabled                       |
| Multi-region coverage            | Not established by the sample |
| Log storage destination          | Configured                    |
| Log file validation              | Not established by the sample |
| Log retention configuration      | Not provided                  |
| Alerting and escalation evidence | Not provided                  |
| Configuration history            | Not provided                  |

### Assessor notes

The sample supports the limited conclusion that CloudTrail is shown as enabled in the synthetic configuration summary.

It does not establish complete logging coverage, appropriate retention, protection against unauthorized alteration, or effective alerting and monitoring.

The control objective requires more than the presence of a logging service. The assessor must evaluate whether the relevant events are captured, whether monitoring operates as intended, and whether security events are investigated appropriately.

### Follow-up requests

* Obtain the relevant trail configuration and account coverage.
* Determine whether the required regions and services are covered.
* Inspect the destination and access restrictions for stored logs.
* Review retention and integrity-protection settings.
* Obtain representative security events and monitoring records.
* Inspect examples of alerts and documented follow-up.
* Compare the configuration with the defined logging requirements.

### Preliminary assessment

**Status:** Partially supported; additional testing required.

The sample supports a limited configuration observation, not a conclusion that cloud logging and monitoring are fully effective.

---

## 6. Evidence Sample EVD-016: Incident Response Exercise Record

**Control reference:** CTRL-008 — Incident Response
**Evidence ID:** EVD-016
**Evidence type:** Synthetic tabletop exercise summary

### Sample record

| Field                          | Synthetic value                                   |
| ------------------------------ | ------------------------------------------------- |
| Exercise ID                    | IR-TTX-2026-01                                    |
| Exercise date                  | August 20, 2026                                   |
| Scenario                       | Suspected unauthorized access to customer records |
| Participants                   | Security, IT Operations, Customer Operations      |
| Detection discussion           | Documented                                        |
| Escalation discussion          | Documented                                        |
| Customer notification decision | Discussed                                         |
| Action items                   | Three recorded                                    |
| Action owners                  | Two of three assigned                             |
| Closure evidence               | Not provided                                      |

### Assessor notes

The sample indicates that a tabletop exercise was documented and that several incident response topics were discussed.

It does not establish that participants followed an approved procedure, that escalation requirements were correctly applied, or that action items were completed.

Customer notification is also relevant to CTRL-009, Customer Incident Notification. However, this sample is primarily intended to assess CTRL-008. The notification discussion alone is not sufficient to establish that customer notification requirements are appropriately defined and implemented.

### Follow-up requests

* Obtain the exercise plan and final notes.
* Confirm whether the exercise covered the documented incident response process.
* Review the escalation decisions and recorded actions.
* Assign ownership for the action item without an owner.
* Obtain completion evidence for any action items reported as closed.
* Determine whether the exercise identified improvements to the incident response procedure.
* Confirm whether a separate notification procedure or exercise record exists for CTRL-009.

### Preliminary assessment

**Status:** Partially supported; follow-up required.

The sample provides evidence of an exercise record but does not independently demonstrate that incident response controls are fully designed or operating effectively.

---

## 7. Evidence Sample EVD-024: Change Management Record

**Control reference:** CTRL-012 — Change Management
**Evidence ID:** EVD-024
**Evidence type:** Synthetic production change record

### Sample record

| Field                      | Synthetic value                               |
| -------------------------- | --------------------------------------------- |
| Change ID                  | CHG-2026-104                                  |
| Change summary             | Production application configuration update   |
| Request date               | September 22, 2026                            |
| Implemented date           | September 24, 2026                            |
| Requester                  | Application Engineering                       |
| Change approval            | Approval timestamp not included in the sample |
| Testing evidence           | Test summary referenced but not attached      |
| Deployment record          | Available in the synthetic record             |
| Rollback plan              | Referenced but not attached                   |
| Post-implementation review | Not documented in the sample                  |

### Assessor notes

The record provides a change identifier, dates, a description, and a deployment reference.

It does not contain enough information to determine whether the change was approved before implementation, appropriately tested, or supported by a rollback plan.

The absence of supporting records in this sample does not establish that the activities did not occur. Follow-up is necessary before reaching a conclusion.

### Follow-up requests

* Obtain the approval record and verify its timing.
* Review the referenced test results.
* Obtain the rollback plan.
* Inspect the deployment record and determine whether it matches the approved change.
* Determine whether a post-implementation review was required.
* Obtain evidence of any required review.
* Compare the change with the documented change management procedure.

### Preliminary assessment

**Status:** Inconclusive pending evidence.

The missing supporting records should be investigated before concluding that the change management control failed.

---

## 8. Evidence Sample EVD-028: Third-Party Risk Assessment Record

**Control reference:** CTRL-014 — Third-Party Risk Management
**Evidence ID:** EVD-028
**Evidence type:** Synthetic vendor assessment record
**Vendor:** SignalBridge Support
**Vendor function:** Customer support platform

### Sample record

| Field                        | Synthetic value                    |
| ---------------------------- | ---------------------------------- |
| Vendor ID                    | VND-002                            |
| Assessment date              | September 15, 2026                 |
| Business owner               | Customer Operations                |
| Data access                  | Customer support records           |
| Inherent risk rating         | Moderate                           |
| Inherent risk score          | 3.30                               |
| Security questionnaire       | Received in the fictional scenario |
| Independent assurance report | Not provided in this sample        |
| Data retention terms         | Pending review                     |
| Subprocessor review          | Not documented in this sample      |
| Risk approval                | Not provided                       |
| Reassessment date            | Not established                    |

### Assessor notes

The sample documents a vendor assessment for SignalBridge Support and identifies a preliminary inherent risk score of 3.30, corresponding to the Moderate tier under the project's vendor risk assessment methodology.

The sample does not demonstrate that all identified risks were evaluated, that contractual safeguards were reviewed, or that the vendor was approved under a defined risk acceptance process.

The vendor's Moderate inherent risk rating does not eliminate the need to address the simulated data-exposure and excessive-permission weaknesses documented in the third-party risk workstream. Finding severity and inherent vendor risk tier are separate assessment concepts.

The absence of an assurance report in this sample does not establish that the vendor lacks one. Similarly, missing subprocessor documentation does not establish that subprocessors are used or that the vendor has failed to manage them.

The assessor must compare the available records with the organization's vendor risk management requirements and document any additional evidence needed.

### Follow-up requests

* Obtain the completed vendor questionnaire and supporting evidence.
* Review the contract and applicable data protection terms.
* Determine whether subprocessors are used and how they are assessed.
* Obtain the documented risk decision and any required safeguards.
* Confirm the business owner's approval responsibilities.
* Determine the required reassessment frequency.
* Confirm how identified risks and outstanding actions are tracked.

### Preliminary assessment

**Status:** Inconclusive pending additional documentation.

The sample indicates incomplete assessment documentation. A control conclusion requires comparison with the defined vendor risk management process.

---

## 9. Evidence Index

The following table maps each sample to the existing evidence request register. The IDs and control mappings must remain consistent with that register.

| Evidence ID | Evidence Name                            | Control ID | Evidence Type                   | Preliminary Assessment                      |
| ----------- | ---------------------------------------- | ---------- | ------------------------------- | ------------------------------------------- |
| EVD-008     | Access Review Records                    | CTRL-004   | Synthetic access review record  | Inconclusive                                |
| EVD-010     | Multifactor Authentication Configuration | CTRL-005   | Synthetic configuration summary | Potential exception requiring investigation |
| EVD-012     | Cloud Security Logging Configuration     | CTRL-006   | Synthetic configuration summary | Partially supported                         |
| EVD-016     | Incident Response Exercise Record        | CTRL-008   | Synthetic exercise record       | Partially supported                         |
| EVD-024     | Change Management Record                 | CTRL-012   | Synthetic change record         | Inconclusive                                |
| EVD-028     | Third-Party Risk Assessment Record       | CTRL-014   | Synthetic vendor assessment     | Inconclusive                                |

**Important:** The preliminary assessments in this index describe the fictional samples only. They are not final control-testing results or confirmed findings.

When recording evidence in `evidence-request-register.md`, use the existing evidence ID and control mapping. Do not create a second ID for an artifact that represents the same evidence request.

---

## 10. Relationship to the Evidence Request Register

The evidence request register contains 30 planned evidence requests. This document provides illustrative samples for six of them.

The samples do not mean the remaining evidence requests have been fulfilled.

For each sample used in assessment work:

1. Verify the evidence ID and control mapping.
2. Identify the relevant test procedure.
3. Document the artifact's synthetic origin.
4. Record whether the artifact is available for the exercise, requested from a fictional owner, or still planned.
5. Distinguish the existence of a portfolio-created sample from receipt of evidence from a real organization.
6. Record the procedures actually performed and the observations supported by the sample.
7. Identify additional evidence required to reach a conclusion.
8. Update the evidence request register only when the status is supported by the project's documented status definitions.

The evidence request register remains the authoritative source for request status. The presence of a sample in this document must not automatically change a request to Received.

**Status clarification:** The samples in this document were created for the portfolio exercise. They are not evidence collected from a real vendor or production environment. Their availability within the repository does not establish that the underlying control operates effectively.

The evidence request register should retain its documented request statuses unless the fictional scenario explicitly records a status change and the change is reflected consistently across the relevant workpapers.
