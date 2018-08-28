---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Dataflow API Constant map update
  description: Updates the constant map corresponding to the provided constant map
    ref. This is only authorized if the constant map has been created by the subscriber
    (not provided by the system).
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
  /constantMaps/{constantMapRef}:
    get:
      summary: Constant map retrieval
      description: Retrieves the constant map corresponding to the provided constant
        map ref..
      operationId: retrieves-the-constant-map-corresponding-to-the-provided-constant-map-ref
      x-api-path-slug: constantmapsconstantmapref-get
      parameters:
      - in: path
        name: constantMapRef
        description: Ref of the constant map to retrieve
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Map
      - Retrieval
    put:
      summary: Constant map update
      description: Updates the constant map corresponding to the provided constant
        map ref. This is only authorized if the constant map has been created by the
        subscriber (not provided by the system).
      operationId: updates-the-constant-map-corresponding-to-the-provided-constant-map-ref-this-is-only-authorized-if-t
      x-api-path-slug: constantmapsconstantmapref-put
      parameters:
      - in: body
        name: constantMap
        description: Contents of the constant map to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: constantMapRef
        description: Ref of the constant map to update
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Map
      - Update
    delete:
      summary: Constant map deletion
      description: Deletes the constant map corresponding to the provided constant
        map ref. This is only authorized if the constant map has been created by the
        subscriber (not provided by the system).
      operationId: deletes-the-constant-map-corresponding-to-the-provided-constant-map-ref-this-is-only-authorized-if-t
      x-api-path-slug: constantmapsconstantmapref-delete
      parameters:
      - in: path
        name: constantMapRef
        description: Ref of the constant map to delete
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Map
      - Deletion
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