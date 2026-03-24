# Data Loss Prevention (DLP) Strategy

## Purpose

This document defines the strategy for preventing unauthorized access, transfer, or exposure of sensitive data across the environment.

---

## Scope

This applies to all data in use, in transit, and at rest across systems, endpoints, and network channels.

---

## Objectives

- Prevent unauthorized data exfiltration
- Protect sensitive and critical data
- Monitor data movement across systems
- Enforce policies for data handling and transfer

---

## DLP Approach

The strategy focuses on identifying sensitive data and controlling how it is accessed and transferred.

Key elements:

- Data classification awareness
- Monitoring of data movement
- Enforcement of access and transfer policies
- Detection of abnormal data behavior

---

## Data Protection Controls

### Endpoint Controls

- Monitor data copied to external devices
- Restrict unauthorized file transfers
- Control use of removable media

---

### Network Controls

- Monitor outbound traffic for sensitive data
- Restrict unauthorized data transfers
- Inspect data leaving the network

---

### Access Controls

- Limit access to sensitive data based on role
- Enforce least privilege access
- Monitor access to critical data stores

---

## Monitoring and Detection

- Data access and transfer activities are logged
- Alerts are generated for suspicious behavior
- Abnormal data movement patterns are investigated
- Logs are analyzed through centralized monitoring systems

---

## Policy Enforcement

- Policies define acceptable data handling practices
- Violations are detected and acted upon
- Enforcement includes blocking, alerting, or restricting actions

---

## Risk Considerations

- Unauthorized data transfer leads to data exposure
- Lack of monitoring reduces visibility into data movement
- Weak access controls increase risk of misuse
- Inadequate enforcement allows policy violations

---

## Evidence

### Data Monitoring
![DLP](../screenshots/data/dlp-placeholder.png)

---

## Summary

A DLP strategy ensures that sensitive data is protected from unauthorized access and transfer. Monitoring, policy enforcement, and access control reduce the risk of data exposure and support secure data handling practices.
