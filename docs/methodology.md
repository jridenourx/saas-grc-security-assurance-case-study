# GRC Assessment Methodology

## 1. Purpose

This document establishes a consistent methodology for evaluating risks, reviewing evidence, assessing controls, documenting findings, and tracking remediation within the Northstar Cloud Solutions case study.

The methodology will be reused across third-party risk management, customer security assurance, SOC 2 readiness, and technical control validation.

## 2. Assessment Principles

All assessments will follow these principles:

* **Risk-based:** Prioritize risks according to potential business impact and likelihood.
* **Evidence-based:** Support conclusions with documented evidence and defined assessment criteria.
* **Traceable:** Connect risks, controls, evidence, findings, and remediation actions using unique identifiers.
* **Consistent:** Apply documented scoring criteria across comparable assessments.
* **Transparent:** Record limitations, assumptions, and unresolved questions.
* **Proportionate:** Match assessment depth to the risk and business importance of the activity.
* **Honest:** Do not represent missing evidence as proof of failure or unverified controls as effective.

## 3. Risk Assessment Methodology

### 3.1 Inherent Risk

Inherent risk represents the level of risk before considering the effectiveness of mitigating controls.

For third-party assessments, inherent risk will be evaluated using four factors:

| Factor                                | Weight | Assessment Considerations                                                               |
| ------------------------------------- | -----: | --------------------------------------------------------------------------------------- |
| Data sensitivity                      |    30% | Sensitivity and volume of information the vendor may access, process, or store          |
| System access and integration         |    25% | Access privileges, connectivity, integrations, and potential paths into company systems |
| Business criticality                  |    25% | Operational impact if the vendor becomes unavailable or fails to deliver its service    |
| External dependency and concentration |    20% | Difficulty replacing the vendor and the degree of dependency on its services            |

Each factor receives a score from 1 to 5.

| Score | General Meaning              |
| ----- | ---------------------------- |
| 1     | Very low exposure or impact  |
| 2     | Low exposure or impact       |
| 3     | Moderate exposure or impact  |
| 4     | High exposure or impact      |
| 5     | Very high exposure or impact |

The weighted inherent risk score is calculated as:

**Inherent Risk Score = (Data Sensitivity × 0.30) + (System Access × 0.25) + (Business Criticality × 0.25) + (Dependency and Concentration × 0.20)**

The result ranges from 1.00 to 5.00.

### 3.2 Provisional Risk Tiers

The following thresholds are proposed for this case study:

| Score     | Risk Tier |
| --------- | --------- |
| 1.00–2.00 | Low       |
| 2.01–3.50 | Moderate  |
| 3.51–5.00 | High      |

These thresholds are internal design choices for the simulation, not universal industry standards.

Risk tiers will be reviewed against the vendor profiles to determine whether they produce reasonable and defensible results.

### 3.3 Mandatory Escalation

A numerical score does not automatically capture every material risk.

The following conditions require documented escalation and consideration of a higher risk tier or additional approval:

* Broad privileged access to sensitive systems or data.
* Sensitive data processing without adequate safeguards.
* Critical service dependency without a credible continuity or recovery approach.
* Unresolved critical security issues.
* Insufficient evidence to evaluate a critical control or material risk.

An escalation does not automatically establish that a vendor has failed a control. The rationale and resulting decision must be documented.

### 3.4 Control Risk and Residual Risk

Control risk considers whether relevant safeguards are appropriately designed and supported by evidence of operation.

Residual risk represents the remaining risk after considering the controls and risk treatments that are sufficiently supported by the assessment.

Residual risk must not be calculated by simply subtracting a control score from inherent risk. Any residual-risk rating must consider the nature of the threat, the importance of the safeguards, evidence limitations, and the remaining exposure.

Where evidence is insufficient, the assessment will document the uncertainty rather than assume the control is effective.

## 4. Evidence Evaluation

Evidence will be assessed for relevance, reliability, completeness, and timeliness.

| Evidence Attribute | Review Question                                                                     |
| ------------------ | ----------------------------------------------------------------------------------- |
| Relevance          | Does the evidence address the control or risk being assessed?                       |
| Reliability        | Is the source identifiable, and is the evidence credible for the conclusion?        |
| Completeness       | Does the evidence cover the relevant systems, users, period, or population?         |
| Timeliness         | Is the evidence current enough for the assessment purpose?                          |
| Traceability       | Can the evidence be linked to a specific control, request, or assessment procedure? |

Evidence records should include an identifier, description, source, date, related control or risk, assessment status, and limitations where applicable.

Synthetic evidence must be labeled as simulated. It must not be represented as a genuine company record or production-system export.

## 5. Assessment Conclusion Categories

Assessment results will distinguish among the following conditions:

**Effective within scope:** The evidence and procedures performed support the conclusion that the control operated as intended within the defined scope and period.

**Design weakness:** The control or process is inadequately designed to address the identified risk.

**Operating failure:** Evidence indicates that the control did not operate as intended under the assessed conditions.

**Evidence gap:** Available evidence is insufficient to support a reliable conclusion.

**Not assessed:** The control was outside the assessment scope or was not evaluated.

These categories are assessment conclusions, not automatic severity ratings. The significance of each issue must be evaluated separately.

## 6. Finding Severity

Findings will be assigned a severity based on the significance of the risk, potential business impact, affected systems or data, existing safeguards, and urgency of remediation.

| Severity | General Criteria                                                                                 |
| -------- | ------------------------------------------------------------------------------------------------ |
| Critical | A severe exposure or control failure requiring immediate escalation and urgent risk treatment    |
| High     | A significant weakness that could materially affect security, compliance, or business operations |
| Moderate | A meaningful weakness requiring planned corrective action                                        |
| Low      | A limited weakness or improvement opportunity with comparatively low expected impact             |

Severity decisions must include a documented rationale. The table provides general guidance rather than an automatic scoring formula.

An evidence gap may warrant significant attention when it prevents evaluation of a critical safeguard, but missing evidence alone does not prove that the underlying control has failed.

## 7. Remediation Management

Each remediation action should document:

* Action identifier.
* Related finding and risk identifiers.
* Description of the required corrective action.
* Assigned owner or responsible function.
* Priority and target completion date.
* Current status.
* Required closure evidence.
* Validation result and closure date, when applicable.

Remediation status will use the following values:

* Open
* In Progress
* Pending Validation
* Closed
* Accepted Risk
* Deferred

Accepted risks and deferred actions must include a documented rationale, appropriate approval, and review date where applicable.

An action should not be marked closed solely because the responsible person reports that the work is complete. Closure requires the specified evidence and validation appropriate to the finding.

## 8. Identifier Standards

The project will use consistent identifiers to maintain traceability.

| Record Type            | Prefix | Example  |
| ---------------------- | ------ | -------- |
| Vendor                 | VND    | VND-001  |
| Risk                   | RSK    | RSK-001  |
| Control                | CTRL   | CTRL-001 |
| Evidence               | EVD    | EVD-001  |
| Customer Questionnaire | CQA    | CQA-001  |
| Finding                | FND    | FND-001  |
| Remediation Action     | ACT    | ACT-001  |

Identifiers must be unique within their record type and remain stable when the related record is updated.

## 9. Framework Use

Relevant industry frameworks and guidance will inform the assessment criteria where appropriate.

These include:

* AICPA Trust Services Criteria for the SOC 2 readiness workstream.
* NIST SP 800-161 Rev. 1 for cybersecurity supply chain risk management concepts.
* NIST SP 800-53 Rev. 5 for relevant security and privacy control concepts.
* AWS security guidance for selected cloud configuration assessments.

Framework references will be used selectively. The project will not imply that every framework control applies to every vendor or that a mapping alone demonstrates compliance.

## 10. Quality Review

Before a work product is finalized, it should be checked for:

* Clear scope and assessment criteria.
* Consistency between evidence and conclusions.
* Documented rationale for risk and severity ratings.
* Traceability between related records.
* Appropriate handling of evidence gaps and limitations.
* Clear ownership and closure criteria for remediation.
* Accurate use of framework references.
* Compliance with the project's simulation disclaimer.

## 11. Limitations

This methodology is designed for a simulated portfolio exercise. Its scoring thresholds and assessment procedures are proposed approaches for the fictional scenario, not a substitute for an organization's approved risk methodology or an independent auditor's professional judgment.
