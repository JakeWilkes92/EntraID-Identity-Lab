# Entra ID Identity & Security Lab

## Overview
This project demonstrates the architectural implementation of identity governance and access security within Microsoft Entra ID. It covers user provisioning, Zero-Trust access controls, security auditing, and modern authentication hardening.

## Phase 1: Identity Foundation
Managed user provisioning and assigned administrative roles following the principle of least privilege.

## Phase 2: Zero-Trust Access Control
Enforced geographic security through Conditional Access, with administrative 'break-glass' exclusions.

## Phase 3: Monitoring & Verification
Validated policy enforcement via sign-in logs and captured unauthorized access attempts.

## Phase 4: Modern Authentication Standards
Hardened identity security by configuring Phishing-Resistant MFA Authentication Strengths to mitigate credential interception.
* **Evidence:** [Conditional Access Policy Summary](Phase-4/Phase-4-Conditional-Access-Policy-Summary.png)

## Phase 5: Security Posture Hardening
Proactively audited and remediated environment gaps against Microsoft Entra recommendations to enhance overall tenant security hygiene.

| Recommendation | Status | Evidence |
| :--- | :--- | :--- |
| Password Policy (NIST Alignment) | Remediated | [View Evidence](Phase-5/01-Password-Policy.png) |
| Restrict User Consent | Remediated | [View Evidence](Phase-5/02-Consent-Settings.png) |

