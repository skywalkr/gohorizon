# UnauthenticatedAccessUserInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AliasName** | Pointer to **string** | Alias used for login from client. | [optional] 
**Description** | Pointer to **string** | Description of the unauthenticated access user. | [optional] 
**HybridLogonMode** | Pointer to **string** | Mode used for hybrid logon. * PASSWORD: Hybrid logon via username and password. * TRUESSO: Hybrid logon via True SSO. * DISABLED: Hybrid logon disabled. | [optional] 
**Id** | Pointer to **string** | ID of the unauthenticated access configuration for the user. | [optional] 
**SourcePodIds** | Pointer to **[]string** | Pods in which the unauthenticated access user was created.  This will be unset if CPA is not initialized or if the caller does not have FEDERATED_LDAP_VIEW privilege. | [optional] 
**UserId** | Pointer to **string** | SID of the user for whom unauthenticated access is configured. | [optional] 

## Methods

### NewUnauthenticatedAccessUserInfo

`func NewUnauthenticatedAccessUserInfo() *UnauthenticatedAccessUserInfo`

NewUnauthenticatedAccessUserInfo instantiates a new UnauthenticatedAccessUserInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUnauthenticatedAccessUserInfoWithDefaults

`func NewUnauthenticatedAccessUserInfoWithDefaults() *UnauthenticatedAccessUserInfo`

NewUnauthenticatedAccessUserInfoWithDefaults instantiates a new UnauthenticatedAccessUserInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAliasName

`func (o *UnauthenticatedAccessUserInfo) GetAliasName() string`

GetAliasName returns the AliasName field if non-nil, zero value otherwise.

### GetAliasNameOk

`func (o *UnauthenticatedAccessUserInfo) GetAliasNameOk() (*string, bool)`

GetAliasNameOk returns a tuple with the AliasName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAliasName

`func (o *UnauthenticatedAccessUserInfo) SetAliasName(v string)`

SetAliasName sets AliasName field to given value.

### HasAliasName

`func (o *UnauthenticatedAccessUserInfo) HasAliasName() bool`

HasAliasName returns a boolean if a field has been set.

### GetDescription

`func (o *UnauthenticatedAccessUserInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UnauthenticatedAccessUserInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UnauthenticatedAccessUserInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UnauthenticatedAccessUserInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetHybridLogonMode

`func (o *UnauthenticatedAccessUserInfo) GetHybridLogonMode() string`

GetHybridLogonMode returns the HybridLogonMode field if non-nil, zero value otherwise.

### GetHybridLogonModeOk

`func (o *UnauthenticatedAccessUserInfo) GetHybridLogonModeOk() (*string, bool)`

GetHybridLogonModeOk returns a tuple with the HybridLogonMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHybridLogonMode

`func (o *UnauthenticatedAccessUserInfo) SetHybridLogonMode(v string)`

SetHybridLogonMode sets HybridLogonMode field to given value.

### HasHybridLogonMode

`func (o *UnauthenticatedAccessUserInfo) HasHybridLogonMode() bool`

HasHybridLogonMode returns a boolean if a field has been set.

### GetId

`func (o *UnauthenticatedAccessUserInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UnauthenticatedAccessUserInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UnauthenticatedAccessUserInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *UnauthenticatedAccessUserInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSourcePodIds

`func (o *UnauthenticatedAccessUserInfo) GetSourcePodIds() []string`

GetSourcePodIds returns the SourcePodIds field if non-nil, zero value otherwise.

### GetSourcePodIdsOk

`func (o *UnauthenticatedAccessUserInfo) GetSourcePodIdsOk() (*[]string, bool)`

GetSourcePodIdsOk returns a tuple with the SourcePodIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePodIds

`func (o *UnauthenticatedAccessUserInfo) SetSourcePodIds(v []string)`

SetSourcePodIds sets SourcePodIds field to given value.

### HasSourcePodIds

`func (o *UnauthenticatedAccessUserInfo) HasSourcePodIds() bool`

HasSourcePodIds returns a boolean if a field has been set.

### GetUserId

`func (o *UnauthenticatedAccessUserInfo) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UnauthenticatedAccessUserInfo) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UnauthenticatedAccessUserInfo) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *UnauthenticatedAccessUserInfo) HasUserId() bool`

HasUserId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


