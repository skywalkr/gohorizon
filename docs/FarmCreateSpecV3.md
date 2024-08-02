# FarmCreateSpecV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessGroupId** | **string** | Access groups can organize the entities such as farms in the organization. They can also be used for delegated administration. | 
**AutomatedFarmSettings** | Pointer to [**FarmAutomatedSettingsCreateSpecV3**](FarmAutomatedSettingsCreateSpecV3.md) |  | [optional] 
**Description** | Pointer to **string** | Description of the farm. | [optional] 
**DisplayName** | Pointer to **string** | Display name of the farm. If the display name is left blank, it defaults to name. | [optional] 
**DisplayProtocolSettings** | Pointer to [**FarmDisplayProtocolSettingsCreateSpec**](FarmDisplayProtocolSettingsCreateSpec.md) |  | [optional] 
**Enabled** | Pointer to **bool** | Indicates whether the farm is enabled for brokering. Default value is true. | [optional] 
**LoadBalancerSettings** | Pointer to [**RDSHLoadBalancerSettingsCreateSpecV2**](RDSHLoadBalancerSettingsCreateSpecV2.md) |  | [optional] 
**Name** | **string** | Name of the farm. This property must contain only alphanumerics, underscores, and dashes. | 
**RdsServerIds** | Pointer to **[]string** | List of IDs of RDS Servers in the Manual Farm. This is applicable if type is set to MANUAL. | [optional] 
**ServerErrorThreshold** | Pointer to **int32** | The minimum number of machines that must be fully operational in order to avoid showing the farm in an error state. Default value is 0. | [optional] 
**SessionSettings** | Pointer to [**FarmSessionSettingsCreateSpecV2**](FarmSessionSettingsCreateSpecV2.md) |  | [optional] 
**Type** | **string** | Type of the farm. * AUTOMATED: Automated Farm. * MANUAL: Manual Farm. | 
**UseCustomScriptForLoadBalancing** | Pointer to **bool** | Indicates whether to use custom scripts for load balancing or not. Default value is false. | [optional] 

## Methods

### NewFarmCreateSpecV3

`func NewFarmCreateSpecV3(accessGroupId string, name string, type_ string, ) *FarmCreateSpecV3`

NewFarmCreateSpecV3 instantiates a new FarmCreateSpecV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmCreateSpecV3WithDefaults

`func NewFarmCreateSpecV3WithDefaults() *FarmCreateSpecV3`

NewFarmCreateSpecV3WithDefaults instantiates a new FarmCreateSpecV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessGroupId

`func (o *FarmCreateSpecV3) GetAccessGroupId() string`

GetAccessGroupId returns the AccessGroupId field if non-nil, zero value otherwise.

### GetAccessGroupIdOk

`func (o *FarmCreateSpecV3) GetAccessGroupIdOk() (*string, bool)`

GetAccessGroupIdOk returns a tuple with the AccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessGroupId

`func (o *FarmCreateSpecV3) SetAccessGroupId(v string)`

SetAccessGroupId sets AccessGroupId field to given value.


### GetAutomatedFarmSettings

`func (o *FarmCreateSpecV3) GetAutomatedFarmSettings() FarmAutomatedSettingsCreateSpecV3`

GetAutomatedFarmSettings returns the AutomatedFarmSettings field if non-nil, zero value otherwise.

### GetAutomatedFarmSettingsOk

`func (o *FarmCreateSpecV3) GetAutomatedFarmSettingsOk() (*FarmAutomatedSettingsCreateSpecV3, bool)`

GetAutomatedFarmSettingsOk returns a tuple with the AutomatedFarmSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomatedFarmSettings

`func (o *FarmCreateSpecV3) SetAutomatedFarmSettings(v FarmAutomatedSettingsCreateSpecV3)`

SetAutomatedFarmSettings sets AutomatedFarmSettings field to given value.

### HasAutomatedFarmSettings

`func (o *FarmCreateSpecV3) HasAutomatedFarmSettings() bool`

HasAutomatedFarmSettings returns a boolean if a field has been set.

### GetDescription

`func (o *FarmCreateSpecV3) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *FarmCreateSpecV3) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *FarmCreateSpecV3) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *FarmCreateSpecV3) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDisplayName

`func (o *FarmCreateSpecV3) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *FarmCreateSpecV3) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *FarmCreateSpecV3) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *FarmCreateSpecV3) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetDisplayProtocolSettings

`func (o *FarmCreateSpecV3) GetDisplayProtocolSettings() FarmDisplayProtocolSettingsCreateSpec`

GetDisplayProtocolSettings returns the DisplayProtocolSettings field if non-nil, zero value otherwise.

### GetDisplayProtocolSettingsOk

`func (o *FarmCreateSpecV3) GetDisplayProtocolSettingsOk() (*FarmDisplayProtocolSettingsCreateSpec, bool)`

GetDisplayProtocolSettingsOk returns a tuple with the DisplayProtocolSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayProtocolSettings

`func (o *FarmCreateSpecV3) SetDisplayProtocolSettings(v FarmDisplayProtocolSettingsCreateSpec)`

SetDisplayProtocolSettings sets DisplayProtocolSettings field to given value.

### HasDisplayProtocolSettings

`func (o *FarmCreateSpecV3) HasDisplayProtocolSettings() bool`

HasDisplayProtocolSettings returns a boolean if a field has been set.

### GetEnabled

`func (o *FarmCreateSpecV3) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FarmCreateSpecV3) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FarmCreateSpecV3) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *FarmCreateSpecV3) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetLoadBalancerSettings

`func (o *FarmCreateSpecV3) GetLoadBalancerSettings() RDSHLoadBalancerSettingsCreateSpecV2`

GetLoadBalancerSettings returns the LoadBalancerSettings field if non-nil, zero value otherwise.

### GetLoadBalancerSettingsOk

`func (o *FarmCreateSpecV3) GetLoadBalancerSettingsOk() (*RDSHLoadBalancerSettingsCreateSpecV2, bool)`

GetLoadBalancerSettingsOk returns a tuple with the LoadBalancerSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadBalancerSettings

`func (o *FarmCreateSpecV3) SetLoadBalancerSettings(v RDSHLoadBalancerSettingsCreateSpecV2)`

SetLoadBalancerSettings sets LoadBalancerSettings field to given value.

### HasLoadBalancerSettings

`func (o *FarmCreateSpecV3) HasLoadBalancerSettings() bool`

HasLoadBalancerSettings returns a boolean if a field has been set.

### GetName

`func (o *FarmCreateSpecV3) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FarmCreateSpecV3) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FarmCreateSpecV3) SetName(v string)`

SetName sets Name field to given value.


### GetRdsServerIds

`func (o *FarmCreateSpecV3) GetRdsServerIds() []string`

GetRdsServerIds returns the RdsServerIds field if non-nil, zero value otherwise.

### GetRdsServerIdsOk

`func (o *FarmCreateSpecV3) GetRdsServerIdsOk() (*[]string, bool)`

GetRdsServerIdsOk returns a tuple with the RdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRdsServerIds

`func (o *FarmCreateSpecV3) SetRdsServerIds(v []string)`

SetRdsServerIds sets RdsServerIds field to given value.

### HasRdsServerIds

`func (o *FarmCreateSpecV3) HasRdsServerIds() bool`

HasRdsServerIds returns a boolean if a field has been set.

### GetServerErrorThreshold

`func (o *FarmCreateSpecV3) GetServerErrorThreshold() int32`

GetServerErrorThreshold returns the ServerErrorThreshold field if non-nil, zero value otherwise.

### GetServerErrorThresholdOk

`func (o *FarmCreateSpecV3) GetServerErrorThresholdOk() (*int32, bool)`

GetServerErrorThresholdOk returns a tuple with the ServerErrorThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerErrorThreshold

`func (o *FarmCreateSpecV3) SetServerErrorThreshold(v int32)`

SetServerErrorThreshold sets ServerErrorThreshold field to given value.

### HasServerErrorThreshold

`func (o *FarmCreateSpecV3) HasServerErrorThreshold() bool`

HasServerErrorThreshold returns a boolean if a field has been set.

### GetSessionSettings

`func (o *FarmCreateSpecV3) GetSessionSettings() FarmSessionSettingsCreateSpecV2`

GetSessionSettings returns the SessionSettings field if non-nil, zero value otherwise.

### GetSessionSettingsOk

`func (o *FarmCreateSpecV3) GetSessionSettingsOk() (*FarmSessionSettingsCreateSpecV2, bool)`

GetSessionSettingsOk returns a tuple with the SessionSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionSettings

`func (o *FarmCreateSpecV3) SetSessionSettings(v FarmSessionSettingsCreateSpecV2)`

SetSessionSettings sets SessionSettings field to given value.

### HasSessionSettings

`func (o *FarmCreateSpecV3) HasSessionSettings() bool`

HasSessionSettings returns a boolean if a field has been set.

### GetType

`func (o *FarmCreateSpecV3) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *FarmCreateSpecV3) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *FarmCreateSpecV3) SetType(v string)`

SetType sets Type field to given value.


### GetUseCustomScriptForLoadBalancing

`func (o *FarmCreateSpecV3) GetUseCustomScriptForLoadBalancing() bool`

GetUseCustomScriptForLoadBalancing returns the UseCustomScriptForLoadBalancing field if non-nil, zero value otherwise.

### GetUseCustomScriptForLoadBalancingOk

`func (o *FarmCreateSpecV3) GetUseCustomScriptForLoadBalancingOk() (*bool, bool)`

GetUseCustomScriptForLoadBalancingOk returns a tuple with the UseCustomScriptForLoadBalancing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCustomScriptForLoadBalancing

`func (o *FarmCreateSpecV3) SetUseCustomScriptForLoadBalancing(v bool)`

SetUseCustomScriptForLoadBalancing sets UseCustomScriptForLoadBalancing field to given value.

### HasUseCustomScriptForLoadBalancing

`func (o *FarmCreateSpecV3) HasUseCustomScriptForLoadBalancing() bool`

HasUseCustomScriptForLoadBalancing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


