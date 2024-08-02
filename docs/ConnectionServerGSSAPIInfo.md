# ConnectionServerGSSAPIInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowReceivingNtlm** | Pointer to **bool** | Indicates whether connection server supports NTLM or not. | [optional] 
**GssApiauthenticatorId** | Pointer to **string** | ID of the GSS API authenticator to use. | [optional] 
**GssApienabled** | Pointer to **bool** | Indicates whether GSSAPI authentication is enabled. | [optional] 

## Methods

### NewConnectionServerGSSAPIInfo

`func NewConnectionServerGSSAPIInfo() *ConnectionServerGSSAPIInfo`

NewConnectionServerGSSAPIInfo instantiates a new ConnectionServerGSSAPIInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerGSSAPIInfoWithDefaults

`func NewConnectionServerGSSAPIInfoWithDefaults() *ConnectionServerGSSAPIInfo`

NewConnectionServerGSSAPIInfoWithDefaults instantiates a new ConnectionServerGSSAPIInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowReceivingNtlm

`func (o *ConnectionServerGSSAPIInfo) GetAllowReceivingNtlm() bool`

GetAllowReceivingNtlm returns the AllowReceivingNtlm field if non-nil, zero value otherwise.

### GetAllowReceivingNtlmOk

`func (o *ConnectionServerGSSAPIInfo) GetAllowReceivingNtlmOk() (*bool, bool)`

GetAllowReceivingNtlmOk returns a tuple with the AllowReceivingNtlm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowReceivingNtlm

`func (o *ConnectionServerGSSAPIInfo) SetAllowReceivingNtlm(v bool)`

SetAllowReceivingNtlm sets AllowReceivingNtlm field to given value.

### HasAllowReceivingNtlm

`func (o *ConnectionServerGSSAPIInfo) HasAllowReceivingNtlm() bool`

HasAllowReceivingNtlm returns a boolean if a field has been set.

### GetGssApiauthenticatorId

`func (o *ConnectionServerGSSAPIInfo) GetGssApiauthenticatorId() string`

GetGssApiauthenticatorId returns the GssApiauthenticatorId field if non-nil, zero value otherwise.

### GetGssApiauthenticatorIdOk

`func (o *ConnectionServerGSSAPIInfo) GetGssApiauthenticatorIdOk() (*string, bool)`

GetGssApiauthenticatorIdOk returns a tuple with the GssApiauthenticatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGssApiauthenticatorId

`func (o *ConnectionServerGSSAPIInfo) SetGssApiauthenticatorId(v string)`

SetGssApiauthenticatorId sets GssApiauthenticatorId field to given value.

### HasGssApiauthenticatorId

`func (o *ConnectionServerGSSAPIInfo) HasGssApiauthenticatorId() bool`

HasGssApiauthenticatorId returns a boolean if a field has been set.

### GetGssApienabled

`func (o *ConnectionServerGSSAPIInfo) GetGssApienabled() bool`

GetGssApienabled returns the GssApienabled field if non-nil, zero value otherwise.

### GetGssApienabledOk

`func (o *ConnectionServerGSSAPIInfo) GetGssApienabledOk() (*bool, bool)`

GetGssApienabledOk returns a tuple with the GssApienabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGssApienabled

`func (o *ConnectionServerGSSAPIInfo) SetGssApienabled(v bool)`

SetGssApienabled sets GssApienabled field to given value.

### HasGssApienabled

`func (o *ConnectionServerGSSAPIInfo) HasGssApienabled() bool`

HasGssApienabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


