# Third-Party Vendor Inventory

## 1. Purpose

This inventory identifies the external service providers included in the Northstar Cloud Solutions third-party risk management case study.

The inventory establishes a common record of each vendor's service, business purpose, data exposure, system access, criticality, and oversight responsibilities.

All vendors and vendor details in this document are fictional scenario assumptions.

## 2. Vendor Inventory

| Vendor ID | Vendor Name             | Service Category          | Business Purpose                                        | Data Exposure                                                                                                                | System Access                                                                                               | Proposed Business Owner | Initial Review Status |
| --------- | ----------------------- | ------------------------- | ------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ----------------------- | --------------------- |
| VND-001   | Northstar Cloud Hosting | Cloud Infrastructure      | Hosts the SaaS platform and supporting infrastructure   | Customer business records may be stored in the hosted environment; application and infrastructure logs may also be processed | Cloud infrastructure dependency; precise provider access and administrative arrangements require assessment | Security / IT           | Assessment Pending    |
| VND-002   | SignalBridge Support    | Customer Support Platform | Supports customer inquiries and service operations      | May process customer account information and support records; access to customer business data requires validation           | Support personnel may access customer records according to assigned permissions                             | Customer Success        | Assessment Pending    |
| VND-003   | MetricForge Analytics   | Product Analytics         | Supports product usage analysis and service improvement | May process application events, usage metadata, and identifiers; the inclusion of customer content requires validation       | Application integration may transmit selected event data to the vendor                                      | Engineering             | Assessment Pending    |

## 3. Vendor Record Details

### VND-001 — Northstar Cloud Hosting

**Service:** Cloud infrastructure

**Business purpose:** Provides the hosting foundation for Northstar's SaaS application.

**Key risk considerations:**

* Dependence on external cloud infrastructure.
* Administrative access and responsibility boundaries.
* Identity and access management.
* Logging, monitoring, and incident response.
* Availability, resilience, and recovery arrangements.
* Contractual security commitments and shared responsibilities.

**Due diligence priorities:**

* Confirm the service scope and applicable contractual terms.
* Identify the security responsibilities of Northstar and the provider.
* Review relevant independent assurance documentation where available in the simulation.
* Evaluate access-management and logging responsibilities.
* Assess availability, incident notification, and recovery commitments.

### VND-002 — SignalBridge Support

**Service:** Customer support platform

**Business purpose:** Enables customer service personnel to manage support interactions.

**Key risk considerations:**

* Exposure of customer account information or support records.
* Excessive access granted to support personnel.
* Authentication and privileged access.
* Data retention and deletion.
* Subprocessor use and external data sharing.
* Access removal when personnel change roles or leave.

**Due diligence priorities:**

* Define the customer information available through the platform.
* Review user roles and permissions.
* Assess authentication and access-review practices.
* Examine retention and deletion arrangements.
* Identify relevant subprocessors and contractual safeguards.

### VND-003 — MetricForge Analytics

**Service:** Product analytics

**Business purpose:** Helps Northstar understand application usage and improve its product.

**Key risk considerations:**

* Collection of unnecessary customer or user information.
* Transmission of sensitive data through analytics events.
* Excessive data retention.
* Access to analytics datasets.
* External data sharing and subprocessor use.
* Security of application integrations.

**Due diligence priorities:**

* Document the information transmitted to the service.
* Determine whether customer content or sensitive identifiers are included.
* Review data minimization and retention practices.
* Assess access permissions and authentication.
* Review relevant data-sharing arrangements and security documentation.

## 4. Ownership and Accountability

The proposed business owner is responsible for the business relationship and helping evaluate the consequences of service disruption or vendor failure.

Security / IT and GRC support technical security review, evidence evaluation, risk documentation, and remediation tracking.

Procurement and Legal / Privacy should be involved when contractual terms, data-processing obligations, privacy requirements, or vendor onboarding decisions need review.

These assignments are proposed for the fictional scenario and should be confirmed before an actual vendor relationship is approved.

## 5. Inventory Maintenance

The inventory should be updated when:

* A new vendor is proposed or onboarded.
* The vendor's service or data access changes.
* A new integration or subprocessor is introduced.
* A material security incident occurs.
* A contract is renewed or materially amended.
* The vendor is terminated.
* A reassessment identifies a change in risk.

Each material change should be recorded so the organization can explain why a vendor's risk assessment or oversight requirements changed.

## 6. Current Limitations

The inventory establishes the starting vendor population for the simulation. It does not establish that any vendor has passed due diligence or meets Northstar's security requirements.

Initial review status remains **Assessment Pending** until the relevant assessment work is completed and documented.
