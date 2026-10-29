# SaaS GRC and Security Assurance Case Study

## Project Overview

This repository documents a simulated Governance, Risk, and Compliance (GRC) program for Northstar Cloud Solutions, a fictional business-to-business software-as-a-service (SaaS) company hosted on Amazon Web Services (AWS).

The case study demonstrates how a GRC practitioner can structure third-party risk assessments, manage customer security questionnaires, evaluate SOC 2 readiness, plan technical control validation, track findings and remediation, and communicate risk through management reporting.

The project emphasizes risk-based decision-making, evidence traceability, consistent documentation, and transparent assessment limitations.

**Project status:** Portfolio case study with documented assessment methodology, preliminary simulated results, and planned technical testing procedures.

**Evidence classification:** Fictional scenario information and synthetic evidence.

## Business Scenario

Northstar Cloud Solutions is a fictional SaaS company preparing to strengthen its security and compliance program in response to customer assurance requirements.

The company relies on external service providers, processes customer business data, and operates cloud-hosted systems. Its security processes require consistent evidence collection, vendor oversight, control documentation, and remediation tracking.

This case study develops a structured approach to those challenges using fictional company information and synthetic assessment artifacts.

### Vendors in Scope

| Vendor                  | Service                   | Preliminary Inherent Risk Tier |
| ----------------------- | ------------------------- | ------------------------------ |
| Northstar Cloud Hosting | Cloud infrastructure      | High                           |
| SignalBridge Support    | Customer support platform | Moderate                       |
| MetricForge Analytics   | Product analytics         | Moderate                       |

The ratings use the project's documented weighted inherent-risk methodology. They are scenario-based estimates and are not independently verified assessments of real vendors.

## Project Objectives

* Establish a risk-based third-party risk management process.
* Develop a repeatable approach to customer security questionnaires and evidence-backed responses.
* Assess readiness against selected SOC 2 security control areas.
* Document control objectives, evidence requests, planned testing procedures, and preliminary assessment statuses.
* Define technical validation procedures for selected identity and access management, multifactor authentication, and logging controls.
* Connect risks, controls, evidence, findings, and remediation activities.
* Produce management-oriented reporting and portfolio documentation.
* Demonstrate the ability to document assessment methodology, evaluate evidence limitations, and communicate security risks.

## Repository Navigation

### 1. Project Documentation — `docs/`

| File                            | Purpose                                                                                                                                  |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| `docs/project-charter.md`       | Defines the project purpose, objectives, scope, and intended deliverables.                                                               |
| `docs/company-profile.md`       | Describes the fictional company, operating environment, and business context.                                                            |
| `docs/scope-and-assumptions.md` | Documents scope boundaries, assumptions, exclusions, and limitations.                                                                    |
| `docs/methodology.md`           | Defines risk scoring, evidence evaluation, assessment conclusions, finding severity, remediation management, and identifier conventions. |

### 2. Third-Party Risk Management — `01-third-party-risk/`

This workstream evaluates three fictional vendors using a consistent inherent-risk methodology and documents due diligence, evidence follow-up, findings, and remediation expectations.

Key artifacts:

* `01-third-party-risk/vendor-inventory.md`
* `01-third-party-risk/vendor-due-diligence-questionnaire.md`
* `01-third-party-risk/vendor-risk-assessment-matrix.md`
* `01-third-party-risk/synthetic-vendor-assessments.md`
* `01-third-party-risk/vendor-assessment-workpapers.md`
* `01-third-party-risk/evidence-register.md`
* `01-third-party-risk/risk-register.md`
* `01-third-party-risk/findings-remediation-tracker.md`
* `01-third-party-risk/vendor-lifecycle-procedure.md`
* `01-third-party-risk/vendor-risk-summary.md`

The simulated vendor assessment records three documented findings: two associated with SignalBridge Support and one associated with MetricForge Analytics. Evidence follow-up items are tracked separately where the available information does not establish a control deficiency.

### 3. Customer Security Assurance — `02-customer-assurance/`

This workstream demonstrates a repeatable approach to receiving, reviewing, and responding to customer security questionnaires.

Key artifacts:

* `02-customer-assurance/customer-security-questionnaire.md`
* `02-customer-assurance/security-questionnaire-response-library.md`
* `02-customer-assurance/sample-customer-questionnaire.md`
* `02-customer-assurance/questionnaire-review-procedure.md`

These documents demonstrate how responses can be standardized, reviewed, and linked to supporting evidence while distinguishing verified information from assumptions and evidence gaps.

### 4. SOC 2 Readiness — `03-soc2-readiness/`

This workstream organizes a simulated readiness assessment around 15 security control areas.

Key artifacts:

* `03-soc2-readiness/readiness-scope.md`
* `03-soc2-readiness/control-matrix.md`
* `03-soc2-readiness/evidence-request-register.md`
* `03-soc2-readiness/control-testing-plan.md`
* `03-soc2-readiness/evidence-samples.md`
* `03-soc2-readiness/assessment-results.md`
* `03-soc2-readiness/findings-register.md`
* `03-soc2-readiness/remediation-tracker.md`

**Current assessment status:** Six controls are marked In Progress because preliminary synthetic evidence samples have been drafted. Nine controls remain Not Tested.

In Progress does not mean a control has passed testing. The SOC 2 findings register currently contains no confirmed findings based on the preliminary samples, and the SOC 2 remediation tracker has no documented actions.

These statuses describe the state of this simulated exercise. They do not establish that the fictional environment has no deficiencies or that it would pass a SOC 2 examination.

### 5. Technical Control Validation — `04-technical-validation/`

This workstream defines planned procedures for examining selected technical controls.

Key artifact:

* `04-technical-validation/technical-control-validation-plan.md`

The plan covers:

* User access provisioning and removal.
* Privileged access and least privilege.
* Multifactor authentication.
* Security logging and monitoring.
* Log protection and retention.

Each planned test includes an objective, procedures, evidence requirements, expected results, and potential exceptions.

**Execution status:** The repository contains a validation plan. It does not claim that production systems were tested or that the planned procedures have been completed.

### 6. Management Reporting — `05-management-reporting/`

This workstream consolidates risk and readiness information for a management audience.

Key artifact:

* `05-management-reporting/consolidated-grc-management-report.md`

The report summarizes vendor risk ratings, documented vendor findings, evidence follow-up items, SOC 2 assessment statuses, recommended priorities, and reporting limitations.

Workstream prefixes are used where necessary to distinguish records that share similar identifier patterns across separate registers.

### 7. Portfolio Materials — `06-portfolio/`

This workstream presents the project in a format suitable for portfolio review and interview preparation.

| File                                  | Purpose                                                                                           |
| ------------------------------------- | ------------------------------------------------------------------------------------------------- |
| `06-portfolio/case-study.md`          | Summarizes the business scenario, methodology, workstreams, findings, and limitations.            |
| `06-portfolio/lessons-learned.md`     | Documents lessons about risk scoring, evidence quality, traceability, remediation, and reporting. |
| `06-portfolio/project-walkthrough.md` | Provides a guided repository walkthrough and interview talking points.                            |

These documents are designed to help recruiters and hiring managers understand the project without having to read every workpaper.

### 8. Framework References — `references/`

* `references/framework-reference-register.md`

This register documents the framework references used to inform the simulated assessment methodology.

Frameworks and guidance are applied selectively according to the scope and relevance of each workstream.

## Methodology and Evidence Governance

The project uses documented assessment criteria, synthetic evidence, consistent identifiers, and traceable findings.

The assessment process distinguishes among:

* Preliminary inherent-risk estimates.
* Evidence requests and evidence gaps.
* Planned testing procedures.
* Preliminary observations.
* Supported assessment conclusions.
* Findings requiring remediation.
* Risks requiring acceptance or further review.

Key principles include:

1. **Use documented scoring criteria.** Risk ratings should be based on defined factors and a consistent methodology.
2. **Distinguish inherent risk from control effectiveness.** A high inherent-risk rating does not automatically establish a control failure.
3. **Treat evidence gaps carefully.** Missing evidence is not automatically proof that a control failed.
4. **Preserve traceability.** Risks, controls, evidence, findings, and remediation actions should be linked where applicable.
5. **Represent testing status accurately.** Planned procedures must not be described as completed tests.
6. **Require support for conclusions.** Assessment conclusions should be consistent with the procedures performed and the evidence available.
7. **Document limitations.** Unverified information and unresolved questions should remain visible in reporting.

## Scope and Limitations

This is a simulated portfolio case study. Northstar Cloud Solutions, its vendors, customers, users, configurations, records, and evidence are fictional or synthetic.

The project does not represent:

* A real client engagement.
* A production-system assessment.
* An independent audit.
* Completed production technical testing.
* A completed SOC 2 examination.
* A SOC 2 report or certification.
* Verified security assurance for any real vendor.

Conclusions apply only to the defined fictional scenario and the evidence created for the exercise. Synthetic examples demonstrate assessment methods; they do not establish that real-world controls operate effectively.

## Skills Demonstrated

This project is intended to demonstrate practical exposure to:

* Third-party risk management.
* Inherent-risk scoring and risk classification.
* Evidence collection and tracking.
* Security questionnaire review.
* SOC 2 readiness documentation.
* Control mapping and test planning.
* Findings and remediation tracking.
* Management reporting.
* Cross-workstream traceability.
* Procedure and process documentation.
* Communicating assessment limitations and security risks.

## Recommended Starting Points

**For recruiters and hiring managers:** Start with `06-portfolio/case-study.md`.

**For GRC and IT audit reviewers:** Review `01-third-party-risk/vendor-risk-assessment-matrix.md`, `03-soc2-readiness/control-matrix.md`, and `03-soc2-readiness/assessment-results.md`.

**For technical control validation:** Review `04-technical-validation/technical-control-validation-plan.md`.

**For management reporting:** Review `05-management-reporting/consolidated-grc-management-report.md`.

**For interview preparation:** Review `06-portfolio/project-walkthrough.md`.

## Simulation Disclaimer

All company names, vendors, customers, records, configurations, evidence, assessment results, and findings created for this project are fictional or synthetic unless explicitly identified otherwise.

This project demonstrates a learning exercise in GRC assessment and documentation. It does not establish professional audit experience, represent work performed for a real organization, or certify that any real organization meets a compliance framework.

