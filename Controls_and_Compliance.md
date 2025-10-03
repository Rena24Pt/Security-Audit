# Botium Toys: Controls and Compliance Checklist

---

## 🛡️ Controls Assessment

| Control | Implemented? |
|---------|--------------|
| Least Privilege | ❌ No |
| Disaster Recovery Plans | ❌ No |
| Password Policies | ⚠️ Yes (weak) |
| Separation of Duties | ❌ No |
| Firewall | ✅ Yes |
| Intrusion Detection System (IDS) | ❌ No |
| Backups | ❌ No |
| Antivirus Software | ✅ Yes |
| Manual Monitoring of Legacy Systems | ⚠️ Yes (inconsistent) |
| Encryption | ❌ No |
| Password Management System | ❌ No |
| Locks (offices, warehouse) | ✅ Yes |
| CCTV Surveillance | ✅ Yes |
| Fire Detection/Prevention | ✅ Yes |

---

## 📜 Compliance Checklist

### PCI DSS
| Best Practice | Compliant? |
|---------------|------------|
| Only authorized users access credit card data | ❌ No |
| Credit card data stored/processed securely | ❌ No |
| Data encryption for transactions and storage | ❌ No |
| Secure password management policies | ❌ No |

### GDPR
| Best Practice | Compliant? |
|---------------|------------|
| EU customers’ data is kept private/secured | ❌ No |
| Breach notification within 72h | ✅ Yes |
| Data properly classified and inventoried | ❌ No |
| Privacy policies/procedures enforced | ✅ Yes |

### SOC 1 / SOC 2
| Best Practice | Compliant? |
|---------------|------------|
| User access policies established | ❌ No |
| Sensitive data (PII/SPII) confidential/private | ❌ No |
| Data integrity validated and consistent | ✅ Yes |
| Data available to authorized users | ✅ Yes |

---

## 🔑 Recommendations
- Implement **encryption** for credit card and customer data.  
- Enforce **least privilege and separation of duties**.  
- Deploy an **IDS** and establish **backups/DR plan**.  
- Strengthen **password policies** with centralized management.  
- Improve GDPR compliance with **data classification and retention policies**.  
