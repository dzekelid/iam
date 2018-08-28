---
name: Google Cloud Key Management Service
x-slug: google-cloud-key-management-service
description: Cloud KMS is a cloud-hosted key management service that lets you manage
  encryption for your cloud services the same way you do on-premises. You can generate,
  use, rotate and destroy AES256 encryption keys. Cloud KMS is integrated with IAM
  and Cloud Audit Logging so that you can manage permissions on individual keys, and
  monitor how these are used. Use Cloud KMS to protect secrets and other sensitive
  data which you need to store in Google Cloud Platform.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kms-lead.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-key-management-service/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Key Management Service API Get IAM Policy
  x-api-slug: google-cloud-key-management-service-api
  description: |-
    Gets the access control policy for a resource.
    Returns an empty policy if the resource exists and does not have a policy
    set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kms-lead.png
  humanURL: https://cloud.google.com/kms/
  baseURL: ://cloudkms.googleapis.com////v1/{resource}:getIamPolicy
  tags: IAM Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-key-management-service/v1resourcegetiampolicy-get-openapi.md
- name: Google Cloud Key Management Service API Set IAM Policy
  x-api-slug: google-cloud-key-management-service-api
  description: |-
    Sets the access control policy on the specified resource. Replaces any
    existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kms-lead.png
  humanURL: https://cloud.google.com/kms/
  baseURL: ://cloudkms.googleapis.com////v1/{resource}:setIamPolicy
  tags: IAM Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-key-management-service/v1resourcesetiampolicy-post-openapi.md
- name: Google Cloud Key Management Service API Test IAM Permissions
  x-api-slug: google-cloud-key-management-service-api
  description: |-
    Returns permissions that a caller has on the specified resource.
    If the resource does not exist, this will return an empty set of
    permissions, not a NOT_FOUND error.

    Note: This operation is designed to be used for building permission-aware
    UIs and command-line tools, not for authorization checking. This operation
    may "fail open" without warning.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kms-lead.png
  humanURL: https://cloud.google.com/kms/
  baseURL: ://cloudkms.googleapis.com////v1/{resource}:testIamPermissions
  tags: IAM Permission
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-key-management-service/v1resourcetestiampermissions-post-openapi.md
- name: Google Cloud Key Management Service API
  x-api-slug: google-cloud-key-management-service-api
  description: Cloud KMS is a cloud-hosted key management service that lets you manage
    encryption for your cloud services the same way you do on-premises. You can generate,
    use, rotate and destroy AES256 encryption keys. Cloud KMS is integrated with IAM
    and Cloud Audit Logging so that you can manage permissions on individual keys,
    and monitor how these are used. Use Cloud KMS to protect secrets and other sensitive
    data which you need to store in Google Cloud Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kms-lead.png
  humanURL: https://cloud.google.com/kms/
  baseURL: ://cloudkms.googleapis.com//
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-key-management-service/openapi.md
x-common:
- type: x-change-log
  url: https://cloud.google.com/kms/docs/release-notes
- type: x-code
  url: https://cloud.google.com/kms/docs/reference/libraries
- type: x-concepts
  url: https://cloud.google.com/kms/docs/concepts
- type: x-getting-started
  url: https://cloud.google.com/kms/docs/quickstart
- type: x-how-to-guides
  url: https://cloud.google.com/kms/docs/how-tos
- type: x-issues
  url: https://cloud.google.com/kms/known-issues
- type: x-pricing
  url: https://cloud.google.com/kms/pricing
- type: x-rate-limits
  url: https://cloud.google.com/kms/quota
- type: x-service-level-agreement
  url: https://cloud.google.com/kms/sla
- type: x-support
  url: https://cloud.google.com/kms/docs/support
- type: x-website
  url: https://cloud.google.com/kms/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---