# LAB 3.4 – Android Work Profile (BYOD)

## Goal

The goal of this lab is to configure **Android Work Profile** to support **Bring Your Own Device (BYOD)** scenarios while ensuring corporate data remains protected.

This allows personal devices to be used securely for work purposes.

---

## Why This Matters

In BYOD scenarios, organizations must balance:
- User privacy
- Corporate data protection
- Device security

Without Work Profile:
- Corporate data mixes with personal data
- Security controls are limited
- Data leakage risks increase

Android Work Profile provides **secure separation** between personal and work data.

---

## What Was Implemented

During this lab, the following configuration was completed:

- Android Work Profile configuration in Intune
- Enrollment of an Android device using Work Profile
- Separation of work and personal applications
- Management of work apps without affecting personal space

The device was successfully enrolled as **BYOD with a managed work profile**.

---

## Validation

The configuration was validated by:

- Confirming creation of the work profile on the device
- Verifying managed apps are installed in the work profile
- Ensuring personal apps remain unmanaged
- Reviewing device status in Intune

---

## Key Concepts Applied

- BYOD security architecture
- Work vs personal data separation
- Mobile Application Management (MAM)
- Privacy-preserving device management

---

## Result

At the end of this lab:

- BYOD devices are securely supported
- Corporate data is isolated from personal data
- User privacy is preserved
- Mobile devices align with Zero Trust principles

This lab enables **secure mobile access** without full device control.
