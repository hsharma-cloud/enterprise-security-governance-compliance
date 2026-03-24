# Network Architecture

## Purpose

This document defines the network architecture, segmentation model, and traffic control strategy used to protect systems and data across the environment.

---

## Architecture Overview

The network is designed with segmentation and controlled communication paths to reduce risk and limit unauthorized access.

Core design principles:

- Segmentation based on system function
- Controlled access between network zones
- Centralized monitoring of network activity
- Restricted administrative access

---

## Network Zones

The environment is divided into logical network segments:

| Zone | Description |
|------|------------|
| **External / Internet** | Untrusted network |
| **Perimeter (DMZ)** | Public-facing services |
| **Internal Network** | Core business systems |
| **Management Network** | Administrative and control systems |
| **Security Zone** | Monitoring and security tools |

---

## System Placement

| System | Network Zone |
|--------|-------------|
| Firewall | Perimeter |
| Web Server | DMZ |
| Domain Controller | Internal |
| Database Server | Internal |
| Storage Systems | Internal |
| SIEM Platform | Security Zone |
| Vulnerability Scanner | Security Zone |
| Endpoints | Internal |
| Administrative Systems | Management Network |

---

## Segmentation Strategy

- Internal systems are isolated from public-facing services
- Sensitive systems are restricted to specific network zones
- Communication between zones is explicitly controlled
- Administrative access is limited to the management network

---

## Traffic Control

- All inbound and outbound traffic is filtered through the firewall
- Only required ports and protocols are allowed
- Default deny policy is enforced
- Internal traffic is monitored and controlled

---

## Remote Access

- Remote access is restricted and secured
- Administrative access is limited and monitored
- External connections are authenticated and controlled

---

## Monitoring and Visibility

- Network traffic is logged and monitored
- Security events are forwarded to centralized monitoring systems
- Suspicious activity is detected and investigated
- Logs are retained for analysis and auditing

---

## Risk Considerations

- Flat networks increase risk of lateral movement
- Misconfigured firewall rules expose internal systems
- Unmonitored traffic reduces visibility
- Weak segmentation increases impact of compromise

---

## Evidence

### Firewall Configuration
![Firewall](../screenshots/network/firewall-placeholder.png)

### Network Segmentation
![Segmentation](../screenshots/network/network-placeholder.png)

---

## Summary

The network architecture enforces segmentation, controlled communication, and centralized monitoring. This reduces exposure, limits lateral movement, and strengthens overall security posture.
