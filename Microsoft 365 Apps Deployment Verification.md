# Phase 10 – Microsoft 365 Apps Deployment Verification

Verified the successful deployment of Microsoft 365 Apps on a domain-joined Windows client after deployment using the Microsoft Deployment Toolkit (MDT), Office Deployment Tool (ODT), and Group Policy.

---

## Overview

The purpose of this phase was to confirm that Microsoft 365 Apps were successfully installed and configured on the client computer following the automated deployment process.

Verification included launching Office applications, confirming activation status, and validating the installation through Windows.

---

## Verification Steps

On **CLIENT01**:

1. Open the **Run** dialog (`Win + R`).
2. Launch Microsoft Word by running:

```text
winword
```

Or launch Microsoft Excel by running:

```text
excel
```

3. Confirm the following:

   * Microsoft Word opens successfully.
   * Microsoft Excel opens successfully.
   * Office is activated (if a valid Microsoft 365 license is assigned).
   * Microsoft 365 Apps appear under **Programs and Features** or **Installed Apps**.

---

## Screenshots

### Microsoft Word Successfully Launched

> *Insert screenshot here*

### Microsoft Excel Successfully Launched

> *Insert screenshot here*

### Microsoft 365 Apps Listed in Installed Apps

> *Insert screenshot here*

### Office Activation Status

> *Insert screenshot here*

---

## Outcome

The deployment was successfully verified, confirming that Microsoft 365 Apps were installed and accessible on the client computer. This validated the MDT task sequence, Office Deployment Tool configuration, network deployment share, and Group Policy deployment process.

---

## Skills Demonstrated

* Microsoft 365 Administration
* Microsoft Deployment Toolkit (MDT)
* Office Deployment Tool (ODT)
* Group Policy
* Enterprise Software Deployment
* Windows 11 Administration
* Application Deployment Verification
* IT Infrastructure Validation
