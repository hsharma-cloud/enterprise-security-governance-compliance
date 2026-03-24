# Encryption Standards

## Purpose

This document defines the standards for encrypting data at rest and in transit to protect confidentiality and integrity.

---

## Scope

This applies to all systems, applications, and data across the environment, including on-premises and cloud platforms.

---

## Objectives

- Protect sensitive data from unauthorized access
- Ensure secure transmission of data
- Maintain data integrity
- Align encryption practices across systems

---

## Encryption Principles

- Encryption is applied based on data classification
- Strong, industry-accepted algorithms are used
- Encryption keys are protected and managed securely
- Encryption is enforced for sensitive data

---

## Data at Rest

- Sensitive data must be encrypted when stored
- Encryption applies to:
  - Databases
  - File systems
  - Storage systems
- Access to encrypted data is restricted and controlled

---

## Data in Transit

- All sensitive data must be encrypted during transmission
- Secure protocols are required (e.g., TLS)
- Unencrypted communication is restricted or blocked
- External connections must be secured

---

## Key Management

- Encryption keys are securely stored
- Access to keys is restricted
- Keys are rotated periodically
- Key usage is monitored and logged

---

## Access Control

- Only authorized systems and users can access encrypted data
- Access is based on identity and role
- Privileged access to encryption systems is restricted

---

## Monitoring and Validation

- Encryption status is periodically validated
- Systems are monitored for compliance
- Weak or outdated encryption methods are identified and replaced

---

## Risk Considerations

- Weak encryption exposes sensitive data
- Poor key management compromises security
- Unencrypted transmission increases interception risk
- Lack of monitoring reduces visibility into encryption failures

---

## Evidence

### Secure Communication
![Encryption](../screenshots/data/encryption-placeholder.png)

---

## Summary

Encryption ensures that sensitive data remains protected both at rest and in transit. Strong encryption standards and proper key management are essential for maintaining confidentiality and integrity.
