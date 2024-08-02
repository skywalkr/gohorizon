# RADIUSAuthenticatorUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The description for this RADIUS authenticator. | [optional] 
**Label** | **string** | The label for this RADIUS authenticator. It must be unique among all other RADIUS authenticators. | 
**PasscodeLabel** | Pointer to **string** | The label for the RADIUS authenticator passcode. | [optional] 
**RadiusServers** | [**[]RADIUSServerUpdateSpec**](RADIUSServerUpdateSpec.md) | List of RADIUS servers. The list must have exactly one primary RADIUS server i.e. with primary_radius_server set to true. | 
**UserNameLabel** | Pointer to **string** | The label for the RADIUS authenticator user name. | [optional] 

## Methods

### NewRADIUSAuthenticatorUpdateSpec

`func NewRADIUSAuthenticatorUpdateSpec(label string, radiusServers []RADIUSServerUpdateSpec, ) *RADIUSAuthenticatorUpdateSpec`

NewRADIUSAuthenticatorUpdateSpec instantiates a new RADIUSAuthenticatorUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRADIUSAuthenticatorUpdateSpecWithDefaults

`func NewRADIUSAuthenticatorUpdateSpecWithDefaults() *RADIUSAuthenticatorUpdateSpec`

NewRADIUSAuthenticatorUpdateSpecWithDefaults instantiates a new RADIUSAuthenticatorUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *RADIUSAuthenticatorUpdateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RADIUSAuthenticatorUpdateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RADIUSAuthenticatorUpdateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RADIUSAuthenticatorUpdateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLabel

`func (o *RADIUSAuthenticatorUpdateSpec) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *RADIUSAuthenticatorUpdateSpec) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *RADIUSAuthenticatorUpdateSpec) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetPasscodeLabel

`func (o *RADIUSAuthenticatorUpdateSpec) GetPasscodeLabel() string`

GetPasscodeLabel returns the PasscodeLabel field if non-nil, zero value otherwise.

### GetPasscodeLabelOk

`func (o *RADIUSAuthenticatorUpdateSpec) GetPasscodeLabelOk() (*string, bool)`

GetPasscodeLabelOk returns a tuple with the PasscodeLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasscodeLabel

`func (o *RADIUSAuthenticatorUpdateSpec) SetPasscodeLabel(v string)`

SetPasscodeLabel sets PasscodeLabel field to given value.

### HasPasscodeLabel

`func (o *RADIUSAuthenticatorUpdateSpec) HasPasscodeLabel() bool`

HasPasscodeLabel returns a boolean if a field has been set.

### GetRadiusServers

`func (o *RADIUSAuthenticatorUpdateSpec) GetRadiusServers() []RADIUSServerUpdateSpec`

GetRadiusServers returns the RadiusServers field if non-nil, zero value otherwise.

### GetRadiusServersOk

`func (o *RADIUSAuthenticatorUpdateSpec) GetRadiusServersOk() (*[]RADIUSServerUpdateSpec, bool)`

GetRadiusServersOk returns a tuple with the RadiusServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusServers

`func (o *RADIUSAuthenticatorUpdateSpec) SetRadiusServers(v []RADIUSServerUpdateSpec)`

SetRadiusServers sets RadiusServers field to given value.


### GetUserNameLabel

`func (o *RADIUSAuthenticatorUpdateSpec) GetUserNameLabel() string`

GetUserNameLabel returns the UserNameLabel field if non-nil, zero value otherwise.

### GetUserNameLabelOk

`func (o *RADIUSAuthenticatorUpdateSpec) GetUserNameLabelOk() (*string, bool)`

GetUserNameLabelOk returns a tuple with the UserNameLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserNameLabel

`func (o *RADIUSAuthenticatorUpdateSpec) SetUserNameLabel(v string)`

SetUserNameLabel sets UserNameLabel field to given value.

### HasUserNameLabel

`func (o *RADIUSAuthenticatorUpdateSpec) HasUserNameLabel() bool`

HasUserNameLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


