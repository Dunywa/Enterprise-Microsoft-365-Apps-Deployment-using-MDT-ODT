# Phase 9 - Deploy Microsoft 365 Apps Using Group Policy

Deploy Microsoft 365 Apps automatically to all domain-joined computers using a Group Policy Startup Script and the Office Deployment Tool (ODT).

---

## Project Overview

This phase demonstrates how to automate Microsoft 365 Apps deployment using Active Directory Group Policy. Instead of installing Office manually on each workstation, a startup script executes the Office Deployment Tool from a shared network location every time a computer starts.

This approach is commonly used in enterprise and Managed Service Provider (MSP) environments to standardize software deployments across multiple devices.

---

## Technologies Used

* Windows Server 2022
* Active Directory Domain Services (AD DS)
* Group Policy Management
* Office Deployment Tool (ODT)
* Microsoft 365 Apps
* SMB File Shares
* Windows 11

---

## Objectives

* Create a startup script to install Microsoft 365 Apps.
* Store the script in the SYSVOL scripts folder.
* Create and configure a Group Policy Object (GPO).
* Deploy Microsoft 365 Apps automatically during computer startup.
* Eliminate the need for manual Office installations.

---

## Startup Script

```cmd
@echo off

\\DC01\Deploy$\Office\setup.exe /configure \\DC01\Deploy$\Office\configuration.xml
```

---

## Deployment Process

1. Create the `InstallOffice.cmd` startup script.
2. Copy the script to the domain SYSVOL scripts folder.
3. Create a new Group Policy Object named **Deploy Office**.
4. Configure the Startup Script under **Computer Configuration → Policies → Windows Settings → Scripts (Startup/Shutdown)**.
5. Link the GPO to the domain.
6. Restart a domain-joined computer to trigger the Office installation.

---

## Folder Structure

```text
\\corp.local\SYSVOL\corp.local\scripts
│
└── InstallOffice.cmd
```

---

## Screenshots

### Office Deployment Share

> *Insert screenshot here*

### InstallOffice.cmd Script

> *Insert screenshot here*

### Group Policy Object (Deploy Office)

> *Insert screenshot here*

### Startup Script Configuration

> *Insert screenshot here*

### Client Receiving Group Policy

> *Insert screenshot here*

### Microsoft Word Installed

> *Insert screenshot here*

---

## Skills Demonstrated

* Active Directory Administration
* Group Policy Management
* Enterprise Software Deployment
* Office Deployment Tool (ODT)
* Microsoft 365 Administration
* Windows Server Administration
* Network File Sharing
* Startup Script Automation

---

## Learning Outcomes

* Deploy applications using Group Policy Startup Scripts.
* Centralize Microsoft 365 Apps deployment from a network share.
* Automate software installation for domain-joined computers.
* Configure enterprise software deployment using Active Directory.

---

## Author

**Mvula**
Level 2 IT Support Technician

Focused on Microsoft Infrastructure, Active Directory, Azure, VMware, Microsoft 365, and Enterprise IT Administration.
