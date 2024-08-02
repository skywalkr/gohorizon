# PermissionInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdUserOrGroupId** | Pointer to **string** | The AD User or Group SID for this permission. | [optional] 
**FederationAccessGroupId** | Pointer to **string** | The federation access group ID for this permission. | [optional] 
**Id** | Pointer to **string** | Unique ID representing this permission. | [optional] 
**LocalAccessGroupId** | Pointer to **string** | The local access group ID for this permission. | [optional] 
**RoleId** | Pointer to **string** | Role ID for this permission. | [optional] 

## Methods

### NewPermissionInfo

`func NewPermissionInfo() *PermissionInfo`

NewPermissionInfo instantiates a new PermissionInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermissionInfoWithDefaults

`func NewPermissionInfoWithDefaults() *PermissionInfo`

NewPermissionInfoWithDefaults instantiates a new PermissionInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdUserOrGroupId

`func (o *PermissionInfo) GetAdUserOrGroupId() string`

GetAdUserOrGroupId returns the AdUserOrGroupId field if non-nil, zero value otherwise.

### GetAdUserOrGroupIdOk

`func (o *PermissionInfo) GetAdUserOrGroupIdOk() (*string, bool)`

GetAdUserOrGroupIdOk returns a tuple with the AdUserOrGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdUserOrGroupId

`func (o *PermissionInfo) SetAdUserOrGroupId(v string)`

SetAdUserOrGroupId sets AdUserOrGroupId field to given value.

### HasAdUserOrGroupId

`func (o *PermissionInfo) HasAdUserOrGroupId() bool`

HasAdUserOrGroupId returns a boolean if a field has been set.

### GetFederationAccessGroupId

`func (o *PermissionInfo) GetFederationAccessGroupId() string`

GetFederationAccessGroupId returns the FederationAccessGroupId field if non-nil, zero value otherwise.

### GetFederationAccessGroupIdOk

`func (o *PermissionInfo) GetFederationAccessGroupIdOk() (*string, bool)`

GetFederationAccessGroupIdOk returns a tuple with the FederationAccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederationAccessGroupId

`func (o *PermissionInfo) SetFederationAccessGroupId(v string)`

SetFederationAccessGroupId sets FederationAccessGroupId field to given value.

### HasFederationAccessGroupId

`func (o *PermissionInfo) HasFederationAccessGroupId() bool`

HasFederationAccessGroupId returns a boolean if a field has been set.

### GetId

`func (o *PermissionInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PermissionInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PermissionInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PermissionInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLocalAccessGroupId

`func (o *PermissionInfo) GetLocalAccessGroupId() string`

GetLocalAccessGroupId returns the LocalAccessGroupId field if non-nil, zero value otherwise.

### GetLocalAccessGroupIdOk

`func (o *PermissionInfo) GetLocalAccessGroupIdOk() (*string, bool)`

GetLocalAccessGroupIdOk returns a tuple with the LocalAccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalAccessGroupId

`func (o *PermissionInfo) SetLocalAccessGroupId(v string)`

SetLocalAccessGroupId sets LocalAccessGroupId field to given value.

### HasLocalAccessGroupId

`func (o *PermissionInfo) HasLocalAccessGroupId() bool`

HasLocalAccessGroupId returns a boolean if a field has been set.

### GetRoleId

`func (o *PermissionInfo) GetRoleId() string`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *PermissionInfo) GetRoleIdOk() (*string, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *PermissionInfo) SetRoleId(v string)`

SetRoleId sets RoleId field to given value.

### HasRoleId

`func (o *PermissionInfo) HasRoleId() bool`

HasRoleId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


