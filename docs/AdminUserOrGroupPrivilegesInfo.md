# AdminUserOrGroupPrivilegesInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessGroupId** | Pointer to **string** | ID of the access group. | [optional] 
**AccessGroupName** | Pointer to **string** | Name of the access group. | [optional] 
**Privileges** | Pointer to **[]string** | The set of privileges on the access group. | [optional] 

## Methods

### NewAdminUserOrGroupPrivilegesInfo

`func NewAdminUserOrGroupPrivilegesInfo() *AdminUserOrGroupPrivilegesInfo`

NewAdminUserOrGroupPrivilegesInfo instantiates a new AdminUserOrGroupPrivilegesInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminUserOrGroupPrivilegesInfoWithDefaults

`func NewAdminUserOrGroupPrivilegesInfoWithDefaults() *AdminUserOrGroupPrivilegesInfo`

NewAdminUserOrGroupPrivilegesInfoWithDefaults instantiates a new AdminUserOrGroupPrivilegesInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessGroupId

`func (o *AdminUserOrGroupPrivilegesInfo) GetAccessGroupId() string`

GetAccessGroupId returns the AccessGroupId field if non-nil, zero value otherwise.

### GetAccessGroupIdOk

`func (o *AdminUserOrGroupPrivilegesInfo) GetAccessGroupIdOk() (*string, bool)`

GetAccessGroupIdOk returns a tuple with the AccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessGroupId

`func (o *AdminUserOrGroupPrivilegesInfo) SetAccessGroupId(v string)`

SetAccessGroupId sets AccessGroupId field to given value.

### HasAccessGroupId

`func (o *AdminUserOrGroupPrivilegesInfo) HasAccessGroupId() bool`

HasAccessGroupId returns a boolean if a field has been set.

### GetAccessGroupName

`func (o *AdminUserOrGroupPrivilegesInfo) GetAccessGroupName() string`

GetAccessGroupName returns the AccessGroupName field if non-nil, zero value otherwise.

### GetAccessGroupNameOk

`func (o *AdminUserOrGroupPrivilegesInfo) GetAccessGroupNameOk() (*string, bool)`

GetAccessGroupNameOk returns a tuple with the AccessGroupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessGroupName

`func (o *AdminUserOrGroupPrivilegesInfo) SetAccessGroupName(v string)`

SetAccessGroupName sets AccessGroupName field to given value.

### HasAccessGroupName

`func (o *AdminUserOrGroupPrivilegesInfo) HasAccessGroupName() bool`

HasAccessGroupName returns a boolean if a field has been set.

### GetPrivileges

`func (o *AdminUserOrGroupPrivilegesInfo) GetPrivileges() []string`

GetPrivileges returns the Privileges field if non-nil, zero value otherwise.

### GetPrivilegesOk

`func (o *AdminUserOrGroupPrivilegesInfo) GetPrivilegesOk() (*[]string, bool)`

GetPrivilegesOk returns a tuple with the Privileges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivileges

`func (o *AdminUserOrGroupPrivilegesInfo) SetPrivileges(v []string)`

SetPrivileges sets Privileges field to given value.

### HasPrivileges

`func (o *AdminUserOrGroupPrivilegesInfo) HasPrivileges() bool`

HasPrivileges returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


