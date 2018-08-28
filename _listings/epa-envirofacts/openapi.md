swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 1
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking
    Water Act
  description: enforcement-and-compliance-history-online-echo-is-a-tool-developed-and-maintained-by-epas-office-of-enforcement-and-compliance-assurance-for-public-use--echo-provides-integrated-compliance-and-enforcement-information-for-about-800000-regulated-facilities-nationwide-brbrsdw-rest-services-provides-multiple-service-endpoints-each-with-specific-capabilities-to-search-and-retrieve-data-on-public-water-systems-regulated-under-the-safe-drinking-water-act-sdwa--the-returned-results-reflect-data-drawn-from-epas-federal-safe-drinking-water-information-system-sdwis-database-brbrthe-get-systems-get-qid-and-get-download-end-points-are-meant-to-be-used-together-brbrthe-recommended-use-scenario-for-get-systems-get-qid-and-get-downoad-isbrbrb1bnbsp-use-get-systems-to-validate-passed-query-parameters-obtain-summary-statistics-and-to-obtain-a-query-id-qid---qids-are-time-sensitive-and-will-be-valid-for-approximately-30-minutes-brb2bnbsp-use-get-qid-with-the-returned-qid-to-paginate-through-arrays-of-water-system-results-brb3bnbsp-use-get-download-with-the-returned-qid-to-generate-a-comma-separated-value-csv-file-of-water-system-information-that-meets-the-qid-query-criteria-brbruse-the-qcolumns-parameter-to-customize-your-search-results---use-the-metdata-service-endpoint-for-a-list-of-available-output-objects-their-column-ids-and-their-definitions-to-help-you-build-your-customized-output--brbradditional-echo-resourcesnbspnbsp-a-hrefhttpsecho-epa-govtoolswebservicesweb-servicesa-a-hrefhttpsecho-epa-govresourcesechodataaboutthedataabout-echos-dataa-a-hrefhttpsecho-epa-govtoolsdatadownloadsdata-downloadsabr
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /echo_rest_services.get_map:
    get:
      summary: Combined ECHO Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: echo-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Combined
      - ECHO
      - Map
      - Service
  /air_rest_services.get_map:
    get:
      summary: Clean Air Act Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: air-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Air
      - Act
      - Map
      - Service
  /cwa_rest_services.get_map:
    get:
      summary: Clean Water Act (CWA) Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: cwa-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Map
      - Service
  /dfr_rest_services.get_map:
    get:
      summary: Detailed Facility Report Map Service
      description: Returns an object with the facility's latitude and longitude coordinates.
      operationId: returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-
      x-api-path-slug: dfr-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - Map
      - Service
  /case_rest_services.get_map:
    get:
      summary: Enforcement Case Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_cases query. Currently, the maximum
        number of coordinates returned is 500. GET_MAP performs automatic clustering
        at the state, county, and zip code levels to maximize the number of coordinates
        returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: case-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Enforcement
      - Case
      - Map
      - Service
  /rcra_rest_services.get_map:
    get:
      summary: Resource Conservation and Recovery Act (RCRA) Map Service
      description: The purpose of the GET_MAP service is to display facility coordinates
        and facility clusters related to a get_facilities facility query. Currently,
        the maximum number of coordinates returned is 500. GET_MAP performs automatic
        clustering at the state, county, and zip code levels to maximize the number
        of coordinates returned.
      operationId: the-purpose-of-the-get-map-service-is-to-display-facility-coordinates-and-facility-clusters-related-
      x-api-path-slug: rcra-rest-services-get-map-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Resource
      - Conservation
      - Recovery
      - Act
      - (RCRA)
      - Map
      - Service