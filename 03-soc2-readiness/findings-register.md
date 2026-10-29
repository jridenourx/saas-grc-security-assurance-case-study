# SOC 2 Readiness Findings Register

## 1. Purpose

This register documents exceptions identified during the simulated SOC 2 readiness assessment of Northstar Cloud Solutions.

It provides a consistent record of control gaps, supporting evidence, risk implications, severity, ownership, and remediation status. Each finding must be traceable to the relevant control, test procedure, evidence, and risk where applicable.

**Assessment status:** Pending testing
**Current finding status:** No findings documented yet

No finding should be recorded as confirmed until the available evidence has been reviewed and the exception has been evaluated. Illustrative examples, if added later, must be explicitly labeled as illustrative rather than actual assessment results.

## 2. Finding Identification and Classification

Assign each confirmed finding a unique identifier using the format `FND-001`, `FND-002`, and so on. Never reuse an identifier.

### Finding severity

| Severity    | Definition                                                                                                                                           | General response expectation                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Critical    | A significant control failure creates an immediate or potentially severe risk to sensitive data, critical systems, or essential security operations. | Escalate immediately; establish containment and an urgent corrective-action plan. |
| High        | A material control weakness creates substantial risk or affects an important security requirement.                                                   | Prioritize remediation and obtain management visibility.                          |
| Moderate    | A control weakness increases risk but has a more limited scope or impact.                                                                            | Assign an owner, document corrective action, and track to completion.             |
| Low         | A limited weakness or documentation deficiency with comparatively low risk.                                                                          | Correct through routine improvement activities.                                   |
| Observation | An improvement opportunity or process concern that does not currently meet the threshold for a control finding.                                      | Document and evaluate for improvement.                                            |

Severity must reflect the evidence, potential impact, likelihood, scope, and effectiveness of existing safeguards. These categories are proposed internal conventions for this case study, not universal SOC 2 severity requirements.

## 3. Evidence and Evaluation Requirements

Before confirming a finding, document:

* The control ID and control objective.
* The test procedure and test period.
* The evidence reviewed, including evidence IDs.
* The condition observed.
* The expected control requirement or acceptance criterion.
* The gap between the expected and observed conditions.
* The risk and potential business impact.
* The cause, if it can be supported by evidence.
* Any compensating controls considered.
* The proposed severity and rationale.
* The responsible owner and required corrective action.

Distinguish among these exception types:

* **Design weakness:** The control is absent or is not adequately designed to address the risk.
* **Operating failure:** The control is designed appropriately but did not operate as intended.
* **Evidence gap:** Available documentation is insufficient to demonstrate that the control is appropriately designed or operating. An evidence gap alone does not prove the control failed.
* **Scope or applicability issue:** The control or test population requires clarification before a conclusion can be reached.
* **Observation:** An improvement opportunity that does not currently meet the threshold for a formal finding.

If evidence is unavailable, contradictory, incomplete, or outside the assessment period, document the limitation rather than assuming the control passed or failed.

## 4. Findings Register

No findings have been entered at project initialization. Populate this table after control testing and exception evaluation.

| Finding ID | Finding Title | Control ID | Test ID | Exception Type | Severity | Condition and Supporting Evidence | Risk / Impact | Root Cause | Compensating Controls | Owner | Target Date | Status | Remediation Action ID |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| No findings documented yet | — | — | — | — | — | Pending assessment | — | — | — | — | — | Pending testing | — |

Replace the initialization row when actual assessment results are documented. Do not treat it as a finding.

## 5. Finding Status Definitions

| Status                  | Definition                                                                                                       |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Pending testing         | Testing has not yet produced an evaluated exception.                                                             |
| Draft                   | A potential finding is being documented and evaluated.                                                           |
| Open                    | The finding has been confirmed and requires action.                                                              |
| Remediation in progress | Corrective action is underway.                                                                                   |
| Pending validation      | The owner reports completion and independent or designated validation is required.                               |
| Closed                  | The corrective action has been validated against defined acceptance criteria.                                    |
| Risk accepted           | An authorized decision-maker has formally accepted the residual risk, with rationale and review date documented. |

A finding must not be marked **Closed** solely because an owner reports that work is complete. Validation evidence and the result must be recorded.

Risk acceptance does not mean the control weakness has been corrected. Keep accepted-risk items distinguishable from remediated findings.

## 6. Remediation and Validation

For every confirmed finding:

1. Assign an accountable owner.
2. Create a linked remediation action in `remediation-tracker.md`.
3. Define a specific corrective action and measurable acceptance criteria.
4. Set a target date based on severity and business risk.
5. Record any interim safeguards or compensating controls.
6. Track status and overdue actions.
7. Collect completion evidence.
8. Validate that the action addresses the underlying issue.
9. Update the finding status and record the validation result.
10. Escalate overdue, disputed, or risk-accepted items according to the organization's governance process.

The person validating remediation should be sufficiently independent of the person performing the work to provide a credible review.

## 7. Reporting and Escalation

Readiness reporting should summarize:

* Total confirmed findings by severity.
* Findings by control and exception type.
* Open, overdue, and risk-accepted findings.
* Remediation progress and upcoming target dates.
* Evidence limitations affecting conclusions.
* Significant risks requiring management attention.

Critical or high-risk issues should be escalated promptly to the designated security or management owner. The escalation and decision should be documented.

## 8. Relationship to Other Project Artifacts

| Artifact                                         | Relationship                                                              |
| ------------------------------------------------ | ------------------------------------------------------------------------- |
| `control-matrix.md`                              | Identifies the control and objective associated with the finding.         |
| `evidence-request-register.md`                   | Tracks evidence requested or received for the assessment.                 |
| `control-testing-plan.md`                        | Defines the planned test procedures and expected results.                 |
| `remediation-tracker.md`                         | Tracks corrective actions associated with confirmed findings.             |
| Risk register in the third-party risk workstream | Supports linkage to broader business and security risks where applicable. |

## 9. Simulation Limitations

This register is part of a fictional portfolio case study. All assessment results and evidence must be synthetic or otherwise clearly authorized for portfolio use.

The work demonstrates a readiness-assessment process. It is not an independent SOC 2 examination, audit opinion, certification, or representation that Northstar Cloud Solutions is SOC 2 compliant.
