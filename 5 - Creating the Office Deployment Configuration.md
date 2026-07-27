# Phase 4 - Creating the Office Deployment Configuration

Configured a custom Office Deployment Tool (ODT) XML file to perform a silent installation of Microsoft 365 Apps.

## Overview

The Office Deployment Tool uses a configuration XML file to define how Microsoft 365 Apps are installed. In this phase, a configuration file was created to install the 64-bit edition of Microsoft 365 Apps silently, automatically accept the license agreement, and enable automatic activation for licensed users.

## Configuration

* 64-bit Microsoft 365 Apps installation
* English (United States) language pack
* Silent installation (no user interaction)
* Automatically accepts the Microsoft license agreement
* Enables automatic Office activation

## Configuration File

```xml
<Configuration>

  <Add OfficeClientEdition="64">
    <Product ID="O365ProPlusRetail">
      <Language ID="en-us"/>
    </Product>
  </Add>

  <Display Level="None"
           AcceptEULA="TRUE"/>

  <Property Name="AUTOACTIVATE"
            Value="1"/>

</Configuration>
```

## Outcome

This configuration file is used by the Office Deployment Tool to install Microsoft 365 Apps silently from the deployment share. It will later be integrated into Microsoft Deployment Toolkit (MDT) and Group Policy for automated enterprise-wide software deployment.

## Screenshots

### Office Deployment Folder

> *Insert screenshot here*

### configuration.xml

> *Insert screenshot here*

## Skills Demonstrated

* Office Deployment Tool (ODT)
* Microsoft 365 Apps Administration
* XML Configuration
* Silent Software Installation
* Enterprise Software Deployment
* Microsoft Deployment Toolkit (MDT) Integration
