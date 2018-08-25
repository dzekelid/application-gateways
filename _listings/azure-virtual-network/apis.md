---
name: Azure Virtual Network
x-slug: azure-virtual-network
description: Azure Virtual Network lets you create private networks in the cloud with
  full control over IP addresses, DNS servers, security rules, and traffic flows.
  Securely connect a virtual network to on-premises networks by using a VPN tunnel,
  or connect privately by using the ExpressRoute service.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Application Gateways
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/apis.md
specificationVersion: "0.14"
apis:
- name: NetworkManagementClient - Application Gateways Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-delete
  description: Deletes the specified application gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-delete-openapi.md
- name: NetworkManagementClient - Application Gateways Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-get
  description: Gets the specified application gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewayname-get-openapi.md
- name: NetworkManagementClient - Application Gateways List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgateways-get
  description: Lists all application gateways in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgateways-get-openapi.md
- name: NetworkManagementClient - Application Gateways List All
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-networkapplicationgateways-get
  description: Gets all the application gateways in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoft-networkapplicationgateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoft-networkapplicationgateways-get-openapi.md
- name: NetworkManagementClient - Application Gateways Start
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamestart-post
  description: Starts the specified application gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamestart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamestart-post-openapi.md
- name: NetworkManagementClient - Application Gateways Stop
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamestop-post
  description: Stops the specified application gateway in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamestop-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamestop-post-openapi.md
- name: NetworkManagementClient - Application Gateways Backend Health
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamebackendhealth-post
  description: Gets the backend health of the specified application gateway in a resource
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamebackendhealth-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkapplicationgatewaysapplicationgatewaynamebackendhealth-post-openapi.md
- name: NetworkManagementClient - Application Gateways List Available Waf Rule Sets
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-networkapplicationgatewayavailablewafrulesets-get
  description: Lists all available web application firewall rule sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoft-networkapplicationgatewayavailablewafrulesets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/application-gateways/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoft-networkapplicationgatewayavailablewafrulesets-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.traffic.manager.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.virtual.network.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/virtual-network/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/virtual-network/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---