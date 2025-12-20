# LAB 2.3 – Conditional Access Basics

## Goal

The goal of this lab is to understand and implement the **fundamentals of Conditional Access (CA)** in Microsoft Entra ID, using a **safe and controlled approach**.

This lab focuses on learning how to design Conditional Access policies **without risking tenant lockout**.

---

## Why This Matters

Conditional Access is one of the most powerful security controls in Microsoft Entra ID.

Incorrectly configured policies can:
- Lock administrators out of the tenant
- Disrupt user access
- Cause unintended security gaps

Understanding **how** and **where** to apply Conditional Access is essential before enforcing Zero Trust policies.

---

## What Was Implemented

During this lab, the following Conditional Access fundamentals were implemented:

- Creation of a Conditional Access policy targeting test users
- Proper use of exclusions to avoid administrator lockout
- MFA enforcement in a controlled scenario
- Policy applied to test users, not to the active admin account

This approach ensures safe experimentation and learning.

---

## Validation

The Conditional Access configuration was validated by:

- Signing in with a test user
- Confirming MFA enforcement
- Verifying that excluded accounts were not impacted
- Reviewing sign-in logs to confirm policy evaluation

---

## Key Concepts Applied

- Conditional Access policy design
- Safe rollout practices
- Exclusions and break-glass considerations
- MFA enforcement through Conditional Access

---

## Result

At the end of this lab:

- Conditional Access fundamentals are clearly understood
- Policies can be created without lockout risk
- MFA is enforced in a controlled manner
- The tenant is ready for Zero Trust Conditional Access policies

This lab provides the **foundation for all advanced Conditional Access scenarios**.
