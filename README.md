# ![Alt Azure Marketplace shopping bag icon](images/Azure_Store_Marketplace_COLOR.svg "Azure Marketplace icon") Microsoft Marketplace Samples and Resources Index

This repository provides pointers to resources to help you onboard your solution to the Microsoft commercial marketplace. These resources focus on transactable offer types in the Microsoft commercial marketplace.

Included in this document are links to sample code, technical learning content, reference implementations, and key documentation. 

**Included in this document**

- [SaaS offers](#saas-offers)
  - [Client libraries](#saas-client-libraries)
  - [Learning resources](#saas-learning-resources)
  - [Sample projects](#saas-sample-projects)
  - [Key links and documentation](#saas-key-links-and-documentation)
- [Virtual Machine offers](#virtual-machine-offers)
  - [Learning resources](#vm-learning-resources)
  - [Sample projects](#vm-sample-projects)
  - [Key links and documentation](#vm-key-links-and-documentation)
- [Azure Managed Application offers](#azure-managed-application-offers)
  - [Learning resources](#ama-learning-resources)
  - [Sample projects](#ama-sample-projects)
  - [Key links and documentation](#ama-key-links-and-documentation)
- [General marketplace knowledge](#general-marketplace-knowledge)
    - [Sample projects](#general-sample-projects)
    - [Learning resources](#general-learning-resources)
    - [Key links and documentation](#general-key-links-and-documentation)

## SaaS offers

### <a name="saas-client-libraries">Client libraries</a>

The following repositories are not guaranteed through Microsoft support. They are intended as samples and reference implementations.

- Open API Specification (OAS) for REST Fulfillment API v2 and Metering API | [Specification](https://github.com/microsoft/commercial-marketplace-openapi)
- Client library for .NET | [Repository](https://github.com/microsoft/commercial-marketplace-client-dotnet) | [NuGet](https://www.nuget.org/packages/Marketplace.SaaS.Client)
- Client library for Java | [Repository](https://github.com/microsoft/commercial-marketplace-client-java)
- Client library for Python | [Repository](https://github.com/microsoft/commercial-marketplace-client-python) | [PyPi](https://pypi.org/project/azuremarketplace/)
- Client library for Node.js | [Repository](https://github.com/microsoft/commercial-marketplace-client-node) | [NPM for SaaS](https://www.npmjs.com/package/microsoft.marketplace.saas) | [NPM for Metering](https://www.npmjs.com/package/microsoft.marketplace.metering)
- Client library for Go (coming soon) | [Repository](https://github.com/microsoft/commercial-marketplace-client-go)

### <a name="saas-learning-resources">Learning resources</a>

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

### <a name="saas-sample-projects">Sample projects</a>

- [SaaS Accelerator](https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator) - A complete reference implementation of a SaaS offer

### <a name="saas-key-links-and-documentation">Key links and documentation</a>

- [How to plan a SaaS offer for the commercial marketplace](https://docs.microsoft.com/azure/marketplace/plan-saas-offer)
- [Build the landing page for your transactable SaaS offer in the commercial marketplace](https://docs.microsoft.com/azure/marketplace/azure-ad-transactable-saas-landing-page)
- [SaaS fulfillment APIs version 2 in the commercial marketplace](https://docs.microsoft.com/azure/marketplace/partner-center-portal/pc-saas-fulfillment-api-v2)
- [Metered billing for SaaS using the commercial marketplace metering service](https://docs.microsoft.com/azure/marketplace/partner-center-portal/saas-metered-billing)

## Virtual Machine offers

### <a name="vm-learning-resources">Learning resources</a>

#### Webinars

> For access to webinar recordings you will be asked to register to view the content.

- [Transactable Virtual Machine Offer Overview](https://microsoftcloudpartner.eventbuilder.com/event/40202)
- [Building a Virtual Machine offer](https://microsoftcloudpartner.eventbuilder.com/event/38108)
- [The Virtual Machine Offer Validation Process](https://microsoftcloudpartner.eventbuilder.com/event/39384)

#### Microsoft Learn courses

- [Create a virtual machine offer for the commercial marketplace](https://docs.microsoft.com/learn/modules/create-vm-offer-commercial-marketplace/)

#### Community content

- [Create Azure VM image for Azure Marketplace Virtual Machine Offer using Packer with VHD destination](https://www.youtube.com/watch?v=AcsXUuYCvQw)
- [Creating Azure VM image for Azure Marketplace Virtual Machine Offer using Packer with Azure Shared Image Gallery](https://www.youtube.com/watch?v=FVPiecI5r3s)
- [Publishing Azure Marketplace Virtual Machine Offer in Partner Center using SAS VHD URL](https://www.youtube.com/watch?v=44v3lseTsP0)
- [Using Cloud Partner Portal CPP API for managing "Virtual Machine" offers in Azure Marketplace](https://www.youtube.com/watch?v=3LDwrq7a8E8)
- [Deploying and testing "Preview" Azure VM Offer published in Azure Marketplace](https://youtu.be/BJjdoHAIap8)

### <a name="vm-sample-projects">Sample projects</a>

- [Building a Linux or Windows Virtual Machine for the Azure Marketplace](https://github.com/microsoft/commerical-marketplace-vm-sample)
- [Marketplace VM Samples with Packer and Terraform](https://github.com/microsoft/commerical-marketplace-vm-sample)

### <a name="vm-key-links-and-documentation">Key links and documentation</a>

  - [Plan a virtual machine offer](https://docs.microsoft.com/azure/marketplace/marketplace-virtual-machines)
  - [Create a virtual machine using an approved base](https://docs.microsoft.com/azure/marketplace/azure-vm-create-using-approved-base)
  - [Create a virtual machine using your own image](https://docs.microsoft.com/azure/marketplace/azure-vm-create-using-own-image)
  - [Troubleshoot virtual machine certification](https://docs.microsoft.com/azure/marketplace/partner-center-portal/vm-certification-issues-solutions)
  
## Azure Managed Application offers

### <a name="ama-learning-resources">Learning resources</a>

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

### <a name="ama-sample-projects">Sample projects</a>

- [Posting Usage With the Azure Managed Application Metered Billing API](https://github.com/microsoft/commercial-marketplace-managed-application-metering-samples)


### <a name="ama-key-links-and-documentation">Key links and documentation</a>

  - [Plan an Azure Application offer for the commercial marketplace](https://docs.microsoft.com/azure/marketplace/plan-azure-application-offer)
  - [Publishing guide for Azure managed applications](https://docs.microsoft.com/azure/marketplace/marketplace-managed-apps)

## General marketplace knowledge

### <a name="general-sample-projects">Sample projects</a>

- [HubSpot CRM Integration](https://github.com/santhoshb-msft/amp-leadgen2hubspot)





### <a name="general-learning-resources">Learning resources</a>

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

### <a name="general-key-links-and-documentation">Key links and documentation</a>

- [Join the Microsoft Partner Network](https://partner.microsoft.com/en-us/dashboard/account/v3/enrollment/introduction/partnership)
- [Create a commercial marketplace account in Partner Center](https://docs.microsoft.com/en-us/azure/marketplace/create-account)
- [Partner Center](https://partner.microsoft.com/dashboard) (You must be a Microsoft partner and have an account)
- [Microsoft commercial marketplace documentation home](https://docs.microsoft.com/azure/marketplace/)






## Community content

- [Building a Virtual Machine offer](https://microsoftcloudpartner.eventbuilder.com/event/38108): In this session, we will cover how to build and test a Virtual Machine offer for the Azure Marketplace. This includes pointers to example implementations of building images.
- [VM Content and Metadata Validation Process](https://microsoftcloudpartner.eventbuilder.com/event/39384): Becky Gaudet will explain how Azure Virtual Machine offer content and metadata validation works. She will focus on common issues seen by the validation team. She will also explain the process and highlight any recent changes to the VM validation process. 
- [Lab: Publish a VM Offer](https://www.azurecitadel.com/marketplace/vmoffer/): An end to end walkthrough of building a VM Offer from creating the technical assets to publishing in Partner Center.
