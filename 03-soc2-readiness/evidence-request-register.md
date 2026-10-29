# SOC 2 Readiness Evidence Request Register

> **SIMULATION NOTICE:** This register defines proposed evidence requests for Northstar Cloud Solutions, a fictional SaaS provider. All evidence examples and records created for this portfolio must be clearly labeled as synthetic.

## 1. Purpose

The evidence request register tracks documentation and records needed to assess the controls in the SOC 2 readiness control matrix.

It supports evidence collection, accountability, review, and traceability between controls, risks, findings, and remediation actions.

A request being listed in this register does not mean the evidence has been provided or reviewed.

**Portfolio-sample distinction:** The synthetic artifacts in `evidence-samples.md` were drafted for this portfolio exercise. They do not mean that evidence requests were issued to a real or fictional production owner, or that production evidence was received. Therefore, the request statuses below remain **Not Requested** unless a request was explicitly issued within the simulation. The separate assessment-results register records six controls as In Progress because preliminary samples have been drafted; that status does not change the request status or establish completed testing.

## 2. Evidence Status Definitions

| Status         | Definition                                                                                           |
| -------------- | ---------------------------------------------------------------------------------------------------- |
| Not Requested  | The evidence request has not been issued.                                                            |
| Requested      | The request has been assigned or issued to the proposed evidence owner.                              |
| Received       | The evidence artifact has been obtained but not yet evaluated.                                       |
| Under Review   | The evidence is being evaluated for relevance, scope, reliability, and completeness.                 |
| Accepted       | The evidence is suitable for the specific assessment purpose, subject to its documented limitations. |
| Rejected       | The evidence is unsuitable or insufficient for the intended assessment purpose.                      |
| Not Available  | The requested evidence cannot currently be provided. The reason should be documented.                |
| Not Applicable | The request does not apply, with a documented rationale and appropriate review.                      |

**Important:** "Accepted" means the evidence is suitable for the intended assessment procedure. It does not automatically mean the control is effective.

## 3. Evidence Request Register

The requests below are planned for the simulated assessment. Their initial status is **Not Requested**.

| Evidence ID | Control ID | Evidence Requested                                                         | Proposed Evidence Owner | Assessment Purpose                                                | Initial Status |
| ----------- | ---------- | -------------------------------------------------------------------------- | ----------------------- | ----------------------------------------------------------------- | -------------- |
| EVD-001     | CTRL-001   | Approved information security policies and review records                  | Security / IT           | Evaluate policy governance and review requirements                | Not Requested  |
| EVD-002     | CTRL-001   | Security responsibilities matrix and approval records                      | GRC                     | Evaluate assignment of security responsibilities                  | Not Requested  |
| EVD-003     | CTRL-002   | Risk assessment methodology and scoring criteria                           | GRC                     | Evaluate whether risk assessment criteria are documented          | Not Requested  |
| EVD-004     | CTRL-002   | Risk register with owners, treatment decisions, and review records         | GRC                     | Evaluate risk identification and follow-up                        | Not Requested  |
| EVD-005     | CTRL-003   | User provisioning, role-change, and access-removal procedures              | Security / IT           | Evaluate the documented access lifecycle                          | Not Requested  |
| EVD-006     | CTRL-003   | Synthetic access request and termination records                           | Security / IT           | Test authorization and access lifecycle processing                | Not Requested  |
| EVD-007     | CTRL-004   | Privileged account inventory and approved role-permission matrix           | Security / IT           | Evaluate privileged access and least privilege                    | Not Requested  |
| EVD-008     | CTRL-004   | Access-review records and documented exceptions                            | Security / IT           | Evaluate review completion and exception handling                 | Not Requested  |
| EVD-009     | CTRL-005   | Authentication standard and documented MFA requirements                    | Security / IT           | Establish the required MFA scope                                  | Not Requested  |
| EVD-010     | CTRL-005   | Synthetic MFA configuration summary and coverage information               | Security / IT           | Compare configured MFA settings with requirements                 | Not Requested  |
| EVD-011     | CTRL-006   | System inventory and security logging requirements                         | Security / IT           | Establish the required logging scope                              | Not Requested  |
| EVD-012     | CTRL-006   | Synthetic logging configuration, sample events, and monitoring records     | Security / IT           | Evaluate logging coverage and monitoring evidence                 | Not Requested  |
| EVD-013     | CTRL-007   | Log access permissions and retention requirements                          | Security / IT           | Evaluate log protection and retention settings                    | Not Requested  |
| EVD-014     | CTRL-007   | Synthetic log retention configuration and exception records                | Security / IT           | Compare actual or simulated settings with requirements            | Not Requested  |
| EVD-015     | CTRL-008   | Incident response plan, roles, and escalation procedures                   | Security / IT           | Evaluate incident response design                                 | Not Requested  |
| EVD-016     | CTRL-008   | Synthetic incident exercise record and corrective action log               | Security / IT           | Evaluate exercise results and follow-up                           | Not Requested  |
| EVD-017     | CTRL-009   | Applicable customer notification requirements and procedure                | Legal / Privacy         | Evaluate notification obligations and documented responsibilities | Not Requested  |
| EVD-018     | CTRL-009   | Synthetic notification workflow or exercise record                         | Legal / Privacy         | Evaluate whether the process can be followed as designed          | Not Requested  |
| EVD-019     | CTRL-010   | Data inventory, data-flow documentation, and handling requirements         | Security / IT           | Establish the data and system scope                               | Not Requested  |
| EVD-020     | CTRL-010   | Retention schedule, deletion procedure, and synthetic test results         | Engineering             | Evaluate retention and deletion requirements                      | Not Requested  |
| EVD-021     | CTRL-011   | Vulnerability management procedure and prioritization criteria             | Security / IT           | Evaluate vulnerability management design                          | Not Requested  |
| EVD-022     | CTRL-011   | Synthetic vulnerability records and remediation evidence                   | Engineering             | Evaluate issue prioritization, treatment, and closure             | Not Requested  |
| EVD-023     | CTRL-012   | Change management procedure and approval requirements                      | Engineering             | Evaluate change management design                                 | Not Requested  |
| EVD-024     | CTRL-012   | Synthetic change records, testing evidence, and approvals                  | Engineering             | Test selected change records against defined requirements         | Not Requested  |
| EVD-025     | CTRL-013   | Secure development requirements and security testing procedure             | Engineering             | Evaluate documented development safeguards                        | Not Requested  |
| EVD-026     | CTRL-013   | Synthetic release records and deployment permission summary                | Engineering             | Evaluate security testing and deployment authorization            | Not Requested  |
| EVD-027     | CTRL-014   | Vendor inventory, risk-tiering methodology, and due diligence records      | GRC                     | Evaluate the third-party risk management process                  | Not Requested  |
| EVD-028     | CTRL-014   | Synthetic vendor assessments, evidence references, and remediation records | GRC                     | Evaluate application of vendor assessment criteria                | Not Requested  |
| EVD-029     | CTRL-015   | Questionnaire review procedure and response library                        | GRC                     | Evaluate the design of customer assurance governance              | Not Requested  |
| EVD-030     | CTRL-015   | Synthetic completed questionnaire and reviewer approval record             | GRC                     | Trace customer-facing claims to evidence and approvals            | Not Requested  |

## 4. Evidence Handling Requirements

For each received artifact, record:

* Evidence ID.
* Control ID.
* Artifact name and description.
* Source or provider.
* Date received or created.
* Relevant assessment period, if applicable.
* Evidence status.
* Reviewer.
* Review date.
* Limitations or exceptions.
* Storage location or repository path.

Evidence should be appropriate to the assessment purpose. A procedure may support an evaluation of control design, while configuration records or transaction samples may be needed to evaluate implementation or operation.

## 5. Evidence Quality Review

Reviewers should consider:

**Relevance:** Does the artifact address the control being assessed?

**Scope:** Does it cover the relevant system, process, account, or vendor?

**Reliability:** Is the source sufficiently trustworthy for the intended conclusion?

**Currency:** Is the evidence current enough for the assessment?

**Completeness:** Are material periods, systems, records, or exceptions missing?

**Traceability:** Can the artifact be linked to the control and the procedure performed?

**Integrity:** Is the artifact maintained in a way that supports confidence that it has not been inappropriately altered?

Document limitations rather than assuming missing information is immaterial.

## 6. Evidence and Finding Traceability

Where an evidence review identifies a potential issue:

1. Record the observation and relevant evidence ID.
2. Determine whether the issue reflects a design weakness, implementation issue, operating failure, or insufficient evidence.
3. Link the issue to the relevant control and risk record.
4. Create a finding only when the available evidence supports a documented conclusion.
5. Link any remediation action to the finding.
6. Retain evidence supporting remediation and closure validation.

Not every evidence gap must immediately become a confirmed control deficiency. The assessor should document the uncertainty and perform appropriate follow-up.

## 7. Synthetic Evidence Rules

Evidence created for this portfolio must be labeled **Synthetic — Portfolio Simulation**.

Do not present invented configuration screenshots, access records, approvals, incident records, or test results as genuine organizational evidence.

Where an artifact models a realistic record, document:

* The fictional system or process it represents.
* The purpose of the artifact.
* The assumptions used to create it.
* Any limitations that affect the assessment.

Synthetic evidence can demonstrate assessment methodology but cannot substantiate the operating effectiveness of a real organization's controls.

## 8. Current Register Status

At the time this register is created, all requests are planned and remain **Not Requested**.

Statuses should be updated as each artifact is created, collected, reviewed, and evaluated. Evidence should not be marked Accepted merely because the file exists.

The existence of a synthetic sample in `evidence-samples.md` does not change the request status. The register should reflect whether a request was issued within the simulation, separately from whether a sample was drafted for portfolio demonstration.

## 9. Simulation Disclaimer

This register is a proposed evidence-management artifact for a fictional SaaS provider. It does not establish that the listed evidence exists in a real organization or that any control has been tested or found effective.

