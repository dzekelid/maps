---
swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 1
info:
  title: Broadleaf Commerce API
  description: the-default-broadleaf-commerce-apis
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mappings:
    get:
      summary: Get Mappings
      description: Get mappings.
      operationId: getMappings
      x-api-path-slug: mappings-get
      responses:
        200:
          description: OK
      tags:
      - Mappings
  /mappings.json:
    get:
      summary: Get Mappings
      description: Get mappings.
      operationId: getMappings.json
      x-api-path-slug: mappings-json-get
      responses:
        200:
          description: OK
      tags:
      - Mappings
---