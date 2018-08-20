---
swagger: "2.0"
x-collection-name: Azure Logic Apps
x-complete: 0
info:
  title: Azure Logic Apps API Maps Delete
  description: Deletes an integration account map.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Logic/integrationAccounts/{integrationAccountName}/maps/{mapName}
  : get:
      summary: Maps Get
      description: Gets an integration account map.
      operationId: Maps_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnamemapsmapname-get
      parameters:
      - in: path
        name: integrationAccountName
        description: The integration account name
      - in: path
        name: mapName
        description: The integration account map name
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The resource group name
      responses:
        200:
          description: OK
      tags:
      - Maps
    put:
      summary: Maps Create Or Update
      description: Creates or updates an integration account map.
      operationId: Maps_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnamemapsmapname-put
      parameters:
      - in: path
        name: integrationAccountName
        description: The integration account name
      - in: body
        name: map
        description: The integration account map
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: mapName
        description: The integration account map name
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The resource group name
      responses:
        200:
          description: OK
      tags:
      - Maps
    delete:
      summary: Maps Delete
      description: Deletes an integration account map.
      operationId: Maps_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnamemapsmapname-delete
      parameters:
      - in: path
        name: integrationAccountName
        description: The integration account name
      - in: path
        name: mapName
        description: The integration account map name
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The resource group name
      responses:
        200:
          description: OK
      tags:
      - Maps
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