# FarmMaintenanceSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the number of cores per socket for the CPU in the compute profile to be configured on clones.  If set, both compute_profile_num_cpus and compute_profile_ram_mb need to be set.  | [optional] 
**ComputeProfileNumCpus** | Pointer to **int32** | Indicates the number of CPUs in the compute profile to be configured on clones.  If set, this must be a multiple of compute_profile_num_cores_per_socket. | [optional] 
**ComputeProfileRamMb** | Pointer to **int32** | Indicates the RAM in MB in the compute profile to be configured on clones. | [optional] 
**ImStreamId** | Pointer to **string** | New image management stream for the farm. Either parent_vm_id and snapshot_id or im_stream_id and im_tag_id are to be specified. | [optional] 
**ImTagId** | Pointer to **string** | New image management tag for the farm. This tag must be within the im_stream_id. Either parent_vm_id and snapshot_id or im_stream_id and im_tag_id are to be specified. | [optional] 
**LogoffPolicy** | **string** | Determines when to perform the operation on RDS servers which have an active session. * FORCE_LOGOFF: Users will be forced to log off when the system is ready to execute the operation. Before being forcibly logged off, users may have a grace period in which to save their work which can be configured in Global Settings. * WAIT_FOR_LOGOFF: Wait for connected users to disconnect before the task starts. The operation starts immediately when there are no active sessions. | 
**MaintenanceMode** | **string** | The mode of schedule maintenance for Instant Clone Farm. * IMMEDIATE: All server VMs will be refreshed once, immediately or at user scheduled time. * RECURRING: All server VMs will be periodically refreshed based on FarmInstantCloneRecurringMaintenancePeriod and StartTime | 
**NextScheduledTime** | Pointer to **int64** | Time when next scheduled maintenance would happen. If maintenance_mode is set to IMMEDIATE and next_scheduled_time is not set, maintenance will begin immediately. If maintenance_mode is set to RECURRING and next_scheduled_time is not set, it will be calculated based on current recurring maintenance configuration. If the value is in the past, maintenance will begin immediately. Measured as epoch time. | [optional] 
**ParentVmId** | Pointer to **string** | New base image VM for the instant clone farm. This must be in the same datacenter as the base image of the farm. Either parent_vm_id and snapshot_id or im_stream_id and im_tag_id are to be specified. | [optional] 
**RdsServerIds** | Pointer to **[]string** | Set of RDS servers from the farm on which the new image is to be applied. This can be set when selective_schedule_maintenance is set to true. | [optional] 
**RecurringMaintenanceSettings** | Pointer to [**FarmRecurringMaintenanceSettingsSpec**](FarmRecurringMaintenanceSettingsSpec.md) |  | [optional] 
**SelectiveScheduleMaintenance** | Pointer to **bool** | Indicates whether selective scheduled maintenance is to be applied. If set to true, the new image will be applied to specified rds_server_ids in the farm. The image published with this option will be held as a pending image, unless it is promoted or cancelled. The default value is false. | [optional] 
**SnapshotId** | Pointer to **string** | New base image snapshot for the instant clone farm. This must be a snapshot of the parent_vm_id. Either parent_vm_id and snapshot_id or im_stream_id and im_tag_id are to be specified. | [optional] 
**StopOnFirstError** | Pointer to **bool** | Indicates whether the operation should stop on first error. Default value is true. | [optional] 

## Methods

### NewFarmMaintenanceSpecV2

`func NewFarmMaintenanceSpecV2(logoffPolicy string, maintenanceMode string, ) *FarmMaintenanceSpecV2`

NewFarmMaintenanceSpecV2 instantiates a new FarmMaintenanceSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmMaintenanceSpecV2WithDefaults

`func NewFarmMaintenanceSpecV2WithDefaults() *FarmMaintenanceSpecV2`

NewFarmMaintenanceSpecV2WithDefaults instantiates a new FarmMaintenanceSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComputeProfileNumCoresPerSocket

`func (o *FarmMaintenanceSpecV2) GetComputeProfileNumCoresPerSocket() int32`

GetComputeProfileNumCoresPerSocket returns the ComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetComputeProfileNumCoresPerSocketOk

`func (o *FarmMaintenanceSpecV2) GetComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetComputeProfileNumCoresPerSocketOk returns a tuple with the ComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCoresPerSocket

`func (o *FarmMaintenanceSpecV2) SetComputeProfileNumCoresPerSocket(v int32)`

SetComputeProfileNumCoresPerSocket sets ComputeProfileNumCoresPerSocket field to given value.

### HasComputeProfileNumCoresPerSocket

`func (o *FarmMaintenanceSpecV2) HasComputeProfileNumCoresPerSocket() bool`

HasComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetComputeProfileNumCpus

`func (o *FarmMaintenanceSpecV2) GetComputeProfileNumCpus() int32`

GetComputeProfileNumCpus returns the ComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetComputeProfileNumCpusOk

`func (o *FarmMaintenanceSpecV2) GetComputeProfileNumCpusOk() (*int32, bool)`

GetComputeProfileNumCpusOk returns a tuple with the ComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCpus

`func (o *FarmMaintenanceSpecV2) SetComputeProfileNumCpus(v int32)`

SetComputeProfileNumCpus sets ComputeProfileNumCpus field to given value.

### HasComputeProfileNumCpus

`func (o *FarmMaintenanceSpecV2) HasComputeProfileNumCpus() bool`

HasComputeProfileNumCpus returns a boolean if a field has been set.

### GetComputeProfileRamMb

`func (o *FarmMaintenanceSpecV2) GetComputeProfileRamMb() int32`

GetComputeProfileRamMb returns the ComputeProfileRamMb field if non-nil, zero value otherwise.

### GetComputeProfileRamMbOk

`func (o *FarmMaintenanceSpecV2) GetComputeProfileRamMbOk() (*int32, bool)`

GetComputeProfileRamMbOk returns a tuple with the ComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileRamMb

`func (o *FarmMaintenanceSpecV2) SetComputeProfileRamMb(v int32)`

SetComputeProfileRamMb sets ComputeProfileRamMb field to given value.

### HasComputeProfileRamMb

`func (o *FarmMaintenanceSpecV2) HasComputeProfileRamMb() bool`

HasComputeProfileRamMb returns a boolean if a field has been set.

### GetImStreamId

`func (o *FarmMaintenanceSpecV2) GetImStreamId() string`

GetImStreamId returns the ImStreamId field if non-nil, zero value otherwise.

### GetImStreamIdOk

`func (o *FarmMaintenanceSpecV2) GetImStreamIdOk() (*string, bool)`

GetImStreamIdOk returns a tuple with the ImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImStreamId

`func (o *FarmMaintenanceSpecV2) SetImStreamId(v string)`

SetImStreamId sets ImStreamId field to given value.

### HasImStreamId

`func (o *FarmMaintenanceSpecV2) HasImStreamId() bool`

HasImStreamId returns a boolean if a field has been set.

### GetImTagId

`func (o *FarmMaintenanceSpecV2) GetImTagId() string`

GetImTagId returns the ImTagId field if non-nil, zero value otherwise.

### GetImTagIdOk

`func (o *FarmMaintenanceSpecV2) GetImTagIdOk() (*string, bool)`

GetImTagIdOk returns a tuple with the ImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImTagId

`func (o *FarmMaintenanceSpecV2) SetImTagId(v string)`

SetImTagId sets ImTagId field to given value.

### HasImTagId

`func (o *FarmMaintenanceSpecV2) HasImTagId() bool`

HasImTagId returns a boolean if a field has been set.

### GetLogoffPolicy

`func (o *FarmMaintenanceSpecV2) GetLogoffPolicy() string`

GetLogoffPolicy returns the LogoffPolicy field if non-nil, zero value otherwise.

### GetLogoffPolicyOk

`func (o *FarmMaintenanceSpecV2) GetLogoffPolicyOk() (*string, bool)`

GetLogoffPolicyOk returns a tuple with the LogoffPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoffPolicy

`func (o *FarmMaintenanceSpecV2) SetLogoffPolicy(v string)`

SetLogoffPolicy sets LogoffPolicy field to given value.


### GetMaintenanceMode

`func (o *FarmMaintenanceSpecV2) GetMaintenanceMode() string`

GetMaintenanceMode returns the MaintenanceMode field if non-nil, zero value otherwise.

### GetMaintenanceModeOk

`func (o *FarmMaintenanceSpecV2) GetMaintenanceModeOk() (*string, bool)`

GetMaintenanceModeOk returns a tuple with the MaintenanceMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceMode

`func (o *FarmMaintenanceSpecV2) SetMaintenanceMode(v string)`

SetMaintenanceMode sets MaintenanceMode field to given value.


### GetNextScheduledTime

`func (o *FarmMaintenanceSpecV2) GetNextScheduledTime() int64`

GetNextScheduledTime returns the NextScheduledTime field if non-nil, zero value otherwise.

### GetNextScheduledTimeOk

`func (o *FarmMaintenanceSpecV2) GetNextScheduledTimeOk() (*int64, bool)`

GetNextScheduledTimeOk returns a tuple with the NextScheduledTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextScheduledTime

`func (o *FarmMaintenanceSpecV2) SetNextScheduledTime(v int64)`

SetNextScheduledTime sets NextScheduledTime field to given value.

### HasNextScheduledTime

`func (o *FarmMaintenanceSpecV2) HasNextScheduledTime() bool`

HasNextScheduledTime returns a boolean if a field has been set.

### GetParentVmId

`func (o *FarmMaintenanceSpecV2) GetParentVmId() string`

GetParentVmId returns the ParentVmId field if non-nil, zero value otherwise.

### GetParentVmIdOk

`func (o *FarmMaintenanceSpecV2) GetParentVmIdOk() (*string, bool)`

GetParentVmIdOk returns a tuple with the ParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentVmId

`func (o *FarmMaintenanceSpecV2) SetParentVmId(v string)`

SetParentVmId sets ParentVmId field to given value.

### HasParentVmId

`func (o *FarmMaintenanceSpecV2) HasParentVmId() bool`

HasParentVmId returns a boolean if a field has been set.

### GetRdsServerIds

`func (o *FarmMaintenanceSpecV2) GetRdsServerIds() []string`

GetRdsServerIds returns the RdsServerIds field if non-nil, zero value otherwise.

### GetRdsServerIdsOk

`func (o *FarmMaintenanceSpecV2) GetRdsServerIdsOk() (*[]string, bool)`

GetRdsServerIdsOk returns a tuple with the RdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRdsServerIds

`func (o *FarmMaintenanceSpecV2) SetRdsServerIds(v []string)`

SetRdsServerIds sets RdsServerIds field to given value.

### HasRdsServerIds

`func (o *FarmMaintenanceSpecV2) HasRdsServerIds() bool`

HasRdsServerIds returns a boolean if a field has been set.

### GetRecurringMaintenanceSettings

`func (o *FarmMaintenanceSpecV2) GetRecurringMaintenanceSettings() FarmRecurringMaintenanceSettingsSpec`

GetRecurringMaintenanceSettings returns the RecurringMaintenanceSettings field if non-nil, zero value otherwise.

### GetRecurringMaintenanceSettingsOk

`func (o *FarmMaintenanceSpecV2) GetRecurringMaintenanceSettingsOk() (*FarmRecurringMaintenanceSettingsSpec, bool)`

GetRecurringMaintenanceSettingsOk returns a tuple with the RecurringMaintenanceSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringMaintenanceSettings

`func (o *FarmMaintenanceSpecV2) SetRecurringMaintenanceSettings(v FarmRecurringMaintenanceSettingsSpec)`

SetRecurringMaintenanceSettings sets RecurringMaintenanceSettings field to given value.

### HasRecurringMaintenanceSettings

`func (o *FarmMaintenanceSpecV2) HasRecurringMaintenanceSettings() bool`

HasRecurringMaintenanceSettings returns a boolean if a field has been set.

### GetSelectiveScheduleMaintenance

`func (o *FarmMaintenanceSpecV2) GetSelectiveScheduleMaintenance() bool`

GetSelectiveScheduleMaintenance returns the SelectiveScheduleMaintenance field if non-nil, zero value otherwise.

### GetSelectiveScheduleMaintenanceOk

`func (o *FarmMaintenanceSpecV2) GetSelectiveScheduleMaintenanceOk() (*bool, bool)`

GetSelectiveScheduleMaintenanceOk returns a tuple with the SelectiveScheduleMaintenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectiveScheduleMaintenance

`func (o *FarmMaintenanceSpecV2) SetSelectiveScheduleMaintenance(v bool)`

SetSelectiveScheduleMaintenance sets SelectiveScheduleMaintenance field to given value.

### HasSelectiveScheduleMaintenance

`func (o *FarmMaintenanceSpecV2) HasSelectiveScheduleMaintenance() bool`

HasSelectiveScheduleMaintenance returns a boolean if a field has been set.

### GetSnapshotId

`func (o *FarmMaintenanceSpecV2) GetSnapshotId() string`

GetSnapshotId returns the SnapshotId field if non-nil, zero value otherwise.

### GetSnapshotIdOk

`func (o *FarmMaintenanceSpecV2) GetSnapshotIdOk() (*string, bool)`

GetSnapshotIdOk returns a tuple with the SnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotId

`func (o *FarmMaintenanceSpecV2) SetSnapshotId(v string)`

SetSnapshotId sets SnapshotId field to given value.

### HasSnapshotId

`func (o *FarmMaintenanceSpecV2) HasSnapshotId() bool`

HasSnapshotId returns a boolean if a field has been set.

### GetStopOnFirstError

`func (o *FarmMaintenanceSpecV2) GetStopOnFirstError() bool`

GetStopOnFirstError returns the StopOnFirstError field if non-nil, zero value otherwise.

### GetStopOnFirstErrorOk

`func (o *FarmMaintenanceSpecV2) GetStopOnFirstErrorOk() (*bool, bool)`

GetStopOnFirstErrorOk returns a tuple with the StopOnFirstError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopOnFirstError

`func (o *FarmMaintenanceSpecV2) SetStopOnFirstError(v bool)`

SetStopOnFirstError sets StopOnFirstError field to given value.

### HasStopOnFirstError

`func (o *FarmMaintenanceSpecV2) HasStopOnFirstError() bool`

HasStopOnFirstError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


