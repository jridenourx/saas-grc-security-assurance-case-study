# Third-Party Risk Findings and Remediation Tracker

> **SIMULATION NOTICE:** All findings, evidence, owners, deadlines, and remediation activities in this document are fictional. They demonstrate a proposed GRC process and do not describe actual vendor deficiencies.

## 1. Purpose

This tracker documents findings arising from the simulated third-party assessments, including their supporting evidence, severity rationale, corrective actions, ownership, and closure requirements.

A finding is recorded when the synthetic assessment supports a specific weakness. Evidence gaps that do not establish a control deficiency are tracked separately for follow-up.

## 2. Finding Severity Methodology

Severity is assigned using the approach in `docs/methodology.md`.

| Severity | General Interpretation                                                            |
| -------- | --------------------------------------------------------------------------------- |
| Critical | Severe exposure requiring immediate escalation and urgent treatment               |
| High     | Significant weakness that could materially affect security or business operations |
| Moderate | Meaningful weakness requiring planned corrective action                           |
| Low      | Limited weakness or improvement opportunity                                       |

Severity ratings below are provisional judgments for the fictional scenario. They should be revisited if additional evidence materially changes the assessment.

## 3. Findings Register

| Finding ID | Vendor ID | Finding Title                                              | Related Risk ID | Severity | Assessment Conclusion | Status |
| ---------- | --------- | ---------------------------------------------------------- | --------------- | -------- | --------------------- | ------ |
| FND-001    | VND-002   | Excessive customer information exposed in support workflow | RSK-004         | High     | Design weakness       | Open   |
| FND-002    | VND-002   | Support-role permissions exceed documented business need   | RSK-004         | High     | Design weakness       | Open   |
| FND-003    | VND-003   | Analytics event schema permits unnecessary free-text data  | RSK-007         | Moderate | Design weakness       | Open   |

These three findings are supported by the synthetic assessment scenarios described in `synthetic-vendor-assessments.md`.

They are not findings against real vendors.

## 4. Detailed Findings

### FND-001 — Excessive Customer Information Exposed in Support Workflow

**Vendor:** SignalBridge Support
**Vendor ID:** VND-002
**Related risk:** RSK-004
**Severity:** High
**Status:** Open

#### Condition

The synthetic support-platform data-flow summary describes a support workflow that displays more customer record information than is necessary for basic case routing.

#### Assessment Criteria

The workflow should expose only the customer information needed for its intended business purpose. Access to additional information should be justified and appropriately restricted.

#### Evidence

* EVD-005 — Fictional support-platform data-flow summary.
* Questionnaire references Q-12 and Q-17.

#### Risk and Impact

Unnecessary customer information displayed in support workflows could increase the likelihood and potential impact of inappropriate disclosure or access.

#### Root Cause

The synthetic scenario suggests that the workflow's data-display requirements have not been sufficiently limited to the minimum information necessary for the stated function.

This is a proposed explanation based on the fictional design. It is not a verified root cause from a real investigation.

#### Recommended Remediation

1. Identify customer fields required for support case routing.
2. Remove unnecessary fields from the support workflow.
3. Restrict access to sensitive fields where they remain operationally necessary.
4. Document the approved data-display requirements.
5. Validate the revised workflow using a synthetic test record.

#### Proposed Owner

Customer Success, supported by Security / IT and the support-platform administrator.

#### Closure Criteria

* An updated workflow specification documents the permitted fields.
* Synthetic test evidence demonstrates that unnecessary customer information is no longer displayed in the assessed workflow.
* Any remaining access to sensitive fields has a documented business justification.
* A reviewer confirms that the evidence supports the intended correction.

**Related remediation action:** ACT-001

---

### FND-002 — Support-Role Permissions Exceed Documented Business Need

**Vendor:** SignalBridge Support
**Vendor ID:** VND-002
**Related risk:** RSK-004
**Severity:** High
**Status:** Open

#### Condition

The synthetic role-permission matrix includes a support role with broader record visibility than the minimum required for basic support case handling. The supplied access-review summary does not demonstrate that this permission was reviewed and justified during the relevant review period.

#### Assessment Criteria

User permissions should be consistent with assigned responsibilities and the principle of least privilege. Access reviews should identify and resolve unnecessary permissions.

#### Evidence

* EVD-006 — Fictional role-permission matrix and access-review summary.
* Questionnaire references Q-08, Q-09, and Q-11.

#### Risk and Impact

Excessive permissions could allow personnel to view customer information outside their business needs, increasing the potential impact of misuse or account compromise.

#### Root Cause

The synthetic evidence suggests that role design and access-review documentation do not adequately demonstrate that permissions are limited to required support functions.

The precise cause remains a scenario assumption until further investigation within the simulation.

#### Recommended Remediation

1. Review the permissions assigned to each support role.
2. Define the minimum permissions required for each role.
3. Remove permissions that are not justified by business requirements.
4. Document approval for any necessary exceptions.
5. Establish a periodic access-review process with defined ownership.
6. Validate the revised permissions using a synthetic role-permission test.

#### Proposed Owner

Customer Success, supported by Security / IT.

#### Closure Criteria

* An approved role-permission matrix documents the intended access.
* Synthetic test results demonstrate that the assessed role no longer has the identified unnecessary permission.
* Any exceptions have a documented business justification and approval.
* The access-review procedure identifies a responsible owner and review frequency.
* A reviewer validates the closure evidence.

**Related remediation action:** ACT-002

---

### FND-003 — Analytics Event Schema Permits Unnecessary Free-Text Data

**Vendor:** MetricForge Analytics
**Vendor ID:** VND-003
**Related risk:** RSK-007
**Severity:** Moderate
**Status:** Open

#### Condition

The synthetic analytics event schema contains a free-text field populated from an application record. The documented analytics objective does not require that field to contain customer business information.

#### Assessment Criteria

Data collected through analytics integrations should be limited to information necessary for the stated purpose. Event schemas should define permitted attributes and prevent unnecessary sensitive information from being transmitted.

#### Evidence

* EVD-009 — Fictional analytics event schema.
* Questionnaire references Q-12, Q-13, and Q-17.

#### Risk and Impact

Unnecessary free-text collection could transmit customer information to an external analytics service, increasing the risk of inappropriate disclosure, retention, or sharing.

#### Root Cause

The synthetic event specification does not sufficiently constrain the content permitted in the free-text field.

This is a design-level observation within the simulation, not evidence that a real customer record was transmitted.

#### Recommended Remediation

1. Remove the unnecessary free-text field from the analytics event schema.
2. Define an approved list of event attributes.
3. Document prohibited data types, including customer content not required for analytics.
4. Add a validation step to the event-generation process.
5. Test the revised schema using synthetic event data.
6. Document the approved schema and its owner.

#### Proposed Owner

Engineering, supported by Security / IT and GRC.

#### Closure Criteria

* The updated event schema excludes the unnecessary free-text field.
* Synthetic test results demonstrate that the revised event does not transmit that field.
* The approved event attributes and prohibited data types are documented.
* A reviewer confirms that the evidence supports the intended correction.

**Related remediation action:** ACT-003

---

## 5. Remediation Action Tracker

The following dates are proposed planning dates for the fictional case study. They are not actual vendor commitments.

| Action ID | Finding ID | Corrective Action                                                                  | Proposed Owner                   | Target Date | Status | Required Closure Evidence                                                    |
| --------- | ---------- | ---------------------------------------------------------------------------------- | -------------------------------- | ----------- | ------ | ---------------------------------------------------------------------------- |
| ACT-001   | FND-001    | Minimize customer information displayed in the support workflow                    | Customer Success                 | 2026-11-13  | Open   | Updated workflow specification and synthetic test results                    |
| ACT-002   | FND-002    | Restrict support-role permissions and establish documented access reviews          | Customer Success / Security / IT | 2026-11-20  | Open   | Approved role matrix, synthetic permission test, and access-review procedure |
| ACT-003   | FND-003    | Remove unnecessary free-text analytics data and validate the approved event schema | Engineering                      | 2026-11-13  | Open   | Updated event schema and synthetic test results                              |

### Remediation Status Definitions

| Status             | Meaning                                                                         |
| ------------------ | ------------------------------------------------------------------------------- |
| Open               | Action is documented but work has not been confirmed as underway.               |
| In Progress        | Corrective work has started.                                                    |
| Pending Validation | The owner reports completion, but closure evidence requires review.             |
| Closed             | Required evidence has been reviewed and closure criteria are met.               |
| Accepted Risk      | An authorized decision-maker has formally accepted the remaining risk.          |
| Deferred           | Work has been postponed with documented justification and appropriate approval. |

Do not change an action to **Closed** until the specified closure evidence has been reviewed and the closure criteria are satisfied.

## 6. Evidence Gaps Requiring Follow-Up

The following items remain evidence gaps rather than confirmed control failures.

| Follow-Up ID | Vendor ID | Issue Requiring Follow-Up                                                   | Related Evidence | Required Next Step                                                                             |
| ------------ | --------- | --------------------------------------------------------------------------- | ---------------- | ---------------------------------------------------------------------------------------------- |
| FUP-001      | VND-001   | Shared security responsibilities are not fully mapped to accountable owners | EVD-001          | Complete the responsibility mapping and obtain confirmation of material ownership assignments. |
| FUP-002      | VND-001   | Privileged-access and MFA implementation is not sufficiently demonstrated   | EVD-003          | Obtain appropriately scoped configuration evidence and evaluate account coverage.              |
| FUP-003      | VND-001   | Logging coverage and recovery performance are not sufficiently demonstrated | EVD-004          | Review logging-coverage evidence and a relevant recovery test record.                          |
| FUP-004      | VND-002   | Complete subprocessor oversight is not demonstrated                         | EVD-007          | Reconcile the subprocessor inventory with applicable security and contractual requirements.    |
| FUP-005      | VND-003   | Least-privilege integration permissions are not sufficiently demonstrated   | EVD-010          | Validate permissions against the minimum requirements for the analytics function.              |
| FUP-006      | VND-003   | Complete analytics data lifecycle coverage is not demonstrated              | EVD-011          | Review retention, exports, backups, deletion, and downstream sharing.                          |

These follow-up items should remain open until the necessary evidence has been evaluated or the outstanding uncertainty has been addressed through a documented risk decision.

If subsequent evidence establishes a control deficiency, create or update a finding with a clear evidence reference and rationale.

## 7. Reporting and Escalation

The GRC function should periodically review:

* Open findings by severity.
* Remediation actions approaching or exceeding target dates.
* Evidence gaps affecting critical safeguards.
* Findings awaiting validation.
* Accepted or deferred risks requiring review.
* Vendors whose risk profile has materially changed.

High-severity findings should be escalated according to the organization's defined risk governance and approval process.

The severity of a finding and the inherent-risk tier of its vendor are related but distinct measures. A high-risk vendor does not automatically have a high-severity finding, and a moderate-risk vendor can still have a significant control weakness.

## 8. Simulation Limitations

The findings and actions above are based on fictional evidence descriptions. They demonstrate how assessment observations can be translated into documented corrective actions.

No real vendor has been tested, contacted, or assessed. No remediation has actually been completed. All statuses must be interpreted within the simulation.

## 9. Simulation Disclaimer

This document is a fictional GRC portfolio artifact. It does not represent a real audit finding, actual security incident, vendor remediation commitment, or verified assessment of any real organization.
