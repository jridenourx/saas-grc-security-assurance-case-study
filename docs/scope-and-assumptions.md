# Scope and Assumptions

## 1. Purpose

This document defines the boundaries, assumptions, and limitations for the simulated GRC case study involving Northstar Cloud Solutions.

The purpose is to establish a consistent basis for third-party risk assessments, customer security assurance, SOC 2 readiness activities, and technical control validation.

## 2. Organizational Scope

The assessment covers the fictional Northstar Cloud Solutions organization and its assumed SaaS service.

Relevant business functions include:

* Security and IT
* Governance, Risk, and Compliance (GRC)
* Engineering
* Legal and Privacy
* Procurement
* Customer Success and Sales
* Business owners and executive management

These functions represent proposed roles within the scenario. They do not describe an actual organization.

## 3. System and Technology Scope

The simulated environment includes a business-to-business SaaS application hosted on Amazon Web Services (AWS).

The assessment will consider the following areas:

* Identity and access management
* Least-privilege access
* Multifactor authentication
* Cloud activity logging and monitoring
* Security evidence collection and retention
* Third-party service dependencies
* Customer data handling
* Security governance and remediation tracking

No production environment is assumed to exist. Technical findings must be based on documented synthetic evidence or evidence collected from an explicitly identified sandbox environment.

## 4. Data Scope

The scenario includes the following data categories:

| Data Category                | Assessment Considerations                                      |
| ---------------------------- | -------------------------------------------------------------- |
| Customer business records    | Confidentiality, integrity, access restrictions, and retention |
| Customer account information | Appropriate access, protection, and handling                   |
| Application activity logs    | Coverage, retention, monitoring, and access restrictions       |
| Internal operational records | Access restrictions, retention, and protection                 |

Detailed data flows, processing purposes, and retention requirements will be defined only where necessary to support a particular assessment.

The presence of a data category does not establish that a specific control is implemented or operating effectively.

## 5. Third-Party Scope

The vendor risk assessment will cover three fictional service providers:

| Vendor ID | Vendor                  | Service                   |
| --------- | ----------------------- | ------------------------- |
| VND-001   | Northstar Cloud Hosting | Cloud infrastructure      |
| VND-002   | SignalBridge Support    | Customer support platform |
| VND-003   | MetricForge Analytics   | Product analytics         |

The assessments will consider business criticality, data sensitivity, access, service dependency, due diligence evidence, and identified risk treatment needs.

Vendor names and services are fictional. No real vendor security posture is being evaluated.

## 6. SOC 2 Readiness Scope

The readiness workstream will focus primarily on the Security category of the AICPA Trust Services Criteria.

Additional Trust Services Criteria will be considered only if the scenario and documented assessment objectives justify their inclusion.

Activities may include:

* Defining the proposed assessment boundary.
* Mapping selected criteria to internal controls.
* Identifying control owners and evidence requirements.
* Developing test procedures.
* Evaluating synthetic evidence.
* Documenting readiness gaps and remediation actions.

This work is a readiness exercise, not a SOC 2 examination. It does not produce a SOC 2 report or establish compliance.

## 7. Customer Assurance Scope

The customer assurance workstream will develop a repeatable process for handling security questionnaires.

It will include:

* A structured questionnaire.
* A reusable response library.
* Evidence references for supported answers.
* Review and approval requirements.
* A process for handling unknown, incomplete, or unsupported responses.

Responses must not claim that a control exists or operates effectively unless the simulated evidence supports that statement.

## 8. Technical Validation Scope

Technical validation will focus on three areas:

1. Identity and access management, including least privilege.
2. Multifactor authentication.
3. Cloud activity logging and monitoring.

Each assessment will define the expected control behavior, evidence examined, procedures performed, results, limitations, and any resulting findings.

Synthetic records must be clearly labeled. They must not be presented as genuine AWS configuration exports, production logs, or results from a real security test.

## 9. Out of Scope

The following activities are excluded:

* Testing or accessing real third-party systems.
* Testing a real production environment.
* Penetration testing or vulnerability exploitation.
* Making legal determinations about contractual or regulatory compliance.
* Conducting an independent SOC 2 examination.
* Issuing a SOC 2 report or certification.
* Claiming that a real organization complies with a security framework.
* Building a production-ready GRC software platform.

## 10. Assessment Assumptions

The case study uses the following assumptions:

* Northstar Cloud Solutions is a fictional SaaS provider.
* All three vendors are fictional.
* Company records, users, configurations, evidence, and assessment results are synthetic unless explicitly identified otherwise.
* Proposed organizational roles and responsibilities are scenario assumptions.
* Risk-scoring thresholds are internal design choices for this exercise, not universal requirements.
* Assessment conclusions are limited to the stated criteria and available evidence.
* Missing evidence does not automatically prove that a control is absent or ineffective.
* A documented policy does not, by itself, prove that a control operates effectively.

## 11. Evidence and Conclusion Standards

Assessment work products will distinguish among the following conditions:

**Evidence gap:** Available information is insufficient to support a conclusion.

**Design weakness:** The documented control or process does not adequately address the identified risk.

**Operating failure:** Evidence indicates that a control did not function as intended during the assessed period or under the tested conditions.

**No issue identified within scope:** The evidence and procedures performed did not identify a relevant issue within the defined assessment boundaries. This does not guarantee that no other issue exists.

These labels will be applied based on documented assessment criteria and evidence rather than assumptions.

## 12. Simulation Disclaimer

This document defines a fictional learning exercise. It does not represent a real client engagement, independent audit, vendor assessment, compliance certification, or professional opinion concerning an actual organization.
