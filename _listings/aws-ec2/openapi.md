swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
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
  /?Action=ModifyIdentityIdFormat:
    get:
      summary: Modify Identity Id Format
      description: |-
        Modifies the ID format of a resource for a specified IAM user, IAM role, or the root
              user for an account; or all IAM users, IAM roles, and the root user for an account.
      operationId: modifyidentityidformat
      x-api-path-slug: actionmodifyidentityidformat-get
      parameters:
      - in: query
        name: Resource
        description: 'The type of resource: instance | reservation |        snapshot
          | volume'
        type: string
      - in: query
        name: UseLongIds
        description: Indicate whether the resource should use longer IDs (17-character
          IDs)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Format