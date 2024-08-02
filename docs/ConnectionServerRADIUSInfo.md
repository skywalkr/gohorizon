# ConnectionServerRADIUSInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RadiusAuthenticatorId** | Pointer to **string** | The RADIUS Authenticator to use. | [optional] 
**RadiusEnabled** | Pointer to **bool** | Flag to specify if RADIUS authentication is enabled. | [optional] 
**RadiusNameMapping** | Pointer to **bool** | Flag to specify if RADIUS name mapping is enabled. | [optional] 
**RadiusSso** | Pointer to **bool** | Flag to specify if RADIUS Windows Single Sign-On is enabled. | [optional] 

## Methods

### NewConnectionServerRADIUSInfo

`func NewConnectionServerRADIUSInfo() *ConnectionServerRADIUSInfo`

NewConnectionServerRADIUSInfo instantiates a new ConnectionServerRADIUSInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerRADIUSInfoWithDefaults

`func NewConnectionServerRADIUSInfoWithDefaults() *ConnectionServerRADIUSInfo`

NewConnectionServerRADIUSInfoWithDefaults instantiates a new ConnectionServerRADIUSInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRadiusAuthenticatorId

`func (o *ConnectionServerRADIUSInfo) GetRadiusAuthenticatorId() string`

GetRadiusAuthenticatorId returns the RadiusAuthenticatorId field if non-nil, zero value otherwise.

### GetRadiusAuthenticatorIdOk

`func (o *ConnectionServerRADIUSInfo) GetRadiusAuthenticatorIdOk() (*string, bool)`

GetRadiusAuthenticatorIdOk returns a tuple with the RadiusAuthenticatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusAuthenticatorId

`func (o *ConnectionServerRADIUSInfo) SetRadiusAuthenticatorId(v string)`

SetRadiusAuthenticatorId sets RadiusAuthenticatorId field to given value.

### HasRadiusAuthenticatorId

`func (o *ConnectionServerRADIUSInfo) HasRadiusAuthenticatorId() bool`

HasRadiusAuthenticatorId returns a boolean if a field has been set.

### GetRadiusEnabled

`func (o *ConnectionServerRADIUSInfo) GetRadiusEnabled() bool`

GetRadiusEnabled returns the RadiusEnabled field if non-nil, zero value otherwise.

### GetRadiusEnabledOk

`func (o *ConnectionServerRADIUSInfo) GetRadiusEnabledOk() (*bool, bool)`

GetRadiusEnabledOk returns a tuple with the RadiusEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusEnabled

`func (o *ConnectionServerRADIUSInfo) SetRadiusEnabled(v bool)`

SetRadiusEnabled sets RadiusEnabled field to given value.

### HasRadiusEnabled

`func (o *ConnectionServerRADIUSInfo) HasRadiusEnabled() bool`

HasRadiusEnabled returns a boolean if a field has been set.

### GetRadiusNameMapping

`func (o *ConnectionServerRADIUSInfo) GetRadiusNameMapping() bool`

GetRadiusNameMapping returns the RadiusNameMapping field if non-nil, zero value otherwise.

### GetRadiusNameMappingOk

`func (o *ConnectionServerRADIUSInfo) GetRadiusNameMappingOk() (*bool, bool)`

GetRadiusNameMappingOk returns a tuple with the RadiusNameMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusNameMapping

`func (o *ConnectionServerRADIUSInfo) SetRadiusNameMapping(v bool)`

SetRadiusNameMapping sets RadiusNameMapping field to given value.

### HasRadiusNameMapping

`func (o *ConnectionServerRADIUSInfo) HasRadiusNameMapping() bool`

HasRadiusNameMapping returns a boolean if a field has been set.

### GetRadiusSso

`func (o *ConnectionServerRADIUSInfo) GetRadiusSso() bool`

GetRadiusSso returns the RadiusSso field if non-nil, zero value otherwise.

### GetRadiusSsoOk

`func (o *ConnectionServerRADIUSInfo) GetRadiusSsoOk() (*bool, bool)`

GetRadiusSsoOk returns a tuple with the RadiusSso field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusSso

`func (o *ConnectionServerRADIUSInfo) SetRadiusSso(v bool)`

SetRadiusSso sets RadiusSso field to given value.

### HasRadiusSso

`func (o *ConnectionServerRADIUSInfo) HasRadiusSso() bool`

HasRadiusSso returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


