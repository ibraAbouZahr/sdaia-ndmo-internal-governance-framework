## levels: Public, Internal, Confidential, Sensitive.

# 📚 Data Classification Policy

**Version:** 1.0  
**Last Updated:** July 2025  
**Owner:** Data Governance Officer  
**Reference:** [Saudi NDMO Framework](https://dgp.sdaia.gov.sa/wps/portal/pdp/home), [PDPL]

---

## 🧭 Purpose

The purpose of this Data Classification Policy is to ensure that all data assets managed by the organization are identified, classified, and protected in alignment with their sensitivity, regulatory requirements, and business value—according to the guidelines of the **Saudi National Data Management Office (NDMO)** and **Personal Data Protection Law (PDPL)**.

---

## 🎯 Scope

This policy applies to all data created, received, processed, stored, or transmitted by the organization across all systems, departments, and third-party entities.

---

## 🏷️ Data Classification Levels

| Classification Level | Description                                                                                                                 | Example Data                                                           | Handling Requirements                                                                                                 |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Public**           | Data intended for public distribution. Unauthorized disclosure poses no risk.                                               | Published reports, marketing material, public datasets.                | No restrictions. Can be freely shared.                                                                                |
| **Internal**         | Data meant for internal use. Disclosure may cause minor harm or reputational risk.                                          | Employee lists, internal memos, project documents.                     | Limit access to internal staff. Share on secured channels.                                                            |
| **Confidential**     | Sensitive operational data. Unauthorized disclosure can result in moderate damage.                                          | Financial data, strategy documents, procurement details.               | Encrypted storage. Access on a need-to-know basis.                                                                    |
| **Restricted**       | Highly sensitive data with legal, regulatory, or contractual restrictions. Breach could result in severe penalties or harm. | Personal data (PDPL), national identifiers, medical or biometric data. | Strict access control. Encryption in transit & at rest. Mandatory auditing. Prior authorization required for sharing. |

---

## 👤 Roles and Responsibilities

| Role                          | Responsibility                                                                                               |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Data Owner**                | Assign classification level at data creation or acquisition. Ensure compliance with classification policies. |
| **Data Custodian**            | Implement appropriate security controls according to classification.                                         |
| **Data Users**                | Follow access and handling rules. Report incidents or breaches.                                              |
| **Data Governance Committee** | Review classification rules and ensure alignment with national standards.                                    |

---

## 🛠️ Classification Guidelines

1. **Default Classification**  
   All data must be classified as **Internal** unless otherwise specified by the Data Owner.

2. **Reclassification**  
   Data must be re-evaluated when:

   - Sensitivity changes
   - Regulatory context changes
   - Data is aggregated or anonymized

3. **Data Lifecycle Consideration**  
   Classification must be maintained throughout the data lifecycle—from creation to archival and deletion.

---

## 🧪 Handling Requirements by Level

| Classification | Storage                | Transmission                 | Access Control                 | Disposal                          |
| -------------- | ---------------------- | ---------------------------- | ------------------------------ | --------------------------------- |
| Public         | General storage        | Open networks allowed        | No restriction                 | Standard deletion                 |
| Internal       | Secured file systems   | Organization email only      | Basic authentication           | Secure wipe recommended           |
| Confidential   | Encrypted storage      | VPN or secure tunnel         | Role-based access              | Secure deletion (shred/overwrite) |
| Restricted     | Encrypted + segregated | Encrypted channels (TLS/SSL) | Multi-factor auth, access logs | Certified secure destruction      |

---

## 🧾 Compliance References

- 🏛️ [NDMO National Data Classification Policy](https://www.ndmo.gov.sa)
- ⚖️ [Personal Data Protection Law (PDPL)](https://sdaia.gov.sa)
- 🛡️ [SDAIA Cybersecurity Controls]

---

## 📅 Review & Audit

This policy must be reviewed **annually** or when significant regulatory updates occur. Data audits should validate correct classification and handling of sensitive datasets.

---

## ✅ Acknowledgement

All employees, contractors, and third party users must read and acknowledge this policy as part of their onboarding and annual compliance training.

---

> **Note:** Misclassification of data may result in disciplinary action and legal liability under applicable Saudi regulations.

---
