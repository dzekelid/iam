---
swagger: "2.0"
x-collection-name: Google Cloud Resource Manager
x-complete: 0
info:
  title: Google Cloud Resource Manager API Get IAM Policy
  description: |-
    Returns the IAM access control policy for the specified Project.
    Permission is denied if the policy or the resource does not exist.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudresourcemanager.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/projects/{resource}:getIamPolicy:
    post:
      summary: Get IAM Policy
      description: |-
        Returns the IAM access control policy for the specified Project.
        Permission is denied if the policy or the resource does not exist.
      operationId: cloudresourcemanager.projects.getIamPolicy
      x-api-path-slug: v1projectsresourcegetiampolicy-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which the policy is being requested'
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