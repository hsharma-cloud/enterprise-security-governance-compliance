# Identity Lifecycle Management

## Purpose

This document defines the lifecycle of user and privileged identities, including provisioning, modification, and deprovisioning. It ensures that access is granted, maintained, and revoked in a controlled and auditable manner.

---

## Scope

This applies to all user accounts, administrative accounts, service accounts, and application identities across on-premises and cloud environments.

---

## Identity Types

| Type | Description |
|------|------------|
| **User Accounts** | Standard user access for employees |
| **Privileged Accounts** | Administrative access with elevated permissions |
| **Service Accounts** | Non-interactive accounts used by applications and services |
| **Application Identities** | Identities used by applications and integrations |

---

## Lifecycle Phases

### 1. Provisioning (Joiner)

- Identity is created upon onboarding
- Access is assigned based on role and job function
- Approval is required from the asset or system owner
- Default access follows least privilege principles

---

### 2. Access Modification (Mover)

- Access is reviewed and updated when roles change
- Privileges are adjusted based on new responsibilities
- Unnecessary access is removed
- Changes require approval and are logged

---

### 3. Deprovisioning (Leaver)

- Access is revoked immediately upon termination or role exit
- Accounts are disabled or removed
- Tokens, sessions, and credentials are invalidated
- Associated access (VPN, email, applications) is revoked

---

## Privileged Access Management

- Privileged accounts are separate from standard user accounts
- Access is granted only when required
- Administrative activity is monitored and logged
- Privileged access is reviewed regularly

---

## Access Control Principles

- Least privilege is enforced across all systems
- Role-based access control is applied where possible
- Strong authentication mechanisms are required for sensitive systems
- Access must be traceable to an individual identity

---

## Identity Governance

- Access reviews are conducted periodically
- Orphaned and inactive accounts are identified and removed
- Access exceptions are documented and approved
- Identity data is synchronized across systems

---

## Monitoring and Logging

- Authentication activity is logged and monitored
- Failed login attempts are tracked
- Privileged actions are audited
- Logs are forwarded to centralized monitoring systems

---

## Evidence

### Identity System
![Active Directory](../screenshots/identity/ad-placeholder.png)

### Access Review
![Access Review](../screenshots/identity/access-review-placeholder.png)

---

## Summary

Identity lifecycle management ensures that access is controlled throughout the entire lifecycle of an identity. It reduces the risk of unauthorized access and provides accountability across all systems.
