# Privileged Access Management

## Purpose

This document defines how privileged access is controlled, monitored, and secured across the environment. It ensures that administrative privileges are granted only when necessary and used in a controlled and auditable manner.

---

## Scope

This applies to all administrative and elevated access across systems, including identity platforms, servers, network devices, security tools, and cloud environments.

---

## Definition of Privileged Access

Privileged access includes any level of access that allows:

- System configuration changes
- User and identity management
- Security control modification
- Access to sensitive data or systems

---

## Privileged Account Types

| Type | Description |
|------|------------|
| **Domain Administrators** | Full control over identity systems |
| **Local Administrators** | Administrative access on individual systems |
| **Service Accounts** | Elevated permissions for applications |
| **Network Administrators** | Access to firewall and network infrastructure |
| **Security Administrators** | Access to SIEM, scanning, and monitoring systems |

---

## Access Control Principles

- Privileged access is separate from standard user accounts
- Access is granted based on role and necessity
- Standing administrative access is minimized
- All privileged actions must be traceable to an individual

---

## Privileged Access Controls

### Account Separation
- Administrative accounts are distinct from user accounts
- Direct use of high-privilege accounts is restricted

### Least Privilege
- Only required permissions are granted
- Access is scoped to specific systems and functions

### Access Approval
- Privileged access requires formal approval
- Approvals are documented and auditable

### Session Control
- Privileged sessions are monitored
- Sensitive actions are logged

---

## Credential Management

- Strong authentication mechanisms are enforced
- Password policies are strictly applied
- Shared credentials are prohibited
- Credential exposure is monitored and remediated

---

## Monitoring and Logging

- All privileged activity is logged
- Logs are forwarded to centralized monitoring systems
- Alerts are generated for suspicious behavior
- Failed and successful administrative actions are tracked

---

## Privileged Access Review

- Privileged accounts are reviewed regularly
- Unused or unnecessary privileges are removed
- Temporary access is revoked after use
- Access certifications are conducted periodically

---

## Risk Considerations

- Privileged accounts are high-value targets
- Misuse can result in full system compromise
- Lack of monitoring increases detection risk
- Shared or unmanaged credentials increase exposure

---

## Evidence

### Administrative Access
![Admin Access](../screenshots/identity/admin-placeholder.png)

### Monitoring
![Monitoring](../screenshots/operations/siem-placeholder.png)

---

## Summary

Privileged access must be tightly controlled, continuously monitored, and regularly reviewed. Strong governance of administrative access reduces the risk of unauthorized changes and ensures accountability across the environment.
