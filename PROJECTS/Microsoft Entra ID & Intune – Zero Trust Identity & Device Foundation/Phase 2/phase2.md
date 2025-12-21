# Phase 2 – Conditional Access & Device Trust (Zero Trust Access Control)

## Overview

Phase 2 focuses on designing and implementing **Conditional Access (CA)** policies that enforce **Zero Trust access decisions** by combining **identity signals**, **authentication strength**, and **device trust**.

Building on the structured identity foundation from Phase 1, this phase ensures that **access to cloud resources is no longer based on credentials alone**, but on verified conditions such as MFA, device compliance, and risk signals.

---

## Objective of Phase 2

The primary goal of this phase is to ensure that:

- Access decisions are enforced through Conditional Access
- MFA is consistently required where appropriate
- Only trusted and compliant devices can access resources
- High-risk sign-ins or devices are blocked
- Policies are rolled out safely without user lockout

This phase translates Zero Trust theory into **practical, enforceable access controls**.

---

## Problems Addressed

Before this phase, the environment still relied on basic identity security controls:

- MFA was enabled but not context-aware
- Devices were not evaluated during sign-in
- No distinction between trusted and untrusted devices
- No structured way to block risky access attempts
- Limited visibility into why access was allowed or denied

These gaps prevent organizations from enforcing **real Zero Trust access**.

---

## What Was Implemented

During Phase 2, the following Conditional Access capabilities were implemented:

### Device Trust as an Access Signal
- Device compliance state used as an input for access decisions
- Only Intune-compliant devices are allowed to access protected resources
- Foundation for trusted vs untrusted device differentiation

### Conditional Access Policy Design
- Creation of controlled Conditional Access policies
- Policies scoped to test users and workloads
- Exclusions configured to prevent administrator lockout

### MFA Enforcement
- MFA required for cloud applications
- MFA enforced in a controlled and predictable way
- Alignment with Zero Trust baseline recommendations

### Risk-Based Access Control
- Blocking access from high-risk devices or sign-ins
- Integration of risk signals into access decisions
- Preparation for deeper identity protection scenarios

### Safe Rollout & Validation
- Gradual policy enablement
- Validation through sign-in logs and compliance reporting
- Understanding why access is granted or denied

---

## Key Conditional Access Policies Implemented

The following core Conditional Access policies were implemented:

| Policy | Purpose |
|------|--------|
| Require compliant device | Allow access only from Intune-compliant devices |
| Block high-risk devices | Prevent access when device or sign-in risk is high |
| Require MFA for cloud apps | Enforce strong authentication as a Zero Trust baseline |

These policies form the **core Zero Trust access layer** of the environment.

---

## Visibility & Validation

To validate Conditional Access behavior, the following were actively used:

- Device compliance reporting
- Sign-in logs analysis
- Compliance vs non-compliance evaluation
- Understanding Conditional Access outcomes

This ensures that access control is **measurable, explainable, and auditable**.

---

## Outcome of Phase 2

At the end of Phase 2:

- Conditional Access is actively enforcing Zero Trust principles
- MFA is consistently required where needed
- Device compliance is a mandatory access condition
- Risky access attempts are blocked
- Administrators understand *why* access is allowed or denied

Phase 2 delivers a **real access control layer**, not just security configuration.

---

## Readiness for Next Phases

With Conditional Access in place, the environment is now ready for:

- Device identity expansion (Windows, iOS, Android)
- Advanced device compliance and hardening
- Endpoint security integration with Microsoft Defender for Endpoint
- App-level and data-level protection

Phase 2 acts as the **gatekeeper** between identity and device security in the Zero Trust architecture.
