# Phase 8 – Deploy Microsoft 365 Apps to Existing Domain Computers

Deploy Microsoft 365 Apps to existing domain-joined Windows computers without reimaging by using a centralized network share and the Office Deployment Tool (ODT).

---

## Project Overview

This phase demonstrates how to deploy Microsoft 365 Apps to existing Windows devices from a shared network location. Instead of rebuilding or reimaging client computers, users or administrators can install Office silently using the Office Deployment Tool (ODT) hosted on the Domain Controller.

This approach is commonly used in enterprise and Managed Service Provider (MSP) environments to standardize software deployments and reduce manual installations.

---

## Technologies Used

* Windows Server 2022
* Active Directory Domain Services (AD DS)
* SMB File Sharing
* Office Deployment Tool (ODT)
* Microsoft 365 Apps
* Windows 11

---

## Objective

* Create a centralized Office installation repository.
* Share the Office installation files from the Domain Controller.
* Install Microsoft 365 Apps on existing domain computers without reimaging.
* Perform a silent installation using a predefined configuration file.

---

## Shared Installation Path

```text
\\DC01\Deploy$\Office
```

---

## Installation Command

Run the following command from a domain-joined client computer:

```cmd
\\DC01\Deploy$\Office\setup.exe /configure \\DC01\Deploy$\Office\configuration.xml
```

The installation runs silently using the settings defined in the configuration file.

---

## Folder Structure

```text
D:\Deploy
│
└── Office
    ├── setup.exe
    ├── configuration.xml
    └── Office Installation Files
```

---

## Verification

After the installation completes:

* Launch Microsoft Word or Excel.
* Verify Microsoft 365 Apps appear in the Start Menu.
* Confirm the applications open successfully.
* Verify activation (if licensing has been configured).

---

## Screenshots

### Office Deployment Share

> *Insert screenshot here*

### Office Folder Contents

> *Insert screenshot here*

### Running the Installation Command

> *Insert screenshot here*

### Microsoft Word Installed

> *Insert screenshot here*

---

## Skills Demonstrated

* Office Deployment Tool (ODT)
* Microsoft 365 Apps Deployment
* Enterprise Software Deployment
* Network File Shares
* Silent Software Installation
* Windows Server Administration
* Active Directory Environment
* Microsoft 365 Administration

---

## Learning Outcomes

* Deploy Microsoft 365 Apps without rebuilding client computers.
* Use a centralized deployment repository for application installation.
* Perform unattended software installations using ODT.
* Simulate enterprise application deployment practices used in corporate IT environments.
