# Microsoft Commercial Marketplace samples index

This is a list of repositories of samples we find useful in understanding Microsoft Commercial Marketplace concepts. Please submit a pull request if there is a sample you have developed, or find that you think that may benefit the community by adding a section under the relevant offer type with a short description and a link to the sample repo.

## SaaS offers

### Clients for Fulfillment and Metering APIs

We are using an Open API Specification (OAS) document (previously known as Swagger) for generating open source community API clients targeting different programming languages. Currently the following are available (all in preview).

- OAS document for Fulfillment API v2 and Metering service API, https://github.com/azure/commercial-marketplace-openapi 
- Client library for .NET, https://github.com/Azure/commercial-marketplace-client-dotnet
- Client library for Java, https://github.com/Azure/commercial-marketplace-client-java
- Client library for Python, https://github.com/Azure/commercial-marketplace-client-python, [PyPi](https://pypi.org/project/azuremarketplace/)
- Client library for Node.js (coming soon), https://github.com/Azure/commercial-marketplace-sdk-node
- Client library for Go (coming soon), https://github.com/Azure/commercial-marketplace-sdk-go

### Basic integration and manual onboarding sample (a.k.a. Contoso sample)
Some solutions require out-of-band or manual on-boarding steps, such as validating a customer, running scripts manually for deploying resources needed for a new customer etc. This sample uses email notifications for a new customer, or any changes on the subscription status made outside of the solution code.

[GitHub repo](https://github.com/Azure-Samples/Commercial-Marketplace-SaaS-Manual-On-Boarding)

### Sample for customer and subscription management (a.k.a. SaaS SDK)
This sample along with its API client library was released during the Microsoft Build in 2020. It demonstrates an approach for managing customers and subscriptions, along with implementing the protocol for managing the lifetime of a SaaS offer subscription using the Fulfillment APIs.

[GitHub repo](https://github.com/Azure/Microsoft-commercial-marketplace-transactable-SaaS-offer-SDK)


## Azure application offers - Azure managed applications

### Custom metering, retrieving "resourceId" for a subscription
There are multiple approaches when a managed application needs to post usage to metering service. This set of notes and samples go through those approaches, and explain the relationship between them.

[GitHub repo](https://github.com/Azure-Samples/commercial-marketplace-managed-application-metering-samples)


## Azure virtual machine offers

## Azure CRM Integration samples
- [HubSpot Integration](https://github.com/santhoshb-msft/amp-leadgen2hubspot)

## References

- Azure virtual machine offers
  - [Overview](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-virtual-machines)
  - [Technical assets](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/vm-certification-issues-solutions)
- Azure application offers - Azure managed applications
  - [Overview](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-managed-apps)

- SaaS offers
  - [Overview](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-managed-apps)
  - [Fulfillment APIs version 2 reference](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-api-v2)
- [Marketplace metering service API reference](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/marketplace-metering-service-apis)
