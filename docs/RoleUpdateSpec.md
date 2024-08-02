# RoleUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | Role description. | [optional] 
**Privileges** | **[]string** | Privileges for this role. When being created or updated, input non-selectable privileges are ignored.  | 

## Methods

### NewRoleUpdateSpec

`func NewRoleUpdateSpec(privileges []string, ) *RoleUpdateSpec`

NewRoleUpdateSpec instantiates a new RoleUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleUpdateSpecWithDefaults

`func NewRoleUpdateSpecWithDefaults() *RoleUpdateSpec`

NewRoleUpdateSpecWithDefaults instantiates a new RoleUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *RoleUpdateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RoleUpdateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RoleUpdateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RoleUpdateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPrivileges

`func (o *RoleUpdateSpec) GetPrivileges() []string`

GetPrivileges returns the Privileges field if non-nil, zero value otherwise.

### GetPrivilegesOk

`func (o *RoleUpdateSpec) GetPrivilegesOk() (*[]string, bool)`

GetPrivilegesOk returns a tuple with the Privileges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivileges

`func (o *RoleUpdateSpec) SetPrivileges(v []string)`

SetPrivileges sets Privileges field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


