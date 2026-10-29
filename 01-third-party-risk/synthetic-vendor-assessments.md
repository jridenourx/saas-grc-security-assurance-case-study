# Synthetic Vendor Assessments and Evidence

> **SIMULATION NOTICE:** This document contains fictional vendor responses, fictional evidence descriptions, and simulated assessment results created for a portfolio exercise. It does not represent actual vendor statements, real assurance reports, or evidence obtained from real organizations.

## 1. Purpose

This document demonstrates how a GRC analyst can evaluate third-party due diligence responses, review supporting evidence, identify limitations, and reach documented assessment conclusions.

The assessments use the vendor inventory, due diligence questionnaire, evidence register, preliminary risk matrix, and risk register established in this repository.

All responses and evidence described below are synthetic scenario artifacts. They should not be interpreted as statements about real service providers.

## 2. Assessment Approach

Each vendor assessment follows five steps:

1. Document the fictional vendor response.
2. Identify the supporting synthetic evidence.
3. Evaluate whether the evidence supports the response.
4. Document the assessment conclusion and limitations.
5. Identify any required follow-up, finding, or risk treatment.

A vendor response is not accepted automatically. The assessment considers the evidence available, the scope covered, and the risk being evaluated.

## 3. VND-001 — Northstar Cloud Hosting

### 3.1 Assessment Profile

| Field                          | Details                                                                            |
| ------------------------------ | ---------------------------------------------------------------------------------- |
| Vendor ID                      | VND-001                                                                            |
| Service                        | Cloud infrastructure                                                               |
| Preliminary inherent-risk tier | High                                                                               |
| Assessment type                | Initial due diligence                                                              |
| Evidence type                  | Synthetic documentation and fictional assessment records                           |
| Assessment status              | Simulated assessment completed for selected topics; other topics remain unassessed |

### 3.2 Synthetic Responses and Evidence

#### Assessment Area A — Shared Security Responsibilities

**Questionnaire reference:** Q-05

**Synthetic vendor response:** Yes. The provider documents responsibilities for the cloud infrastructure service, while customers remain responsible for certain configuration and access-management activities.

**Synthetic evidence:** EVD-001 — Fictional shared-responsibility summary.

**Evidence description:** The simulated document identifies general responsibility categories for infrastructure operations, customer-managed identities, workload configuration, and application-level safeguards. It does not assign a named owner to every material control in Northstar's proposed environment.

**Assessment procedure:** Compare the documented responsibility categories with the security responsibilities Northstar needs to manage.

**Result:** The synthetic evidence establishes that a responsibility model is documented, but it does not establish complete responsibility allocation for Northstar's specific environment.

**Conclusion:** Evidence gap.

**Limitation:** This result concerns the fictional evidence supplied for this exercise. It is not a statement about any actual cloud provider.

#### Assessment Area B — Privileged Access and MFA

**Questionnaire references:** Q-07, Q-08, Q-11

**Synthetic vendor response:** Yes. Privileged access is intended to be restricted, and multifactor authentication is required for designated administrative access.

**Synthetic evidence:** EVD-003 — Fictional access-control standard and administrative access procedure.

**Evidence description:** The simulated documentation states that privileged access should be limited to authorized personnel, use MFA, and be reviewed periodically. The evidence package does not contain a complete configuration export or a population-level test demonstrating that all relevant privileged identities comply with the stated requirements.

**Assessment procedure:** Compare the documented requirements with the evidence needed to validate actual access settings and account coverage.

**Result:** The documentation supports the existence of an access-control requirement, but it does not demonstrate that the requirement is consistently implemented.

**Conclusion:** Evidence gap.

**Limitation:** No claim is made that privileged accounts actually lack MFA or that unauthorized access occurred.

#### Assessment Area C — Logging and Recovery

**Questionnaire references:** Q-21, Q-24, Q-26, Q-27

**Synthetic vendor response:** Partially. Logging and recovery procedures are documented, but the fictional evidence package contains no completed recovery exercise report or sufficiently detailed logging-coverage assessment.

**Synthetic evidence:** EVD-004 — Fictional logging and recovery procedure.

**Evidence description:** The procedure describes security logging and recovery responsibilities. It does not establish the coverage of all relevant systems, demonstrate the effectiveness of monitoring, or show that recovery objectives were achieved in a completed test.

**Assessment procedure:** Compare the documented procedures with the evidence needed to demonstrate coverage and operating performance.

**Result:** Documentation is available, but operating effectiveness and completeness remain unverified.

**Conclusion:** Evidence gap requiring follow-up. The absence of test evidence does not, by itself, establish an operating failure.

### 3.3 VND-001 Assessment Summary

| Area                      | Conclusion   | Follow-Up                                                            |
| ------------------------- | ------------ | -------------------------------------------------------------------- |
| Shared responsibilities   | Evidence gap | Map material responsibilities to accountable owners                  |
| Privileged access and MFA | Evidence gap | Obtain scoped configuration evidence and validate account coverage   |
| Logging and recovery      | Evidence gap | Obtain logging-coverage evidence and a relevant recovery test record |

**Overall assessment conclusion:** The selected synthetic documentation does not provide sufficient evidence to validate all material access, logging, and recovery safeguards within the defined scope.

**Risk implication:** Maintain the preliminary high inherent-risk tier. Evaluate residual risk only after relevant safeguards and remaining exposure have been assessed.

**Recommended next step:** Complete the evidence requests and escalate material unresolved questions through the vendor oversight process.

---

## 4. VND-002 — SignalBridge Support

### 4.1 Assessment Profile

| Field                          | Details                                                                            |
| ------------------------------ | ---------------------------------------------------------------------------------- |
| Vendor ID                      | VND-002                                                                            |
| Service                        | Customer support platform                                                          |
| Preliminary inherent-risk tier | Moderate                                                                           |
| Assessment type                | Initial due diligence                                                              |
| Evidence type                  | Synthetic data-flow, permission, and retention records                             |
| Assessment status              | Simulated assessment completed for selected topics; other topics remain unassessed |

### 4.2 Synthetic Responses and Evidence

#### Assessment Area A — Customer Data Access

**Questionnaire references:** Q-12, Q-17

**Synthetic vendor response:** Yes. Customer support personnel can access information required to manage support cases.

**Synthetic evidence:** EVD-005 — Fictional support-platform data-flow summary.

**Evidence description:** The simulated data-flow summary identifies customer account information and support-case content as information available to the support platform. The scenario includes a fictional example of a support case displaying more customer record information than is necessary for basic case routing.

**Assessment procedure:** Compare the described data exposure with the minimum information needed for the stated support function.

**Result:** The synthetic example indicates that the configured support workflow may expose unnecessary customer information.

**Conclusion:** Design weakness in the fictional support workflow.

**Limitation:** The example does not establish that a real customer was exposed or that unauthorized access occurred.

#### Assessment Area B — Role Permissions and Access Review

**Questionnaire references:** Q-08, Q-09, Q-11

**Synthetic vendor response:** Partially. Role-based permissions are available, but the supplied simulated records do not establish that access reviews consistently cover all support roles.

**Synthetic evidence:** EVD-006 — Fictional role-permission matrix and access-review summary.

**Evidence description:** The fictional role matrix includes a support role with broader record visibility than the minimum required for basic support case handling. The simulated access-review summary does not demonstrate that the broader permission was reviewed and justified during the relevant review period.

**Assessment procedure:** Compare the role permissions with the stated support responsibilities and examine whether the documented review addresses the identified permission.

**Result:** The example supports a least-privilege concern. The evidence does not establish that every support user has excessive access or that a security incident occurred.

**Conclusion:** Design weakness requiring corrective action in the fictional scenario.

#### Assessment Area C — Retention and Subprocessors

**Questionnaire references:** Q-16, Q-18

**Synthetic vendor response:** Yes. Retention and deletion practices are documented, and external service providers are managed through a vendor process.

**Synthetic evidence:** EVD-007 — Fictional retention policy and subprocessor overview.

**Evidence description:** The simulated policy describes retention and deletion responsibilities. The supplied subprocessor overview does not establish whether every external party handling Northstar's data has been evaluated against the relevant contractual and security requirements.

**Assessment procedure:** Compare the documentation with the expected inventory and oversight requirements.

**Result:** Retention requirements are documented, but the available evidence does not demonstrate complete subprocessor oversight for the Northstar service.

**Conclusion:** Evidence gap.

**Limitation:** The absence of complete oversight evidence does not establish that an unapproved subprocessor actually received customer data.

### 4.3 VND-002 Assessment Summary

| Area                        | Conclusion                               | Follow-Up                                                                   |
| --------------------------- | ---------------------------------------- | --------------------------------------------------------------------------- |
| Customer data exposure      | Design weakness in the synthetic example | Minimize the customer information displayed in support workflows            |
| Role permissions            | Design weakness in the synthetic example | Restrict broad permissions and validate access assignments                  |
| Retention and subprocessors | Evidence gap                             | Reconcile the subprocessor inventory with applicable oversight requirements |

**Overall assessment conclusion:** The synthetic evidence identifies potential overexposure of customer information and an access-design weakness requiring corrective action. Subprocessor oversight remains insufficiently evidenced.

**Risk implication:** Reassess the preliminary moderate inherent-risk tier if the confirmed scope of data access or operational dependency materially differs from the original assumptions. Evaluate residual risk after reviewing safeguards and remediation evidence.

**Recommended next step:** Correct the fictional support workflow and permission model, then define the evidence required to validate the changes.

---

## 5. VND-003 — MetricForge Analytics

### 5.1 Assessment Profile

| Field                          | Details                                                                            |
| ------------------------------ | ---------------------------------------------------------------------------------- |
| Vendor ID                      | VND-003                                                                            |
| Service                        | Product analytics                                                                  |
| Preliminary inherent-risk tier | Moderate                                                                           |
| Assessment type                | Initial due diligence                                                              |
| Evidence type                  | Synthetic event schema and integration records                                     |
| Assessment status              | Simulated assessment completed for selected topics; other topics remain unassessed |

### 5.2 Synthetic Responses and Evidence

#### Assessment Area A — Analytics Data Minimization

**Questionnaire references:** Q-12, Q-13, Q-17

**Synthetic vendor response:** Partially. The service is intended to collect product usage information, but the fictional integration specification has not fully defined which event attributes are necessary.

**Synthetic evidence:** EVD-009 — Fictional analytics event schema.

**Evidence description:** The simulated event schema includes a user identifier, event name, timestamp, and a free-text field populated from an application record. The scenario's stated analytics objective does not require the free-text field to contain customer business information.

**Assessment procedure:** Compare collected event attributes with the stated analytics purpose and identify unnecessary or potentially sensitive data.

**Result:** The free-text field could transmit information beyond the intended analytics purpose.

**Conclusion:** Design weakness in the fictional integration.

**Limitation:** The synthetic schema demonstrates a plausible exposure path; it does not establish that real customer information was transmitted to a real service.

#### Assessment Area B — Integration Permissions

**Questionnaire references:** Q-06, Q-07, Q-08

**Synthetic vendor response:** Yes. The integration uses an application credential, and access is intended to be restricted to analytics functions.

**Synthetic evidence:** EVD-010 — Fictional integration-permission specification.

**Evidence description:** The fictional specification lists the permissions assigned to the analytics integration but does not include evidence demonstrating that those permissions were validated against the minimum required scope.

**Assessment procedure:** Compare the documented permissions with the stated analytics function and identify permissions that may exceed the service's requirements.

**Result:** The available specification is insufficient to establish whether the integration follows least-privilege principles.

**Conclusion:** Evidence gap.

**Limitation:** No claim is made that the integration credential has been compromised or that excessive permissions are definitively present.

#### Assessment Area C — Retention and External Sharing

**Questionnaire references:** Q-16, Q-18

**Synthetic vendor response:** Partially. Retention and deletion arrangements are documented, but the supplied fictional evidence does not establish how all analytics event data is handled across the full retention lifecycle.

**Synthetic evidence:** EVD-011 — Fictional analytics retention summary.

**Evidence description:** The simulated summary identifies a proposed retention period for primary analytics records but does not establish the handling of exported data, backups, or all downstream recipients.

**Assessment procedure:** Compare the retention summary with the information lifecycle and external-sharing requirements for the service.

**Result:** The available evidence does not establish complete coverage of the analytics data lifecycle.

**Conclusion:** Evidence gap.

**Limitation:** No conclusion is made that the vendor retained information beyond an actual contractual or policy requirement.

### 5.3 VND-003 Assessment Summary

| Area                           | Conclusion                               | Follow-Up                                                                           |
| ------------------------------ | ---------------------------------------- | ----------------------------------------------------------------------------------- |
| Analytics data minimization    | Design weakness in the synthetic example | Remove unnecessary free-text fields and define an approved event schema             |
| Integration permissions        | Evidence gap                             | Validate permissions against the minimum required scope                             |
| Retention and external sharing | Evidence gap                             | Document retention across primary data, exports, backups, and downstream recipients |

**Overall assessment conclusion:** The synthetic event schema demonstrates a plausible data-minimization weakness. Integration permissions and complete data lifecycle coverage remain insufficiently evidenced.

**Risk implication:** Review the data sensitivity score if the integration can transmit customer content. Reassess the remaining factors if evidence changes the assumed business dependency or access scope.

**Recommended next step:** Correct the fictional event schema, validate integration permissions, and document the evidence needed to support closure.

---

## 6. Consolidated Assessment Results

| Vendor ID | Preliminary Inherent Risk | Selected Assessment Results                                                                   | Main Follow-Up                                                        |
| --------- | ------------------------- | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| VND-001   | High                      | Evidence gaps concerning responsibility allocation, privileged access, logging, and recovery  | Obtain and evaluate additional evidence                               |
| VND-002   | Moderate                  | Synthetic design weaknesses in data exposure and role permissions; subprocessor evidence gap  | Correct the workflow and permission design; complete oversight review |
| VND-003   | Moderate                  | Synthetic data-minimization weakness; evidence gaps concerning permissions and data lifecycle | Minimize event data and validate integration controls                 |

## 7. Interpretation

The results illustrate three important assessment distinctions:

1. **A documented process is not proof of effective operation.** Policies and procedures must be evaluated against the evidence required for the assessment objective.
2. **An evidence gap is not automatically a control failure.** It means that the available information does not support a reliable conclusion.
3. **A design weakness should be tied to a specific risk.** The assessment should explain what is deficient, why it matters, and what corrective action would address it.

The results above apply only to the fictional evidence described in this document.

## 8. Simulation Disclaimer

All vendor responses, evidence descriptions, observations, and conclusions in this document are synthetic. They are intended to demonstrate a structured GRC assessment process and must not be represented as real vendor disclosures, actual security incidents, or independently verified findings.
