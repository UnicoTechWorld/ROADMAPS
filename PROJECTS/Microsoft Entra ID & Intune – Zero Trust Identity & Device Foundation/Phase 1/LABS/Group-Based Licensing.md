# LAB 2 – Group-Based Licensing

## Goal

The goal of this lab is to move away from **manual, per-user license assignment** and implement **group-based licensing** in Microsoft Entra ID.

This enables scalable, consistent, and automated license management.

---

## Why This Matters

Manual license assignment:
- Does not scale
- Is error-prone
- Breaks automation
- Makes onboarding inconsistent

Group-based licensing ensures that **licenses follow the user’s role**, not manual actions.

---

## What Was Implemented

During this lab, the following configuration was applied:

- Creation of a dedicated licensing security group:
  - `LIC_M365_BusinessPremium_AllStaff`
- Microsoft 365 Business Premium license assigned to the group
- Validation that test users automatically receive licenses when added to the group
- Verification of license status and conflict handling

(Screens)
---

## Key Concepts Applied

- Group-based license assignment
- Separation between identity and licensing logic
- Automation-ready onboarding
- Reduced administrative overhead

---

## Result

At the end of this lab:

- Licenses are managed centrally via security groups
- Users receive licenses automatically based on group membership
- Manual license assignment is no longer required
- The foundation is in place for fully automated onboarding

This lab establishes a **scalable and maintainable licensing model** aligned with enterprise best practices.
