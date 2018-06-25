---
name: Google Cloud Identity Access Management
x-slug: google-cloud-identity-access-management
description: Google Cloud Identity &amp; Access Management (IAM) lets administrators
  authorize who can take action on specific resources, giving you full control and
  visibility to manage cloud resources centrally. For established enterprises with
  complex organizational structures, hundreds of workgroups and potentially many more
  projects, Cloud IAM provides a unified view into security policy across your entire
  organization, with built-in auditing to ease compliance processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-identity-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Identity & Access Management API Return IAM Access Control Policy
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Returns the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{resource}:getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-identity-access-management/v1resourcegetiampolicy-post-openapi.md
- name: Google Cloud Identity & Access Management API Set IAM Access Control Policy
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Sets the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{resource}:setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-identity-access-management/v1resourcesetiampolicy-post-openapi.md
- name: Google Cloud Identity & Access Management API
  x-api-slug: google-cloud-identity--access-management-api
  description: Google Cloud Identity &amp; Access Management (IAM) lets administrators
    authorize who can take action on specific resources, giving you full control and
    visibility to manage cloud resources centrally. For established enterprises with
    complex organizational structures, hundreds of workgroups and potentially many
    more projects, Cloud IAM provides a unified view into security policy across your
    entire organization, with built-in auditing to ease compliance processes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-identity-access-management/openapi.md
x-common:
- type: x-concepts
  url: https://cloud.google.com/iam/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/iam/docs/
- type: x-faq
  url: https://cloud.google.com/iam/docs/faq
- type: x-getting-started
  url: https://cloud.google.com/iam/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/iam/docs/how-to
- type: x-website
  url: https://cloud.google.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---