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
---