# RDSHLoadBalancerSettingsCreateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectingSessionThreshold** | Pointer to **int32** | Represents the maximum number of sessions that can concurrently log into each RDSH agent machine in the farm, exempting reconnecting sessions. By default, this threshold is disabled and does not deny session logins. Default value is 0. | [optional] 
**CpuThreshold** | Pointer to **int32** | Represents threshold of CPU usage, in percentage. If the value is 0, then this metric is not considered for load balancing. Default value is 0. | [optional] 
**DiskQueueLengthThreshold** | Pointer to **int32** | Represents the threshold of average number of both read and write requests that were queued for the selected disk during the sample interval. If the value is 0, then this metric is not considered for load balancing. Default value is 0. | [optional] 
**DiskReadLatencyThreshold** | Pointer to **int32** | Represents the threshold of average time, in milliseconds, of a read of data from the disk. If the value is 0, then this metric is not considered for load balancing. Default value is 0. | [optional] 
**DiskWriteLatencyThreshold** | Pointer to **int32** | Represents the threshold of average time, in milliseconds, of a write of data to the disk. If the value is 0, then this metric is not considered for load balancing. Default value is 0. | [optional] 
**IncludeSessionCount** | Pointer to **bool** | Indicates whether to include session count for load balancing. Default value is true when use_custom_script_for_load_balancing is false. | [optional] 
**LoadIndexThreshold** | Pointer to **int32** | Represents the minimum load index at which each RDSH agent machine in the farm will start denying session logins, exempting reconnecting sessions. By default, this threshold is disabled and does not deny session logins. Default value is 0. | [optional] 
**MemoryThreshold** | Pointer to **int32** | Represents threshold of memory usage, in percentage. If the value is 0, then this metric is not considered for load balancing. Default value is 0. | [optional] 

## Methods

### NewRDSHLoadBalancerSettingsCreateSpecV2

`func NewRDSHLoadBalancerSettingsCreateSpecV2() *RDSHLoadBalancerSettingsCreateSpecV2`

NewRDSHLoadBalancerSettingsCreateSpecV2 instantiates a new RDSHLoadBalancerSettingsCreateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRDSHLoadBalancerSettingsCreateSpecV2WithDefaults

`func NewRDSHLoadBalancerSettingsCreateSpecV2WithDefaults() *RDSHLoadBalancerSettingsCreateSpecV2`

NewRDSHLoadBalancerSettingsCreateSpecV2WithDefaults instantiates a new RDSHLoadBalancerSettingsCreateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetConnectingSessionThreshold() int32`

GetConnectingSessionThreshold returns the ConnectingSessionThreshold field if non-nil, zero value otherwise.

### GetConnectingSessionThresholdOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetConnectingSessionThresholdOk() (*int32, bool)`

GetConnectingSessionThresholdOk returns a tuple with the ConnectingSessionThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetConnectingSessionThreshold(v int32)`

SetConnectingSessionThreshold sets ConnectingSessionThreshold field to given value.

### HasConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasConnectingSessionThreshold() bool`

HasConnectingSessionThreshold returns a boolean if a field has been set.

### GetCpuThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetCpuThreshold() int32`

GetCpuThreshold returns the CpuThreshold field if non-nil, zero value otherwise.

### GetCpuThresholdOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetCpuThresholdOk() (*int32, bool)`

GetCpuThresholdOk returns a tuple with the CpuThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetCpuThreshold(v int32)`

SetCpuThreshold sets CpuThreshold field to given value.

### HasCpuThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasCpuThreshold() bool`

HasCpuThreshold returns a boolean if a field has been set.

### GetDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetDiskQueueLengthThreshold() int32`

GetDiskQueueLengthThreshold returns the DiskQueueLengthThreshold field if non-nil, zero value otherwise.

### GetDiskQueueLengthThresholdOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetDiskQueueLengthThresholdOk() (*int32, bool)`

GetDiskQueueLengthThresholdOk returns a tuple with the DiskQueueLengthThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetDiskQueueLengthThreshold(v int32)`

SetDiskQueueLengthThreshold sets DiskQueueLengthThreshold field to given value.

### HasDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasDiskQueueLengthThreshold() bool`

HasDiskQueueLengthThreshold returns a boolean if a field has been set.

### GetDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetDiskReadLatencyThreshold() int32`

GetDiskReadLatencyThreshold returns the DiskReadLatencyThreshold field if non-nil, zero value otherwise.

### GetDiskReadLatencyThresholdOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetDiskReadLatencyThresholdOk() (*int32, bool)`

GetDiskReadLatencyThresholdOk returns a tuple with the DiskReadLatencyThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetDiskReadLatencyThreshold(v int32)`

SetDiskReadLatencyThreshold sets DiskReadLatencyThreshold field to given value.

### HasDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasDiskReadLatencyThreshold() bool`

HasDiskReadLatencyThreshold returns a boolean if a field has been set.

### GetDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetDiskWriteLatencyThreshold() int32`

GetDiskWriteLatencyThreshold returns the DiskWriteLatencyThreshold field if non-nil, zero value otherwise.

### GetDiskWriteLatencyThresholdOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetDiskWriteLatencyThresholdOk() (*int32, bool)`

GetDiskWriteLatencyThresholdOk returns a tuple with the DiskWriteLatencyThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetDiskWriteLatencyThreshold(v int32)`

SetDiskWriteLatencyThreshold sets DiskWriteLatencyThreshold field to given value.

### HasDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasDiskWriteLatencyThreshold() bool`

HasDiskWriteLatencyThreshold returns a boolean if a field has been set.

### GetIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetIncludeSessionCount() bool`

GetIncludeSessionCount returns the IncludeSessionCount field if non-nil, zero value otherwise.

### GetIncludeSessionCountOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetIncludeSessionCountOk() (*bool, bool)`

GetIncludeSessionCountOk returns a tuple with the IncludeSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetIncludeSessionCount(v bool)`

SetIncludeSessionCount sets IncludeSessionCount field to given value.

### HasIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasIncludeSessionCount() bool`

HasIncludeSessionCount returns a boolean if a field has been set.

### GetLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetLoadIndexThreshold() int32`

GetLoadIndexThreshold returns the LoadIndexThreshold field if non-nil, zero value otherwise.

### GetLoadIndexThresholdOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetLoadIndexThresholdOk() (*int32, bool)`

GetLoadIndexThresholdOk returns a tuple with the LoadIndexThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetLoadIndexThreshold(v int32)`

SetLoadIndexThreshold sets LoadIndexThreshold field to given value.

### HasLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasLoadIndexThreshold() bool`

HasLoadIndexThreshold returns a boolean if a field has been set.

### GetMemoryThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetMemoryThreshold() int32`

GetMemoryThreshold returns the MemoryThreshold field if non-nil, zero value otherwise.

### GetMemoryThresholdOk

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) GetMemoryThresholdOk() (*int32, bool)`

GetMemoryThresholdOk returns a tuple with the MemoryThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) SetMemoryThreshold(v int32)`

SetMemoryThreshold sets MemoryThreshold field to given value.

### HasMemoryThreshold

`func (o *RDSHLoadBalancerSettingsCreateSpecV2) HasMemoryThreshold() bool`

HasMemoryThreshold returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


