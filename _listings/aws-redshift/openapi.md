---
swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 1
info:
  title: AWS Redshift API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ModifyClusterIamRoles:
    get:
      summary: Modify Cluster Iam Roles
      description: |-
        Modifies the list of AWS Identity and Access Management (IAM) roles that can be
                    used by the cluster to access other AWS services.
      operationId: modifyClusterIamRoles
      x-api-path-slug: actionmodifyclusteriamroles-get
      parameters:
      - in: query
        name: AddIamRoles.IamRoleArn.N
        description: Zero or more IAM roles to associate with the cluster
        type: string
      - in: query
        name: ClusterIdentifier
        description: The unique identifier of the cluster for which you want to associate
          or            disassociate IAM roles
        type: string
      - in: query
        name: RemoveIamRoles.IamRoleArn.N
        description: Zero or more IAM roles in ARN format to disassociate from the
          cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster IAM Roles
---