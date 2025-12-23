# Hybrid Identity & Infrastructure Engineering Project

## Project Overview
This project documents the design and implementation of a hybrid identity and infrastructure environment.  
It starts from a traditional on-premises Windows Server setup and evolves step by step towards a hybrid Microsoft Entra ID and Intune architecture.

The purpose of this project is to demonstrate how a system/infrastructure engineer designs, builds, and evolves a realistic enterprise environment with a clear separation between identity, infrastructure, and device management.

---

## Scenario
**UnicoTechWorld** is a small-to-medium organization that currently relies on a traditional on-premises Active Directory environment.  
As part of a modernization initiative, UnicoTechWorld wants to introduce cloud identity and modern device management while keeping its existing on-premises infrastructure operational.

In this project, I take the role of a **system/infrastructure engineer** responsible for designing, implementing, and gradually evolving the UnicoTechWorld environment from on-premises to a hybrid architecture.

---

## Project Phases

### Phase 1 – On-Prem Foundation
Build a solid on-premises foundation using Windows Server, including Active Directory Domain Services, DNS, DHCP, Group Policy, and Windows client integration.

### Phase 2 – Growth & Resilience
Enhance the reliability and availability of the on-premises environment by introducing redundancy, replication, and failover mechanisms.

### Phase 3 – Hybrid Identity
Integrate the on-premises Active Directory environment with Microsoft Entra ID to enable hybrid identity and hybrid device join scenarios.

### Phase 4 – Modern Management
Introduce modern device management using Microsoft Intune, including device enrollment, compliance evaluation, Conditional Access, and operational lifecycle management.

---

## Repository Structure
Each phase is documented in its own folder, with a clear separation between architecture, implementation, and operational considerations.

This repository focuses on **design decisions, implementation logic, and operational understanding**, rather than only step-by-step lab execution.
