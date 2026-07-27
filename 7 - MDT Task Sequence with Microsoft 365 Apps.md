# Phase 7 - MDT Task Sequence with Microsoft 365 Apps

Created an MDT Task Sequence to automate the deployment of Windows 11 and Microsoft 365 Apps during operating system installation.

---

## Overview

The purpose of this phase was to integrate Microsoft 365 Apps into the Microsoft Deployment Toolkit (MDT) Task Sequence. By adding Office as an application during the **State Restore** phase, every new Windows 11 deployment automatically installs Microsoft 365 Apps without requiring manual intervention.

This approach simulates a real-world enterprise deployment where operating systems and business applications are deployed together from a centralized deployment server.

---

## Tasks Completed

* Created a new MDT Task Sequence
* Configured a Windows 11 deployment task
* Added Microsoft 365 Apps as an MDT Application
* Configured the **State Restore** phase to install Office automatically
* Validated the deployment sequence

---

## Deployment Workflow

```text
Start Deployment
       │
       ▼
Install Windows 11
       │
       ▼
Apply Drivers
       │
       ▼
State Restore
       │
       ▼
Install Microsoft 365 Apps
       │
       ▼
Complete Deployment
```

---

## Technologies Used

* Microsoft Deployment Toolkit (MDT)
* Windows ADK
* Windows 11
* Microsoft 365 Apps
* Office Deployment Tool (ODT)
* Windows Server 2022

---

## Screenshots

### MDT Task Sequence

> *Insert screenshot here*

### Install Applications Step

> *Insert screenshot here*

### Microsoft 365 Apps Added

> *Insert screenshot here*

### Successful Windows 11 Deployment

> *Insert screenshot here*

---

## Skills Demonstrated

* Microsoft Deployment Toolkit (MDT)
* Task Sequence Configuration
* Automated Windows Deployment
* Enterprise Software Deployment
* Microsoft 365 Administration
* Office Deployment Tool Integration
* Windows Imaging and Provisioning

---

## Outcome

Every Windows 11 deployment performed through MDT now includes an automated installation of Microsoft 365 Apps during the **State Restore** phase, providing a consistent and fully configured workstation immediately after deployment.
