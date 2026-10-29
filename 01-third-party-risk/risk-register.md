# Third-Party Risk Register

## 1. Purpose

This register documents third-party risks identified or requiring evaluation within the Northstar Cloud Solutions case study.

It connects vendor risk assessments to supporting evidence, potential business impact, risk treatment, and remediation activities.

The risks below are initial assessment items based on the fictional scenario. They are not all confirmed control deficiencies. Each risk must be evaluated against the evidence collected during due diligence.

## 2. Risk Rating Approach

Initial inherent-risk tiers are established using the methodology in `docs/methodology.md` and the preliminary scores in `01-third-party-risk/vendor-risk-assessment-matrix.md`.

The risk register distinguishes between:

* **Potential risk:** An exposure requiring assessment.
* **Confirmed issue:** A weakness or exposure supported by sufficient evidence.
* **Evidence gap:** Information is insufficient to reach a reliable conclusion.
* **Residual risk:** Risk remaining after supported consideration of controls and risk treatment.

A risk can be recorded before a control failure has been confirmed.

## 3. Risk Register

| Risk ID | Vendor ID | Risk Description                                                                                                                                     | Potential Business Impact                                                                  | Initial Priority | Supporting Evidence        | Current Status     | Proposed Risk Treatment                                                                     |
| ------- | --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------- | -------------------------- | ------------------ | ------------------------------------------------------------------------------------------- |
| RSK-001 | VND-001   | Insufficient clarity regarding shared security responsibilities could leave important safeguards without a clearly accountable owner.                | Security-control gaps, delayed incident response, or unclear accountability                | High             | EVD-001 — Planned          | Assessment Pending | Document shared responsibilities and confirm ownership of material security controls.       |
| RSK-002 | VND-001   | Inadequate privileged-access safeguards could increase the risk of unauthorized changes to systems supporting Northstar's service.                   | Unauthorized access, service disruption, or exposure of customer information               | High             | EVD-003 — Planned          | Assessment Pending | Review privileged-access requirements, MFA, permissions, and available supporting evidence. |
| RSK-003 | VND-001   | Insufficient logging, incident response, or recovery capabilities could limit detection and recovery from security events or service disruptions.    | Delayed detection, prolonged outage, or incomplete incident investigation                  | High             | EVD-004 — Planned          | Assessment Pending | Review logging responsibilities, incident procedures, and recovery documentation.           |
| RSK-004 | VND-002   | Excessive support-user permissions could expose customer information to personnel without a business need.                                           | Unauthorized disclosure or inappropriate access to customer records                        | High             | EVD-005, EVD-006 — Planned | Assessment Pending | Validate data exposure and review role assignments against least-privilege expectations.    |
| RSK-005 | VND-002   | Inadequate retention, deletion, or subprocessor oversight could result in customer information being retained or shared inappropriately.             | Unintended data exposure, contractual issues, or loss of control over customer information | Moderate         | EVD-007 — Planned          | Assessment Pending | Review retention requirements, deletion procedures, and subprocessor arrangements.          |
| RSK-006 | VND-002   | Inadequate incident notification arrangements could delay Northstar's response to an incident affecting the support service or customer data.        | Delayed investigation, response, or customer communication                                 | Moderate         | EVD-008 — Planned          | Assessment Pending | Review incident response responsibilities and applicable notification commitments.          |
| RSK-007 | VND-003   | The analytics integration could transmit sensitive identifiers or customer content beyond the intended data scope.                                   | Unnecessary exposure of customer information or inappropriate data sharing                 | Moderate         | EVD-009 — Planned          | Assessment Pending | Review event schemas and data flows; document data minimization requirements.               |
| RSK-008 | VND-003   | Excessive integration permissions or weak authentication could permit unauthorized access to analytics-related systems or data.                      | Unauthorized access, data disclosure, or misuse of integration credentials                 | Moderate         | EVD-010 — Planned          | Assessment Pending | Review integration permissions, authentication, and credential-management expectations.     |
| RSK-009 | VND-003   | Inadequate retention or external-sharing controls could result in analytics data being kept longer than intended or shared beyond approved purposes. | Unnecessary data exposure and reduced control over information                             | Moderate         | EVD-011 — Planned          | Assessment Pending | Review retention, deletion, and external data-sharing arrangements.                         |

## 4. Risk Ownership

| Risk ID | Proposed Risk Owner | Supporting Functions           |
| ------- | ------------------- | ------------------------------ |
| RSK-001 | Security / IT       | GRC, Procurement               |
| RSK-002 | Security / IT       | GRC, Engineering               |
| RSK-003 | Security / IT       | GRC, Engineering               |
| RSK-004 | Customer Success    | Security / IT, GRC             |
| RSK-005 | Customer Success    | Legal / Privacy, GRC           |
| RSK-006 | Customer Success    | Security / IT, Legal / Privacy |
| RSK-007 | Engineering         | Security / IT, GRC             |
| RSK-008 | Engineering         | Security / IT, GRC             |
| RSK-009 | Engineering         | Legal / Privacy, GRC           |

These are proposed responsibilities for the fictional organization. They must not be interpreted as assignments at a real company.

## 5. Risk Status Definitions

| Status                    | Meaning                                                                                                     |
| ------------------------- | ----------------------------------------------------------------------------------------------------------- |
| Assessment Pending        | The risk has been identified for evaluation, but sufficient assessment work has not been completed.         |
| Under Assessment          | Relevant evidence is being reviewed and the risk is being evaluated.                                        |
| Open — Treatment Required | Assessment supports a risk requiring corrective action or another documented treatment.                     |
| Pending Validation        | Treatment has been reported complete but requires validation.                                               |
| Accepted Risk             | An authorized decision-maker has formally accepted the risk within the defined authority and review period. |
| Closed                    | The risk has been addressed or otherwise resolved, and the documented closure criteria have been met.       |

Do not move a risk to a confirmed issue or treatment-required status without recording the assessment basis.

## 6. Risk Treatment and Closure Requirements

When assessment confirms a material issue, the corresponding record should include:

* A clear description of the supported exposure
