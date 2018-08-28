---
swagger: "2.0"
x-collection-name: AWS Elastic Load Balancing
x-complete: 0
info:
  title: AWS Elastic Load Balancing API Describe Target Group Attributes
  version: 1.0.0
  description: Describes the attributes for the specified target group.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateTargetGroup:
    get:
      summary: Create Target Group
      description: Creates a target group.
      operationId: createTargetGroup
      x-api-path-slug: actioncreatetargetgroup-get
      parameters:
      - in: query
        name: HealthCheckIntervalSeconds
        description: The approximate amount of time, in seconds, between health checks
          of an individual target
        type: string
      - in: query
        name: HealthCheckPath
        description: The ping path that is the destination on the targets for health
          checks
        type: string
      - in: query
        name: HealthCheckPort
        description: The port the load balancer uses when performing health checks
          on targets
        type: string
      - in: query
        name: HealthCheckProtocol
        description: The protocol the load balancer uses when performing health checks
          on targets
        type: string
      - in: query
        name: HealthCheckTimeoutSeconds
        description: The amount of time, in seconds, during which no response from
          a target means a failed health check
        type: string
      - in: query
        name: HealthyThresholdCount
        description: The number of consecutive health checks successes required before
          considering an unhealthy target healthy
        type: string
      - in: query
        name: Matcher
        description: The HTTP codes to use when checking for a successful response
          from a target
        type: string
      - in: query
        name: Name
        description: The name of the target group
        type: string
      - in: query
        name: Port
        description: The port on which the targets receive traffic
        type: string
      - in: query
        name: Protocol
        description: The protocol to use for routing traffic to the targets
        type: string
      - in: query
        name: UnhealthyThresholdCount
        description: The number of consecutive health check failures required before
          considering a target unhealthy
        type: string
      - in: query
        name: VpcId
        description: The identifier of the virtual private cloud (VPC)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Target Groups
  /?Action=DeleteTargetGroup:
    get:
      summary: Delete Target Group
      description: Deletes the specified target group.
      operationId: deleteTargetGroup
      x-api-path-slug: actiondeletetargetgroup-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Target Groups
  /?Action=DeregisterTargets:
    get:
      summary: Deregister Targets
      description: Deregisters the specified targets from the specified target group.
      operationId: deregisterTargets
      x-api-path-slug: actionderegistertargets-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      - in: query
        name: Targets.member.N
        description: The targets
        type: string
      responses:
        200:
          description: OK
      tags:
      - Targets
  /?Action=DescribeTargetGroupAttributes:
    get:
      summary: Describe Target Group Attributes
      description: Describes the attributes for the specified target group.
      operationId: describeTargetGroupAttributes
      x-api-path-slug: actiondescribetargetgroupattributes-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Target Groups
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