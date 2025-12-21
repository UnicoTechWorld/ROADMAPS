# LAB 2.1 – Device Compliance Policies (Device Trust Foundation)

## Goal

The goal of this lab is to define **when a device is considered trusted** by creating **device compliance policies** in Microsoft Intune.

These compliance signals will later be used by **Conditional Access** to allow or block access.

---

## Why This Matters

In a Zero Trust model, access decisions must not rely on identity alone.

Without device compliance:
- Unsecured or outdated devices can access company data
- There is no distinction between trusted and untrusted endpoints
- Conditional Access cannot enforce device-based controls

Device compliance is the **foundation of device trust**.

---

## What Was Implemented

During this lab, a Windows device compliance policy was created with the following requirements:

- Password protection enforced
- Minimum operating system version required
- BitLocker encryption required
- Microsoft Defender Antivirus active
- Non-compliant devices detected and flagged

The policy was assigned to test devices managed by Intune.

---

<img width="1124" height="882" alt="image" src="https://github.com/user-attachments/assets/11fff02f-2746-4c07-9e5b-efc740517a1d" />

<img width="965" height="455" alt="image" src="https://github.com/user-attachments/assets/61a43de1-22af-4893-aaed-44b47afd1d67" />

<img width="1536" height="1152" alt="image" src="https://github.com/user-attachments/assets/090021f5-7b15-4993-b992-d8b33aa9eb01" />

---

## Validation

The compliance configuration was validated by:

- Forcing an Intune sync on the test device
- Reviewing device compliance status in Intune
- Identifying compliant vs non-compliant states
- Confirming that the device reports correctly to Intune

---

## Key Concepts Applied

- Device trust as a Zero Trust principle
- Compliance-based access control
- Separation between device state and user identity
- Preparation for Conditional Access enforcement

---

## Result

At the end of this lab:

- Devices are evaluated against security requirements
- Non-compliant devices are clearly identified
- A trusted device baseline is established
- The environment is ready to use device compliance in Conditional Access

This lab provides the **device trust signal** required for Phase 2 Conditional Access policies.
