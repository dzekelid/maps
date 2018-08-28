---
name: IBM Watson
x-slug: ibm-watson
description: Meet IBM Watson, a cognitive system that enables a new partnership between
  people and computers that enhances and scales human expertise. Watson has been learning
  the language of professions and is trained by experts to work across many different
  industries.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Maps
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/apis.md
specificationVersion: "0.14"
apis:
- name: IBM Watson IoT Platform HTTP REST API - Get the list of active property mappings
    for the device type
  x-api-slug: devicetypestypeidmappings-get
  description: |-
    Retrieve the list of active property mappings for the specified device
    type.  A property mapping defines how properties from inbound events are
    mapped to properties defined on an logical interface associated with
    the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface
    for a device type.
  x-api-slug: devicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of draft property mappings
    for the device type
  x-api-slug: draftdevicetypestypeidmappings-get
  description: |-
    Retrieve the list of draft property mappings for the specified device
    type.  A property mapping defines how properties from inbound events are
    mapped to properties defined on an logical interface associated with
    the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Create the draft property mappings for a logical interface for the
    device type
  x-api-slug: draftdevicetypestypeidmappings-post
  description: |-
    Creates the draft property mappings for an logical interface for the
    device type.  The mapping object must specify:
    - The id for for the logical interface that the mappings are for
    - The mappings that define how to map from properties on the inbound
      events to the properties on the logical interface.  The mappings
      are keyed off of the event ids defined by the physical interface
      associated with the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappings-post-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of active property mappings
    for the thing type
  x-api-slug: thingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of active property mappings for the specified thing
    type.  A property mapping defines how properties from state update events
    on aggregated devices or things are mapped to properties defined on a
    logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/thingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface for
    a thing type.
  x-api-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/thingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of draft property mappings
    for the thing type
  x-api-slug: draftthingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of draft property mappings for the specified draft
    thing type.  A property mapping defines how properties from state update
    events on aggregated devices or things are mapped to properties defined
    on a logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Create the draft property mappings for a logical interface for the thing
    type
  x-api-slug: draftthingtypesthingtypeidmappings-post
  description: |-
    Creates the draft property mappings for a logical interface for the
    thing type.  The mapping object must specify:
    - The id for for the logical interface that the mappings are for
    - The mappings that define how to map from properties on the state
      update events to the properties on the logical interface.  The
      mappings are keyed off of the name of the internal properties of the
      thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-post-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the property mappings for a specific logical interface for
    the thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the property mappings for a specific logical interface for
    the draft thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of active property mappings
    for the device type
  x-api-slug: devicetypestypeidmappings-get
  description: |-
    Retrieve the list of active property mappings for the specified device
    type.  A property mapping defines how properties from inbound events are
    mapped to properties defined on an logical interface associated with
    the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface
    for a device type.
  x-api-slug: devicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of draft property mappings
    for the device type
  x-api-slug: draftdevicetypestypeidmappings-get
  description: |-
    Retrieve the list of draft property mappings for the specified device
    type.  A property mapping defines how properties from inbound events are
    mapped to properties defined on an logical interface associated with
    the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Create the draft property mappings for a logical interface for the
    device type
  x-api-slug: draftdevicetypestypeidmappings-post
  description: |-
    Creates the draft property mappings for an logical interface for the
    device type.  The mapping object must specify:
    - The id for for the logical interface that the mappings are for
    - The mappings that define how to map from properties on the inbound
      events to the properties on the logical interface.  The mappings
      are keyed off of the event ids defined by the physical interface
      associated with the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappings-post-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of active property mappings
    for the thing type
  x-api-slug: thingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of active property mappings for the specified thing
    type.  A property mapping defines how properties from state update events
    on aggregated devices or things are mapped to properties defined on a
    logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/thingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface for
    a thing type.
  x-api-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/thingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the list of draft property mappings
    for the thing type
  x-api-slug: draftthingtypesthingtypeidmappings-get
  description: |-
    Retrieve the list of draft property mappings for the specified draft
    thing type.  A property mapping defines how properties from state update
    events on aggregated devices or things are mapped to properties defined
    on a logical interface associated with the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Create the draft property mappings for a logical interface for the thing
    type
  x-api-slug: draftthingtypesthingtypeidmappings-post
  description: |-
    Creates the draft property mappings for a logical interface for the
    thing type.  The mapping object must specify:
    - The id for for the logical interface that the mappings are for
    - The mappings that define how to map from properties on the state
      update events to the properties on the logical interface.  The
      mappings are keyed off of the name of the internal properties of the
      thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappings-post-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the property mappings for a specific logical interface for
    the thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the property mappings for a specific logical interface for
    the draft thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/maps/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://ibm.financial.crimes.insight.for.insurance.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ibm.watson.stack.network
- type: x-application-gallery
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/gallery.html
- type: x-blog
  url: https://developer.ibm.com/watson/blog/
- type: x-blog-rss
  url: https://developer.ibm.com/watson/feed/
- type: x-developer
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/
- type: x-developer
  url: https://developer.ibm.com/watson/
- type: x-documentation
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/apis/
- type: x-forum
  url: https://developer.ibm.com/answers/smartspace/watson/
- type: x-getting-started
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/getstarted.html
- type: x-github
  url: https://github.com/IBM-Watson
- type: x-partners
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/ecosystem.html
- type: x-privacy
  url: http://www.ibm.com/privacy/us/en/?lnk=flg-priv-usen
- type: x-terms-of-service
  url: http://www.ibm.com/legal/us/en/?lnk=flg-tous-usen
- type: x-twitter
  url: https://twitter.com/IBMWatson
- type: x-videos
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/
- type: x-website
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
- type: x-white-papers
  url: https://developer.ibm.com/watson/docs/whitepapers/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---