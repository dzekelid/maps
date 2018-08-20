---
swagger: "2.0"
x-collection-name: Azure Logic Apps
x-complete: 1
info:
  title: LogicManagementClient
  description: rest-api-for-azure-logic-apps-
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
---