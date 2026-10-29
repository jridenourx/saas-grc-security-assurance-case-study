# SaaS Security Compliance, Customer Assurance & Third-Party Risk

## Project Overview

This repository documents a simulated Governance, Risk, and Compliance (GRC) program for Northstar Cloud Solutions, a fictional business-to-business software-as-a-service (SaaS) company hosted on Amazon Web Services (AWS).

The case study demonstrates how a GRC practitioner can structure third-party risk assessments, manage customer security questionnaires, evaluate SOC 2 readiness, document control testing, and connect risks with evidence and remediation activities.

The project emphasizes risk-based decision-making, evidence traceability, consistent documentation, and transparent assessment limitations.

## Business Scenario

Northstar Cloud Solutions is a fictional SaaS company preparing to strengthen its security and compliance program in response to customer assurance requirements.

The company relies on external service providers, processes customer business data, and operates cloud-hosted systems. Its security processes require more consistent evidence collection, vendor oversight, control documentation, and remediation tracking.

This case study develops a structured approach to those challenges using fictional company information and synthetic assessment artifacts.

## Project Objectives

* Establish a risk-based third-party risk management process.
* Develop a repeatable approach to customer security questionnaires and evidence-backed responses.
* Assess readiness against selected SOC 2 Trust Services Criteria.
* Document control objectives, evidence requests, planned testing procedures, and preliminary assessment results.
* Evaluate selected technical controls related to identity and access management, multifactor authentication, and security logging.
* Connect risks, controls, evidence, findings, and remediation activities.
* Produce management-oriented reporting and professional portfolio documentation.
* Demonstrate the ability to document assessment methodology, evaluate evidence limitations, and communicate security risks.

## Project Workstreams

| Workstream                         | Focus                                                                                                                 | Repository Location                                                 |
| ---------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Third-Party Risk Management        | Vendor inventory, inherent risk scoring, due diligence, evidence review, risk tracking, and remediation               | `01-third-party-risk/`                                              |
| Customer Security Assurance        | Security questionnaires, response library, evidence mapping, and review and approval procedures                       | `02-customer-assurance/`                                            |
| SOC 2 Readiness                    | Scope definition, control matrix, evidence requests, testing procedures, assessment results, and remediation tracking | `03-soc2-readiness/`                                                |
| Technical Control Validation       | Planned and simulated validation of selected IAM, MFA, and security logging controls                                  | Planned workstream: `04-technical-validation/`                      |
| Management Reporting and Portfolio | Consolidated risk reporting, management summary, final case study, and lessons learned                                | Planned workstreams: `05-management-reporting/` and `06-portfolio/` |

The first three workstreams contain the principal assessment documentation. Technical validation and consolidated portfolio reporting are separate planned deliverables and should not be considered complete until their corresponding artifacts have been created and reviewed.

## Repository Navigation

### Project Documentation

The `docs/` directory contains the foundational documents for the case study.

| File                            | Purpose                                                                                                                                  |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| `docs/project-charter.md`       | Defines the project purpose, objectives, scope, and intended deliverables.                                                               |
| `docs/company-profile.md`       | Describes the fictional company, operating environment, and business context.                                                            |
| `docs/scope-and-assumptions.md` | Documents scope boundaries, assumptions, exclusions, and limitations.                                                                    |
| `docs/methodology.md`           | Defines risk scoring, evidence evaluation, assessment conclusions, finding severity, remediation management, and identifier conventions. |

### Third-Party Risk Management

The `01-third-party-risk/` directory contains the vendor risk management workstream.

Key artifacts include:

* Vendor inventory and service descriptions.
* Vendor due diligence questionnaire.
* Vendor risk assessment matrix.
* Synthetic vendor assessment records.
* Vendor assessment workpapers.
* Evidence register.
* Risk register.
* Findings and remediation tracker.
* Vendor lifecycle procedure.
* Vendor risk summary.

### Customer Security Assurance

The `02-customer-assurance/` directory contains the customer questionnaire workstream.

Key artifacts include:

* Customer security questionnaire.
* Security questionnaire response library.
* Sample completed customer questionnaire.
* Questionnaire review procedure.

These artifacts demonstrate how customer security responses can be standardized, reviewed, and linked to supporting evidence while distinguishing verified information from assumptions and evidence gaps.

### SOC 2 Readiness

The `03-soc2-readiness/` directory contains the SOC 2 readiness workstream.

Key artifacts include:

* Readiness scope.
* Control matrix.
* Evidence request register.
* Control testing plan.
* Synthetic evidence samples.
* Assessment results.
* Findings register.
* Remediation tracker.

The workstream focuses on the Security Trust Services Criterion and is intended to demonstrate readiness assessment and evidence management. It is not an independent SOC 2 examination.

### Planned Technical Validation

The planned `04-technical-validation/` directory will document selected technical control validation activities.

The intended focus includes:

* Identity and access management.
* Least privilege and privileged access.
* Multifactor authentication.
* Security logging and monitoring.
* Evidence review and test limitations.
* Links between technical observations, controls, risks, and remediation actions.

Any technical evidence created for this workstream will be synthetic and clearly labeled. No real AWS production environment or customer system is represented as having been tested.

### Planned Management Reporting and Portfolio

The planned `05-management-reporting/` directory will provide a consolidated view of the case study, including risk priorities, evidence gaps, assessment status, findings, and remediation.

The planned `06-portfolio/` directory will contain a final case study summary, methodology overview, and lessons learned.

These directories should be treated as planned deliverables until their contents are added.

### Framework References

The `references/` directory contains the framework reference register and supporting references used to inform the assessment methodology.

Frameworks and guidance are applied selectively according to the scope and relevance of each workstream.

## Methodology

The case study uses documented assessment criteria, synthetic evidence, consistent identifiers, and traceable findings.

The assessment process distinguishes among:

* Preliminary risk estimates.
* Evidence requests and evidence gaps.
* Planned testing procedures.
* Preliminary observations.
* Supported assessment conclusions.
* Findings requiring remediation.
* Risks requiring acceptance or further review.

Risk ratings and conclusions should be supported by documented rationale and relevant evidence. Missing evidence is not automatically proof of a control failure, and an unverified control must not be described as effective.

Cross-workstream reporting must identify the workstream associated with each record so that similar identifiers in different registers are not confused.

## Scope and Limitations

This is an independent, simulated portfolio case study. Northstar Cloud Solutions, its vendors, customers, users, configurations, records, and evidence are fictional or synthetic.

The project does not represent:

* A real client engagement.
* A production-system assessment.
* An independent audit.
* A completed SOC 2 examination.
* A SOC 2 report or certification.
* Verified security assurance for any real vendor.

Conclusions apply only to the defined fictional scenario and the evidence created for the exercise. Synthetic examples demonstrate assessment methods; they do not establish that real-world controls operate effectively.

## Simulation Disclaimer

All company names, vendors, customers, records, configurations, evidence, assessment results, and findings created for this project are fictional or synthetic unless explicitly identified otherwise.

This project demonstrates a learning exercise in GRC assessment and documentation. It does not establish professional audit experience, represent work performed for a real organization, or certify that any real organization meets a compliance framework.

