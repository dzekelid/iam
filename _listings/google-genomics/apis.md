---
name: Google Genomics
x-slug: google-genomics
description: Google Genomics helps the life science community organize the world&rsquo;s
  genomic information and make it accessible and useful. Big genomic data is here
  today, with petabytes rapidly growing toward exabytes. Through our extensions to
  Google Cloud Platform, you can apply the same technologies that power Google Search
  and Maps to securely store, process, explore, and share large, complex datasets.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-genomics/apis.md
specificationVersion: "0.14"
apis:
- name: Google Genomics API Get IAM Policy
  x-api-slug: google-genomics-api
  description: |-
    Gets the access control policy for the dataset. This is empty if the
    policy or resource does not exist.

    See <a href="/iam/docs/managing-policies#getting_a_policy">Getting a
    Policy</a> for more information.

    For the definitions of datasets and other genomics resources, see
    [Fundamentals of Google
    Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
  humanURL: https://cloud.google.com/genomics/
  baseURL: ://genomics.googleapis.com////v1/{resource}:getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-genomics/v1resourcegetiampolicy-post-openapi.md
- name: Google Genomics API Set IAM Policy
  x-api-slug: google-genomics-api
  description: |-
    Sets the access control policy on the specified dataset. Replaces any
    existing policy.

    For the definitions of datasets and other genomics resources, see
    [Fundamentals of Google
    Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)

    See <a href="/iam/docs/managing-policies#setting_a_policy">Setting a
    Policy</a> for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
  humanURL: https://cloud.google.com/genomics/
  baseURL: ://genomics.googleapis.com////v1/{resource}:setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-genomics/v1resourcesetiampolicy-post-openapi.md
- name: Google Genomics API Test IAM Permissions
  x-api-slug: google-genomics-api
  description: |-
    Returns permissions that a caller has on the specified resource.
    See <a href="/iam/docs/managing-policies#testing_permissions">Testing
    Permissions</a> for more information.

    For the definitions of datasets and other genomics resources, see
    [Fundamentals of Google
    Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
  humanURL: https://cloud.google.com/genomics/
  baseURL: ://genomics.googleapis.com////v1/{resource}:testIamPermissions
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-genomics/v1resourcetestiampermissions-post-openapi.md
- name: Google Genomics API
  x-api-slug: google-genomics-api
  description: Google Genomics helps the life science community organize the world&rsquo;s
    genomic information and make it accessible and useful. Big genomic data is here
    today, with petabytes rapidly growing toward exabytes. Through our extensions
    to Google Cloud Platform, you can apply the same technologies that power Google
    Search and Maps to securely store, process, explore, and share large, complex
    datasets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
  humanURL: https://cloud.google.com/genomics/
  baseURL: ://genomics.googleapis.com//
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-genomics/openapi.md
x-common:
- type: x-documentation
  url: https://cloud.google.com/genomics/overview
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-genomics-discuss/join
- type: x-pricing
  url: https://cloud.google.com/genomics/pricing
- type: x-rate-limits
  url: https://cloud.google.com/genomics/quotas
- type: x-support
  url: https://cloud.google.com/genomics/support
- type: x-website
  url: https://cloud.google.com/genomics/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---