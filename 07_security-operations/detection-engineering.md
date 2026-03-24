# Detection Engineering

## Purpose

This document defines the approach for designing, implementing, and maintaining detection rules to identify suspicious and malicious activity across the environment.

---

## Scope

This applies to all detection logic within the monitoring platform, including rules, alerts, and correlation mechanisms across identity, network, and system activity.

---

## Objectives

- Detect unauthorized and suspicious activity
- Reduce false positives and improve signal quality
- Provide actionable alerts for investigation
- Continuously improve detection coverage

---

## Detection Strategy

Detections are developed based on:

- Known threat behaviors
- High-risk activities
- Critical system monitoring
- Anomalous patterns in user or system activity

---

## Detection Categories

| Category | Description |
|---------|------------|
| **Authentication Events** | Failed logins, unusual login patterns |
| **Privileged Activity** | Administrative actions and access changes |
| **Network Activity** | Suspicious connections or traffic patterns |
| **System Changes** | Configuration or file modifications |
| **Vulnerability Exploitation** | Indicators of exploit attempts |

---

## Detection Development Process

### 1. Use Case Identification

- Identify high-risk scenarios
- Focus on critical systems and assets

---

### 2. Rule Creation

- Define logic for detecting suspicious behavior
- Use multiple data sources where possible
- Ensure alerts are meaningful and actionable

---

### 3. Testing and Validation

- Validate detection against expected behavior
- Simulate scenarios where applicable
- Ensure accuracy before deployment

---

### 4. Deployment

- Enable detection rules in the monitoring platform
- Integrate with alerting and response workflows

---

### 5. Tuning and Optimization

- Reduce false positives
- Adjust thresholds and logic
- Improve detection accuracy over time

---

## Example Detection Use Cases

| Use Case | Description |
|---------|------------|
| Multiple Failed Logins | Potential brute-force attempt |
| Privileged Account Usage | Administrative activity outside normal patterns |
| New Account Creation | Unauthorized account provisioning |
| Unusual Network Traffic | Potential lateral movement or data exfiltration |

---

## Monitoring and Maintenance

- Detection rules are reviewed regularly
- Ineffective detections are updated or removed
- New threats are incorporated into detection logic
- Coverage is expanded based on risk and environment changes

---

## Risk Considerations

- Poorly tuned detections generate excessive noise
- Missing detections increase exposure to threats
- Lack of maintenance reduces effectiveness
- Over-reliance on single data sources limits visibility

---

## Evidence

### Detection Alerts
![Detection](../screenshots/operations/detection-placeholder.png)

---

## Summary

Detection engineering ensures that security monitoring is effective, accurate, and actionable. Continuous improvement of detection logic enhances the ability to identify and respond to threats.
