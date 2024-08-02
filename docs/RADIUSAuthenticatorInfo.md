# RADIUSAuthenticatorInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The description for this RADIUS authenticator. | [optional] 
**Id** | Pointer to **string** | Unique ID representing this RADIUS Authenticator. | [optional] 
**Label** | Pointer to **string** | The label for this RADIUS authenticator. | [optional] 
**PasscodeLabel** | Pointer to **string** | The label for the RADIUS authenticator passcode. | [optional] 
**RadiusServers** | Pointer to [**[]RADIUSServerInfo**](RADIUSServerInfo.md) | List of RADIUS servers. | [optional] 
**UserNameLabel** | Pointer to **string** | The label for the RADIUS authenticator user name. | [optional] 

## Methods

### NewRADIUSAuthenticatorInfo

`func NewRADIUSAuthenticatorInfo() *RADIUSAuthenticatorInfo`

NewRADIUSAuthenticatorInfo instantiates a new RADIUSAuthenticatorInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRADIUSAuthenticatorInfoWithDefaults

`func NewRADIUSAuthenticatorInfoWithDefaults() *RADIUSAuthenticatorInfo`

NewRADIUSAuthenticatorInfoWithDefaults instantiates a new RADIUSAuthenticatorInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *RADIUSAuthenticatorInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RADIUSAuthenticatorInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RADIUSAuthenticatorInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RADIUSAuthenticatorInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *RADIUSAuthenticatorInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RADIUSAuthenticatorInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RADIUSAuthenticatorInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *RADIUSAuthenticatorInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLabel

`func (o *RADIUSAuthenticatorInfo) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *RADIUSAuthenticatorInfo) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *RADIUSAuthenticatorInfo) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *RADIUSAuthenticatorInfo) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetPasscodeLabel

`func (o *RADIUSAuthenticatorInfo) GetPasscodeLabel() string`

GetPasscodeLabel returns the PasscodeLabel field if non-nil, zero value otherwise.

### GetPasscodeLabelOk

`func (o *RADIUSAuthenticatorInfo) GetPasscodeLabelOk() (*string, bool)`

GetPasscodeLabelOk returns a tuple with the PasscodeLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasscodeLabel

`func (o *RADIUSAuthenticatorInfo) SetPasscodeLabel(v string)`

SetPasscodeLabel sets PasscodeLabel field to given value.

### HasPasscodeLabel

`func (o *RADIUSAuthenticatorInfo) HasPasscodeLabel() bool`

HasPasscodeLabel returns a boolean if a field has been set.

### GetRadiusServers

`func (o *RADIUSAuthenticatorInfo) GetRadiusServers() []RADIUSServerInfo`

GetRadiusServers returns the RadiusServers field if non-nil, zero value otherwise.

### GetRadiusServersOk

`func (o *RADIUSAuthenticatorInfo) GetRadiusServersOk() (*[]RADIUSServerInfo, bool)`

GetRadiusServersOk returns a tuple with the RadiusServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusServers

`func (o *RADIUSAuthenticatorInfo) SetRadiusServers(v []RADIUSServerInfo)`

SetRadiusServers sets RadiusServers field to given value.

### HasRadiusServers

`func (o *RADIUSAuthenticatorInfo) HasRadiusServers() bool`

HasRadiusServers returns a boolean if a field has been set.

### GetUserNameLabel

`func (o *RADIUSAuthenticatorInfo) GetUserNameLabel() string`

GetUserNameLabel returns the UserNameLabel field if non-nil, zero value otherwise.

### GetUserNameLabelOk

`func (o *RADIUSAuthenticatorInfo) GetUserNameLabelOk() (*string, bool)`

GetUserNameLabelOk returns a tuple with the UserNameLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserNameLabel

`func (o *RADIUSAuthenticatorInfo) SetUserNameLabel(v string)`

SetUserNameLabel sets UserNameLabel field to given value.

### HasUserNameLabel

`func (o *RADIUSAuthenticatorInfo) HasUserNameLabel() bool`

HasUserNameLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


