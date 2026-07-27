# Phase 2 - Microsoft Deployment Toolkit (MDT) Deployment Server

Installed and configured Microsoft Deployment Toolkit (MDT) on the Domain Controller to create a centralized deployment share for Windows operating system and application deployments.

---

## Project Overview

This phase focuses on preparing a deployment server using the Microsoft Deployment Toolkit (MDT). The Windows Assessment and Deployment Kit (Windows ADK), WinPE Add-on, and MDT were installed to create a deployment infrastructure capable of deploying Windows operating systems and enterprise applications across the network.

A deployment share was created to serve as the central repository for operating systems, drivers, applications, task sequences, and deployment scripts.

---

## Technologies Used

* Windows Server 2022
* Microsoft Deployment Toolkit (MDT)
* Windows Assessment and Deployment Kit (Windows ADK)
* Windows PE Add-on
* SMB File Sharing

---

## Completed Tasks

* Installed Windows Assessment and Deployment Kit (Windows ADK)
* Installed Windows PE Add-on
* Installed Microsoft Deployment Toolkit (MDT)
* Created the MDT Deployment Share
* Configured the deployment share location
* Shared the deployment repository for network access

---

## Deployment Share

**Location**

```text
D:\Deploy\MDT
```

**Share Name**

```text
DeploymentShare$
```

---

## Screenshots

### Windows ADK Installation

> *Insert screenshot here*

### WinPE Add-on Installation

> *Insert screenshot here*

### Microsoft Deployment Toolkit Installation

> *Insert screenshot here*

### MDT Deployment Share Configuration

> *Insert screenshot here*

### Deployment Workbench

> *Insert screenshot here*

---

## Skills Demonstrated

* Microsoft Deployment Toolkit (MDT)
* Windows Deployment Services
* Windows ADK
* Windows PE
* Deployment Share Configuration
* Enterprise Operating System Deployment
* Windows Server Administration
* Network File Sharing

---

## Learning Outcomes

* Configure an MDT deployment server.
* Create a centralized deployment share.
* Prepare infrastructure for Windows imaging and application deployment.
* Build the foundation for automated enterprise operating system deployments.

---

## Next Phase

The next phase focuses on downloading and configuring Microsoft 365 Apps using the Office Deployment Tool (ODT) before integrating Office into MDT for automated deployment.
