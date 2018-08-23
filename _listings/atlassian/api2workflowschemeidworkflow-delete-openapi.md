---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Delete workflow mapping
  description: Delete the passed workflow from the workflow scheme.
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/workflowscheme/{id}/draft/workflow:
    put:
      summary: Update draft workflow mapping
      description: |-
        Update the draft scheme to include the passed mapping.

        The body is a representation of the workflow mapping. Values not passed are assumed to indicate no change for that field.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.updateDraftWorkflowMapping_pu
      x-api-path-slug: api2workflowschemeiddraftworkflow-put
      parameters:
      - in: path
        name: id
        description: the id of the parent scheme
      - in: query
        name: workflowName
        description: the name of the workflow mapping to update
      responses:
        200:
          description: OK
      tags:
      - Draft
      - Workflow
      - Mapping
    delete:
      summary: Delete draft workflow mapping
      description: Delete the passed workflow from the draft workflow scheme.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.deleteDraftWorkflowMapping_de
      x-api-path-slug: api2workflowschemeiddraftworkflow-delete
      parameters:
      - in: path
        name: id
        description: the id of the parent scheme
      - in: query
        name: workflowName
        description: the name of the workflow to delete
      responses:
        200:
          description: OK
      tags:
      - Draft
      - Workflow
      - Mapping
  /api/2/workflowscheme/{id}/workflow:
    put:
      summary: Update workflow mapping
      description: |-
        Update the scheme to include the passed mapping.

        The body is a representation of the workflow mapping. Values not passed are assumed to indicate no change for that field.

        The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.updateWorkflowMapping_put
      x-api-path-slug: api2workflowschemeidworkflow-put
      parameters:
      - in: path
        name: id
        description: the id of the scheme
      - in: query
        name: workflowName
        description: the name of the workflow mapping to update
      responses:
        200:
          description: OK
      tags:
      - Workflow
      - Mapping
    delete:
      summary: Delete workflow mapping
      description: Delete the passed workflow from the workflow scheme.
      operationId: com.atlassian.jira.rest.v2.admin.workflowscheme.WorkflowSchemeResource.deleteWorkflowMapping_delete
      x-api-path-slug: api2workflowschemeidworkflow-delete
      parameters:
      - in: path
        name: id
        description: the id of the scheme
      - in: query
        name: updateDraftIfNeeded
        description: flag to indicate if a draft should be created if necessary to
          delete the workflow from the scheme
      - in: query
        name: workflowName
        description: the name of the workflow to delete
      responses:
        200:
          description: OK
      tags:
      - Workflow
      - Mapping
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