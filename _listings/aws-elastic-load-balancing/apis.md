---
name: AWS Elastic Load Balancing
x-slug: aws-elastic-load-balancing
description: Elastic Load Balancing automatically distributes incoming application
  traffic across multiple Amazon EC2 instances. It enables you to achieve fault tolerance
  in your applications, seamlessly providing the required amount of load balancing
  capacity needed to route application traffic.Elastic Load Balancing offers two types
  of load balancers that both feature high availability, automatic scaling, and robust
  security. These include theClassic Load Balancerthat routes traffic based on either
  application or network level information, and theApplication Load Balancerthat routes
  traffic based on advanced application level information that includes the content
  of the request. The Classic Load Balancer is ideal for simple load balancing of
  traffic across multiple EC2 instances, while the Application Load Balancer is ideal
  for applications needing advanced routing capabilities, microservices, and container-based
  architectures. Application Load Balancer offers ability to route traffic to multiple
  services or load balance across multiple ports on the same EC2 instance.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Target
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Elastic Load Balancing API - Create Target Group
  x-api-slug: actioncreatetargetgroup-get
  description: Creates a target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actioncreatetargetgroup-get-openapi.md
- name: AWS Elastic Load Balancing API - Delete Target Group
  x-api-slug: actiondeletetargetgroup-get
  description: Deletes the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actiondeletetargetgroup-get-openapi.md
- name: AWS Elastic Load Balancing API - Deregister Targets
  x-api-slug: actionderegistertargets-get
  description: Deregisters the specified targets from the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actionderegistertargets-get-openapi.md
- name: AWS Elastic Load Balancing API - Describe Target Group Attributes
  x-api-slug: actiondescribetargetgroupattributes-get
  description: Describes the attributes for the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actiondescribetargetgroupattributes-get-openapi.md
- name: AWS Elastic Load Balancing API - Describe Target Groups
  x-api-slug: actiondescribetargetgroups-get
  description: Describes the specified target groups or all of your target groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actiondescribetargetgroups-get-openapi.md
- name: AWS Elastic Load Balancing API - Describe Target Health
  x-api-slug: actiondescribetargethealth-get
  description: Describes the health of the specified targets or all of your targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actiondescribetargethealth-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actiondescribetargethealth-get-openapi.md
- name: AWS Elastic Load Balancing API - Modify Target Group
  x-api-slug: actionmodifytargetgroup-get
  description: Modifies the health checks used when evaluating the health state of
    the targets in the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actionmodifytargetgroup-get-openapi.md
- name: AWS Elastic Load Balancing API - Modify Target Group Attributes
  x-api-slug: actionmodifytargetgroupattributes-get
  description: Modifies the specified attributes of the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actionmodifytargetgroupattributes-get-openapi.md
- name: AWS Elastic Load Balancing API - Register Targets
  x-api-slug: actionregistertargets-get
  description: Registers the specified targets with the specified target group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
  humanURL: https://aws.amazon.com/elasticloadbalancing/
  baseURL: :///
  tags: Amazon Web Services, Compute, Servers, Performance, Availability, Stack Network,
    API Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-elastic-load-balancing/actionregistertargets-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.elastic.beanstalk.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.elastic.load.balancing.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/elbv2/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/pricing/
- type: x-website
  url: https://aws.amazon.com/elasticloadbalancing/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---