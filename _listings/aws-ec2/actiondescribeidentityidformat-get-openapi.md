---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Describe Identity Id Format
  version: 1.0.0
  description: |-
    Describes the ID format settings for resources for the specified IAM user, IAM role, or root
          user.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeIdentityIdFormat:
    get:
      summary: Describe Identity Id Format
      description: |-
        Describes the ID format settings for resources for the specified IAM user, IAM role, or root
              user.
      operationId: describeidentityidformat
      x-api-path-slug: actiondescribeidentityidformat-get
      parameters:
      - in: query
        name: Resource
        description: 'The type of resource: instance | reservation |        snapshot
          | volume'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Format
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