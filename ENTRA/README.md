# Microsoft Entra Roadmap (Zero → Expert)

## Phase 1 — Foundations (Beginner → Comfortable)
Goal: Learn the basics of identity, authentication, and Entra ID structure.

### 1. Introduction to Microsoft Entra
- What is Microsoft Entra?
- Difference between Entra ID, Azure RBAC, Workload Identities
- Microsoft Identity Platform basics (OAuth2, OIDC)

### 2. Core Entra ID Concepts
- Users
- Groups (Security and Microsoft 365)
- Devices
- Licenses (E3/E5, P1/P2)
- Directory roles (Global Admin, User Admin, Device Admin)

### 3. Basic Access & Authentication
- MFA
- Self-Service Password Reset (SSPR)
- Authentication methods
- Authentication strengths

### Mini-labs (Phase 1)
- Create a new tenant
- Create users and groups
- Group-based licensing
- Configure MFA

---

## Phase 2 — Identity Security (Intermediate)
Goal: Apply Zero Trust through Conditional Access and Identity Protection.

### 4. Conditional Access
- Require MFA
- Block legacy authentication
- Require compliant devices
- Require trusted location
- Risk-based Conditional Access policies

### 5. Identity Protection
- Risky users
- Risky sign-ins
- Risk detections (TOR, impossible travel, unfamiliar sign-in properties)
- Automated remediation

### 6. Defender for Identity (Optional)
- On-prem AD threat detection
- Lateral movement detection
- Identity security posture reports

### Mini-labs (Phase 2)
- Build multiple Conditional Access scenarios
- Trigger risky sign-ins using a VPN/TOR
- Create break-glass exclusions

---

## Phase 3 — Application Identity & Access (Intermediate → Advanced)
Goal: Understand authentication/authorization for enterprise applications.

### 7. Enterprise Applications (SSO)
- SAML, OAuth2, OpenID Connect
- Configure Enterprise Applications
- App roles
- Consent (user vs admin)
- SCIM provisioning

### 8. Workload Identities
- Service principals
- Managed identities
- App registrations
- Azure RBAC vs Entra roles

### Mini-labs (Phase 3)
- Add Slack or GitHub as an SSO application
- Configure SCIM provisioning
- Managed Identity authentication to Key Vault

---

## Phase 4 — Identity Governance (Advanced)
Goal: Implement scalable identity lifecycle management.

### 9. Entitlement Management
- Catalogs
- Access packages
- Approval workflows
- Guest lifecycle automation

### 10. Access Reviews
- For groups, Teams, and enterprise apps
- Recurring reviews
- Automatic remediation

### 11. Lifecycle Workflows
- New hire
- Onboarding
- Offboarding
- Role change automation

### Mini-labs (Phase 4)
- Build access packages for HR/IT/Finance
- Configure guest expiration
- Build onboarding/offboarding workflows

---

## Phase 5 — Privileged Access (Expert)
Goal: Secure administrative access following Zero Trust architecture.

### 12. Privileged Identity Management (PIM)
- Just-In-Time access
- Approval workflows
- Privileged access groups
- PIM alerts and auditing

### 13. Break-glass Accounts
- Policy exclusions
- Monitoring and alerting
- Password hardening

### 14. Zero Trust Admin Model
- Admin tiering
- Secure workstations
- No persistent admin privileges

### Mini-labs (Phase 5)
- Configure PIM for admin roles
- Require MFA + justification for elevation
- Configure break-glass monitoring alerts

---

## Phase 6 — Hybrid Identity (Expert)
Goal: Integrate on-premises AD with Entra ID.

### 15. Entra Connect Cloud Sync
- OU filtering
- Password hash sync
- Seamless SSO
- Sync health

### 16. Hybrid Identity Lifecycle
- Source of authority design
- Soft/hard deletes
- Solving sync errors

### Mini-labs (Phase 6)
- Set up a Domain Controller in a VM
- Configure Entra Connect Cloud Sync
- Modify attributes and observe synchronization

---

## Phase 7 — Expert-Level Projects (Portfolio Ready)
Goal: Build real-world IAM solutions for your GitHub portfolio.

### Project 1 — End-to-End Identity Automation System
- Automated onboarding
- License assignment
- Group assignment
- Automated offboarding

### Project 2 — Zero Trust Conditional Access Framework
- Full CA matrix
- Policy documentation
- Break-glass strategy

### Project 3 — Guest Access Governance Model
- Access packages
- Access reviews
- Automated expiration

### Project 4 — Application SSO & Provisioning Hub
- 3 enterprise apps with SSO
- SCIM provisioning
- Role-based access

### Project 5 — Identity Security Dashboard
- KQL queries for sign-in logs
- Risky users report
- Workload identity activity

---

## Additional Recommended Topics
- Microsoft Sentinel identity monitoring
- Defender for Cloud Apps (session controls)
- MFA number matching enforcement
- FIDO2 hardware keys
- Attack simulation training

---

## Certification Route (Optional but Recommended)
- SC-900 — Microsoft Security Fundamentals
- SC-300 — Identity and Access Administrator
- SC-400 — Information Protection Administrator
- SC-100 — Cybersecurity Architect

