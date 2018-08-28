---
swagger: "2.0"
x-collection-name: Google Cloud Key Management Service
x-complete: 1
info:
  title: Google Cloud Key Management Service (KMS)
  description: manages-encryption-for-your-cloud-services-the-same-way-you-do-onpremise--you-can-generate-use-rotate-and-destroy-aes256-encryption-keys-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudkms.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{resource}:getIamPolicy:
    get:
      summary: Get IAM Policy
      description: |-
        Gets the access control policy for a resource.
        Returns an empty policy if the resource exists and does not have a policy
        set.
      operationId: cloudkms.projects.locations.keyRings.cryptoKeys.getIamPolicy
      x-api-path-slug: v1resourcegetiampolicy-get
      parameters:
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which the policy is being requested'
      responses:
        200:
          description: OK
      tags:
      - IAM Policy
  /v1/{resource}:setIamPolicy:
    post:
      summary: Set IAM Policy
      description: |-
        Sets the access control policy on the specified resource. Replaces any
        existing policy.
      operationId: cloudkms.projects.locations.keyRings.cryptoKeys.setIamPolicy
      x-api-path-slug: v1resourcesetiampolicy-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which the policy is being specified'
      responses:
        200:
          description: OK
      tags:
      - IAM Policy
  /v1/{resource}:testIamPermissions:
    post:
      summary: Test IAM Permissions
      description: |-
        Returns permissions that a caller has on the specified resource.
        If the resource does not exist, this will return an empty set of
        permissions, not a NOT_FOUND error.

        Note: This operation is designed to be used for building permission-aware
        UIs and command-line tools, not for authorization checking. This operation
        may "fail open" without warning.
      operationId: cloudkms.projects.locations.keyRings.cryptoKeys.testIamPermissions
      x-api-path-slug: v1resourcetestiampermissions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which the policy detail is being
          requested'
      responses:
        200:
          description: OK
      tags:
      - IAM Permission
---