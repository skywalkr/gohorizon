# ConnectionServerRSASecureIdInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClearNodeSecret** | Pointer to **bool** | When set to TRUE the SecureID node secret is cleared | [optional] 
**NameMapping** | Pointer to **bool** | Indicates how SecureID names map to AD usernames. It is false for not mapped. | [optional] 
**SecureIdEnabled** | Pointer to **bool** | Indicates whether SecureID authentication is required. | [optional] 
**SecurityFileUploaded** | Pointer to **bool** | If SecureID sdconf.rec file is already uploaded. The client can never download the file. | [optional] 

## Methods

### NewConnectionServerRSASecureIdInfo

`func NewConnectionServerRSASecureIdInfo() *ConnectionServerRSASecureIdInfo`

NewConnectionServerRSASecureIdInfo instantiates a new ConnectionServerRSASecureIdInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerRSASecureIdInfoWithDefaults

`func NewConnectionServerRSASecureIdInfoWithDefaults() *ConnectionServerRSASecureIdInfo`

NewConnectionServerRSASecureIdInfoWithDefaults instantiates a new ConnectionServerRSASecureIdInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClearNodeSecret

`func (o *ConnectionServerRSASecureIdInfo) GetClearNodeSecret() bool`

GetClearNodeSecret returns the ClearNodeSecret field if non-nil, zero value otherwise.

### GetClearNodeSecretOk

`func (o *ConnectionServerRSASecureIdInfo) GetClearNodeSecretOk() (*bool, bool)`

GetClearNodeSecretOk returns a tuple with the ClearNodeSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearNodeSecret

`func (o *ConnectionServerRSASecureIdInfo) SetClearNodeSecret(v bool)`

SetClearNodeSecret sets ClearNodeSecret field to given value.

### HasClearNodeSecret

`func (o *ConnectionServerRSASecureIdInfo) HasClearNodeSecret() bool`

HasClearNodeSecret returns a boolean if a field has been set.

### GetNameMapping

`func (o *ConnectionServerRSASecureIdInfo) GetNameMapping() bool`

GetNameMapping returns the NameMapping field if non-nil, zero value otherwise.

### GetNameMappingOk

`func (o *ConnectionServerRSASecureIdInfo) GetNameMappingOk() (*bool, bool)`

GetNameMappingOk returns a tuple with the NameMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameMapping

`func (o *ConnectionServerRSASecureIdInfo) SetNameMapping(v bool)`

SetNameMapping sets NameMapping field to given value.

### HasNameMapping

`func (o *ConnectionServerRSASecureIdInfo) HasNameMapping() bool`

HasNameMapping returns a boolean if a field has been set.

### GetSecureIdEnabled

`func (o *ConnectionServerRSASecureIdInfo) GetSecureIdEnabled() bool`

GetSecureIdEnabled returns the SecureIdEnabled field if non-nil, zero value otherwise.

### GetSecureIdEnabledOk

`func (o *ConnectionServerRSASecureIdInfo) GetSecureIdEnabledOk() (*bool, bool)`

GetSecureIdEnabledOk returns a tuple with the SecureIdEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecureIdEnabled

`func (o *ConnectionServerRSASecureIdInfo) SetSecureIdEnabled(v bool)`

SetSecureIdEnabled sets SecureIdEnabled field to given value.

### HasSecureIdEnabled

`func (o *ConnectionServerRSASecureIdInfo) HasSecureIdEnabled() bool`

HasSecureIdEnabled returns a boolean if a field has been set.

### GetSecurityFileUploaded

`func (o *ConnectionServerRSASecureIdInfo) GetSecurityFileUploaded() bool`

GetSecurityFileUploaded returns the SecurityFileUploaded field if non-nil, zero value otherwise.

### GetSecurityFileUploadedOk

`func (o *ConnectionServerRSASecureIdInfo) GetSecurityFileUploadedOk() (*bool, bool)`

GetSecurityFileUploadedOk returns a tuple with the SecurityFileUploaded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityFileUploaded

`func (o *ConnectionServerRSASecureIdInfo) SetSecurityFileUploaded(v bool)`

SetSecurityFileUploaded sets SecurityFileUploaded field to given value.

### HasSecurityFileUploaded

`func (o *ConnectionServerRSASecureIdInfo) HasSecurityFileUploaded() bool`

HasSecurityFileUploaded returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


