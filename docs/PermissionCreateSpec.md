# PermissionCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdUserOrGroupId** | **string** | The AD User or Group SID for this permission. | 
**FederationAccessGroupId** | Pointer to **string** | The federation access group ID for this permission. | [optional] 
**LocalAccessGroupId** | Pointer to **string** | The local access group ID for this permission. | [optional] 
**RoleId** | **string** | Role ID for this permission. | 

## Methods

### NewPermissionCreateSpec

`func NewPermissionCreateSpec(adUserOrGroupId string, roleId string, ) *PermissionCreateSpec`

NewPermissionCreateSpec instantiates a new PermissionCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermissionCreateSpecWithDefaults

`func NewPermissionCreateSpecWithDefaults() *PermissionCreateSpec`

NewPermissionCreateSpecWithDefaults instantiates a new PermissionCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdUserOrGroupId

`func (o *PermissionCreateSpec) GetAdUserOrGroupId() string`

GetAdUserOrGroupId returns the AdUserOrGroupId field if non-nil, zero value otherwise.

### GetAdUserOrGroupIdOk

`func (o *PermissionCreateSpec) GetAdUserOrGroupIdOk() (*string, bool)`

GetAdUserOrGroupIdOk returns a tuple with the AdUserOrGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdUserOrGroupId

`func (o *PermissionCreateSpec) SetAdUserOrGroupId(v string)`

SetAdUserOrGroupId sets AdUserOrGroupId field to given value.


### GetFederationAccessGroupId

`func (o *PermissionCreateSpec) GetFederationAccessGroupId() string`

GetFederationAccessGroupId returns the FederationAccessGroupId field if non-nil, zero value otherwise.

### GetFederationAccessGroupIdOk

`func (o *PermissionCreateSpec) GetFederationAccessGroupIdOk() (*string, bool)`

GetFederationAccessGroupIdOk returns a tuple with the FederationAccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederationAccessGroupId

`func (o *PermissionCreateSpec) SetFederationAccessGroupId(v string)`

SetFederationAccessGroupId sets FederationAccessGroupId field to given value.

### HasFederationAccessGroupId

`func (o *PermissionCreateSpec) HasFederationAccessGroupId() bool`

HasFederationAccessGroupId returns a boolean if a field has been set.

### GetLocalAccessGroupId

`func (o *PermissionCreateSpec) GetLocalAccessGroupId() string`

GetLocalAccessGroupId returns the LocalAccessGroupId field if non-nil, zero value otherwise.

### GetLocalAccessGroupIdOk

`func (o *PermissionCreateSpec) GetLocalAccessGroupIdOk() (*string, bool)`

GetLocalAccessGroupIdOk returns a tuple with the LocalAccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAccessGroupId

`func (o *PermissionCreateSpec) SetLocalAccessGroupId(v string)`

SetLocalAccessGroupId sets LocalAccessGroupId field to given value.

### HasLocalAccessGroupId

`func (o *PermissionCreateSpec) HasLocalAccessGroupId() bool`

HasLocalAccessGroupId returns a boolean if a field has been set.

### GetRoleId

`func (o *PermissionCreateSpec) GetRoleId() string`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *PermissionCreateSpec) GetRoleIdOk() (*string, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *PermissionCreateSpec) SetRoleId(v string)`

SetRoleId sets RoleId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


