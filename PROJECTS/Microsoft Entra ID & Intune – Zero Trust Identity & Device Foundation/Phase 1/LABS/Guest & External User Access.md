# LAB 6 – Guest & External User Access

## Goal

The goal of this lab is to implement **controlled and secure access for external users** by correctly configuring guest identities in Microsoft Entra ID.

This ensures collaboration without compromising internal security.

---

## Why This Matters

External collaboration is common, but unmanaged guest access can:
- Increase data exposure risks
- Lead to uncontrolled access sprawl
- Bypass internal security standards

Guest users must be **clearly separated and restricted** compared to internal identities.

---

## What Was Implemented

During this lab, the following configuration was applied:

- Invitation of external users as **Guest** accounts
- Validation of guest identity type and properties
- Assignment of guests to dedicated security groups
- Limited access without assigning unnecessary licenses
- Verification that guests do not receive administrative privileges

---

<img width="904" height="782" alt="image" src="https://github.com/user-attachments/assets/216589ec-7b76-4538-87dc-dba79e551fa2" />

<img width="2752" height="1800" alt="image" src="https://github.com/user-attachments/assets/a9f461a4-b32c-4d7f-8189-115336f0f872" />


---


## Key Concepts Applied

- External identity management
- Guest vs internal user separation
- Least-privilege access for externals
- Secure collaboration

---

## Result

At the end of this lab:

- External users are correctly identified as guests
- Access is limited to what is strictly necessary
- Licensing is controlled and cost-efficient
- Internal security boundaries remain intact

This lab completes the **Phase 1 identity foundation** by addressing external collaboration scenarios.
