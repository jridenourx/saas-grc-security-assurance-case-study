# Third-Party Risk Evidence Register

## 1. Purpose

This register tracks evidence requested, received, reviewed, and used to support third-party risk assessments for Northstar Cloud Solutions.

It provides traceability between vendor due diligence responses, supporting evidence, risk decisions, findings, and remediation activities.

All records in this portfolio are part of a fictional simulation. Evidence status must accurately reflect whether a record is planned, created, received, or reviewed.

## 2. Evidence Status Definitions

| Status       | Definition                                                                                  |
| ------------ | ------------------------------------------------------------------------------------------- |
| Planned      | Evidence has been identified as necessary but has not yet been created or requested.        |
| Requested    | Evidence has been requested from the fictional vendor within the simulation.                |
| Received     | The evidence artifact is available for review.                                              |
| Under Review | The assessor is evaluating the evidence.                                                    |
| Accepted     | The evidence is sufficiently relevant and reliable for its stated assessment purpose.       |
| Rejected     | The evidence is unsuitable for its intended purpose, with the reason documented.            |
| Superseded   | A newer or more appropriate artifact has replaced the evidence for the relevant assessment. |

**Important:** "Accepted" means the evidence is suitable for the specific assessment purpose. It does not automatically mean the associated control is effective.

## 3. Evidence Register

The register tracks evidence state within the fictional simulation. Most entries remain **Planned** because the corresponding artifacts have not yet been documented as available for review. EVD-005, EVD-006, and EVD-009 are marked **Received** because corresponding synthetic scenario artifacts are documented in `synthetic-vendor-assessments.md` and referenced by the simulated findings.

"Received" means that a fictional artifact is available for review in the scenario. It does not establish that real vendor evidence was received, that a real-world incident occurred, or that a control is operating effectively. The three received artifacts support the stated simulated design observations only. Technical and operational validation remains outstanding.

| Evidence ID | Vendor ID | Evidence Description                                         | Related Questionnaire IDs    | Assessment Purpose                                                | Initial Status | Limitations / Notes                                                                                                                                                                                  |
| ----------- | --------- | ------------------------------------------------------------ | ---------------------------- | ----------------------------------------------------------------- | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EVD-001     | VND-001   | Service scope and shared-responsibility documentation        | Q-05, Q-12                   | Establish service boundaries and responsibility allocation        | Planned        | Scope and responsibilities have not yet been validated.                                                                                                                                              |
| EVD-002     | VND-001   | Relevant independent security assurance summary              | Q-29                         | Evaluate available independent assurance                          | Planned        | Report availability, period, scope, and exceptions require review.                                                                                                                                   |
| EVD-003     | VND-001   | Identity, privileged access, and MFA control documentation   | Q-06, Q-07, Q-08, Q-11       | Assess access-control expectations and responsibilities           | Planned        | Documentation alone does not establish operating effectiveness.                                                                                                                                      |
| EVD-004     | VND-001   | Logging, incident response, and recovery documentation       | Q-21, Q-22, Q-24, Q-26, Q-27 | Assess logging and resilience practices                           | Planned        | Actual configuration and test results have not been evaluated.                                                                                                                                       |
| EVD-005     | VND-002   | Support-platform data-flow and data-handling summary         | Q-12, Q-13, Q-17             | Determine the type and sensitivity of customer data exposed       | Received       | Synthetic scenario artifact is documented in `synthetic-vendor-assessments.md`; supports the simulated design observation only. Actual vendor data access and processing are not verified.           |
| EVD-006     | VND-002   | User-role and permission matrix                              | Q-08, Q-09, Q-11, Q-17       | Evaluate least privilege and access governance                    | Received       | Synthetic role-permission and access-review details are documented in the scenario; supports the simulated design observation only. Actual assignments and operating effectiveness are not verified. |
| EVD-007     | VND-002   | Data retention, deletion, and subprocessor documentation     | Q-16, Q-18                   | Assess data lifecycle and external data-sharing risks             | Planned        | Contractual and operational implementation require review.                                                                                                                                           |
| EVD-008     | VND-002   | Incident notification and response documentation             | Q-24, Q-25                   | Evaluate incident handling and customer notification arrangements | Planned        | Actual response performance has not been tested.                                                                                                                                                     |
| EVD-009     | VND-003   | Analytics event schema and data-flow description             | Q-12, Q-13, Q-17             | Identify information transmitted through the integration          | Received       | Synthetic event-schema artifact is documented in `synthetic-vendor-assessments.md`; supports the simulated design observation only. No real customer information transmission is established.        |
| EVD-010     | VND-003   | Integration permissions and authentication documentation     | Q-06, Q-07, Q-08             | Evaluate integration access and authentication safeguards         | Planned        | Actual permissions and configuration require validation.                                                                                                                                             |
| EVD-011     | VND-003   | Data retention, deletion, and external sharing documentation | Q-16, Q-18                   | Assess retention and third-party data-sharing risks               | Planned        | Actual retention settings and sharing practices have not been verified.                                                                                                                              |
| EVD-012     | VND-003   | Security logging and incident response documentation         | Q-21, Q-23, Q-24             | Evaluate relevant security monitoring and response arrangements   | Planned        | Evidence of actual monitoring and response effectiveness remains outstanding.                                                                                                                        |

## 4. Evidence Review Record

When an evidence artifact becomes available, record the review using the following fields.

| Field                  | Description                                                            |
| ---------------------- | ---------------------------------------------------------------------- |
| Evidence ID            | Unique identifier from this register.                                  |
| Artifact Name          | Name of the specific document or synthetic record.                     |
| Artifact Location      | Relative repository path or documented source.                         |
| Source                 | Origin of the artifact.                                                |
| Date Created or Issued | Date associated with the artifact, where applicable.                   |
| Date Reviewed          | Date the assessor reviewed the artifact.                               |
| Reviewer               | Responsible assessor or simulated role.                                |
| Scope and Period       | Systems, users, locations, or period covered.                          |
| Relevance              | How the evidence addresses the assessment question.                    |
| Reliability            | Whether the source and content are credible for the intended purpose.  |
| Completeness           | Whether relevant scope and information are covered.                    |
| Timeliness             | Whether the artifact is current enough for the assessment.             |
| Conclusion             | What the evidence supports and what remains uncertain.                 |
| Limitations            | Missing information, exceptions, or other constraints.                 |
| Related IDs            | Relevant vendor, risk, control, questionnaire, finding, or action IDs. |

Do not create an entry marked "Accepted" without recording the rationale for accepting the evidence.

## 5. Evidence Handling Rules

### 5.1 Synthetic Evidence

Artifacts created for this case study must be labeled clearly, for example:

`SYNTHETIC EVIDENCE — FICTIONAL VENDOR — PORTFOLIO SIMULATION`

Synthetic evidence should use fictional names, accounts, records, and configurations. It must not contain real credentials, sensitive customer information, or private organizational records.

### 5.2 Evidence Gaps

If required evidence is unavailable, document the gap and its significance.

An evidence gap means the assessor cannot reach a sufficiently supported conclusion from the information available. It does not automatically prove that the underlying control is absent or ineffective.

### 5.3 Conflicting Evidence

When evidence conflicts with a questionnaire response or another artifact:

1. Record the conflicting sources.
2. Determine whether scope, timing, or terminology explains the difference.
3. Request clarification when appropriate.
4. Document the resolution or remaining uncertainty.
5. Link material unresolved issues to the risk register and remediation tracker.

### 5.4 Evidence Retention

Store only the evidence necessary to support the assessment. Use sanitized artifacts and maintain clear links between the evidence register and the corresponding files.

## 6. Relationship to Other Records

The evidence register supports the following work products:

* **Vendor inventory:** Identifies the vendor associated with each evidence record.
* **Vendor risk assessment matrix:** Provides supporting information that may change preliminary ratings.
* **Due diligence questionnaire:** Connects responses to supporting artifacts.
* **Risk register:** Records material exposures and uncertainty.
* **Findings register:** Documents identified control or process weaknesses.
* **Remediation tracker:** Tracks corrective actions and closure evidence.

Use the existing identifiers consistently rather than creating duplicate records for the same issue.

## 7. Current Limitations

Most entries in this register remain **Planned**. EVD-005, EVD-006, and EVD-009 are marked **Received** because corresponding synthetic artifacts are documented in the scenario. These three records have not been represented as real vendor evidence.

The presence of an artifact does not by itself establish that the associated control is effective. Further evaluation, technical or operational validation where applicable, and documentation of limitations are required before making stronger conclusions.

Vendor conclusions and final risk ratings should be updated only when the relevant evidence and assessment results have been documented.

## 8. Simulation Disclaimer

This register is part of a fictional GRC portfolio exercise. All simulated artifacts and results must be clearly identified as such and must not be represented as evidence from a real vendor assessment.
