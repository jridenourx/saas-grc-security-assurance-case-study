# Vendor Risk Assessment Workpapers

## 1. Purpose

These workpapers document the procedures, evidence, assessment results, and conclusions used to evaluate third-party risks at Northstar Cloud Solutions.

They provide a repeatable approach for reviewing vendor due diligence responses and supporting evidence, identifying evidence gaps, evaluating potential control weaknesses, and determining whether risk treatment is necessary.

All assessments are part of a fictional portfolio simulation.

## 2. Assessment Procedure

Each vendor assessment should follow these steps.

### Step 1 — Confirm Vendor Scope

Document:

* Vendor ID and name.
* Service provided.
* Business purpose.
* Data accessed, processed, or stored.
* System integrations and access permissions.
* Business owner.
* Initial inherent-risk tier.
* Assessment reason and date.

**Expected output:** A confirmed assessment scope and documented assumptions.

### Step 2 — Review Due Diligence Responses

Review the completed vendor questionnaire.

For each material response:

1. Record the response.
2. Identify the associated evidence request.
3. Determine whether supporting evidence is available.
4. Evaluate whether the evidence supports the response.
5. Record unanswered questions and conflicting information.
6. Identify issues requiring follow-up.

**Expected output:** A documented assessment of questionnaire responses and evidence requirements.

### Step 3 — Evaluate Evidence

Assess relevant evidence for:

* Relevance to the control or risk.
* Reliability of the source.
* Completeness of scope and coverage.
* Timeliness.
* Traceability to the assessment procedure.

Record evidence limitations explicitly.

**Expected output:** An updated evidence register and documented assessment observations.

### Step 4 — Evaluate Risks and Controls

For each material risk:

1. Identify the risk and related vendor.
2. Identify the expected safeguard or control objective.
3. Review the supporting evidence.
4. Determine whether the evidence supports a conclusion.
5. Distinguish a design weakness, operating failure, or evidence gap.
6. Evaluate potential business impact.
7. Determine whether the initial risk assessment requires revision.

**Expected output:** A supported assessment conclusion or a clearly documented unresolved question.

### Step 5 — Determine Risk Treatment

Where assessment identifies a material issue:

* Document the finding and rationale.
* Assign an appropriate severity.
* Recommend corrective action.
* Identify the proposed owner.
* Establish a target date.
* Define required closure evidence.
* Identify approval or escalation requirements.

**Expected output:** A traceable finding and remediation action, when warranted.

### Step 6 — Finalize the Assessment

Before finalizing:

* Confirm that all material evidence requests have been addressed or documented as outstanding.
* Review the consistency of questionnaire responses and evidence.
* Reassess the risk tier where warranted.
* Document unresolved issues and limitations.
* Identify any required risk acceptance or escalation.
* Record the review date and assessment status.

**Expected output:** A documented assessment conclusion with clear limitations and next steps.

## 3. Assessment Conclusion Standards

Use the following conclusion categories:

| Conclusion             | Meaning                                                                                                |
| ---------------------- | ------------------------------------------------------------------------------------------------------ |
| Effective within scope | Available evidence and procedures support the control's operation within the defined scope and period. |
| Design weakness        | The documented control is not adequately designed to address the identified risk.                      |
| Operating failure      | Evidence indicates the control did not operate as intended under the assessed conditions.              |
| Evidence gap           | Available evidence is insufficient to reach a reliable conclusion.                                     |
| Not assessed           | The control was outside the defined scope or was not evaluated.                                        |

Do not infer a control failure solely because a vendor has not yet supplied evidence.

## 4. Vendor Assessment Workpapers

### WP-001 — Northstar Cloud Hosting

**Vendor ID:** VND-001

**Service:** Cloud infrastructure

**Preliminary inherent-risk tier:** High

**Assessment status:** Planned

**Assessment objective:** Evaluate the vendor's security responsibilities, access safeguards, logging, incident response, and recovery arrangements relevant to Northstar's hosting dependency.

#### Planned Procedures

| Procedure ID | Procedure                                                                                          | Evidence Reference | Expected Assessment Output                                                      |
| ------------ | -------------------------------------------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------- |
| WP-001-P01   | Review service scope and shared-responsibility documentation.                                      | EVD-001            | Document responsibility boundaries and unresolved ownership questions.          |
| WP-001-P02   | Review available independent assurance documentation and identify scope limitations or exceptions. | EVD-002            | Document what the assurance evidence supports and what it does not cover.       |
| WP-001-P03   | Evaluate documentation supporting privileged access, MFA, and access-management safeguards.        | EVD-003            | Document supported conclusions and remaining evidence gaps.                     |
| WP-001-P04   | Review logging, incident response, and recovery documentation.                                     | EVD-004            | Evaluate documented responsibilities and identify outstanding validation needs. |

#### Initial Assessment Notes

The hosting service is assumed to be foundational to the SaaS platform. The preliminary high inherent-risk rating reflects the potential impact of infrastructure disruption and the importance of understanding the provider's security responsibilities.

This rating does not establish that the provider has a control weakness.

#### Conclusion

**Final assessment conclusion:** Pending evidence review.

**Risk-tier decision:** Reassess after due diligence and evidence review.

**Required follow-up:** Obtain and evaluate the planned evidence, document material gaps, and determine whether escalation or risk treatment is necessary.

---

### WP-002 — SignalBridge Support

**Vendor ID:** VND-002

**Service:** Customer support platform

**Preliminary inherent-risk tier:** Moderate

**Assessment status:** Simulated desk review completed; technical and operational validation pending

**Assessment objective:** Evaluate customer data exposure, support-user permissions, data lifecycle controls, subprocessors, and incident notification arrangements.

#### Procedures and Follow-up

| Procedure ID | Procedure                                                                                                   | Evidence Reference | Status and Expected Output                                                                                                  |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| WP-002-P01   | Review the documented data flows and determine which customer information the support platform may process. | EVD-005            | Simulated desk review documented; validate the design and actual data-flow assumptions before drawing stronger conclusions. |
| WP-002-P02   | Evaluate user roles, permissions, and access-review evidence.                                               | EVD-006            | Simulated desk review documented; actual assignments and operating effectiveness remain unverified.                         |
| WP-002-P03   | Review retention, deletion, and subprocessor documentation.                                                 | EVD-007            | Planned; document data lifecycle and external-sharing considerations when evidence becomes available.                       |
| WP-002-P04   | Review incident response and customer notification documentation.                                           | EVD-008            | Planned; evaluate documented responsibilities and notification arrangements when evidence becomes available.                |

#### Simulated Desk Review Results

The fictional data-flow and role-permission artifacts described in `synthetic-vendor-assessments.md` were reviewed as part of this portfolio simulation. The scenario supports two design-level observations recorded as FND-001 and FND-002:

* The support workflow exposes more customer information than the stated support purpose requires.
* The documented support-role permissions exceed the stated business need.

These are simulated design weaknesses, not findings from a real vendor assessment. The scenario artifacts do not establish actual vendor configuration, real customer-data exposure, unauthorized access, or operating effectiveness. The related corrective actions remain open.

#### Conclusion

**Simulated assessment conclusion:** Two design-level findings are documented within the fictional scenario; technical and operational validation remains pending.

**Risk-tier decision:** The preliminary inherent-risk tier remains Moderate. Reassess residual risk only after relevant evidence and remediation validation are documented.

**Required follow-up:** Validate the data flow and role permissions, complete subprocessor oversight review, and review synthetic remediation evidence against the documented closure criteria.

---

### WP-003 — MetricForge Analytics

**Vendor ID:** VND-003

**Service:** Product analytics

**Preliminary inherent-risk tier:** Moderate

**Assessment status:** Simulated desk review completed; technical and operational validation pending

**Assessment objective:** Evaluate analytics data flows, integration permissions, data minimization, retention, external sharing, and relevant security monitoring.

#### Procedures and Follow-up

| Procedure ID | Procedure                                                        | Evidence Reference | Status and Expected Output                                                                                           |
| ------------ | ---------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------------------------------------- |
| WP-003-P01   | Review the analytics event schema and documented data flows.     | EVD-009            | Simulated desk review documented; validate the design and data-flow assumptions before drawing stronger conclusions. |
| WP-003-P02   | Review integration permissions and authentication documentation. | EVD-010            | Planned; evaluate the documented access model and identify necessary technical validation.                           |
| WP-003-P03   | Review retention, deletion, and external-sharing documentation.  | EVD-011            | Planned; document the expected data lifecycle and relevant limitations when evidence becomes available.              |
| WP-003-P04   | Review security logging and incident response documentation.     | EVD-012            | Planned; evaluate available documentation and identify outstanding evidence needs.                                   |

#### Simulated Desk Review Results

The fictional analytics event schema described in `synthetic-vendor-assessments.md` was reviewed as part of this portfolio simulation. The scenario supports FND-003: the documented event schema permits unnecessary free-text data that is not required by the stated analytics purpose.

This is a simulated design weakness, not evidence that real customer information was transmitted to an actual analytics service. Integration permissions and the complete data lifecycle remain evidence gaps, and technical validation has not been completed.

#### Conclusion

**Simulated assessment conclusion:** One design-level finding is documented within the fictional scenario; integration permissions and data lifecycle coverage remain unresolved.

**Risk-tier decision:** The preliminary inherent-risk tier remains Moderate. Reassess residual risk after evidence review and any remediation validation.

**Required follow-up:** Remove the unnecessary free-text field in the fictional design, validate the revised schema with synthetic data, review integration permissions, and evaluate retention, deletion, and external-sharing evidence.

## 5. Assessment Review Checklist

Use this checklist before marking a vendor assessment complete.

| Review Item                    | Completion Requirement                                                         |
| ------------------------------ | ------------------------------------------------------------------------------ |
| Vendor scope documented        | Service, business purpose, data exposure, and access are recorded.             |
| Questionnaire reviewed         | Responses are documented and material unanswered questions are identified.     |
| Evidence register updated      | Evidence status accurately reflects the work performed.                        |
| Evidence evaluated             | Relevant evidence is assessed for reliability, completeness, and scope.        |
| Risk register reviewed         | Relevant risk records and statuses are updated with supporting rationale.      |
| Findings documented            | Material deficiencies are supported by evidence and clear assessment criteria. |
| Risk tier reconsidered         | Changes are documented where the evidence or circumstances warrant them.       |
| Remediation defined            | Required actions have proposed owners, timelines, and closure criteria.        |
| Limitations documented         | Unresolved questions and assessment boundaries are explicit.                   |
| Assessment conclusion recorded | Final status, rationale, reviewer, and date are documented.                    |

## 6. Assessment Record Template

Use this template when recording a completed or updated vendor assessment.

| Field                       | Entry |
| --------------------------- | ----- |
| Workpaper ID                |       |
| Vendor ID                   |       |
| Assessment Date             |       |
| Assessor                    |       |
| Assessment Scope            |       |
| Procedures Performed        |       |
| Evidence Reviewed           |       |
| Results                     |       |
| Exceptions or Evidence Gaps |       |
| Related Risk IDs            |       |
| Related Finding IDs         |       |
| Initial Risk Tier           |       |
| Final Risk Tier             |       |
| Conclusion and Rationale    |       |
| Required Actions            |       |
| Review Status               |       |

## 7. Limitations

The procedures in this document include planned assessment procedures and documented simulated desk-review activities. A planned procedure must not be represented as completed until the corresponding work has actually been performed within the simulation and documented.

The simulated desk-review conclusions for SignalBridge Support and MetricForge Analytics are limited to the fictional artifacts described in this repository. They do not establish actual vendor configurations, operating effectiveness, real customer-data exposure, or the occurrence of a real incident.

All conclusions must be supported by documented evidence, assessment criteria, and explicit limitations.

## 8. Simulation Disclaimer

These workpapers are part of a fictional GRC portfolio exercise. They do not represent actual vendor assessments, independent audits, or verified security findings about real organizations.
