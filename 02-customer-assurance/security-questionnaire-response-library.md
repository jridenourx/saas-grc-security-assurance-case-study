# Security Questionnaire Response Library

> **SIMULATION NOTICE:** This library contains sample responses for Northstar Cloud Solutions, a fictional SaaS company. Responses are illustrative drafts, not verified statements about a real organization's security posture.

## 1. Purpose

This library provides reusable draft responses to common customer security questions.

Its purpose is to improve consistency, reduce duplicated effort, and establish traceability between customer-facing statements, internal controls, and supporting evidence.

A reusable response must still be validated against the customer's question, the applicable service scope, and the evidence available at the time of submission.

## 2. Response Management Principles

All responses must follow these principles:

1. **Evidence first:** Do not make a security claim without appropriate supporting evidence.
2. **Scope accurately:** Specify the service, systems, or activities covered by the response where relevant.
3. **Distinguish design from operation:** A written policy does not prove that a control operates effectively.
4. **Disclose limitations:** Identify material gaps, exceptions, and restrictions on the available evidence.
5. **Avoid unsupported certifications:** Do not claim SOC 2 certification or a completed independent examination unless the applicable report exists and its scope has been verified.
6. **Review before reuse:** Revalidate responses when supporting evidence changes or a customer asks a materially different question.
7. **Protect sensitive information:** Share only approved evidence and use appropriate redactions.

## 3. Response Status Definitions

| Status    | Meaning                                                                                                |
| --------- | ------------------------------------------------------------------------------------------------------ |
| Draft     | A response has been prepared but has not completed review.                                             |
| In Review | The response and supporting evidence are being evaluated.                                              |
| Approved  | An authorized reviewer has approved the response for its defined scope.                                |
| Rejected  | The response was rejected because it was inaccurate, unsupported, incomplete, or otherwise unsuitable. |
| Expired   | The response requires revalidation before reuse.                                                       |

**Important:** The sample responses in this library are drafts. None should be considered approved for an actual customer.

## 4. Reusable Response Library

### RSP-001 — Information Security Policies

**Related questionnaire:** CQA-001

**Customer question:** Does your organization maintain documented information security policies?

**Draft response:**

Northstar's security program is being evaluated against a documented set of security governance expectations. The existence, approval status, and current applicability of the relevant policies must be confirmed before making a definitive statement about implementation.

**Evidence required:**

* Approved information security policy.
* Policy owner and approval record.
* Review history.

**Current response status:** In Review

**Approval requirement:** GRC and Security / IT.

**Limitation:** The fictional company profile describes a developing security program but does not establish that an approved information security policy exists.

---

### RSP-002 — Risk Management

**Related questionnaire:** CQA-003

**Customer question:** Does your organization maintain a documented process for identifying and managing security risks?

**Draft response:**

Northstar's proposed risk management process includes documented risk identification, risk evaluation, ownership, treatment planning, and tracking. The implementation status of the process and any operational records must be validated before this statement is used as a representation of the company's actual practices.

**Evidence required:**

* Approved risk assessment methodology.
* Current risk register.
* Risk ownership and approval records.
* Evidence of periodic review.

**Current response status:** In Review

**Approval requirement:** GRC and the designated risk owner.

**Limitation:** A proposed process or portfolio artifact does not establish that a real organization operates the process.

---

### RSP-003 — Least-Privilege Access

**Related questionnaire:** CQA-006

**Customer question:** Is access granted according to least-privilege principles?

**Draft response:**

Northstar's assessment criteria require access permissions to be aligned with documented business needs. Confirmation of implementation requires review of the applicable role definitions, assigned permissions, and relevant access-review evidence.

**Evidence required:**

* Access-control policy.
* Approved role-permission matrix.
* Relevant access assignments.
* Completed access-review records.

**Current response status:** In Review

**Approval requirement:** Security / IT.

**Limitation:** The fictional scenario does not establish that all production access permissions have been validated.

---

### RSP-004 — Multifactor Authentication

**Related questionnaire:** CQA-007

**Customer question:** Is multifactor authentication required for applicable privileged and remote access?

**Draft response:**

The applicable authentication requirements and their implementation status must be confirmed for the systems and access paths within the customer's assessment scope. A definitive statement requires evidence demonstrating the relevant MFA settings and coverage.

**Evidence required:**

* Authentication and MFA standard.
* Configuration evidence for the relevant systems.
* Defined scope of covered identities and access paths.
* Documented exceptions, if any.

**Current response status:** In Review

**Approval requirement:** Security / IT.

**Limitation:** A written MFA requirement alone does not demonstrate that all relevant accounts and access paths enforce MFA.

---

### RSP-005 — Security Logging

**Related questionnaire:** CQA-017

**Customer question:** Are relevant security events logged for systems supporting the service?

**Draft response:**

Northstar's logging assessment should identify the systems and security events within scope, the applicable logging requirements, and the evidence available to demonstrate coverage. The actual coverage and operation of logging must be validated before making a definitive customer-facing claim.

**Evidence required:**

* Logging standard.
* System and logging coverage inventory.
* Relevant configuration evidence.
* Evidence of monitoring and log protection, where applicable.

**Current response status:** In Review

**Approval requirement:** Security / IT and Engineering.

**Limitation:** The existence of a logging procedure does not establish complete system coverage or effective monitoring.

---

### RSP-006 — Incident Response

**Related questionnaire:** CQA-021

**Customer question:** Does your organization maintain a documented security incident response process?

**Draft response:**

The applicable incident response documentation, assigned responsibilities, and escalation arrangements must be reviewed to establish the organization's current position. Any statement about testing or demonstrated response effectiveness requires additional supporting evidence.

**Evidence required:**

* Incident response plan.
* Defined roles and escalation procedures.
* Relevant exercise or test records.
* Tracked improvements from exercises or incidents.

**Current response status:** In Review

**Approval requirement:** Security / IT and the designated incident response owner.

**Limitation:** A documented plan does not prove that the organization has successfully executed or tested the plan.

---

### RSP-007 — Data Retention and Deletion

**Related questionnaire:** CQA-014

**Customer question:** Are data retention and deletion requirements documented?

**Draft response:**

Northstar's data retention and deletion position must be established from the applicable data-handling requirements, retention schedules, service configuration, and contractual obligations. Any statement about completed deletion or verified retention behavior must be supported by appropriate evidence.

**Evidence required:**

* Data retention schedule.
* Deletion procedure.
* Relevant system settings or test evidence.
* Contractual requirements, where applicable.

**Current response status:** In Review

**Approval requirement:** Legal / Privacy, Security / IT, and the relevant data owner.

**Limitation:** A written retention policy does not establish that all systems, backups, and downstream copies follow the policy.

---

### RSP-008 — Third-Party Risk Management

**Related questionnaire:** CQA-031

**Customer question:** Are third-party service providers assessed according to their risk?

**Draft response:**

Northstar's proposed third-party risk management approach uses service scope, data sensitivity, system access, business criticality, and external dependency to guide assessment depth. Implementation and operating effectiveness must be supported by completed assessments, review records, and documented decisions.

**Evidence required:**

* Approved vendor risk methodology.
* Vendor inventory.
* Completed risk assessments.
* Evidence register and risk register.
* Monitoring and reassessment records.

**Current response status:** In Review

**Approval requirement:** GRC and the responsible business owner.

**Limitation:** A documented methodology does not establish that every relevant vendor has been assessed.

---

### RSP-009 — Independent Security Assurance

**Related questionnaire:** CQA-032

**Customer question:** Does your organization obtain or review independent security assurance?

**Draft response:**

The availability and applicability of independent security assurance must be confirmed using the relevant report or other authoritative documentation. Any response must identify the applicable service scope and reporting period and disclose material qualifications or exceptions relevant to the question.

**Evidence required:**

* Applicable independent assurance report, if available.
* Report period and scope.
* Relevant exceptions and qualifications.
* Evidence of review and follow-up, where applicable.

**Current response status:** In Review

**Approval requirement:** GRC and Security / IT.

**Limitation:** The fictional scenario does not establish that Northstar has obtained a SOC 2 report or another independent assurance report.

---

### RSP-010 — SOC 2 Status

**Related questionnaire:** CQA-039

**Customer question:** Has your organization completed an independent SOC 2 examination?

**Draft response:**

Northstar's SOC 2 status must be confirmed before this question is answered. A readiness assessment, internal control review, or plan to pursue an examination is not equivalent to a completed independent SOC 2 examination or an issued SOC 2 report.

**Evidence required:**

* Issued SOC 2 report, if one exists.
* Applicable report type and period.
* Covered service and system boundaries.
* Relevant exceptions or qualifications.

**Current response status:** In Review

**Approval requirement:** GRC, Security / IT, and the authorized business representative.

**Limitation:** Do not represent the simulated readiness work in this portfolio as a completed SOC 2 examination.

---

### RSP-011 — Vulnerability Management

**Related questionnaire:** CQA-027

**Customer question:** Are vulnerabilities identified, prioritized, and remediated?

**Draft response:**

The organization's vulnerability management process and its implementation must be validated against the relevant systems and assessment scope. A definitive response should be supported by documented procedures, relevant assessment results, prioritization criteria, and remediation records.

**Evidence required:**

* Vulnerability management procedure.
* Relevant vulnerability assessment results.
* Risk-based remediation criteria.
* Remediation tracking and validation evidence.

**Current response status:** In Review

**Approval requirement:** Security / IT and Engineering.

**Limitation:** The fictional scenario does not establish that vulnerability assessments have been performed or that remediation timelines have been met.

---

### RSP-012 — Customer Incident Notification

**Related questionnaire:** CQA-024

**Customer question:** Are customers notified of incidents affecting their information?

**Draft response:**

Customer incident notification requirements must be determined from applicable contractual commitments, legal requirements, and the documented incident response process. Any definitive statement should be reviewed by the appropriate legal, privacy, and security representatives.

**Evidence required:**

* Incident response and notification procedures.
* Applicable contractual provisions.
* Defined notification responsibilities.
* Relevant test records or incident documentation, where available and appropriate.

**Current response status:** In Review

**Approval requirement:** Legal / Privacy and Security / IT.

**Limitation:** Do not promise a specific notification period or legal outcome unless the applicable obligation has been verified.

---

## 5. Evidence Mapping and Traceability

The following table connects reusable responses to the questionnaire and the evidence needed to support them.

| Response ID | Questionnaire ID | Primary Evidence Required                                            | Related Internal Control |
| ----------- | ---------------- | -------------------------------------------------------------------- | ------------------------ |
| RSP-001     | CQA-001          | Approved security policy and review records                          | To be assigned           |
| RSP-002     | CQA-003          | Risk methodology and risk register                                   | To be assigned           |
| RSP-003     | CQA-006          | Role matrix, access assignments, and review records                  | To be assigned           |
| RSP-004     | CQA-007          | MFA requirements and scoped configuration evidence                   | To be assigned           |
| RSP-005     | CQA-017          | Logging requirements, coverage inventory, and configuration evidence | To be assigned           |
| RSP-006     | CQA-021          | Incident response plan and relevant exercise records                 | To be assigned           |
| RSP-007     | CQA-014          | Retention schedule, deletion procedure, and relevant test evidence   | To be assigned           |
| RSP-008     | CQA-031          | Vendor risk methodology and completed assessment records             | To be assigned           |
| RSP-009     | CQA-032          | Applicable independent assurance report and review records           | To be assigned           |
| RSP-010     | CQA-039          | Issued SOC 2 report, if one exists                                   | To be assigned           |
| RSP-011     | CQA-027          | Vulnerability assessment and remediation records                     | To be assigned           |
| RSP-012     | CQA-024          | Incident notification procedure and contractual requirements         | To be assigned           |

Internal control IDs will be assigned when the common control library is developed in the SOC 2 readiness workstream. Until then, do not invent control IDs or treat the mapping as complete.

## 6. Response Review and Approval Workflow

### Step 1 — Intake

Record the customer request, response deadline, applicable service, questionnaire version, and required reviewers.

### Step 2 — Scope Review

Confirm which systems, data categories, integrations, and services the questions cover. Identify questions that require clarification.

### Step 3 — Drafting

Use an existing response only if it accurately addresses the current question and scope. Otherwise, draft a tailored response.

### Step 4 — Evidence Validation

Check supporting evidence for relevance, completeness, reliability, and timeliness. Identify gaps and qualifications.

### Step 5 — Subject-Matter Review

Route technical questions to Security / IT or Engineering, contractual and privacy questions to Legal / Privacy, and risk or control questions to GRC as appropriate.

### Step 6 — Approval

Obtain approval from the designated authority before sending responses externally. Record material qualifications and any approved exceptions.

### Step 7 — Submission and Retention

Retain the submitted questionnaire, approved responses, supporting evidence references, reviewer decisions, and submission date in the appropriate repository.

### Step 8 — Revalidation

Revalidate responses when supporting evidence expires, controls materially change, an incident affects the claim, or a customer asks a materially different question.

## 7. Prohibited Response Practices

Do not:

* Claim SOC 2 compliance or certification without appropriate supporting facts.
* State that MFA is enforced everywhere based solely on a written policy.
* Claim that all vulnerabilities are remediated without evidence.
* Describe an untested recovery plan as proven effective.
* Treat a vendor questionnaire response as independent assurance.
* Omit material limitations that would make the response misleading.
* Send confidential technical evidence without authorization.
* Reuse an expired response without revalidation.

## 8. Current Limitations

All responses in this library remain drafts because the fictional scenario has not established the operational evidence needed to approve them.

The library demonstrates response governance and evidence traceability. It does not certify that Northstar Cloud Solutions has implemented the controls described.

## 9. Simulation Disclaimer

This library is a fictional portfolio artifact. The response wording must not be used to make unsupported claims about a real organization. In a real customer assurance process, each response must be validated against the current service scope, available evidence, and required approval process.
