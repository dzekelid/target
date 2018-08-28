---
name: AWS Inspector
x-slug: aws-inspector
description: Amazon Inspector is an automated security assessment service that helps
  improve the security and compliance of applications deployed on AWS. Amazon Inspector
  automatically assesses applications for vulnerabilities or deviations from best
  practices. After performing an assessment, Amazon Inspector produces a detailed
  list of security findings prioritized by level of severity.To help you get started
  quickly, Amazon Inspector includes a knowledge base of hundreds of rules mapped
  to common security best practices and vulnerability definitions. Examples of built-in
  rules include checking for remote root login being enabled, or vulnerable software
  versions installed. These rules are regularly updated by AWS security researchers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Target
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-inspector/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Inspector API - Create Assessment Target
  x-api-slug: actioncreateassessmenttarget-get
  description: |-
    Creates a new assessment target using the ARN of the resource group that is generated
             by.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-inspector/actioncreateassessmenttarget-get-openapi.md
- name: AWS Inspector API - Delete Assessment Target
  x-api-slug: actiondeleteassessmenttarget-get
  description: |-
    Deletes the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-inspector/actiondeleteassessmenttarget-get-openapi.md
- name: AWS Inspector API - Describe Assessment Targets
  x-api-slug: actiondescribeassessmenttargets-get
  description: |-
    Describes the assessment targets that are specified by the ARNs of the assessment
             targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-inspector/actiondescribeassessmenttargets-get-openapi.md
- name: AWS Inspector API - List Assessment Targets
  x-api-slug: actionlistassessmenttargets-get
  description: Lists the ARNs of the assessment targets within this AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-inspector/actionlistassessmenttargets-get-openapi.md
- name: AWS Inspector API - Update Assessment Target
  x-api-slug: actionupdateassessmenttarget-get
  description: |-
    Updates the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/target/master/_listings/aws-inspector/actionupdateassessmenttarget-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.identity.and.access.management.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.inspector.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/inspector/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/inspector/faqs/
- type: x-getting-started
  url: https://docs.aws.amazon.com/inspector/latest/userguide/inspector_quickstart.html
- type: x-partners
  url: https://aws.amazon.com/inspector/partners/
- type: x-pricing
  url: https://aws.amazon.com/inspector/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/inspector/customers/
- type: x-website
  url: https://aws.amazon.com/inspector/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---