# SOC 2 Readiness Assessment Results

> **SIMULATION NOTICE:** This document is part of a fictional GRC portfolio case study for Northstar Cloud Solutions. All evidence samples, assessment observations, and results are synthetic. They do not represent a real SOC 2 examination or audit.

## 1. Purpose

This document records the results of control testing for the simulated SOC 2 readiness assessment of Northstar Cloud Solutions.

It links each control to its test procedures, supporting evidence, assessment conclusions, exceptions, and any resulting findings.

**Assessment status:** In progress
**Assessment type:** Simulated SOC 2 readiness assessment
**Assessment period:** Varies by evidence sample; see individual workpapers
**Control framework:** SOC 2 Security Trust Services Criterion, supported by the control objectives documented in `control-matrix.md`

This document supports readiness analysis. It does not provide an independent auditor's opinion or establish SOC 2 compliance or certification.

## 2. Assessment Methodology

For each control:

1. Review the control objective and description in `control-matrix.md`.
2. Identify the corresponding procedure in `control-testing-plan.md`.
3. Confirm the relevant evidence request in `evidence-request-register.md`.
4. Review the available evidence and record what it demonstrates.
5. Compare the evidence with the expected result.
6. Document limitations, exceptions, and additional evidence needed.
7. Determine whether the result is supported, inconclusive, or indicates a potential exception.
8. Create a formal finding only when the available evidence supports a documented conclusion.
9. Link confirmed findings to `findings-register.md`.
10. Track approved corrective actions in `remediation-tracker.md`.

Planned procedures must not be represented as completed tests. Evidence gaps must not automatically be treated as operating failures.

## 3. Assessment Result Definitions

| Result               | Definition                                                                                                                                                    |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Not Tested           | Testing has not been performed.                                                                                                                               |
| In Progress          | Evidence collection or evaluation is underway.                                                                                                                |
| Supported            | The evidence reviewed supports the control objective for the defined scope and procedure. This is not a blanket conclusion about all periods or environments. |
| Exception Identified | Testing identified a condition that does not meet an expected requirement and requires documented evaluation.                                                 |
| Inconclusive         | Available evidence is insufficient to reach a reliable conclusion.                                                                                            |
| Not Applicable       | The control does not apply to the defined scope, with rationale documented and appropriately reviewed.                                                        |

A test result is not automatically a formal finding. Evaluate the condition, cause, risk, scope, and significance before recording a confirmed deficiency.

## 4. Control Testing Results Summary

The table below records the current working status of the 15 controls.

The six evidence samples in `evidence-samples.md` are illustrative synthetic artifacts. Their preliminary observations are not equivalent to completed testing or confirmed control deficiencies.

| Control ID | Control Name                                     | Evidence Reference | Current Result | Outstanding Work                                                                                                      |
| ---------- | ------------------------------------------------ | ------------------ | -------------- | --------------------------------------------------------------------------------------------------------------------- |
| CTRL-001   | Security Governance and Policy Management        | EVD-001, EVD-002   | Not Tested     | Review policies, review records, responsibility assignments, and approvals.                                           |
| CTRL-002   | Risk Assessment and Treatment                    | EVD-003, EVD-004   | Not Tested     | Review risk methodology, scoring criteria, risk register, owners, and treatment decisions.                            |
| CTRL-003   | User Access Provisioning and Removal             | EVD-005, EVD-006   | Not Tested     | Review provisioning, role-change, and termination procedures and inspect representative records.                      |
| CTRL-004   | Privileged Access and Least Privilege            | EVD-007, EVD-008   | In Progress    | Evaluate the privileged account inventory, role permissions, access-review documentation, and follow-up.              |
| CTRL-005   | Multifactor Authentication                       | EVD-009, EVD-010   | In Progress    | Compare MFA requirements with the synthetic configuration summary and investigate exclusions.                         |
| CTRL-006   | Security Logging and Monitoring                  | EVD-011, EVD-012   | In Progress    | Evaluate required logging coverage, configuration, representative events, and monitoring records.                     |
| CTRL-007   | Protection and Retention of Security Logs        | EVD-013, EVD-014   | Not Tested     | Review log permissions, retention requirements, configuration, and exception records.                                 |
| CTRL-008   | Incident Response                                | EVD-015, EVD-016   | In Progress    | Evaluate the incident response plan, exercise documentation, escalation, and corrective-action follow-up.             |
| CTRL-009   | Customer Incident Notification                   | EVD-017, EVD-018   | Not Tested     | Review notification requirements and evaluate the documented workflow or exercise.                                    |
| CTRL-010   | Data Handling, Retention, and Deletion           | EVD-019, EVD-020   | Not Tested     | Review data flows, handling requirements, retention schedules, deletion procedures, and test results.                 |
| CTRL-011   | Vulnerability Management                         | EVD-021, EVD-022   | Not Tested     | Review prioritization criteria, synthetic vulnerability records, remediation, and closure evidence.                   |
| CTRL-012   | Change Management                                | EVD-023, EVD-024   | In Progress    | Evaluate change approval, testing, deployment, rollback planning, and applicable post-implementation review.          |
| CTRL-013   | Secure Development and Deployment Access         | EVD-025, EVD-026   | Not Tested     | Review secure development requirements, release records, security testing, and deployment permissions.                |
| CTRL-014   | Third-Party Risk Management                      | EVD-027, EVD-028   | In Progress    | Review the vendor inventory, risk-tiering method, due diligence, assessment records, and risk decisions.              |
| CTRL-015   | Customer Security Assurance and Control Evidence | EVD-029, EVD-030   | Not Tested     | Evaluate the questionnaire review procedure, response library, completed sample questionnaire, and approval evidence. |

**Status note:** In Progress means that preliminary synthetic evidence has been drafted for the control. It does not mean that all planned procedures have been completed.

## 5. Preliminary Evidence Observations

This section summarizes the observations documented in `evidence-samples.md`.

These are preliminary observations from fictional evidence samples. They must be evaluated against the applicable test procedures before a final conclusion or formal finding is recorded.

### 5.1 CTRL-004 — Privileged Access and Least Privilege

**Evidence reference:** EVD-008 — Access Review Records

**Sample observation:** The synthetic review record identifies 24 accounts, with documented decisions for 22 and two decisions outstanding.

**What the sample supports:**

* A quarterly access-review record is represented in the simulation.
* The sample contains incomplete decision documentation.

**What remains unverified:**

* Whether the two accounts were reviewed through another documented process.
* Whether the reviewed accounts include privileged accounts.
* Whether assigned permissions are consistent with approved roles.
* Whether identified access concerns were resolved.

**Preliminary conclusion:** Inconclusive pending follow-up.

**Finding status:** No confirmed finding recorded.

**Next steps:** Obtain the complete access-review record, privileged account inventory, role-permission matrix, and relevant follow-up evidence.

### 5.2 CTRL-005 — Multifactor Authentication

**Evidence reference:** EVD-010 — Multifactor Authentication Configuration

**Sample observation:** The synthetic summary indicates that the MFA policy covers 30 of 32 workforce accounts. Two accounts are listed as excluded, with no approval records included in the sample.

**What the sample supports:**

* The sample represents an MFA configuration summary.
* Two exclusions require investigation.

**What remains unverified:**

* The identities and account types of the excluded accounts.
* Whether the exclusions are authorized and justified.
* Whether the exclusions affect privileged access.
* Whether other applicable authentication safeguards exist.
* Whether the configuration was consistently enforced during the relevant period.

**Preliminary conclusion:** Potential exception requiring investigation.

**Finding status:** No confirmed finding recorded.

**Next steps:** Review the authentication standard, complete account population, MFA configuration, exception approvals, and relevant sign-in evidence.

### 5.3 CTRL-006 — Security Logging and Monitoring

**Evidence reference:** EVD-012 — Cloud Security Logging Configuration

**Sample observation:** The synthetic configuration summary shows CloudTrail enabled for a fictional production account. Multi-region coverage, retention, log integrity protection, and alerting are not established by the sample.

**What the sample supports:**

* The sample represents a configuration in which CloudTrail is enabled.

**What remains unverified:**

* Whether required accounts, regions, and services are covered.
* Whether logs are protected against unauthorized alteration or deletion.
* Whether retention settings meet defined requirements.
* Whether security events are monitored and investigated.
* Whether the configuration was maintained throughout the relevant period.

**Preliminary conclusion:** Partially supported; additional testing required.

**Finding status:** No confirmed finding recorded.

**Next steps:** Obtain trail configuration, log destination permissions, retention settings, representative events, and monitoring and escalation records.

### 5.4 CTRL-008 — Incident Response

**Evidence reference:** EVD-016 — Incident Response Exercise Record

**Sample observation:** The synthetic exercise record documents a tabletop exercise and three action items. One action item lacks an assigned owner, and closure evidence is not provided.

**What the sample supports:**

* The simulation includes an incident response exercise record.
* Follow-up documentation is incomplete in the sample.

**What remains unverified:**

* Whether the exercise adequately tested the documented response process.
* Whether all action items have been assigned and addressed.
* Whether response and escalation requirements were followed.
* Whether the exercise identified and resolved material process weaknesses.

**Preliminary conclusion:** Partially supported; follow-up required.

**Finding status:** No confirmed finding recorded.

**Next steps:** Review the exercise plan, final notes, action-item register, ownership assignments, and completion evidence.

### 5.5 CTRL-012 — Change Management

**Evidence reference:** EVD-024 — Change Management Record

**Sample observation:** The synthetic record identifies a production change and deployment date, but the sample does not include the approval timestamp, test results, or rollback plan.

**What the sample supports:**

* The simulation includes a documented change record and deployment reference.

**What remains unverified:**

* Whether approval occurred before implementation.
* Whether testing met defined requirements.
* Whether an appropriate rollback plan was available.
* Whether the deployment matched the approved change.
* Whether a post-implementation review was required and performed.

**Preliminary conclusion:** Inconclusive pending evidence.

**Finding status:** No confirmed finding recorded.

**Next steps:** Obtain the approval record, test results, rollback plan, deployment evidence, and any required post-implementation review.

### 5.6 CTRL-014 — Third-Party Risk Management

**Evidence reference:** EVD-028 — Third-Party Risk Assessment Record

**Sample observation:** The synthetic record identifies a high inherent risk rating for SignalBridge Support. The sample does not include documented risk approval, completed review of retention terms, or subprocessor review records.

**What the sample supports:**

* A vendor assessment is represented in the simulation.
* The sample identifies a high inherent risk rating.
* Several assessment records are not included.

**What remains unverified:**

* Whether due diligence was completed.
* Whether applicable contractual safeguards were reviewed.
* Whether subprocessors are used and appropriately assessed.
* Whether the vendor was approved or subject to documented risk acceptance.
* Whether outstanding risks have owners and target dates.

**Preliminary conclusion:** Inconclusive pending additional documentation.

**Finding status:** No confirmed finding recorded.

**Next steps:** Review the vendor inventory, completed questionnaire, supporting assurance evidence, contract terms, subprocessor information, and risk decision records.

## 6. Detailed Control Test Workpaper Template

Use this template for each control test. Complete it based on procedures actually performed and evidence actually reviewed within the simulation.

### Control identification

* **Control ID:**
* **Control name:**
* **Control owner:**
* **Test reference:**
* **Test date:**
* **Assessment period:**
* **Evidence IDs reviewed:**

### Test objective

State what the test is intended to establish and how it relates to the control objective.

### Procedures performed

Document the steps actually performed. Do not describe a planned procedure as completed.

1.
2.
3.

### Evidence reviewed

For each item, record:

* Evidence ID and description.
* Source or origin within the simulation.
* Date created or relevant period.
* Population and sample size, if applicable.
* Completeness and limitations.
* What the evidence demonstrates.

### Expected result

Describe the expected condition based on the control definition, applicable policy, and assessment criteria.

### Actual result

Describe the condition supported by the evidence reviewed. Separate observed facts from assumptions and interpretation.

### Exceptions and limitations

Document any differences between the expected and actual results, evidence gaps, scope limitations, or unresolved questions.

### Conclusion

* **Result:** Not Tested / In Progress / Supported / Exception Identified / Inconclusive / Not Applicable
* **Rationale:**
* **Finding required:** Yes / No / Pending evaluation
* **Finding ID, if applicable:**
* **Additional evidence required:**
* **Follow-up owner:**
* **Follow-up target date:**

### Review

* **Prepared by:**
* **Reviewed by:**
* **Review date:**
* **Review comments:**

## 7. Exception Evaluation

Before creating a formal finding, determine:

1. What requirement was not met or could not be demonstrated?
2. Is the issue a design weakness, implementation issue, operating failure, or evidence gap?
3. Is the evidence complete and relevant to the defined scope?
4. Could additional evidence resolve the apparent exception?
5. What is the potential risk and business impact?
6. Are compensating controls present and supported by evidence?
7. What severity is justified by the available information?
8. What corrective action would address the issue?
9. Who should review or approve the conclusion?

If the evidence is insufficient, record an inconclusive result and request follow-up rather than forcing a pass or fail.

A formal finding should include the control reference, test procedure, supporting evidence, condition, expected requirement, risk implication, and documented rationale.

## 8. Findings and Remediation Linkage

When a potential exception is confirmed:

1. Assign a unique finding identifier, such as `FND-001`.
2. Record the finding in `findings-register.md`.
3. Link it to the relevant control and evidence.
4. Document the severity and rationale.
5. Assign an accountable owner.
6. Create a linked remediation action using an identifier such as `ACT-001`.
7. Track corrective action and completion evidence in `remediation-tracker.md`.
8. Validate remediation before marking the finding closed.

**Current state:** No confirmed findings have been entered based solely on the preliminary samples in this document.

## 9. Reporting Summary

Complete this summary after the planned tests have been performed and reviewed.

| Metric                                            | Result                 |
| ------------------------------------------------- | ---------------------- |
| Total controls in scope                           | 15                     |
| Controls with preliminary evidence samples        | 6                      |
| Controls tested according to completed procedures | Pending                |
| Controls supported by evidence                    | Pending                |
| Controls with exceptions confirmed                | Pending                |
| Inconclusive controls                             | Pending                |
| Controls not tested                               | Pending                |
| Confirmed findings                                | 0 currently documented |
| Open remediation actions                          | 0 currently documented |
| Material evidence limitations                     | Pending evaluation     |

The current zero counts for findings and remediation actions mean that none have been formally documented at this stage. They do not mean that the environment has no deficiencies.

Do not treat untested controls as passing. Report them separately from controls that have been tested.

## 10. Assessment Limitations

This assessment is a simulated portfolio exercise. All evidence and results must be clearly identified as synthetic.

The assessment is limited to the scope, procedures, evidence samples, and assumptions documented in this repository. Incomplete evidence may prevent a reliable conclusion.

A readiness assessment identifies gaps and opportunities to improve control design, documentation, and operation. It does not provide an independent auditor's opinion or establish SOC 2 compliance or certification.

