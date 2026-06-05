# Business Requirements Document (BRD)

## Project Title

Personal Banking Current Account

## Version

1.0

## Prepared By

Business Analyst Team

## Date

June 2026

---

# 1. Executive Summary

The objective of this project is to provide customers with the ability to open and manage a Personal Current Account through digital and branch banking channels. The solution aims to simplify account opening, improve customer experience, and support daily banking transactions.

---

# 2. Business Objective

* Enable customers to open a current account digitally.
* Reduce account opening turnaround time.
* Provide seamless banking services through online and mobile channels.
* Increase customer acquisition and retention.
* Ensure compliance with banking regulations and KYC requirements.

---

# 3. Scope

## In Scope

* Current account application.
* Customer identity verification (KYC).
* Account approval workflow.
* Debit card issuance.
* Online banking enrollment.
* Mobile banking enrollment.
* Account maintenance.
* Transaction history viewing.
* Statement generation.

## Out of Scope

* Loan processing.
* Credit card applications.
* Investment products.
* Business current accounts.

---

# 4. Stakeholders

| Stakeholder          | Role                  |
| -------------------- | --------------------- |
| Customer             | Account holder        |
| Relationship Manager | Customer support      |
| Operations Team      | Account verification  |
| Compliance Team      | KYC verification      |
| Branch Staff         | Account assistance    |
| IT Team              | System implementation |

---

# 5. Business Requirements

## BR-001: Account Opening

**Description:** Customers shall be able to apply for a personal current account through digital channels and branch offices.

### Acceptance Criteria

* Customer can initiate account opening.
* Application form is available online.
* Mandatory fields are validated.

---

## BR-002: Customer KYC Verification

**Description:** System shall verify customer identity using KYC documents.

### Acceptance Criteria

* Aadhaar, PAN, Passport, or Driving License accepted.
* KYC verification status displayed.
* Application cannot proceed without successful verification.

---

## BR-003: Eligibility Validation

**Description:** System shall verify customer eligibility before account creation.

### Acceptance Criteria

* Customer must be at least 18 years old.
* Customer must possess valid identification.
* Existing blacklisted customers cannot open accounts.

---

## BR-004: Account Creation

**Description:** System shall create a current account upon successful verification.

### Acceptance Criteria

* Unique account number generated.
* Customer receives confirmation notification.
* Account status marked as Active.

---

## BR-005: Debit Card Request

**Description:** Customer may request a debit card during account opening.

### Acceptance Criteria

* Customer can opt-in or opt-out.
* Card request sent to card management system.
* Customer receives tracking information.

---

## BR-006: Online Banking Registration

**Description:** Customer shall be able to register for internet banking.

### Acceptance Criteria

* User credentials generated securely.
* Multi-factor authentication enabled.
* Registration confirmation sent to customer.

---

## BR-007: Transaction Management

**Description:** Customer shall perform banking transactions after account activation.

### Acceptance Criteria

* Funds transfer supported.
* Balance inquiry available.
* Transaction history accessible.

---

## BR-008: Statement Generation

**Description:** Customer shall be able to generate account statements.

### Acceptance Criteria

* Statements available in PDF format.
* Customer can select date range.
* Statements downloadable and printable.

---

# 6. Functional Requirements

| ID     | Requirement                   |
| ------ | ----------------------------- |
| FR-001 | Capture customer details      |
| FR-002 | Validate mandatory fields     |
| FR-003 | Upload KYC documents          |
| FR-004 | Perform identity verification |
| FR-005 | Generate account number       |
| FR-006 | Send email notifications      |
| FR-007 | Send SMS notifications        |
| FR-008 | Generate account statements   |
| FR-009 | Support debit card requests   |
| FR-010 | Enable online banking access  |

---

# 7. Non-Functional Requirements

| ID      | Requirement                           |
| ------- | ------------------------------------- |
| NFR-001 | System availability of 99.9%          |
| NFR-002 | Response time under 3 seconds         |
| NFR-003 | Data encrypted in transit and at rest |
| NFR-004 | Regulatory compliance maintained      |
| NFR-005 | Audit logging enabled                 |
| NFR-006 | Mobile responsive user interface      |

---

# 8. Assumptions

* Customer possesses valid identification documents.
* SMS and email services are operational.
* Core banking system is available.

---

# 9. Constraints

* Must comply with banking regulations.
* Must support approved KYC document types.
* Integration dependent on core banking APIs.

---

# 10. Risks

| Risk                  | Impact | Mitigation                   |
| --------------------- | ------ | ---------------------------- |
| KYC service outage    | High   | Manual verification process  |
| Core banking downtime | High   | Retry and recovery mechanism |
| Regulatory changes    | Medium | Periodic compliance review   |

---

# 11. Success Metrics

* Account opening completed within 10 minutes.
* 95% digital application success rate.
* Reduced branch visits by 40%.
* Customer satisfaction score above 4.5/5.

---

# 12. Approval

| Role             | Name | Signature |
| ---------------- | ---- | --------- |
| Business Sponsor |      |           |
| Product Owner    |      |           |
| Compliance Head  |      |           |
| IT Manager       |      |           |

---

**End of Document**
