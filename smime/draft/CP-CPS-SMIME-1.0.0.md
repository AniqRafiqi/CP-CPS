# MSC Trustgate Public Trust S/MIME Certificate Policy and Certification Practice Statement (CP/CPS)

| Document Metadata | Details |
| :--- | :--- |
| **Document Title:** | MSC Trustgate Public Trust S/MIME CP/CPS |
| **Document Version:** | 1.0 |
| **Effective Date:** | October 21, 2026 |
| **Object Identifier (OID):** | `1.3.6.1.4.1.9216.[Insert Branch].[Insert Use Case ID]` |
| **Location:** | https://github.com/msc-trustgate/cps-[use-case] |

## Document Version Control

| Version | Effective Date | Author / Editor | Approved By | Summary of Changes |
| :--- | :--- | :--- | :--- | :--- |
| **1.0** | 2026-10-21 | Policy Working Group | Board of Directors / Policy Authority | Initial split and restructuring from master CP/CPS into dedicated [Use Case] document. |
| | | | | |

---

## 1. Introduction

### 1.1 Overview
This Certificate Policy / Certification Practice Statement (CP/CPS) defines the operational and legal practices of MSC Trustgate.com Sdn Bhd ("MSC Trustgate") in issuing, managing, revoking, and renewing public trust [Insert Use Case] certificates. 

### 1.2 Document Name and Identification
* **Document Name:** MSC Trustgate Public Trust [Insert Use Case] CP/CPS
* **Object Identifier (OID):** `[Insert OID]`

### 1.3 PKI Participants
* **Certification Authority (CA):** MSC Trustgate
* **Registration Authority (RA):** [Internal RAs or Delegated Third Parties]
* **Subscribers:** [Entities bound by the Subscriber Agreement]
* **Relying Parties:** [Entities relying on the validity of the certificate]

### 1.4 Certificate Usage
* **Appropriate Certificate Uses:** [Specify permitted uses, key usages, and limitations for this specific domain]
* **Prohibited Certificate Uses:** [Specify prohibited high-risk or non-compliant uses]

### 1.5 Policy Administration
* **Organization Administering the Document:** MSC Trustgate Policy Authority
* **Contact Information:** `pki-policy@msctrustgate.com`

---

## 2. Publication and Repository Responsibilities

### 2.1 Repositories
MSC Trustgate maintains an online repository containing this CP/CPS, certificate revocation lists (CRLs), and other relevant public trust documentation at https://www.msctrustgate.com/repository and via GitHub.

### 2.2 Publication of Certification Information
Publication schedules, audit reports, and public keys are maintained in accordance with CA/Browser Forum and Adobe requirements.

### 2.3 Time or Frequency of Publication
* **CP/CPS Updates:** Published promptly following approval of modifications.
* **CRL Issuance:** Issued at least every [Specify frequency, e.g., 7 days or upon revocation].
* **OCSP Responders:** Updated continuously.

---

## 3. Identification and Authentication

### 3.1 Initial Registration
* **Requirement to Restrict Domain Authorization:** [Reference CA/B Forum BRs or relevant standards]
* **Authentication of Organization Identity:** [Describe validation checks for organizational identity, Business Registration numbers, etc.]
* **Authentication of Individual Identity:** [Describe passport/ID validation for S/MIME or Document Signing]

### 3.2 Routine Renewal and Re-key
* Re-verification requirements for certificate renewals.

---

## 4. Certificate Life-Cycle Operational Requirements

### 4.1 Certificate Application & Issuance
* Application process, validation checks, and subscriber agreement execution.

### 4.2 Certificate Revocation and Suspension
* Circumstances for revocation, revocation request procedure, and CRL/OCSP checking requirements.

---

## 5. Facility, Management, and Operational Controls

### 5.1 Physical Controls
* Access controls, physical security, and environmental controls for HSMs and CA infrastructure (ISO 27001 / WebTrust compliance).

### 5.2 Procedural and Personnel Controls
* Background checks, segregation of duties, and trusted roles.

---

## 6. Technical Security Controls

### 6.1 Key Pair Generation and Installation
* HSM utilization, FIPS 140-2 Level 3 (or Level 4) compliance, and key length requirements (e.g., RSA 2048/4096, ECC, PQC readiness).

### 6.2 Private Key Protection and Cryptographic Module Engineering
* Lifecycle management of CA private keys.

---

## 7. Certificate, CRL, and OCSP Profiles

### 7.1 Certificate Profile
* Summary of extensions, key usage fields, and certificate policies OID mapping.

### 7.2 CRL and OCSP Profiles
* Version numbers, extensions, and responder configurations.

---

## 8. Compliance Audit and Other Assessments

### 8.1 Frequency and Circumstances of Assessment
* Annual WebTrust for CAs, WebTrust for BRs, ISO 27001, and AATL audits.

### 8.2 Identity/Qualifications of Assessor
* Independent, licensed, and qualified third-party auditing firms.

---

## 9. Other Business and Legal Matters

### 9.1 Fees, Financial Limitations, and Indemnification
### 9.2 Confidentiality and Privacy of Information
### 9.3 Intellectual Property Rights
### 9.4 Representations and Warranties
### 9.5 Governing Law and Jurisdiction