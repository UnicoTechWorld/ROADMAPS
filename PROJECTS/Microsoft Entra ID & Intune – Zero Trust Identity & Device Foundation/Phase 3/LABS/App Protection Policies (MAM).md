# LAB 3.7 – App Protection Policies (MAM)

## Goal

The goal of this lab is to protect **corporate data at the application level** by configuring **App Protection Policies (MAM)** in Microsoft Intune.

This allows secure access to company data **even on unmanaged or BYOD devices**.

---

## Why This Matters

Not all devices can or should be fully managed.

Without app-level protection:
- Corporate data can be copied to personal apps
- Data leakage risks increase on BYOD devices
- Security depends entirely on device management

App Protection Policies ensure that **data remains protected regardless of device ownership**.

---

## What Was Implemented

During this lab, the following App Protection configurations were applied:

- Creation of App Protection Policies for mobile applications
- Protection of Microsoft 365 apps (e.g. Outlook, Teams)
- Restrictions on data actions such as:
  - Copy / paste
  - Save-as
  - Data sharing to unmanaged apps
- Enforcement of app-level PIN or biometric protection

These policies apply **without requiring full device enrollment**.

---

## Validation

The App Protection setup was validated by:

- Signing in to protected apps on a mobile device
- Verifying enforcement of app-level restrictions
- Confirming separation between corporate and personal data
- Testing access behavior on unmanaged or BYOD devices

---

## Key Concepts Applied

- Mobile Application Management (MAM)
- Data Loss Prevention (DLP)
- App-level security controls
- Secure BYOD access

---

## Result

At the end of this lab:

- Corporate data is protected at application level
- BYOD devices can access data securely
- Data leakage risks are reduced
- App-level security complements device compliance

This lab ensures **data protection beyond device management**.
