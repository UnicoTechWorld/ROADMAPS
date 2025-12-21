# LAB 4 – Roles & Privileged Access

## Goal

The goal of this lab is to establish a **least-privilege administration model** by correctly separating administrative roles and reducing reliance on the Global Administrator role.

This ensures that administrative access is **controlled, auditable, and secure**.

---

## Why This Matters

Using Global Administrator for daily tasks:
- Increases security risk
- Violates least-privilege principles
- Makes auditing difficult
- Expands the blast radius of compromised accounts

A role-based administration model is essential for secure identity operations.

---

## What Was Implemented

During this lab, the following changes were made:

- Assignment of appropriate admin roles to the main admin account:
  - User Administrator
  - Authentication Administrator (if required)
- Restriction of the Global Administrator role to:
  - `LAB_Admin_Global` (break-glass only)
- Validation of role assignments by performing real administrative tasks:
  - Password reset for a test user

---

<img width="1605" height="360" alt="image" src="https://github.com/user-attachments/assets/a535fec9-7682-4474-bdea-230234fa5e4d" />

<img width="421" height="419" alt="image" src="https://github.com/user-attachments/assets/84d37223-f769-44df-9000-8f3d3300beee" />

<img width="1641" height="500" alt="image" src="https://github.com/user-attachments/assets/d53a2032-0145-4766-9ea1-6cecd0b2cc7e" />

<img width="1890" height="680" alt="image" src="https://github.com/user-attachments/assets/6cff1cb1-a320-4754-a06e-fa3ca3713741" />

---

## Key Concepts Applied

- Least-privilege access
- Role-based administration
- Separation of admin and user identities
- Break-glass account usage

---

## Result

At the end of this lab:

- Daily administration is performed without Global Admin rights
- Administrative roles are scoped correctly
- Global Administrator is reserved for emergencies only
- The tenant follows least-privilege best practices

This lab establishes a **secure administrative foundation** for identity management.
