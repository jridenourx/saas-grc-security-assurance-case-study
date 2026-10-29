# Vendor Risk Assessment Matrix

## 1. Purpose

This matrix applies the risk-tiering methodology defined in `docs/methodology.md` to the three vendors in the Northstar Cloud Solutions scenario.

The ratings are preliminary, scenario-based estimates used to establish initial due diligence priorities. They are not conclusions based on completed vendor questionnaires or independently verified vendor evidence.

## 2. Scoring Method

Each vendor receives a score from 1 to 5 for four inherent-risk factors.

| Factor                                | Weight |
| ------------------------------------- | -----: |
| Data sensitivity                      |    30% |
| System access and integration         |    25% |
| Business criticality                  |    25% |
| External dependency and concentration |    20% |

### Calculation

**Inherent Risk Score = (Data Sensitivity × 0.30) + (System Access × 0.25) + (Business Criticality × 0.25) + (Dependency and Concentration × 0.20)**

Risk tiers:

* Low: 1.00–2.00
* Moderate: 2.01–3.50
* High: 3.51–5.00

The score is rounded to two decimal places for reporting.

These thresholds are proposed for this simulated case study and are not universal industry standards.

## 3. Preliminary Vendor Ratings

| Vendor ID | Vendor                  | Data Sensitivity (30%) | System Access (25%) | Business Criticality (25%) | Dependency (20%) | Weighted Score | Preliminary Tier |
| --------- | ----------------------- | ---------------------: | ------------------: | -------------------------: | ---------------: | -------------: | ---------------- |
| VND-001   | Northstar Cloud Hosting |                      5 |                   4 |                          5 |                5 |           4.75 | High             |
| VND-002   | SignalBridge Support    |                      4 |                   3 |                          3 |                3 |           3.30 | Moderate         |
| VND-003   | MetricForge Analytics   |                      3 |                   3 |                          2 |                2 |           2.55 | Moderate         |

### Calculation Verification

**VND-001 — Northstar Cloud Hosting**

(5 × 0.30) + (4 × 0.25) + (5 × 0.25) + (5 × 0.20)

= 1.50 + 1.00 + 1.25 + 1.00

= **4.75 — High**

**VND-002 — SignalBridge Support**

(4 × 0.30) + (3 × 0.25) + (3 × 0.25) + (3 × 0.20)

= 1.20 + 0.75 + 0.75 + 0.60

= **3.30 — Moderate**

**VND-003 — MetricForge Analytics**

(3 × 0.30) + (3 × 0.25) + (2 × 0.25) + (2 × 0.20)

= 0.90 + 0.75 + 0.50 + 0.40

= **2.55 — Moderate**

## 4. Scoring Rationale

### VND-001 — Northstar Cloud Hosting

**Preliminary score: 4.75 — High**

* **Data sensitivity: 5.** The scenario assumes the hosted environment stores customer business records and may process application or infrastructure logs.
* **System access: 4.** The hosting relationship creates significant infrastructure and administrative access considerations. Actual provider access arrangements remain unverified.
* **Business criticality: 5.** A disruption to the hosting service could prevent customers from using Northstar's core SaaS platform.
* **Dependency: 5.** The service is assumed to be foundational to the platform. Migration complexity and alternative hosting options have not yet been evaluated.

**Assessment priority:** Highest. Review service responsibilities, access arrangements, independent assurance evidence, incident handling, resilience, and recovery commitments.

**Important limitation:** The score reflects the assumed importance of the hosting service, not evidence of a security weakness at the provider.

### VND-002 — SignalBridge Support

**Preliminary score: 3.30 — Moderate**

* **Data sensitivity: 4.** The service may process customer account information and support records. The extent of access to customer business records needs confirmation.
* **System access: 3.** Support personnel may access customer information through assigned permissions. The actual permissions and integration scope have not been validated.
* **Business criticality: 3.** A disruption could affect customer support operations, but the scenario does not establish that the platform is required to run the core SaaS application.
* **Dependency: 3.** The business relies on the support platform, but replacement options and transition complexity remain unknown.

**Assessment priority:** Review customer data exposure, user permissions, authentication, retention, subprocessors, and contractual security requirements.

**Important limitation:** The rating assumes a moderate operational dependency. It should be revisited if the platform proves essential to incident response or other critical operations.

### VND-003 — MetricForge Analytics

**Preliminary score: 2.55 — Moderate**

* **Data sensitivity: 3.** The service is assumed to process application events and usage metadata. Whether sensitive identifiers or customer content are transmitted remains unverified.
* **System access: 3.** An application integration may transmit event data. The integration's permissions and technical boundaries require validation.
* **Business criticality: 2.** The scenario treats analytics as useful for product improvement rather than essential to core service delivery.
* **Dependency: 2.** The initial assumption is that analytics could be disabled or replaced with limited operational impact. This must be confirmed.

**Assessment priority:** Review event schemas, data minimization, retention, access permissions, and external data sharing.

**Important limitation:** The rating could increase if analytics receives sensitive customer content or becomes operationally essential.

## 5. Escalation Review

The numerical score is only one input into the final tier decision.

The following escalation questions must be addressed during due diligence:

| Vendor ID | Escalation Question                                                                                     | Current Status |
| --------- | ------------------------------------------------------------------------------------------------------- | -------------- |
| VND-001   | Are critical security, administrative access, logging, or recovery safeguards insufficiently evidenced? | Unassessed     |
| VND-002   | Can support users access sensitive customer data beyond their business need?                            | Unassessed     |
| VND-003   | Does the analytics integration transmit sensitive information or provide excessive access?              | Unassessed     |

If an escalation condition is identified, the rationale, decision, approval requirements, and resulting risk treatment must be documented.

Insufficient evidence is a reason to investigate and manage uncertainty; it is not automatically proof of a control failure.

## 6. Reassessment Triggers

Risk scores and tiers should be reviewed when:

* New evidence changes the understanding of vendor controls.
* Data categories or volumes change.
* Access permissions or integrations change.
* Business criticality changes.
* A material incident occurs.
* A vendor introduces a significant subprocessor.
* A contract or service changes materially.
* A previously identified risk is remediated or accepted.

A reassessment should document the reason for the change, the revised factor scores where applicable, the recalculated weighted score, the resulting tier, and any required approval or risk treatment.

## 7. Limitations and Next Steps

These are preliminary inherent-risk ratings. They do not represent residual risk and do not establish that any vendor has passed or failed a security assessment.

The next assessment steps are to collect synthetic due diligence evidence, evaluate vendor responses, document evidence limitations, identify supported findings, and determine whether the initial ratings require revision.

The numerical score should be retained as a preliminary assessment until the relevant evidence has been reviewed. Any subsequent tier change should include a documented rationale.

All vendor profiles and scores are fictional and intended solely for this portfolio case study.

