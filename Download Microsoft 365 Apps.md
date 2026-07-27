# Phase 4 – Download Microsoft 365 Apps

Downloaded the Microsoft 365 Apps installation files using the Office Deployment Tool (ODT) for offline deployment in an enterprise environment.

---

## Overview

In this phase, the Office Deployment Tool (ODT) was used to download the latest Microsoft 365 Apps installation files to a central repository hosted on the Domain Controller. Hosting the installation source locally reduces internet bandwidth usage and enables consistent deployments across multiple domain-joined devices.

---

## Technologies Used

* Microsoft Office Deployment Tool (ODT)
* Microsoft 365 Apps
* Windows Server 2022
* Command Prompt

---

## Configuration File

The following configuration was used to download the 64-bit version of Microsoft 365 Apps from the Current Channel.

```xml
<Configuration>

  <Add OfficeClientEdition="64"
       Channel="Current">

    <Product ID="O365ProPlusRetail">

      <Language ID="en-us"/>

    </Product>

  </Add>

  <Display Level="None"
           AcceptEULA="TRUE"/>

</Configuration>
```

---

## Download Command

The Office installation files were downloaded using the following command:

```cmd
setup.exe /download configuration.xml
```

---

## Download Location

The downloaded installation files were stored in the following directory:

```text
D:\Deploy\Office
```

This repository will be used by MDT and Group Policy for centralized Microsoft 365 Apps deployment.

---

## Screenshots

### Office Deployment Tool Files

> *Insert screenshot here*

### Command Prompt Download

> *Insert screenshot here*

### Downloaded Office Files

> *Insert screenshot here*

---

## Skills Demonstrated

* Microsoft Office Deployment Tool (ODT)
* Microsoft 365 Apps Administration
* Enterprise Software Deployment
* Offline Office Installation
* Windows Server Administration
* Command-Line Administration
* Centralized Software Repository

---

## Learning Outcomes

* Configure the Office Deployment Tool using XML.
* Download Microsoft 365 Apps for offline deployment.
* Create a centralized Office installation repository.
* Prepare Microsoft 365 Apps for deployment using MDT and Group Policy.
