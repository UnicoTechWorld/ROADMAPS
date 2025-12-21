# LAB 3.9 – Endpoint Security Controls (ASR & Device Control)

## Goal

The goal of this lab is to strengthen **endpoint protection** by configuring **Attack Surface Reduction (ASR) rules** and **Device Control policies** using Microsoft Defender for Endpoint and Intune.

This lab focuses on reducing common attack vectors and controlling peripheral device usage.

---

## Why This Matters

Even well-configured and compliant devices remain vulnerable to:
- Malware delivered through common attack techniques
- Unauthorized use of removable media
- Lateral movement after initial compromise

ASR rules and Device Control provide **preventive security controls** that reduce the attack surface before incidents occur.

---

## What Was Implemented

During this lab, the following endpoint security controls were configured:

### Attack Surface Reduction (ASR)
- Enforcement of ASR rules to block common attack techniques
- Protection against:
  - Malicious scripts
  - Credential theft attempts
  - Exploit-based attacks
- Application of ASR policies via Intune

### Device Control
- Configuration of USB and removable media restrictions
- Prevention of unauthorized data exfiltration
- Controlled access to external storage devices

These controls were applied to managed Windows devices.

---


<img width="484" height="360" alt="image" src="https://github.com/user-attachments/assets/91acc775-addb-4d0a-aaa2-4576719d069f" />

<img width="1691" height="798" alt="image" src="https://github.com/user-attachments/assets/82628f4a-75bf-4018-9af6-509d168a1b88" />

<img width="855" height="987" alt="image" src="https://github.com/user-attachments/assets/2e9553bd-1e6f-48d7-9484-2aeb67549344" />

---

## Validation

The endpoint security configuration was validated by:

- Verifying policy deployment status in Intune
- Confirming ASR rule enforcement on devices
- Testing behavior with removable media
- Reviewing security events in Defender

---

## Key Concepts Applied

- Attack surface reduction
- Preventive endpoint security
- Peripheral device control
- Defense-in-depth strategy

---

## Result

At the end of this lab:

- Common attack vectors are actively blocked
- Unauthorized device usage is restricted
- Endpoint security posture is significantly improved
- Devices are better protected against modern threats

This lab completes **Phase 3 by enforcing advanced endpoint security controls**.
