# LAB 2.4 – Zero Trust Conditional Access Policies

## Goal

The goal of this lab is to implement **core Zero Trust Conditional Access policies** that actively control access to cloud resources based on **identity, device trust, and risk signals**.

This lab moves from theory to **real enforcement**.

---

## Why This Matters

Without enforced Conditional Access policies:
- MFA usage remains inconsistent
- Untrusted or risky devices can access resources
- Zero Trust principles are not fully applied

Zero Trust requires **explicit access decisions**, not optional security.

---

## What Was Implemented

During this lab, three key Conditional Access policies were created:

### Policy 1 – Require Compliant Device
- Allows access only from Intune-compliant devices
- Ensures that only trusted endpoints can access resources

### Policy 2 – Block High-Risk Devices
- Blocks access when device or sign-in risk is detected
- Prevents access from potentially compromised devices

### Policy 3 – Require MFA for Cloud Applications
- Enforces strong authentication
- Establishes a Zero Trust MFA baseline

All policies were carefully scoped and tested to avoid administrator lockout.

---

## Validation

The Conditional Access policies were validated by:

- Signing in from compliant and non-compliant devices
- Verifying access is blocked or allowed as expected
- Reviewing sign-in logs and policy evaluation results
- Confirming MFA challenges where required

---

## Key Concepts Applied

- Zero Trust access enforcement
- Identity and device signal correlation
- Risk-based access control
- Controlled Conditional Access rollout

---

## Result

At the end of this lab:

- Access is enforced based on trust and risk
- Only compliant devices can access protected resources
- Risky access attempts are blocked
- MFA is consistently enforced across cloud apps

This lab completes the **Zero Trust access layer** of Phase 2.
