# Risk Register

## Purpose

This document captures identified risks across the environment, evaluates their potential impact, and defines mitigation strategies. It supports informed decision-making and prioritization of security controls.

---

## Risk Evaluation Criteria

| Level | Description |
|------|------------|
| **High** | Significant impact to business operations or security posture |
| **Medium** | Moderate impact requiring timely mitigation |
| **Low** | Limited impact with minimal disruption |

---

## Risk Register

| ID | Asset | Risk Description | Impact | Likelihood | Risk Level | Mitigation |
|----|------|----------------|--------|-----------|-----------|-----------|
| R-001 | Domain Controller | Unauthorized access to identity system | High | Medium | High | Enforce MFA, restrict admin access, monitor authentication logs |
| R-002 | Firewall | Misconfiguration exposing internal network | High | Medium | High | Implement rule review process and network segmentation |
| R-003 | SIEM | Incomplete log ingestion | High | Medium | High | Ensure log sources are integrated and validated |
| R-004 | Database Server | Data exposure or unauthorized access | High | Medium | High | Apply encryption and access controls |
| R-005 | Endpoints | Malware or unauthorized software | Medium | High | High | Deploy endpoint protection and enforce patching |
| R-006 | Vulnerability Scanner | Unpatched vulnerabilities not detected | Medium | Medium | Medium | Schedule regular scans and reporting |
| R-007 | Web Server | Application vulnerabilities | Medium | Medium | Medium | Conduct regular assessments and patching |
| R-008 | Storage Systems | Data loss or corruption | High | Low | Medium | Implement backups and redundancy |

---

## Risk Treatment Strategy

- **Mitigate**: Apply controls to reduce risk
- **Accept**: Acknowledge risk within acceptable thresholds
- **Transfer**: Shift risk through external mechanisms
- **Avoid**: Eliminate risk by removing exposure

---

## Monitoring and Review

- Risks are reviewed periodically
- High risks are prioritized for remediation
- Changes in infrastructure trigger reassessment
- Risk status is tracked through operational processes

---

## Evidence

### Security Monitoring
![SIEM](../screenshots/operations/siem-placeholder.png)

### Vulnerability Management
![Nessus](../screenshots/vulnerability/nessus-placeholder.png)

---

## Summary

The risk register provides visibility into security risks and ensures that mitigation efforts are aligned with business priorities. It enables structured, consistent, and measurable risk management across the environment.
