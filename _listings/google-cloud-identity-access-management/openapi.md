swagger: "2.0"
x-collection-name: Google Cloud Identity Access Management
x-complete: 1
info:
  title: Google Identity and Access Management (IAM)
  description: manages-identity-and-access-control-for-google-cloud-platform-resources-including-the-creation-of-service-accounts-which-you-can-use-to-authenticate-to-google-and-make-api-calls-
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