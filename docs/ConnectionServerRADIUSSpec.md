# ConnectionServerRADIUSSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RadiusAuthenticatorId** | Pointer to **string** | The RADIUS Authenticator to use. | [optional] 
**RadiusEnabled** | **bool** | Indicates whether RADIUS authentication is enabled. | 
**RadiusNameMapping** | Pointer to **bool** | Indicates whether RADIUS name mapping is enabled. | [optional] 
**RadiusSso** | Pointer to **bool** | Indicates whether RADIUS Windows Single Sign-On is enabled. | [optional] 

## Methods

### NewConnectionServerRADIUSSpec

`func NewConnectionServerRADIUSSpec(radiusEnabled bool, ) *ConnectionServerRADIUSSpec`

NewConnectionServerRADIUSSpec instantiates a new ConnectionServerRADIUSSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerRADIUSSpecWithDefaults

`func NewConnectionServerRADIUSSpecWithDefaults() *ConnectionServerRADIUSSpec`

NewConnectionServerRADIUSSpecWithDefaults instantiates a new ConnectionServerRADIUSSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRadiusAuthenticatorId

`func (o *ConnectionServerRADIUSSpec) GetRadiusAuthenticatorId() string`

GetRadiusAuthenticatorId returns the RadiusAuthenticatorId field if non-nil, zero value otherwise.

### GetRadiusAuthenticatorIdOk

`func (o *ConnectionServerRADIUSSpec) GetRadiusAuthenticatorIdOk() (*string, bool)`

GetRadiusAuthenticatorIdOk returns a tuple with the RadiusAuthenticatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusAuthenticatorId

`func (o *ConnectionServerRADIUSSpec) SetRadiusAuthenticatorId(v string)`

SetRadiusAuthenticatorId sets RadiusAuthenticatorId field to given value.

### HasRadiusAuthenticatorId

`func (o *ConnectionServerRADIUSSpec) HasRadiusAuthenticatorId() bool`

HasRadiusAuthenticatorId returns a boolean if a field has been set.

### GetRadiusEnabled

`func (o *ConnectionServerRADIUSSpec) GetRadiusEnabled() bool`

GetRadiusEnabled returns the RadiusEnabled field if non-nil, zero value otherwise.

### GetRadiusEnabledOk

`func (o *ConnectionServerRADIUSSpec) GetRadiusEnabledOk() (*bool, bool)`

GetRadiusEnabledOk returns a tuple with the RadiusEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusEnabled

`func (o *ConnectionServerRADIUSSpec) SetRadiusEnabled(v bool)`

SetRadiusEnabled sets RadiusEnabled field to given value.


### GetRadiusNameMapping

`func (o *ConnectionServerRADIUSSpec) GetRadiusNameMapping() bool`

GetRadiusNameMapping returns the RadiusNameMapping field if non-nil, zero value otherwise.

### GetRadiusNameMappingOk

`func (o *ConnectionServerRADIUSSpec) GetRadiusNameMappingOk() (*bool, bool)`

GetRadiusNameMappingOk returns a tuple with the RadiusNameMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusNameMapping

`func (o *ConnectionServerRADIUSSpec) SetRadiusNameMapping(v bool)`

SetRadiusNameMapping sets RadiusNameMapping field to given value.

### HasRadiusNameMapping

`func (o *ConnectionServerRADIUSSpec) HasRadiusNameMapping() bool`

HasRadiusNameMapping returns a boolean if a field has been set.

### GetRadiusSso

`func (o *ConnectionServerRADIUSSpec) GetRadiusSso() bool`

GetRadiusSso returns the RadiusSso field if non-nil, zero value otherwise.

### GetRadiusSsoOk

`func (o *ConnectionServerRADIUSSpec) GetRadiusSsoOk() (*bool, bool)`

GetRadiusSsoOk returns a tuple with the RadiusSso field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusSso

`func (o *ConnectionServerRADIUSSpec) SetRadiusSso(v bool)`

SetRadiusSso sets RadiusSso field to given value.

### HasRadiusSso

`func (o *ConnectionServerRADIUSSpec) HasRadiusSso() bool`

HasRadiusSso returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


