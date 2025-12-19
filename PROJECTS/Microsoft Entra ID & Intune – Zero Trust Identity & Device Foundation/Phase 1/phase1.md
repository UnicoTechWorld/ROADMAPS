# Phase 1 – Identity Foundation

## Overview

Phase 1 focuses on building a **clean, secure, and scalable identity foundation** in Microsoft Entra ID.  
This phase establishes the baseline required for any modern cloud environment before advanced security, device management, or Conditional Access can be safely implemented.

The work in this phase reflects how an organization moves away from ad-hoc identity management toward a **structured, least-privilege, and automation-ready identity model**.

---

## Objective of Phase 1

The primary goal of Phase 1 is to ensure that:

- Identities are consistently created and managed  
- Access is group-based instead of user-based  
- Security is enabled at the identity level  
- Administrative privileges are correctly scoped  
- Internal and external users are clearly separated  

This phase lays the groundwork for Zero Trust by ensuring that **identity is reliable, structured, and secure**.

---

## Problems Addressed

Before this phase, the environment suffered from common early-stage identity issues:

- No clear distinction between test and production objects  
- Inconsistent user naming and missing metadata  
- Manual license assignment per user  
- Overuse of Global Administrator privileges  
- No enforced MFA or self-service password reset  
- Uncontrolled handling of guest users  

These issues create operational overhead and increase security risk as an organization grows.

---

## What Was Implemented

During Phase 1, the following foundations were implemented:

### Tenant Preparation & Lab Separation
- Clear separation between test and non-test objects  
- Naming conventions using a `LAB_` prefix  
- Dedicated test users and admin accounts  

### Identity Structure
- Department-based user modeling using profile attributes  
- Standardized user creation approach  
- Security groups aligned with departments and access needs  

### Group-Based Licensing
- Licensing managed through security groups  
- Removal of per-user license assignments  
- Foundation for scalable onboarding and automation  

### Baseline Identity Security
- Multi-Factor Authentication (MFA) enabled  
- Self-Service Password Reset (SSPR) activated  
- Mandatory security registration for users  

### Role-Based Administration
- Separation between admin and user identities  
- Least-privilege role assignments  
- Global Administrator restricted to break-glass usage  
- Validation of administrative roles through real tasks  

### Guest & External User Management
- Controlled guest invitation process  
- Clear distinction between internal and external users  
- Limited access for guests without unnecessary licensing  

---

## Business Flow Validation

To validate the identity foundation, a realistic onboarding flow was simulated:

- A new employee is created  
- Assigned to the correct department  
- Added to the appropriate security groups  
- Automatically receives the correct license  
- MFA and SSPR are enforced by default  
- Administration is performed without Global Admin access  

This confirms that the identity model supports **clean, repeatable, and secure onboarding**.

---

## Outcome of Phase 1

At the end of Phase 1:

- Identity management is standardized  
- Security is enforced at tenant level  
- Licenses are managed centrally via groups  
- Administrative access follows least-privilege principles  
- External users are safely controlled  

Phase 1 delivers a **stable and secure identity foundation**, enabling more advanced security controls such as Conditional Access, device trust, and endpoint security in later phases.

---

## Readiness for Next Phases

With Phase 1 completed, the environment is ready for:

- Conditional Access policy design  
- Device identity and compliance enforcement  
- Endpoint security integration  
- Zero Trust access decisions based on identity and device signals  

Phase 1 is the **cornerstone** upon which the rest of the Zero Trust architecture is built.
