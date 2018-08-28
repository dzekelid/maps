---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Maps
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/mapview-get-openapi.md
- name: Map Tile API - Terrain Map
  x-api-slug: terrain-day76645256png8-get
  description: |-
    *Request a terrain map tile*

    Terrain map tile are available by passing `terrain.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-openapi.md
- name: Map Tile API - Multiple Base64 Encoded Map Tiles
  x-api-slug: maptilenewestnormal-day63024256png8-get
  description: "*Request multiple base64 encoded map tiles*\n\nA square consisting
    of multiple base64 encoded tiles is requested by adding the parameters `output=base64`
    and `range=NxN` to the request URL. The `column` and `row` in the path of the
    URL, defining the top left-hand corner of the tile group must be divisible by
    the value of the `range` parameter.\n  \n  Click on the response to decode the
    tiles returned.\n\n\n\n* **output**  `text`\n \\- Indicates whether to return
    the tile as base64 encoded text.\n\n* **range**  `enum`\n \\- Indicates the size
    of the array of tiles returned. Valid values are `2x2`, `3x3` or `4x4`\n\n Valid
    values are : `2x2`, `3x3`, `4x4`\n\n* **app_id**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-openapi.md
- name: Map Tile API - Color-reduced Transit Map
  x-api-slug: maptilenewestnormal-day-transit1220741409256png8-get
  description: |-
    *Request a color-reduced map tile with public transport*

    Color-reduced street map tiles with full-color transit overlays are requested by passing `normal.day.transit` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-openapi.md
- name: Map Tile API - Hybrid Map
  x-api-slug: hybrid-day485256png8-get
  description: |-
    *Request a hybrid map tile - satellite imagery with labels*

    Hybrid map tile are available by passing `hybrid.day` in the path of the request URL. The map tiles will display using the default language of the server unless the `lg` query parameter is used to change the map tile language. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-openapi.md
- name: Map Tile API - Truck Restrictions Map
  x-api-slug: trucktilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a street map tile showing restrictions for heavy vehicles*

    To obtain a map tile displaying route restrictions for trucks, use the `trucktile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Toll Zone Map
  x-api-slug: maptilenewestnormal-day9255170256png8-get
  description: |-
    *Request a street map tile highlighting congestion and environmental toll zones*

    To highlight such toll zones, add the `congestion` parameter to the request URL.



    * **congestion**  `null`
     \- Flag to indicate if congestion zones are to be shown on the map.

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-openapi.md
- name: Map Tile API - Satellite Map
  x-api-slug: satellite-day51512256png8-get
  description: |-
    *Request a satellite map tile*

    Satellite map tiles do not display labels and are available by passing `satellite.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-openapi.md
- name: Map Tile API - Fleet Vehicle Map
  x-api-slug: maptilenewestnormal-day1340932723256png8-get
  description: |-
    *Request a street map tile using the fleet vehicle color scheme*

    Fleet color scheme map tiles are available by passing `style=fleet` as a parameter of the request URL.



    * **style**  `enum`
     \- If present, selects the style to use to render the tile.

     Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`, `mini`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-openapi.md
- name: Map Tile API - Base64 Encoded Map Tile
  x-api-slug: maptilenewestnormal-day11525761256png8-get
  description: "*Request a base64 encoded map tile*\n\nBase64 encoded tiles are requested
    by adding the parameter `output=base64` to the request URL.\n  \n  Click on the
    response to decode the tile returned.\n\n\n\n* **output**  `text`\n \\- Indicates
    whether to return the tile as base64 encoded text.\n\n* **app_id**  `text`\n \\-
    A 20 byte Base64 URL-safe encoded string used for the authentication of the client
    application.    You must include an `app_id` with every request.\n\n* **app_code**
    \ `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication
    of the client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-openapi.md
- name: Map Tile API - Color-reduced Street Map
  x-api-slug: maptilenewestnormal-day-grey11525761256png8-get
  description: |-
    *Request a greyed out street map tile*

    Maps using a reduced color palette can be requested by passing `normal.day.grey` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-openapi.md
- name: Map Tile API - Map Tile Type Information
  x-api-slug: info-get
  description: |-
    *Request information about the types of map tiles available on a server*

    To make a request for metadata information, use the `info` parameter in the path of the request URL.



    * **output**  `enum`
     \- Indicates whether to return the information in XML format, JSON format or as an XML schema (XSD) of the API metadata

     Valid values are : `json`, `xml`, `xsd`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-openapi.md
- name: Map Tile API - Transparent Truck Restrictions Map
  x-api-slug: truckonlytilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a transparent tile showing restrictions for heavy vehicles only*

    To obtain a transparent map tile displaying route restrictions for trucks, use the `truckonlytile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Terrain Map
  x-api-slug: terrain-day76645256png8-get
  description: |-
    *Request a terrain map tile*

    Terrain map tile are available by passing `terrain.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-openapi.md
- name: Map Tile API - Terrain Map
  x-api-slug: terrain-day76645256png8-get
  description: |-
    *Request a terrain map tile*

    Terrain map tile are available by passing `terrain.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-openapi.md
- name: Map Tile API - Multiple Base64 Encoded Map Tiles
  x-api-slug: maptilenewestnormal-day63024256png8-get
  description: "*Request multiple base64 encoded map tiles*\n\nA square consisting
    of multiple base64 encoded tiles is requested by adding the parameters `output=base64`
    and `range=NxN` to the request URL. The `column` and `row` in the path of the
    URL, defining the top left-hand corner of the tile group must be divisible by
    the value of the `range` parameter.\n  \n  Click on the response to decode the
    tiles returned.\n\n\n\n* **output**  `text`\n \\- Indicates whether to return
    the tile as base64 encoded text.\n\n* **range**  `enum`\n \\- Indicates the size
    of the array of tiles returned. Valid values are `2x2`, `3x3` or `4x4`\n\n Valid
    values are : `2x2`, `3x3`, `4x4`\n\n* **app_id**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-openapi.md
- name: Map Tile API - Multiple Base64 Encoded Map Tiles
  x-api-slug: maptilenewestnormal-day63024256png8-get
  description: "*Request multiple base64 encoded map tiles*\n\nA square consisting
    of multiple base64 encoded tiles is requested by adding the parameters `output=base64`
    and `range=NxN` to the request URL. The `column` and `row` in the path of the
    URL, defining the top left-hand corner of the tile group must be divisible by
    the value of the `range` parameter.\n  \n  Click on the response to decode the
    tiles returned.\n\n\n\n* **output**  `text`\n \\- Indicates whether to return
    the tile as base64 encoded text.\n\n* **range**  `enum`\n \\- Indicates the size
    of the array of tiles returned. Valid values are `2x2`, `3x3` or `4x4`\n\n Valid
    values are : `2x2`, `3x3`, `4x4`\n\n* **app_id**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-openapi.md
- name: Map Tile API - Color-reduced Transit Map
  x-api-slug: maptilenewestnormal-day-transit1220741409256png8-get
  description: |-
    *Request a color-reduced map tile with public transport*

    Color-reduced street map tiles with full-color transit overlays are requested by passing `normal.day.transit` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-openapi.md
- name: Map Tile API - Color-reduced Transit Map
  x-api-slug: maptilenewestnormal-day-transit1220741409256png8-get
  description: |-
    *Request a color-reduced map tile with public transport*

    Color-reduced street map tiles with full-color transit overlays are requested by passing `normal.day.transit` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-openapi.md
- name: Map Tile API - Hybrid Map
  x-api-slug: hybrid-day485256png8-get
  description: |-
    *Request a hybrid map tile - satellite imagery with labels*

    Hybrid map tile are available by passing `hybrid.day` in the path of the request URL. The map tiles will display using the default language of the server unless the `lg` query parameter is used to change the map tile language. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-openapi.md
- name: Map Tile API - Hybrid Map
  x-api-slug: hybrid-day485256png8-get
  description: |-
    *Request a hybrid map tile - satellite imagery with labels*

    Hybrid map tile are available by passing `hybrid.day` in the path of the request URL. The map tiles will display using the default language of the server unless the `lg` query parameter is used to change the map tile language. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-openapi.md
- name: Map Tile API - Truck Restrictions Map
  x-api-slug: trucktilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a street map tile showing restrictions for heavy vehicles*

    To obtain a map tile displaying route restrictions for trucks, use the `trucktile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Truck Restrictions Map
  x-api-slug: trucktilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a street map tile showing restrictions for heavy vehicles*

    To obtain a map tile displaying route restrictions for trucks, use the `trucktile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Toll Zone Map
  x-api-slug: maptilenewestnormal-day9255170256png8-get
  description: |-
    *Request a street map tile highlighting congestion and environmental toll zones*

    To highlight such toll zones, add the `congestion` parameter to the request URL.



    * **congestion**  `null`
     \- Flag to indicate if congestion zones are to be shown on the map.

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-openapi.md
- name: Map Tile API - Toll Zone Map
  x-api-slug: maptilenewestnormal-day9255170256png8-get
  description: |-
    *Request a street map tile highlighting congestion and environmental toll zones*

    To highlight such toll zones, add the `congestion` parameter to the request URL.



    * **congestion**  `null`
     \- Flag to indicate if congestion zones are to be shown on the map.

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-openapi.md
- name: Map Tile API - Satellite Map
  x-api-slug: satellite-day51512256png8-get
  description: |-
    *Request a satellite map tile*

    Satellite map tiles do not display labels and are available by passing `satellite.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-openapi.md
- name: Map Tile API - Satellite Map
  x-api-slug: satellite-day51512256png8-get
  description: |-
    *Request a satellite map tile*

    Satellite map tiles do not display labels and are available by passing `satellite.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-openapi.md
- name: Map Tile API - Fleet Vehicle Map
  x-api-slug: maptilenewestnormal-day1340932723256png8-get
  description: |-
    *Request a street map tile using the fleet vehicle color scheme*

    Fleet color scheme map tiles are available by passing `style=fleet` as a parameter of the request URL.



    * **style**  `enum`
     \- If present, selects the style to use to render the tile.

     Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`, `mini`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-openapi.md
- name: Map Tile API - Fleet Vehicle Map
  x-api-slug: maptilenewestnormal-day1340932723256png8-get
  description: |-
    *Request a street map tile using the fleet vehicle color scheme*

    Fleet color scheme map tiles are available by passing `style=fleet` as a parameter of the request URL.



    * **style**  `enum`
     \- If present, selects the style to use to render the tile.

     Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`, `mini`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-openapi.md
- name: Map Tile API - Base64 Encoded Map Tile
  x-api-slug: maptilenewestnormal-day11525761256png8-get
  description: "*Request a base64 encoded map tile*\n\nBase64 encoded tiles are requested
    by adding the parameter `output=base64` to the request URL.\n  \n  Click on the
    response to decode the tile returned.\n\n\n\n* **output**  `text`\n \\- Indicates
    whether to return the tile as base64 encoded text.\n\n* **app_id**  `text`\n \\-
    A 20 byte Base64 URL-safe encoded string used for the authentication of the client
    application.    You must include an `app_id` with every request.\n\n* **app_code**
    \ `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication
    of the client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-openapi.md
- name: Map Tile API - Base64 Encoded Map Tile
  x-api-slug: maptilenewestnormal-day11525761256png8-get
  description: "*Request a base64 encoded map tile*\n\nBase64 encoded tiles are requested
    by adding the parameter `output=base64` to the request URL.\n  \n  Click on the
    response to decode the tile returned.\n\n\n\n* **output**  `text`\n \\- Indicates
    whether to return the tile as base64 encoded text.\n\n* **app_id**  `text`\n \\-
    A 20 byte Base64 URL-safe encoded string used for the authentication of the client
    application.    You must include an `app_id` with every request.\n\n* **app_code**
    \ `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication
    of the client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-openapi.md
- name: Map Tile API - Color-reduced Street Map
  x-api-slug: maptilenewestnormal-day-grey11525761256png8-get
  description: |-
    *Request a greyed out street map tile*

    Maps using a reduced color palette can be requested by passing `normal.day.grey` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-openapi.md
- name: Map Tile API - Color-reduced Street Map
  x-api-slug: maptilenewestnormal-day-grey11525761256png8-get
  description: |-
    *Request a greyed out street map tile*

    Maps using a reduced color palette can be requested by passing `normal.day.grey` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-openapi.md
- name: Map Tile API - Map Tile Type Information
  x-api-slug: info-get
  description: |-
    *Request information about the types of map tiles available on a server*

    To make a request for metadata information, use the `info` parameter in the path of the request URL.



    * **output**  `enum`
     \- Indicates whether to return the information in XML format, JSON format or as an XML schema (XSD) of the API metadata

     Valid values are : `json`, `xml`, `xsd`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-openapi.md
- name: Map Tile API - Map Tile Type Information
  x-api-slug: info-get
  description: |-
    *Request information about the types of map tiles available on a server*

    To make a request for metadata information, use the `info` parameter in the path of the request URL.



    * **output**  `enum`
     \- Indicates whether to return the information in XML format, JSON format or as an XML schema (XSD) of the API metadata

     Valid values are : `json`, `xml`, `xsd`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-openapi.md
- name: Map Tile API - Transparent Truck Restrictions Map
  x-api-slug: truckonlytilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a transparent tile showing restrictions for heavy vehicles only*

    To obtain a transparent map tile displaying route restrictions for trucks, use the `truckonlytile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Transparent Truck Restrictions Map
  x-api-slug: truckonlytilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a transparent tile showing restrictions for heavy vehicles only*

    To obtain a transparent map tile displaying route restrictions for trucks, use the `truckonlytile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Transparent Truck Restrictions Map
  x-api-slug: truckonlytilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a transparent tile showing restrictions for heavy vehicles only*

    To obtain a transparent map tile displaying route restrictions for trucks, use the `truckonlytile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Transparent Truck Restrictions Map
  x-api-slug: truckonlytilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a transparent tile showing restrictions for heavy vehicles only*

    To obtain a transparent map tile displaying route restrictions for trucks, use the `truckonlytile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Transparent Truck Restrictions Map
  x-api-slug: truckonlytilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a transparent tile showing restrictions for heavy vehicles only*

    To obtain a transparent map tile displaying route restrictions for trucks, use the `truckonlytile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Transparent Truck Restrictions Map
  x-api-slug: truckonlytilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a transparent tile showing restrictions for heavy vehicles only*

    To obtain a transparent map tile displaying route restrictions for trucks, use the `truckonlytile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/truckonlytilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Map Tile Type Information
  x-api-slug: info-get
  description: |-
    *Request information about the types of map tiles available on a server*

    To make a request for metadata information, use the `info` parameter in the path of the request URL.



    * **output**  `enum`
     \- Indicates whether to return the information in XML format, JSON format or as an XML schema (XSD) of the API metadata

     Valid values are : `json`, `xml`, `xsd`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-openapi.md
- name: Map Tile API - Map Tile Type Information
  x-api-slug: info-get
  description: |-
    *Request information about the types of map tiles available on a server*

    To make a request for metadata information, use the `info` parameter in the path of the request URL.



    * **output**  `enum`
     \- Indicates whether to return the information in XML format, JSON format or as an XML schema (XSD) of the API metadata

     Valid values are : `json`, `xml`, `xsd`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-openapi.md
- name: Map Tile API - Map Tile Type Information
  x-api-slug: info-get
  description: |-
    *Request information about the types of map tiles available on a server*

    To make a request for metadata information, use the `info` parameter in the path of the request URL.



    * **output**  `enum`
     \- Indicates whether to return the information in XML format, JSON format or as an XML schema (XSD) of the API metadata

     Valid values are : `json`, `xml`, `xsd`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-openapi.md
- name: Map Tile API - Map Tile Type Information
  x-api-slug: info-get
  description: |-
    *Request information about the types of map tiles available on a server*

    To make a request for metadata information, use the `info` parameter in the path of the request URL.



    * **output**  `enum`
     \- Indicates whether to return the information in XML format, JSON format or as an XML schema (XSD) of the API metadata

     Valid values are : `json`, `xml`, `xsd`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/info-get-openapi.md
- name: Map Tile API - Color-reduced Street Map
  x-api-slug: maptilenewestnormal-day-grey11525761256png8-get
  description: |-
    *Request a greyed out street map tile*

    Maps using a reduced color palette can be requested by passing `normal.day.grey` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-openapi.md
- name: Map Tile API - Color-reduced Street Map
  x-api-slug: maptilenewestnormal-day-grey11525761256png8-get
  description: |-
    *Request a greyed out street map tile*

    Maps using a reduced color palette can be requested by passing `normal.day.grey` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-openapi.md
- name: Map Tile API - Color-reduced Street Map
  x-api-slug: maptilenewestnormal-day-grey11525761256png8-get
  description: |-
    *Request a greyed out street map tile*

    Maps using a reduced color palette can be requested by passing `normal.day.grey` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-openapi.md
- name: Map Tile API - Color-reduced Street Map
  x-api-slug: maptilenewestnormal-day-grey11525761256png8-get
  description: |-
    *Request a greyed out street map tile*

    Maps using a reduced color palette can be requested by passing `normal.day.grey` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-grey11525761256png8-get-openapi.md
- name: Map Tile API - Base64 Encoded Map Tile
  x-api-slug: maptilenewestnormal-day11525761256png8-get
  description: "*Request a base64 encoded map tile*\n\nBase64 encoded tiles are requested
    by adding the parameter `output=base64` to the request URL.\n  \n  Click on the
    response to decode the tile returned.\n\n\n\n* **output**  `text`\n \\- Indicates
    whether to return the tile as base64 encoded text.\n\n* **app_id**  `text`\n \\-
    A 20 byte Base64 URL-safe encoded string used for the authentication of the client
    application.    You must include an `app_id` with every request.\n\n* **app_code**
    \ `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication
    of the client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-openapi.md
- name: Map Tile API - Base64 Encoded Map Tile
  x-api-slug: maptilenewestnormal-day11525761256png8-get
  description: "*Request a base64 encoded map tile*\n\nBase64 encoded tiles are requested
    by adding the parameter `output=base64` to the request URL.\n  \n  Click on the
    response to decode the tile returned.\n\n\n\n* **output**  `text`\n \\- Indicates
    whether to return the tile as base64 encoded text.\n\n* **app_id**  `text`\n \\-
    A 20 byte Base64 URL-safe encoded string used for the authentication of the client
    application.    You must include an `app_id` with every request.\n\n* **app_code**
    \ `text`\n \\- A 20 byte Base64 URL-safe encoded string used for the authentication
    of the client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day11525761256png8-get-openapi.md
- name: Map Tile API - Fleet Vehicle Map
  x-api-slug: maptilenewestnormal-day1340932723256png8-get
  description: |-
    *Request a street map tile using the fleet vehicle color scheme*

    Fleet color scheme map tiles are available by passing `style=fleet` as a parameter of the request URL.



    * **style**  `enum`
     \- If present, selects the style to use to render the tile.

     Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`, `mini`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-openapi.md
- name: Map Tile API - Fleet Vehicle Map
  x-api-slug: maptilenewestnormal-day1340932723256png8-get
  description: |-
    *Request a street map tile using the fleet vehicle color scheme*

    Fleet color scheme map tiles are available by passing `style=fleet` as a parameter of the request URL.



    * **style**  `enum`
     \- If present, selects the style to use to render the tile.

     Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`, `mini`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-openapi.md
- name: Map Tile API - Fleet Vehicle Map
  x-api-slug: maptilenewestnormal-day1340932723256png8-get
  description: |-
    *Request a street map tile using the fleet vehicle color scheme*

    Fleet color scheme map tiles are available by passing `style=fleet` as a parameter of the request URL.



    * **style**  `enum`
     \- If present, selects the style to use to render the tile.

     Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`, `mini`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day1340932723256png8-get-openapi.md
- name: Map Tile API - Satellite Map
  x-api-slug: satellite-day51512256png8-get
  description: |-
    *Request a satellite map tile*

    Satellite map tiles do not display labels and are available by passing `satellite.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/satellite-day51512256png8-get-openapi.md
- name: Map Tile API - Toll Zone Map
  x-api-slug: maptilenewestnormal-day9255170256png8-get
  description: |-
    *Request a street map tile highlighting congestion and environmental toll zones*

    To highlight such toll zones, add the `congestion` parameter to the request URL.



    * **congestion**  `null`
     \- Flag to indicate if congestion zones are to be shown on the map.

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day9255170256png8-get-openapi.md
- name: Map Tile API - Truck Restrictions Map
  x-api-slug: trucktilenewestnormal-day1221991342256png8-get
  description: |-
    *Request a street map tile showing restrictions for heavy vehicles*

    To obtain a map tile displaying route restrictions for trucks, use the `trucktile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/trucktilenewestnormal-day1221991342256png8-get-openapi.md
- name: Map Tile API - Hybrid Map
  x-api-slug: hybrid-day485256png8-get
  description: |-
    *Request a hybrid map tile - satellite imagery with labels*

    Hybrid map tile are available by passing `hybrid.day` in the path of the request URL. The map tiles will display using the default language of the server unless the `lg` query parameter is used to change the map tile language. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-openapi.md
- name: Map Tile API - Hybrid Map
  x-api-slug: hybrid-day485256png8-get
  description: |-
    *Request a hybrid map tile - satellite imagery with labels*

    Hybrid map tile are available by passing `hybrid.day` in the path of the request URL. The map tiles will display using the default language of the server unless the `lg` query parameter is used to change the map tile language. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-openapi.md
- name: Map Tile API - Hybrid Map
  x-api-slug: hybrid-day485256png8-get
  description: |-
    *Request a hybrid map tile - satellite imagery with labels*

    Hybrid map tile are available by passing `hybrid.day` in the path of the request URL. The map tiles will display using the default language of the server unless the `lg` query parameter is used to change the map tile language. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-openapi.md
- name: Map Tile API - Hybrid Map
  x-api-slug: hybrid-day485256png8-get
  description: |-
    *Request a hybrid map tile - satellite imagery with labels*

    Hybrid map tile are available by passing `hybrid.day` in the path of the request URL. The map tiles will display using the default language of the server unless the `lg` query parameter is used to change the map tile language. Consult the  Map Tile API Reference for a full list of available languages.



    * **lg**  `enum`
     \- Alters the language of the labels displayed on the map. Three letter MARC code, for example `rus` for Russian language.

     Valid values are : `ara` - Arabic, `chi` - Chinese, `cht` - Chinese (Trad), `dut` - Dutch, `eng` - English, `fre` - French, `ger` - German, `gle` - Gaelic, `gre` - Greek, `heb` - Hebrew, `hin` - Hindi, `ind` - Indonesian, `ita` - Italian, `per` - Persian, `pol` - Polish, `por` - Portuguese, `rus` - Russian, `sin` - Sinhalese, `spa` - Spanish, `tha` - Thai, `tur` - Turkish, `ukr` - Ukranian, `urd` - Urdu, `vie` - Vietnamese, `wel` - Welsh

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/hybrid-day485256png8-get-openapi.md
- name: Map Tile API - Color-reduced Transit Map
  x-api-slug: maptilenewestnormal-day-transit1220741409256png8-get
  description: |-
    *Request a color-reduced map tile with public transport*

    Color-reduced street map tiles with full-color transit overlays are requested by passing `normal.day.transit` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day-transit1220741409256png8-get-openapi.md
- name: Map Tile API - Multiple Base64 Encoded Map Tiles
  x-api-slug: maptilenewestnormal-day63024256png8-get
  description: "*Request multiple base64 encoded map tiles*\n\nA square consisting
    of multiple base64 encoded tiles is requested by adding the parameters `output=base64`
    and `range=NxN` to the request URL. The `column` and `row` in the path of the
    URL, defining the top left-hand corner of the tile group must be divisible by
    the value of the `range` parameter.\n  \n  Click on the response to decode the
    tiles returned.\n\n\n\n* **output**  `text`\n \\- Indicates whether to return
    the tile as base64 encoded text.\n\n* **range**  `enum`\n \\- Indicates the size
    of the array of tiles returned. Valid values are `2x2`, `3x3` or `4x4`\n\n Valid
    values are : `2x2`, `3x3`, `4x4`\n\n* **app_id**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-openapi.md
- name: Map Tile API - Multiple Base64 Encoded Map Tiles
  x-api-slug: maptilenewestnormal-day63024256png8-get
  description: "*Request multiple base64 encoded map tiles*\n\nA square consisting
    of multiple base64 encoded tiles is requested by adding the parameters `output=base64`
    and `range=NxN` to the request URL. The `column` and `row` in the path of the
    URL, defining the top left-hand corner of the tile group must be divisible by
    the value of the `range` parameter.\n  \n  Click on the response to decode the
    tiles returned.\n\n\n\n* **output**  `text`\n \\- Indicates whether to return
    the tile as base64 encoded text.\n\n* **range**  `enum`\n \\- Indicates the size
    of the array of tiles returned. Valid values are `2x2`, `3x3` or `4x4`\n\n Valid
    values are : `2x2`, `3x3`, `4x4`\n\n* **app_id**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-openapi.md
- name: Map Tile API - Multiple Base64 Encoded Map Tiles
  x-api-slug: maptilenewestnormal-day63024256png8-get
  description: "*Request multiple base64 encoded map tiles*\n\nA square consisting
    of multiple base64 encoded tiles is requested by adding the parameters `output=base64`
    and `range=NxN` to the request URL. The `column` and `row` in the path of the
    URL, defining the top left-hand corner of the tile group must be divisible by
    the value of the `range` parameter.\n  \n  Click on the response to decode the
    tiles returned.\n\n\n\n* **output**  `text`\n \\- Indicates whether to return
    the tile as base64 encoded text.\n\n* **range**  `enum`\n \\- Indicates the size
    of the array of tiles returned. Valid values are `2x2`, `3x3` or `4x4`\n\n Valid
    values are : `2x2`, `3x3`, `4x4`\n\n* **app_id**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-openapi.md
- name: Map Tile API - Multiple Base64 Encoded Map Tiles
  x-api-slug: maptilenewestnormal-day63024256png8-get
  description: "*Request multiple base64 encoded map tiles*\n\nA square consisting
    of multiple base64 encoded tiles is requested by adding the parameters `output=base64`
    and `range=NxN` to the request URL. The `column` and `row` in the path of the
    URL, defining the top left-hand corner of the tile group must be divisible by
    the value of the `range` parameter.\n  \n  Click on the response to decode the
    tiles returned.\n\n\n\n* **output**  `text`\n \\- Indicates whether to return
    the tile as base64 encoded text.\n\n* **range**  `enum`\n \\- Indicates the size
    of the array of tiles returned. Valid values are `2x2`, `3x3` or `4x4`\n\n Valid
    values are : `2x2`, `3x3`, `4x4`\n\n* **app_id**  `text`\n \\- A 20 byte Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/maptilenewestnormal-day63024256png8-get-openapi.md
- name: Map Tile API - Terrain Map
  x-api-slug: terrain-day76645256png8-get
  description: |-
    *Request a terrain map tile*

    Terrain map tile are available by passing `terrain.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-openapi.md
- name: Map Tile API - Terrain Map
  x-api-slug: terrain-day76645256png8-get
  description: |-
    *Request a terrain map tile*

    Terrain map tile are available by passing `terrain.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-openapi.md
- name: Map Tile API - Terrain Map
  x-api-slug: terrain-day76645256png8-get
  description: |-
    *Request a terrain map tile*

    Terrain map tile are available by passing `terrain.day` in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/terrain-day76645256png8-get-openapi.md
- name: Platform Data Extension API - Available Map Data Layers
  x-api-slug: doclayers-json-get
  description: |-
    *Request which data layers can be accessed within a specified map region and release*

    To make a request for data layer availability information, use the `layers.json` endpoint, supplying the `release` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-openapi.md
- name: Platform Data Extension API - Map Data Availability and Freshness
  x-api-slug: docmaps-json-get
  description: |-
    *Request the release date and area covered by each available map region*

    To make a request for release date information, use the `maps.json` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-openapi.md
- name: Platform Data Extension API - Available Attributes within a Map Data Layer
  x-api-slug: doclayer-json-get
  description: |-
    *Request which attributes are available within a specified map data layer*

    To make a request for map data layer information, use the `layer``.json` endpoint, supplying the `release`, `layer` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-openapi.md
- name: Platform Data Extension API - Available Map Data Layers
  x-api-slug: doclayers-json-get
  description: |-
    *Request which data layers can be accessed within a specified map region and release*

    To make a request for data layer availability information, use the `layers.json` endpoint, supplying the `release` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-openapi.md
- name: Platform Data Extension API - Available Map Data Layers
  x-api-slug: doclayers-json-get
  description: |-
    *Request which data layers can be accessed within a specified map region and release*

    To make a request for data layer availability information, use the `layers.json` endpoint, supplying the `release` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-openapi.md
- name: Platform Data Extension API - Map Data Availability and Freshness
  x-api-slug: docmaps-json-get
  description: |-
    *Request the release date and area covered by each available map region*

    To make a request for release date information, use the `maps.json` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-openapi.md
- name: Platform Data Extension API - Map Data Availability and Freshness
  x-api-slug: docmaps-json-get
  description: |-
    *Request the release date and area covered by each available map region*

    To make a request for release date information, use the `maps.json` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-openapi.md
- name: Platform Data Extension API - Available Attributes within a Map Data Layer
  x-api-slug: doclayer-json-get
  description: |-
    *Request which attributes are available within a specified map data layer*

    To make a request for map data layer information, use the `layer``.json` endpoint, supplying the `release`, `layer` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-openapi.md
- name: Platform Data Extension API - Available Attributes within a Map Data Layer
  x-api-slug: doclayer-json-get
  description: |-
    *Request which attributes are available within a specified map data layer*

    To make a request for map data layer information, use the `layer``.json` endpoint, supplying the `release`, `layer` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-openapi.md
- name: Platform Data Extension API - Available Attributes within a Map Data Layer
  x-api-slug: doclayer-json-get
  description: |-
    *Request which attributes are available within a specified map data layer*

    To make a request for map data layer information, use the `layer``.json` endpoint, supplying the `release`, `layer` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-openapi.md
- name: Platform Data Extension API - Available Attributes within a Map Data Layer
  x-api-slug: doclayer-json-get
  description: |-
    *Request which attributes are available within a specified map data layer*

    To make a request for map data layer information, use the `layer``.json` endpoint, supplying the `release`, `layer` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-openapi.md
- name: Platform Data Extension API - Available Attributes within a Map Data Layer
  x-api-slug: doclayer-json-get
  description: |-
    *Request which attributes are available within a specified map data layer*

    To make a request for map data layer information, use the `layer``.json` endpoint, supplying the `release`, `layer` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayer-json-get-openapi.md
- name: Platform Data Extension API - Map Data Availability and Freshness
  x-api-slug: docmaps-json-get
  description: |-
    *Request the release date and area covered by each available map region*

    To make a request for release date information, use the `maps.json` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-openapi.md
- name: Platform Data Extension API - Map Data Availability and Freshness
  x-api-slug: docmaps-json-get
  description: |-
    *Request the release date and area covered by each available map region*

    To make a request for release date information, use the `maps.json` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-openapi.md
- name: Platform Data Extension API - Map Data Availability and Freshness
  x-api-slug: docmaps-json-get
  description: |-
    *Request the release date and area covered by each available map region*

    To make a request for release date information, use the `maps.json` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/docmaps-json-get-openapi.md
- name: Platform Data Extension API - Available Map Data Layers
  x-api-slug: doclayers-json-get
  description: |-
    *Request which data layers can be accessed within a specified map region and release*

    To make a request for data layer availability information, use the `layers.json` endpoint, supplying the `release` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-openapi.md
- name: Platform Data Extension API - Available Map Data Layers
  x-api-slug: doclayers-json-get
  description: |-
    *Request which data layers can be accessed within a specified map region and release*

    To make a request for data layer availability information, use the `layers.json` endpoint, supplying the `release` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-openapi.md
- name: Platform Data Extension API - Available Map Data Layers
  x-api-slug: doclayers-json-get
  description: |-
    *Request which data layers can be accessed within a specified map region and release*

    To make a request for data layer availability information, use the `layers.json` endpoint, supplying the `release` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/doclayers-json-get-openapi.md
- name: Traffic API - Transparent Traffic Map
  x-api-slug: flowtilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a transparent tile with traffic flow information*

    To obtain a transparent map tile displaying traffic flow, use the `flowtile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map via TDA (to be deprecated)
  x-api-slug: png32-get
  description: |-
    *Request a transparent tile with traffic flow information*

    Supports custom coloring, functional class filters, DLR rendering, sub-segment traffic rendering.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-openapi.md
- name: Traffic API - Traffic Map
  x-api-slug: traffictilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a map tile with traffic flow information*

    To obtain a traffic map tile, use the  `traffictile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map
  x-api-slug: flowtilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a transparent tile with traffic flow information*

    To obtain a transparent map tile displaying traffic flow, use the `flowtile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map
  x-api-slug: flowtilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a transparent tile with traffic flow information*

    To obtain a transparent map tile displaying traffic flow, use the `flowtile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map via TDA (to be deprecated)
  x-api-slug: png32-get
  description: |-
    *Request a transparent tile with traffic flow information*

    Supports custom coloring, functional class filters, DLR rendering, sub-segment traffic rendering.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-openapi.md
- name: Traffic API - Transparent Traffic Map via TDA (to be deprecated)
  x-api-slug: png32-get
  description: |-
    *Request a transparent tile with traffic flow information*

    Supports custom coloring, functional class filters, DLR rendering, sub-segment traffic rendering.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-openapi.md
- name: Traffic API - Traffic Map
  x-api-slug: traffictilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a map tile with traffic flow information*

    To obtain a traffic map tile, use the  `traffictile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Traffic Map
  x-api-slug: traffictilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a map tile with traffic flow information*

    To obtain a traffic map tile, use the  `traffictile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Traffic Map
  x-api-slug: traffictilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a map tile with traffic flow information*

    To obtain a traffic map tile, use the  `traffictile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Traffic Map
  x-api-slug: traffictilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a map tile with traffic flow information*

    To obtain a traffic map tile, use the  `traffictile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Traffic Map
  x-api-slug: traffictilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a map tile with traffic flow information*

    To obtain a traffic map tile, use the  `traffictile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Traffic Map
  x-api-slug: traffictilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a map tile with traffic flow information*

    To obtain a traffic map tile, use the  `traffictile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/traffictilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map via TDA (to be deprecated)
  x-api-slug: png32-get
  description: |-
    *Request a transparent tile with traffic flow information*

    Supports custom coloring, functional class filters, DLR rendering, sub-segment traffic rendering.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-openapi.md
- name: Traffic API - Transparent Traffic Map via TDA (to be deprecated)
  x-api-slug: png32-get
  description: |-
    *Request a transparent tile with traffic flow information*

    Supports custom coloring, functional class filters, DLR rendering, sub-segment traffic rendering.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/png32-get-openapi.md
- name: Traffic API - Transparent Traffic Map
  x-api-slug: flowtilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a transparent tile with traffic flow information*

    To obtain a transparent map tile displaying traffic flow, use the `flowtile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map
  x-api-slug: flowtilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a transparent tile with traffic flow information*

    To obtain a transparent map tile displaying traffic flow, use the `flowtile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map
  x-api-slug: flowtilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a transparent tile with traffic flow information*

    To obtain a transparent map tile displaying traffic flow, use the `flowtile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-openapi.md
- name: Traffic API - Transparent Traffic Map
  x-api-slug: flowtilenewestnormal-day151635810898256png8-get
  description: |-
    *Request a transparent tile with traffic flow information*

    To obtain a transparent map tile displaying traffic flow, use the `flowtile` parameter in the path of the request URL.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/flowtilenewestnormal-day151635810898256png8-get-openapi.md
- name: Venue Maps - Venue Map Tile
  x-api-slug: 0tilespngl112022001101210030210-png-get
  description: |-
    *Request an individual venue map tile*

    In addition to the usual `app_id` and `app_code`, three additional parameters are required for authentication purposes. The `Signature`, `Policy` and `Key-Pair-Id` parameters have been obtained from a prior request to the `Signature` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-openapi.md
- name: Venue Maps - Base64 Encoded Map Tiles
  x-api-slug: 0tilesiab64l112022001101210030210-js-get
  description: |-
    *Request a base64 encoded map tile and associated room definitions with a single request*

    A base64 encoded map tile together with the room definitions, is requested by passing `tiles-ia-b64` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-openapi.md
- name: Venue Maps - Venue Map Tile
  x-api-slug: 0tilespngl112022001101210030210-png-get
  description: |-
    *Request an individual venue map tile*

    In addition to the usual `app_id` and `app_code`, three additional parameters are required for authentication purposes. The `Signature`, `Policy` and `Key-Pair-Id` parameters have been obtained from a prior request to the `Signature` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-openapi.md
- name: Venue Maps - Venue Map Tile
  x-api-slug: 0tilespngl112022001101210030210-png-get
  description: |-
    *Request an individual venue map tile*

    In addition to the usual `app_id` and `app_code`, three additional parameters are required for authentication purposes. The `Signature`, `Policy` and `Key-Pair-Id` parameters have been obtained from a prior request to the `Signature` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-openapi.md
- name: Venue Maps - Base64 Encoded Map Tiles
  x-api-slug: 0tilesiab64l112022001101210030210-js-get
  description: |-
    *Request a base64 encoded map tile and associated room definitions with a single request*

    A base64 encoded map tile together with the room definitions, is requested by passing `tiles-ia-b64` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-openapi.md
- name: Venue Maps - Base64 Encoded Map Tiles
  x-api-slug: 0tilesiab64l112022001101210030210-js-get
  description: |-
    *Request a base64 encoded map tile and associated room definitions with a single request*

    A base64 encoded map tile together with the room definitions, is requested by passing `tiles-ia-b64` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-openapi.md
- name: Venue Maps - Base64 Encoded Map Tiles
  x-api-slug: 0tilesiab64l112022001101210030210-js-get
  description: |-
    *Request a base64 encoded map tile and associated room definitions with a single request*

    A base64 encoded map tile together with the room definitions, is requested by passing `tiles-ia-b64` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilesiab64l112022001101210030210-js-get-openapi.md
- name: Venue Maps - Venue Map Tile
  x-api-slug: 0tilespngl112022001101210030210-png-get
  description: |-
    *Request an individual venue map tile*

    In addition to the usual `app_id` and `app_code`, three additional parameters are required for authentication purposes. The `Signature`, `Policy` and `Key-Pair-Id` parameters have been obtained from a prior request to the `Signature` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/here/0tilespngl112022001101210030210-png-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---