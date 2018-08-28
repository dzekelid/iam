swagger: "2.0"
x-collection-name: Google Cloud Spanner
x-complete: 1
info:
  title: Cloud Spanner
  description: cloud-spanner-is-a-managed-missioncritical-globally-consistent-and-scalable-relational-database-service-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: spanner.googleapis.com
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
        Gets the access control policy for a database resource. Returns an empty
        policy if a database exists but does not have a policy set.

        Authorization requires `spanner.databases.getIamPolicy` permission on
        resource.
      operationId: spanner.projects.instances.databases.getIamPolicy
      x-api-path-slug: v1resourcegetiampolicy-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The Cloud Spanner resource for which the policy is
          being retrieved'
      responses:
        200:
          description: OK
      tags:
      - IAM
  /v1/{resource}:setIamPolicy:
    post:
      summary: Set IAM Policy
      description: |-
        Sets the access control policy on a database resource. Replaces any
        existing policy.

        Authorization requires `spanner.databases.setIamPolicy` permission on
        resource.
      operationId: spanner.projects.instances.databases.setIamPolicy
      x-api-path-slug: v1resourcesetiampolicy-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The Cloud Spanner resource for which the policy is
          being set'
      responses:
        200:
          description: OK
      tags:
      - IAM
  /v1/{resource}:testIamPermissions:
    post:
      summary: Test IAM Permissions
      description: |-
        Returns permissions that the caller has on the specified database resource.

        Attempting this RPC on a non-existent Cloud Spanner database will result in
        a NOT_FOUND error if the user has `spanner.databases.list` permission on
        the containing Cloud Spanner instance. Otherwise returns an empty set of
        permissions.
      operationId: spanner.projects.instances.databases.testIamPermissions
      x-api-path-slug: v1resourcetestiampermissions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The Cloud Spanner resource for which permissions are
          being tested'
      responses:
        200:
          description: OK
      tags:
      - IAM