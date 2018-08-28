---
swagger: "2.0"
x-collection-name: AWS Security Token Service
x-complete: 0
info:
  title: AWS Security Token Service API Get Session Token
  version: 1.0.0
  description: Returns a set of temporary credentials for an AWS account or IAM user.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetCallerIdentity:
    get:
      summary: Get Caller Identity
      description: |-
        Returns details about the IAM identity whose credentials are used to call the
              API.
      operationId: getCallerIdentity
      x-api-path-slug: actiongetcalleridentity-get
      parameters:
      - in: query
        name: Account
        description: The AWS account ID number of the account that owns or contains
          the calling      entity
        type: string
      - in: query
        name: Arn
        description: The AWS ARN associated with the calling entity
        type: string
      - in: query
        name: UserId
        description: The unique identifier of the calling entity
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=GetSessionToken:
    get:
      summary: Get Session Token
      description: Returns a set of temporary credentials for an AWS account or IAM
        user.
      operationId: getSessionToken
      x-api-path-slug: actiongetsessiontoken-get
      parameters:
      - in: query
        name: DurationSeconds
        description: The duration, in seconds, that the credentials should remain
          valid
        type: string
      - in: query
        name: SerialNumber
        description: The identification number of the MFA device that is associated
          with the IAM user who      is making the GetSessionToken call
        type: string
      - in: query
        name: TokenCode
        description: The value provided by the MFA device, if MFA is required
        type: string
      responses:
        200:
          description: OK
      tags:
      - Session Token
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