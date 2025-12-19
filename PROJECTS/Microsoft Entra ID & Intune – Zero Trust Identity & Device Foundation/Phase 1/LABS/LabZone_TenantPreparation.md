# LAB 0 – Lab Zone & Tenant Preparation

## Goal

The goal of this lab is to **prepare the Microsoft Entra ID tenant** so that all test objects are clearly separated from any production-like configuration.

This creates a **safe lab environment** where identity and security features can be tested without impacting real users or configurations.

---

## Why This Matters

Without a clear separation between test and non-test objects, identity environments quickly become:
- Hard to manage
- Error-prone
- Unsafe to experiment in

A dedicated lab zone is a **best practice** for identity engineering and is essential for:
- Safe testing
- Clear documentation
- Scalable experimentation

---

## What Was Implemented

During this lab, the following preparations were made:

- A naming convention using the `LAB_` prefix for:
  - Test users
  - Test security groups
- Optional use of descriptive labels to simulate OU-like organization
- Creation of multiple test users
- Creation of a dedicated test Global Administrator account:
  - `LAB_Admin_Global`
- Clear distinction between lab identities and future production identities

---

## Key Concepts Applied

- Environment separation (lab vs non-lab)
- Naming conventions for identity clarity
- Safe administrative access for testing
- Foundation for structured identity work

---

## Result

At the end of this lab:

- The tenant is ready for structured identity labs
- Test objects are easily identifiable
- Administrative testing can be done safely
- The foundation is set for all subsequent Phase 1 labs

This lab establishes a **clean and controlled starting point** for the entire Zero Trust identity project.
