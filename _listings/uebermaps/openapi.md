---
swagger: "2.0"
x-collection-name: uebermaps
x-complete: 1
info:
  title: uebermaps
  description: enable-people-to-store-spots-on-public-and-private-maps
  termsOfService: https://uebermaps.com/terms/
  contact:
    name: uebermaps API Team
  version: "2.0"
host: uebermaps.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /maps:
    get:
      summary: List your own maps
      description: List your own maps.
      operationId: maps.get
      x-api-path-slug: maps-get
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Your
      - Own
      - Maps
  /maps/search:
    get:
      summary: Search maps
      description: Search maps
      operationId: maps.search.get
      x-api-path-slug: mapssearch-get
      parameters:
      - in: query
        name: d
        description: Distance
      - in: query
        name: lat
        description: 'Latitude for search radius (default distance: 2000 meter)'
      - in: query
        name: lon
        description: 'Longitude for search radius (default distance: 2000 meter)'
      - in: query
        name: q
        description: Query
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Search
      - Maps
  /respot_maps:
    get:
      summary: List maps that user can respot to
      description: List maps that user can respot to.
      operationId: respot_maps.get
      x-api-path-slug: respot-maps-get
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Maps
      - That
      - User
      - Can
      - Respot
      - To
  /trends/latest:
    get:
      summary: List latest maps
      description: List latest maps.
      operationId: trends.latest.get
      x-api-path-slug: trendslatest-get
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Latest
      - Maps
  /trends/recommended:
    get:
      summary: List recommended maps
      description: List recommended maps.
      operationId: trends.recommended.get
      x-api-path-slug: trendsrecommended-get
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Recommended
      - Maps
---