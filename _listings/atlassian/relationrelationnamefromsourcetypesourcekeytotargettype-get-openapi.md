---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Find target entities related to a source entity
  description: "Returns all target entities that have a particular relationship to
    the \nsource entity. Note, relationships are one way.\n\nFor example, the following
    method finds all content that the current user \nhas an 'ignore' relationship
    with:\n`GET https://your-domain.atlassian.net/wiki/rest/api/relation/ignore/from/user/current/to/content`\nNote,
    'ignore' is an example custom relationship type.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view both the target entity and source entity."
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
  /relation/{relationName}/from/{sourceType}/{sourceKey}/to/{targetType}:
    get:
      summary: Find target entities related to a source entity
      description: "Returns all target entities that have a particular relationship
        to the \nsource entity. Note, relationships are one way.\n\nFor example, the
        following method finds all content that the current user \nhas an 'ignore'
        relationship with:\n`GET https://your-domain.atlassian.net/wiki/rest/api/relation/ignore/from/user/current/to/content`\nNote,
        'ignore' is an example custom relationship type.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to view both the target entity and source entity."
      operationId: com.atlassian.confluence.plugins.restapi.resources.RelationResource.findTargetFromSource_get
      x-api-path-slug: relationrelationnamefromsourcetypesourcekeytotargettype-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the response
          object to expand
      - in: query
        name: limit
        description: The maximum number of relationships to return per page
      - in: path
        name: relationName
        description: The name of the relationship
      - in: path
        name: sourceKey
        description: '- The identifier for the source entity:- If `sourceType` is
          user, then specify either current (logged-in   user) or the user key'
      - in: query
        name: sourceStatus
        description: The status of the source
      - in: path
        name: sourceType
        description: The source entity type of the relationship
      - in: query
        name: sourceVersion
        description: The version of the source
      - in: query
        name: start
        description: The starting index of the returned relationships
      - in: query
        name: targetStatus
        description: The status of the target
      - in: path
        name: targetType
        description: The target entity type of the relationship
      - in: query
        name: targetVersion
        description: The version of the target
      responses:
        200:
          description: OK
      tags:
      - Find
      - Target
      - Entities
      - Related
      - To
      - Source
      - Entity
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