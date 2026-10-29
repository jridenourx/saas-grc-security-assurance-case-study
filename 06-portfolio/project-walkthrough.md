# Project Walkthrough: SaaS GRC and Security Assurance Case Study

## Purpose

This guide provides a structured walkthrough of the SaaS GRC and Security Assurance Case Study.

It is designed to help a reviewer understand the project quickly and help the author explain the methodology, documentation, findings, and limitations during an interview.

**Project disclaimer:** Northstar Cloud Solutions, its vendors, and the supporting records are fictional or synthetic. This is a simulated GRC assessment and readiness exercise, not a real audit or SOC 2 certification.

## 1. Start with the Business Scenario

### What to Show

Start with the repository `README.md`, followed by:

* `docs/project-charter.md`
* `docs/company-profile.md`
* `docs/scope-and-assumptions.md`
* `docs/methodology.md`

### What to Explain

The project simulates a B2B SaaS organization hosted on AWS. The organization relies on cloud infrastructure, a customer support platform, and an analytics service.

The purpose is to demonstrate how a GRC practitioner can organize risk assessments, evidence requests, customer security responses, control readiness activities, and management reporting into a connected process.

### Talking Point

"I built this project around a fictional SaaS company to demonstrate how several GRC activities fit together. I wanted to show not just individual documents, but how risk identification, evidence tracking, control assessment, remediation, and reporting connect."

## 2. Explain Third-Party Risk Management

### What to Show

Open the `01-third-party-risk/` directory.

Recommended files:

* `vendor-inventory.md`
* `vendor-risk-assessment-matrix.md`
* `vendor-risk-summary.md`
* `risk-register.md`
* `findings-remediation-tracker.md`
* `evidence-register.md`
* `vendor-lifecycle-procedure.md`

### What to Explain

The vendor workstream evaluates three fictional vendors using a consistent inherent-risk scoring method.

The model considers data sensitivity, system access, business criticality, and dependency or concentration risk. Each factor has a defined weight, and the resulting score maps to a risk tier.

The project also distinguishes between documented vendor findings and evidence follow-up items. This distinction matters because missing documentation does not automatically prove that a security control failed.

### Key Scenario Results

| Vendor                  | Score | Tier     |
| ----------------------- | ----: | -------- |
| Northstar Cloud Hosting |  4.75 | High     |
| SignalBridge Support    |  3.30 | Moderate |
| MetricForge Analytics   |  2.55 | Moderate |

The scenario documents two High findings associated with SignalBridge Support and one Moderate finding associated with MetricForge Analytics.

These are fictional scenario findings, not verified weaknesses in actual vendors.

### Talking Point

"I used the same documented scoring methodology across all three vendors so that the results could be compared consistently. I also kept evidence gaps separate from findings so that the assessment wouldn't make stronger claims than the available information supported."

### Likely Interview Question

**Why use a weighted risk-scoring model?**

A weighted model provides a repeatable way to compare vendors based on defined criteria. It also makes the rationale easier to communicate. The score supports prioritization, but it does not replace professional judgment or establish control effectiveness by itself.

## 3. Explain Customer Security Assurance

### What to Show

Open the `02-customer-assurance/` directory.

Recommended files:

* `customer-security-questionnaire.md`
* `security-questionnaire-response-library.md`
* `sample-customer-questionnaire.md`
* `questionnaire-review-procedure.md`

### What to Explain

This workstream simulates a controlled process for responding to customer security questionnaires.

The response library supports consistency, while the review procedure establishes how responses should be checked and escalated. The goal is to avoid inconsistent or unsupported claims about security controls.

### Talking Point

"I treated customer questionnaires as a governance process rather than just a writing exercise. Responses should be consistent, but they also need to be supported by current documentation and reviewed when the question requires technical or compliance input."

### Likely Interview Question

**What would you do if a customer asked about a control that had not been verified?**

I would not present the control as implemented without support. I would identify the appropriate control owner, request the necessary evidence, and use the organization's approved review process. If the question could not be answered accurately, I would escalate it rather than guess.

## 4. Explain SOC 2 Readiness

### What to Show

Open the `03-soc2-readiness/` directory.

Recommended files:

* `readiness-scope.md`
* `control-matrix.md`
* `evidence-request-register.md`
* `control-testing-plan.md`
* `evidence-samples.md`
* `assessment-results.md`
* `findings-register.md`
* `remediation-tracker.md`

### What to Explain

This workstream organizes 15 security-control areas into a readiness process.

Each control is associated with expected evidence. The testing plan defines how the control could be assessed, and the results register records the current status.

Six controls are marked In Progress because preliminary synthetic evidence samples have been drafted. Nine controls are marked Not Tested.

These statuses do not mean that the six controls have passed or that the remaining controls have failed. They communicate the current state of the simulated assessment work.

### Talking Point

"I focused on building traceability between control expectations, evidence requests, testing procedures, and assessment status. I also made sure the documentation distinguished readiness activities from completed testing and formal SOC 2 assurance."

### Likely Interview Question

**Does this project show that the company passed a SOC 2 audit?**

No. It is a simulated readiness exercise. The project demonstrates how control documentation, evidence requests, and testing procedures can be organized. It does not represent a completed independent SOC 2 examination or certification.

## 5. Explain Technical Control Validation Planning

### What to Show

Open `04-technical-validation/technical-control-validation-plan.md`.

### What to Explain

The technical validation plan outlines procedures for examining selected control areas:

* User access provisioning and removal
* Privileged access and least privilege
* Multifactor authentication
* Security logging and monitoring
* Log protection and retention

Each planned test includes an objective, procedures, evidence requirements, expected results, and potential exceptions.

The plan is linked to existing SOC 2 control and evidence identifiers to preserve traceability.

### Talking Point

"I wanted to connect the documented control requirements to practical validation procedures. The plan describes what I would examine, what evidence I would need, and what conditions could indicate an exception. I have not represented the planned procedures as completed technical tests."

### Likely Interview Question

**How would you validate an access-control process?**

I would first understand the control objective and obtain the approved procedure. Depending on the scope, I would examine access requests, approvals, provisioning records, role assignments, and termination records. I would define the relevant population and period, perform the authorized procedures, document exceptions, and link the evidence to the control being assessed.

The exact procedures would depend on the system, the control design, the scope, and the evidence available.

## 6. Explain Management Reporting

### What to Show

Open `05-management-reporting/consolidated-grc-management-report.md`.

### What to Explain

The management report brings together information from the vendor risk, customer assurance, and SOC 2 readiness workstreams.

It summarizes vendor risk tiers, documented vendor findings, evidence follow-up items, assessment status, and recommended priorities.

The report also uses workstream prefixes to clarify references when different registers have similar identifier patterns.

### Talking Point

"I created the consolidated report so that management would not have to review every workpaper to understand the major risks and outstanding work. The report distinguishes documented findings from evidence gaps and untested controls so that the status is clear."

### Likely Interview Question

**How would you decide which issues to prioritize?**

I would consider the potential impact, likelihood, business criticality, data sensitivity, access level, existing safeguards, and urgency. I would also consider whether the issue affects multiple systems or vendors. I would document the rationale, confirm ownership, and align remediation priorities with the organization's risk criteria.

## 7. Explain Lessons Learned

### What to Show

Open `06-portfolio/lessons-learned.md`.

### What to Explain

The lessons document summarizes improvements that could make the assessment process more consistent and effective.

Key themes include:

* Documenting the risk-scoring methodology
* Separating evidence gaps from control failures
* Maintaining traceability
* Defining specific evidence requests
* Reviewing customer security responses
* Distinguishing readiness from formal assurance
* Requiring verifiable remediation closure
* Connecting technical tests to business risks
* Improving management reporting
* Reviewing consistency across documents

### Talking Point

"One of the main lessons was that documentation needs to be consistent across the entire process. A risk rating, finding, evidence request, and remediation action should be traceable to each other. I also learned the importance of clearly documenting what has and has not been verified."

## 8. Explain the Project's Limitations

Be direct about the limitations.

The project uses a fictional organization and synthetic evidence. It does not demonstrate access to a real company's security environment, completion of production technical testing, or completion of a SOC 2 examination.

The value of the project is its demonstration of methodology, documentation, traceability, and reporting.

### Talking Point

"I intentionally labeled the scenario and evidence as fictional or synthetic. I wanted the project to demonstrate how I would approach the work without implying that I performed a real audit or verified controls that I did not test."

## 9. A Short Interview Summary

Use this when an interviewer asks you to describe the project in about a minute.

> I built a simulated GRC and security assurance case study around a fictional SaaS company hosted on AWS. The project covers third-party risk management, customer security questionnaires, SOC 2 readiness, technical control validation planning, and management reporting.
>
> I developed a weighted vendor risk-scoring approach, documented vendor findings and evidence follow-up items, organized 15 security-control areas into a readiness framework, and created a plan for validating selected technical controls.
>
> I also consolidated the results into management-oriented reporting. One of the main things I focused on was traceability between risks, controls, evidence, findings, and remediation actions. I clearly labeled the scenario and evidence as synthetic so the project demonstrates my methodology without misrepresenting it as a real audit or certification.

## 10. Recommended Walkthrough Order

For a short demonstration, use this order:

1. **README and project scope:** Explain the business scenario and project objectives.
2. **Vendor risk assessment:** Show the scoring methodology and the difference between findings and evidence gaps.
3. **Customer assurance:** Explain how questionnaire responses are standardized and reviewed.
4. **SOC 2 readiness:** Show the control matrix, evidence register, and assessment statuses.
5. **Technical validation plan:** Demonstrate how control expectations translate into test procedures.
6. **Management report:** Explain how detailed work is summarized for decision-makers.
7. **Lessons learned:** Close with the process improvements and limitations.

For a short interview, spend more time explaining your reasoning and methodology than reading the documents aloud.

## Final Reminder

Be prepared to explain why you selected the methodology, how you would validate evidence, how you would document an exception, and how you would prioritize remediation.

A strong walkthrough is not about claiming that every control passed. It is about demonstrating that you understand how to structure an assessment, evaluate evidence carefully, communicate uncertainty, and document defensible conclusions.
