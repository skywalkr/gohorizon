# DesktopPoolNetworkInterfaceCardSettingsUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NetworkInterfaceCardId** | **string** | The network interface card id for these settings. | 
**NetworkLabelAssignmentSpecs** | Pointer to [**[]DesktopPoolNetworkLabelAssignmentSettingsUpdateSpec**](DesktopPoolNetworkLabelAssignmentSettingsUpdateSpec.md) | Automatic network label assignment feature settings for this NIC. If network_label_assignment_specs is not set, nics will be ignored. By default, newly provisioned machines of an automated desktop pool retain their parent image&#39;s network labels on each of their network interface cards. In certain circumstances, notably dealing with VLAN subset sizing and DHCP IP address availability, it may be desirable for the desktop pool to instead use different network labels for these newly provisioned machines. This feature allows an administrator to provide a per NIC list of network labels and their maximum availability to be automatically distributed to newly provisioned machines. &lt;br&gt; If this is unset, the feature is disabled.&lt;br&gt; Starting at the alphabetically first network label specification in the list that has not yet been assigned its maximum count for this NIC on this desktop pool, the desktop pool will have its next provisioned machine&#39;s NIC assigned that label. If all network labels in this list have reached their maximum count, this desktop pool will have further provisioned machines assigned the last label in the list over capacity, and an error will be logged. Not all labels need be configured. &lt;br&gt; | [optional] 

## Methods

### NewDesktopPoolNetworkInterfaceCardSettingsUpdateSpec

`func NewDesktopPoolNetworkInterfaceCardSettingsUpdateSpec(networkInterfaceCardId string, ) *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec`

NewDesktopPoolNetworkInterfaceCardSettingsUpdateSpec instantiates a new DesktopPoolNetworkInterfaceCardSettingsUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesktopPoolNetworkInterfaceCardSettingsUpdateSpecWithDefaults

`func NewDesktopPoolNetworkInterfaceCardSettingsUpdateSpecWithDefaults() *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec`

NewDesktopPoolNetworkInterfaceCardSettingsUpdateSpecWithDefaults instantiates a new DesktopPoolNetworkInterfaceCardSettingsUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworkInterfaceCardId

`func (o *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec) GetNetworkInterfaceCardId() string`

GetNetworkInterfaceCardId returns the NetworkInterfaceCardId field if non-nil, zero value otherwise.

### GetNetworkInterfaceCardIdOk

`func (o *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec) GetNetworkInterfaceCardIdOk() (*string, bool)`

GetNetworkInterfaceCardIdOk returns a tuple with the NetworkInterfaceCardId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkInterfaceCardId

`func (o *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec) SetNetworkInterfaceCardId(v string)`

SetNetworkInterfaceCardId sets NetworkInterfaceCardId field to given value.


### GetNetworkLabelAssignmentSpecs

`func (o *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec) GetNetworkLabelAssignmentSpecs() []DesktopPoolNetworkLabelAssignmentSettingsUpdateSpec`

GetNetworkLabelAssignmentSpecs returns the NetworkLabelAssignmentSpecs field if non-nil, zero value otherwise.

### GetNetworkLabelAssignmentSpecsOk

`func (o *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec) GetNetworkLabelAssignmentSpecsOk() (*[]DesktopPoolNetworkLabelAssignmentSettingsUpdateSpec, bool)`

GetNetworkLabelAssignmentSpecsOk returns a tuple with the NetworkLabelAssignmentSpecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkLabelAssignmentSpecs

`func (o *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec) SetNetworkLabelAssignmentSpecs(v []DesktopPoolNetworkLabelAssignmentSettingsUpdateSpec)`

SetNetworkLabelAssignmentSpecs sets NetworkLabelAssignmentSpecs field to given value.

### HasNetworkLabelAssignmentSpecs

`func (o *DesktopPoolNetworkInterfaceCardSettingsUpdateSpec) HasNetworkLabelAssignmentSpecs() bool`

HasNetworkLabelAssignmentSpecs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


