# LAB 3 – Basic Identity Security (MFA & SSPR)

## Goal

The goal of this lab is to implement **baseline identity security** by enforcing **Multi-Factor Authentication (MFA)** and enabling **Self-Service Password Reset (SSPR)**.

This ensures that all users meet minimum security requirements at the identity level.

---

## Why This Matters

Usernames and passwords alone are not sufficient to protect cloud identities.

Without MFA and SSPR:
- Accounts are vulnerable to phishing
- Password incidents increase support workload
- Users depend entirely on IT for recovery

Baseline identity security is a **mandatory first step** in a Zero Trust model.

---

## What Was Implemented

Two configuration approaches were evaluated:

- **Option A:** Security Defaults (basic, tenant-wide)
- **Option B:** Custom configuration (professional approach)

The following settings were implemented using a custom configuration:

- MFA registration policy via **Authentication Methods**
- Self-Service Password Reset (SSPR) enabled
- MFA enforcement at the next user sign-in

---

<img width="1579" height="742" alt="image" src="https://github.com/user-attachments/assets/fd4aa0f6-875e-4967-83b8-86472bb24169" />

<img width="1898" height="837" alt="image" src="https://github.com/user-attachments/assets/c1cbe318-9cf0-4f74-a0ec-85360306e869" />

<img width="760" height="706" alt="image" src="https://github.com/user-attachments/assets/3dc90210-fbfe-4f38-bf3c-05254e5cc6c5" />

<img width="734" height="341" alt="image" src="https://github.com/user-attachments/assets/cd1ca2a6-b051-40f2-8ba7-9a75b15aeacc" />


---

## Validation

The configuration was validated by:

- Signing in with a test user
- Completing MFA registration
- Performing a password reset via:
  - https://passwordreset.microsoftonline.com

---

## Key Concepts Applied

- Strong authentication enforcement
- Identity protection at tenant level
- User self-service recovery
- Foundation for Conditional Access

---

## Result

At the end of this lab:

- MFA is enforced for users
- SSPR is operational and tested
- Identity security is enabled tenant-wide
- The tenant meets minimum security standards

This lab delivers the **baseline identity security** required before implementing Conditional Access.
