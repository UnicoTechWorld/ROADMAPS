# Business Scenario – Unico Tech World

This multi-phase project is based on a fictional organization called **Unico Tech World**, used to simulate real-world identity, access, device, and governance challenges in Microsoft Entra ID and Microsoft 365.

The same scenario is used across all phases (Identity Foundation, Conditional Access, Device Identity, and Governance), ensuring a consistent and realistic environment for progressive learning and implementation.

---

## Company Overview

- **Name:** Unico Tech World  
- **Industry:** IT & Smart Mobility Services  
- **Employees:** ~250  
- **Regions:** Belgium, Netherlands, France  
- **Workforce Composition:**  
  - Headquarters staff  
  - Support technicians  
  - Field engineers  
  - Operations team  
  - Marketing team  
  - External consultants and contractors  
- **IT Direction:**  
  The company is moving toward a modern, cloud-first, Zero Trust identity and security model.

---

## Business Context

Unico Tech World relies heavily on digital workflows to manage its mobility solutions (electric scooters, bikes, IoT management, field operations).  
As the company grows, so do the identity and access-related challenges.

The leadership has asked IT to build a secure, scalable, and well-governed identity platform that:

- supports hybrid and remote work  
- secures access to internal and external applications  
- manages employee lifecycle efficiently  
- integrates device management and compliance  
- improves governance and auditing capabilities  

This long-term vision aligns with Microsoft’s **Zero Trust** principles.

---

## IT Challenges Motivating This Project

Across all phases, Unico Tech World faces several problems:

### **Identity Foundation Problems (Phase 1)**
- Inconsistent user creation  
- Missing metadata (job title, department, location)  
- No naming standards  
- Too many manual processes  
- Group structure unclear or missing  
- Licensing managed manually  
- MFA and SSPR not enforced  
- Global Admin used for daily tasks

### **Access & Security Problems (Phase 2 – Conditional Access)**
- No Conditional Access (CA) policies  
- No protection against risky sign-ins  
- Legacy authentication still enabled  
- No access segmentation (internal/external, location-based)  
- No authentication strength strategy

### **Device Identity Problems (Phase 3 – Devices & Compliance)**
- Devices not enrolled in Intune  
- No compliance policies  
- No device-based access conditions  
- BYOD unmanaged  
- No integration between devices and Conditional Access

### **Governance Problems (Phase 4 – Identity Governance)**
- No lifecycle workflows  
- No automated onboarding/offboarding  
- No Access Packages  
- Guest access unmanaged  
- No periodic Access Reviews  
- No separation of internal vs. external governance

Each phase of this project addresses one of these areas.

---

## Departments In Scope

To simulate realistic business operations, the following departments are included:

- **Support** – Helpdesk and assistive roles  
- **Operations** – Fleet & depot management  
- **Marketing** – Campaigns, external partners  
- **Management / IT** – Administrators, governance owners  
- **External Partners** – Agencies, contractors, consultants  

Each department has different identity, access, device, and governance requirements.

---

## Personas Used in the Labs

The following personas are used across phases to simulate end users, managers, and administrators:

### **Internal Staff**
- **Support Technician** – Needs access to support tools, Teams, SharePoint.  
- **Operations Manager** – Needs access to reports, operational platforms.  
- **Marketing Associate** – Needs cloud apps, collaboration with external partners.  
- **New Hire** – Used for onboarding flows (Phase 1 + Phase 4).

### **Administrators**
- **Global Administrator (Break-glass)** – Only for emergencies and tenant-wide operations.  
- **User Administrator** – Handles identity and user lifecycle tasks.  
- **Conditional Access Administrator** – Designs and manages CA policies.  
- **Intune Administrator** – Handles device onboarding and compliance (Phase 3).  
- **Identity Governance Administrator** – Manages workflows and access packages (Phase 4).

### **External Users**
- Marketing agency partners  
- Contractors  
- Temporary consultants  
Used especially in Phase 1 (guest onboarding) and Phase 4 (governance).

---

## Project Vision Across All Phases

| Phase | Focus | End Goal |
|------|--------|----------|
| **Phase 1** | Identity Foundation | Clean identity structure, groups, SSPR, MFA, least privilege |
| **Phase 2** | Conditional Access | Zero Trust access model based on user, device, location, risk |
| **Phase 3** | Device Identity | Devices enrolled, compliant, and part of access control |
| **Phase 4** | Governance | Automated lifecycle, access packages, reviews, external governance |

This scenario ensures that all four phases connect into a realistic, enterprise-level identity and access ecosystem.

---

## Why This Scenario?

Using a single, evolving business scenario across all phases makes the work:

- **coherent** – everything builds on existing decisions  
- **realistic** – just like how organizations mature their identity posture  
- **solid** – no shortcuts, full lifecycle simulation  
- **scalable** – future labs naturally plug into the story  

This is the same approach used by identity engineers, IAM specialists, and Microsoft consultants.

