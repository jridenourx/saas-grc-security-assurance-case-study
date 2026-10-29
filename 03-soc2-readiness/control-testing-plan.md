# SOC 2 Readiness Control Testing Plan

> **SIMULATION NOTICE:** This plan defines proposed readiness testing procedures for Northstar Cloud Solutions, a fictional SaaS provider. The procedures are planned activities, not completed audit tests. Any later results must be supported by clearly labeled synthetic evidence.

## 1. Purpose

This plan defines how selected controls in the SOC 2 readiness control matrix will be evaluated.

It establishes the assessment objective, planned procedures, evidence requirements, and criteria for documenting results.

The goal is to produce repeatable, evidence-based conclusions while distinguishing control design, implementation, operating effectiveness, and evidence limitations.

## 2. Assessment Approach

Each control will be evaluated against its documented objective and relevant assessment criteria.

The assessment may include:

* **Inquiry:** Asking the designated owner to explain the process.
* **Inspection:** Reviewing policies, records, approvals, or configuration summaries.
* **Observation:** Observing a process or configuration where appropriate and available.
* **Reperformance:** Independently repeating a calculation or procedure using the available evidence.

Inquiry alone is generally insufficient to establish that a control operated effectively. Where practical, explanations should be corroborated with relevant records or other evidence.

## 3. Test Status Definitions

| Status                              | Definition                                                                                     |
| ----------------------------------- | ---------------------------------------------------------------------------------------------- |
| Not Started                         | Testing has not begun.                                                                         |
| In Progress                         | Procedures are underway.                                                                       |
| Completed — No Exception Identified | The planned procedures were completed and no exception was identified within the tested scope. |
| Exception Identified                | The test identified a discrepancy requiring evaluation.                                        |
| Evidence Gap                        | Evidence was insufficient to complete the procedure or support a conclusion.                   |
| Not Applicable                      | The procedure does not apply, with a documented rationale.                                     |

"Completed — No Exception Identified" does not automatically establish that a control was effective throughout a broader period or across an entire system. The conclusion must reflect the scope, evidence, and procedures actually completed.

## 4. Sampling Approach

For this simulation, samples will be selected to demonstrate assessment methodology rather than provide statistical assurance.

Where synthetic records are used, the workpaper should identify:

* The defined population.
* The selection method.
* The sample size.
* The selected records.
* The period represented.
* The procedures performed.
* The limitations of the sample.

Do not generalize a result beyond the population and period supported by the evidence.

## 5. Control Testing Procedures

### CTRL-001 — Security Governance and Policy Management

**Objective:** Determine whether security policies and responsibilities are documented, approved, and subject to appropriate review.

**Planned procedures:**

1. Obtain the relevant policy inventory and approved policy documents.
2. Inspect approval and review records.
3. Compare policy coverage with the defined service scope.
4. Inspect the security responsibilities matrix.
5. Record missing approvals, outdated documents, or unclear ownership.

**Evidence references:** EVD-001, EVD-002

**Expected result:** Relevant policies have appropriate approval and review evidence, and responsibilities are assigned.

**Potential exceptions:** Missing approval records, unclear ownership, or policies that do not cover relevant activities.

**Current test status:** Not Started

### CTRL-002 — Risk Assessment and Treatment

**Objective:** Determine whether security risks are evaluated consistently and assigned appropriate follow-up.

**Planned procedures:**

1. Inspect the risk assessment methodology and scoring criteria.
2. Select a sample of risk records from the defined population.
3. Verify that each selected risk has a documented rationale and rating.
4. Check whether an owner and treatment or acceptance decision are recorded.
5. Inspect review history and follow-up evidence.

**Evidence references:** EVD-003, EVD-004

**Expected result:** Selected risks are supported by documented assessment rationale, ownership, and treatment decisions.

**Potential exceptions:** Unsupported ratings, missing owners, undocumented risk decisions, or overdue actions without explanation.

**Current test status:** Not Started

### CTRL-003 — User Access Provisioning and Removal

**Objective:** Determine whether access is authorized and appropriately changed or removed during the user lifecycle.

**Planned procedures:**

1. Obtain the documented access lifecycle procedure.
2. Define the population of synthetic access and termination records.
3. Select a sample of provisioning, role-change, and termination records.
4. Compare requests with approvals and assigned access.
5. Inspect evidence that access was modified or removed when required.
6. Record missing approvals, mismatches, or unexplained delays.

**Evidence references:** EVD-005, EVD-006

**Expected result:** Selected access changes are supported by appropriate authorization and completion evidence.

**Potential exceptions:** Unapproved access, permissions inconsistent with the approved request, or missing evidence of required access removal.

**Current test status:** Not Started

### CTRL-004 — Privileged Access and Least Privilege

**Objective:** Determine whether privileged permissions are appropriately restricted and reviewed.

**Planned procedures:**

1. Obtain the privileged account inventory and role-permission matrix.
2. Identify the defined population of privileged accounts.
3. Select accounts for review using a documented selection method.
4. Compare assigned permissions with approved business requirements.
5. Inspect access-review records and documented exceptions.
6. Determine whether excessive or unexplained permissions require further investigation.

**Evidence references:** EVD-007, EVD-008

**Expected result:** Selected privileged permissions are supported by documented requirements and appropriate review evidence.

**Potential exceptions:** Unapproved administrative access, excessive permissions, or missing review and exception records.

**Current test status:** Not Started

### CTRL-005 — Multifactor Authentication

**Objective:** Determine whether MFA requirements are defined and appropriately enforced for the relevant access scope.

**Planned procedures:**

1. Obtain the authentication standard and define applicable accounts and access paths.
2. Identify relevant identity systems and authentication configurations.
3. Inspect synthetic configuration evidence for MFA enforcement.
4. Compare the configuration with the stated requirements.
5. Review exceptions and assess whether they are authorized and appropriately treated.
6. Document systems or account categories not covered by the available evidence.

**Evidence references:** EVD-009, EVD-010

**Expected result:** The evidence supports MFA enforcement for the defined scope or identifies the specific gaps.

**Potential exceptions:** Required accounts without MFA, unapproved exceptions, or incomplete configuration coverage.

**Current test status:** Not Started

### CTRL-006 — Security Logging and Monitoring

**Objective:** Determine whether relevant systems generate required security events and whether monitoring activities are documented.

**Planned procedures:**

1. Obtain the system inventory and logging requirements.
2. Identify the systems and events expected to be logged.
3. Compare the defined requirements with the available coverage inventory.
4. Inspect synthetic configuration summaries and sample log events.
5. Review available monitoring and alert records.
6. Document missing coverage, configuration gaps, or unsupported monitoring claims.

**Evidence references:** EVD-011, EVD-012

**Expected result:** Relevant logging requirements are mapped to the defined systems and supported by appropriate evidence.

**Potential exceptions:** Systems omitted from the coverage inventory, required events not captured, or missing evidence of required monitoring.

**Current test status:** Not Started

### CTRL-007 — Protection and Retention of Security Logs

**Objective:** Determine whether access to security logs is restricted and retention settings align with documented requirements.

**Planned procedures:**

1. Obtain log access permissions and retention requirements.
2. Inspect the roles permitted to access or administer security logs.
3. Compare synthetic retention settings with the documented requirements.
4. Review documented exceptions and approvals.
5. Record any mismatch or limitation in the available evidence.

**Evidence references:** EVD-013, EVD-014

**Expected result:** The evidence supports appropriate log access restrictions and retention settings for the defined scope.

**Potential exceptions:** Excessive access, retention settings inconsistent with requirements, or undocumented exceptions.

**Current test status:** Not Started

### CTRL-008 — Incident Response

**Objective:** Determine whether incident response responsibilities and procedures are documented and whether available exercise evidence supports the process.

**Planned procedures:**

1. Obtain the incident response plan and escalation procedures.
2. Verify that responsibilities are assigned.
3. Inspect available synthetic exercise records.
4. Compare documented exercise objectives with recorded results.
5. Check whether lessons learned and corrective actions are tracked.
6. Distinguish documented design from demonstrated operation.

**Evidence references:** EVD-015, EVD-016

**Expected result:** The response process is documented and available exercise evidence supports the conclusions within the tested scope.

**Potential exceptions:** Missing responsibilities, incomplete escalation procedures, or exercise findings without documented follow-up.

**Current test status:** Not Started

### CTRL-009 — Customer Incident Notification

**Objective:** Determine whether applicable notification obligations are identified and reflected in the documented process.

**Planned procedures:**

1. Obtain the applicable contractual notification requirements.
2. Inspect the notification procedure and assigned responsibilities.
3. Compare the documented process with the applicable requirements.
4. Review an appropriate synthetic workflow or exercise record, if available.
5. Record any conflict, missing responsibility, or untested assumption.

**Evidence references:** EVD-017, EVD-018

**Expected result:** Relevant obligations are identified and the documented process addresses them.

**Potential exceptions:** Missing requirements, conflicting procedures, or unclear responsibility for notification.

**Current test status:** Not Started

### CTRL-010 — Data Handling, Retention, and Deletion

**Objective:** Determine whether relevant data flows and retention requirements are documented and supported by available evidence.

**Planned procedures:**

1. Obtain the data inventory and relevant data-flow documentation.
2. Compare the documented data scope with the service boundary.
3. Inspect the retention schedule and deletion procedure.
4. Review synthetic configuration or test evidence for selected data stores.
5. Identify excluded systems, copies, or processes that limit the conclusion.
6. Document gaps between defined requirements and available evidence.

**Evidence references:** EVD-019, EVD-020

**Expected result:** Data-handling and retention requirements are documented and supported by evidence appropriate to the assessed scope.

**Potential exceptions:** Unidentified data flows, missing retention requirements, or insufficient evidence of deletion behavior.

**Current test status:** Not Started

### CTRL-011 — Vulnerability Management

**Objective:** Determine whether vulnerabilities are assessed, prioritized, tracked, and supported by remediation evidence.

**Planned procedures:**

1. Obtain the vulnerability management procedure and prioritization criteria.
2. Define the population of synthetic vulnerability records.
3. Select a sample and inspect severity, owner, and remediation status.
4. Compare treatment decisions with the documented criteria.
5. Inspect closure and validation evidence for records marked resolved.
6. Record overdue or unsupported closures.

**Evidence references:** EVD-021, EVD-022

**Expected result:** Selected vulnerability records are supported by documented assessment, treatment, and appropriate closure evidence.

**Potential exceptions:** Unassigned vulnerabilities, unsupported prioritization, or records marked closed without sufficient validation evidence.

**Current test status:** Not Started

### CTRL-012 — Change Management

**Objective:** Determine whether selected changes are appropriately authorized, tested, and documented.

**Planned procedures:**

1. Obtain the change management procedure.
2. Define the population of synthetic change records.
3. Select a sample of changes.
4. Inspect approval, testing, and implementation records.
5. Review emergency changes and any documented exceptions.
6. Compare selected records with the documented requirements.

**Evidence references:** EVD-023, EVD-024

**Expected result:** Selected changes have evidence of required authorization, testing, and implementation.

**Potential exceptions:** Missing approvals, insufficient testing evidence, or undocumented emergency changes.

**Current test status:** Not Started

### CTRL-013 — Secure Development and Deployment Access

**Objective:** Determine whether relevant secure development requirements are documented and production deployment access is appropriately restricted.

**Planned procedures:**

1. Obtain secure development requirements and the relevant testing procedure.
2. Inspect selected synthetic release records.
3. Review evidence of required security testing and approval.
4. Inspect the deployment permission summary.
5. Compare assigned permissions with documented responsibilities.
6. Record any unsupported or unexplained access.

**Evidence references:** EVD-025, EVD-026

**Expected result:** Selected release and deployment records support the defined security requirements and authorization process.

**Potential exceptions:** Missing security testing evidence, unapproved deployment access, or incomplete release approvals.

**Current test status:** Not Started

### CTRL-014 — Third-Party Risk Management

**Objective:** Determine whether the vendor risk management process is documented and applied consistently to the selected fictional vendors.

**Planned procedures:**

1. Inspect the vendor inventory and risk-tiering methodology.
2. Verify that the scoring criteria and tier rationale are documented.
3. Review the three synthetic vendor assessments.
4. Trace assessment conclusions to the supporting evidence.
5. Inspect documented findings, treatment decisions, and reassessment requirements.
6. Identify unsupported assumptions and missing evidence.

**Evidence references:** EVD-027, EVD-028

**Expected result:** Selected vendor assessments have documented rationale, traceable evidence, and appropriate follow-up.

**Potential exceptions:** Unsupported risk ratings, missing assessment evidence, or risks without documented ownership or treatment.

**Current test status:** Not Started

### CTRL-015 — Customer Security Assurance and Control Evidence

**Objective:** Determine whether customer security responses are reviewed, supported by evidence, and approved before release.

**Planned procedures:**

1. Inspect the questionnaire review procedure and response library.
2. Review the selected synthetic customer questionnaire.
3. Trace selected customer-facing claims to supporting evidence.
4. Verify that required technical or legal review is documented where applicable.
5. Inspect the approval and submission record.
6. Identify unsupported claims, missing approvals, or outdated response references.

**Evidence references:** EVD-029, EVD-030

**Expected result:** The selected response record demonstrates the required review and approval workflow, with claims supported by appropriate evidence.

**Potential exceptions:** Unsupported claims, incomplete reviews, missing approval, or use of outdated evidence.

**Current test status:** Not Started

## 6. Workpaper Documentation Requirements

For each completed control test, record:

| Field                | Required Information                                   |
| -------------------- | ------------------------------------------------------ |
| Workpaper ID         | Unique identifier for the test workpaper               |
| Control ID           | Relevant control from the control matrix               |
| Test Objective       | What the procedure is intended to evaluate             |
| Assessment Criteria  | Applicable requirement or documented control objective |
| Evidence IDs         | Evidence artifacts reviewed                            |
| Population           | Records or systems included in the assessment          |
| Sample Selection     | Method and rationale                                   |
| Procedures Performed | Steps actually completed                               |
| Results              | Factual observations and test outcomes                 |
| Exceptions           | Identified discrepancies or evidence limitations       |
| Conclusion           | Assessment result and rationale                        |
| Finding ID           | Related finding, if one is established                 |
| Reviewer             | Person or role reviewing the workpaper                 |
| Review Date          | Date the review was completed                          |

Record only procedures that were actually performed. Do not prepopulate successful results before evidence has been evaluated.

## 7. Evaluation of Exceptions

When a test identifies an exception:

1. Confirm the facts and relevant evidence.
2. Determine whether the exception reflects a design deficiency, implementation deficiency, operating deficiency, or evidence gap.
3. Consider the affected system, data, control objective, and relevant risk.
4. Determine whether additional evidence or testing is needed.
5. Document the issue and supporting rationale.
6. Create or update a finding when justified.
7. Define remediation and closure validation requirements where appropriate.

The existence of an exception does not automatically determine its severity. Severity should be based on documented impact, likelihood, scope, and applicable assessment criteria.

## 8. Reporting Limitations

The testing plan is designed for a simulated readiness assessment.

Synthetic records can demonstrate how a procedure is performed, how results are documented, and how findings are linked to controls. They cannot demonstrate that a real organization operated the control effectively over an actual period.

Any summary must distinguish planned testing from completed procedures and must identify material limitations.

## 9. Simulation Disclaimer

This testing plan defines proposed procedures for a fictional SaaS provider. It is not an independent audit program, completed SOC 2 examination, or certification of compliance.
