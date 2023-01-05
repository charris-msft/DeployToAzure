---
description: Create a Container App Environment with a Lightdash Container App and a PostgreSQL database.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: container-app-create
languages:
- json
- bicep
---
# Creates a Metabase Container App within a Container App Environment

![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.app/container-app-create/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.app/container-app-create/PublicDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.app/container-app-create/BestPracticeResult.svg)
![Cred Scan Check](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.app/container-app-create/CredScanResult.svg)

![Bicep Version](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.app/container-app-create/BicepVersion.svg)

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcharris-msft%2FDeployToAzure%2Fmain%2FLightdash%2Fazuredeploy.json){:target="_blank"}
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fcharris-msft%2FDeployToAzure%2Fmain%2FLightdash%2Fazuredeploy.json)

This template provides a way to deploy Lightdash as a **Container App** in a **Container App Environment** along with PostgreSQL database.

If you're new to **Container App**, see:

- [Microsoft Container Apps Documentation](https://docs.microsoft.com/azure/container-apps/)
- [Quickstarts: Microsoft Container Apps](https://docs.microsoft.com/azure/container-apps/get-started)
- [Container Apps Pricing](https://azure.microsoft.com/pricing/details/container-apps/)

If you're new to template deployment, see:

- [Azure Resource Manager documentation](https://docs.microsoft.com/azure/azure-resource-manager/)

`Tags: ContainerApp, Container App, Container, Web, ARM Template, Microsoft.OperationalInsights/workspaces, Microsoft.App/managedEnvironments, Microsoft.App/containerApps`
