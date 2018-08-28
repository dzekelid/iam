swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 1
info:
  title: AWS EC2 Systems Manager API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeActivations:
    get:
      summary: Describe Activations
      description: |-
        Details about the activation, including: the date and time the activation was created,
           the expiration date, the IAM role assigned to the instances in the activation, and the number of
           instances activated by this registration.
      operationId: describeActivations
      x-api-path-slug: actiondescribeactivations-get
      parameters:
      - in: query
        name: Filters
        description: A filter to view information about your activations
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: A token to start the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activations
  /?Action=UpdateManagedInstanceRole:
    get:
      summary: Update Managed Instance Role
      description: |-
        Assigns or changes an Amazon Identity and Access Management (IAM) role to the managed
           instance.
      operationId: updateManagedInstanceRole
      x-api-path-slug: actionupdatemanagedinstancerole-get
      parameters:
      - in: query
        name: IamRole
        description: The IAM role you want to assign or change
        type: string
      - in: query
        name: InstanceId
        description: The ID of the managed instance where you want to update the role
        type: string
      responses:
        200:
          description: OK
      tags:
      - Managed
      - Instance
      - Role