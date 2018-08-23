---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/items/attributes/maps:
    get:
      summary: Lists all attribute maps.
      description: Lists all attribute maps..
      operationId: getRestItemsAttributesMaps
      x-api-path-slug: restitemsattributesmaps-get
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Attribute
      - Maps
  /rest/items/attributes/values/maps:
    get:
      summary: Lists all attribute value maps.
      description: Lists all attribute value maps..
      operationId: getRestItemsAttributesValuesMaps
      x-api-path-slug: restitemsattributesvaluesmaps-get
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Attribute
      - Value
      - Maps
  /rest/items/attributes/markets/maps:
    post:
      summary: Creates a new attribute map.
      description: Creates a new attribute map..
      operationId: postRestItemsAttributesMarketsMaps
      x-api-path-slug: restitemsattributesmarketsmaps-post
      parameters:
      - in: body
        name: /rest/items/attributes/markets/maps
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Attribute
      - Map
  /rest/items/attributes/values/markets/maps:
    post:
      summary: Creates a new attribute value map.
      description: Creates a new attribute value map..
      operationId: postRestItemsAttributesValuesMarketsMaps
      x-api-path-slug: restitemsattributesvaluesmarketsmaps-post
      parameters:
      - in: body
        name: /rest/items/attributes/values/markets/maps
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Attribute
      - Value
      - Map
  /rest/items/attributes/{attributeId}/markets/{marketId}/maps:
    delete:
      summary: Deletes an attribute map.
      description: Deletes an attribute map. The ID of the attribute and the ID of
        the market must be specified.
      operationId: deleteRestItemsAttributesAttributeMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidmarketsmarketidmaps-delete
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Map
    get:
      summary: Gets an attribute map.
      description: Gets an attribute map. The ID of the attribute and the ID of the
        market must be specified.
      operationId: getRestItemsAttributesAttributeMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidmarketsmarketidmaps-get
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Map
    put:
      summary: Updates an attribute map.
      description: Updates an attribute map. The ID of the attribute and the ID of
        the market must be specified.
      operationId: putRestItemsAttributesAttributeMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidmarketsmarketidmaps-put
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Map
  /rest/items/attributes/{attributeId}/values/{attributeValueId}/markets/{marketId}/maps:
    delete:
      summary: Deletes an attribute value map.
      description: Deletes an attribute value map. The ID of the attribute, the ID
        of the attribute value and the ID of the market must be specified.
      operationId: deleteRestItemsAttributesAttributeValuesAttributevalueMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-delete
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: attributeValueId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Value
      - Map
    get:
      summary: Gets an attribute value map.
      description: Gets an attribute value map. The ID of the attribute, the ID of
        the attribute value and the ID of the market must be specified.
      operationId: getRestItemsAttributesAttributeValuesAttributevalueMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-get
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: attributeValueId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Value
      - Map
    put:
      summary: Updates an attribute value map.
      description: Updates an attribute value map. The ID of the attribute, the ID
        of the attribute value and the ID of the market must be specified.
      operationId: putRestItemsAttributesAttributeValuesAttributevalueMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-put
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: attributeValueId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Value
      - Map
---