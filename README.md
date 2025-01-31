# **Botium Toys Security Audit Report**  

## **1. Introduction**  
This repository contains the security audit report for **Botium Toys**, evaluating their security posture, identifying risks, assessing security controls, and providing compliance checks. The audit follows industry standards such as **NIST CSF, PCI DSS, GDPR, and SOC 2**, ensuring that Botium Toys strengthens its security measures to mitigate potential threats.  

## **2. Scenario**  
Botium Toys has an established IT infrastructure but lacks essential security controls and compliance adherence. The audit scope covers **on-premises equipment, employee devices, internal networks, data storage, and legacy systems**. The key issues identified include:  
- Unrestricted access to sensitive customer data.  
- Lack of encryption for credit card information.  
- No **intrusion detection system (IDS)** or **disaster recovery plans**.  
- Weak password policies and lack of centralized password management.  
- Absence of **Least Privilege** and **Separation of Duties** principles.  

The audit aims to identify these security gaps and recommend necessary improvements.  

## **3. Security Audit Workflow**  
The security audit was conducted following these key steps:  
1. **Asset Identification** – Identified IT assets and evaluated their security controls.  
2. **Risk Assessment** – Assessed potential threats and assigned a **risk score of 8/10**.  
3. **Controls Evaluation** – Reviewed existing security controls and identified gaps.  
4. **Compliance Check** – Assessed adherence to PCI DSS, GDPR, and SOC 2 requirements.  
5. **Recommendations** – Proposed improvements to enhance security.  

## **4. Control Assessment**  
The following security controls were evaluated:  

| Security Control          | Implemented? |
|--------------------------|-------------|
| Least Privilege          | ❌ No       |
| Disaster Recovery Plan   | ❌ No       |
| Password Policies        | ❌ No       |
| Separation of Duties     | ❌ No       |
| Firewall                | ✅ Yes      |
| Intrusion Detection (IDS)| ❌ No       |
| Backups                 | ❌ No       |
| Antivirus Software      | ✅ Yes      |
| Legacy System Monitoring| ❌ No       |
| Encryption              | ❌ No       |
| Password Management System | ❌ No  |
| Physical Security (Locks, CCTV) | ✅ Yes  |

## **5. Compliance Check**  
Botium Toys was evaluated against major compliance standards:  

### **PCI DSS Compliance**  
- ❌ No access restrictions for credit card data.  
- ❌ No encryption for cardholder data.  
- ❌ Weak password policies.  

### **GDPR Compliance**  
- ✅ A data breach notification plan exists.  
- ❌ Lack of **proper asset classification** and **data protection policies**.  

### **SOC 2 Compliance**  
- ❌ No established user access policies.  
- ❌ No **data integrity measures** to ensure consistency and accuracy.  
- ❌ No **Least Privilege enforcement**.  

## **6. Recommendations**  
To improve security and compliance, Botium Toys must implement the following:  
- **Apply Least Privilege and Separation of Duties** to limit unauthorized access.  
- **Implement strong password policies and a password management system**.  
- **Adopt encryption** to secure sensitive customer and financial data.  
- **Deploy an Intrusion Detection System (IDS)** for proactive threat monitoring.  
- **Develop a disaster recovery plan** and establish routine data backups.  
- **Ensure compliance with PCI DSS, GDPR, and SOC 2** by restricting access, encrypting data, and properly classifying assets.  

By implementing these controls, Botium Toys will significantly reduce security risks and enhance compliance with industry standards.  
