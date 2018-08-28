---
swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 0
info:
  title: AWS Auto Scaling API Attach Load Balancer Target Groups
  version: 1.0.0
  description: Attaches one or more target groups to the specified Auto Scaling group.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AttachLoadBalancerTargetGroups:
    get:
      summary: Attach Load Balancer Target Groups
      description: Attaches one or more target groups to the specified Auto Scaling
        group.
      operationId: attachLoadBalancerTargetGroups
      x-api-path-slug: actionattachloadbalancertargetgroups-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: TargetGroupARNs.member.N
        description: The Amazon Resource Names (ARN) of the target groups
        type: string
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
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