---
layout: post
title: "Azure App Service on Azure Stack Update 6 Released"
categories: "Azure Stack"
tags: "Azure Stack"
author: "Andrew Westgarth"
---

This afternoon we released the sixth update to Azure App Service on Azure Stack.  This release updates the resource provider and brings the following key capabilities and fixes:

- Updates to **App Service Tenant, Admin, Functions portals and Kudu tools**. Consistent with Azure Stack Portal SDK version.
- Updates to **Kudu** tools to resolve issues with styling and functionality for customers operating **disconnected** Azure Stack.
- Updates to core service to improve reliability and error messaging enabling easier diagnosis of common issues.
- All other fixes and updates are detailed in the [App Service on Azure Stack Update Six Release Notes](https://docs.microsoft.com/en-us/azure-stack/operator/azure-stack-app-service-release-notes-update-six)

The App Service on Azure Stack Update 6 build number is **82.0.1.50**

You can download the new installer and helper scripts:

- [Installer](https://aka.ms/appsvcupdate6installer)
- [Helper Scripts](https://aka.ms/appsvconmashelpers)

Please read the updated documentation prior to getting started with deployment:

- [Update 5 Release Notes](https://docs.microsoft.com/en-us/azure-stack/operator/azure-stack-app-service-release-notes-update-six)
- [Before you get started with App Service on Azure Stack](https://docs.microsoft.com/azure/azure-stack/azure-stack-app-service-before-you-get-started)
- [Deploy the App Service Resource Provider](https://docs.microsoft.com/azure/azure-stack/azure-stack-app-service-deploy) for new deployments
- [Update the App Service Resource Provider](https://docs.microsoft.com/azure/azure-stack/azure-stack-app-service-update) for updating existing deployments