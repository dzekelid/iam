---
name: Google Cloud Storage
x-slug: google-cloud-storage
description: Google Cloud Storage is unified object storage for developers and enterprises,
  from live data serving to data analytics/ML to data archiving. Google Cloud Storage
  allows world-wide storage and retrieval of any amount of data at any time. You can
  use Google Cloud Storage for a range of scenarios including serving website content,
  storing data for archival and disaster recovery, or distributing large data objects
  to users via direct download.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
x-kinRank: "9"
x-alexaRank: "0"
tags: IAM
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Storage Get Bucket IAM
  x-api-slug: google-cloud-storage
  description: Returns an IAM policy for the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https://///b/{bucket}/iam
  tags: Bucket IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/bbucketiam-get-openapi.md
- name: Google Cloud Storage Update Bucket IAM
  x-api-slug: google-cloud-storage
  description: Updates an IAM policy for the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https://///b/{bucket}/iam
  tags: Bucket IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/bbucketiam-put-openapi.md
- name: Google Cloud Storage Test Bucket IAM Permissions
  x-api-slug: google-cloud-storage
  description: Tests a set of permissions on the given bucket to see which, if any,
    are held by the caller.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https://///b/{bucket}/iam/testPermissions
  tags: Bucket IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/bbucketiamtestpermissions-get-openapi.md
- name: Google Cloud Storage Get Object IAM
  x-api-slug: google-cloud-storage
  description: Returns an IAM policy for the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https://///b/{bucket}/o/{object}/iam
  tags: Object IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/bbucketoobjectiam-get-openapi.md
- name: Google Cloud Storage Update Object IAM
  x-api-slug: google-cloud-storage
  description: Updates an IAM policy for the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https://///b/{bucket}/o/{object}/iam
  tags: Object IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/bbucketoobjectiam-put-openapi.md
- name: Google Cloud Storage Test Object IAM Permissions
  x-api-slug: google-cloud-storage
  description: Tests a set of permissions on the given object to see which, if any,
    are held by the caller.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https://///b/{bucket}/o/{object}/iam/testPermissions
  tags: Object IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/bbucketoobjectiamtestpermissions-get-openapi.md
- name: Google Cloud Storage
  x-api-slug: google-cloud-storage
  description: Google Cloud Storage is unified object storage for developers and enterprises,
    from live data serving to data analytics/ML to data archiving. Google Cloud Storage
    allows world-wide storage and retrieval of any amount of data at any time. You
    can use Google Cloud Storage for a range of scenarios including serving website
    content, storing data for archival and disaster recovery, or distributing large
    data objects to users via direct download.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/iam/master/_listings/google-cloud-storage/openapi.md
x-common:
- type: x-authentication
  url: https://cloud.google.com/storage/docs/authentication
- type: x-best-practices
  url: https://cloud.google.com/storage/docs/best-practices
- type: x-change-log
  url: https://cloud.google.com/storage/release-notes
- type: x-code
  url: https://cloud.google.com/storage/docs/reference/libraries
- type: x-concepts
  url: https://cloud.google.com/storage/docs/concepts
- type: x-dmca-policy
  url: https://cloud.google.com/storage/docs/dmca
- type: x-faq
  url: https://cloud.google.com/storage/docs/faq
- type: x-getting-started
  url: https://cloud.google.com/storage/docs/quickstarts
- type: x-guides
  url: https://cloud.google.com/storage/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/storage/pricing
- type: x-service-level-agreements
  url: https://cloud.google.com/storage/sla
- type: x-support
  url: https://cloud.google.com/storage/docs/resources-support
- type: x-tutorials
  url: https://cloud.google.com/storage/docs/tutorials
- type: x-website
  url: https://cloud.google.com/storage/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---