---
name: Google Cloud Pub Sub
x-slug: google-cloud-pub-sub
description: Cloud Pub/Sub is a fully-managed real-time messaging service that allows
  you to send and receive messages between independent applications. You can leverage
  Cloud Pub/Sub&rsquo;s flexibility to decouple systems and components hosted on Google
  Cloud Platform or elsewhere on the Internet. By building on the same technology
  Google uses, Cloud Pub/Sub is designed to provide &ldquo;at least once&rdquo; delivery
  at low latency with on-demand scalability to 1 million messages per second (and
  beyond).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-pub-sub-middleware.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-pub-sub/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Pub/Sub API Get IAM Policy
  x-api-slug: google-cloud-pubsub-api
  description: |-
    Gets the access control policy for a resource.
    Returns an empty policy if the resource exists and does not have a policy
    set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-pub-sub-middleware.png
  humanURL: https://cloud.google.com/pubsub/docs/
  baseURL: ://pubsub.googleapis.com////v1/{resource}:getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-pub-sub/v1resourcegetiampolicy-get-openapi.md
- name: Google Cloud Pub/Sub API Set IAM Policy
  x-api-slug: google-cloud-pubsub-api
  description: |-
    Sets the access control policy on the specified resource. Replaces any
    existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-pub-sub-middleware.png
  humanURL: https://cloud.google.com/pubsub/docs/
  baseURL: ://pubsub.googleapis.com////v1/{resource}:setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-pub-sub/v1resourcesetiampolicy-post-openapi.md
- name: Google Cloud Pub/Sub API Test IAM Permission
  x-api-slug: google-cloud-pubsub-api
  description: |-
    Returns permissions that a caller has on the specified resource.
    If the resource does not exist, this will return an empty set of
    permissions, not a NOT_FOUND error.

    Note: This operation is designed to be used for building permission-aware
    UIs and command-line tools, not for authorization checking. This operation
    may "fail open" without warning.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-pub-sub-middleware.png
  humanURL: https://cloud.google.com/pubsub/docs/
  baseURL: ://pubsub.googleapis.com////v1/{resource}:testIamPermissions
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-pub-sub/v1resourcetestiampermissions-post-openapi.md
- name: Google Cloud Pub/Sub API
  x-api-slug: google-cloud-pubsub-api
  description: Google Cloud Pub/Sub is a fully-managed real-time messaging service
    that allows you to send and receive messages between independent applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-pub-sub-middleware.png
  humanURL: https://cloud.google.com/pubsub/docs/
  baseURL: ://pubsub.googleapis.com//
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-pub-sub/openapi.md
x-common:
- type: x-change-log
  url: https://cloud.google.com/pubsub/docs/release-notes
- type: x-code
  url: https://cloud.google.com/pubsub/docs/reference/libraries
- type: x-faq
  url: https://cloud.google.com/pubsub/docs/faq
- type: x-getting-started
  url: https://cloud.google.com/pubsub/docs/quickstarts
- type: x-guides
  url: https://cloud.google.com/pubsub/docs/how-to
- type: x-issues
  url: https://issuetracker.google.com/issues?q=componentid:187173%20status:open
- type: x-pricing
  url: https://cloud.google.com/pubsub/pricing
- type: x-rate-limits
  url: https://cloud.google.com/pubsub/quotas
- type: x-service-level-agreement
  url: https://cloud.google.com/pubsub/sla
- type: x-support
  url: https://cloud.google.com/pubsub/docs/support
- type: x-website
  url: https://cloud.google.com/pubsub/docs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---