# SOC 2 Readiness Remediation Tracker

## 1. Purpose

This tracker records corrective actions arising from confirmed findings in the simulated SOC 2 readiness assessment of Northstar Cloud Solutions.

It establishes accountability, target dates, acceptance criteria, progress reporting, and validation requirements. Each corrective action must link to a finding or clearly documented improvement initiative.

**Initial status:** No remediation actions documented yet

Do not create remediation actions as though confirmed findings already exist. Populate this tracker when an exception is confirmed or an improvement initiative is formally approved.

## 2. Remediation Principles

Every remediation action should:

* Address the documented condition and underlying cause where known.
* Have a named accountable owner or clearly defined role.
* Include a target completion date and priority.
* Define measurable acceptance criteria.
* Identify required implementation and validation evidence.
* Record dependencies, interim safeguards, and blockers.
* Be traceable to the finding it addresses.
* Remain open until the required validation is complete, unless risk acceptance is formally approved.

A task being completed does not automatically demonstrate that the associated control is effective.

## 3. Priority Guidance

| Priority | General criteria                                                                                                      | Management response                                  |
| -------- | --------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Critical | Immediate or potentially severe exposure affecting sensitive data, critical systems, or essential security functions. | Immediate escalation and urgent response planning.   |
| High     | Material weakness with substantial potential business or security impact.                                             | Prioritized action and regular management oversight. |
| Moderate | Meaningful control gap with a more limited scope or impact.                                                           | Assign a target date and monitor progress.           |
| Low      | Limited deficiency or process improvement.                                                                            | Schedule within routine improvement work.            |

Priority should reflect the associated finding's severity, residual risk, exposure, dependencies, and feasibility of interim safeguards. These are proposed project conventions, not universal SOC 2 requirements.

## 4. Remediation Tracker

No actions have been entered at project initialization. Add one row for each approved corrective action.

| Action ID                 | Finding ID | Control ID | Corrective Action  | Root Cause Addressed | Priority | Owner | Date Opened | Target Date | Status      | Acceptance Criteria | Required Completion Evidence | Validation Owner | Validation Result | Date Closed | Blocker / Dependency |
| ------------------------- | ---------- | ---------- | ------------------ | -------------------- | -------- | ----- | ----------- | ----------- | ----------- | ------------------- | ---------------------------- | ---------------- | ----------------- | ----------- | -------------------- |
| No actions documented yet | —          | —          | Pending assessment | —                    | —        | —     | —           | —           | Not Started | —                   | —                            | —                | Not Tested        | —           | —                    |

Replace the initialization row when approved remediation actions are created. Do not treat it as an actual action.

Use unique action identifiers such as `ACT-001`, `ACT-002`, and so on. Never reuse an identifier.

## 5. Action Status Definitions

| Status                           | Definition                                                                                           |
| -------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Not Started                      | The action is approved but work has not begun.                                                       |
| In Progress                      | The owner is actively implementing the action.                                                       |
| Blocked                          | Progress depends on an unresolved issue or decision.                                                 |
| Implemented — Pending Validation | The owner reports implementation is complete, but validation remains outstanding.                    |
| Closed — Validated               | Acceptance criteria have been met and validation evidence has been reviewed.                         |
| Risk Accepted                    | An authorized decision-maker has approved documented residual risk instead of requiring remediation. |

If an action is blocked, document the blocker, the person or role responsible for resolving it, and the next review date.

Risk acceptance must include an approver, rationale, residual-risk statement, expiration or review date, and any required monitoring. It is not equivalent to successful remediation.

## 6. Acceptance Criteria and Validation

Acceptance criteria must be specific enough for a reviewer to determine whether the corrective action worked.

Avoid vague criteria such as:

* Improve access controls.
* Update the policy.
* Fix logging.
* Complete security training.

Prefer criteria that identify the expected result and the evidence required to demonstrate it. For example, for a hypothetical access-review issue, criteria might require an approved access review for the defined population, documented resolution of identified inappropriate access, and evidence that the updated process has been followed.

This example illustrates how to write criteria; it is not a claim that Northstar has an access-review finding.

For each action, record:

1. The requirement being addressed.
2. The expected outcome.
3. The population, system, or process in scope.
4. The completion evidence required.
5. The validation procedure.
6. The validation result and date.
7. Any remaining exceptions or residual risk.

Validation should determine whether the corrective action addresses the finding, not merely whether a task was performed. Where appropriate, inspect configuration or documentation and sample operating evidence.

## 7. Overdue Actions and Escalation

Review open actions regularly. At a minimum, the review should identify:

* Actions past their target dates.
* Critical or high-priority actions without timely progress.
* Actions blocked by unresolved dependencies.
* Actions implemented but awaiting validation.
* Actions with incomplete or disputed evidence.
* Risk-accepted actions approaching their review dates.

For overdue actions, document the reason, revised target date, interim safeguards, and escalation decision. Do not silently extend deadlines or close actions to improve reported metrics.

## 8. Management Reporting

Use the tracker to summarize:

* Total open actions by priority.
* Actions overdue and their age.
* Actions blocked or awaiting validation.
* Actions closed with validated evidence.
* Risk-accepted actions and upcoming review dates.
* Significant dependencies or recurring root causes.

Report implementation progress separately from validated closure. This prevents the completion of administrative tasks from being mistaken for demonstrated control improvement.

## 9. Relationship to Other Project Artifacts

| Artifact                       | Relationship                                                                |
| ------------------------------ | --------------------------------------------------------------------------- |
| `findings-register.md`         | Provides the finding and links to the corrective action.                    |
| `control-matrix.md`            | Identifies the control being remediated.                                    |
| `evidence-request-register.md` | Helps track evidence used to demonstrate implementation or operation.       |
| `control-testing-plan.md`      | Provides the original test objective and can inform remediation validation. |

## 10. Simulation Limitations

This tracker belongs to a fictional portfolio case study. Use synthetic evidence and clearly label illustrative examples.

The tracker demonstrates a remediation-management process. It does not establish that a real organization has remediated deficiencies or achieved SOC 2 compliance.
