# RDSHLoadBalancerSettingsInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectingSessionThreshold** | Pointer to **int32** | Represents the maximum number of sessions that can concurrently log into each RDSH agent machine in the farm, exempting reconnecting sessions. | [optional] 
**CpuThreshold** | Pointer to **int32** | Represents threshold of CPU usage, in percentage. If the value is 0, then this metric is not considered for load balancing. | [optional] 
**DiskQueueLengthThreshold** | Pointer to **int32** | Represents the threshold of average number of both read and write requests that were queued for the selected disk during the sample interval. If the value is 0, then this metric is not considered for load balancing. | [optional] 
**DiskReadLatencyThreshold** | Pointer to **int32** | Represents the threshold of average time, in milliseconds, of a read of data from the disk. If the value is 0, then this metric is not considered for load balancing.  | [optional] 
**DiskWriteLatencyThreshold** | Pointer to **int32** | Represents the threshold of average time, in milliseconds, of a write of data to the disk. If the value is 0, then this metric is not considered for load balancing. | [optional] 
**IncludeSessionCount** | Pointer to **bool** | Indicates whether to include session count for load balancing. | [optional] 
**LoadIndexThreshold** | Pointer to **int32** | Represents the minimum load index at which each RDSH agent machine in the farm will start denying session logins, exempting reconnecting sessions. | [optional] 
**MemoryThreshold** | Pointer to **int32** | Represents threshold of memory usage, in percentage. If the value is 0, then this metric is not considered for load balancing.  | [optional] 

## Methods

### NewRDSHLoadBalancerSettingsInfoV2

`func NewRDSHLoadBalancerSettingsInfoV2() *RDSHLoadBalancerSettingsInfoV2`

NewRDSHLoadBalancerSettingsInfoV2 instantiates a new RDSHLoadBalancerSettingsInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRDSHLoadBalancerSettingsInfoV2WithDefaults

`func NewRDSHLoadBalancerSettingsInfoV2WithDefaults() *RDSHLoadBalancerSettingsInfoV2`

NewRDSHLoadBalancerSettingsInfoV2WithDefaults instantiates a new RDSHLoadBalancerSettingsInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) GetConnectingSessionThreshold() int32`

GetConnectingSessionThreshold returns the ConnectingSessionThreshold field if non-nil, zero value otherwise.

### GetConnectingSessionThresholdOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetConnectingSessionThresholdOk() (*int32, bool)`

GetConnectingSessionThresholdOk returns a tuple with the ConnectingSessionThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) SetConnectingSessionThreshold(v int32)`

SetConnectingSessionThreshold sets ConnectingSessionThreshold field to given value.

### HasConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) HasConnectingSessionThreshold() bool`

HasConnectingSessionThreshold returns a boolean if a field has been set.

### GetCpuThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) GetCpuThreshold() int32`

GetCpuThreshold returns the CpuThreshold field if non-nil, zero value otherwise.

### GetCpuThresholdOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetCpuThresholdOk() (*int32, bool)`

GetCpuThresholdOk returns a tuple with the CpuThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) SetCpuThreshold(v int32)`

SetCpuThreshold sets CpuThreshold field to given value.

### HasCpuThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) HasCpuThreshold() bool`

HasCpuThreshold returns a boolean if a field has been set.

### GetDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) GetDiskQueueLengthThreshold() int32`

GetDiskQueueLengthThreshold returns the DiskQueueLengthThreshold field if non-nil, zero value otherwise.

### GetDiskQueueLengthThresholdOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetDiskQueueLengthThresholdOk() (*int32, bool)`

GetDiskQueueLengthThresholdOk returns a tuple with the DiskQueueLengthThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) SetDiskQueueLengthThreshold(v int32)`

SetDiskQueueLengthThreshold sets DiskQueueLengthThreshold field to given value.

### HasDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) HasDiskQueueLengthThreshold() bool`

HasDiskQueueLengthThreshold returns a boolean if a field has been set.

### GetDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) GetDiskReadLatencyThreshold() int32`

GetDiskReadLatencyThreshold returns the DiskReadLatencyThreshold field if non-nil, zero value otherwise.

### GetDiskReadLatencyThresholdOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetDiskReadLatencyThresholdOk() (*int32, bool)`

GetDiskReadLatencyThresholdOk returns a tuple with the DiskReadLatencyThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) SetDiskReadLatencyThreshold(v int32)`

SetDiskReadLatencyThreshold sets DiskReadLatencyThreshold field to given value.

### HasDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) HasDiskReadLatencyThreshold() bool`

HasDiskReadLatencyThreshold returns a boolean if a field has been set.

### GetDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) GetDiskWriteLatencyThreshold() int32`

GetDiskWriteLatencyThreshold returns the DiskWriteLatencyThreshold field if non-nil, zero value otherwise.

### GetDiskWriteLatencyThresholdOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetDiskWriteLatencyThresholdOk() (*int32, bool)`

GetDiskWriteLatencyThresholdOk returns a tuple with the DiskWriteLatencyThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) SetDiskWriteLatencyThreshold(v int32)`

SetDiskWriteLatencyThreshold sets DiskWriteLatencyThreshold field to given value.

### HasDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) HasDiskWriteLatencyThreshold() bool`

HasDiskWriteLatencyThreshold returns a boolean if a field has been set.

### GetIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsInfoV2) GetIncludeSessionCount() bool`

GetIncludeSessionCount returns the IncludeSessionCount field if non-nil, zero value otherwise.

### GetIncludeSessionCountOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetIncludeSessionCountOk() (*bool, bool)`

GetIncludeSessionCountOk returns a tuple with the IncludeSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsInfoV2) SetIncludeSessionCount(v bool)`

SetIncludeSessionCount sets IncludeSessionCount field to given value.

### HasIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsInfoV2) HasIncludeSessionCount() bool`

HasIncludeSessionCount returns a boolean if a field has been set.

### GetLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) GetLoadIndexThreshold() int32`

GetLoadIndexThreshold returns the LoadIndexThreshold field if non-nil, zero value otherwise.

### GetLoadIndexThresholdOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetLoadIndexThresholdOk() (*int32, bool)`

GetLoadIndexThresholdOk returns a tuple with the LoadIndexThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) SetLoadIndexThreshold(v int32)`

SetLoadIndexThreshold sets LoadIndexThreshold field to given value.

### HasLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) HasLoadIndexThreshold() bool`

HasLoadIndexThreshold returns a boolean if a field has been set.

### GetMemoryThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) GetMemoryThreshold() int32`

GetMemoryThreshold returns the MemoryThreshold field if non-nil, zero value otherwise.

### GetMemoryThresholdOk

`func (o *RDSHLoadBalancerSettingsInfoV2) GetMemoryThresholdOk() (*int32, bool)`

GetMemoryThresholdOk returns a tuple with the MemoryThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) SetMemoryThreshold(v int32)`

SetMemoryThreshold sets MemoryThreshold field to given value.

### HasMemoryThreshold

`func (o *RDSHLoadBalancerSettingsInfoV2) HasMemoryThreshold() bool`

HasMemoryThreshold returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


