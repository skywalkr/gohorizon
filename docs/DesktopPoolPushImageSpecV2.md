# DesktopPoolPushImageSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddVirtualTpm** | Pointer to **bool** | Indicates whether to add Virtual TPM device. Default: false | [optional] 
**ComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the number of cores per socket for the CPU in the compute profile to be configured on clones.  If set, both compute_profile_num_cpus and compute_profile_ram_mb need to be set.  | [optional] 
**ComputeProfileNumCpus** | Pointer to **int32** | Indicates the number of CPUs in the compute profile to be configured on clones.  If set, this must be a multiple of compute_profile_num_cores_per_socket. | [optional] 
**ComputeProfileRamMb** | Pointer to **int32** | Indicates the RAM in MB in the compute profile to be configured on clones. | [optional] 
**ImStreamId** | Pointer to **string** | New image management stream for the desktop pool.&lt;br&gt;Either parent VM and snapshot or image management stream and tag are to be specified. | [optional] 
**ImTagId** | Pointer to **string** | New image management tag for the desktop pool. This must be a tag of the image management stream. | [optional] 
**LogoffPolicy** | **string** | Determines when to perform the operation on machines which have an active session. * FORCE_LOGOFF: Users will be forced to log off when the system is ready to execute the operation. Before being forcibly logged off, users may have a grace period in which to save their work which can be configured in Global Settings. * WAIT_FOR_LOGOFF: Wait for connected users to disconnect before the task starts. The operation starts immediately when there are no active sessions. | 
**MachineIds** | Pointer to **[]string** | Set of machines from the desktop pool on which the new image is to be applied. This can be set when selective_push_image is set to true. | [optional] 
**ParentVmId** | Pointer to **string** | New base image virtual machine for the desktop pool. This must be in the same datacenter as the base image of the desktop pool.&lt;br&gt;Either parent VM and snapshot or image management stream and tag are to be specified. | [optional] 
**SelectivePushImage** | Pointer to **bool** | Indicates whether selective push image is to be applied. If set to true, the new image will be applied to specified machine_ids in the desktop pool. The image published with this option will be held as a pending image, unless it is promoted or cancelled. The default value is false. | [optional] 
**SnapshotId** | Pointer to **string** | New base image snapshot for the desktop pool. This must be a snapshot of the parent VM. | [optional] 
**StartTime** | Pointer to **int64** | When to start the operation. If unset or the time is in the past, the operation will begin immediately. Measured as epoch time. | [optional] 
**StopOnFirstError** | Pointer to **bool** | Indicates that the operation should stop on first error. Default: true | [optional] 

## Methods

### NewDesktopPoolPushImageSpecV2

`func NewDesktopPoolPushImageSpecV2(logoffPolicy string, ) *DesktopPoolPushImageSpecV2`

NewDesktopPoolPushImageSpecV2 instantiates a new DesktopPoolPushImageSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesktopPoolPushImageSpecV2WithDefaults

`func NewDesktopPoolPushImageSpecV2WithDefaults() *DesktopPoolPushImageSpecV2`

NewDesktopPoolPushImageSpecV2WithDefaults instantiates a new DesktopPoolPushImageSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddVirtualTpm

`func (o *DesktopPoolPushImageSpecV2) GetAddVirtualTpm() bool`

GetAddVirtualTpm returns the AddVirtualTpm field if non-nil, zero value otherwise.

### GetAddVirtualTpmOk

`func (o *DesktopPoolPushImageSpecV2) GetAddVirtualTpmOk() (*bool, bool)`

GetAddVirtualTpmOk returns a tuple with the AddVirtualTpm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddVirtualTpm

`func (o *DesktopPoolPushImageSpecV2) SetAddVirtualTpm(v bool)`

SetAddVirtualTpm sets AddVirtualTpm field to given value.

### HasAddVirtualTpm

`func (o *DesktopPoolPushImageSpecV2) HasAddVirtualTpm() bool`

HasAddVirtualTpm returns a boolean if a field has been set.

### GetComputeProfileNumCoresPerSocket

`func (o *DesktopPoolPushImageSpecV2) GetComputeProfileNumCoresPerSocket() int32`

GetComputeProfileNumCoresPerSocket returns the ComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetComputeProfileNumCoresPerSocketOk

`func (o *DesktopPoolPushImageSpecV2) GetComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetComputeProfileNumCoresPerSocketOk returns a tuple with the ComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCoresPerSocket

`func (o *DesktopPoolPushImageSpecV2) SetComputeProfileNumCoresPerSocket(v int32)`

SetComputeProfileNumCoresPerSocket sets ComputeProfileNumCoresPerSocket field to given value.

### HasComputeProfileNumCoresPerSocket

`func (o *DesktopPoolPushImageSpecV2) HasComputeProfileNumCoresPerSocket() bool`

HasComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetComputeProfileNumCpus

`func (o *DesktopPoolPushImageSpecV2) GetComputeProfileNumCpus() int32`

GetComputeProfileNumCpus returns the ComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetComputeProfileNumCpusOk

`func (o *DesktopPoolPushImageSpecV2) GetComputeProfileNumCpusOk() (*int32, bool)`

GetComputeProfileNumCpusOk returns a tuple with the ComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCpus

`func (o *DesktopPoolPushImageSpecV2) SetComputeProfileNumCpus(v int32)`

SetComputeProfileNumCpus sets ComputeProfileNumCpus field to given value.

### HasComputeProfileNumCpus

`func (o *DesktopPoolPushImageSpecV2) HasComputeProfileNumCpus() bool`

HasComputeProfileNumCpus returns a boolean if a field has been set.

### GetComputeProfileRamMb

`func (o *DesktopPoolPushImageSpecV2) GetComputeProfileRamMb() int32`

GetComputeProfileRamMb returns the ComputeProfileRamMb field if non-nil, zero value otherwise.

### GetComputeProfileRamMbOk

`func (o *DesktopPoolPushImageSpecV2) GetComputeProfileRamMbOk() (*int32, bool)`

GetComputeProfileRamMbOk returns a tuple with the ComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileRamMb

`func (o *DesktopPoolPushImageSpecV2) SetComputeProfileRamMb(v int32)`

SetComputeProfileRamMb sets ComputeProfileRamMb field to given value.

### HasComputeProfileRamMb

`func (o *DesktopPoolPushImageSpecV2) HasComputeProfileRamMb() bool`

HasComputeProfileRamMb returns a boolean if a field has been set.

### GetImStreamId

`func (o *DesktopPoolPushImageSpecV2) GetImStreamId() string`

GetImStreamId returns the ImStreamId field if non-nil, zero value otherwise.

### GetImStreamIdOk

`func (o *DesktopPoolPushImageSpecV2) GetImStreamIdOk() (*string, bool)`

GetImStreamIdOk returns a tuple with the ImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImStreamId

`func (o *DesktopPoolPushImageSpecV2) SetImStreamId(v string)`

SetImStreamId sets ImStreamId field to given value.

### HasImStreamId

`func (o *DesktopPoolPushImageSpecV2) HasImStreamId() bool`

HasImStreamId returns a boolean if a field has been set.

### GetImTagId

`func (o *DesktopPoolPushImageSpecV2) GetImTagId() string`

GetImTagId returns the ImTagId field if non-nil, zero value otherwise.

### GetImTagIdOk

`func (o *DesktopPoolPushImageSpecV2) GetImTagIdOk() (*string, bool)`

GetImTagIdOk returns a tuple with the ImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImTagId

`func (o *DesktopPoolPushImageSpecV2) SetImTagId(v string)`

SetImTagId sets ImTagId field to given value.

### HasImTagId

`func (o *DesktopPoolPushImageSpecV2) HasImTagId() bool`

HasImTagId returns a boolean if a field has been set.

### GetLogoffPolicy

`func (o *DesktopPoolPushImageSpecV2) GetLogoffPolicy() string`

GetLogoffPolicy returns the LogoffPolicy field if non-nil, zero value otherwise.

### GetLogoffPolicyOk

`func (o *DesktopPoolPushImageSpecV2) GetLogoffPolicyOk() (*string, bool)`

GetLogoffPolicyOk returns a tuple with the LogoffPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoffPolicy

`func (o *DesktopPoolPushImageSpecV2) SetLogoffPolicy(v string)`

SetLogoffPolicy sets LogoffPolicy field to given value.


### GetMachineIds

`func (o *DesktopPoolPushImageSpecV2) GetMachineIds() []string`

GetMachineIds returns the MachineIds field if non-nil, zero value otherwise.

### GetMachineIdsOk

`func (o *DesktopPoolPushImageSpecV2) GetMachineIdsOk() (*[]string, bool)`

GetMachineIdsOk returns a tuple with the MachineIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineIds

`func (o *DesktopPoolPushImageSpecV2) SetMachineIds(v []string)`

SetMachineIds sets MachineIds field to given value.

### HasMachineIds

`func (o *DesktopPoolPushImageSpecV2) HasMachineIds() bool`

HasMachineIds returns a boolean if a field has been set.

### GetParentVmId

`func (o *DesktopPoolPushImageSpecV2) GetParentVmId() string`

GetParentVmId returns the ParentVmId field if non-nil, zero value otherwise.

### GetParentVmIdOk

`func (o *DesktopPoolPushImageSpecV2) GetParentVmIdOk() (*string, bool)`

GetParentVmIdOk returns a tuple with the ParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentVmId

`func (o *DesktopPoolPushImageSpecV2) SetParentVmId(v string)`

SetParentVmId sets ParentVmId field to given value.

### HasParentVmId

`func (o *DesktopPoolPushImageSpecV2) HasParentVmId() bool`

HasParentVmId returns a boolean if a field has been set.

### GetSelectivePushImage

`func (o *DesktopPoolPushImageSpecV2) GetSelectivePushImage() bool`

GetSelectivePushImage returns the SelectivePushImage field if non-nil, zero value otherwise.

### GetSelectivePushImageOk

`func (o *DesktopPoolPushImageSpecV2) GetSelectivePushImageOk() (*bool, bool)`

GetSelectivePushImageOk returns a tuple with the SelectivePushImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectivePushImage

`func (o *DesktopPoolPushImageSpecV2) SetSelectivePushImage(v bool)`

SetSelectivePushImage sets SelectivePushImage field to given value.

### HasSelectivePushImage

`func (o *DesktopPoolPushImageSpecV2) HasSelectivePushImage() bool`

HasSelectivePushImage returns a boolean if a field has been set.

### GetSnapshotId

`func (o *DesktopPoolPushImageSpecV2) GetSnapshotId() string`

GetSnapshotId returns the SnapshotId field if non-nil, zero value otherwise.

### GetSnapshotIdOk

`func (o *DesktopPoolPushImageSpecV2) GetSnapshotIdOk() (*string, bool)`

GetSnapshotIdOk returns a tuple with the SnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotId

`func (o *DesktopPoolPushImageSpecV2) SetSnapshotId(v string)`

SetSnapshotId sets SnapshotId field to given value.

### HasSnapshotId

`func (o *DesktopPoolPushImageSpecV2) HasSnapshotId() bool`

HasSnapshotId returns a boolean if a field has been set.

### GetStartTime

`func (o *DesktopPoolPushImageSpecV2) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *DesktopPoolPushImageSpecV2) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *DesktopPoolPushImageSpecV2) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *DesktopPoolPushImageSpecV2) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetStopOnFirstError

`func (o *DesktopPoolPushImageSpecV2) GetStopOnFirstError() bool`

GetStopOnFirstError returns the StopOnFirstError field if non-nil, zero value otherwise.

### GetStopOnFirstErrorOk

`func (o *DesktopPoolPushImageSpecV2) GetStopOnFirstErrorOk() (*bool, bool)`

GetStopOnFirstErrorOk returns a tuple with the StopOnFirstError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopOnFirstError

`func (o *DesktopPoolPushImageSpecV2) SetStopOnFirstError(v bool)`

SetStopOnFirstError sets StopOnFirstError field to given value.

### HasStopOnFirstError

`func (o *DesktopPoolPushImageSpecV2) HasStopOnFirstError() bool`

HasStopOnFirstError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


