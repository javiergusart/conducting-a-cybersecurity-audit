# Navigating Controls and Compliance: Identifying Security Gaps and Compliance Issues in a Mock Audit.

Cybersecurity is more than just preventing hackers from getting into your network. It’s about controls, compliance, and risk management—a trifecta that ensures companies protect not only their data but their reputation. As someone new to the field, I recently took a deep dive into creating a mock Controls and Compliance Checklist for a fictional company, **Botium Toys**, and I wanted to share my experience, insights, and what I learned along the way.

## A Quick Overview of Botium Toys

Botium Toys, a mid-sized toy retailer, faces multiple cybersecurity challenges. They store sensitive customer data (like credit card information and personally identifiable information, or PII) on-premises, while managing remote workstations and retail operations both online and offline. The company has critical assets, from employee devices to internal networks, but their security posture is far from where it needs to be. My task was to assess their current controls and compliance, identify gaps, and make recommendations on how to mitigate these risks.

## Understanding the Scope and Goals

Before jumping into any cybersecurity audit, you need a clear understanding of what you're dealing with. For Botium Toys, the **scope** included everything: their internal network, data storage, employee devices, and storefront products. The **goal**? To evaluate existing security measures and determine which industry best practices needed to be implemented to improve Botium Toys’ overall security posture. This was outlined clearly in the **Scope, Goals, and Risk Assessment Report**.

## The Controls and Compliance Checklist: Breaking it Down

When people talk about “controls,” they’re referring to measures put in place to prevent, detect, or correct security risks. “Compliance,” on the other hand, deals with following legal and regulatory standards (think GDPR for E.U. customers or PCI DSS for handling credit card information). The **Controls and Compliance Checklist** is a tool that helps evaluate whether a company is adhering to these standards and what measures they have in place.

Here’s where Botium Toys fell short—and how we can fix it:

### 1. Lack of Access Controls

Every employee at Botium Toys could access sensitive customer data, which is a big red flag. The concept of **least privilege** was missing—an important control that limits data access only to those who need it to perform their job. This would reduce the risk of insider threats and prevent potential breaches. The solution here is simple: Implement **role-based access control (RBAC)** to ensure only authorized personnel can access sensitive information.

### 2. No Encryption for Credit Card Data

Perhaps the most glaring issue was that customer credit card information wasn’t encrypted at all. In today’s cybersecurity landscape, encryption is non-negotiable, especially for payment information. Botium Toys needs to encrypt data both **at rest** and **in transit**. Without this, even a minor breach could lead to devastating consequences for customers and the company itself.

### 3. Weak Password Policies

Weak password policies are often the Achilles' heel of many organizations, and Botium Toys was no exception. Their password requirements were outdated, failing to meet the complexity needed to ward off brute force attacks. Introducing **multi-factor authentication (MFA)** and stronger, regularly enforced password policies would immediately tighten up this weak spot.

### 4. No Intrusion Detection System (IDS)

Botium Toys had a firewall and antivirus software in place, but that’s not enough. Without an **Intrusion Detection System (IDS)**, the company had no way of knowing if they were already under attack. Installing an IDS would give them visibility into potential threats and allow them to respond quickly.

### 5. No Backups or Disaster Recovery Plans

Shockingly, Botium Toys didn’t have a **disaster recovery plan** (DRP) or regular backups of critical data. This is a huge risk for any business—especially in an era where ransomware attacks are increasingly common. I recommended that Botium Toys develop a DRP immediately and set up **regular backups** to ensure business continuity in the event of a cyberattack or system failure.

## Compliance Issues

Now, let’s talk about compliance. **GDPR** and **PCI DSS** are two major regulations that Botium Toys needed to comply with. They did have a breach notification plan in place for E.U. customers, ensuring that they'd be notified within 72 hours if their data was compromised—a key GDPR requirement. However, they failed to meet several other compliance best practices:

- **Credit card information** wasn’t stored in a secure environment.
- **PII/SPII (Sensitive Personally Identifiable Information)** wasn’t sufficiently protected.
- **Data encryption** and **user access policies** were missing.

Failing to meet these regulations could lead to hefty fines and legal penalties, something no company wants to deal with.

## Risk Management: Prioritizing the Gaps

Cybersecurity risk is all about identifying what can go wrong, how likely it is to happen, and the impact if it does. In Botium Toys’ case, the **risk score** was quite high—an 8 out of 10. This was largely due to their lack of controls around data access, encryption, and backups. The **potential for fines and data loss** was significant.

## Key Takeaways and Recommendations

1. **Implement Role-Based Access Controls**: Limit access to sensitive data and systems by introducing least privilege policies. Only those who need access should have it.

2. **Encrypt Sensitive Data**: Protect customer credit card information and PII with strong encryption methods at every stage of the data lifecycle—whether it’s being stored, transmitted, or processed.

3. **Strengthen Password and Authentication Policies**: Introduce a robust password policy that meets current standards and implement multi-factor authentication to add another layer of security.

4. **Set Up an IDS and Backups**: Install an Intrusion Detection System to monitor for potential threats and set up regular backups and a disaster recovery plan to ensure business continuity.

5. **Adhere to Compliance Standards**: Get up to speed with PCI DSS and GDPR requirements. Botium Toys must ensure that data is protected and breaches are handled according to regulations to avoid fines.

## Wrapping Up

Working on the Controls and Compliance Checklist for Botium Toys was eye-opening. It highlighted the importance of not only having controls in place but also ensuring compliance with regulations to avoid both security risks and legal consequences. These gaps aren’t just theoretical—they represent real risks that could affect any organization.

For anyone starting out in cybersecurity like I am, this kind of hands-on experience is invaluable. It’s not just about learning the technical jargon; it’s about understanding how everything connects to protect an organization from internal and external threats. Controls and compliance are at the heart of that protection, and I’m excited to keep building my knowledge in this area.
