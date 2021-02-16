# Microsoft Commercial Marketplace samples index

This is a list of repositories of samples we find useful in understanding Microsoft Commercial Marketplace concepts. Please submit a pull request if there is a sample you have developed, or find that you think that may benefit the community by adding a section under the relevant offer type with a short description and a link to the sample repo.

## SaaS offers

### Clients for Fulfillment and Metering APIs

We are using an Open API Specification (OAS) document (previously known as Swagger) for generating open source community API clients targeting different programming languages. Currently the following are available (all in preview).

- OAS document for Fulfillment API v2 and Metering service API, https://github.com/microsoft/commercial-marketplace-openapi 
- Client library for .NET, https://github.com/microsoft/commercial-marketplace-client-dotnet
- Client library for Java, https://github.com/microsoft/commercial-marketplace-client-java
- Client library for Python, https://github.com/microsoft/commercial-marketplace-client-python, [PyPi](https://pypi.org/project/azuremarketplace/)
- Client library for Node.js (coming soon), https://github.com/microsoft/commercial-marketplace-sdk-node
- Client library for Go (coming soon), https://github.com/microsoft/commercial-marketplace-sdk-go

### Basic integration and manual onboarding sample (a.k.a. Contoso sample)
Some solutions require out-of-band or manual on-boarding steps, such as validating a customer, running scripts manually for deploying resources needed for a new customer etc. This sample uses email notifications for a new customer, or any changes on the subscription status made outside of the solution code.

[GitHub repo](https://github.com/microsoft/Commercial-Marketplace-SaaS-Manual-On-Boarding)

### Complete Sample for customer registration, provisioning and subscription management (a.k.a. Microsoft Commercial Marketplace transactable SaaS offer SDK)
The sample code provides a framework for excercising the commercial marketplace billing system, including the SaaS Fulfillment API (v2) and Marketplace Metering Service API. Leveraging the SDK, the sample code demonstrates how a typical SaaS platform interacts with the marketplace APIs in order to provision subscriptions for customers, enable logging, and manage commercial marketplace subscriptions.

![Usecase](https://github.com/Azure/Microsoft-commercial-marketplace-transactable-SaaS-offer-SDK/blob/main/docs/images/sdk_overview.png)

[GitHub repo](https://github.com/Azure/Microsoft-commercial-marketplace-transactable-SaaS-offer-SDK)


## Azure application offers - Azure managed applications

### Custom metering, retrieving "resourceId" for a subscription
There are multiple approaches when a managed application needs to post usage to metering service. This set of notes and samples go through those approaches, and explain the relationship between them.

[GitHub repo](https://github.com/microsoft/commercial-marketplace-managed-application-metering-samples)


## Azure virtual machine offers

## Lead management integration samples
- [HubSpot Integration](https://github.com/santhoshb-msft/amp-leadgen2hubspot)

## References and resources

- Azure virtual machine offers
  - [Overview](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-virtual-machines)
  - [Technical assets](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/vm-certification-issues-solutions)
  - [Simple Azure Marketplace Virtual Machine Offer: creating VM images and publishing in Partner Center](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/simple-azure-marketplace-virtual-machine-offer-creating-vm/ba-p/2058093)

- Azure application offers - Solution Template Offers
  - [Overview](https://docs.microsoft.com/en-us/azure/marketplace/plan-azure-application-offer)
  - [Azure QuickStart Templates](https://github.com/github/azure-quickstart-templates)
  - [MS Build 2018 Presentation: Building Solution Templates and Managed Applications for the Azure Marketplace](https://channel9.msdn.com/Events/Build/2018/BRK3603)
    
- Azure application offers - Azure managed applications
  - [Overview](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-managed-apps)
  - [Simple Azure Managed Application: creating, testing, and publishing in Partner Center](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/simple-azure-managed-application-creating-testing-and-publishing/ba-p/2071773)

- SaaS offers
  - [Overview](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-managed-apps)
  - [Fulfillment APIs version 2 reference](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-api-v2)
- [Marketplace metering service API reference](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/marketplace-metering-service-apis)
