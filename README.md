# Ms-Sentinel
Microsoft Sentinel repository

# Dismiss-AADRiskyUser

Author: Nicholas DiCola
Modified by: Nidhal Ferchichi

This playbook will dismiss the Risky User property in AAD using Graph API.

## Quick Deployment
**Deploy with incident trigger** (recommended)

After deployment, attach this playbook to an **automation rule** so it runs when the incident is created.

[Learn more about automation rules](https://docs.microsoft.com/azure/sentinel/automate-incident-handling-with-automation-rules#creating-and-managing-automation-rules)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FDismiss-AADRiskyUser%2Fincident-trigger%2Fazuredeploy.json)
[![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FDismiss-AADRiskyUser%2Fincident-trigger%2Fazuredeploy.json)

**Deploy with alert trigger**

After deployment, you can run this playbook manually on an alert or attach it to an **analytics rule** so it will run when an alert is created.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FDismiss-AADRiskyUser%2Falert-trigger%2Fazuredeploy.json)
[![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FDismiss-AADRiskyUser%2Falert-trigger%2Fazuredeploy.json)

## Prerequisites

- You will need to add the managed identity that is created by the Logic App to the Security Administrator role in Azure AD.

## Screenshots
**Incident Trigger**<br>
![Incident Trigger](./incident-trigger/images/Dismiss-AADRiskyUser_incident.png)<br>

**Alert Trigger**<br>
![Alert Trigger](./alert-trigger/images/Dismiss-AADRiskyUser_alert.png)<br>
