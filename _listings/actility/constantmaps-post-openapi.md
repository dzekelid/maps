---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Dataflow API Constant maps creation
  description: Creates a new custom constant map for the subscriber.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /dataflow/v021/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /constantMaps:
    get:
      summary: Constant maps retrieval
      description: Retrieves the list of constant maps (both system-provided and custom)
        available in the scope.
      operationId: retrieves-the-list-of-constant-maps-both-systemprovided-and-custom-available-in-the-scope
      x-api-path-slug: constantmaps-get
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Maps
      - Retrieval
    post:
      summary: Constant maps creation
      description: Creates a new custom constant map for the subscriber.
      operationId: creates-a-new-custom-constant-map-for-the-subscriber
      x-api-path-slug: constantmaps-post
      parameters:
      - in: body
        name: constantMap
        description: Contents of the constant map to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Maps
      - Creation
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