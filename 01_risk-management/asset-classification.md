# Asset Classification Standard

## Purpose

This document defines how assets are identified, classified, and protected across the enterprise. Classification ensures that security controls are applied based on business impact, sensitivity, and operational importance.

---

## Scope

This standard applies to all systems, applications, data, and infrastructure components within the environment, including on-premises and cloud platforms.

---

## Asset Inventory

The environment consists of the following core systems:

### Identity and Access Systems
- Active Directory Domain Controller

### Network and Security Infrastructure
- Firewall platform
- Security monitoring platform (SIEM)
- Vulnerability management system

### Servers and Applications
- Web server
- Database server
- Storage systems

### Endpoints and Supporting Systems
- User endpoints
- Administrative systems
- Security testing systems

### Cloud Platforms
- AWS infrastructure
- Azure infrastructure

All assets are subject to classification and control requirements defined in this standard.

---

## Classification Levels

| Level | Description |
|------|------------|
| **Critical** | Systems essential to security or business operations. Loss or compromise has severe impact. |
| **High** | Systems containing sensitive or important data. Impact is significant. |
| **Medium** | Systems supporting operations with moderate impact if compromised. |
| **Low** | Systems with minimal business impact or used for testing purposes. |

---

## Asset Ownership

Every asset must have clearly defined ownership:

| Role | Responsibility |
|-----|--------------|
| **Asset Owner** | Accountable for classification and business value |
| **System Owner** | Responsible for operation and maintenance |
| **Security Team** | Responsible for control implementation and monitoring |
| **Users** | Responsible for appropriate usage |

---

## Asset Classification

| Asset | Category | Classification | Owner |
|------|---------|---------------|------|
| Domain Controller | Identity | Critical | IT / Security |
| Firewall | Network | Critical | Network Team |
| SIEM Platform | Security | Critical | Security Team |
| Database Server | Data | High | Data Owner |
| Storage System | Data | High | Infrastructure |
| Web Server | Application | Medium | Application Team |
| Vulnerability Scanner | Security | Medium | Security Team |
| Endpoints | User Systems | Medium | IT |
| Security Testing System | Security | Low | Security Team |

---

## Data Classification

| Data Type | Classification |
|----------|---------------|
| Authentication Data | Critical |
| Security Logs | High |
| Application Data | High |
| Public Content | Low |

---

## Control Requirements

| Classification | Control Requirements |
|--------------|---------------------|
| Critical | Strong access control, monitoring, segmentation, multi-factor authentication |
| High | Encryption, access control, logging |
| Medium | Standard security controls and patching |
| Low | Baseline security controls |

---

## Monitoring and Maintenance

- Asset inventory must be reviewed regularly
- Classification must be updated based on changes in business impact
- Unauthorized assets must be identified and removed
- All critical assets must be continuously monitored

---

## Evidence

### Identity System
![Identity](../screenshots/identity/ad-placeholder.png)

### Asset Inventory
![Asset](../screenshots/risk/asset-placeholder.png)

---

## Summary

Asset classification ensures that security controls are applied consistently and proportionally based on the importance of each system. It provides the foundation for access control, monitoring, and risk management across the environment.
