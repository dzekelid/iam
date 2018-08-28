---
swagger: "2.0"
x-collection-name: AWS CodeDeploy
x-complete: 0
info:
  title: AWS CodeDeploy API List Deployment Configs
  version: 1.0.0
  description: |-
    Lists the deployment configurations with the applicable IAM user or AWS
                account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListApplications:
    get:
      summary: List Applications
      description: |-
        Lists the applications registered with the applicable IAM user or AWS
                    account.
      operationId: listApplications
      x-api-path-slug: actionlistapplications-get
      parameters:
      - in: query
        name: nextToken
        description: An identifier returned from the previous list applications call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=ListDeploymentConfigs:
    get:
      summary: List Deployment Configs
      description: |-
        Lists the deployment configurations with the applicable IAM user or AWS
                    account.
      operationId: listDeploymentConfigs
      x-api-path-slug: actionlistdeploymentconfigs-get
      parameters:
      - in: query
        name: nextToken
        description: An identifier returned from the previous list deployment configurations
          call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployments
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