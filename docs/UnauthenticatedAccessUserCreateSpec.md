# UnauthenticatedAccessUserCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AliasName** | Pointer to **string** | Alias to be used for login from client. If unset, AD login name of the user would be used. | [optional] 
**Description** | Pointer to **string** | Description of the unauthenticated access user. | [optional] 
**HybridLogonMode** | Pointer to **string** | Mode to be used for hybrid logon. If unset, hybrid logon will be disabled. * PASSWORD: Hybrid logon via username and password. * TRUESSO: Hybrid logon via True SSO. * DISABLED: Hybrid logon disabled. | [optional] 
**HybridLogonPassword** | Pointer to **[]string** | Password for the user for hybrid logon. This is required when hybrid_logon_mode is set to PASSWORD. | [optional] 
**UserId** | **string** | SID of the user for whom unauthenticated access is to be configured. | 

## Methods

### NewUnauthenticatedAccessUserCreateSpec

`func NewUnauthenticatedAccessUserCreateSpec(userId string, ) *UnauthenticatedAccessUserCreateSpec`

NewUnauthenticatedAccessUserCreateSpec instantiates a new UnauthenticatedAccessUserCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUnauthenticatedAccessUserCreateSpecWithDefaults

`func NewUnauthenticatedAccessUserCreateSpecWithDefaults() *UnauthenticatedAccessUserCreateSpec`

NewUnauthenticatedAccessUserCreateSpecWithDefaults instantiates a new UnauthenticatedAccessUserCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAliasName

`func (o *UnauthenticatedAccessUserCreateSpec) GetAliasName() string`

GetAliasName returns the AliasName field if non-nil, zero value otherwise.

### GetAliasNameOk

`func (o *UnauthenticatedAccessUserCreateSpec) GetAliasNameOk() (*string, bool)`

GetAliasNameOk returns a tuple with the AliasName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAliasName

`func (o *UnauthenticatedAccessUserCreateSpec) SetAliasName(v string)`

SetAliasName sets AliasName field to given value.

### HasAliasName

`func (o *UnauthenticatedAccessUserCreateSpec) HasAliasName() bool`

HasAliasName returns a boolean if a field has been set.

### GetDescription

`func (o *UnauthenticatedAccessUserCreateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UnauthenticatedAccessUserCreateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UnauthenticatedAccessUserCreateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UnauthenticatedAccessUserCreateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetHybridLogonMode

`func (o *UnauthenticatedAccessUserCreateSpec) GetHybridLogonMode() string`

GetHybridLogonMode returns the HybridLogonMode field if non-nil, zero value otherwise.

### GetHybridLogonModeOk

`func (o *UnauthenticatedAccessUserCreateSpec) GetHybridLogonModeOk() (*string, bool)`

GetHybridLogonModeOk returns a tuple with the HybridLogonMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHybridLogonMode

`func (o *UnauthenticatedAccessUserCreateSpec) SetHybridLogonMode(v string)`

SetHybridLogonMode sets HybridLogonMode field to given value.

### HasHybridLogonMode

`func (o *UnauthenticatedAccessUserCreateSpec) HasHybridLogonMode() bool`

HasHybridLogonMode returns a boolean if a field has been set.

### GetHybridLogonPassword

`func (o *UnauthenticatedAccessUserCreateSpec) GetHybridLogonPassword() []string`

GetHybridLogonPassword returns the HybridLogonPassword field if non-nil, zero value otherwise.

### GetHybridLogonPasswordOk

`func (o *UnauthenticatedAccessUserCreateSpec) GetHybridLogonPasswordOk() (*[]string, bool)`

GetHybridLogonPasswordOk returns a tuple with the HybridLogonPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHybridLogonPassword

`func (o *UnauthenticatedAccessUserCreateSpec) SetHybridLogonPassword(v []string)`

SetHybridLogonPassword sets HybridLogonPassword field to given value.

### HasHybridLogonPassword

`func (o *UnauthenticatedAccessUserCreateSpec) HasHybridLogonPassword() bool`

HasHybridLogonPassword returns a boolean if a field has been set.

### GetUserId

`func (o *UnauthenticatedAccessUserCreateSpec) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UnauthenticatedAccessUserCreateSpec) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UnauthenticatedAccessUserCreateSpec) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


