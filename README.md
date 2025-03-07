# Risk Management Plan for DHA Enterprise Inc.  

## Project Overview  
This project presents a **comprehensive Risk Management Plan** for **DHA Enterprise Inc. (DHAEI), a growing software development company**. The plan outlines a **risk assessment framework**, evaluates critical **cybersecurity risks**, and provides **mitigation strategies** based on **ISO 31000 and the NIST Risk Management Framework (RMF)**.  

By implementing this risk management approach, DHAEI aims to **protect sensitive data, ensure business continuity, manage third-party risks, and strengthen security awareness across the organization**.  

## Objectives  
- **Identify and assess** cybersecurity risks that could impact DHAEI’s operations.  
- **Analyze risk likelihood and impact** based on the **CIA triad (Confidentiality, Integrity, Availability)**.  
- **Develop a risk treatment plan** aligned with **ISO 31000 and NIST RMF**.  
- **Recommend security strategies** such as **MFA, encryption, network segmentation, and employee training**.  
- **Ensure compliance** with industry security standards and best practices.  

## Frameworks & Methodologies Used  
- **NIST Risk Management Framework (RMF)**  
- **ISO 31000: Risk Management Guidelines**  
- **CISA Security Recommendations**  
- **MITRE ATT&CK Framework (for Threat Modeling)**  

## Key Risks Identified  
The following **critical cybersecurity risks** were identified and assessed based on **likelihood and impact**:  

| **Risk**                           | **Confidentiality** | **Integrity** | **Availability** | **Likelihood (0-5)** | **Impact (0-10)** |  
|------------------------------------|--------------------|--------------|----------------|------------------|---------------|  
| **Unauthorized Access (Insider/External Threats)** | 🔴 High | 🟡 Medium | 🟡 Medium | **4** | **8** |  
| **Data Breach or Loss**            | 🔴 High | 🟡 Medium | 🟡 Medium | **3** | **9** |  
| **System Downtime or Service Disruption** | 🟡 Medium | 🟡 Medium | 🔴 High | **4** | **7** |  
| **Phishing & Social Engineering Attacks** | 🔴 High | 🟡 Medium | 🟡 Medium | **5** | **6** |  
| **Third-Party Vendor Risks**       | 🔴 High | 🟡 Medium | 🟡 Medium | **4** | **8** |  
| **Ransomware or Malware Attacks**  | 🔴 High | 🟡 Medium | 🔴 High | **4** | **9** |  

## Risk Treatment Strategies  
DHAEI implemented **four primary risk treatment approaches**: **Avoidance, Reduction, Sharing, and Retention**.  

### **1 Unauthorized Access (Insider Threats & External Breaches)**  
✔ **Implemented Multi-Factor Authentication (MFA)** to strengthen authentication security.  
✔ **Enforced Least Privilege Access (LPA)** and **Role-Based Access Control (RBAC)**.  
✔ **Established real-time monitoring** for detecting abnormal login attempts.  

### **2 Data Breach or Loss**  
✔ **Encrypted sensitive data at rest and in transit** using **AES-256 and TLS 1.2+**.  
✔ **Implemented a Data Loss Prevention (DLP) system** to prevent unauthorized data transfers.  
✔ **Strengthened backup and disaster recovery strategies** for secure data storage.  

### **3 System Downtime & Service Disruption**  
✔ **Established redundancy and failover mechanisms** to ensure high availability.  
✔ **Deployed system monitoring tools** to proactively detect system failures.  
✔ **Performed regular disaster recovery drills** to test failover readiness.  

### **4 Phishing & Social Engineering Attacks**  
✔ **Conducted phishing simulation training** for employees.  
✔ **Implemented AI-powered email filtering** to block malicious phishing attempts.  
✔ **Developed a reporting protocol** for users to flag suspicious emails.  

### **5 Third-Party Vendor Risks**  
✔ **Enforced strict vendor security policies** and **performed security assessments**.  
✔ **Added security clauses to vendor contracts**, ensuring compliance with DHAEI’s security requirements.  
✔ **Monitored vendor access logs** to detect unauthorized activities.  

### **6 Ransomware & Malware Attacks**  
✔ **Deployed endpoint protection software** with advanced threat detection capabilities.  
✔ **Established network segmentation** to **contain ransomware spread**.  
✔ **Implemented offline backups** to ensure data recovery after an attack.  

## Implementation & Continuous Monitoring  
DHAEI’s risk management approach follows a **continuous improvement cycle**:  
1 **Assess Risks** – Regularly evaluate **new and evolving threats**.  
2 **Implement Controls** – Apply risk treatment measures **based on priority**.  
3 **Monitor & Detect** – Use **SIEM, IDS/IPS, and endpoint monitoring** for early threat detection.  
4 **Improve & Adapt** – Conduct **risk assessments** to adjust security strategies.  

## Key Takeaways  
- **Risk management is an ongoing process.** Regular assessments help adapt to evolving threats.  
- **Cybersecurity awareness training significantly reduces human-related risks.**  
- **Strong access controls and encryption protect critical data from unauthorized access.**  
- **Vendor risk management is crucial**—third parties should meet **DHAEI's security standards**.  
- **A well-structured incident response plan** ensures rapid containment and mitigation of cyber threats.  

## Supporting Files  
**Risk Assessment Reports, Policy Documents, and Security Implementation Plans** are included in this repository (sanitized).  

