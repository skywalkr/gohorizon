# AdminUserOrGroupPermissionsInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FederatedPrivilegesInfo** | Pointer to [**[]AdminUserOrGroupPrivilegesInfo**](AdminUserOrGroupPrivilegesInfo.md) | Set of privileges information based on federated access groups for this user or group. | [optional] 
**HelpDeskAdmin** | Pointer to **bool** |  | [optional] 
**Id** | Pointer to **string** | Unique SID representing the admin user or group. | [optional] 
**LocalPrivilegesInfo** | Pointer to [**[]AdminUserOrGroupPrivilegesInfo**](AdminUserOrGroupPrivilegesInfo.md) | Set of privileges information based on local access groups for this user or group. | [optional] 

## Methods

### NewAdminUserOrGroupPermissionsInfo

`func NewAdminUserOrGroupPermissionsInfo() *AdminUserOrGroupPermissionsInfo`

NewAdminUserOrGroupPermissionsInfo instantiates a new AdminUserOrGroupPermissionsInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminUserOrGroupPermissionsInfoWithDefaults

`func NewAdminUserOrGroupPermissionsInfoWithDefaults() *AdminUserOrGroupPermissionsInfo`

NewAdminUserOrGroupPermissionsInfoWithDefaults instantiates a new AdminUserOrGroupPermissionsInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFederatedPrivilegesInfo

`func (o *AdminUserOrGroupPermissionsInfo) GetFederatedPrivilegesInfo() []AdminUserOrGroupPrivilegesInfo`

GetFederatedPrivilegesInfo returns the FederatedPrivilegesInfo field if non-nil, zero value otherwise.

### GetFederatedPrivilegesInfoOk

`func (o *AdminUserOrGroupPermissionsInfo) GetFederatedPrivilegesInfoOk() (*[]AdminUserOrGroupPrivilegesInfo, bool)`

GetFederatedPrivilegesInfoOk returns a tuple with the FederatedPrivilegesInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederatedPrivilegesInfo

`func (o *AdminUserOrGroupPermissionsInfo) SetFederatedPrivilegesInfo(v []AdminUserOrGroupPrivilegesInfo)`

SetFederatedPrivilegesInfo sets FederatedPrivilegesInfo field to given value.

### HasFederatedPrivilegesInfo

`func (o *AdminUserOrGroupPermissionsInfo) HasFederatedPrivilegesInfo() bool`

HasFederatedPrivilegesInfo returns a boolean if a field has been set.

### GetHelpDeskAdmin

`func (o *AdminUserOrGroupPermissionsInfo) GetHelpDeskAdmin() bool`

GetHelpDeskAdmin returns the HelpDeskAdmin field if non-nil, zero value otherwise.

### GetHelpDeskAdminOk

`func (o *AdminUserOrGroupPermissionsInfo) GetHelpDeskAdminOk() (*bool, bool)`

GetHelpDeskAdminOk returns a tuple with the HelpDeskAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelpDeskAdmin

`func (o *AdminUserOrGroupPermissionsInfo) SetHelpDeskAdmin(v bool)`

SetHelpDeskAdmin sets HelpDeskAdmin field to given value.

### HasHelpDeskAdmin

`func (o *AdminUserOrGroupPermissionsInfo) HasHelpDeskAdmin() bool`

HasHelpDeskAdmin returns a boolean if a field has been set.

### GetId

`func (o *AdminUserOrGroupPermissionsInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AdminUserOrGroupPermissionsInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AdminUserOrGroupPermissionsInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AdminUserOrGroupPermissionsInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLocalPrivilegesInfo

`func (o *AdminUserOrGroupPermissionsInfo) GetLocalPrivilegesInfo() []AdminUserOrGroupPrivilegesInfo`

GetLocalPrivilegesInfo returns the LocalPrivilegesInfo field if non-nil, zero value otherwise.

### GetLocalPrivilegesInfoOk

`func (o *AdminUserOrGroupPermissionsInfo) GetLocalPrivilegesInfoOk() (*[]AdminUserOrGroupPrivilegesInfo, bool)`

GetLocalPrivilegesInfoOk returns a tuple with the LocalPrivilegesInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalPrivilegesInfo

`func (o *AdminUserOrGroupPermissionsInfo) SetLocalPrivilegesInfo(v []AdminUserOrGroupPrivilegesInfo)`

SetLocalPrivilegesInfo sets LocalPrivilegesInfo field to given value.

### HasLocalPrivilegesInfo

`func (o *AdminUserOrGroupPermissionsInfo) HasLocalPrivilegesInfo() bool`

HasLocalPrivilegesInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


