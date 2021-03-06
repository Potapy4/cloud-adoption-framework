---
title: Implement Cloud Adoption Framework enterprise-scale landing zones in Azure
description: Review options to implement the Cloud Adoption Framework for Azure enterprise-scale architecture.
author: JefferyMitchell
ms.author: brblanch
ms.date: 06/15/2020
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: ready
ms.custom: think-tank
---

# Implement Cloud Adoption Framework enterprise-scale landing zones in Azure

When business requirements necessitate a rich initial implementation of landing zones with fully integrated governance, security, and operations control plane from the start, use the enterprise-scale example options listed here. With this approach, you can use the Azure portal or infrastructure as code to set up and configure your Azure environment. It's also possible to transition between the portal and infrastructure as code (recommended) when your organization is ready.

## Reference implementation

The following table lists example reference implementations based on the recommended enterprise-scale architecture.

| Example deployment | Description | GitHub repo | Deploy to Azure |
|---------|---------|---------|---------|---------|---------|---------|---------|
| Enterprise-scale foundation | This is the suggested foundation for enterprise-scale adoption. | [Example in GitHub][GitHub-WingTip] | [![DTA-Button-WingTip]][DTA-WingTip] |
| Enterprise-scale hub and spoke | Add a hub and spoke network module to the enterprise-scale foundation. | [Example in GitHub][GitHub-AdventureWorks] | [![DTA-Button-AdventureWorks]][DTA-AdventureWorks] |
| Enterprise-scale Virtual WAN | Add a Virtual WAN network module to the enterprise-scale foundation. | [Example in GitHub][GitHub-Contoso] | [![DTA-Button-Contoso]][DTA-Contoso] |

## Next steps

These examples provide an easy deployment option to support continued learning for the enterprise-scale approach. Before you use these examples in a production version of enterprise-scale, review the enterprise-scale architecture.

> [!div class="nextstepaction"]
> [Review the enterprise-scale architecture](./architecture.md)

<!-- The following section is used to store references to external images and links to reduce maintenance overhead and enable tooltips -->

[//]: # (*******************************)
[//]: # (EXTERNAL IMAGE REFERENCES BELOW)
[//]: # (*******************************)

[DTA-Button-WingTip]: https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true "Deploy WingTip reference implementation (foundation) to Azure."
[DTA-Button-AdventureWorks]: https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true "Deploy AdventureWorks reference implementation (hybrid connectivity with hub and spoke) to Azure."
[DTA-Button-Contoso]: https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true "Deploy Contoso reference implementation (hybrid connectivity with virtual wan) to Azure."

[//]: # (**************************)
[//]: # (EXTERNAL LINK LABELS BELOW)
[//]: # (**************************)

[GitHub-WingTip]: https://github.com/Azure/Enterprise-Scale/blob/main/docs/reference/wingtip/README.md
[GitHub-AdventureWorks]: https://github.com/Azure/Enterprise-Scale/blob/main/docs/reference/adventureworks/README.md
[GitHub-Contoso]: https://github.com/Azure/Enterprise-Scale/blob/main/docs/reference/contoso/Readme.md

[DTA-WingTip]: https://ms.portal.azure.com/?feature.customportal=false#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Fwingtip%2FarmTemplates%2Fes-foundation.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Fwingtip%2FarmTemplates%2Fportal-es-foundation.json
[DTA-AdventureWorks]: https://ms.portal.azure.com/?feature.customportal=false#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Fadventureworks%2FarmTemplates%2Fes-hubspoke.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Fadventureworks%2FarmTemplates%2Fportal-es-hubspoke.json

[DTA-Contoso]: https://ms.portal.azure.com/?feature.customportal=false#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Fcontoso%2FarmTemplates%2Fes-vwan.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Fcontoso%2FarmTemplates%2Fportal-es-vwan.json
