# Enterprise-Microsoft-365-Apps-Deployment-using-MDT-ODT

Automated deployment of Microsoft 365 Apps in an Active Directory environment using the Microsoft Deployment Toolkit (MDT) and the Office Deployment Tool (ODT).

---

## Project Overview

This lab demonstrates how to centrally deploy Microsoft 365 Apps across domain-joined Windows devices using Microsoft's deployment tools. The solution uses a Windows Server 2022 Domain Controller to host the Office installation files, an MDT deployment share for operating system and application deployment, and Group Policy to automate Office installation on client computers.

This project simulates a real-world enterprise or Managed Service Provider (MSP) environment where applications are deployed from a central repository instead of being installed manually on each workstation.

---

## Technologies Used

* Windows Server 2022
* Active Directory Domain Services (AD DS)
* DNS
* DHCP
* Microsoft Deployment Toolkit (MDT)
* Windows ADK
* Office Deployment Tool (ODT)
* Microsoft 365 Apps
* Group Policy
* SMB File Shares
* Windows 11

---

## Topology Overview

<img width="1536" height="1024" alt="Topology" src="https://github.com/user-attachments/assets/7e393ce1-9c8d-4df7-9d8c-3bb53ebcff93" />

---

## Features

* Centralized Office installation repository
* Silent Microsoft 365 Apps deployment
* Office Deployment Tool (ODT) configuration
* MDT application integration
* Automated software installation during Windows deployment
* Group Policy Startup Script deployment
* Shared deployment repository hosted on the Domain Controller

---

## Deployment Process

1. Configure Active Directory, DNS, and DHCP.
2. Install Windows ADK and Microsoft Deployment Toolkit.
3. Create an MDT Deployment Share.
4. Download Microsoft 365 Apps using the Office Deployment Tool.
5. Create a silent installation configuration file.
6. Import Microsoft 365 Apps into MDT as an application.
7. Add Office installation to an MDT Task Sequence.
8. Create a network share for Office installation files.
9. Deploy Office to existing domain computers using a Group Policy Startup Script.
10. Verify successful installation on client devices.

---

## Folder Structure

```text
D:\Deploy
│
├── MDT
├── Office
│   ├── setup.exe
│   ├── configuration.xml
│   └── Office Files
├── Applications
└── Logs
```

---

## Screenshots

### Domain Controller

> *Insert screenshot here*

### MDT Deployment Share

> *Insert screenshot here*

### Office Deployment Tool Files

> *Insert screenshot here*

### MDT Application Configuration

> *Insert screenshot here*

### Task Sequence

> *Insert screenshot here*

### Group Policy Startup Script

> *Insert screenshot here*

### Microsoft Word Installed on Client

> *Insert screenshot here*

---

## Skills Demonstrated

* Active Directory Administration
* Windows Server Management
* Microsoft Deployment Toolkit
* Office Deployment Tool
* Group Policy Management
* Enterprise Software Deployment
* Network File Sharing
* Windows Deployment Automation
* Microsoft 365 Administration
* IT Infrastructure Automation

---

## Learning Outcomes

* Deploy Microsoft 365 Apps without manual installation.
* Automate software deployment using MDT.
* Configure silent Office installations with ODT.
* Deploy applications using Group Policy.
* Build a centralized enterprise software deployment solution.

---

## Author

**Mvula**
Level 2 IT Support Technician

Focused on Microsoft Infrastructure, Active Directory, Azure, VMware, Microsoft 365, and Enterprise IT Administration.
