# Customer Security Questionnaire Review and Approval Procedure

> **SIMULATION NOTICE:** This procedure defines a proposed workflow for Northstar Cloud Solutions, a fictional SaaS company. It does not establish that the process has been implemented by a real organization.

## 1. Purpose

This procedure establishes a consistent process for receiving, completing, reviewing, approving, submitting, and retaining customer security questionnaires.

The objective is to provide accurate, evidence-backed responses while protecting confidential information and maintaining clear accountability.

## 2. Scope

This procedure applies to customer security questionnaires, due diligence requests, security assessment forms, and similar requests concerning Northstar's security and compliance practices.

It applies to requests involving the SaaS service, its supporting systems, relevant vendors, and associated security controls.

## 3. Roles and Responsibilities

| Role                     | Responsibilities                                                                                                          |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| Customer Success / Sales | Receives requests, coordinates customer deadlines, and manages customer communications                                    |
| GRC                      | Coordinates the response workflow, identifies evidence requirements, maintains the response library, and tracks approvals |
| Security / IT            | Reviews identity, access, infrastructure, logging, incident response, and related technical statements                    |
| Engineering              | Validates application architecture, development practices, technical configurations, and remediation claims               |
| Legal / Privacy          | Reviews contractual, privacy, data-handling, and incident notification statements                                         |
| Business Owner           | Confirms business context and ensures the response is appropriate for the customer relationship                           |
| Authorized Approver      | Provides final approval according to the organization's delegated authority                                               |

A single individual may perform multiple roles in a small organization, provided the required reviews and approvals remain appropriate to the risk.

## 4. Workflow Overview

The questionnaire workflow consists of eight stages:

1. Intake and registration.
2. Scope and deadline confirmation.
3. Question assignment and evidence identification.
4. Response drafting.
5. Evidence and subject-matter review.
6. Final approval.
7. Submission and record retention.
8. Revalidation and continuous improvement.

Each request should have a traceable record from receipt through final disposition.

## 5. Stage 1 — Intake and Registration

When a customer request is received, Customer Success / Sales should notify the designated questionnaire coordinator.

The coordinator records:

* Request ID.
* Customer name.
* Date received.
* Requested response date.
* Service under review.
* Questionnaire format and version.
* Customer-specific instructions.
* Internal request owner.
* Required reviewers.
* Current workflow status.

A unique request ID should be assigned even when the customer sends a revised questionnaire.

**Required output:** Registered request with a named owner and deadline.

## 6. Stage 2 — Scope and Deadline Confirmation

The coordinator confirms:

* Which service or product is being evaluated.
* Whether the request concerns existing or prospective use.
* What data the customer expects to process.
* Whether specific environments, integrations, or vendors are in scope.
* Whether the customer requires supporting documents.
* Whether contractual, regulatory, or privacy considerations require additional review.

If a question is ambiguous, the coordinator should request clarification or document the interpretation used.

The coordinator should identify the most time-sensitive questions and assign reviewers early enough to allow meaningful validation.

**Required output:** Confirmed assessment scope, deadline, and review plan.

## 7. Stage 3 — Question Assignment and Evidence Identification

Questions should be grouped by subject area and assigned to appropriate reviewers.

| Subject Area                              | Primary Reviewer                               |
| ----------------------------------------- | ---------------------------------------------- |
| Governance and risk management            | GRC                                            |
| Identity and access management            | Security / IT                                  |
| Cloud infrastructure and logging          | Security / IT                                  |
| Application security and development      | Engineering                                    |
| Data protection and privacy               | Legal / Privacy, with technical support        |
| Incident response and business continuity | Security / IT                                  |
| Third-party risk management               | GRC and the relevant business owner            |
| Contractual commitments                   | Legal / Privacy                                |
| Independent assurance and SOC 2 status    | GRC and the authorized business representative |

For each question, identify:

* The relevant response-library entry, if one exists.
* The supporting control or process.
* Required evidence.
* Evidence owner.
* Known limitations.
* Required reviewer and approver.

**Required output:** Assigned questions with documented evidence requirements.

## 8. Stage 4 — Response Drafting

The response owner should use the response library when the existing language accurately addresses the customer's question and scope.

If the question differs materially, the owner should adapt the response rather than copying it without review.

Responses should:

* Directly answer the question.
* Use precise, understandable language.
* Avoid unnecessary technical detail.
* State relevant scope limitations.
* Disclose material exceptions.
* Avoid unsupported statements about certifications or independent assurance.
* Avoid guarantees that cannot be substantiated.

When evidence is missing, the response owner should document the gap and determine whether the appropriate next step is additional evidence collection, a qualified response, or escalation.

**Required output:** Draft responses with supporting evidence references and identified limitations.

## 9. Stage 5 — Evidence and Subject-Matter Review

The designated reviewer evaluates the draft and its supporting material.

### Evidence Review Criteria

**Relevance:** Does the evidence support the specific claim?

**Scope:** Does it cover the service, systems, identities, or processes addressed by the question?

**Reliability:** Is the evidence sufficiently authoritative for the claim being made?

**Currency:** Is it current enough to support the response?

**Completeness:** Are important exclusions, exceptions, or gaps identified?

**Consistency:** Does the response agree with other approved documentation and known assessment results?

### Review Outcomes

| Outcome                      | Required Action                                                                  |
| ---------------------------- | -------------------------------------------------------------------------------- |
| Approved for final review    | Evidence and wording are adequate for the defined scope                          |
| Revision required            | Response wording or supporting documentation must be corrected                   |
| Additional evidence required | The response remains pending until the necessary evidence is evaluated           |
| Escalation required          | A material risk, uncertainty, or approval issue requires a higher-level decision |
| Not applicable               | The rationale must be documented and reviewed where appropriate                  |

An evidence gap does not automatically establish that a control has failed. However, the response must not imply that the control has been verified when it has not.

**Required output:** Documented reviewer decision, comments, and outstanding actions.

## 10. Stage 6 — Final Approval

Before submission, the designated approver confirms that:

* The assessment scope is accurate.
* Material questions have been addressed.
* Responses are supported by appropriate evidence.
* Required technical and legal reviews are complete.
* Material limitations are disclosed.
* Supporting documents are approved for release.
* No unsupported certification or compliance claim is included.

The approver records the decision, approval date, and any conditions.

If a material response changes after approval, the changed response must be reviewed again before submission.

**Required output:** Approved final questionnaire and recorded approval.

## 11. Stage 7 — Submission and Record Retention

The designated customer-facing owner submits the approved response through the appropriate channel.

The organization should retain:

* Original customer request.
* Final submitted questionnaire.
* Supporting evidence references.
* Relevant approved documents.
* Reviewer comments and decisions.
* Final approval record.
* Submission date.
* Material follow-up questions and subsequent responses.

Access to retained records should be limited according to their confidentiality and business purpose.

Customer information and sensitive technical evidence should not be disclosed beyond the approved scope.

**Required output:** Traceable submission record and retained supporting documentation.

## 12. Stage 8 — Revalidation and Continuous Improvement

The response library should be reviewed when:

* Supporting evidence expires or becomes outdated.
* A relevant control or system changes materially.
* A security incident affects a previous claim.
* An assessment identifies a material deficiency.
* A customer asks a question that exposes an ambiguity.
* A certification or assurance-report status changes.
* A contractual or regulatory obligation changes.

Repeated questions and recurring evidence gaps should be reviewed to identify opportunities to improve documentation and control ownership.

A response should not be reused solely because it was approved for a previous customer.

**Required output:** Updated response library, revised evidence references, and documented review dates.

## 13. Proposed Service-Level Targets

The following targets are illustrative internal planning goals for this case study, not regulatory requirements or established commitments.

| Activity                               | Proposed Target                                   |
| -------------------------------------- | ------------------------------------------------- |
| Register new request                   | Within one business day of receipt                |
| Confirm scope and deadline             | Within two business days of receipt               |
| Assign questions and reviewers         | Within two business days after scope confirmation |
| Escalate a likely deadline risk        | As soon as identified                             |
| Complete final review                  | Before the agreed submission deadline             |
| Revalidate a material changed response | Before its next external use                      |

Complex questionnaires may require different timelines. The coordinator should agree on realistic deadlines with the customer-facing owner and reviewers.

## 14. Metrics and Reporting

The coordinator may track:

* Number of questionnaires received.
* Number submitted by the agreed deadline.
* Average completion time.
* Percentage of responses requiring revision.
* Number of responses awaiting evidence.
* Number of overdue reviewer actions.
* Number of responses reused from the approved library.
* Number of expired responses identified before reuse.

Metrics should be interpreted in context. For example, a high response-library reuse rate is not necessarily beneficial if the reused responses are outdated or do not match the customer's scope.

## 15. Exceptions and Escalations

Escalation is appropriate when:

* A material claim lacks adequate evidence.
* A requested statement conflicts with known assessment results.
* The customer requests a certification or assurance report that is not available.
* The response could create a contractual commitment.
* Confidential information may be disclosed.
* Reviewers disagree about a material risk or claim.
* The response deadline cannot reasonably be met.

Any approved exception should document the issue, decision, approving authority, rationale, and any conditions.

## 16. Simulation Disclaimer

This procedure is a proposed process for a fictional organization. It demonstrates questionnaire governance and evidence management but does not establish that a real organization has implemented the process or achieved a particular compliance status.
