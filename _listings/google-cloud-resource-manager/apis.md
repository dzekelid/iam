---
name: Google Cloud Resource Manager
x-slug: google-cloud-resource-manager
description: Google Cloud Platform provides resource containers such as Organizations
  and Projects, that allow you to group and hierarchically organize other Cloud Platform
  resources. This hierarchical organization lets you easily manage common aspects
  of your resources such as access control and configuration settings. The Google
  Cloud Resource Manager service enables you to programmatically manage these resource
  containers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-resource-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Resource Manager API Get IAM Policy
  x-api-slug: google-cloud-resource-manager-api
  description: |-
    Returns the IAM access control policy for the specified Project.
    Permission is denied if the policy or the resource does not exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com////v1/projects/{resource}:getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-resource-manager/v1projectsresourcegetiampolicy-post-openapi.md
- name: Google Cloud Resource Manager API Set IAM Policy
  x-api-slug: google-cloud-resource-manager-api
  description: |-
    Sets the IAM access control policy for the specified Project. Replaces
    any existing policy.

    The following constraints apply when using `setIamPolicy()`:

    + Project does not support `allUsers` and `allAuthenticatedUsers` as
    `members` in a `Binding` of a `Policy`.

    + The owner role can be granted only to `user` and `serviceAccount`.

    + Service accounts can be made owners of a project directly
    without any restrictions. However, to be added as an owner, a user must be
    invited via Cloud Platform console and must accept the invitation.

    + A user cannot be granted the owner role using `setIamPolicy()`. The user
    must be granted the owner role using the Cloud Platform Console and must
    explicitly accept the invitation.

    + Invitations to grant the owner role cannot be sent using
    `setIamPolicy()`;
    they must be sent only using the Cloud Platform Console.

    + Membership changes that leave the project without any owners that have
    accepted the Terms of Service (ToS) will be rejected.

    + There must be at least one owner who has accepted the Terms of
    Service (ToS) agreement in the policy. Calling `setIamPolicy()` to
    to remove the last ToS-accepted owner from the policy will fail. This
    restriction also applies to legacy projects that no longer have owners
    who have accepted the ToS. Edits to IAM policies will be rejected until
    the lack of a ToS-accepting owner is rectified.

    + Calling this method requires enabling the App Engine Admin API.

    Note: Removing service accounts from policies or changing their roles
    can render services completely inoperable. It is important to understand
    how the service account is being used before removing or updating its
    roles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com////v1/projects/{resource}:setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-resource-manager/v1projectsresourcesetiampolicy-post-openapi.md
- name: Google Cloud Resource Manager API Test IAM Policy
  x-api-slug: google-cloud-resource-manager-api
  description: Returns permissions that a caller has on the specified Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com////v1/projects/{resource}:testIamPermissions
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-resource-manager/v1projectsresourcetestiampermissions-post-openapi.md
- name: Google Cloud Resource Manager API
  x-api-slug: google-cloud-resource-manager-api
  description: Google Cloud Platform provides resource containers such as Organizations
    and Projects, that allow you to group and hierarchically organize other Cloud
    Platform resources. This hierarchical organization lets you easily manage common
    aspects of your resources such as access control and configuration settings. The
    Google Cloud Resource Manager service enables you to programmatically manage these
    resource containers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-resource-manager/openapi.md
x-common:
- type: x-authentication
  url: https://cloud.google.com/resource-manager/docs/authorizing
- type: x-code
  url: https://cloud.google.com/resource-manager/docs/libraries
- type: x-documentation
  url: https://cloud.google.com/resource-manager/docs/
- type: x-errors
  url: https://cloud.google.com/resource-manager/docs/core_errors
- type: x-how-to-guides
  url: https://cloud.google.com/resource-manager/docs/how-to
- type: x-performance
  url: https://cloud.google.com/resource-manager/docs/performance
- type: x-pricing
  url: https://cloud.google.com/resource-manager/pricing
- type: x-rate-limits
  url: https://cloud.google.com/resource-manager/docs/limits
- type: x-website
  url: https://cloud.google.com/resource-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---