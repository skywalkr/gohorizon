# FarmUpdateSpecV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessGroupId** | **string** | Access groups can organize the entities such as farms in the organization. They can also be used for delegated administration. | 
**AutomatedFarmSettings** | Pointer to [**FarmAutomatedSettingsUpdateSpecV2**](FarmAutomatedSettingsUpdateSpecV2.md) |  | [optional] 
**Description** | Pointer to **string** | Description of the farm. | [optional] 
**DisplayName** | **string** | Display name of the farm. | 
**DisplayProtocolSettings** | [**FarmDisplayProtocolSettingsUpdateSpec**](FarmDisplayProtocolSettingsUpdateSpec.md) |  | 
**Enabled** | **bool** | Indicates whether the farm is enabled for brokering. | 
**LoadBalancerSettings** | [**RDSHLoadBalancerSettingsUpdateSpecV2**](RDSHLoadBalancerSettingsUpdateSpecV2.md) |  | 
**ServerErrorThreshold** | **int32** | The minimum number of machines that must be fully operational in order to avoid showing the farm in an error state.  | 
**SessionSettings** | [**FarmSessionSettingsUpdateSpecV2**](FarmSessionSettingsUpdateSpecV2.md) |  | 
**UseCustomScriptForLoadBalancing** | **bool** | Indicates whether to use custom scripts for load balancing or not.  | 

## Methods

### NewFarmUpdateSpecV3

`func NewFarmUpdateSpecV3(accessGroupId string, displayName string, displayProtocolSettings FarmDisplayProtocolSettingsUpdateSpec, enabled bool, loadBalancerSettings RDSHLoadBalancerSettingsUpdateSpecV2, serverErrorThreshold int32, sessionSettings FarmSessionSettingsUpdateSpecV2, useCustomScriptForLoadBalancing bool, ) *FarmUpdateSpecV3`

NewFarmUpdateSpecV3 instantiates a new FarmUpdateSpecV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmUpdateSpecV3WithDefaults

`func NewFarmUpdateSpecV3WithDefaults() *FarmUpdateSpecV3`

NewFarmUpdateSpecV3WithDefaults instantiates a new FarmUpdateSpecV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessGroupId

`func (o *FarmUpdateSpecV3) GetAccessGroupId() string`

GetAccessGroupId returns the AccessGroupId field if non-nil, zero value otherwise.

### GetAccessGroupIdOk

`func (o *FarmUpdateSpecV3) GetAccessGroupIdOk() (*string, bool)`

GetAccessGroupIdOk returns a tuple with the AccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessGroupId

`func (o *FarmUpdateSpecV3) SetAccessGroupId(v string)`

SetAccessGroupId sets AccessGroupId field to given value.


### GetAutomatedFarmSettings

`func (o *FarmUpdateSpecV3) GetAutomatedFarmSettings() FarmAutomatedSettingsUpdateSpecV2`

GetAutomatedFarmSettings returns the AutomatedFarmSettings field if non-nil, zero value otherwise.

### GetAutomatedFarmSettingsOk

`func (o *FarmUpdateSpecV3) GetAutomatedFarmSettingsOk() (*FarmAutomatedSettingsUpdateSpecV2, bool)`

GetAutomatedFarmSettingsOk returns a tuple with the AutomatedFarmSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomatedFarmSettings

`func (o *FarmUpdateSpecV3) SetAutomatedFarmSettings(v FarmAutomatedSettingsUpdateSpecV2)`

SetAutomatedFarmSettings sets AutomatedFarmSettings field to given value.

### HasAutomatedFarmSettings

`func (o *FarmUpdateSpecV3) HasAutomatedFarmSettings() bool`

HasAutomatedFarmSettings returns a boolean if a field has been set.

### GetDescription

`func (o *FarmUpdateSpecV3) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *FarmUpdateSpecV3) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *FarmUpdateSpecV3) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *FarmUpdateSpecV3) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDisplayName

`func (o *FarmUpdateSpecV3) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *FarmUpdateSpecV3) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *FarmUpdateSpecV3) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.


### GetDisplayProtocolSettings

`func (o *FarmUpdateSpecV3) GetDisplayProtocolSettings() FarmDisplayProtocolSettingsUpdateSpec`

GetDisplayProtocolSettings returns the DisplayProtocolSettings field if non-nil, zero value otherwise.

### GetDisplayProtocolSettingsOk

`func (o *FarmUpdateSpecV3) GetDisplayProtocolSettingsOk() (*FarmDisplayProtocolSettingsUpdateSpec, bool)`

GetDisplayProtocolSettingsOk returns a tuple with the DisplayProtocolSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayProtocolSettings

`func (o *FarmUpdateSpecV3) SetDisplayProtocolSettings(v FarmDisplayProtocolSettingsUpdateSpec)`

SetDisplayProtocolSettings sets DisplayProtocolSettings field to given value.


### GetEnabled

`func (o *FarmUpdateSpecV3) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FarmUpdateSpecV3) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FarmUpdateSpecV3) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetLoadBalancerSettings

`func (o *FarmUpdateSpecV3) GetLoadBalancerSettings() RDSHLoadBalancerSettingsUpdateSpecV2`

GetLoadBalancerSettings returns the LoadBalancerSettings field if non-nil, zero value otherwise.

### GetLoadBalancerSettingsOk

`func (o *FarmUpdateSpecV3) GetLoadBalancerSettingsOk() (*RDSHLoadBalancerSettingsUpdateSpecV2, bool)`

GetLoadBalancerSettingsOk returns a tuple with the LoadBalancerSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadBalancerSettings

`func (o *FarmUpdateSpecV3) SetLoadBalancerSettings(v RDSHLoadBalancerSettingsUpdateSpecV2)`

SetLoadBalancerSettings sets LoadBalancerSettings field to given value.


### GetServerErrorThreshold

`func (o *FarmUpdateSpecV3) GetServerErrorThreshold() int32`

GetServerErrorThreshold returns the ServerErrorThreshold field if non-nil, zero value otherwise.

### GetServerErrorThresholdOk

`func (o *FarmUpdateSpecV3) GetServerErrorThresholdOk() (*int32, bool)`

GetServerErrorThresholdOk returns a tuple with the ServerErrorThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerErrorThreshold

`func (o *FarmUpdateSpecV3) SetServerErrorThreshold(v int32)`

SetServerErrorThreshold sets ServerErrorThreshold field to given value.


### GetSessionSettings

`func (o *FarmUpdateSpecV3) GetSessionSettings() FarmSessionSettingsUpdateSpecV2`

GetSessionSettings returns the SessionSettings field if non-nil, zero value otherwise.

### GetSessionSettingsOk

`func (o *FarmUpdateSpecV3) GetSessionSettingsOk() (*FarmSessionSettingsUpdateSpecV2, bool)`

GetSessionSettingsOk returns a tuple with the SessionSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionSettings

`func (o *FarmUpdateSpecV3) SetSessionSettings(v FarmSessionSettingsUpdateSpecV2)`

SetSessionSettings sets SessionSettings field to given value.


### GetUseCustomScriptForLoadBalancing

`func (o *FarmUpdateSpecV3) GetUseCustomScriptForLoadBalancing() bool`

GetUseCustomScriptForLoadBalancing returns the UseCustomScriptForLoadBalancing field if non-nil, zero value otherwise.

### GetUseCustomScriptForLoadBalancingOk

`func (o *FarmUpdateSpecV3) GetUseCustomScriptForLoadBalancingOk() (*bool, bool)`

GetUseCustomScriptForLoadBalancingOk returns a tuple with the UseCustomScriptForLoadBalancing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCustomScriptForLoadBalancing

`func (o *FarmUpdateSpecV3) SetUseCustomScriptForLoadBalancing(v bool)`

SetUseCustomScriptForLoadBalancing sets UseCustomScriptForLoadBalancing field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


