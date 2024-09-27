# Identifying Security Gaps and Compliance Issues in Cybersecurity Audits

## Table of Contents
1. [Introduction](#introduction)
2. [Audit Scenario](#audit-scenario)
3. [Audit Workflow Checklist](#audit-workflow-checklist)
4. [Controls Assessment](#controls-assessment)
5. [Compliance Checklist](#compliance-checklist)
6. [Recommendations for the IT Manager](#recommendations-for-the-it-manager)
7. [Conclusion](#conclusion)

## Introduction

This report outlines an internal security audit conducted on Botium Toys, a fictitious toy company, as part of my portfolio for the Google Cybersecurity Professional Certificate program, specifically in the Play It Safe: Manage Security Risks course. The primary aim of this audit is to evaluate Botium Toys' cybersecurity practices and align them with industry standards, providing recommendations for addressing identified vulnerabilities to enhance the organization’s overall security posture.

This audit is informed by the **[Botium Toys: Scope, Goals, and Risk Assessment Report](https://docs.google.com/document/d/10_ZmqYdn5XoL6UW03TiVoMQJKeVcEU8RIRMTag1UT8M/edit?usp=share_link)**, which outlines the current state of the organization’s cybersecurity measures and identifies key areas requiring improvement.

## Audit Scenario

Botium Toys operates as a small U.S.-based toy retailer with a growing online presence. The company faces challenges in managing its IT infrastructure while ensuring compliance with online payment regulations and safeguarding sensitive customer information. The IT manager has recognized the need for a comprehensive internal audit to assess potential risks, enhance business continuity, and establish a solid security framework as the business expands both domestically and internationally.

The goals of the audit, as outlined in the **Scope, Goals, and Risk Assessment Report**, are:

- To implement the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF).
- To improve processes for compliance.
- To fortify system controls.
- To enforce the principle of least privilege in user credential management.
- To develop and document necessary policies and procedures.

## Audit Workflow Checklist

The audit process consists of the following steps:

1. **Define Audit Scope and Goals**
   - Establish the scope of the audit.
   - Identify specific goals aligned with NIST CSF.

2. **Conduct the Audit**
   - Analyze the current cybersecurity landscape.
   - Perform a comprehensive assessment of existing security measures.

3. **Complete Controls Assessment**
   - Evaluate current controls and identify gaps.
   - Prioritize necessary controls for implementation.

4. **Complete Compliance Checklist**
   - Review compliance regulations and standards.
   - Justify adherence to selected regulations.

5. **Document Findings and Recommendations**
   - Summarize findings from the audit.
   - Clearly outline actionable recommendations for stakeholders.

6. **Communicate Findings**
   - Prepare a concise report for stakeholders.
   - Present findings and recommendations clearly.

## Controls Assessment

### Current Assets

The IT Department manages several essential assets, including:

- On-premises equipment for daily operations.
- Employee devices (desktops, laptops, smartphones).
- Management of systems and services (accounting, telecommunications, security, ecommerce).
- Internet connectivity and internal network management.
- Vendor access control and data storage solutions.

### Controls Assessment Checklist

Does Botium Toys currently have this control in place?

| Control                                                   | Control in Place | Control Not in Place |
|----------------------------------------------------------|------------------|---------------------|
| Least Privilege                                          |                  | ✔️                  |
| Disaster Recovery Plans                                   |                  | ✔️                  |
| Password Policies                                        |                  | ✔️                  |
| Separation of Duties                                     |                  | ✔️                  |
| Firewall                                                 | ✔️               |                     |
| Intrusion Detection System (IDS)                         |                  | ✔️                  |
| Backups                                                  |                  | ✔️                  |
| Antivirus Software                                       | ✔️               |                     |
| Manual Monitoring, Maintenance, and Intervention for Legacy Systems |                  | ✔️                  |
| Encryption                                               | ✔️               |                     |
| Password Management System                                |                  | ✔️                  |
| Locks (Offices, Storefront, Warehouse)                  | ✔️               |                     |
| Closed-Circuit Television (CCTV) Surveillance            | ✔️               |                     |
| Fire Detection/Prevention (Fire Alarm, Sprinkler System) | ✔️               |                     |

## Compliance Checklist

Does Botium Toys currently adhere to this compliance best practice?

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                   | Control in Place | Control Not in Place |
|----------------------------------------------------------------|------------------|---------------------|
| Only authorized users have access to customers’ credit card information.  |                  | ✔️                  |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |                  | ✔️                  |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. |                  | ✔️                  |
| Adopt secure password management policies.                            |                  | ✔️                  |

### General Data Protection Regulation (GDPR)

| Best Practice                                                   | Control in Place | Control Not in Place |
|----------------------------------------------------------------|------------------|---------------------|
| E.U. customers’ data is kept private/secured.                  |                  | ✔️                  |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | ✔️               |                     |
| Ensure data is properly classified and inventoried.            |                  | ✔️                  |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | ✔️               |                     |

### System and Organizations Controls (SOC type 1, SOC type 2)

| Best Practice                                                   | Control in Place | Control Not in Place |
|----------------------------------------------------------------|------------------|---------------------|
| User access policies are established.                          |                  | ✔️                  |
| Sensitive data (PII/SPII) is confidential/private.            |                  | ✔️                  |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated. | ✔️               |                     |
| Data is available to individuals authorized to access it.     |                  | ✔️                  |

## Recommendations for the IT Manager

**TO:** IT Manager, Stakeholders  
**FROM:** [Your Name]  
**DATE:** [Insert Date]  
**SUBJECT:** Internal IT Audit Findings and Recommendations

---

### Overview

This memorandum presents the internal audit findings for Botium Toys, highlighting critical vulnerabilities in both the organization's security controls and compliance with essential regulations. The audit has identified significant issues, particularly concerning the Payment Card Industry Data Security Standard (PCI DSS), which is crucial for any business handling credit card transactions. Specifically, Botium Toys lacks proper access controls for customer credit card information, secure storage mechanisms, and necessary encryption protocols, posing substantial risks to both customer data and the company's reputation.

Additionally, the audit has revealed multiple deficiencies in the implementation of System and Organizations Controls (SOC type 1 and SOC type 2). These standards are designed to ensure that organizations maintain effective internal controls over financial reporting and data security. Key controls such as user access policies and confidentiality measures for sensitive data (PII/SPII) are currently not in place. This not only exposes the organization to potential data breaches but also increases the risk of regulatory penalties.

While the General Data Protection Regulation (GDPR) compliance requirements are noted, they are not the primary focus of concern in this audit. Instead, the lack of adherence to PCI DSS and SOC controls presents immediate and more pressing vulnerabilities that Botium Toys must address to safeguard its operations and customer trust.

In light of these findings, actionable recommendations will be provided to enhance the organization's cybersecurity posture and ensure compliance with relevant regulatory standards.

---

### Audit Scope

The audit evaluated systems including:

- Accounting
- Endpoint detection
- Firewalls
- Intrusion detection systems
- Security information management tools

### Audit Goals

- Align with the NIST Cybersecurity Framework (NIST CSF)
- Enhance compliance processes
- Strengthen overall system controls
- Implement least privilege for user management
- Develop comprehensive policies and procedures

---

### Critical Findings

| Control Area                                    | Finding Description                                                                                   | Recommendation                                                                                 |
|------------------------------------------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| **Least Privilege**                            | Not implemented, allowing unnecessary access to sensitive data for some employees.                  | Develop and enforce role-based access controls (RBAC) to ensure employees only have access to the information necessary for their job functions. |
| **Disaster Recovery Plans**                     | No disaster recovery plan is currently in place, posing significant risk during data loss incidents.| Create a comprehensive disaster recovery plan that outlines procedures for maintaining business continuity in the event of a disaster or cyber incident. |
| **Password Policies**                          | Weak policies not adequately protecting user accounts.                                              | Implement a robust password policy that includes requirements for complexity, length, and periodic changes. Consider enforcing multi-factor authentication (MFA) for additional security. |
| **Separation of Duties**                       | Lack of separation increases fraud risk.                                                             | Establish clear role definitions and responsibilities within the organization to ensure that no single individual has control over all aspects of a critical process. |
| **Intrusion Detection System (IDS)**           | Absent; no monitoring of network traffic for suspicious activity.                                    | Invest in an IDS to enhance security monitoring capabilities and enable quick response to potential threats. |
| **Backups**                                    | No regular backup procedures for critical data.                                                    | Implement a regular backup schedule, including offsite backups, to ensure data can be restored in the event of loss or corruption. |
| **Manual Monitoring for Legacy Systems**       | Current processes for managing legacy systems are insufficient.                                     | Establish a structured monitoring and maintenance plan for legacy systems to mitigate vulnerabilities associated with outdated technology. |
| **Password Management System**                 | No centralized system to enforce password policies.                                                 | Deploy a password management solution to store and manage passwords securely, helping to reduce the risk of password-related breaches. |
| **PCI DSS Compliance Issues**                   | - Unauthorized access to credit card information.<br>- Lack of secure storage and processing of credit card information.<br>- Inadequate data encryption procedures.<br>- Weak password management policies. | Implement strict access controls and secure storage for credit card data, develop strong password management policies, and adopt encryption for sensitive data both at rest and in transit. |

---

### Recommendations

Addressing these findings is essential for Botium Toys as it expands its services. Recommendations include:

1. **PCI DSS Compliance**: 
   - Implement strict access controls and secure storage for credit card data.
   - Develop and enforce strong password management policies.
   - Adopt encryption for sensitive data both at rest and in transit.

2. **General Data Protection Regulation (GDPR)**:
   - Strengthen data privacy policies and ensure compliance with data classification and inventory.

3. **Control Enhancements**:
   - Establish disaster recovery plans and implement regular backups.
   - Integrate an intrusion detection system to monitor for threats.

4. **Policy Development**:
   - Create and enforce comprehensive policies for password management, user access, and separation of duties.

---

## Conclusion

This mock security audit report provides a comprehensive examination of Botium Toys' cybersecurity practices, highlighting key areas of vulnerability and opportunities for improvement. Throughout the audit process, I have identified critical controls that are not currently in place, which poses significant risks to the organization's security posture.

Reflecting on this experience, I learned the importance of clarity and thoroughness in evaluating cybersecurity measures. The process of reviewing the existing policies and identifying gaps was eye-opening and has deepened my understanding of the complexities involved in maintaining a secure environment. 

I also recognized the value of implementing structured processes and controls, such as the principle of least privilege, disaster recovery planning, and robust password management. These recommendations are not merely theoretical; they represent real-world necessities for organizations striving to protect sensitive information and maintain compliance with regulatory standards.

Overall, this audit has reinforced my commitment to advancing my knowledge and skills in cybersecurity. It has also highlighted the need for continuous improvement in security practices to adapt to an ever-evolving threat landscape. The lessons learned will be invaluable as I move forward in my professional journey.
