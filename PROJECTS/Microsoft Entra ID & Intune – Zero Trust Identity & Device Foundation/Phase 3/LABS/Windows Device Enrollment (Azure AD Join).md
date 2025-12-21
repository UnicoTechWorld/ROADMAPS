# LAB 3.2 – Windows Device Enrollment (Azure AD Join)

## Goal

The goal of this lab is to **enroll a Windows device into Microsoft Entra ID and Microsoft Intune** using **Azure AD Join**.

This establishes the device as a **managed and trusted endpoint** within the organization.

---

## Why This Matters

Without proper device enrollment:
- Devices cannot be managed or secured centrally
- Compliance and security policies cannot be enforced
- Device trust cannot be evaluated for access decisions

Azure AD Join ensures that Windows devices are **identity-aware and manageable**.

---

## What Was Implemented

During this lab, the following steps were completed:

- Preparation of a Windows test device / virtual machine
- Azure AD Join of the Windows device
- Automatic enrollment into Microsoft Intune
- Verification of device presence in:
  - Microsoft Entra ID
  - Microsoft Intune

The device was confirmed as both **Entra ID–joined** and **Intune-managed**.

---

<img width="708" height="686" alt="image" src="https://github.com/user-attachments/assets/bd3e58f6-3abc-4afa-8c23-0ee5439a8135" />

<img width="1022" height="680" alt="image" src="https://github.com/user-attachments/assets/f9c037fe-98bb-436a-80c5-1c4042dcb272" />

<img width="1415" height="954" alt="image" src="https://github.com/user-attachments/assets/1b3bdedb-b9f9-451a-a439-4e333024d3fe" />

<img width="1082" height="700" alt="image" src="https://github.com/user-attachments/assets/d6931b73-7c6a-4d7c-af26-793ae632a881" />

<img width="1233" height="312" alt="image" src="https://github.com/user-attachments/assets/a32d26f5-153c-48b5-96f2-677337619997" />

---
## Validation

The enrollment was validated by:

- Checking device status in Microsoft Entra ID
- Confirming Intune management and sync status
- Verifying device ownership and compliance evaluation
- Ensuring the device appears correctly in management portals

---

## Key Concepts Applied

- Device identity in Entra ID
- Azure AD Join vs local join
- Automatic MDM enrollment
- Foundation for device compliance and security

---

## Result

At the end of this lab:

- The Windows device is successfully enrolled
- Device identity is established
- Intune management is active
- The device is ready for compliance and security policies

This lab establishes the **primary Windows device identity** used throughout Phase 3.
