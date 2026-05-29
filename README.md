# Entra ID Identity & Security Lab

## Overview
This project demonstrates the architectural implementation of identity governance and access security within Microsoft Entra ID.

## Phase 1: Identity Foundation
Managed user provisioning and assigned administrative roles following the principle of least privilege.
* **User Directory:** ![User Listing](Phase-1/01-User-Directory-Listing.png)
* **RBAC Implementation:** ![Admin Assignment](Phase-1/02-Global-Admin-Assignment.png)

## Phase 2: Zero-Trust Access Control
Implemented a custom Conditional Access policy to enforce geographic restrictions, specifically blocking access from outside the United Kingdom to mitigate regional credential threats.
* **Policy Deployment:** ![Conditional Access Policies](Phase-2/image_e6b566.png)

## Phase 3: Security Posture & Continuous Improvement
Conducted an audit of the environment using Entra recommendations to harden the tenant security posture.
* **Audit Findings:** ![Security Recommendations](Phase-3/image_d872bf.png)

## Reflections & Lessons Learned
* **Operational Security:** Learned to manage administrative access via 'break-glass' accounts to prevent lockout during policy deployment.
* **Continuous Monitoring:** Recognized that security is not a static setup; it requires constant review of identity recommendations to remediate vulnerabilities such as legacy authentication and privilege mismanagement.


## Phase 2: Security & Conditional Access
I implemented a geographic restriction policy to block all access outside of the United Kingdom.

### Evidence
![Policy Network Exclusion](Phase-2/1.%20Location%20Exclusion.png)
![Policy Block Control](Phase-2/2.%20Block%20Access.png)
