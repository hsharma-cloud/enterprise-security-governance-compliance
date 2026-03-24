# SIEM Architecture

## Purpose

This document defines the architecture and operation of the centralized security monitoring platform. It enables visibility, detection, and response to security events across the environment.

---

## Scope

This applies to all systems generating security-relevant logs, including identity systems, network devices, servers, endpoints, and applications.

---

## Architecture Overview

The SIEM platform aggregates logs from multiple sources, normalizes data, and enables analysis for detection and response.

Core capabilities:

- Centralized log collection
- Event correlation
- Alerting and detection
- Investigation and analysis

---

## Log Sources

The following systems provide data to the SIEM:

| Source | Description |
|-------|------------|
| Identity Systems | Authentication and access events |
| Firewall | Network traffic and security events |
| Servers | System logs and activity |
| Endpoints | User and system behavior |
| Vulnerability Scanner | Scan results and findings |
| Applications | Application-level events |

---

## Log Collection

- Logs are forwarded from systems to the SIEM
- Standardized formats are used where possible
- Log integrity and completeness are maintained
- Data is retained based on operational and compliance needs

---

## Detection and Alerting

- Alerts are generated based on defined rules and patterns
- Detection includes:
  - Failed authentication attempts
  - Privileged account activity
  - Suspicious network behavior
  - Unusual system activity

---

## Correlation and Analysis

- Events are correlated across multiple sources
- Patterns are identified to detect potential threats
- Context is applied to improve accuracy
- False positives are minimized through tuning

---

## Incident Investigation

- Alerts are reviewed and validated
- Relevant logs are analyzed
- Root cause is identified
- Actions are taken based on findings

---

## Monitoring and Operations

- Continuous monitoring of security events
- Alert triage and prioritization
- Escalation for critical incidents
- Integration with incident response processes

---

## Risk Considerations

- Missing log sources reduce visibility
- Poor correlation leads to missed detections
- Excessive noise impacts response effectiveness
- Lack of monitoring increases dwell time

---

## Evidence

### SIEM Dashboard
![SIEM](../screenshots/operations/siem-placeholder.png)

---

## Summary

The SIEM platform provides centralized visibility into security events and enables detection and response across the environment. Effective monitoring and analysis are critical for identifying and managing threats.
