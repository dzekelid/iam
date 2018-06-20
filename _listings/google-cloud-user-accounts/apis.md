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
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud User Accounts API Get IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{resource}/getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcegetiampolicy-get-openapi.md
- name: Google Cloud User Accounts API Set IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{resource}/setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcesetiampolicy-post-openapi.md
- name: Google Cloud User Accounts API Test IAM Permissions
  x-api-slug: google-cloud-user-accounts-api
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{resource}/testIamPermissions
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcetestiampermissions-post-openapi.md
- name: Google Cloud User Accounts API Get User IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{resource}/getIamPolicy
  tags: User IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalusersresourcegetiampolicy-get-openapi.md
- name: Google Cloud User Accounts API Set User IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{resource}/setIamPolicy
  tags: User IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalusersresourcesetiampolicy-post-openapi.md
- name: Google Cloud User Accounts API Test User IAM Permissions
  x-api-slug: google-cloud-user-accounts-api
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{resource}/testIamPermissions
  tags: User IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/projectglobalusersresourcetestiampermissions-post-openapi.md
- name: Google Cloud User Accounts API
  x-api-slug: google-cloud-user-accounts-api
  description: Service for managing the global Google Cloud user accounts. This API
    reference is organized by resource type. Each resource type has one or more data
    representations and one or more methods.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-user-accounts/openapi.md
x-common:
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