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

**Assessment status:** Planned

**Assessment objective:** Evaluate customer data exposure, support-user permissions, data lifecycle controls, subprocessors, and incident notification arrangements.

#### Planned Procedures

| Procedure ID | Procedure                                                                                                   | Evidence Reference | Expected Assessment Output                                                                      |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------ | ----------------------------------------------------------------------------------------------- |
| WP-002-P01   | Review the documented data flows and determine which customer information the support platform may process. | EVD-005            | Document the assumed and evidenced data exposure.                                               |
| WP-002-P02   | Evaluate user roles, permissions, and access-review evidence.                                               | EVD-006            | Identify whether the available evidence supports least-privilege and access-review conclusions. |
| WP-002-P03   | Review retention, deletion, and subprocessor documentation.                                                 | EVD-007            | Document data lifecycle and external-sharing considerations.                                    |
| WP-002-P04   | Review incident response and customer notification documentation.                                           | EVD-008            | Evaluate documented responsibilities and notification arrangements.                             |

#### Initial Assessment Notes

The initial scenario assumes that support personnel may access customer account information and support records.

The extent of access, appropriateness of permissions, and effectiveness of safeguards have not yet been established.

#### Conclusion

**Final assessment conclusion:** Pending evidence review.

**Risk-tier decision:** Reassess after due diligence and evidence review.

**Required follow-up:** Validate data exposure, evaluate access permissions, and document any evidence gaps or supported control weaknesses.

---

### WP-003 — MetricForge Analytics

**Vendor ID:** VND-003

**Service:** Product analytics

**Preliminary inherent-risk tier:** Moderate

**Assessment status:** Planned

**Assessment objective:** Evaluate analytics data flows, integration permissions, data minimization, retention, external sharing, and relevant security monitoring.

#### Planned Procedures

| Procedure ID | Procedure                                                        | Evidence Reference | Expected Assessment Output                                                                                |
| ------------ | ---------------------------------------------------------------- | ------------------ | --------------------------------------------------------------------------------------------------------- |
| WP-003-P01   | Review the analytics event schema and documented data flows.     | EVD-009            | Determine what information is intended to be transmitted and identify unresolved data exposure questions. |
| WP-003-P02   | Review integration permissions and authentication documentation. | EVD-010            | Evaluate the documented access model and identify necessary technical validation.                         |
| WP-003-P03   | Review retention, deletion, and external-sharing documentation.  | EVD-011            | Document the expected data lifecycle and relevant limitations.                                            |
| WP-003-P04   | Review security logging and incident response documentation.     | EVD-012            | Evaluate available documentation and identify outstanding evidence needs.                                 |

#### Initial Assessment Notes

The scenario assumes that the analytics service supports product improvement rather than core service delivery.

The data transmitted through the integration, the permissions granted, and the service's actual dependency level require validation.

#### Conclusion

**Final assessment conclusion:** Pending evidence review.

**Risk-tier decision:** Reassess after due diligence and evidence review.

**Required follow-up:** Validate the data flow and permissions, evaluate the relevant evidence, and revise the preliminary risk assessment if necessary.

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

The procedures in this document are planned assessment procedures. They must not be represented as completed tests until the corresponding work has actually been performed within the simulation.

The workpapers do not establish that any vendor has passed or failed an assessment.

All results must be supported by the documented evidence, assessment criteria, and limitations.

## 8. Simulation Disclaimer

These workpapers are part of a fictional GRC portfolio exercise. They do not represent actual vendor assessments, independent audits, or verified security findings about real organizations.
