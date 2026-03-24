# Zero Trust Architecture Model

## Purpose

This document defines the Zero Trust model used to secure access to systems, applications, and data. It enforces continuous verification of identity and access, regardless of network location.

---

## Core Principles

- Never trust, always verify
- Enforce least privilege access
- Assume breach and limit impact
- Verify explicitly using multiple signals
- Continuously monitor and validate access

---

## Architecture Overview

The environment is designed to enforce access decisions based on identity, device, and context rather than network location.

### Key Components

- Identity provider (central authentication system)
- Access control mechanisms
- Network segmentation controls
- Monitoring and logging systems
- Endpoint security controls

---

## Identity-Centric Access

- All access requests are authenticated and authorized
- Identity is the primary control plane
- Multi-factor authentication is required for sensitive systems
- Access decisions are based on user role and context

---

## Device and Endpoint Validation

- Only trusted and compliant systems are allowed access
- Endpoint security controls are enforced
- Systems are monitored for security posture
- Unauthorized or unmanaged devices are restricted

---

## Network Segmentation

- Systems are segmented based on function and sensitivity
- Access between segments is controlled and monitored
- Internal systems are not inherently trusted
- Lateral movement is restricted

---

## Application Access Control

- Access to applications is controlled at the identity level
- Authentication is required regardless of network location
- Direct access to backend systems is restricted

---

## Monitoring and Visibility

- All access attempts are logged
- Authentication and authorization events are monitored
- Suspicious behavior triggers alerts
- Logs are centralized for analysis

---

## Enforcement Strategy

| Control Area | Implementation |
|-------------|--------------|
| Identity | Centralized authentication and role-based access |
| Network | Segmentation and controlled communication paths |
| Endpoint | Security controls and posture validation |
| Monitoring | Centralized logging and alerting |

---

## Risk Considerations

- Implicit trust increases attack surface
- Lack of segmentation enables lateral movement
- Weak identity controls lead to unauthorized access
- Limited visibility reduces detection capability

---

## Evidence

### Network Segmentation
![Network](../screenshots/network/network-placeholder.png)

### Identity and Access
![Identity](../screenshots/identity/ad-placeholder.png)

---

## Summary

Zero Trust enforces strict access control by verifying every request and minimizing trust across the environment. It reduces the risk of unauthorized access and limits the impact of potential compromises.
