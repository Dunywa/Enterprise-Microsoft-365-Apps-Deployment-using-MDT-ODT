# Phase 6 - Creating an MDT Application for Microsoft 365 Apps

Imported Microsoft 365 Apps into Microsoft Deployment Toolkit (MDT) as an application to enable automated deployment during Windows installations.

## Overview

The purpose of this phase was to package Microsoft 365 Apps within MDT using the Office Deployment Tool (ODT). This allows Office to be installed silently as part of an operating system deployment, eliminating the need for manual installation on each device.

## Tasks Completed

* Opened Microsoft Deployment Toolkit (MDT).
* Navigated to the **Applications** node.
* Created a new application using **Application with source files**.
* Imported the Office installation source from `D:\Deploy\Office`.
* Configured the destination directory as **Office365**.
* Specified the silent installation command:

  ```cmd
  setup.exe /configure configuration.xml
  ```
* Verified the application was successfully imported into the MDT Deployment Share.

## Screenshots

### MDT Applications Node

> *Insert screenshot here*

### New Application Wizard

> *Insert screenshot here*

### Office Source Files

> *Insert screenshot here*

### Installation Command Configuration

> *Insert screenshot here*

### Microsoft 365 Application in MDT

> *Insert screenshot here*

## Skills Demonstrated

* Microsoft Deployment Toolkit (MDT)
* Office Deployment Tool (ODT)
* Microsoft 365 Apps Deployment
* Silent Application Installation
* Enterprise Software Packaging
* Windows Deployment Automation

## Outcome

Microsoft 365 Apps were successfully added to the MDT Deployment Share and are ready to be included in Task Sequences for automated operating system and application deployment.
