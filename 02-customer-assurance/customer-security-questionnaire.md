# Customer Security Questionnaire

> **SIMULATION NOTICE:** This questionnaire is designed for Northstar Cloud Solutions, a fictional SaaS provider. It is a portfolio artifact and does not represent a completed security review of a real organization.

## 1. Purpose

This questionnaire provides a standardized way for Northstar Cloud Solutions to collect and review information about its security and compliance practices when responding to prospective or existing customers.

It is intended to support consistent responses, identify questions requiring subject-matter review, and link security claims to relevant evidence.

The questionnaire should be tailored to the customer's service scope and actual requirements before use.

## 2. Instructions

For each question, the response owner should:

1. Review the question and confirm that it applies to the service being evaluated.
2. Identify the relevant policy, procedure, control, or technical evidence.
3. Draft a response that accurately reflects the available evidence.
4. Record any limitations or outstanding validation requirements.
5. Obtain the required review and approval before sending the response externally.

Do not answer "Yes" merely because a policy or procedure exists. A claim about a control's operation should be supported by evidence appropriate to that claim.

### Response Options

| Response       | Definition                                                                         |
| -------------- | ---------------------------------------------------------------------------------- |
| Yes            | The requirement is met within the stated scope, supported by appropriate evidence. |
| Partially      | Some elements are implemented, but material limitations or gaps remain.            |
| No             | The requirement is not met within the assessed scope.                              |
| Not Applicable | The requirement does not apply, with a documented rationale.                       |
| Under Review   | The response is awaiting evidence, validation, or approval.                        |

"Under Review" is an internal workflow status, not necessarily an acceptable final answer to a customer.

## 3. Company and Service Overview

| Field               | Description                                                                        |
| ------------------- | ---------------------------------------------------------------------------------- |
| Company             | Northstar Cloud Solutions                                                          |
| Service             | Fictional business-to-business SaaS platform                                       |
| Hosting             | Amazon Web Services (AWS)                                                          |
| Data Types          | Customer business records, customer account information, application activity logs |
| Assessment Scope    | To be confirmed for each customer request                                          |
| Questionnaire Owner | Customer Success / Sales, with GRC coordination                                    |
| Technical Review    | Security / IT and Engineering, as applicable                                       |
| Final Approval      | Authorized business and security representatives                                   |

The service description and data categories are scenario assumptions. They must be confirmed and adapted to the relevant service scope before any real-world use.

## 4. Security Governance and Policies

| ID      | Question                                                                                    | Evidence to Consider                                         |
| ------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| CQA-001 | Does the organization maintain documented information security policies?                    | Approved information security policy and review history      |
| CQA-002 | Are security responsibilities assigned to appropriate personnel or functions?               | Roles and responsibilities matrix                            |
| CQA-003 | Are security risks identified, assessed, and tracked through a documented process?          | Risk assessment methodology and risk register                |
| CQA-004 | Are security policies and procedures reviewed periodically and when material changes occur? | Policy review schedule and approval records                  |
| CQA-005 | Is there a process for tracking and remediating identified security weaknesses?             | Findings register, remediation tracker, and closure criteria |

## 5. Identity and Access Management

| ID      | Question                                                                                           | Evidence to Consider                                       |
| ------- | -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| CQA-006 | Is access granted according to defined business requirements and least-privilege principles?       | Access-control policy, role matrix, and permission review  |
| CQA-007 | Is multifactor authentication required for applicable privileged and remote access?                | MFA policy and appropriately scoped configuration evidence |
| CQA-008 | Are user access rights reviewed periodically?                                                      | Access-review procedure and completed review records       |
| CQA-009 | Is access removed or modified promptly when a user's role changes or access is no longer required? | Joiner-mover-leaver procedure and sample records           |
| CQA-010 | Are privileged accounts identified and subject to additional safeguards?                           | Privileged-access standard and account inventory           |

## 6. Data Protection and Privacy

| ID      | Question                                                                                           | Evidence to Consider                                               |
| ------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| CQA-011 | Is customer information handled according to documented data-protection requirements?              | Data-handling policy and relevant procedures                       |
| CQA-012 | Are data flows and categories of information processed by the service documented?                  | Data-flow diagrams and data inventory                              |
| CQA-013 | Is information collected and processed limited to legitimate, documented business purposes?        | Data-minimization requirements and system design                   |
| CQA-014 | Are data retention and deletion requirements documented?                                           | Retention schedule and deletion procedures                         |
| CQA-015 | Are safeguards in place to protect customer information against unauthorized access or disclosure? | Security architecture, access controls, and relevant test evidence |
| CQA-016 | Are external service providers that may handle customer information identified and evaluated?      | Vendor inventory, risk assessments, and subprocessor records       |

## 7. Security Operations and Monitoring

| ID      | Question                                                                        | Evidence to Consider                                                    |
| ------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| CQA-017 | Are relevant security events logged for systems within the service scope?       | Logging standard, system coverage inventory, and configuration evidence |
| CQA-018 | Are security logs protected against unauthorized access or modification?        | Logging architecture and access permissions                             |
| CQA-019 | Are security events reviewed or monitored according to documented requirements? | Monitoring procedures, alert rules, and review records                  |
| CQA-020 | Are logging coverage and retention requirements defined?                        | Logging policy, retention settings, and coverage review                 |

## 8. Incident Response and Business Continuity

| ID      | Question                                                                                                                | Evidence to Consider                                                |
| ------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| CQA-021 | Is there a documented process for identifying, reporting, and responding to security incidents?                         | Incident response plan and escalation procedure                     |
| CQA-022 | Are incident response responsibilities assigned to appropriate personnel?                                               | Incident response roles and contact procedures                      |
| CQA-023 | Are incident response procedures exercised or tested periodically?                                                      | Exercise records, test results, and tracked improvements            |
| CQA-024 | Are customers notified of incidents affecting their information in accordance with applicable contractual requirements? | Incident notification procedure and relevant contractual provisions |
| CQA-025 | Are backup and recovery requirements documented for systems supporting the service?                                     | Backup policy, recovery procedures, and defined objectives          |
| CQA-026 | Are recovery capabilities tested and results documented?                                                                | Recovery test records and remediation actions                       |

## 9. Vulnerability, Change, and Development Management

| ID      | Question                                                                             | Evidence to Consider                                       |
| ------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| CQA-027 | Are vulnerabilities identified, assessed, prioritized, and remediated?               | Vulnerability management procedure and remediation records |
| CQA-028 | Are material system changes reviewed and approved before implementation?             | Change-management procedure and change records             |
| CQA-029 | Are security requirements considered during application development and testing?     | Secure development standard and relevant test evidence     |
| CQA-030 | Are production access and deployment permissions restricted to authorized personnel? | Deployment permissions, role matrix, and approval records  |

## 10. Third-Party Risk and Assurance

| ID      | Question                                                                                                         | Evidence to Consider                                                  |
| ------- | ---------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| CQA-031 | Are third-party service providers assessed according to their risk and service scope?                            | Vendor risk methodology and completed assessments                     |
| CQA-032 | Is independent security assurance obtained or reviewed where appropriate?                                        | Applicable assurance reports, scope, reporting period, and exceptions |
| CQA-033 | Are material vendor risks and remediation activities tracked?                                                    | Vendor risk register and remediation tracker                          |
| CQA-034 | Are material changes in vendor services or security posture evaluated?                                           | Vendor monitoring and reassessment records                            |
| CQA-035 | Does the organization maintain a process for reviewing customer security questionnaires and approving responses? | Questionnaire workflow, response library, and approval records        |

## 11. Compliance and Independent Assurance

| ID      | Question                                                                               | Evidence to Consider                                         |
| ------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| CQA-036 | Has the organization defined the scope of its security and compliance program?         | Documented system scope and applicable control criteria      |
| CQA-037 | Are security controls mapped to relevant requirements or frameworks where appropriate? | Control matrix and mapping rationale                         |
| CQA-038 | Is evidence collected to support control assessments and compliance activities?        | Evidence register and evidence review records                |
| CQA-039 | Has the organization completed an independent SOC 2 examination and received a report? | Issued SOC 2 report, if one exists                           |
| CQA-040 | Are control deficiencies and readiness gaps tracked through remediation?               | Findings register, remediation tracker, and closure evidence |

**Important:** CQA-039 must be answered based on the organization's actual status. A readiness assessment, internal review, or planned examination must not be described as a completed independent SOC 2 examination.

## 12. Response Record Template

Use the following fields to record a response for each question.

| Field                        | Description                                          |
| ---------------------------- | ---------------------------------------------------- |
| Question ID                  | Unique questionnaire identifier                      |
| Customer Question            | Original question or an approved equivalent          |
| Applicability                | Applicable, not applicable, or pending determination |
| Draft Response               | Proposed customer-facing answer                      |
| Response Status              | Yes, Partially, No, Not Applicable, or Under Review  |
| Supporting Control           | Relevant internal control ID, when assigned          |
| Supporting Evidence          | Evidence IDs or approved artifact references         |
| Evidence Limitation          | Known gaps, exclusions, or qualification             |
| Response Owner               | Person or function responsible for the answer        |
| Reviewer                     | Required technical, security, legal, or GRC reviewer |
| Approval Status              | Draft, In Review, Approved, or Rejected              |
| Last Validated               | Date supporting information was last reviewed        |
| Expiration or Review Trigger | Date or event requiring revalidation                 |

## 13. Response Quality Requirements

Before a response is approved, confirm that:

* The answer addresses the actual question.
* The response matches the service and system scope.
* Supporting evidence is relevant and sufficiently current.
* Any limitations are accurately disclosed.
* The response does not claim an unverified certification or independent assurance report.
* The response does not imply that a policy proves operating effectiveness.
* Any "Not Applicable" response includes a rationale.
* The appropriate reviewer has approved the answer.

## 14. Simulation Disclaimer

This questionnaire is a fictional portfolio artifact. It does not establish that Northstar Cloud Solutions has implemented the controls described in the questions.

Responses must be completed and validated against appropriate evidence before they are used to represent the security posture of an actual organization.
