# Framework Reference Register

## 1. Purpose

This register identifies the frameworks and technical guidance informing the Northstar Cloud Solutions GRC case study.

References will be applied selectively based on the assessment objective, system scope, and relevant risks. Referencing a framework does not establish compliance with that framework.

## 2. Reference Register

| Reference ID | Framework or Guidance                                                                                      | Intended Use                                                                                              | Relevant Workstream                   |
| ------------ | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------- |
| REF-001      | AICPA Trust Services Criteria                                                                              | Inform the selection and evaluation of criteria relevant to the proposed SOC 2 readiness assessment       | SOC 2 Readiness; Customer Assurance   |
| REF-002      | NIST SP 800-161 Rev. 1, Cybersecurity Supply Chain Risk Management Practices for Systems and Organizations | Inform the development of a risk-based third-party risk management process and vendor oversight practices | Third-Party Risk Management           |
| REF-003      | NIST SP 800-53 Rev. 5, Security and Privacy Controls for Information Systems and Organizations             | Provide a reference for selecting and describing relevant security controls                               | SOC 2 Readiness; Technical Validation |
| REF-004      | AWS Identity and Access Management best practices                                                          | Inform the evaluation of access permissions, least privilege, and identity security                       | Technical Validation                  |
| REF-005      | AWS CloudTrail documentation and security guidance                                                         | Inform the evaluation of cloud activity logging and relevant evidence                                     | Technical Validation                  |

## 3. Application of References

### REF-001 — AICPA Trust Services Criteria

The project will primarily consider the Security category when defining the proposed SOC 2 readiness scope.

Any additional Trust Services Criteria will be included only when justified by the scenario and assessment objectives.

The case study is not an independent SOC 2 examination and does not produce a SOC 2 report.

### REF-002 — NIST SP 800-161 Rev. 1

This guidance will inform the structure of the third-party risk management lifecycle, including:

* Vendor identification and inventory.
* Risk-based vendor categorization.
* Due diligence and evidence review.
* Risk treatment and remediation.
* Ongoing monitoring and reassessment.

The vendor assessment methodology developed for this project is a proposed internal approach informed by relevant guidance. It is not presented as a reproduction of the complete NIST publication.

### REF-003 — NIST SP 800-53 Rev. 5

Relevant control concepts may be used to support control descriptions, assessment procedures, and evidence requirements.

The project will select controls appropriate to the fictional system and defined scope rather than attempting to assess the entire catalog.

A control mapping is not, by itself, evidence that a control is implemented or effective.

### REF-004 — AWS Identity and Access Management Guidance

AWS guidance will inform the assessment of identity-related security practices, including least privilege and access permissions.

Assessment conclusions will be based on the evidence defined for the simulation or collected from an explicitly identified sandbox environment.

### REF-005 — AWS CloudTrail Guidance

AWS CloudTrail guidance will inform the review of cloud activity logging, including relevant configuration, coverage, and evidence considerations.

The project will distinguish between the existence of a logging configuration and evidence that logging meets the defined assessment requirements.

## 4. Reference Management

For each reference used in a completed assessment, the project should record:

* Reference ID.
* Official publication or documentation title.
* Issuing organization.
* Version or revision, where applicable.
* Official source location.
* Date accessed, when relevant.
* Specific control, section, or guidance applied.
* Work product in which the reference was used.

When framework versions or official guidance change, the project should identify which version was used for the assessment rather than silently mixing requirements from different versions.

## 5. Interpretation and Limitations

Frameworks and guidance serve as assessment references, not automatic pass/fail checklists.

The project will document how each selected reference applies to the fictional scenario. Where a requirement is outside the defined scope, not applicable, or unsupported by available evidence, that limitation will be stated explicitly.

All assessments remain simulated portfolio exercises and do not represent a real audit, certification, or compliance determination.
