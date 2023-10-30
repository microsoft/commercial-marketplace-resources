# ![Alt Azure Marketplace shopping bag icon](images/Azure_Store_Marketplace_COLOR.svg "Azure Marketplace icon") Microsoft Marketplace Resources Index

This repository provides pointers to repositories and learning resources to help understand the Microsoft commercial marketplace. Please submit a pull request if there is a sample you have developed. If there is a sample you wish existed, please add it to our [Issues](https://github.com/microsoft/commercial-marketplace-samples/issues).

Included in this document is technical learning content, links to sample code, reference implementations, webinars, and key documentation. These resources focus on transactable offer types in the Azure marketplace.

<!-- no toc -->
- [SaaS offers](#saas-offers)
  - [Sample projects](#sample-projects)
  - [Learning resources](#learning-resources)
  - [Key links and documentation](#key-links-and-documentation)
- [Virtual Machine offers](#virtual-machine-offers)
  - [Sample projects](#sample-projects-1)
  - [Learning resources](#learning-resources-1)
  - [Key links and documentation](#key-links-and-documentation-1)
- [Azure Managed Application offers](#azure-managed-application-offers)
  - [Sample projects](#sample-projects-2)
  - [Learning resources](#learning-resources-2)
  - [Key links and documentation](#key-links-and-documentation-2)
- [General marketplace knowledge](#general-marketplace-knowledge)
  - [Sample projects](#sample-projects-3)
  - [Learning resources](#learning-resources-3)
  - [Key links and documentation](#key-links-and-documentation-3)

## SaaS offers

### Client libraries (In progress)

The following repositories are not guaranteed through Microsoft support. They are intended as samples and reference implementations.

- Client library for .NET | [Repository](https://github.com/microsoft/commercial-marketplace-client-dotnet) | [NuGet](https://www.nuget.org/packages/Marketplace.SaaS.Client)
- Client library for Java | [Repository](https://github.com/microsoft/commercial-marketplace-client-java)

The following apply to the REST API.

- Open API Specification (OAS) for REST Fulfillment API v2 and Metering API | [Specification](https://github.com/microsoft/commercial-marketplace-openapi)
- [Postman scripts for REST APIs](./src/postman/README.md)

### Sample projects

- [SaaS Accelerator](https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator) - A complete reference implementation of a SaaS offer you can use to jumpstart your SaaS solution into the Azure marketplace
- [Commercial Marketplace Solutions](https://github.com/microsoft/commercial-marketplace-solutions) - A set of solutions for various scenarios to do with various offer types.

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

#### Microsoft Learn courses

- [Create a SaaS offer for the commercial marketplace](https://docs.microsoft.com/learn/modules/create-saas-offer-commercial-marketplace/)

### Key links and documentation

- [How to plan a SaaS offer for the commercial marketplace](https://docs.microsoft.com/azure/marketplace/plan-saas-offer)
- [Build the landing page for your transactable SaaS offer in the commercial marketplace](https://docs.microsoft.com/azure/marketplace/azure-ad-transactable-saas-landing-page)
- [SaaS fulfillment APIs version 2 in the commercial marketplace](https://docs.microsoft.com/azure/marketplace/partner-center-portal/pc-saas-fulfillment-api-v2)
- [Metered billing for SaaS using the commercial marketplace metering service](https://docs.microsoft.com/azure/marketplace/partner-center-portal/saas-metered-billing)

## Virtual Machine offers

### Sample projects

- [Building a Linux or Windows Virtual Machine for the Azure Marketplace](https://github.com/microsoft/commerical-marketplace-vm-sample)
- [Marketplace VM Samples with Packer and Terraform](https://github.com/microsoft/commerical-marketplace-vm-sample)
- [VM Sample with GitHub Actions](https://github.com/microsoft/commercial-marketplace-offer-solution/tree/main/marketplace/virtual-machine/basic-windows-vm)

### Learning resources

#### Mastering the Marketplace learning library

This library of technical content is designed to help speed your time to publish your virtual machine offer to the Azure marketplace.

[View the course here](https://github.com/microsoft/Mastering-the-Marketplace/tree/main/vm).

#### Microsoft Learn courses

- [Create a virtual machine offer for the commercial marketplace](https://docs.microsoft.com/learn/modules/create-vm-offer-commercial-marketplace/)

#### Webinars

> For access to webinar recordings you will be asked to register to view the content.

- [Transactable Virtual Machine Offer Overview](https://microsoftcloudpartner.eventbuilder.com/event/40202)
- [Building a Virtual Machine offer](https://microsoftcloudpartner.eventbuilder.com/event/38108)
- [The Virtual Machine Offer Validation Process](https://microsoftcloudpartner.eventbuilder.com/event/39384)

#### Community content

- [Video: Create Azure VM image for Azure Marketplace Virtual Machine Offer using Packer with VHD destination](https://www.youtube.com/watch?v=AcsXUuYCvQw)
- [Video: Creating Azure VM image for Azure Marketplace Virtual Machine Offer using Packer with Azure Shared Image Gallery](https://www.youtube.com/watch?v=FVPiecI5r3s)
- [Video: Publishing Azure Marketplace Virtual Machine Offer in Partner Center using SAS VHD URL](https://www.youtube.com/watch?v=44v3lseTsP0)
- [Video: Using Cloud Partner Portal CPP API for managing "Virtual Machine" offers in Azure Marketplace](https://www.youtube.com/watch?v=3LDwrq7a8E8)
- [Video: Deploying and testing "Preview" Azure VM Offer published in Azure Marketplace](https://youtu.be/BJjdoHAIap8)
- [Lab: Publish a VM Offer](https://www.azurecitadel.com/marketplace/vmoffer/): An end to end walkthrough of building a VM Offer from creating the technical assets to publishing in Partner Center.



### Key links and documentation

  - [Plan a virtual machine offer](https://docs.microsoft.com/azure/marketplace/marketplace-virtual-machines)
  - [Create a virtual machine using an approved base](https://docs.microsoft.com/azure/marketplace/azure-vm-create-using-approved-base)
  - [Create a virtual machine using your own image](https://docs.microsoft.com/azure/marketplace/azure-vm-create-using-own-image)
  - [Troubleshoot virtual machine certification](https://docs.microsoft.com/azure/marketplace/partner-center-portal/vm-certification-issues-solutions)

## Azure Managed Application offers

### Sample projects

- [Metered Billing Accelerator](https://github.com/microsoft/commercial-marketplace-ama-metering-accelerator)
- [Azure App Management Extras](https://github.com/Azure/azure-marketplace-management-extras) - Contains two Azure Function applications designed to help Managed Application solution owners in Partner Centre monitor and manage their deployed apps.
- [Commercial Marketplace Solutions](https://github.com/microsoft/commercial-marketplace-solutions) - A set of solutions for various scenarios to do with various offer types.
  
### Learning resources

#### Mastering the Marketplace learning library

This library of technical content is designed to help speed your time to publish your Azure Managed Application offer to the Azure marketplace.

- [Mastering Azure Managed Applications](https://github.com/microsoft/Mastering-the-Marketplace/blob/main/ama/README.md)

#### Webinars

> For access to webinar recordings you will be asked to register to view the content.

- [Managed Applications Overview](https://microsoftcloudpartner.eventbuilder.com/event/28512)
- [Transactable Azure Managed Application Overview](https://microsoftcloudpartner.eventbuilder.com/event/40203)
- [Walkthrough of publishing an Azure Managed Application (AMA) to Partner Center](https://microsoftcloudpartner.eventbuilder.com/event/42625)
- [Working with Managed Application package artifacts](https://microsoftcloudpartner.eventbuilder.com/event/43714)
- [Creating Dynamic UIs for Managed Applications](https://microsoftcloudpartner.eventbuilder.com/event/38112)
- [Azure Managed Applications and Custom Providers](https://microsoftcloudpartner.eventbuilder.com/event/43703)


#### Community content

- [Creating and testing a simple Azure Managed Application in the developer’s Azure subscription](https://www.youtube.com/watch?v=eCGFmUirLGU)
- [Publishing Azure Managed App in Partner Center and testing in end-customer’s Azure subscription](https://www.youtube.com/watch?v=3ODHzEjomro)
- [Refreshing Azure Managed Application permissions and using Managed App's Identity](https://www.youtube.com/watch?v=sDjY_mD3fqY)
- [Adding cross-tenant role assignments for Managed Identity in Azure Managed Application](https://www.youtube.com/watch?v=zAbOlqf21No)
- [Using Partner Center Ingestion API for managing "Azure Application" offers in Azure Marketplace](https://youtu.be/omEjvvF9g6Y)

### Key links and documentation

  - [Plan an Azure Application offer for the commercial marketplace](https://docs.microsoft.com/azure/marketplace/plan-azure-application-offer)
  - [Publishing guide for Azure managed applications](https://docs.microsoft.com/azure/marketplace/marketplace-managed-apps)

## Azure Container offers for kubernetes apps
### Sample projects
- [Azure Vote Code](https://github.com/Azure-Samples/kubernetes-offer-samples)
- [Azure Managed Application with Container Offer bundle](https://github.com/microsoft/commercial-marketplace-solutions/tree/main/container-offer-samples/container-azure-app-bundle)
- [Azure Container boilerplate](https://github.com/microsoft/commercial-marketplace-solutions/tree/main/container-offer-samples/container-bolierplate-template)
- [Azure Container with Custom Meters](https://github.com/microsoft/commercial-marketplace-solutions/tree/main/container-offer-samples/container-custom-meter)
### Learning resources

#### Mastering the Marketplace learning library

This library of technical content is designed to help speed your time to publish your container offer to the Azure marketplace.

[View the course here](https://microsoft.github.io/Mastering-the-Marketplace/container/).

#### Microsoft Learn courses

- [Create a Container offer for the commercial marketplace](https://learn.microsoft.com/en-us/partner-center/marketplace/azure-container-offer-setup)
  
## General marketplace knowledge

### Sample projects

- [HubSpot CRM Integration](https://github.com/santhoshb-msft/amp-leadgen2hubspot)

### Learning resources

#### Webinars

> For access to previous webinars you will be asked to register to view the content.

- [Introduction to Commercial Marketplace transactable offer types](https://microsoftcloudpartner.eventbuilder.com/event/40200)
- [Developing for commercial marketplace](https://microsoftcloudpartner.eventbuilder.com/event/32337): Join the Microsoft Architect team to discuss what is new in the Commercial Marketplace, deep dives on a rotating list of developer topics, and live Q&A to help you get your solution published.
- [Transactable Offer Types](https://microsoftcloudpartner.eventbuilder.com/event/38053)
- [Common Consumption Meters for Azure Marketplace](https://microsoftcloudpartner.eventbuilder.com/event/28507)

#### Microsoft Learn content

- [Introduction to the Microsoft commercial marketplace](https://docs.microsoft.com/learn/modules/intro-commercial-marketplace/)
- [Go to market through the commercial marketplace](https://docs.microsoft.com/learn/modules/go-to-market-commercial-marketplace/)
- [Simplify cloud procurement and governance with Azure Marketplace](https://docs.microsoft.com/learn/modules/simplify-cloud-procurement-governance-azure-marketplace/)

### Key links and documentation

- [Join the Microsoft Partner Network](https://partner.microsoft.com/en-us/dashboard/account/v3/enrollment/introduction/partnership)
- [Create a commercial marketplace account in Partner Center](https://docs.microsoft.com/en-us/azure/marketplace/create-account)
- [Partner Center](https://partner.microsoft.com/dashboard) (You must be a Microsoft partner and have an account)
- [Microsoft commercial marketplace documentation home](https://docs.microsoft.com/azure/marketplace/)
- [GitHub commercial marketplace project template](https://github.com/microsoft/commercial-marketplace-offer-solution)






