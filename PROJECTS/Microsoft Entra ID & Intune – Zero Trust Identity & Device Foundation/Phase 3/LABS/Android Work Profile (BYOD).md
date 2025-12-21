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

<img width="1899" height="783" alt="image" src="https://github.com/user-attachments/assets/aa7c7a18-b898-489b-9af8-6d857b1b879c" />

<img width="270" height="551" alt="image" src="https://github.com/user-attachments/assets/ef1fc563-2072-4c6e-b418-e185ecf0802a" />

<img width="1592" height="617" alt="image" src="https://github.com/user-attachments/assets/69273381-8279-4d01-b109-752afab0584e" />

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
