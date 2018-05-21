---
name: Azure Traffic Manager
x-slug: azure-traffic-manager
description: 'Azure Traffic Manager gives you three methods for traffic routing: failover,
  performance, or weighted round-robin. Choose the one that&rsquo;s right for your
  application or scenario.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Traffic Manager
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Traffic Manager API Endpoints Update
  x-api-slug: azure-traffic-manager-api
  description: Update a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}/{endpointType}/{endpointName}
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilenameendpointtypeendpointname-patch-openapi.md
- name: Azure Traffic Manager API Endpoints Get
  x-api-slug: azure-traffic-manager-api
  description: Gets a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}/{endpointType}/{endpointName}
  tags: Endpoints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilenameendpointtypeendpointname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilenameendpointtypeendpointname-get-openapi.md
- name: Azure Traffic Manager API Endpoints Create Or Update
  x-api-slug: azure-traffic-manager-api
  description: Create or update a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}/{endpointType}/{endpointName}
  tags: Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilenameendpointtypeendpointname-put-openapi.md
- name: Azure Traffic Manager API Endpoints Delete
  x-api-slug: azure-traffic-manager-api
  description: Deletes a Traffic Manager endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}/{endpointType}/{endpointName}
  tags: Endpoints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilenameendpointtypeendpointname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilenameendpointtypeendpointname-delete-openapi.md
- name: Azure Traffic Manager API Profiles Check Traffic Manager Relative Dns Name
    Availability
  x-api-slug: azure-traffic-manager-api
  description: Checks the availability of a Traffic Manager Relative DNS name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////providers/Microsoft.Network/checkTrafficManagerNameAvailability
  tags: Profiles Traffic Manager Relative Dns Name Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/providersmicrosoftnetworkchecktrafficmanagernameavailability-post-openapi.md
- name: Azure Traffic Manager API Profiles List By In Resource Group
  x-api-slug: azure-traffic-manager-api
  description: Lists all Traffic Manager profiles within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles
  tags: Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofiles-get-openapi.md
- name: Azure Traffic Manager API Profiles List All
  x-api-slug: azure-traffic-manager-api
  description: Lists all Traffic Manager profiles within a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Network/trafficmanagerprofiles
  tags: Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidprovidersmicrosoftnetworktrafficmanagerprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidprovidersmicrosoftnetworktrafficmanagerprofiles-get-openapi.md
- name: Azure Traffic Manager API Profiles Get
  x-api-slug: azure-traffic-manager-api
  description: Gets a Traffic Manager profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}
  tags: Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilename-get-openapi.md
- name: Azure Traffic Manager API Profiles Create Or Update
  x-api-slug: azure-traffic-manager-api
  description: Create or update a Traffic Manager profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}
  tags: Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilename-put-openapi.md
- name: Azure Traffic Manager API Profiles Delete
  x-api-slug: azure-traffic-manager-api
  description: Deletes a Traffic Manager profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}
  tags: Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilename-delete-openapi.md
- name: Azure Traffic Manager API Profiles Update
  x-api-slug: azure-traffic-manager-api
  description: Update a Traffic Manager profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}
  tags: Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnetworktrafficmanagerprofilesprofilename-patch-openapi.md
- name: Azure Traffic Manager API Geographic Hierarchies Get Default
  x-api-slug: azure-traffic-manager-api
  description: Gets the default Geographic Hierarchy used by the Geographic traffic
    routing method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com////providers/Microsoft.Network/trafficManagerGeographicHierarchies/default
  tags: Geographic Hierarchies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/providersmicrosoftnetworktrafficmanagergeographichierarchiesdefault-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/providersmicrosoftnetworktrafficmanagergeographichierarchiesdefault-get-openapi.md
- name: Azure Traffic Manager API
  x-api-slug: azure-traffic-manager-api
  description: 'Azure Traffic Manager gives you three methods for traffic routing:
    failover, performance, or weighted round-robin. Choose the one that&rsquo;s right
    for your application or scenario.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-traffic-improved-application-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/traffic-manager/
  baseURL: ://management.azure.com//
  tags: Azure Traffic Manager
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-traffic-manager/master/_listings/azure-traffic-manager/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/traffic-manager/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/traffic-manager/
- type: x-service-level-agreement
  url: https://azure.microsoft.com/en-us/support/legal/sla/traffic-manager/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/traffic-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---