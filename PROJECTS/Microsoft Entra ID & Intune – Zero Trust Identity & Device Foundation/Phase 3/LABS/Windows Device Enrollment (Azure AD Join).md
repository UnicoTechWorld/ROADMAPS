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
