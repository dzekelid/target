{
  "info": {
    "name": "AWS Elastic Load Balancing API Describe Target Health",
    "_postman_id": "21072805-3c26-409d-acef-086296a54b89",
    "description": "Describes the health of the specified targets or all of your targets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "7ded4342-8923-4928-9f25-5f5d856a43a7",
          "name": "addTags",
          "request": {
            "url": "http://example.com/api/?Action=AddTags?ResourceArns.member.N=ResourceArns.member.N&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified tags to the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b74e47b2-49b2-4d7e-97ec-8cb777fbf5b5"
            }
          ]
        },
        {
          "id": "2b13523e-4f44-4953-bcfa-b6da8f5a707c",
          "name": "describeTags",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTags?ResourceArns.member.N=ResourceArns.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the tags for the specified resources."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c60d9406-1b09-447f-a5ff-4709eaaea21f"
            }
          ]
        }
      ]
    },
    {
      "name": "Listeners",
      "item": [
        {
          "id": "53c40305-571c-4dab-af8c-aecf3e088c3a",
          "name": "createListener",
          "request": {
            "url": "http://example.com/api/?Action=CreateListener?Certificates.member.N=Certificates.member.N&DefaultActions.member.N=DefaultActions.member.N&LoadBalancerArn=LoadBalancerArn&Port=Port&Protocol=Protocol&SslPolicy=SslPolicy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a listener for the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "281ca0de-3da6-4df2-aa97-b49187d91c9e"
            }
          ]
        },
        {
          "id": "723a1bf3-e75c-4152-b91d-974bb379b45d",
          "name": "deleteListener",
          "request": {
            "url": "http://example.com/api/?Action=DeleteListener?ListenerArn=ListenerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b191f9df-f6ce-4e0f-a372-ec1c18233169"
            }
          ]
        },
        {
          "id": "3cc72a13-f758-43fe-b1a4-52fe778596de",
          "name": "describeListeners",
          "request": {
            "url": "http://example.com/api/?Action=DescribeListeners?ListenerArns.member.N=ListenerArns.member.N&LoadBalancerArn=LoadBalancerArn&Marker=Marker&PageSize=PageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified listeners or the listeners for the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efc2ca1d-6ca1-452f-bc39-d0882a3bedf5"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "54393c54-f0c0-4009-b591-73f4658276f9",
          "name": "createLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=CreateLoadBalancer?Name=Name&Scheme=Scheme&SecurityGroups.member.N=SecurityGroups.member.N&Subnets.member.N=Subnets.member.N&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c44fa23d-15d6-40d7-9ac7-8bce5169e757"
            }
          ]
        },
        {
          "id": "dfe9e574-8cea-4f96-beec-aaf74b009519",
          "name": "deleteLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLoadBalancer?LoadBalancerArn=LoadBalancerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Application Load Balancer and its attached listeners."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad829b6f-f278-4ca8-82ea-adb5d83eeee8"
            }
          ]
        },
        {
          "id": "ffbfcbe3-fa5b-4e8b-9216-7af2323c78dd",
          "name": "describeLoadBalancerAttributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBalancerAttributes?LoadBalancerArn=LoadBalancerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the attributes for the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbdb4013-ca60-4af2-9dba-e92cbe71d225"
            }
          ]
        },
        {
          "id": "c3468526-e6c5-4c78-aef7-999d663f1be1",
          "name": "describeLoadBalancers",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBalancers?LoadBalancerArns.member.N=LoadBalancerArns.member.N&Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified Application Load Balancers or all of your Application Load Balancers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "807a24c7-7e34-4437-8938-751690d9ea20"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "9215c41e-5520-4f85-9bc7-1cbd739ff316",
          "name": "createRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateRule?Actions.member.N=Actions.member.N&Conditions.member.N=Conditions.member.N&ListenerArn=ListenerArn&Priority=Priority",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a rule for the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58f2044a-8e7f-4de8-b187-63fd8c32d170"
            }
          ]
        },
        {
          "id": "2035dc67-1c58-4f91-b0fd-f99137a8613a",
          "name": "deleteRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRule?RuleArn=RuleArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b8cb24c-3d9b-445f-9320-791032241aa5"
            }
          ]
        },
        {
          "id": "2ae9ee2f-2b77-479a-97dc-cf056e6ea45f",
          "name": "describeRules",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRules?ListenerArn=ListenerArn&RuleArns.member.N=RuleArns.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified rules or the rules for the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4aad9c08-a076-45c9-8d2b-6502d421e88f"
            }
          ]
        }
      ]
    },
    {
      "name": "Target Groups",
      "item": [
        {
          "id": "10c9675d-8786-4bfe-9f0a-175e0b4cd630",
          "name": "createTargetGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateTargetGroup?HealthCheckIntervalSeconds=HealthCheckIntervalSeconds&HealthCheckPath=HealthCheckPath&HealthCheckPort=HealthCheckPort&HealthCheckProtocol=HealthCheckProtocol&HealthCheckTimeoutSeconds=HealthCheckTimeoutSeconds&HealthyThresholdCount=HealthyThresholdCount&Matcher=Matcher&Name=Name&Port=Port&Protocol=Protocol&UnhealthyThresholdCount=UnhealthyThresholdCount&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46adb5ae-c824-4c95-9e0c-6687fbc7e161"
            }
          ]
        },
        {
          "id": "118e7ee5-151d-4109-9b54-ebbb3ddf5dda",
          "name": "deleteTargetGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTargetGroup?TargetGroupArn=TargetGroupArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78fa64ae-8431-4f28-832e-eb2d980377be"
            }
          ]
        },
        {
          "id": "91ac0c62-ae23-49ec-b982-f117ea3b85da",
          "name": "describeTargetGroupAttributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTargetGroupAttributes?TargetGroupArn=TargetGroupArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the attributes for the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00c33eb9-cda8-4989-93d0-502bb26ef1b4"
            }
          ]
        },
        {
          "id": "c8ab8945-84c6-4e6b-8c32-55fd4a4a0c9c",
          "name": "describeTargetGroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTargetGroups?LoadBalancerArn=LoadBalancerArn&Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize&TargetGroupArns.member.N=TargetGroupArns.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified target groups or all of your target groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fa618c5-788a-41d7-8fac-b6597bdcd240"
            }
          ]
        }
      ]
    },
    {
      "name": "Targets",
      "item": [
        {
          "id": "8a5275e2-c279-4f7f-b7cc-150816a3b13e",
          "name": "deregisterTargets",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterTargets?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters the specified targets from the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afa85042-eabc-4db9-8298-6b7418eece30"
            }
          ]
        }
      ]
    },
    {
      "name": "SSL Policies",
      "item": [
        {
          "id": "53306ee9-315a-43b4-a95b-404050bf4192",
          "name": "describeSSLPolicies",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSSLPolicies?Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified policies or all policies used for SSL negotiation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0869a8e4-a313-41e6-a8cc-916c641b24e7"
            }
          ]
        }
      ]
    },
    {
      "name": "Target Health",
      "item": [
        {
          "id": "71dc130b-6887-4ec2-b979-3ad03c586d40",
          "name": "describeTargetHealth",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTargetHealth?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the health of the specified targets or all of your targets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "926e8428-7d60-4d0a-8dc1-350f74392148"
            }
          ]
        }
      ]
    }
  ]
}