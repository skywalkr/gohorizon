# RoleInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppliesToFederationAccessGroup** | Pointer to **bool** | Specifies whether federated access group is applicable for this role. This will be true when the role contains atleast one of FEDEREATED_LDAP_MANAGE, FEDEREATED_LDAP_VIEW, FEDERATED_SESSIONS_MANAGE or FEDERATED_SESSIONS_VIEW privilege. | [optional] 
**AppliesToLocalAccessGroup** | Pointer to **bool** | Specifies whether local access group is applicable for this role. This will be true when the role contains atleast one inventory specific privilege. | [optional] 
**BuiltInRoleType** | Pointer to **string** | The role type. It will be null for custom roles. * ADMINISTRATOR: Role with full administrative rights. * ADMINISTRATOR_READ_ONLY: Role with full read-only administrative rights. * AGENT_REGISTRATION_ADMIN: Role with rights to register Agents. * GLOBAL_CONFIG_AND_POLICY_ADMIN: Role with rights for View Configuration settings and policies. * GLOBAL_CONFIG_AND_POLICY_ADMIN_READ_ONLY: Role with read-only rights for View Configuration settings and policies. * HELP_DESK_ADMIN: Role with rights for Help Desk portal management. * HELP_DESK_ADMIN_READ_ONLY: Role with read only rights for Help Desk portal management. * INVENTORY_ADMIN: Role with rights for inventory management. * INVENTORY_ADMIN_READ_ONLY: Role with read only rights for inventory management. * LOCAL_ADMIN: Local Pod Administration role with full administrative rights. * LOCAL_ADMIN_READ_ONLY: Local Pod Administration role with full read-only administrative rights. * UNKNOWN_ROLE: Unknown Role type. | [optional] 
**Description** | Pointer to **string** | Role description. | [optional] 
**Id** | Pointer to **string** | Unique ID representing this role. | [optional] 
**Name** | Pointer to **string** | Role name. | [optional] 
**PermissionIds** | Pointer to **[]string** | Administrative permissions (user/group and access group) for this role. | [optional] 
**Privileges** | Pointer to **[]string** | Privileges for this role. | [optional] 

## Methods

### NewRoleInfo

`func NewRoleInfo() *RoleInfo`

NewRoleInfo instantiates a new RoleInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleInfoWithDefaults

`func NewRoleInfoWithDefaults() *RoleInfo`

NewRoleInfoWithDefaults instantiates a new RoleInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppliesToFederationAccessGroup

`func (o *RoleInfo) GetAppliesToFederationAccessGroup() bool`

GetAppliesToFederationAccessGroup returns the AppliesToFederationAccessGroup field if non-nil, zero value otherwise.

### GetAppliesToFederationAccessGroupOk

`func (o *RoleInfo) GetAppliesToFederationAccessGroupOk() (*bool, bool)`

GetAppliesToFederationAccessGroupOk returns a tuple with the AppliesToFederationAccessGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppliesToFederationAccessGroup

`func (o *RoleInfo) SetAppliesToFederationAccessGroup(v bool)`

SetAppliesToFederationAccessGroup sets AppliesToFederationAccessGroup field to given value.

### HasAppliesToFederationAccessGroup

`func (o *RoleInfo) HasAppliesToFederationAccessGroup() bool`

HasAppliesToFederationAccessGroup returns a boolean if a field has been set.

### GetAppliesToLocalAccessGroup

`func (o *RoleInfo) GetAppliesToLocalAccessGroup() bool`

GetAppliesToLocalAccessGroup returns the AppliesToLocalAccessGroup field if non-nil, zero value otherwise.

### GetAppliesToLocalAccessGroupOk

`func (o *RoleInfo) GetAppliesToLocalAccessGroupOk() (*bool, bool)`

GetAppliesToLocalAccessGroupOk returns a tuple with the AppliesToLocalAccessGroup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppliesToLocalAccessGroup

`func (o *RoleInfo) SetAppliesToLocalAccessGroup(v bool)`

SetAppliesToLocalAccessGroup sets AppliesToLocalAccessGroup field to given value.

### HasAppliesToLocalAccessGroup

`func (o *RoleInfo) HasAppliesToLocalAccessGroup() bool`

HasAppliesToLocalAccessGroup returns a boolean if a field has been set.

### GetBuiltInRoleType

`func (o *RoleInfo) GetBuiltInRoleType() string`

GetBuiltInRoleType returns the BuiltInRoleType field if non-nil, zero value otherwise.

### GetBuiltInRoleTypeOk

`func (o *RoleInfo) GetBuiltInRoleTypeOk() (*string, bool)`

GetBuiltInRoleTypeOk returns a tuple with the BuiltInRoleType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuiltInRoleType

`func (o *RoleInfo) SetBuiltInRoleType(v string)`

SetBuiltInRoleType sets BuiltInRoleType field to given value.

### HasBuiltInRoleType

`func (o *RoleInfo) HasBuiltInRoleType() bool`

HasBuiltInRoleType returns a boolean if a field has been set.

### GetDescription

`func (o *RoleInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RoleInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RoleInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RoleInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *RoleInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RoleInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RoleInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *RoleInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *RoleInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoleInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoleInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RoleInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPermissionIds

`func (o *RoleInfo) GetPermissionIds() []string`

GetPermissionIds returns the PermissionIds field if non-nil, zero value otherwise.

### GetPermissionIdsOk

`func (o *RoleInfo) GetPermissionIdsOk() (*[]string, bool)`

GetPermissionIdsOk returns a tuple with the PermissionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionIds

`func (o *RoleInfo) SetPermissionIds(v []string)`

SetPermissionIds sets PermissionIds field to given value.

### HasPermissionIds

`func (o *RoleInfo) HasPermissionIds() bool`

HasPermissionIds returns a boolean if a field has been set.

### GetPrivileges

`func (o *RoleInfo) GetPrivileges() []string`

GetPrivileges returns the Privileges field if non-nil, zero value otherwise.

### GetPrivilegesOk

`func (o *RoleInfo) GetPrivilegesOk() (*[]string, bool)`

GetPrivilegesOk returns a tuple with the Privileges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivileges

`func (o *RoleInfo) SetPrivileges(v []string)`

SetPrivileges sets Privileges field to given value.

### HasPrivileges

`func (o *RoleInfo) HasPrivileges() bool`

HasPrivileges returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


