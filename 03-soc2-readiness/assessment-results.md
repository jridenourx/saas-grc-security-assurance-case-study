# SOC 2 Readiness Assessment Results

## 1. Purpose

This document records the results of control testing for the simulated SOC 2 readiness assessment of Northstar Cloud Solutions.

It links each control to its test procedure, supporting evidence, assessment conclusion, exceptions, and any resulting findings.

**Assessment status:** In progress
**Assessment type:** Simulated readiness assessment
**Assessor:** Portfolio case study
**Assessment period:** To be defined for each test based on the evidence available

This document is not an independent SOC 2 examination or audit opinion.

## 2. Assessment Methodology

For each control:

1. Review the control objective and description in `control-matrix.md`.
2. Identify the applicable test in `control-testing-plan.md`.
3. Confirm the evidence requested in `evidence-request-register.md`.
4. Inspect the evidence and record what it demonstrates.
5. Compare the evidence with the expected result.
6. Document limitations, exceptions, and additional evidence needed.
7. Determine whether a finding is warranted.
8. Link any confirmed finding to `findings-register.md`.
9. Link corrective actions to `remediation-tracker.md`.
10. Record the assessor's rationale and conclusion.

Do not infer that a control operated effectively merely because a policy exists or a configuration is shown as enabled.

## 3. Assessment Result Definitions

| Result               | Definition                                                                                                                                                         |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Not Tested           | Testing has not begun.                                                                                                                                             |
| In Progress          | Evidence is being collected or evaluated.                                                                                                                          |
| Supported            | The evidence reviewed supports the control objective for the defined scope and test performed. This is not a blanket conclusion about all periods or environments. |
| Exception Identified | The test identified a condition that does not meet an expected requirement and requires evaluation.                                                                |
| Inconclusive         | Available evidence is insufficient to reach a reliable conclusion.                                                                                                 |
| Not Applicable       | The control is not applicable to the defined scope, with rationale documented and approved as appropriate.                                                         |

A test result is not automatically a formal finding. Evaluate each exception, its cause, risk, scope, and significance before entering it into the findings register.

## 4. Control Testing Results

At project initialization, all controls remain **Not Tested** unless a test has actually been completed and documented. The sample evidence in `evidence-samples.md` provides illustrative starting material for selected controls, not proof that testing is complete.

| Control ID | Control Name                                     | Test Reference                | Evidence Reviewed                           | Result      | Exception / Limitation                                                                                   | Finding ID         | Assessor Rationale                                                                                                      |
| ---------- | ------------------------------------------------ | ----------------------------- | ------------------------------------------- | ----------- | -------------------------------------------------------------------------------------------------------- | ------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| CTRL-001   | Security Governance and Policy Management        | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-002   | Risk Assessment and Treatment                    | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-003   | User Access Provisioning and Removal             | Refer to control testing plan | EVD-003, subject to ID mapping verification | In Progress | Two user accounts in the sample lack documented review decisions.                                        | Pending evaluation | Determine whether the record is complete and obtain follow-up evidence.                                                 |
| CTRL-004   | Privileged Access and Least Privilege            | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-005   | Multifactor Authentication                       | Refer to control testing plan | EVD-006, subject to ID mapping verification | In Progress | Two accounts are listed as excluded from the MFA policy; justification and account types are unknown.    | Pending evaluation | Investigate exclusions, privileged access, and applicable safeguards before determining whether a finding is warranted. |
| CTRL-006   | Security Logging and Monitoring                  | Refer to control testing plan | EVD-010, subject to ID mapping verification | In Progress | Coverage, retention, protection, and alerting have not been established by the sample.                   | Pending evaluation | The sample supports a limited configuration observation only.                                                           |
| CTRL-007   | Protection and Retention of Security Logs        | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-008   | Incident Response                                | Refer to control testing plan | EVD-020, subject to ID mapping verification | In Progress | Exercise follow-up and action-item closure evidence are incomplete.                                      | Pending evaluation | Determine whether the exercise and follow-up meet defined requirements.                                                 |
| CTRL-009   | Customer Incident Notification                   | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-010   | Data Handling, Retention, and Deletion           | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-011   | Vulnerability Management                         | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-012   | Change Management                                | Refer to control testing plan | EVD-024, subject to ID mapping verification | In Progress | Approval, test results, rollback plan, and post-implementation review are not established by the sample. | Pending evaluation | Obtain the referenced evidence before concluding whether the change met requirements.                                   |
| CTRL-013   | Secure Development and Deployment Access         | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |
| CTRL-014   | Third-Party Risk Management                      | Refer to control testing plan | EVD-016, subject to ID mapping verification | In Progress | Vendor risk approval, retention terms, and subprocessor review are not documented in the sample.         | Pending evaluation | Obtain supporting records and compare them with the defined vendor risk management process.                             |
| CTRL-015   | Customer Security Assurance and Control Evidence | Refer to control testing plan | Pending                                     | Not Tested  | —                                                                                                        | —                  | Testing not yet performed.                                                                                              |

## 5. Detailed Test Workpaper Template

Use this template for each completed control test. Keep a separate copy for each control or maintain clearly separated sections within this document.

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
* Relevant date or period.
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

## 6. Exception Evaluation

Before creating a formal finding, determine:

1. What requirement was not met or could not be demonstrated?
2. Is the issue a design weakness, operating failure, evidence gap, or other limitation?
3. Is the evidence complete and relevant to the defined scope?
4. Could another record resolve the apparent exception?
5. What is the potential risk and business impact?
6. Are compensating controls present and supported by evidence?
7. What severity is justified by the available information?
8. What corrective action would address the issue?
9. Who should review or approve the conclusion?

If the evidence is insufficient, record an inconclusive result and request follow-up rather than forcing a pass or fail.

## 7. Reporting Summary

Complete this section after the planned tests have been performed and reviewed.

| Metric                              | Result  |
| ----------------------------------- | ------- |
| Total controls in scope             | 15      |
| Controls tested                     | Pending |
| Controls supported by evidence      | Pending |
| Controls with exceptions identified | Pending |
| Inconclusive controls               | Pending |
| Controls not tested                 | Pending |
| Confirmed findings                  | Pending |
| Open remediation actions            | Pending |
| Material evidence limitations       | Pending |

Do not treat untested controls as passing. Report them separately from tested controls.

## 8. Readiness Assessment Limitations

This assessment is a simulated portfolio exercise. All evidence and results must be clearly identified as synthetic.

A readiness assessment identifies gaps and opportunities to improve control design, documentation, and operation. It does not provide an independent auditor's opinion or establish SOC 2 compliance or certification.
