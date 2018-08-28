swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 1
info:
  title: IBM Watson Machine Learning API
  description: -authorizationstep-by-step-instruction-how-to-use-watson-machine-learning-servicecan-be-found-herehttpsdatascience-ibm-comdocscontentanalyzedatamloverview-htmlcontextanalytics-ibm-watson-machine-learning-credentialsto-start-working-with-api-one-needs-to-generate-an-access-token-using-the-username-and-passwordavailable-on-the-service-credentials-tab-of-the-ibm-watson-machine-learning-service-instance-or-also-available-in-the-vcap-environment-variable-example-of-the-service-credentialsjson----url-httpsibmwatsonml-mybluemix-net----username-c1ef4b802ee2458eab92e9ca97ec657d----password-030528d45a3e4d4c92585d553513be6f----instance-id-a751c209954edc32b441ad56ce7a9f40example-of-obtaining-access-token-from-token-endpoint-using-http-basic-auth-for-details-please-refer-to-token-section-belowcurl-basic-user-usernamepassword-httpsibmwatsonml-mybluemix-netv3identitytokenthe-obtained-access-token-needs-to-be-prepended-with-bearer-word-and-it-needs-to-be-passed-in-the-authorization-header-for-api-calls-example-of-api-request-with-bearer-access-tokencurl-httpsibmwatsonml-mybluemix-netv3wml-instances00fd89e68cf24712a068ade10277b649published-models-h-authorization-bearer-eyjhbgcioijsuzuxmiisinr5cci6ikpxvcj9-eyj0zw5hbnrjzci6imu4ymqzzgm3lwi5y2utndy1oc1iz----apache-spark-service-credentialsthe-ibm-watson-machine-learning-cooperates-with-the-apache-spark-as-a-service-to-create-batch-stream-deploymentsand-for-learning-configuration-functionality-for-api-methods-requiring-apache-spark-service-instance-a-custom-header-xsparkserviceinstancewith-service-credentials-must-be-specified-the-header-value-is-a-base64-encoded-string-with-the-json-data-containing-service-credentials-and-spark-version-example-of-the-json-data---credentials------tenant-ids068ade10277b6495605b1d10fv12b------tenant-id-full00fd89e68cf24712a068ade10277b649-41f37bf21b954c65a15605b1d10fb12b------cluster-master-urlhttpsspark-bluemix-net------instance-id00fd89e68cf24712a068ade10277b649------tenant-secretc74c37cf482a4da4836ef32ca26ccbb9------planibm-sparkservice-paygopersonal------version2-0
  version: 1.0.0
basePath: v3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /device/types/{typeId}/mappings:
    get:
      summary: Get the list of active property mappings for the device type
      description: |-
        Retrieve the list of active property mappings for the specified device
        type.  A property mapping defines how properties from inbound events are
        mapped to properties defined on an logical interface associated with
        the device type.
      operationId: retrieve-the-list-of-active-property-mappings-for-the-specified-devicetype--a-property-mapping-defin
      x-api-path-slug: devicetypestypeidmappings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
      - Mappings
  /device/types/{typeId}/mappings/{logicalInterfaceId}:
    get:
      summary: |-
        Get the active property mappings for a specific logical interface
        for a device type.
      description: |-
        Retrieves the active property mappings for a specific logical
        interface for the device type.
      operationId: retrieves-the-active-property-mappings-for-a-specific-logicalinterface-for-the-device-type
      x-api-path-slug: devicetypestypeidmappingslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Device
      - Types
      - Mappings
      - LogicalInterfaceId
  /draft/device/types/{typeId}/mappings:
    get:
      summary: Get the list of draft property mappings for the device type
      description: |-
        Retrieve the list of draft property mappings for the specified device
        type.  A property mapping defines how properties from inbound events are
        mapped to properties defined on an logical interface associated with
        the device type.
      operationId: retrieve-the-list-of-draft-property-mappings-for-the-specified-devicetype--a-property-mapping-define
      x-api-path-slug: draftdevicetypestypeidmappings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
      - Mappings
    post:
      summary: |-
        Create the draft property mappings for a logical interface for the
        device type
      description: |-
        Creates the draft property mappings for an logical interface for the
        device type.  The mapping object must specify:
        - The id for for the logical interface that the mappings are for
        - The mappings that define how to map from properties on the inbound
          events to the properties on the logical interface.  The mappings
          are keyed off of the event ids defined by the physical interface
          associated with the device type.
      operationId: creates-the-draft-property-mappings-for-an-logical-interface-for-thedevice-type--the-mapping-object-
      x-api-path-slug: draftdevicetypestypeidmappings-post
      parameters:
      - in: body
        name: Device Type Property Mappings
        description: The JSON representation of the draft device type property mappings
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
      - Mappings
  /draft/device/types/{typeId}/mappings/{logicalInterfaceId}:
    get:
      summary: |-
        Get the draft property mappings for a specific logical interface for
        a device type.
      description: |-
        Retrieves the draft property mappings for a specific logical
        interface for the device type.
      operationId: retrieves-the-draft-property-mappings-for-a-specific-logicalinterface-for-the-device-type
      x-api-path-slug: draftdevicetypestypeidmappingslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
      - Mappings
      - LogicalInterfaceId
    put:
      summary: |-
        Update the draft property mappings for a specific logical interface
        for the device type.
      description: |-
        Updates the draft property mappings for a specific logical interface
        for the device type.
      operationId: updates-the-draft-property-mappings-for-a-specific-logical-interfacefor-the-device-type
      x-api-path-slug: draftdevicetypestypeidmappingslogicalinterfaceid-put
      parameters:
      - in: body
        name: Device Type Property Mappings
        description: The JSON representation of the draft device type property mappings
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
      - Mappings
      - LogicalInterfaceId
    delete:
      summary: |-
        Delete the draft property mappings for a specific logical interface
        for the device type.
      description: |-
        Deletes the draft property mappings for a specific logical interface
        for the device type.
      operationId: deletes-the-draft-property-mappings-for-a-specific-logical-interfacefor-the-device-type
      x-api-path-slug: draftdevicetypestypeidmappingslogicalinterfaceid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Device
      - Types
      - Mappings
      - LogicalInterfaceId
  /thing/types/{thingTypeId}/mappings:
    get:
      summary: Get the list of active property mappings for the thing type
      description: |-
        Retrieve the list of active property mappings for the specified thing
        type.  A property mapping defines how properties from state update events
        on aggregated devices or things are mapped to properties defined on a
        logical interface associated with the thing type.
      operationId: retrieve-the-list-of-active-property-mappings-for-the-specified-thingtype--a-property-mapping-define
      x-api-path-slug: thingtypesthingtypeidmappings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Mappings
  /thing/types/{thingTypeId}/mappings/{logicalInterfaceId}:
    get:
      summary: |-
        Get the active property mappings for a specific logical interface for
        a thing type.
      description: |-
        Retrieves the active property mappings for a specific logical interface
        for the thing type.
      operationId: retrieves-the-active-property-mappings-for-a-specific-logical-interfacefor-the-thing-type
      x-api-path-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
  /draft/thing/types/{thingTypeId}/mappings:
    get:
      summary: Get the list of draft property mappings for the thing type
      description: |-
        Retrieve the list of draft property mappings for the specified draft
        thing type.  A property mapping defines how properties from state update
        events on aggregated devices or things are mapped to properties defined
        on a logical interface associated with the thing type.
      operationId: retrieve-the-list-of-draft-property-mappings-for-the-specified-draftthing-type--a-property-mapping-d
      x-api-path-slug: draftthingtypesthingtypeidmappings-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
    post:
      summary: |-
        Create the draft property mappings for a logical interface for the thing
        type
      description: |-
        Creates the draft property mappings for a logical interface for the
        thing type.  The mapping object must specify:
        - The id for for the logical interface that the mappings are for
        - The mappings that define how to map from properties on the state
          update events to the properties on the logical interface.  The
          mappings are keyed off of the name of the internal properties of the
          thing type.
      operationId: creates-the-draft-property-mappings-for-a-logical-interface-for-thething-type--the-mapping-object-mu
      x-api-path-slug: draftthingtypesthingtypeidmappings-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing Type Property Mappings
        description: The JSON representation of the thing type property mappings
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
  /draft/thing/types/{thingTypeId}/mappings/{logicalInterfaceId}:
    get:
      summary: |-
        Get the draft property mappings for a specific logical interface for
        a thing type.
      description: |-
        Retrieves the draft property mappings for a specific logical interface
        for the thing type.
      operationId: retrieves-the-draft-property-mappings-for-a-specific-logical-interfacefor-the-thing-type
      x-api-path-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
    put:
      summary: |-
        Update the property mappings for a specific logical interface for
        the thing type.
      description: |-
        Updates the property mappings for a specific logical interface
        for the draft thing type.
      operationId: updates-the-property-mappings-for-a-specific-logical-interfacefor-the-draft-thing-type
      x-api-path-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Thing Type Property Mappings
        description: The JSON representation of the thing type property mappings
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
    delete:
      summary: |-
        Delete the property mappings for a specific logical interface for
        the draft thing type.
      description: |-
        Deletes the property mappings for a specific logical interface
        for the draft thing type.
      operationId: deletes-the-property-mappings-for-a-specific-logical-interfacefor-the-draft-thing-type
      x-api-path-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Thing
      - Types
      - ThingTypeId
      - Mappings
      - LogicalInterfaceId
host: ibm-watson-ml.mybluemix.net