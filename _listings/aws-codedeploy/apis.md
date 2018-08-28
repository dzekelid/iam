---
name: AWS CodeDeploy
x-slug: aws-codedeploy
description: AWS CodeDeploy is a service that automates code deployments to any instance,
  including Amazon EC2 instances and instances running on-premises. AWS CodeDeploy
  makes it easier for you to rapidly release new features, helps you avoid downtime
  during application deployment, and handles the complexity of updating your applications.
  You can use AWS CodeDeploy to automate software deployments, eliminating the need
  for error-prone manual operations, and the service scales with your infrastructure
  so you can easily deploy to one instance or thousands.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
x-kinRank: "10"
x-alexaRank: "0"
tags: IAM
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/aws-codedeploy/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeDeploy API - List Applications
  x-api-slug: actionlistapplications-get
  description: |-
    Lists the applications registered with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/aws-codedeploy/actionlistapplications-get-openapi.md
- name: AWS CodeDeploy API - List Deployment Configs
  x-api-slug: actionlistdeploymentconfigs-get
  description: |-
    Lists the deployment configurations with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/aws-codedeploy/actionlistdeploymentconfigs-get-openapi.md
- name: AWS CodeDeploy API - List Deployment Groups
  x-api-slug: actionlistdeploymentgroups-get
  description: |-
    Lists the deployment groups for an application registered with the applicable IAM
                user or AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/aws-codedeploy/actionlistdeploymentgroups-get-openapi.md
- name: AWS CodeDeploy API - List Deployment Instances
  x-api-slug: actionlistdeploymentinstances-get
  description: |-
    Lists the instance for a deployment associated with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/aws-codedeploy/actionlistdeploymentinstances-get-openapi.md
- name: AWS CodeDeploy API - List Deployments
  x-api-slug: actionlistdeployments-get
  description: |-
    Lists the deployments in a deployment group for an application registered with the
                applicable IAM user or AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: :///
  tags: Amazon Web Services, SDK, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/aws-codedeploy/actionlistdeployments-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.codecommit.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.codedeploy.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codedeploy
- type: x-documentation
  url: http://docs.aws.amazon.com/codedeploy/latest/APIReference
- type: x-faq
  url: https://aws.amazon.com/codedeploy/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=179
- type: x-getting-started
  url: https://aws.amazon.com/codedeploy/getting-started/
- type: x-integrations
  url: https://aws.amazon.com/codedeploy/product-integrations/
- type: x-partners
  url: https://aws.amazon.com/solutions/partners/dev-ops/
- type: x-pricing
  url: https://aws.amazon.com/codedeploy/pricing/
- type: x-tutorials
  url: https://aws.amazon.com/codedeploy/developer-resources/#tutorials
- type: x-website
  url: https://aws.amazon.com/codedeploy/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---