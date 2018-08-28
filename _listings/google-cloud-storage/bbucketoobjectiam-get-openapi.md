---
swagger: "2.0"
x-collection-name: Google Cloud Storage
x-complete: 0
info:
  title: Google Cloud Storage Get Object IAM
  version: 1.0.0
  description: Returns an IAM policy for the specified object.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /b/{bucket}/iam:
    get:
      summary: Get Bucket IAM
      description: Returns an IAM policy for the specified bucket.
      operationId: storage.buckets.getIamPolicy
      x-api-path-slug: bbucketiam-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      responses:
        200:
          description: OK
      tags:
      - Bucket IAM
    put:
      summary: Update Bucket IAM
      description: Updates an IAM policy for the specified bucket.
      operationId: storage.buckets.setIamPolicy
      x-api-path-slug: bbucketiam-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      responses:
        200:
          description: OK
      tags:
      - Bucket IAM
  /b/{bucket}/iam/testPermissions:
    get:
      summary: Test Bucket IAM Permissions
      description: Tests a set of permissions on the given bucket to see which, if
        any, are held by the caller.
      operationId: storage.buckets.testIamPermissions
      x-api-path-slug: bbucketiamtestpermissions-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: query
        name: permissions
        description: Permissions to test
      responses:
        200:
          description: OK
      tags:
      - Bucket IAM
  /b/{bucket}/o/{object}/iam:
    get:
      summary: Get Object IAM
      description: Returns an IAM policy for the specified object.
      operationId: storage.objects.getIamPolicy
      x-api-path-slug: bbucketoobjectiam-get
      parameters:
      - in: path
        name: bucket
        description: Name of the bucket in which the object resides
      - in: query
        name: generation
        description: If present, selects a specific revision of this object (as opposed
          to the latest version, the default)
      - in: path
        name: object
        description: Name of the object
      responses:
        200:
          description: OK
      tags:
      - Object IAM
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---