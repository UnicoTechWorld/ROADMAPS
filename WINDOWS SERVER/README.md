# 🚀 Windows Server Roadmap  
Zero → Intermediate → Advanced  
**Focus: Infra Engineer • Cloud/System Engineer • Modern Workplace Engineer**

---

## 🔰 FASE 0 — FUNDAMENTEN (Zero → Beginner)

### 0.1 Basisconcepten
- Wat is een server?
- Windows Server rollen vs features
- Server Core vs Desktop Experience
- Windows Admin Center (WAC)
- Remote Server Administration Tools (RSAT)

### 0.2 Netwerkbasis (must-have)
- IPv4 / IPv6
- Subnetting
- DHCP & DNS basis
- NAT, routing basis
- TCP/UDP poorten & protocollen

### 0.3 Eerste installatie
- Windows Server installatie
- NIC configuratie
- Time sync
- Windows Update
- Remote Management activeren

---

## 🟦 FASE 1 — ACTIVE DIRECTORY (Beginner → Intermediate)

### 1.1 AD DS Kernconcepten
- Forests, Trees, Domains
- Domain Controller promotie
- SYSVOL, Global Catalog
- AD schema
- AD replication (site links)

### 1.2 AD User & Group Management
- OU Design (logisch, security, delegation)
- User provisioning & lifecycle
- AGDLP / AGUDLP groepsmodel
- Admin tiers (Tier 0–1–2)

### 1.3 Group Policy (GPO)
- GPO structuur (User vs Computer)
- Loopback Processing
- Security filtering, WMI filters
- Top real-life GPO’s:
  - Password policies
  - Firewall rules
  - Drive maps
  - Software restriction policies

### 1.4 AD Troubleshooting
- `dcdiag`
- `repadmin`
- Kerberos vs NTLM
- UPN issues
- Time skew problemen

---

## 🟩 FASE 2 — CORE INFRASTRUCTURE (Intermediate)

### 2.1 DNS (diepgaand)
- Primary, Secondary, Stub zones
- Forward/Reverse lookup
- Conditional forwarders
- DNS policies
- Tools: nslookup, dnscmd

### 2.2 DHCP
- Scopes & Superscopes
- Reservations
- Lease management
- DHCP Options (inclusief VoIP/WDS opties)
- DHCP Failover

### 2.3 File Services
- NTFS vs Share permissions
- Effective permissions
- DFS-N & DFS-R
- Shadow Copies
- FSRM (Quota, File Screening)

### 2.4 Print Services
- Print server
- Printer deployment via GPO

---

## 🟪 FASE 3 — VIRTUALISATIE (Intermediate → Advanced)

### 3.1 Hyper-V Basics
- Hyper-V rol installatie
- VM types
- Generation 1 vs 2
- Checkpoints
- Integration Services

### 3.2 Virtual Networking
- External / Internal / Private switches
- VLAN tagging
- NIC teaming

### 3.3 VM Storage
- VHDX types (dynamic, fixed, differencing)
- Pass-through disks
- Storage QoS

### 3.4 Hyper-V Advanced
- Live Migration
- Storage Migration
- Hyper-V Replica (DR)
- Host resource management

---

## 🟥 FASE 4 — HIGH AVAILABILITY + FAILOVER CLUSTERING (Advanced)

### 4.1 Failover Cluster Concepts
- Cluster nodes
- Quorum types
- Cluster witness (File / Disk / Cloud)
- Cluster roles

### 4.2 Cluster Workloads
- Highly Available File Server
- Hyper-V cluster
- Scale-out File Server (SOFS)
- SQL clusters (conceptueel)

### 4.3 Cluster Maintenance
- Cluster-Aware Updating (CAU)
- Failover scenarios
- Live node updates

---

## 🟧 FASE 5 — HYBRID IDENTITY (Cruciaal voor Cloud & Workplace Engineers)

### 5.1 Azure AD Connect
- Installatie en configuratie
- Password Hash Sync
- PTA (Pass-through Authentication)
- Federation (AD FS)
- OU & attribute filtering
- Password writeback
- AAD Connect Health monitoring

### 5.2 Hybrid Join Variants
- Hybrid Azure AD Join
- Seamless SSO
- Cloud-only identity migratie

---

## 🟨 FASE 6 — AUTOMATISATIE (Advanced)

### 6.1 PowerShell
- Cmdlets basis
- Pipelines
- Variabelen, functies, modules
- Scriptsignering
- AD automatisatie:
  - `Get-ADUser`
  - `Get-ADGroup`
  - `New-ADUser`
  - Bulk operations

### 6.2 Desired State Configuration (DSC)
- MOF files
- Configuration blocks
- Push vs Pull model
- Azure Guest Configuration

---

## 🟫 FASE 7 — SECURITY (Advanced)

### 7.1 Windows Server Security Essentials
- LAPS (Local Admin Password Solution)
- BitLocker & MBAM
- Windows Firewall advanced rules
- Credential Guard / Device Guard
- Secure Admin Workstations (SAW/PAW)

### 7.2 Hardening
- CIS Benchmarks
- Microsoft Security Baselines
- AD hardening best practices
- Least privilege model

---

## 🟩 FASE 8 — DEPLOYMENT & IMAGING (Workplace & Infra)

### 8.1 MDT / WDS
- WDS PXE boot
- MDT Task Sequences
- Driver management
- Unattend.xml basics

### 8.2 OS Deployment Scenarios
- Bare-metal deployment
- Capture & deploy images
- Boot issues troubleshooting

---

## 🟦 FASE 9 — MODERN MANAGEMENT (must-have voor Workplace Engineers)

### 9.1 Intune Integratie
- Enrollment flows
- Hybrid join
- Autopilot configuratie
- Win32 app packaging
- Compliance policies
- Update rings & feature update policies

### 9.2 Co-Management (SCCM + Intune)
- Workload switching
- Client management
- Software deployment & updates

---

## 🟣 FASE 10 — ENTERPRISE SCENARIO’S (Advanced)

### 10.1 Migraties
- Domain controller upgrade & migration
- DNS migration
- File Server Migration Service (SMS)
- AD cleanup (orphans, stale objects)

### 10.2 Monitoring
- Event Viewer deep dive
- Performance Monitor
- Azure Monitor + Log Analytics (hybrid servers)

### 10.3 Backup & Disaster Recovery
- Bare metal recovery
- AD restore (authoritative vs non-authoritative)
- Application-aware backups
- DR scenario’s testen

---

# 🎯 SKILLSET PER ROL

## Infra Engineer
- AD & GPO (expert)
- DNS, DHCP, File Services, DFS
- Hyper-V + clustering
- Storage (iSCSI, SAN concept)
- PowerShell automation
- Security hardening

## Cloud/System Engineer
- Hybrid identity
- Azure AD Connect
- Windows Server in Azure (IaaS)
- DSC / PowerShell
- Azure Arc
- Monitoring & automation

## Modern Workplace Engineer
- AD + GPO basics/intermediate
- Intune + Autopilot
- OS deployment (MDT/WDS)
- Application deployment
- Device lifecycle management

---

# 💡 TIP: Hoe deze roadmap studeren?
1. Begin met AD + GPO (fundament van alles)  
2. Daarna DNS/DHCP/File Services  
3. Hyper-V + Clustering voor infra roles  
4. Azure AD Connect + Hybrid identity  
5. PowerShell automatisatie  
6. Modern Workplace? → Intune & Autopilot  

---

