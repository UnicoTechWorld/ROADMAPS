# LAB 2.4 – Zero Trust Conditional Access Policies

## Goal
The goal of this lab is to **enforce core Zero Trust Conditional Access controls** by combining **device compliance** and **strong authentication**.

This lab focuses on **real enforcement**, not theoretical or overlapping policies.

---

## Why This Matters
Without enforced Conditional Access policies:

- MFA usage can remain inconsistent  
- Unmanaged or non-compliant devices may access cloud resources  
- Zero Trust principles are only partially applied  

Zero Trust requires **explicit and enforced access conditions**.

---

## What Was Implemented
During this lab, **two Conditional Access policies** were applied:

### 🔐 Policy 1 – Require Compliant Device and MFA
- Grants access **only if the device is marked as Intune-compliant**
- Requires **multi-factor authentication (MFA)** as part of the same policy
- Uses **combined Grant controls (AND logic)** to enforce Zero Trust access
- Ensures that access is allowed **only when both device trust and strong authentication requirements are met**


### 🔐 Policy 2 – Require MFA for Cloud Applications
- Enforces **strong authentication (MFA)** for cloud applications
- Establishes a **Zero Trust MFA baseline**
- This policy was **previously created during the “Conditional Access Basics” lab**
- In this lab, it is **reused and enforced together** with the device compliance requirement

All policies were carefully scoped and tested to avoid administrator lockout.

---

<img width="1908" height="1025" alt="image" src="https://github.com/user-attachments/assets/b103cdfc-dad3-4924-acae-ed294c48fd14" />

<img width="1643" height="759" alt="image" src="https://github.com/user-attachments/assets/46967c20-80c5-4372-81b2-8c0589f538ad" />

---

## Validation
The Conditional Access configuration was validated by:

- Signing in from **compliant and non-compliant devices**
- Confirming that access is **allowed only under the defined conditions**
- Verifying **MFA challenges** during sign-in
- Reviewing **sign-in logs and policy evaluation results**

---

## Key Concepts Applied
- Zero Trust access enforcement  
- Device compliance as an access condition  
- MFA as a mandatory authentication baseline  
- Policy reuse across Conditional Access implementations  

---

## Result
At the end of this lab:

- Access is enforced based on **device trust and authentication**
- Only **Intune-compliant devices** can access protected cloud resources
- MFA is **consistently enforced** across cloud applications
- Conditional Access policies are **minimal, clean, and non-overlapping**

This lab **strengthens the Zero Trust access layer of Phase 2** and builds directly on the Conditional Access Basics configuration.
