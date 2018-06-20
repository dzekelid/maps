---
swagger: "2.0"
x-collection-name: Weather Underground
x-complete: 0
info:
  title: Weather Underground Get Key Radar Image.gif Maxlat 42.35%26maxlon 109.311%26minlat
    39.27%26minlon 114.644%26wth 600%26height 480%26newmaps 0
  description: This example will return dynamic radar image around Salt Lake City,
    UT with a transparent background. See Docs for all the options for creating these
    images.
  version: 1.0.0
host: api.wunderground.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{key}/radar/image.gif?maxlat=42.35%26maxlon=-109.311%26minlat=39.27%26minlon=-114.644%26width=600%26height=480%26newmaps=0:
    get:
      summary: Get Key Radar Image.gif Maxlat 42.35%26maxlon 109.311%26minlat 39.27%26minlon
        114.644%26wth 600%26height 480%26newmaps 0
      description: This example will return dynamic radar image around Salt Lake City,
        UT with a transparent background. See Docs for all the options for creating
        these images.
      operationId: Get_radar_example_
      x-api-path-slug: keyradarimage-gifmaxlat42-3526maxlon109-31126minlat39-2726minlon114-64426width60026height48026newmaps0-get
      parameters:
      - in: query
        name: height
        description: The height
        type: string
        format: string
      - in: query
        name: maxlat
        description: Max longitude
        type: string
        format: string
      - in: query
        name: maxlon
        description: Max longitude
        type: string
        format: string
      - in: query
        name: minlat
        description: Min latitude
        type: string
        format: string
      - in: query
        name: minlon
        description: Min longitude
        type: string
        format: string
      - in: query
        name: width
        description: The width
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Radar
      - Image
      - Gif?maxlat=42
      - 35%26maxlon=-109
      - 311%26minlat=39
      - 27%26minlon=-114
      - 644%26width=600%26height=480%26newmaps=0
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