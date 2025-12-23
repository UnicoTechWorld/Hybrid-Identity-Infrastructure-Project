# Blok 3 – On-Prem Foundation

## Overview
This block focuses on designing and implementing a **solid on-premises Active Directory foundation** as part of the *Hybrid Identity & Infrastructure Engineering Project*.

Rather than documenting step-by-step procedures, this block presents the **architecture, design choices, and outcomes** of a realistic on-prem infrastructure, similar to how an infrastructure or system engineer would document their work.

This on-prem foundation will later serve as the base for **hybrid identity and device management scenarios**.

---

## Objectives
The main objectives of this block are to:

- Build a stable and secure Windows Server environment
- Deploy Active Directory Domain Services (AD DS)
- Configure core infrastructure services (DNS, DHCP)
- Design a clean and scalable Active Directory structure
- Apply baseline security policies using Group Policy
- Implement basic file services with proper access control
- Validate the environment for future hybrid integration

---

## Scope
This block is strictly focused on **on-premises infrastructure**:

- Windows Server
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- File Services

❌ No cloud services are configured in this block  
✅ Hybrid and cloud integration are covered in later blocks

---

## Documentation Philosophy
Each document in this block represents a **separate implementation phase**, documented from an **engineering and architectural perspective**.

The documentation focuses on:
- Design intent
- Configuration outcomes
- Technical decisions
- Validation and results
- Lessons learned

Detailed step-by-step instructions are **intentionally omitted** to keep the documentation:
- Recruiter-friendly  
- Engineer-oriented  
- Focused on reasoning and impact rather than clicks

---

## Folder Structure



01-onprem-foundation/

├── README.md

├── 01-server-preparation.md

├── 02-ad-ds-installation.md

├── 03-dns-configuration.md

├── 04-dhcp-configuration.md

├── 05-ou-and-objects.md

├── 06-gpo-baseline.md

├── 07-file-services.md

└── 08-troubleshooting.md (optional)


Each file documents **what was built, why it was built, and how it was validated**.

---

## Environment Context
- Windows Server (Evaluation)
- Single-domain forest
- Internal lab environment
- Virtualized infrastructure (Hyper-V / VMware / equivalent)

All configurations are designed as if this were a **real small-to-medium enterprise environment**.

---

## Why This Block Matters
A hybrid identity environment is only as strong as its on-prem foundation.

Poorly designed Active Directory environments often lead to:
- Authentication failures
- Device enrollment issues
- Group Policy conflicts
- Security weaknesses
- Complex hybrid sync problems

This block ensures the **foundation is clean, secure, and future-proof** before moving to hybrid scenarios.

---

## Status
🚧 In progress  
Each implementation phase is documented as it is completed.

---

## Author
**Corentin**  
Hybrid Identity & Infrastructure Engineering Project
