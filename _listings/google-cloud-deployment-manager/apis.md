---
name: Google Cloud Deployment Manager
x-slug: google-cloud-deployment-manager
description: Google Cloud Deployment Manager allows you to specify all the resources
  needed for your application in a declarative format using yaml. You can also use
  Python or Jinja2 templates to parameterize the configuration and allow reuse of
  common deployment paradigms such as a load balanced, auto-scaled instance group.
  Treat your configuration as code and perform repeatable deployments.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-deployment-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Deployment Manager Get IAM Policy
  x-api-slug: google-cloud-deployment-manager
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{resource}/getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsresourcegetiampolicy-get-openapi.md
- name: Google Cloud Deployment Manager Set IAM Policy
  x-api-slug: google-cloud-deployment-manager
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{resource}/setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsresourcesetiampolicy-post-openapi.md
- name: Google Cloud Deployment Manager Test IAM Permission
  x-api-slug: google-cloud-deployment-manager
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{resource}/testIamPermissions
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsresourcetestiampermissions-post-openapi.md
- name: Google Cloud Deployment Manager
  x-api-slug: google-cloud-deployment-manager
  description: Google Cloud Deployment Manager allows you to specify all the resources
    needed for your application in a declarative format using yaml. You can also use
    Python or Jinja2 templates to parameterize the configuration and allow reuse of
    common deployment paradigms such as a load balanced, auto-scaled instance group.
    Treat your configuration as code and perform repeatable deployments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https:///
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-deployment-manager/openapi.md
x-common:
- type: x-authentication
  url: https://cloud.google.com/deployment-manager/docs/reference/latest/authorization
- type: x-change-log
  url: https://cloud.google.com/deployment-manager/docs/release-notes
- type: x-code
  url: https://cloud.google.com/deployment-manager/docs/reference/latest/libraries
- type: x-concepts
  url: https://cloud.google.com/deployment-manager/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/deployment-manager/docs/
- type: x-getting-started
  url: https://cloud.google.com/deployment-manager/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/deployment-manager/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/deployment-manager/pricing-and-quotas
- type: x-tutorials
  url: https://cloud.google.com/deployment-manager/docs/tutorials
- type: x-website
  url: https://cloud.google.com/deployment-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---