# Botium Toys: Internal Security Audit Report

---

## 📌 Scope and Goals of the Audit

**Scope:**  
The scope of this audit is defined as the entire security program at Botium Toys.  
This includes their assets like employee equipment and devices, their internal network, and their systems. The audit reviews Botium Toys’ assets as well as the controls and compliance practices currently in place.  

**Goals:**  
- Assess existing assets and risks.  
- Complete the controls and compliance checklist.  
- Determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture.  

---

## 🖥️ Current Assets

Assets managed by the IT Department include:  
- On-premises equipment for in-office business needs.  
- Employee equipment: desktops, laptops, smartphones, remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.  
- Storefront products available for retail sale on site and online, stored in the adjoining warehouse.  
- Management of systems, software, and services: accounting, telecommunications, databases, security, e-commerce, and inventory management.  
- Internet access and internal network.  
- Data retention and storage.  
- Legacy system maintenance: end-of-life systems requiring human monitoring.  

---

## ⚠️ Risk Assessment

**Risk Description:**  
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.  

**Control Best Practices:**  
Following the first function of the NIST CSF, *Identify*, Botium Toys must dedicate resources to properly identify and classify assets. This will allow the organization to manage them more effectively and determine the impact of asset loss on business continuity.  

**Risk Score:**  
On a scale of 1 to 10, the risk score is **8 (High)**, due to lack of controls and adherence to compliance best practices.  

**Additional Comments:**  
- All employees currently have access to internal data, including cardholder data and customers’ PII/SPII.  
- Encryption is not in place for credit card information that is processed, transmitted, or stored.  
- Least privilege and separation of duties are not implemented.  
- Firewall, antivirus, and data integrity controls exist.  
- No intrusion detection system (IDS) is in place.  
- No backups or disaster recovery plans exist.  
- Password policy is weak and not enforced with centralized management.  
- Privacy policies exist, and GDPR breach notification within 72h is planned.  
- Physical security (locks, CCTV, fire prevention) is sufficient.  

---

## 🛡️ Controls Assessment

### Administrative Controls
| Control | Type & Explanation | Implemented? | Priority |
|---------|--------------------|--------------|----------|
| Password Policy | Preventative – enforce complexity to reduce brute force/dictionary attacks. | Weak (not enforced) | High |
| Access Control (Least Privilege) | Preventative – restrict access to only what is necessary for job roles. | No | High |
| Separation of Duties | Preventative – reduce risk of fraud/misuse. | No | Medium |
| Security Awareness Training | Deterrent – reduce risk of phishing and social engineering. | No | Medium |
| Incident Response Plan | Corrective – clear steps for detecting and responding to incidents. | No | High |

---

### Technical Controls
| Control | Type & Explanation | Implemented? | Priority |
|---------|--------------------|--------------|----------|
| Firewall | Preventative – filters traffic based on rules. | Yes | Medium |
| Antivirus/Antimalware | Detective/Corrective – detects and removes malware. | Yes | Medium |
| Intrusion Detection System (IDS) | Detective – identifies anomalous or malicious traffic. | No | High |
| Encryption | Preventative – protects confidentiality of sensitive data. | No | High |
| Centralized Password Management | Preventative – enforces password policy automatically. | No | Medium |
| Backups & Disaster Recovery | Corrective – restores data after incidents. | No | High |

---

### Physical Controls
| Control | Type & Explanation | Implemented? | Priority |
|---------|--------------------|--------------|----------|
| Locks (doors, server rooms) | Preventative – restricts physical access. | Yes | Medium |
| CCTV Surveillance | Preventative/Detective – monitors and records activity. | Yes | Medium |
| Fire Detection/Prevention | Preventative – protects facilities and assets. | Yes | Medium |
| Visitor Access Logs/Badges | Detective – tracks individuals entering sensitive areas. | No | Medium |

---

## ✅ Compliance Checklist

### GDPR (General Data Protection Regulation)  
- Requirement: Protect EU citizens’ personal data; notify breaches within 72h.  
- Status: Partial compliance – breach notification plan exists, but encryption and access controls are missing.  
- Action: Encrypt customer data, enforce least privilege, and establish strict data retention policies.  

### PCI DSS (Payment Card Industry Data Security Standard)  
- Requirement: Securely store, process, and transmit credit card data.  
- Status: Non-compliant – cardholder data is stored unencrypted, access controls missing.  
- Action: Implement encryption/tokenization, restrict access, deploy IDS, monitor logs.  

### U.S. and International Standards  
- HIPAA, SOX not directly applicable to Botium Toys, but industry best practices should be followed to align with international security expectations.  

---

## 📊 Key Recommendations

1. Implement **encryption** for all sensitive and cardholder data.  
2. Deploy an **Intrusion Detection System (IDS)** for real-time monitoring.  
3. Enforce **least privilege and separation of duties** across all employees.  
4. Strengthen and enforce the **password policy** with centralized management.  
5. Establish **regular backups** and a **disaster recovery plan**.  
6. Conduct **mandatory security awareness training** for all staff.  
7. Ensure **compliance with GDPR and PCI DSS** to avoid heavy fines.  
8. Introduce **incident response procedures** with clear escalation paths.  

---

## 📌 About this Project
This project was created as part of the **Google Cybersecurity Professional Certificate**.  
While the scenario and initial risk assessment were provided as part of the course, the **controls assessment, compliance checklist, and recommendations** were developed to complete the audit and strengthen Botium Toys’ security posture.  
