---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Get Context Keys For Principal Policy
  version: 1.0.0
  description: |-
    Gets a list of all of the context keys referenced in all of the IAM policies attached
          to the specified IAM entity.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddClientIDToOpenIDConnectProvider:
    get:
      summary: Add Client I D To Open I D Connect Provider
      description: |-
        Adds a new client ID (also known as audience) to the list of client IDs already
              registered for the specified IAM OpenID Connect (OIDC) provider resource.
      operationId: addClientIDToOpenIDConnectProvider
      x-api-path-slug: actionaddclientidtoopenidconnectprovider-get
      parameters:
      - in: query
        name: ClientID
        description: The client ID (also known as audience) to add to the IAM OpenID
          Connect provider      resource
        type: string
      - in: query
        name: OpenIDConnectProviderArn
        description: The Amazon Resource Name (ARN) of the IAM OpenID Connect (OIDC)
          provider resource to      add the client ID to
        type: string
      responses:
        200:
          description: OK
      tags:
      - OpenID Connect Providers
  /?Action=AddRoleToInstanceProfile:
    get:
      summary: Add Role To Instance Profile
      description: Adds the specified IAM role to the specified instance profile.
      operationId: addRoleToInstanceProfile
      x-api-path-slug: actionaddroletoinstanceprofile-get
      parameters:
      - in: query
        name: InstanceProfileName
        description: The name of the instance profile to update
        type: string
      - in: query
        name: RoleName
        description: The name of the role to add
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Instance
  /?Action=AttachGroupPolicy:
    get:
      summary: Attach Group Policy
      description: Attaches the specified managed policy to the specified IAM group.
      operationId: attachGroupPolicy
      x-api-path-slug: actionattachgrouppolicy-get
      parameters:
      - in: query
        name: GroupName
        description: The name (friendly name, not ARN) of the group to attach the
          policy to
        type: string
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          attach
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group Policies
  /?Action=AttachRolePolicy:
    get:
      summary: Attach Role Policy
      description: Attaches the specified managed policy to the specified IAM role.
      operationId: attachRolePolicy
      x-api-path-slug: actionattachrolepolicy-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          attach
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) of the role to attach the policy
          to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=ChangePassword:
    get:
      summary: Change Password
      description: Changes the password of the IAM user who is calling this action.
      operationId: changePassword
      x-api-path-slug: actionchangepassword-get
      parameters:
      - in: query
        name: NewPassword
        description: The new password
        type: string
      - in: query
        name: OldPassword
        description: The IAM users current password
        type: string
      responses:
        200:
          description: OK
      tags:
      - Passwords
  /?Action=CreateOpenIDConnectProvider:
    get:
      summary: Create Open I D Connect Provider
      description: Creates an IAM entity to describe an identity provider (IdP) that
        supports.
      operationId: createOpenIDConnectProvider
      x-api-path-slug: actioncreateopenidconnectprovider-get
      parameters:
      - in: query
        name: ClientIDList.member.N
        description: A list of client IDs (also known as audiences)
        type: string
      - in: query
        name: ThumbprintList.member.N
        description: A list of server certificate thumbprints for the OpenID Connect
          (OIDC) identity      providers server certificate(s)
        type: string
      - in: query
        name: Url
        description: The URL of the identity provider
        type: string
      responses:
        200:
          description: OK
      tags:
      - OpenID Connect Providers
  /?Action=CreateSAMLProvider:
    get:
      summary: Create S A M L Provider
      description: |-
        Creates an IAM resource that describes an identity provider (IdP) that supports SAML
              2.
      operationId: createSAMLProvider
      x-api-path-slug: actioncreatesamlprovider-get
      parameters:
      - in: query
        name: Name
        description: The name of the provider to create
        type: string
      - in: query
        name: SAMLMetadataDocument
        description: An XML document generated by an identity provider (IdP) that
          supports SAML 2
        type: string
      responses:
        200:
          description: OK
      tags:
      - SAML Providers
  /?Action=CreateUser:
    get:
      summary: Create User
      description: Creates a new IAM user for your AWS account.
      operationId: createUser
      x-api-path-slug: actioncreateuser-get
      parameters:
      - in: query
        name: Path
        description: The path for the user name
        type: string
      - in: query
        name: UserName
        description: The name of the user to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=DeleteAccessKey:
    get:
      summary: Delete Access Key
      description: Deletes the access key pair associated with the specified IAM user.
      operationId: deleteAccessKey
      x-api-path-slug: actiondeleteaccesskey-get
      parameters:
      - in: query
        name: AccessKeyId
        description: The access key ID for the access key ID and secret access key
          you want to      delete
        type: string
      - in: query
        name: UserName
        description: The name of the user whose access key pair you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Access Keys
  /?Action=DeleteGroup:
    get:
      summary: Delete Group
      description: Deletes the specified IAM group.
      operationId: deleteGroup
      x-api-path-slug: actiondeletegroup-get
      parameters:
      - in: query
        name: GroupName
        description: The name of the IAM group to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Groups
  /?Action=DeleteGroupPolicy:
    get:
      summary: Delete Group Policy
      description: |-
        Deletes the specified inline policy that is embedded in the specified IAM
              group.
      operationId: deleteGroupPolicy
      x-api-path-slug: actiondeletegrouppolicy-get
      parameters:
      - in: query
        name: GroupName
        description: The name (friendly name, not ARN) identifying the group that
          the policy is embedded      in
        type: string
      - in: query
        name: PolicyName
        description: The name identifying the policy document to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group Policies
  /?Action=DeleteLoginProfile:
    get:
      summary: Delete Login Profile
      description: |-
        Deletes the password for the specified IAM user, which terminates the user's ability
              to access AWS services through the AWS Management Console.
      operationId: deleteLoginProfile
      x-api-path-slug: actiondeleteloginprofile-get
      parameters:
      - in: query
        name: UserName
        description: The name of the user whose password you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Login Profiles
  /?Action=DeleteOpenIDConnectProvider:
    get:
      summary: Delete Open I D Connect Provider
      description: Deletes an OpenID Connect identity provider (IdP) resource object
        in IAM.
      operationId: deleteOpenIDConnectProvider
      x-api-path-slug: actiondeleteopenidconnectprovider-get
      parameters:
      - in: query
        name: OpenIDConnectProviderArn
        description: The Amazon Resource Name (ARN) of the IAM OpenID Connect provider
          resource object to      delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - OpenID Connect Providers
  /?Action=DeleteRolePolicy:
    get:
      summary: Delete Role Policy
      description: |-
        Deletes the specified inline policy that is embedded in the specified IAM
              role.
      operationId: deleteRolePolicy
      x-api-path-slug: actiondeleterolepolicy-get
      parameters:
      - in: query
        name: PolicyName
        description: The name of the inline policy to delete from the specified IAM
          role
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) identifying the role that the
          policy is embedded      in
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=DeleteSAMLProvider:
    get:
      summary: Delete S A M L Provider
      description: Deletes a SAML provider resource in IAM.
      operationId: deleteSAMLProvider
      x-api-path-slug: actiondeletesamlprovider-get
      parameters:
      - in: query
        name: SAMLProviderArn
        description: The Amazon Resource Name (ARN) of the SAML provider to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - SAML Providers
  /?Action=DeleteSigningCertificate:
    get:
      summary: Delete Signing Certificate
      description: Deletes a signing certificate associated with the specified IAM
        user.
      operationId: deleteSigningCertificate
      x-api-path-slug: actiondeletesigningcertificate-get
      parameters:
      - in: query
        name: CertificateId
        description: The ID of the signing certificate to delete
        type: string
      - in: query
        name: UserName
        description: The name of the user the signing certificate belongs to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Signing Certificates
  /?Action=DeleteUser:
    get:
      summary: Delete User
      description: Deletes the specified IAM user.
      operationId: deleteUser
      x-api-path-slug: actiondeleteuser-get
      parameters:
      - in: query
        name: UserName
        description: The name of the user to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=DeleteUserPolicy:
    get:
      summary: Delete User Policy
      description: |-
        Deletes the specified inline policy that is embedded in the specified IAM
              user.
      operationId: deleteUserPolicy
      x-api-path-slug: actiondeleteuserpolicy-get
      parameters:
      - in: query
        name: PolicyName
        description: The name identifying the policy document to delete
        type: string
      - in: query
        name: UserName
        description: The name (friendly name, not ARN) identifying the user that the
          policy is embedded      in
        type: string
      responses:
        200:
          description: OK
      tags:
      - User Policies
  /?Action=DetachGroupPolicy:
    get:
      summary: Detach Group Policy
      description: Removes the specified managed policy from the specified IAM group.
      operationId: detachGroupPolicy
      x-api-path-slug: actiondetachgrouppolicy-get
      parameters:
      - in: query
        name: GroupName
        description: The name (friendly name, not ARN) of the IAM group to detach
          the policy      from
        type: string
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          detach
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group Policies
  /?Action=EnableMFADevice:
    get:
      summary: Enable M F A Device
      description: Enables the specified MFA device and associates it with the specified
        IAM user.
      operationId: enableMFADevice
      x-api-path-slug: actionenablemfadevice-get
      parameters:
      - in: query
        name: AuthenticationCode1
        description: An authentication code emitted by the device
        type: string
      - in: query
        name: AuthenticationCode2
        description: A subsequent authentication code emitted by the device
        type: string
      - in: query
        name: SerialNumber
        description: The serial number that uniquely identifies the MFA device
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user for whom you want to enable the MFA
          device
        type: string
      responses:
        200:
          description: OK
      tags:
      - MFA Devices
  /?Action=GetAccountAuthorizationDetails:
    get:
      summary: Get Account Authorization Details
      description: |-
        Retrieves information about all IAM users, groups, roles, and policies in your AWS
              account, including their relationships to one another.
      operationId: getAccountAuthorizationDetails
      x-api-path-slug: actiongetaccountauthorizationdetails-get
      parameters:
      - in: query
        name: Filter.member.N
        description: A list of entity types used to filter the results
        type: string
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /?Action=GetAccountSummary:
    get:
      summary: Get Account Summary
      description: |-
        Retrieves information about IAM entity usage and IAM quotas in the AWS
              account.
      operationId: getAccountSummary
      x-api-path-slug: actiongetaccountsummary-get
      parameters:
      - in: query
        name: |-
          SummaryMap
                      , SummaryMap.entry.N.key (key), SummaryMapentry.N.value (value)
        description: A set of key value pairs containing information about IAM entity
          usage and IAM      quotas
        type: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /?Action=GetContextKeysForPrincipalPolicy:
    get:
      summary: Get Context Keys For Principal Policy
      description: |-
        Gets a list of all of the context keys referenced in all of the IAM policies attached
              to the specified IAM entity.
      operationId: getContextKeysForPrincipalPolicy
      x-api-path-slug: actiongetcontextkeysforprincipalpolicy-get
      parameters:
      - in: query
        name: PolicyInputList.member.N
        description: An optional list of additional policies for which you want the
          list of context keys      that are referenced
        type: string
      - in: query
        name: PolicySourceArn
        description: The ARN of a user, group, or role whose policies contain the
          context keys that you want      listed
        type: string
      responses:
        200:
          description: OK
      tags:
      - Context Keys For Principal Policies
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