# ConnectionServerRSASecureIdSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClearNodeSecret** | Pointer to **bool** | When set to TRUE the SecureID node secret is cleared | [optional] 
**NameMapping** | Pointer to **bool** | Indicates how SecureID names map to AD usernames. It is false for not mapped. | [optional] 
**SecureIdEnabled** | **bool** | Indicates whether SecureID authentication is required. | 
**SecurityFileData** | Pointer to **string** | Binary contents of the SecurID sdconf.rec file. | [optional] 

## Methods

### NewConnectionServerRSASecureIdSpec

`func NewConnectionServerRSASecureIdSpec(secureIdEnabled bool, ) *ConnectionServerRSASecureIdSpec`

NewConnectionServerRSASecureIdSpec instantiates a new ConnectionServerRSASecureIdSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerRSASecureIdSpecWithDefaults

`func NewConnectionServerRSASecureIdSpecWithDefaults() *ConnectionServerRSASecureIdSpec`

NewConnectionServerRSASecureIdSpecWithDefaults instantiates a new ConnectionServerRSASecureIdSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClearNodeSecret

`func (o *ConnectionServerRSASecureIdSpec) GetClearNodeSecret() bool`

GetClearNodeSecret returns the ClearNodeSecret field if non-nil, zero value otherwise.

### GetClearNodeSecretOk

`func (o *ConnectionServerRSASecureIdSpec) GetClearNodeSecretOk() (*bool, bool)`

GetClearNodeSecretOk returns a tuple with the ClearNodeSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearNodeSecret

`func (o *ConnectionServerRSASecureIdSpec) SetClearNodeSecret(v bool)`

SetClearNodeSecret sets ClearNodeSecret field to given value.

### HasClearNodeSecret

`func (o *ConnectionServerRSASecureIdSpec) HasClearNodeSecret() bool`

HasClearNodeSecret returns a boolean if a field has been set.

### GetNameMapping

`func (o *ConnectionServerRSASecureIdSpec) GetNameMapping() bool`

GetNameMapping returns the NameMapping field if non-nil, zero value otherwise.

### GetNameMappingOk

`func (o *ConnectionServerRSASecureIdSpec) GetNameMappingOk() (*bool, bool)`

GetNameMappingOk returns a tuple with the NameMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameMapping

`func (o *ConnectionServerRSASecureIdSpec) SetNameMapping(v bool)`

SetNameMapping sets NameMapping field to given value.

### HasNameMapping

`func (o *ConnectionServerRSASecureIdSpec) HasNameMapping() bool`

HasNameMapping returns a boolean if a field has been set.

### GetSecureIdEnabled

`func (o *ConnectionServerRSASecureIdSpec) GetSecureIdEnabled() bool`

GetSecureIdEnabled returns the SecureIdEnabled field if non-nil, zero value otherwise.

### GetSecureIdEnabledOk

`func (o *ConnectionServerRSASecureIdSpec) GetSecureIdEnabledOk() (*bool, bool)`

GetSecureIdEnabledOk returns a tuple with the SecureIdEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecureIdEnabled

`func (o *ConnectionServerRSASecureIdSpec) SetSecureIdEnabled(v bool)`

SetSecureIdEnabled sets SecureIdEnabled field to given value.


### GetSecurityFileData

`func (o *ConnectionServerRSASecureIdSpec) GetSecurityFileData() string`

GetSecurityFileData returns the SecurityFileData field if non-nil, zero value otherwise.

### GetSecurityFileDataOk

`func (o *ConnectionServerRSASecureIdSpec) GetSecurityFileDataOk() (*string, bool)`

GetSecurityFileDataOk returns a tuple with the SecurityFileData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityFileData

`func (o *ConnectionServerRSASecureIdSpec) SetSecurityFileData(v string)`

SetSecurityFileData sets SecurityFileData field to given value.

### HasSecurityFileData

`func (o *ConnectionServerRSASecureIdSpec) HasSecurityFileData() bool`

HasSecurityFileData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


