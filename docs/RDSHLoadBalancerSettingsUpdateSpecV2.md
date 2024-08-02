# RDSHLoadBalancerSettingsUpdateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectingSessionThreshold** | **int32** | Represents the maximum number of sessions that can concurrently log into each RDSH agent machine in the farm, exempting reconnecting sessions. | 
**CpuThreshold** | **int32** | Represents threshold of CPU usage, in percentage. If the value is 0, then this metric is not considered for load balancing. | 
**DiskQueueLengthThreshold** | **int32** | Represents the threshold of average number of both read and write requests that were queued for the selected disk during the sample interval. If the value is 0, then this metric is not considered for load balancing.  | 
**DiskReadLatencyThreshold** | **int32** | Represents the threshold of average time, in milliseconds, of a read of data from the disk. If the value is 0, then this metric is not considered for load balancing. | 
**DiskWriteLatencyThreshold** | **int32** | Represents the threshold of average time, in milliseconds, of a write of data to the disk. If the value is 0, then this metric is not considered for load balancing.  | 
**IncludeSessionCount** | **bool** | Indicates whether to include session count for load balancing. | 
**LoadIndexThreshold** | **int32** | Represents the minimum load index at which each RDSH agent machine in the farm will start denying session logins, exempting reconnecting sessions. | 
**MemoryThreshold** | **int32** | Represents threshold of memory usage, in percentage. If the value is 0, then this metric is not considered for load balancing.  | 

## Methods

### NewRDSHLoadBalancerSettingsUpdateSpecV2

`func NewRDSHLoadBalancerSettingsUpdateSpecV2(connectingSessionThreshold int32, cpuThreshold int32, diskQueueLengthThreshold int32, diskReadLatencyThreshold int32, diskWriteLatencyThreshold int32, includeSessionCount bool, loadIndexThreshold int32, memoryThreshold int32, ) *RDSHLoadBalancerSettingsUpdateSpecV2`

NewRDSHLoadBalancerSettingsUpdateSpecV2 instantiates a new RDSHLoadBalancerSettingsUpdateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRDSHLoadBalancerSettingsUpdateSpecV2WithDefaults

`func NewRDSHLoadBalancerSettingsUpdateSpecV2WithDefaults() *RDSHLoadBalancerSettingsUpdateSpecV2`

NewRDSHLoadBalancerSettingsUpdateSpecV2WithDefaults instantiates a new RDSHLoadBalancerSettingsUpdateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetConnectingSessionThreshold() int32`

GetConnectingSessionThreshold returns the ConnectingSessionThreshold field if non-nil, zero value otherwise.

### GetConnectingSessionThresholdOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetConnectingSessionThresholdOk() (*int32, bool)`

GetConnectingSessionThresholdOk returns a tuple with the ConnectingSessionThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectingSessionThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetConnectingSessionThreshold(v int32)`

SetConnectingSessionThreshold sets ConnectingSessionThreshold field to given value.


### GetCpuThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetCpuThreshold() int32`

GetCpuThreshold returns the CpuThreshold field if non-nil, zero value otherwise.

### GetCpuThresholdOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetCpuThresholdOk() (*int32, bool)`

GetCpuThresholdOk returns a tuple with the CpuThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetCpuThreshold(v int32)`

SetCpuThreshold sets CpuThreshold field to given value.


### GetDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetDiskQueueLengthThreshold() int32`

GetDiskQueueLengthThreshold returns the DiskQueueLengthThreshold field if non-nil, zero value otherwise.

### GetDiskQueueLengthThresholdOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetDiskQueueLengthThresholdOk() (*int32, bool)`

GetDiskQueueLengthThresholdOk returns a tuple with the DiskQueueLengthThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskQueueLengthThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetDiskQueueLengthThreshold(v int32)`

SetDiskQueueLengthThreshold sets DiskQueueLengthThreshold field to given value.


### GetDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetDiskReadLatencyThreshold() int32`

GetDiskReadLatencyThreshold returns the DiskReadLatencyThreshold field if non-nil, zero value otherwise.

### GetDiskReadLatencyThresholdOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetDiskReadLatencyThresholdOk() (*int32, bool)`

GetDiskReadLatencyThresholdOk returns a tuple with the DiskReadLatencyThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskReadLatencyThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetDiskReadLatencyThreshold(v int32)`

SetDiskReadLatencyThreshold sets DiskReadLatencyThreshold field to given value.


### GetDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetDiskWriteLatencyThreshold() int32`

GetDiskWriteLatencyThreshold returns the DiskWriteLatencyThreshold field if non-nil, zero value otherwise.

### GetDiskWriteLatencyThresholdOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetDiskWriteLatencyThresholdOk() (*int32, bool)`

GetDiskWriteLatencyThresholdOk returns a tuple with the DiskWriteLatencyThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskWriteLatencyThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetDiskWriteLatencyThreshold(v int32)`

SetDiskWriteLatencyThreshold sets DiskWriteLatencyThreshold field to given value.


### GetIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetIncludeSessionCount() bool`

GetIncludeSessionCount returns the IncludeSessionCount field if non-nil, zero value otherwise.

### GetIncludeSessionCountOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetIncludeSessionCountOk() (*bool, bool)`

GetIncludeSessionCountOk returns a tuple with the IncludeSessionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeSessionCount

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetIncludeSessionCount(v bool)`

SetIncludeSessionCount sets IncludeSessionCount field to given value.


### GetLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetLoadIndexThreshold() int32`

GetLoadIndexThreshold returns the LoadIndexThreshold field if non-nil, zero value otherwise.

### GetLoadIndexThresholdOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetLoadIndexThresholdOk() (*int32, bool)`

GetLoadIndexThresholdOk returns a tuple with the LoadIndexThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadIndexThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetLoadIndexThreshold(v int32)`

SetLoadIndexThreshold sets LoadIndexThreshold field to given value.


### GetMemoryThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetMemoryThreshold() int32`

GetMemoryThreshold returns the MemoryThreshold field if non-nil, zero value otherwise.

### GetMemoryThresholdOk

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) GetMemoryThresholdOk() (*int32, bool)`

GetMemoryThresholdOk returns a tuple with the MemoryThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryThreshold

`func (o *RDSHLoadBalancerSettingsUpdateSpecV2) SetMemoryThreshold(v int32)`

SetMemoryThreshold sets MemoryThreshold field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


