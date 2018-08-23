---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Intelligent Mapping Rename a map
  description: Updates the name of the map that has the specified identifier.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/maps:
    post:
      summary: Create a map
      description: Creates a map with the specified name.
      operationId: creates-a-map-with-the-specified-name
      x-api-path-slug: v1maps-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Map
    get:
      summary: List all maps for a customer
      description: |-
        Returns an array of maps for the specified customer. The array contains
        the name and identifier for each map.
      operationId: returns-an-array-of-maps-for-the-specified-customer-the-array-containsthe-name-and-identifier-for-ea
      x-api-path-slug: v1maps-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Mapsa
      - Customer
  /v1/maps/{mapId}:
    get:
      summary: Return map details
      description: |-
        For the specified map identifier, returns the map properties and an
        array of the associated layers. For each layer, the identifier, name and
        Uniform Resource Identifier (URI) are returned.
      operationId: for-the-specified-map-identifier-returns-the-map-properties-and-anarray-of-the-associated-layers-for
      x-api-path-slug: v1mapsmapid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Return
      - Map
      - Details
    delete:
      summary: Delete a map
      description: |-
        Deletes the map with the specified identifier. Any layers associated
        with the map are also deleted.
      operationId: deletes-the-map-with-the-specified-identifier-any-layers-associatedwith-the-map-are-also-deleted
      x-api-path-slug: v1mapsmapid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Map
    put:
      summary: Rename a map
      description: Updates the name of the map that has the specified identifier.
      operationId: updates-the-name-of-the-map-that-has-the-specified-identifier
      x-api-path-slug: v1mapsmapid-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Rename
      - Map
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