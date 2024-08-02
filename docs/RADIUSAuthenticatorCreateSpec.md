# RADIUSAuthenticatorCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The description for this RADIUS authenticator. | [optional] 
**Label** | **string** | The label for this RADIUS authenticator. It must be unique among all other RADIUS authenticators. | 
**PasscodeLabel** | Pointer to **string** | The label for the RADIUS authenticator passcode. | [optional] 
**RadiusServers** | [**[]RADIUSServerCreateSpec**](RADIUSServerCreateSpec.md) | List of RADIUS servers. The list must have exactly one primary RADIUS server i.e. with primary_radius_server set to true. | 
**UserNameLabel** | Pointer to **string** | The label for the RADIUS authenticator user name. | [optional] 

## Methods

### NewRADIUSAuthenticatorCreateSpec

`func NewRADIUSAuthenticatorCreateSpec(label string, radiusServers []RADIUSServerCreateSpec, ) *RADIUSAuthenticatorCreateSpec`

NewRADIUSAuthenticatorCreateSpec instantiates a new RADIUSAuthenticatorCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRADIUSAuthenticatorCreateSpecWithDefaults

`func NewRADIUSAuthenticatorCreateSpecWithDefaults() *RADIUSAuthenticatorCreateSpec`

NewRADIUSAuthenticatorCreateSpecWithDefaults instantiates a new RADIUSAuthenticatorCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *RADIUSAuthenticatorCreateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RADIUSAuthenticatorCreateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RADIUSAuthenticatorCreateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RADIUSAuthenticatorCreateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLabel

`func (o *RADIUSAuthenticatorCreateSpec) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *RADIUSAuthenticatorCreateSpec) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *RADIUSAuthenticatorCreateSpec) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetPasscodeLabel

`func (o *RADIUSAuthenticatorCreateSpec) GetPasscodeLabel() string`

GetPasscodeLabel returns the PasscodeLabel field if non-nil, zero value otherwise.

### GetPasscodeLabelOk

`func (o *RADIUSAuthenticatorCreateSpec) GetPasscodeLabelOk() (*string, bool)`

GetPasscodeLabelOk returns a tuple with the PasscodeLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasscodeLabel

`func (o *RADIUSAuthenticatorCreateSpec) SetPasscodeLabel(v string)`

SetPasscodeLabel sets PasscodeLabel field to given value.

### HasPasscodeLabel

`func (o *RADIUSAuthenticatorCreateSpec) HasPasscodeLabel() bool`

HasPasscodeLabel returns a boolean if a field has been set.

### GetRadiusServers

`func (o *RADIUSAuthenticatorCreateSpec) GetRadiusServers() []RADIUSServerCreateSpec`

GetRadiusServers returns the RadiusServers field if non-nil, zero value otherwise.

### GetRadiusServersOk

`func (o *RADIUSAuthenticatorCreateSpec) GetRadiusServersOk() (*[]RADIUSServerCreateSpec, bool)`

GetRadiusServersOk returns a tuple with the RadiusServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusServers

`func (o *RADIUSAuthenticatorCreateSpec) SetRadiusServers(v []RADIUSServerCreateSpec)`

SetRadiusServers sets RadiusServers field to given value.


### GetUserNameLabel

`func (o *RADIUSAuthenticatorCreateSpec) GetUserNameLabel() string`

GetUserNameLabel returns the UserNameLabel field if non-nil, zero value otherwise.

### GetUserNameLabelOk

`func (o *RADIUSAuthenticatorCreateSpec) GetUserNameLabelOk() (*string, bool)`

GetUserNameLabelOk returns a tuple with the UserNameLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserNameLabel

`func (o *RADIUSAuthenticatorCreateSpec) SetUserNameLabel(v string)`

SetUserNameLabel sets UserNameLabel field to given value.

### HasUserNameLabel

`func (o *RADIUSAuthenticatorCreateSpec) HasUserNameLabel() bool`

HasUserNameLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


