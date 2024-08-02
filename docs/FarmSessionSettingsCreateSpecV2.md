# FarmSessionSettingsCreateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DisconnectedSessionTimeoutMinutes** | Pointer to **int32** | Disconnected sessions timeout (in minutes). An empty disconnected session is logged off after the timeout. This is required if the disconnect_session_timeout_policy is set to AFTER. | [optional] 
**DisconnectedSessionTimeoutPolicy** | Pointer to **string** | Log-off policy after disconnected session. Default value is NEVER.  * IMMEDIATELY: Immediately Logoff after user disconnect. * AFTER: Logoff after the specified number of minutes after user disconnect. * NEVER: Do not logoff after user disconnect. | [optional] 
**EmptySessionTimeoutMinutes** | Pointer to **int32** | Application empty session timeout (in minutes). An empty session (that has no remote-able window) is disconnected after the timeout. Default value is 1. This is required if the empty_session_timeout_policy is set to AFTER. | [optional] 
**EmptySessionTimeoutPolicy** | Pointer to **string** | Application empty session timeout policy. Default value is AFTER * IMMEDIATE: Empty session will be disconnected immediately. * NEVER: Empty session will never disconnected. * AFTER: Empty session will be disconnected after specified number of minutes. | [optional] 
**LogoffAfterTimeout** | Pointer to **bool** | Indicates whether the empty application sessions are logged off (true) or disconnected (false) after timeout. Default value is false if emptySessionTimeoutPolicy is set to AFTER or IMMEDIATE. | [optional] 
**PreLaunchSessionTimeoutMinutes** | Pointer to **int32** | Application pre-launch session timeout (in minutes). A pre-launch session is disconnected after the timeout. Default value is 10. This is required if pre_launch_session_timeout_policy is set to AFTER. | [optional] 
**PreLaunchSessionTimeoutPolicy** | Pointer to **string** | Application pre-launch session timeout policy. Default value is AFTER * AFTER: Pre-launched session is disconnected after specified number of minutes. * NEVER: Pre-launched session is never disconnected. | [optional] 
**SessionTimeoutPolicy** | Pointer to **string** | Specifies the session timeout policy for the applications published from the Farm. This policy indicates whether the launched application session is a forever application session or not. Default value is DEFAULT. * DEFAULT: Indicates application sessions will be disconnected either on reaching the global idle timeout or on reaching the max session timeout. * NEVER: Indicates application sessions will not be disconnected either on reaching the global idle timeout or on reaching the max session timeout. | [optional] 

## Methods

### NewFarmSessionSettingsCreateSpecV2

`func NewFarmSessionSettingsCreateSpecV2() *FarmSessionSettingsCreateSpecV2`

NewFarmSessionSettingsCreateSpecV2 instantiates a new FarmSessionSettingsCreateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmSessionSettingsCreateSpecV2WithDefaults

`func NewFarmSessionSettingsCreateSpecV2WithDefaults() *FarmSessionSettingsCreateSpecV2`

NewFarmSessionSettingsCreateSpecV2WithDefaults instantiates a new FarmSessionSettingsCreateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDisconnectedSessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) GetDisconnectedSessionTimeoutMinutes() int32`

GetDisconnectedSessionTimeoutMinutes returns the DisconnectedSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetDisconnectedSessionTimeoutMinutesOk

`func (o *FarmSessionSettingsCreateSpecV2) GetDisconnectedSessionTimeoutMinutesOk() (*int32, bool)`

GetDisconnectedSessionTimeoutMinutesOk returns a tuple with the DisconnectedSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisconnectedSessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) SetDisconnectedSessionTimeoutMinutes(v int32)`

SetDisconnectedSessionTimeoutMinutes sets DisconnectedSessionTimeoutMinutes field to given value.

### HasDisconnectedSessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) HasDisconnectedSessionTimeoutMinutes() bool`

HasDisconnectedSessionTimeoutMinutes returns a boolean if a field has been set.

### GetDisconnectedSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) GetDisconnectedSessionTimeoutPolicy() string`

GetDisconnectedSessionTimeoutPolicy returns the DisconnectedSessionTimeoutPolicy field if non-nil, zero value otherwise.

### GetDisconnectedSessionTimeoutPolicyOk

`func (o *FarmSessionSettingsCreateSpecV2) GetDisconnectedSessionTimeoutPolicyOk() (*string, bool)`

GetDisconnectedSessionTimeoutPolicyOk returns a tuple with the DisconnectedSessionTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisconnectedSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) SetDisconnectedSessionTimeoutPolicy(v string)`

SetDisconnectedSessionTimeoutPolicy sets DisconnectedSessionTimeoutPolicy field to given value.

### HasDisconnectedSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) HasDisconnectedSessionTimeoutPolicy() bool`

HasDisconnectedSessionTimeoutPolicy returns a boolean if a field has been set.

### GetEmptySessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) GetEmptySessionTimeoutMinutes() int32`

GetEmptySessionTimeoutMinutes returns the EmptySessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetEmptySessionTimeoutMinutesOk

`func (o *FarmSessionSettingsCreateSpecV2) GetEmptySessionTimeoutMinutesOk() (*int32, bool)`

GetEmptySessionTimeoutMinutesOk returns a tuple with the EmptySessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmptySessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) SetEmptySessionTimeoutMinutes(v int32)`

SetEmptySessionTimeoutMinutes sets EmptySessionTimeoutMinutes field to given value.

### HasEmptySessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) HasEmptySessionTimeoutMinutes() bool`

HasEmptySessionTimeoutMinutes returns a boolean if a field has been set.

### GetEmptySessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) GetEmptySessionTimeoutPolicy() string`

GetEmptySessionTimeoutPolicy returns the EmptySessionTimeoutPolicy field if non-nil, zero value otherwise.

### GetEmptySessionTimeoutPolicyOk

`func (o *FarmSessionSettingsCreateSpecV2) GetEmptySessionTimeoutPolicyOk() (*string, bool)`

GetEmptySessionTimeoutPolicyOk returns a tuple with the EmptySessionTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmptySessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) SetEmptySessionTimeoutPolicy(v string)`

SetEmptySessionTimeoutPolicy sets EmptySessionTimeoutPolicy field to given value.

### HasEmptySessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) HasEmptySessionTimeoutPolicy() bool`

HasEmptySessionTimeoutPolicy returns a boolean if a field has been set.

### GetLogoffAfterTimeout

`func (o *FarmSessionSettingsCreateSpecV2) GetLogoffAfterTimeout() bool`

GetLogoffAfterTimeout returns the LogoffAfterTimeout field if non-nil, zero value otherwise.

### GetLogoffAfterTimeoutOk

`func (o *FarmSessionSettingsCreateSpecV2) GetLogoffAfterTimeoutOk() (*bool, bool)`

GetLogoffAfterTimeoutOk returns a tuple with the LogoffAfterTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoffAfterTimeout

`func (o *FarmSessionSettingsCreateSpecV2) SetLogoffAfterTimeout(v bool)`

SetLogoffAfterTimeout sets LogoffAfterTimeout field to given value.

### HasLogoffAfterTimeout

`func (o *FarmSessionSettingsCreateSpecV2) HasLogoffAfterTimeout() bool`

HasLogoffAfterTimeout returns a boolean if a field has been set.

### GetPreLaunchSessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) GetPreLaunchSessionTimeoutMinutes() int32`

GetPreLaunchSessionTimeoutMinutes returns the PreLaunchSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetPreLaunchSessionTimeoutMinutesOk

`func (o *FarmSessionSettingsCreateSpecV2) GetPreLaunchSessionTimeoutMinutesOk() (*int32, bool)`

GetPreLaunchSessionTimeoutMinutesOk returns a tuple with the PreLaunchSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreLaunchSessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) SetPreLaunchSessionTimeoutMinutes(v int32)`

SetPreLaunchSessionTimeoutMinutes sets PreLaunchSessionTimeoutMinutes field to given value.

### HasPreLaunchSessionTimeoutMinutes

`func (o *FarmSessionSettingsCreateSpecV2) HasPreLaunchSessionTimeoutMinutes() bool`

HasPreLaunchSessionTimeoutMinutes returns a boolean if a field has been set.

### GetPreLaunchSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) GetPreLaunchSessionTimeoutPolicy() string`

GetPreLaunchSessionTimeoutPolicy returns the PreLaunchSessionTimeoutPolicy field if non-nil, zero value otherwise.

### GetPreLaunchSessionTimeoutPolicyOk

`func (o *FarmSessionSettingsCreateSpecV2) GetPreLaunchSessionTimeoutPolicyOk() (*string, bool)`

GetPreLaunchSessionTimeoutPolicyOk returns a tuple with the PreLaunchSessionTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreLaunchSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) SetPreLaunchSessionTimeoutPolicy(v string)`

SetPreLaunchSessionTimeoutPolicy sets PreLaunchSessionTimeoutPolicy field to given value.

### HasPreLaunchSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) HasPreLaunchSessionTimeoutPolicy() bool`

HasPreLaunchSessionTimeoutPolicy returns a boolean if a field has been set.

### GetSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) GetSessionTimeoutPolicy() string`

GetSessionTimeoutPolicy returns the SessionTimeoutPolicy field if non-nil, zero value otherwise.

### GetSessionTimeoutPolicyOk

`func (o *FarmSessionSettingsCreateSpecV2) GetSessionTimeoutPolicyOk() (*string, bool)`

GetSessionTimeoutPolicyOk returns a tuple with the SessionTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) SetSessionTimeoutPolicy(v string)`

SetSessionTimeoutPolicy sets SessionTimeoutPolicy field to given value.

### HasSessionTimeoutPolicy

`func (o *FarmSessionSettingsCreateSpecV2) HasSessionTimeoutPolicy() bool`

HasSessionTimeoutPolicy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


