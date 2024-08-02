# RoleCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | Role description. | [optional] 
**Name** | **string** | Role name. This property must contain only alphanumerics, underscores, and dashes. | 
**Privileges** | **[]string** | Privileges for this role. When being created or updated, input non-selectable privileges are ignored.  | 

## Methods

### NewRoleCreateSpec

`func NewRoleCreateSpec(name string, privileges []string, ) *RoleCreateSpec`

NewRoleCreateSpec instantiates a new RoleCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleCreateSpecWithDefaults

`func NewRoleCreateSpecWithDefaults() *RoleCreateSpec`

NewRoleCreateSpecWithDefaults instantiates a new RoleCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *RoleCreateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RoleCreateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RoleCreateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RoleCreateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetName

`func (o *RoleCreateSpec) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoleCreateSpec) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoleCreateSpec) SetName(v string)`

SetName sets Name field to given value.


### GetPrivileges

`func (o *RoleCreateSpec) GetPrivileges() []string`

GetPrivileges returns the Privileges field if non-nil, zero value otherwise.

### GetPrivilegesOk

`func (o *RoleCreateSpec) GetPrivilegesOk() (*[]string, bool)`

GetPrivilegesOk returns a tuple with the Privileges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivileges

`func (o *RoleCreateSpec) SetPrivileges(v []string)`

SetPrivileges sets Privileges field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


