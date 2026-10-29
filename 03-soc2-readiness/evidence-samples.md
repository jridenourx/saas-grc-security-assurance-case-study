# Synthetic SOC 2 Assessment Evidence Samples

## 1. Purpose

This document contains fictional evidence samples for the Northstar Cloud Solutions SOC 2 readiness case study.

The samples are designed to demonstrate how a GRC analyst evaluates documentation, access records, security configurations, monitoring records, and operational procedures against defined controls.

**Important:** Northstar Cloud Solutions is fictional. These records are illustrative artifacts created for this portfolio. They were not collected from a real company, AWS account, employee population, or independent audit.

The samples should be evaluated against the relevant control objectives and test procedures before conclusions are recorded.

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

## 3. Evidence Sample EVD-003: User Access Review Record

**Control reference:** CTRL-003 — User Access Provisioning and Removal
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

The sample indicates that a review was documented for 24 accounts, but only 22 have recorded decisions.

The available sample does not establish whether the remaining accounts were reviewed through another documented process. It also does not establish whether inappropriate access exists.

### Follow-up requests

* Obtain the complete review record and reviewer decisions.
* Determine why two accounts lack documented decisions.
* Inspect evidence of follow-up on any access concerns.
* Confirm that the population is complete and reconciles to the relevant account inventory.

### Preliminary assessment

**Status:** Inconclusive pending follow-up.

Do not classify this as an operating failure solely because two decisions are missing from the sample. The missing documentation must be investigated.

---

## 4. Evidence Sample EVD-006: Multifactor Authentication Configuration

**Control reference:** CTRL-005 — Multifactor Authentication
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

The sample alone cannot establish whether the exclusions are justified, whether other authentication safeguards apply, or whether MFA was consistently enforced during the assessment period.

### Follow-up requests

* Obtain the complete account population and MFA configuration.
* Identify both excluded accounts and their business justification.
* Determine whether any excluded accounts have privileged access.
* Obtain approval and expiration records for any exceptions.
* Inspect relevant configuration and sign-in evidence.

### Preliminary assessment

**Status:** Potential exception requiring investigation.

Do not conclude that MFA is ineffective for the entire environment based solely on this summary. Evaluate the exclusions, scope, and applicable requirements first.

---

## 5. Evidence Sample EVD-010: Cloud Security Logging Configuration

**Control reference:** CTRL-006 — Security Logging and Monitoring
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

The sample supports only the limited conclusion that CloudTrail is shown as enabled in the synthetic configuration summary.

It does not establish complete coverage, appropriate retention, protection against unauthorized alteration, or effective alerting and monitoring.

### Follow-up requests

* Obtain the relevant trail configuration and account coverage.
* Inspect the destination and access restrictions for stored logs.
* Review retention and integrity-protection settings.
* Obtain examples of security alerts and documented follow-up.
* Determine whether logging is monitored according to the defined procedure.

### Preliminary assessment

**Status:** Partially supported; additional testing required.

The evidence supports a limited configuration observation, not a conclusion that cloud logging and monitoring are fully effective.

---

## 6. Evidence Sample EVD-016: Third-Party Risk Assessment Record

**Control reference:** CTRL-014 — Third-Party Risk Management
**Evidence type:** Synthetic vendor assessment record
**Vendor:** SignalBridge Support
**Vendor function:** Customer support platform

### Sample record

| Field                        | Synthetic value               |
| ---------------------------- | ----------------------------- |
| Vendor ID                    | VND-002                       |
| Assessment date              | September 15, 2026            |
| Business owner               | Customer Operations           |
| Data access                  | Customer support records      |
| Inherent risk rating         | High                          |
| Security questionnaire       | Received                      |
| Independent assurance report | Not provided in this sample   |
| Data retention terms         | Pending review                |
| Subprocessor review          | Not documented in this sample |
| Risk approval                | Not provided                  |
| Reassessment date            | Not established               |

### Assessor notes

The record documents a vendor assessment and a high inherent risk rating. However, it does not demonstrate that all identified risks were evaluated, that contractual safeguards were reviewed, or that the vendor was approved under a defined risk acceptance process.

The absence of an assurance report in this sample does not establish that the vendor lacks one.

### Follow-up requests

* Obtain the completed vendor questionnaire and supporting evidence.
* Review the contract and applicable data protection terms.
* Determine whether subprocessors are used and how they are assessed.
* Obtain the documented risk decision and any required safeguards.
* Confirm reassessment requirements and ownership.

### Preliminary assessment

**Status:** Inconclusive pending additional documentation.

The sample indicates incomplete assessment documentation. A control conclusion requires comparison with the organization's defined vendor risk management process.

---

## 7. Evidence Sample EVD-020: Incident Response Exercise Record

**Control reference:** CTRL-008 — Incident Response
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

The sample indicates that a tabletop exercise occurred and that several response topics were discussed. It does not establish that all participants followed an approved procedure, that customer notification obligations were correctly evaluated, or that action items were completed.

### Follow-up requests

* Obtain the exercise plan and final notes.
* Confirm whether the exercise covered the documented incident response process.
* Review the three action items and assign ownership where missing.
* Obtain completion evidence for closed action items.
* Determine whether the exercise identified improvements to the incident response procedure.

### Preliminary assessment

**Status:** Partially supported; follow-up required.

The sample provides evidence of an exercise record but does not independently demonstrate that incident response controls are fully designed or operating effectively.

---

## 8. Evidence Sample EVD-024: Change Management Record

**Control reference:** CTRL-012 — Change Management
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

The record provides a change identifier, dates, a description, and a deployment reference. It does not contain enough information to determine whether the change was approved before implementation, appropriately tested, or supported by a rollback plan.

### Follow-up requests

* Obtain the approval record and verify its timing.
* Review the referenced test results.
* Obtain the rollback plan.
* Inspect the deployment record and determine whether it matches the approved change.
* Establish whether a post-implementation review was required and performed.

### Preliminary assessment

**Status:** Inconclusive pending evidence.

The missing supporting records in this sample should be investigated before concluding that the change management control failed.

---

## 9. Evidence Index

| Evidence ID | Evidence Name                        | Control ID | Evidence Type                   | Initial Assessment                          |
| ----------- | ------------------------------------ | ---------- | ------------------------------- | ------------------------------------------- |
| EVD-003     | User Access Review Record            | CTRL-003   | Synthetic review record         | Inconclusive                                |
| EVD-006     | MFA Configuration Summary            | CTRL-005   | Synthetic configuration summary | Potential exception requiring investigation |
| EVD-010     | Cloud Security Logging Configuration | CTRL-006   | Synthetic configuration summary | Partially supported                         |
| EVD-016     | Third-Party Risk Assessment Record   | CTRL-014   | Synthetic vendor assessment     | Inconclusive                                |
| EVD-020     | Incident Response Exercise Record    | CTRL-008   | Synthetic exercise record       | Partially supported                         |
| EVD-024     | Change Management Record             | CTRL-012   | Synthetic change record         | Inconclusive                                |

**ID mapping note:** These samples use the existing evidence ID series as working references. Before marking any evidence request as received, verify that each ID matches the corresponding request in `evidence-request-register.md`. If the register assigns an ID to a different evidence item, preserve the register's established mapping and update these sample references consistently.

## 10. Assessment Limitations

These samples are intentionally incomplete to demonstrate evidence evaluation and follow-up.

They do not represent actual security configurations, real vendor conditions, or the results of a completed audit. They should not be used to claim that Northstar Cloud Solutions has passed or failed a SOC 2 examination.

Any final readiness conclusion must be based on the defined scope, applicable control criteria, complete evidence reviewed, test results, and documented limitations.
