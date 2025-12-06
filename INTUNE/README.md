# Intune Roadmap — Zero to Expert

## Level 0 — Fundamentals (Beginner)

### Doel
Begrijpen wat Intune doet, hoe het past in Microsoft 365 en Entra ID.

### Topics
- MDM vs MAM
- Intune vs Configuration Manager
- Tenant, licenties, identities
- Device identity: Azure AD Join, Hybrid Join, Registered
- BYOD vs Corporate-owned
- Basis Intune-architectuur

### Mini-Labs
- Test user aanmaken in Entra ID
- Windows 11 VM enrollen in Intune
- Basis compliance + configuration profiles verkennen


---

## Level 1 — Core Intune Skills

### Doel
De essentiële configuraties leren die elke Modern Workplace engineer moet beheersen.

### Topics
- Windows / iOS / Android enrollment
- Company Portal en BYOD
- Compliance policies
- Configuration profiles (Settings Catalog, Templates)
- Windows Update Rings
- Role-Based Access Control (RBAC)

### Labs
- Windows-enrollment instellen
- Compliance policy maken
- Device restriction configureren via Settings Catalog
- Windows Update Ring deployen


---

## Level 2 — Endpoint Security (Intermediate)

### Doel
Intune security policies begrijpen en toepassen.

### Topics
- Endpoint Security blade
- Attack Surface Reduction policies
- Defender Antivirus policies
- Firewall rules via Intune
- Integratie met Microsoft Defender for Endpoint
- Device risk + Conditional Access

### Labs
- ASR rules configureren
- Defender Antivirus configureren
- Conditional Access op basis van device compliance
- Controlled Folder Access testen


---

## Level 3 — Autopilot & Zero-Touch Provisioning

### Doel
Windows deployments volledig automatiseren.

### Topics
- Autopilot deployment profiles (User-driven, Self-deploying)
- Pre-Provisioning (WhiteGlove)
- Enrollment Status Page (ESP)
- Hybrid Join Autopilot
- Required apps tijdens deployment

### Labs
- Autopilot hardware hash importeren
- Deployment profile aanmaken en testen
- ESP configureren met blokkades
- Hybrid Autopilot testen
- Pre-provisioning uitvoeren


---

## Level 4 — App Management (Advanced)

### Doel
Enterprise app deployment leren beheren.

### Topics
- Win32 app packaging (IntuneWin tool)
- Line-of-business apps
- App dependencies en supersedence
- App Protection Policies (MAM)
- Managed Google Play integratie
- Apple VPP en MDM

### Labs
- Win32 app packagen en deployen (bv. 7zip)
- Detection rules configureren
- MAM policies opstellen voor iOS/Android
- Managed Google Play verbinden met Intune


---

## Level 5 — Advanced Configurations

### Doel
Gebruik maken van geavanceerde configuratiemogelijkheden.

### Topics
- Security Baselines
- ADMX-ingestie
- OMA-URI custom policies
- Filters in Intune
- Dynamic groups (users/devices)
- PowerShell scripts via Intune

### Labs
- OMA-URI configureren voor een custom Windows setting
- PowerShell scripts pushen naar devices
- Dynamic device group voor Windows 11 maken
- Security Baseline toepassen en evalueren


---

## Level 6 — Monitoring, Troubleshooting & Reporting (Expert)

### Doel
Diep inzicht krijgen in Intune logging, monitoring en debugging.

### Topics
- Intune Troubleshooting Portal
- Device diagnostics en logs
- Autopilot debugging
- Update Compliance
- Microsoft Graph API voor automatisatie

### Labs
- Autopilot ESP fouten analyseren
- Device diagnostics uploaden en bekijken
- Compliance en update reporting evalueren
- Via Graph API devices of users ophalen


---

## Level 7 — Enterprise Architecture & Zero Trust (Expert+)

### Doel
Intune integreren in complexe enterprise-omgevingen en Zero Trust implementeren.

### Topics
- Intune + Conditional Access
- Intune + Microsoft Defender for Endpoint
- Mobile Application Management zonder device enrollment
- Co-management met SCCM
- Azure Lighthouse voor multi-tenant management
- Zero Trust endpoint architecture

### Enterprise Projects
- Zero Trust endpoint model bouwen
- Autopilot "as a service" ontwerpen
- MAM-only BYOD scenario implementeren
- Co-management testomgeving opzetten


---

## 4-Maanden Leerpad (Samenvatting)

### Maand 1
Fundamentals + Core Intune Skills

### Maand 2
Autopilot + Apps + Endpoint Security

### Maand 3
Advanced Configurations

### Maand 4
Expert Topics + Enterprise Projects
