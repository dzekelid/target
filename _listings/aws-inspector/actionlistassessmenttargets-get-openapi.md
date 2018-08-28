---
swagger: "2.0"
x-collection-name: AWS Inspector
x-complete: 0
info:
  title: AWS Inspector API List Assessment Targets
  version: 1.0.0
  description: Lists the ARNs of the assessment targets within this AWS account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateAssessmentTarget:
    get:
      summary: Create Assessment Target
      description: |-
        Creates a new assessment target using the ARN of the resource group that is generated
                 by.
      operationId: createAssessmentTarget
      x-api-path-slug: actioncreateassessmenttarget-get
      parameters:
      - in: query
        name: assessmentTargetName
        description: The user-defined name that identifies the assessment target that
          you want to create
        type: string
      - in: query
        name: resourceGroupArn
        description: The ARN that specifies the resource group that is used to create
          the assessment         target
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assessment Targets
  /?Action=DeleteAssessmentTarget:
    get:
      summary: Delete Assessment Target
      description: |-
        Deletes the assessment target that is specified by the ARN of the assessment
                 target.
      operationId: deleteAssessmentTarget
      x-api-path-slug: actiondeleteassessmenttarget-get
      parameters:
      - in: query
        name: assessmentTargetArn
        description: The ARN that specifies the assessment target that you want to
          delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assessment Targets
  /?Action=DescribeAssessmentTargets:
    get:
      summary: Describe Assessment Targets
      description: |-
        Describes the assessment targets that are specified by the ARNs of the assessment
                 targets.
      operationId: describeAssessmentTargets
      x-api-path-slug: actiondescribeassessmenttargets-get
      parameters:
      - in: query
        name: assessmentTargetArns
        description: The ARNs that specifies the assessment targets that you want
          to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assessment Targets
  /?Action=ListAssessmentTargets:
    get:
      summary: List Assessment Targets
      description: Lists the ARNs of the assessment targets within this AWS account.
      operationId: listAssessmentTargets
      x-api-path-slug: actionlistassessmenttargets-get
      parameters:
      - in: query
        name: filter
        description: You can use this parameter to specify a subset of data to be
          included in the actions         response
        type: string
      - in: query
        name: maxResults
        description: You can use this parameter to indicate the maximum number of
          items you want in the         response
        type: string
      - in: query
        name: nextToken
        description: You can use this parameter when paginating results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assessment Targets
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