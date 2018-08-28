swagger: "2.0"
x-collection-name: Google Genomics
x-complete: 1
info:
  title: Genomics
  description: upload-process-query-and-search-genomics-data-in-the-cloud-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: genomics.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{resource}:getIamPolicy:
    post:
      summary: Get IAM Policy
      description: |-
        Gets the access control policy for the dataset. This is empty if the
        policy or resource does not exist.

        See <a href="/iam/docs/managing-policies#getting_a_policy">Getting a
        Policy</a> for more information.

        For the definitions of datasets and other genomics resources, see
        [Fundamentals of Google
        Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)
      operationId: genomics.datasets.getIamPolicy
      x-api-path-slug: v1resourcegetiampolicy-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which policy is being specified'
      responses:
        200:
          description: OK
      tags:
      - IAM
  /v1/{resource}:setIamPolicy:
    post:
      summary: Set IAM Policy
      description: |-
        Sets the access control policy on the specified dataset. Replaces any
        existing policy.

        For the definitions of datasets and other genomics resources, see
        [Fundamentals of Google
        Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)

        See <a href="/iam/docs/managing-policies#setting_a_policy">Setting a
        Policy</a> for more information.
      operationId: genomics.datasets.setIamPolicy
      x-api-path-slug: v1resourcesetiampolicy-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which policy is being specified'
      responses:
        200:
          description: OK
      tags:
      - IAM
  /v1/{resource}:testIamPermissions:
    post:
      summary: Test IAM Permissions
      description: |-
        Returns permissions that a caller has on the specified resource.
        See <a href="/iam/docs/managing-policies#testing_permissions">Testing
        Permissions</a> for more information.

        For the definitions of datasets and other genomics resources, see
        [Fundamentals of Google
        Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)
      operationId: genomics.datasets.testIamPermissions
      x-api-path-slug: v1resourcetestiampermissions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which policy is being specified'
      responses:
        200:
          description: OK
      tags:
      - IAM