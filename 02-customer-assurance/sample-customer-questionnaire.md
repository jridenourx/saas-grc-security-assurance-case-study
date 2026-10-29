# Sample Customer Security Questionnaire — Completed Simulation

> **SIMULATION NOTICE:** This document represents a fictional customer security review for Northstar Cloud Solutions. The customer, questions, responses, and supporting records are synthetic. This is a demonstration of the response process, not a representation of a real company's security posture.

## 1. Request Overview

| Field                   | Value                                        |
| ----------------------- | -------------------------------------------- |
| Request ID              | CQA-REQ-001                                  |
| Customer                | Acme Business Systems (fictional)            |
| Service Under Review    | Northstar Cloud Solutions SaaS platform      |
| Request Type            | Customer security due diligence              |
| Date Received           | 2026-10-29                                   |
| Requested Response Date | 2026-11-12                                   |
| Request Owner           | Customer Success                             |
| GRC Coordinator         | GRC                                          |
| Technical Reviewers     | Security / IT and Engineering, as applicable |
| Overall Status          | Draft — Pending Evidence Review and Approval |

The customer requests information about Northstar's security governance, identity and access management, logging, incident response, third-party oversight, and independent assurance.

The requested response date is a fictional planning date for this exercise.

## 2. Response Methodology

Each response is evaluated against the evidence described in the simulated project.

The following distinctions apply:

* **Supported:** The available evidence supports the specific statement within the stated scope.
* **Partially supported:** Some elements are supported, but material limitations remain.
* **Evidence gap:** The available material does not establish whether the requirement is met.
* **Not applicable:** The requirement does not apply, and the rationale is documented.

A question cannot be marked "Yes" merely because the project includes a proposed procedure or an assessment document.

The response statuses below are internal assessment outcomes. They are not claims of actual compliance.

## 3. Completed Questionnaire

### CQA-001 — Information Security Policies

**Customer question:** Does Northstar maintain documented information security policies?

**Draft response:** Northstar's security governance documentation is being developed as part of the defined security program. The available simulation materials do not establish that a complete, approved information security policy set is implemented and maintained in an operating organization.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Project charter and fictional company profile
**Limitation:** Project documentation does not prove that an approved operational policy exists.
**Required follow-up:** Obtain the approved policy set, policy owner, approval record, and review history.

### CQA-003 — Risk Management

**Customer question:** Does Northstar maintain a process to identify, assess, and track security risks?

**Draft response:** The case study defines a proposed risk assessment methodology and risk-tracking approach. Evidence of ongoing operational use, assigned risk owners, and periodic review has not been established.

**Internal assessment status:** Partially supported
**Supporting evidence:** `01-third-party-risk/vendor-risk-assessment-matrix.md` and `01-third-party-risk/risk-register.md`
**Limitation:** The existence of portfolio artifacts does not establish that the process operates in a real organization.
**Required follow-up:** Validate approval of the process and obtain evidence of its use, review, and risk decisions.

### CQA-006 — Least-Privilege Access

**Customer question:** Is access restricted according to business need and least-privilege principles?

**Draft response:** Least privilege is an assessment objective in the Northstar scenario. The available simulation does not establish that permissions across the production environment have been validated against approved business requirements.

**Internal assessment status:** Evidence gap
**Supporting evidence:** The planned technical validation workstream and applicable access-control assessment requirements
**Limitation:** A stated control objective does not demonstrate implementation.
**Required follow-up:** Review the role-permission matrix, assigned access, privileged roles, and completed access-review evidence.

### CQA-007 — Multifactor Authentication

**Customer question:** Is multifactor authentication enforced for applicable privileged and remote access?

**Draft response:** The MFA requirements and implementation status have not been sufficiently established for the full service scope in this simulation. A definitive answer requires appropriately scoped configuration evidence.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Planned IAM and MFA technical validation work
**Limitation:** No claim is made that MFA is enforced across all applicable accounts or access paths.
**Required follow-up:** Obtain the applicable authentication standard, configuration evidence, coverage information, and documented exceptions.

### CQA-014 — Data Retention and Deletion

**Customer question:** Are data retention and deletion requirements documented and implemented?

**Draft response:** The Northstar scenario identifies data retention and deletion as relevant assessment areas. The available materials do not establish the complete retention and deletion requirements or demonstrate that they are consistently enforced across the service and its supporting systems.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Fictional company profile and customer questionnaire requirements
**Limitation:** The scenario does not include verified retention settings or deletion-test results.
**Required follow-up:** Review the retention schedule, deletion procedures, relevant system configurations, and applicable contractual commitments.

### CQA-017 — Security Logging

**Customer question:** Are relevant security events logged for systems supporting the service?

**Draft response:** Security logging is included in the defined assessment scope. The available scenario evidence does not establish complete logging coverage or demonstrate the effectiveness of monitoring across all relevant systems.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Planned technical validation work and `01-third-party-risk/synthetic-vendor-assessments.md` where relevant to provider dependencies
**Limitation:** Provider-level evidence does not automatically establish logging coverage within Northstar's own application and environment.
**Required follow-up:** Review the system inventory, logging requirements, configuration evidence, retention settings, and monitoring procedures.

### CQA-021 — Incident Response

**Customer question:** Does Northstar maintain a documented incident response process?

**Draft response:** Incident response is identified as a required component of the proposed security program. The current simulation does not establish that an approved operational incident response plan exists or that the process has been exercised successfully.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Customer questionnaire and proposed GRC assessment scope
**Limitation:** No completed incident response exercise or operational incident record is established by the available materials.
**Required follow-up:** Obtain the approved response plan, role assignments, escalation procedures, and relevant exercise evidence.

### CQA-024 — Customer Incident Notification

**Customer question:** Are customers notified of incidents affecting their information?

**Draft response:** Customer notification requirements would need to be determined from applicable contractual commitments, legal requirements, and the approved incident response process. The available simulation does not establish a verified notification commitment for a real service.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Customer questionnaire and proposed incident response assessment requirements
**Limitation:** No specific notification timeline is represented as a verified commitment.
**Required follow-up:** Review applicable contract terms and obtain approval from the appropriate legal, privacy, and security representatives.

### CQA-027 — Vulnerability Management

**Customer question:** Are vulnerabilities identified, prioritized, and remediated?

**Draft response:** Vulnerability management is within the intended security assessment scope. The available simulation does not establish the operation of a complete vulnerability management process or demonstrate remediation performance against defined timelines.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Customer questionnaire and proposed technical assessment scope
**Limitation:** No production vulnerability scan or operational remediation record is established by the current scenario.
**Required follow-up:** Review the vulnerability management procedure, relevant assessment results, prioritization criteria, and remediation evidence.

### CQA-031 — Third-Party Risk Management

**Customer question:** Are third-party service providers assessed according to their risk?

**Draft response:** This portfolio case study documents a proposed risk-based vendor assessment methodology and applies it to three fictional vendor scenarios. It demonstrates how vendor risk can be classified, evidence gaps documented, and remediation actions tracked. It does not establish that a real organization operates this process.

**Internal assessment status:** Supported within the simulation scope
**Supporting evidence:** `01-third-party-risk/vendor-risk-assessment-matrix.md`, `01-third-party-risk/synthetic-vendor-assessments.md`, and `01-third-party-risk/vendor-lifecycle-procedure.md`
**Limitation:** The support applies only to the existence and documented application of the simulated methodology, not to a real operating environment.
**Required follow-up:** For a real customer response, validate the organization's approved process and current vendor assessment records.

### CQA-032 — Independent Security Assurance

**Customer question:** Does Northstar obtain or review independent security assurance?

**Draft response:** The current portfolio scenario does not establish that Northstar has obtained or completed an independent security assurance examination. Any applicable assurance report would need to be verified for scope, reporting period, and relevant exceptions before being referenced.

**Internal assessment status:** Evidence gap
**Supporting evidence:** Project scope and simulation disclaimer
**Limitation:** No independent assurance report is established in this scenario.
**Required follow-up:** Confirm whether an applicable report exists. If none exists, do not imply that independent assurance has been completed.

### CQA-039 — SOC 2 Examination

**Customer question:** Has Northstar completed an independent SOC 2 examination and received a report?

**Draft response:** The current case study does not establish that Northstar has completed an independent SOC 2 examination or received a SOC 2 report. The planned SOC 2 readiness workstream is a simulated internal assessment and must not be represented as an independent examination.

**Internal assessment status:** Evidence gap — examination status unverified for any real organization
**Supporting evidence:** Project charter and project scope
**Limitation:** A readiness assessment is not equivalent to an issued SOC 2 report.
**Required follow-up:** Confirm the actual examination status with the authorized company representative before responding to a real customer.

## 4. Response Summary

| Questionnaire ID | Topic                    | Internal Assessment Status        | Key Follow-Up                                  |
| ---------------- | ------------------------ | --------------------------------- | ---------------------------------------------- |
| CQA-001          | Security policies        | Evidence gap                      | Obtain approved policies and review records    |
| CQA-003          | Risk management          | Partially supported               | Validate operational use and governance        |
| CQA-006          | Least privilege          | Evidence gap                      | Review permissions and access reviews          |
| CQA-007          | MFA                      | Evidence gap                      | Validate configuration and coverage            |
| CQA-014          | Data retention           | Evidence gap                      | Review retention and deletion evidence         |
| CQA-017          | Logging                  | Evidence gap                      | Validate coverage and monitoring               |
| CQA-021          | Incident response        | Evidence gap                      | Obtain plan and exercise evidence              |
| CQA-024          | Customer notification    | Evidence gap                      | Confirm contractual and legal requirements     |
| CQA-027          | Vulnerability management | Evidence gap                      | Review assessment and remediation records      |
| CQA-031          | Third-party risk         | Supported within simulation scope | Validate actual implementation before real use |
| CQA-032          | Independent assurance    | Evidence gap                      | Confirm report availability and scope          |
| CQA-039          | SOC 2 examination        | Evidence gap                      | Verify actual examination status               |

The internal assessment statuses above do not represent final answers approved for external submission. They identify the current state of the fictional evidence package.

## 5. Internal Review Record

| Review Field                     | Current Status                           |
| -------------------------------- | ---------------------------------------- |
| Questionnaire owner assigned     | Yes — proposed role                      |
| Scope confirmed                  | Pending                                  |
| Evidence reviewed                | Partially; based on simulation materials |
| Technical review completed       | Pending                                  |
| Legal / Privacy review completed | Pending where applicable                 |
| GRC review completed             | Pending                                  |
| Final approval                   | Pending                                  |
| Approved for external submission | No                                       |

## 6. Required Actions Before External Submission

Before a real customer questionnaire is sent:

1. Confirm the actual customer, service, and system scope.
2. Replace fictional evidence references with approved organizational evidence.
3. Validate each response against current implementation.
4. Obtain subject-matter review for technical, contractual, and privacy-related statements.
5. Resolve or appropriately qualify material evidence gaps.
6. Obtain the required approval.
7. Retain the final submitted questionnaire and approval record.

## 7. Lessons Demonstrated

This exercise illustrates three important GRC practices:

* **A response must reflect evidence, not intention.** A planned control or proposed procedure does not establish implementation.
* **Evidence gaps are not automatically control failures.** Missing proof should trigger follow-up and an appropriately qualified response.
* **Customer assurance is a governance process.** Responses require ownership, review, approval, and traceability.

## 8. Simulation Disclaimer

This document is a fictional portfolio exercise. It does not represent a completed customer assessment, verified control effectiveness, independent audit, or actual SOC 2 status for any real organization.
