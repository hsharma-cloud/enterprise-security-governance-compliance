# Network Segmentation Model

## Purpose

This document defines how network segmentation is implemented to control communication between systems and reduce the risk of unauthorized access and lateral movement.

---

## Objectives

* Limit exposure between systems
* Control communication paths
* Reduce impact of potential compromise
* Improve visibility and monitoring

---

## Segmentation Approach

The network is divided into logical zones based on system function and sensitivity.

Key principles:

* Systems are grouped by role and function
* Communication is explicitly defined and controlled
* Default access between segments is restricted
* Monitoring is applied across all segments

---

## Network Zones

| Zone                    | Description                               |
| ----------------------- | ----------------------------------------- |
| **External / Internet** | Untrusted external network                |
| **Perimeter (DMZ)**     | Public-facing systems                     |
| **Internal Network**    | Core systems and services                 |
| **Management Network**  | Administrative access and control systems |
| **Security Zone**       | Monitoring and security tools             |

---

## Segmentation Controls

* Firewall rules control communication between zones
* Only required ports and protocols are allowed
* Default deny policy is enforced
* Administrative access is restricted to management networks

---

## Communication Model

* External access is limited to designated systems
* Internal systems do not communicate freely
* Sensitive systems have restricted access paths
* Cross-zone communication is monitored and logged

---

## Administrative Access

* Administrative access is limited to the management network
* Direct access to critical systems is restricted
* Privileged access is controlled and monitored

---

## Monitoring and Visibility

* Network traffic between zones is logged
* Suspicious communication is detected and investigated
* Logs are integrated with centralized monitoring systems

---

## Risk Considerations

* Flat networks increase risk of lateral movement
* Overly permissive rules expose systems
* Lack of segmentation increases impact of compromise
* Unmonitored traffic reduces visibility

---

## Summary

Network segmentation reduces risk by controlling communication between systems and limiting exposure. A structured segmentation model improves security, visibility, and containment of potential threats.

