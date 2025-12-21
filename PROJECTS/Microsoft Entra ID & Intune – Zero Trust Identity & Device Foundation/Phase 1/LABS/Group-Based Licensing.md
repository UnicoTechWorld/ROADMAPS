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

<img width="639" height="340" alt="image" src="https://github.com/user-attachments/assets/77d4f2f5-2199-4986-92b0-fdac1aff1d64" />

<img width="636" height="267" alt="image" src="https://github.com/user-attachments/assets/e199e452-518b-499c-9679-be8ea0ef086f" />

<img width="1894" height="712" alt="image" src="https://github.com/user-attachments/assets/8b19726a-2ddb-4393-b288-a46727a56524" />

<img width="929" height="556" alt="image" src="https://github.com/user-attachments/assets/1b445f98-321e-45d4-9eec-3d828fbe7779" />

<img width="1915" height="881" alt="image" src="https://github.com/user-attachments/assets/555dc6ac-8217-4713-ba5f-c6a9dc33b94f" />

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
