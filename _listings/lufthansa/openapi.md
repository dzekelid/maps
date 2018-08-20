---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /offers/seatmaps/{flightNumber}/{origin}/{destination}/{date}/{cabinClass}:
    get:
      summary: Seat Maps
      description: Cabin layout and seat characteristics.
      operationId: OffersSeatmapsDestinationDateCabinClassByFlightNumberAndOriginGet
      x-api-path-slug: offersseatmapsflightnumberorigindestinationdatecabinclass-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: cabinClass
        description: 'Cabin class: M, E, C, F'
      - in: path
        name: date
        description: Departure date (YYYY-MM-DD)
      - in: path
        name: destination
        description: Destination airport
      - in: path
        name: flightNumber
        description: Flight number including carrier code and any suffix (e
      - in: path
        name: origin
        description: Departure airport
      responses:
        200:
          description: OK
      tags:
      - Offers
      - Seatmaps
      - FlightNumber
      - Origin
      - Destination
      - Date
      - CabinClass
---