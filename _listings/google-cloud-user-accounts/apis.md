---
name: Google Cloud User Accounts
x-slug: google-cloud-user-accounts
description: Service for managing the global Google Cloud user accounts. This API
  reference is organized by resource type. Each resource type has one or more data
  representations and one or more methods.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/apis.md
specificationVersion: "0.14"
apis:
- name: Cloud User Accounts - Get IAM Policy
  x-api-slug: projectglobalgroupsresourcegetiampolicy-get
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcegetiampolicy-get-openapi.md
- name: Cloud User Accounts - Set IAM Policy
  x-api-slug: projectglobalgroupsresourcesetiampolicy-post
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcesetiampolicy-post-openapi.md
- name: Cloud User Accounts - Test IAM Permissions
  x-api-slug: projectglobalgroupsresourcetestiampermissions-post
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcetestiampermissions-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.storage.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.user.accounts.stack.network
- type: x-code
  url: https://cloud.google.com/compute/docs/access/user-accounts/api/libraries
- type: x-guides
  url: https://cloud.google.com/compute/docs/access/user-accounts/api/how-tos/how-tos
- type: x-website
  url: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---