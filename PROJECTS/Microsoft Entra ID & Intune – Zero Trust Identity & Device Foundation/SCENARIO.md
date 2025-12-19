# Business Scenario – Unico Tech World

**Scope:** Identity, Conditional Access, Device Management & Endpoint Security

This project is based on a fictional organization called **Unico Tech World**, used to simulate real-world identity, access, and device security challenges using **Microsoft Entra ID**, **Microsoft Intune**, **Conditional Access**, and **Microsoft Defender for Endpoint**.

The scenario reflects how a growing organization designs and implements a **cloud-first, Zero Trust identity and device security foundation**, focusing on secure access, managed devices, and endpoint protection.

---

## Company Overview

- **Name:** Unico Tech World  
- **Industry:** IT & Smart Mobility Services  
- **Employees:** ~250  
- **Regions:** Belgium, Netherlands, France  

---

## Workforce Composition

- Headquarters staff  
- Support technicians  
- Field engineers  
- Operations team  
- Marketing team  
- External consultants and contractors  

---

## IT Direction

Unico Tech World is moving toward a **modern, cloud-based security model** centered on **Microsoft Entra ID** and **Microsoft 365**, with a strong emphasis on **Zero Trust principles**.

---

## Business Context

Unico Tech World relies heavily on digital workflows to manage:

- Electric scooters and bikes  
- IoT fleet monitoring  
- Field operations  
- Remote support and collaboration  

As the organization grows, **unmanaged identities**, **inconsistent access controls**, and **unprotected devices** pose increasing security risks.

The leadership has asked IT to design and implement a **secure and scalable identity and device platform** that:

- Supports hybrid and remote work  
- Enforces strong authentication  
- Integrates device management into access decisions  
- Improves endpoint security visibility  

---

## IT Challenges Addressed in This Project

### Identity Foundation

**Initial problems:**
- Inconsistent user creation  
- Missing metadata (job title, department, location)  
- No naming conventions  
- Manual license assignment  
- Overuse of Global Administrator  
- MFA and SSPR not enforced  

**What was implemented:**
- Structured users, groups, and roles in Microsoft Entra ID  
- Role-based administration with least privilege  
- MFA and SSPR enabled  
- Group-based license assignment  
- Clear separation between admin and user identities  

---

### Conditional Access & Authentication

**Initial problems:**
- No Conditional Access policies  
- No enforcement of strong authentication  
- No access segmentation  
- Devices not considered during sign-in  

**What was implemented:**
- Baseline Conditional Access policies  
- MFA enforcement  
- Access decisions based on identity and device state  
- Break-glass account exclusions  
- Foundation for Zero Trust access control  

---

### Device Management & Compliance

**Initial problems:**
- Devices not enrolled in Intune  
- No compliance enforcement  
- BYOD unmanaged  
- Inconsistent device security posture  

**What was implemented:**
- Windows, Android, and iOS devices enrolled in Microsoft Intune  
- Compliance policies for managed devices  
- Android Work Profile for BYOD scenarios  
- App Protection Policies (MAM) for mobile applications  
- Device compliance integrated into Conditional Access decisions  

---

### Endpoint Security (Microsoft Defender for Endpoint)

**Initial problems:**
- No visibility into endpoint security posture  
- No centralized endpoint protection  
- No correlation between device security and access  

**What was implemented:**
- Microsoft Defender for Endpoint enabled  
- Integration between Intune and Defender  
- Automatic onboarding of Windows devices via Intune  
- Devices visible and reporting in the Defender security portal  
- Endpoint protection integrated into the Zero Trust model  

---

## Departments in Scope

To simulate realistic business operations, the following departments are represented:

- **Support** – Helpdesk and support tooling  
- **Operations** – Fleet and operational access  
- **Marketing** – Collaboration and external sharing  
- **IT / Management** – Administration and security ownership  

Each department is represented through **users, groups, devices, and access policies**.

---

## Personas Used

### Internal Users
- Support Technician  
- Operations Manager  
- Marketing Associate  

### Administrators
- Global Administrator *(break-glass only)*  
- User Administrator  
- Conditional Access Administrator  
- Intune Administrator  

These personas are used to simulate realistic enterprise **identity, access, and device management scenarios**.

---

## Project Scope Summary

| Area                           | Status       |
|--------------------------------|--------------|
| Identity (Entra ID)            | Implemented  |
| Conditional Access             | Implemented  |
| MFA & Zero Trust Access        | Implemented  |
| Device Management (Intune)     | Implemented  |
| Device Compliance              | Implemented  |
| Endpoint Security (Defender)   | Implemented  |

---

## Final Scope Definition

This project delivers a complete, **end-to-end implementation** of:

- Secure identity management  
- Zero Trust Conditional Access  
- Device enrollment and compliance  
- Endpoint security integration  

The result is a **coherent, enterprise-ready identity and device security foundation**, aligned with **Microsoft best practices** and **real-world Modern Workplace environments**.
