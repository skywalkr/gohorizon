# DesktopPoolNetworkLabelAssignmentSettingsCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **bool** | Indicates whether or not this specification is enabled. While this specification is disabled, automatic network label assigment for this desktop pool will skip over the network label in this spec. &lt;br&gt; Default value is true. &lt;br&gt; | [optional] 
**MaxLabel** | Pointer to **int32** | The maximum number of times this network label can be assigned to a machine. &lt;br&gt; | [optional] 
**MaxLabelType** | **string** | The property specifies whether or not there is a maximum limit to the number of times this label may be assigned to machines within this spec. * UNLIMITED: The network label assignment specification has no limit on the number of labels to assign. * LIMITED: The network label assignment specification has a limited number of labels to assign. | 
**NetworkLabelName** | **string** | The network label name. &lt;br&gt; | 

## Methods

### NewDesktopPoolNetworkLabelAssignmentSettingsCreateSpec

`func NewDesktopPoolNetworkLabelAssignmentSettingsCreateSpec(maxLabelType string, networkLabelName string, ) *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec`

NewDesktopPoolNetworkLabelAssignmentSettingsCreateSpec instantiates a new DesktopPoolNetworkLabelAssignmentSettingsCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesktopPoolNetworkLabelAssignmentSettingsCreateSpecWithDefaults

`func NewDesktopPoolNetworkLabelAssignmentSettingsCreateSpecWithDefaults() *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec`

NewDesktopPoolNetworkLabelAssignmentSettingsCreateSpecWithDefaults instantiates a new DesktopPoolNetworkLabelAssignmentSettingsCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetMaxLabel

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetMaxLabel() int32`

GetMaxLabel returns the MaxLabel field if non-nil, zero value otherwise.

### GetMaxLabelOk

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetMaxLabelOk() (*int32, bool)`

GetMaxLabelOk returns a tuple with the MaxLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLabel

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) SetMaxLabel(v int32)`

SetMaxLabel sets MaxLabel field to given value.

### HasMaxLabel

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) HasMaxLabel() bool`

HasMaxLabel returns a boolean if a field has been set.

### GetMaxLabelType

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetMaxLabelType() string`

GetMaxLabelType returns the MaxLabelType field if non-nil, zero value otherwise.

### GetMaxLabelTypeOk

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetMaxLabelTypeOk() (*string, bool)`

GetMaxLabelTypeOk returns a tuple with the MaxLabelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLabelType

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) SetMaxLabelType(v string)`

SetMaxLabelType sets MaxLabelType field to given value.


### GetNetworkLabelName

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetNetworkLabelName() string`

GetNetworkLabelName returns the NetworkLabelName field if non-nil, zero value otherwise.

### GetNetworkLabelNameOk

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) GetNetworkLabelNameOk() (*string, bool)`

GetNetworkLabelNameOk returns a tuple with the NetworkLabelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkLabelName

`func (o *DesktopPoolNetworkLabelAssignmentSettingsCreateSpec) SetNetworkLabelName(v string)`

SetNetworkLabelName sets NetworkLabelName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


