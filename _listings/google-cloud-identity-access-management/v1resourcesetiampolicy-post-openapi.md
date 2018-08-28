---
swagger: "2.0"
x-collection-name: Google Cloud Identity Access Management
x-complete: 0
info:
  title: Google Cloud Identity & Access Management API Set IAM Access Control Policy
  description: |-
    Sets the IAM access control policy for a
    ServiceAccount.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: iam.googleapis.com
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
      summary: Return IAM Access Control Policy
      description: |-
        Returns the IAM access control policy for a
        ServiceAccount.
      operationId: iam.projects.serviceAccounts.getIamPolicy
      x-api-path-slug: v1resourcegetiampolicy-post
      parameters:
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which the policy is being requested'
      responses:
        200:
          description: OK
      tags:
      - IAM
  /v1/{resource}:setIamPolicy:
    post:
      summary: Set IAM Access Control Policy
      description: |-
        Sets the IAM access control policy for a
        ServiceAccount.
      operationId: iam.projects.serviceAccounts.setIamPolicy
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
      - IAM
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