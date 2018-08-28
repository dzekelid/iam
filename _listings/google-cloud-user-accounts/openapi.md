swagger: "2.0"
x-collection-name: Google Cloud User Accounts
x-complete: 1
info:
  title: Cloud User Accounts
  description: creates-and-manages-users-and-groups-for-accessing-google-compute-engine-virtual-machines-
  contact:
    name: Google
    url: https://google.com
  version: vm_alpha
host: www.googleapis.com
basePath: /clouduseraccounts/vm_alpha/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/global/groups/{resource}/getIamPolicy:
    get:
      summary: Get IAM Policy
      description: Gets the access control policy for a resource. May be empty if
        no such policy or resource exists.
      operationId: clouduseraccounts.groups.getIamPolicy
      x-api-path-slug: projectglobalgroupsresourcegetiampolicy-get
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: resource
        description: Name of the resource for this request
      responses:
        200:
          description: OK
      tags:
      - IAM
  /{project}/global/groups/{resource}/setIamPolicy:
    post:
      summary: Set IAM Policy
      description: Sets the access control policy on the specified resource. Replaces
        any existing policy.
      operationId: clouduseraccounts.groups.setIamPolicy
      x-api-path-slug: projectglobalgroupsresourcesetiampolicy-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: resource
        description: Name of the resource for this request
      responses:
        200:
          description: OK
      tags:
      - IAM
  /{project}/global/groups/{resource}/testIamPermissions:
    post:
      summary: Test IAM Permissions
      description: Returns permissions that a caller has on the specified resource.
      operationId: clouduseraccounts.groups.testIamPermissions
      x-api-path-slug: projectglobalgroupsresourcetestiampermissions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: resource
        description: Name of the resource for this request
      responses:
        200:
          description: OK
      tags:
      - IAM