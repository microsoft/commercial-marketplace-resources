# ![Alt Azure Marketplace shopping bag icon](images/Azure_Store_Marketplace_COLOR.svg "Azure Marketplace icon") Microsoft Commercial Marketplace | Samples and Learning Resources

This repository provides pointers to repositories and learning resources to help understand the Microsoft commercial marketplace. 

Please submit a pull request if there is a sample you have developed. If there is a sample you wish existed, please add it to our [Issues](https://github.com/microsoft/commercial-marketplace-samples/issues).

Included in this document.

1. [SaaS offers](#saas-offers)
1. [Virtual Machine offers](#virtual-machine-offers)
1. [Azure Managed Application offers](#azure-managed-application-offers)

## SaaS offers

### Learning resources

#### Mastering the Marketplace learning library

This library of technical content is designed to help speed your time to publish your SaaS offer to the Azure marketplace.

- [SaaS offers](https://github.com/microsoft/Mastering-the-Marketplace/blob/main/saas/README.md) - Speed your time to publishing your SaaS offer
- [SaaS Accelerator](https://github.com/microsoft/Mastering-the-Marketplace/blob/main/saas-accelerator/README.md) - Using the SaaS Accelerator reference implementation as your SaaS solution

#### Webinars

> For access to webinar recordings you will be asked to register to view the content.

- [Testing your SaaS Webhook](https://microsoftcloudpartner.eventbuilder.com/event/43707)
- [Dev and test approach for SaaS](https://microsoftcloudpartner.eventbuilder.com/event/42624)
- [Developing for commercial marketplace - SaaS offers and Azure Active Directory](https://microsoftcloudpartner.eventbuilder.com/event/32335)
- [Transactable SaaS Offer Overview](https://microsoftcloudpartner.eventbuilder.com/event/40201)
- [SaaS Overview](https://microsoftcloudpartner.eventbuilder.com/event/38107)
- [Configuring AAD to work with the Azure Marketplace](https://microsoftcloudpartner.eventbuilder.com/event/38110)

#### Microsoft Learn modules

- [Create a SaaS offer for the commercial marketplace](https://docs.microsoft.com/learn/modules/create-saas-offer-commercial-marketplace/)

### Sample projects

- [SaaS Accelerator](https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator) - A complete reference implementation of a SaaS offer


### Client libraries

The following repositories are not guaranteed through Microsoft support. They are intended as samples and reference implementations.

- Open API Specification (OAS) for REST Fulfillment API v2 and Metering API | [Specification](https://github.com/microsoft/commercial-marketplace-openapi)
- Client library for .NET | [Repository](https://github.com/microsoft/commercial-marketplace-client-dotnet) | [NuGet](https://www.nuget.org/packages/Marketplace.SaaS.Client)
- Client library for Java | [Repository](https://github.com/microsoft/commercial-marketplace-client-java)
- Client library for Python | [Repository](https://github.com/microsoft/commercial-marketplace-client-python) | [PyPi](https://pypi.org/project/azuremarketplace/)
- Client library for Node.js | [Repository](https://github.com/microsoft/commercial-marketplace-client-node) | [NPM for SaaS](https://www.npmjs.com/package/microsoft.marketplace.saas) | [NPM for Metering](https://www.npmjs.com/package/microsoft.marketplace.metering)
- Client library for Go (coming soon) | [Repository](https://github.com/microsoft/commercial-marketplace-client-go)

### Key documentation

- [How to plan a SaaS offer for the commercial marketplace](https://docs.microsoft.com/azure/marketplace/plan-saas-offer)
- [Build the landing page for your transactable SaaS offer in the commercial marketplace](https://docs.microsoft.com/azure/marketplace/azure-ad-transactable-saas-landing-page)
- [SaaS fulfillment APIs version 2 in the commercial marketplace](https://docs.microsoft.com/azure/marketplace/partner-center-portal/pc-saas-fulfillment-api-v2)
- [Metered billing for SaaS using the commercial marketplace metering service](https://docs.microsoft.com/azure/marketplace/partner-center-portal/saas-metered-billing)

## Virtual Machine offers

### Learning resources

### Sample projects




## Azure Managed Application offers

### Learning resources

**Mastering the Marketplace learning library**

This library of technical content is designed to help speed your time to publish your SaaS offer to the Azure marketplace.

- [Mastering Azure Managed Applications](https://github.com/microsoft/Mastering-the-Marketplace/blob/main/ama/README.md)

### Sample projects













## Azure application offers - Azure managed applications

### Custom metering, retrieving "resourceId" for a subscription

There are multiple approaches when a managed application needs to post usage to metering service. This set of notes and samples go through those approaches, and explain the relationship between them.

[GitHub repo](https://github.com/microsoft/commercial-marketplace-managed-application-metering-samples)

### Using a secret from the publisher's Azure Key Vault

There are scenarios when the publisher wants to share a secret during the deployment of a Managed Application. This sample demonstrates a technique sharing secrets during the deployment.

[GitHub repo](https://github.com/arsenvlad/azure-managed-app-publisher-secret)

## Azure application offers - Solution Template Offers

- [Overview](https://docs.microsoft.com/en-us/azure/marketplace/plan-azure-application-offer)
- [Azure QuickStart Templates](https://github.com/github/azure-quickstart-templates)
- [MS Build 2018 Presentation: Building Solution Templates and Managed Applications for the Azure Marketplace](https://channel9.msdn.com/Events/Build/2018/BRK3603)

## Azure virtual machine offers

This sample shows how to build a Virtual Machine for Linux or Windows and demonstrates the basic steps required to make the image ready for the Microsoft Commercial Marketplace.

[GitHub repo](https://github.com/microsoft/commerical-marketplace-vm-sample)

## Lead management integration samples

- [HubSpot Integration](https://github.com/santhoshb-msft/amp-leadgen2hubspot)

## Online learning resources

  [Online learning resources](./docs/learning-overview.md) are available to include key articles, webinars, videos and more.



