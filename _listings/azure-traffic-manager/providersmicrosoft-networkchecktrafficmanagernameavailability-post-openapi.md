---
swagger: "2.0"
x-collection-name: Azure Traffic Manager
x-complete: 0
info:
  title: Azure Traffic Manager API Profiles Check Traffic Manager Relative Dns Name
    Availability
  version: 1.0.0
  description: Checks the availability of a Traffic Manager Relative DNS name.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficmanagerprofiles/{profileName}/{endpointType}/{endpointName}
  : patch:
      summary: Endpoints Update
      description: Update a Traffic Manager endpoint.
      operationId: Endpoints_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-patch
      parameters:
      - in: path
        name: endpointName
        description: The name of the Traffic Manager endpoint to be updated
      - in: path
        name: endpointType
        description: The type of the Traffic Manager endpoint to be updated
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The Traffic Manager endpoint parameters supplied to the Update
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileName
        description: The name of the Traffic Manager profile
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the Traffic Manager
          endpoint to be updated
      responses:
        200:
          description: OK
      tags:
      - Endpoints
    get:
      summary: Endpoints Get
      description: Gets a Traffic Manager endpoint.
      operationId: Endpoints_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-get
      parameters:
      - in: path
        name: endpointName
        description: The name of the Traffic Manager endpoint
      - in: path
        name: endpointType
        description: The type of the Traffic Manager endpoint
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: The name of the Traffic Manager profile
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the Traffic Manager
          endpoint
      responses:
        200:
          description: OK
      tags:
      - Endpoints
    put:
      summary: Endpoints Create Or Update
      description: Create or update a Traffic Manager endpoint.
      operationId: Endpoints_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-put
      parameters:
      - in: path
        name: endpointName
        description: The name of the Traffic Manager endpoint to be created or updated
      - in: path
        name: endpointType
        description: The type of the Traffic Manager endpoint to be created or updated
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The Traffic Manager endpoint parameters supplied to the CreateOrUpdate
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileName
        description: The name of the Traffic Manager profile
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the Traffic Manager
          endpoint to be created or updated
      responses:
        200:
          description: OK
      tags:
      - Endpoints
    delete:
      summary: Endpoints Delete
      description: Deletes a Traffic Manager endpoint.
      operationId: Endpoints_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networktrafficmanagerprofilesprofilenameendpointtypeendpointname-delete
      parameters:
      - in: path
        name: endpointName
        description: The name of the Traffic Manager endpoint to be deleted
      - in: path
        name: endpointType
        description: The type of the Traffic Manager endpoint to be deleted
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: The name of the Traffic Manager profile
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the Traffic Manager
          endpoint to be deleted
      responses:
        200:
          description: OK
      tags:
      - Endpoints
  /providers/Microsoft.Network/checkTrafficManagerNameAvailability:
    post:
      summary: Profiles Check Traffic Manager Relative Dns Name Availability
      description: Checks the availability of a Traffic Manager Relative DNS name.
      operationId: Profiles_CheckTrafficManagerRelativeDnsNameAvailability
      x-api-path-slug: providersmicrosoft-networkchecktrafficmanagernameavailability-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The Traffic Manager name parameters supplied to the CheckTrafficManagerNameAvailability
          operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Profiles Traffic Manager Relative Dns Name Availability
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---