# Phase 3 – Device Identity, Endpoint Security & App Protection

## Overview

Phase 3 focuses on establishing **device identity, endpoint security, and data protection** using **Microsoft Intune** and **Microsoft Defender for Endpoint**.

Building on the identity foundation (Phase 1) and Conditional Access enforcement (Phase 2), this phase ensures that **devices themselves are managed, secured, and trustworthy** before they are allowed to access corporate resources.

This phase represents the transition from *access control* to **full device and endpoint security** within a Zero Trust architecture.

---

## Objective of Phase 3

The primary goal of this phase is to ensure that:

- Devices are properly enrolled and identified
- Security baselines are enforced at device level
- Corporate data is protected on managed and unmanaged devices
- Endpoint threats are detected and mitigated
- Device security signals can be integrated into access decisions

Phase 3 ensures that **trusted access is backed by trusted devices**.

---

## Problems Addressed

Before this phase, several device-related security gaps still existed:

- Devices were not consistently enrolled or managed
- No unified view of device security posture
- Limited enforcement of OS-level security settings
- No endpoint threat visibility
- Corporate data not protected on BYOD scenarios

These gaps weaken Zero Trust if devices are not explicitly secured.

---

## What Was Implemented

During Phase 3, the following device and endpoint security capabilities were implemented:

---

### Device Identity & Enrollment

- Microsoft Intune tenant configuration
- Windows device enrollment using Azure AD Join
- iOS device enrollment using APNs and Company Portal
- Android enrollment using **Work Profile (BYOD)**
- Validation of device identity and ownership

This ensures that devices are **known, identifiable, and manageable**.

---

### Device Configuration & Hardening

- Windows security baselines using the Settings Catalog
- Enforcement of OS-level security settings
- Alignment with Microsoft security recommendations

This reduces the attack surface at the operating system level.

---

### App & Data Protection

- App Protection Policies (MAM)
- Data separation between personal and corporate data
- Protection of corporate data even on unmanaged devices
- Secure access to Microsoft 365 applications

This ensures that **data remains protected regardless of device ownership**.

---

### Endpoint Security (Microsoft Defender for Endpoint)

- Microsoft Defender for Endpoint enabled
- Automatic onboarding of Windows devices via Intune
- Endpoint visibility through the Defender security portal
- Attack Surface Reduction (ASR) rules configured
- Device Control policies (e.g. USB restrictions)

Endpoint security adds **real-time threat detection and response** to the environment.

---

## Integration with Zero Trust

Phase 3 integrates tightly with earlier phases:

- Device compliance feeds Conditional Access decisions
- Defender risk signals strengthen access control
- Only secured and compliant devices are trusted

This creates a **complete Zero Trust loop**:
> Identity → Access Conditions → Device Trust → Endpoint Security

---

## Outcome of Phase 3

At the end of Phase 3:

- Devices are securely enrolled and managed
- Endpoint security is active and visible
- Corporate data is protected across device types
- Device risk is measurable and actionable
- The environment meets modern workplace security standards

Phase 3 delivers a **production-ready device and endpoint security foundation**.

---

## Final Project State

With Phase 3 completed, the project now represents a **full end-to-end Zero Trust Identity & Device Foundation**, including:

- Structured identities
- Conditional Access enforcement
- Device trust and compliance
- Endpoint threat protection
- App and data security

This aligns closely with **real-world Modern Workplace and Identity Engineer responsibilities**.
