# SaaS GRC and Security Assurance Case Study

## Project Overview

**Project type:** Governance, Risk, and Compliance (GRC), Third-Party Risk Management (TPRM), Customer Security Assurance, and SOC 2 Readiness
**Organization:** Northstar Cloud Solutions (fictional)
**Environment:** Fictional B2B SaaS company hosted on AWS
**Project status:** Simulated assessment and readiness exercise
**Evidence classification:** Synthetic evidence and illustrative records

## Executive Summary

This project simulates a GRC and security assurance engagement for Northstar Cloud Solutions, a fictional business-to-business SaaS provider hosted on Amazon Web Services (AWS).

The project demonstrates how security and compliance activities can be organized into a consistent process covering third-party risk, customer security questionnaires, SOC 2 readiness, technical control validation planning, remediation tracking, and management reporting.

Rather than treating each activity as an isolated task, the project connects risk identification, control expectations, evidence requests, assessment status, and remediation priorities across multiple workstreams.

The case study is designed to demonstrate practical documentation, risk analysis, evidence management, and reporting skills relevant to entry-level GRC Analyst, IT Auditor, IT Compliance Analyst, and Third-Party Risk Management positions.

**Important limitation:** This is a simulated portfolio exercise. The company, vendors, records, and evidence are fictional or synthetic. The project is not a real independent audit, penetration test, SOC 2 examination, or certification.

## Business Scenario

Northstar Cloud Solutions provides a fictional SaaS application to business customers. Its operating model depends on cloud infrastructure and third-party services that may affect customer data, system access, availability, and security assurance.

The simulated assessment focuses on three vendors:

| Vendor                  | Service                   | Principal Risk Considerations                                                   | Inherent Risk Tier |
| ----------------------- | ------------------------- | ------------------------------------------------------------------------------- | ------------------ |
| Northstar Cloud Hosting | Cloud infrastructure      | Infrastructure dependency, privileged access, logging, and availability         | High               |
| SignalBridge Support    | Customer support platform | Customer information exposure, access permissions, retention, and subprocessors | Moderate           |
| MetricForge Analytics   | Product analytics         | Data minimization, event data, retention, and external sharing                  | Moderate           |

The vendor scores use the project's documented weighted inherent-risk methodology. These are scenario-based risk ratings, not independently verified assessments of actual companies.

## Project Objectives

The project has six primary objectives:

1. Establish a structured third-party risk management process.
2. Assess vendor risk using consistent scoring criteria and documented rationale.
3. Create a repeatable approach to customer security questionnaires and response review.
4. Organize a SOC 2 readiness assessment around control expectations, evidence requests, and assessment status.
5. Develop a technical control validation plan with defined procedures and expected results.
6. Consolidate risk and readiness information into management-oriented reporting.

## Workstream 1: Third-Party Risk Management

### Approach

The vendor risk workstream establishes a vendor inventory, evaluates inherent risk, tracks evidence, documents identified issues, and defines lifecycle procedures.

The inherent-risk scoring methodology uses four factors:

* Data sensitivity: 30%
* System access: 25%
* Business criticality: 25%
* Dependency and concentration: 20%

Each factor is scored on a five-point scale. The weighted results are assigned to documented risk tiers.

### Results

| Vendor                  | Weighted Score | Risk Tier |
| ----------------------- | -------------: | --------- |
| Northstar Cloud Hosting |           4.75 | High      |
| SignalBridge Support    |           3.30 | Moderate  |
| MetricForge Analytics   |           2.55 | Moderate  |

The assessment identifies three documented vendor findings:

* **FND-001 — Excessive customer information exposed in a support workflow:** A simulated design weakness associated with SignalBridge Support.
* **FND-002 — Support-role permissions exceed documented business need:** A simulated least-privilege design weakness associated with SignalBridge Support.
* **FND-003 — Analytics event schema permits unnecessary free-text data:** A simulated data-minimization design weakness associated with MetricForge Analytics.

These findings are recorded as open within the scenario. The repository also tracks evidence follow-up items separately so that missing documentation is not automatically treated as proof that a control failed.

### Key Deliverables

* Vendor inventory
* Vendor risk assessment matrix
* Vendor risk summary
* Evidence register
* Risk register
* Findings and remediation tracker
* Synthetic vendor assessment records
* Vendor lifecycle procedure

## Workstream 2: Customer Security Assurance

### Approach

The customer assurance workstream simulates a repeatable process for receiving, reviewing, and responding to customer security questionnaires.

The process is intended to support accurate, consistent responses while avoiding unsupported security claims.

Key activities include:

* Reviewing customer questions and identifying the relevant control or policy.
* Mapping questions to approved response language.
* Identifying evidence needed to substantiate responses.
* Flagging questions that require additional review or confirmation.
* Maintaining reviewer oversight before responses are issued.

### Key Deliverables

* Customer security questionnaire
* Security questionnaire response library
* Sample customer questionnaire
* Questionnaire review procedure

### Business Value

A structured response process can reduce inconsistent answers, improve reviewability, and help an organization identify evidence gaps before making security representations to customers.

The portfolio materials demonstrate the proposed process; they do not establish that real customer questionnaires were submitted or approved.

## Workstream 3: SOC 2 Readiness

### Approach

The SOC 2 readiness workstream organizes a simulated security-control baseline, evidence requests, testing procedures, preliminary evidence samples, assessment statuses, and finding records.

The workstream covers 15 control areas:

1. Security governance and policy management
2. Risk assessment and treatment
3. User access provisioning and removal
4. Privileged access and least privilege
5. Multifactor authentication
6. Security logging and monitoring
7. Protection and retention of security logs
8. Incident response
9. Customer incident notification
10. Data handling, retention, and deletion
11. Vulnerability management
12. Change management
13. Secure development and deployment access
14. Third-party risk management
15. Customer security assurance and control evidence

An evidence request register assigns identifiers to the expected documentation or illustrative records for each control.

### Assessment Status

The project records six controls as In Progress because preliminary synthetic evidence samples have been drafted for those areas. The other nine controls are marked Not Tested.

The In Progress status does not mean the controls have passed testing. It indicates that the simulated assessment materials have been developed but the full assessment process has not been completed.

The SOC 2 findings register currently documents no confirmed SOC 2 findings, and the SOC 2 remediation tracker contains no documented actions. This should not be interpreted as evidence that all controls are effective.

### Key Deliverables

* Readiness scope
* Control matrix
* Evidence request register
* Control testing plan
* Synthetic evidence samples
* Assessment results
* Findings register
* Remediation tracker

## Workstream 4: Technical Control Validation Planning

The technical validation workstream defines how selected security controls could be examined through a structured testing process.

The plan covers:

* User access provisioning and removal
* Privileged access and least privilege
* Multifactor authentication
* Security logging and monitoring
* Log protection and retention

Each test defines its objective, procedure, evidence requirements, expected results, and potential exceptions.

The plan is linked to existing SOC 2 control and evidence identifiers to maintain traceability.

**Testing limitation:** The plan establishes procedures for future execution. It does not claim that production systems were accessed, configurations were examined, or technical tests were completed.

## Workstream 5: Management Reporting

The consolidated management report brings together vendor risk, documented vendor findings, evidence follow-up items, SOC 2 readiness status, and recommended priorities.

Its purpose is to help a management audience distinguish between:

* Documented risks and findings
* Outstanding evidence requests
* Controls that remain untested
* Preliminary assessment work
* Recommended next steps

The report also uses workstream prefixes to reduce ambiguity where identifiers overlap between registers.

Examples include:

* `TPR:FND-001` for a third-party risk finding
* `SOC2:CTRL-004` for a SOC 2 control
* `CUST:CQA-001` for a customer assurance artifact
* `TECH:CTRL-004` for a technical validation reference, when applicable

The prefixes provide context without requiring existing identifiers to be renamed.

## Methodology and Evidence Governance

The project emphasizes repeatable documentation and traceability.

Key principles include:

* Use documented scoring criteria rather than unsupported risk ratings.
* Distinguish inherent risk from control effectiveness and residual risk.
* Link evidence requests to relevant control objectives.
* Record missing evidence as a follow-up item until sufficient information supports a stronger conclusion.
* Distinguish preliminary evidence from completed testing.
* Record findings, remediation ownership, status, and closure evidence separately.
* Preserve consistent identifiers and document cross-workstream references.
* Label fictional entities, synthetic evidence, and illustrative assessment results clearly.

The project uses a simulated environment, so its results demonstrate the application of a methodology rather than the effectiveness of real-world security controls.

## Key Lessons

This project demonstrates several practical lessons:

1. **Risk scoring needs a documented methodology.** Consistent factors and weighting make assessments easier to explain and review.
2. **Evidence gaps and control failures are different.** Missing documentation may prevent a conclusion but does not automatically prove that a control failed.
3. **Traceability matters.** Linking vendors, risks, findings, evidence, controls, and remediation items supports review and follow-up.
4. **Customer assurance requires careful wording.** Security questionnaire responses should be supported by approved documentation and appropriate evidence.
5. **Readiness is not certification.** A control matrix and evidence register are useful preparation tools, but they do not establish that an independent SOC 2 examination has been completed.
6. **Management reporting should support decisions.** Reporting should distinguish confirmed issues, open questions, testing status, and recommended priorities.

## Skills Demonstrated

This project is designed to demonstrate practical exposure to:

* Third-party risk management
* Inherent-risk scoring and risk classification
* Evidence collection and tracking
* Security questionnaire review
* SOC 2 readiness documentation
* Control mapping and test planning
* Findings and remediation tracking
* Management reporting
* Cross-workstream traceability
* Procedure and process documentation
* Communicating assessment limitations

## Project Limitations

This project has several explicit limitations:

* Northstar Cloud Solutions and the named vendors are fictional.
* Evidence records and assessment examples are synthetic.
* No actual vendor due diligence was performed.
* No real customer security questionnaire was submitted.
* No production system was tested as part of this simulated case study.
* The documented readiness status is not a SOC 2 audit opinion or certification.
* No conclusion about the effectiveness of real-world controls should be inferred from these materials.

## Conclusion

This case study brings together third-party risk management, customer security assurance, SOC 2 readiness, technical control validation planning, and management reporting in one documented scenario.

It demonstrates an organized approach to identifying risk, requesting and tracking evidence, documenting potential issues, planning control tests, and communicating status to stakeholders.

The project is intended to serve as a practical portfolio example for entry-level GRC, IT audit, IT compliance, and third-party risk management opportunities.

## Repository Navigation

Start with the repository `README.md` for the complete project structure and navigation to individual workstreams.
