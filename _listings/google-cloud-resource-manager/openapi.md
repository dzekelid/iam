---
swagger: "2.0"
x-collection-name: Google Cloud Resource Manager
x-complete: 1
info:
  title: Google Cloud Resource Manager
  description: the-google-cloud-resource-manager-api-provides-methods-for-creating-reading-and-updating-project-metadata-
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
  /v1/projects/{resource}:setIamPolicy:
    post:
      summary: Set IAM Policy
      description: |-
        Sets the IAM access control policy for the specified Project. Replaces
        any existing policy.

        The following constraints apply when using `setIamPolicy()`:

        + Project does not support `allUsers` and `allAuthenticatedUsers` as
        `members` in a `Binding` of a `Policy`.

        + The owner role can be granted only to `user` and `serviceAccount`.

        + Service accounts can be made owners of a project directly
        without any restrictions. However, to be added as an owner, a user must be
        invited via Cloud Platform console and must accept the invitation.

        + A user cannot be granted the owner role using `setIamPolicy()`. The user
        must be granted the owner role using the Cloud Platform Console and must
        explicitly accept the invitation.

        + Invitations to grant the owner role cannot be sent using
        `setIamPolicy()`;
        they must be sent only using the Cloud Platform Console.

        + Membership changes that leave the project without any owners that have
        accepted the Terms of Service (ToS) will be rejected.

        + There must be at least one owner who has accepted the Terms of
        Service (ToS) agreement in the policy. Calling `setIamPolicy()` to
        to remove the last ToS-accepted owner from the policy will fail. This
        restriction also applies to legacy projects that no longer have owners
        who have accepted the ToS. Edits to IAM policies will be rejected until
        the lack of a ToS-accepting owner is rectified.

        + Calling this method requires enabling the App Engine Admin API.

        Note: Removing service accounts from policies or changing their roles
        can render services completely inoperable. It is important to understand
        how the service account is being used before removing or updating its
        roles.
      operationId: cloudresourcemanager.projects.setIamPolicy
      x-api-path-slug: v1projectsresourcesetiampolicy-post
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
  /v1/projects/{resource}:testIamPermissions:
    post:
      summary: Test IAM Policy
      description: Returns permissions that a caller has on the specified Project.
      operationId: cloudresourcemanager.projects.testIamPermissions
      x-api-path-slug: v1projectsresourcetestiampermissions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which the policy detail is being
          requested'
      responses:
        200:
          description: OK
      tags:
      - IAM
---