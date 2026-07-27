# Phase 1 – Domain Controller Deployment

Configured a Windows Server 2022 Domain Controller by installing the core infrastructure services required for an enterprise Active Directory environment.

---

## Project Overview

The objective of this phase was to deploy the first Domain Controller and configure the foundational services required for a Windows enterprise network. This included installing Active Directory Domain Services (AD DS), DNS, DHCP, and File Services, then creating a new Active Directory domain named **corp.local**.

This server serves as the foundation for future phases, including centralized authentication, Group Policy, software deployment, and Windows client management.

---

## Roles Installed

* Active Directory Domain Services (AD DS)
* DNS Server
* DHCP Server
* File and Storage Services

---

## Domain Information

| Setting          | Value               |
| ---------------- | ------------------- |
| Domain Name      | `mvulasmsp.local`        |
| Server Role      | Domain Controller   |
| Operating System | Windows Server 2022 |

---

## Services Configured

* Promoted the server to a Domain Controller
* Created the **mvulasmsp.local** Active Directory forest
* Configured DNS during domain promotion
* Installed and authorized the DHCP Server
* Installed File Services for shared resources
* Verified Active Directory and DNS functionality

---

## Screenshots

### Server Manager

> *Insert screenshot here*

### Active Directory Users and Computers

> *Insert screenshot here*

### DNS Manager

> *Insert screenshot here*

### DHCP Manager

> *Insert screenshot here*

### Server Successfully Promoted to Domain Controller

> *Insert screenshot here*

---

## Skills Demonstrated

* Windows Server 2022 Administration
* Active Directory Domain Services (AD DS)
* Domain Controller Deployment
* DNS Configuration
* DHCP Configuration
* File Services
* Enterprise Infrastructure Deployment
* Windows Server Roles and Features
* Active Directory Forest Creation

---

## Learning Outcomes

* Deploy a Windows Server as a Domain Controller.
* Create a new Active Directory forest and domain.
* Configure core infrastructure services for enterprise environments.
* Build the foundation for centralized authentication and domain management.

---

## Next Phase

The next phase builds on this infrastructure by configuring deployment services and preparing a centralized software deployment environment using the Microsoft Deployment Toolkit (MDT) and the Office Deployment Tool (ODT).
