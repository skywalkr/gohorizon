# FarmProvisioningStatusInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstantCloneCurrentImageState** | Pointer to **string** | This represents the state of the current image of this instant clone farms. * READY: This is the state of the current image after successful completion of creation operation. At this stage the current image is ready to be used to create the instant clones. Please note that this state is also reached from UNPUBLISHING state on successful completion of editing of cluster or editing of datastore(s) operations. * FAILED: This is the state of the current image if instant clone delete operation has failed or timed out. * PENDING_UNPUBLISH: This is the state of the current image before instant clone delete or cluster edit or datastore(s) edit operation(s) begins. * UNPUBLISHING: This is the transient state of the current image when instant clone delete or cluster edit or datastore(s) edit operation(s) is going on. | [optional] 
**InstantCloneOperation** | Pointer to **string** | The operation that this instant clone farm is undergoing. * NONE: There is no current operation on the farm. * INITIAL_PUBLISH: The farm has just been created and is undergoing initial publishing. * RECURRING_SCHEDULED_MAINTENANCE: Recurring maintenance operation is scheduled on the farm. * CANCEL_SCHEDULED_MAINTENANCE: The recurring maintenance operation on the farm is being cancelled. * INFRASTRUCTURE_CHANGE: A cluster or datastore change operation was requested for the farm. * FINAL_UNPUBLISH: A farm has been deleted and is undergoing final unpublishing. | [optional] 
**InstantCloneOperationTime** | Pointer to **int64** | Time of the operation that instant clone farm is undergoing. | [optional] 
**InstantClonePendingImStreamId** | Pointer to **string** | Pending image management stream for instant clone farms.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**InstantClonePendingImTagId** | Pointer to **string** | Pending image management tag for instant clone farms.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**InstantClonePendingImageError** | Pointer to **string** | This represents the error message if publishing of push image operation is failed. | [optional] 
**InstantClonePendingImageParentVmId** | Pointer to **string** | Pending base image VM for instant clone farms. This is used to return the information about the parent VM of the pending Image. | [optional] 
**InstantClonePendingImageProgress** | Pointer to **int32** | This represents the pending image publish progress in percentage for an instant clone farm. | [optional] 
**InstantClonePendingImageSnapshotId** | Pointer to **string** | Pending base image snapshot for instant clone farms. This is used to return the information about the snapshot of the pending image. | [optional] 
**InstantClonePendingImageState** | Pointer to **string** | This represents the state of the pending image of this instant clone farms. This will be null when there is no pending image for the farm. * PENDING_PUBLISH: This is the initial transient state of the pending image before instant clone creation operation has started. * PUBLISHING: This is the transient state of the pending image when creation of instant clone operation is going on. * UNPUBLISHING: This is the transient state of the pending image when instant clone delete or cluster edit or datastore(s) edit operation(s) is going on. * READY: This is the state of the pending image after successful publish of the pending image and before that image has been upgraded to the current image. This is normally seen after successful publish for a push image which has been scheduled to trigger at a later time. * FAILED: This is the state of the pending image if creation of instant clone operation has failed or timed out. * READY_HELD: This is the state of the pending image after performing a selective resync operation, in which the image may be applied to some VMs in the desktop pool/farm. | [optional] 
**InstantCloneScheduledMaintenanceData** | Pointer to [**FarmScheduledMaintenanceInfo**](FarmScheduledMaintenanceInfo.md) |  | [optional] 
**LastProvisioningError** | Pointer to **string** | String message detailing the last provisioning error on this farm while stop_provisioning_on_error is enabled. | [optional] 
**LastProvisioningErrorTime** | Pointer to **int64** | Time the last provisioning error occurred on this farm while stop_provisioning_on_error is enabled. Measured as epoch time. | [optional] 
**PendingComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the pending number of cores per socket for the CPU in the compute profile configured on clones. | [optional] 
**PendingComputeProfileNumCpus** | Pointer to **int32** | Indicates the pending number of CPUs in the compute profile configured on clones. | [optional] 
**PendingComputeProfileRamMb** | Pointer to **int32** | Indicates the pending RAM in MB in the compute profile configured on clones. | [optional] 

## Methods

### NewFarmProvisioningStatusInfoV2

`func NewFarmProvisioningStatusInfoV2() *FarmProvisioningStatusInfoV2`

NewFarmProvisioningStatusInfoV2 instantiates a new FarmProvisioningStatusInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmProvisioningStatusInfoV2WithDefaults

`func NewFarmProvisioningStatusInfoV2WithDefaults() *FarmProvisioningStatusInfoV2`

NewFarmProvisioningStatusInfoV2WithDefaults instantiates a new FarmProvisioningStatusInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstantCloneCurrentImageState

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneCurrentImageState() string`

GetInstantCloneCurrentImageState returns the InstantCloneCurrentImageState field if non-nil, zero value otherwise.

### GetInstantCloneCurrentImageStateOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneCurrentImageStateOk() (*string, bool)`

GetInstantCloneCurrentImageStateOk returns a tuple with the InstantCloneCurrentImageState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantCloneCurrentImageState

`func (o *FarmProvisioningStatusInfoV2) SetInstantCloneCurrentImageState(v string)`

SetInstantCloneCurrentImageState sets InstantCloneCurrentImageState field to given value.

### HasInstantCloneCurrentImageState

`func (o *FarmProvisioningStatusInfoV2) HasInstantCloneCurrentImageState() bool`

HasInstantCloneCurrentImageState returns a boolean if a field has been set.

### GetInstantCloneOperation

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneOperation() string`

GetInstantCloneOperation returns the InstantCloneOperation field if non-nil, zero value otherwise.

### GetInstantCloneOperationOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneOperationOk() (*string, bool)`

GetInstantCloneOperationOk returns a tuple with the InstantCloneOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantCloneOperation

`func (o *FarmProvisioningStatusInfoV2) SetInstantCloneOperation(v string)`

SetInstantCloneOperation sets InstantCloneOperation field to given value.

### HasInstantCloneOperation

`func (o *FarmProvisioningStatusInfoV2) HasInstantCloneOperation() bool`

HasInstantCloneOperation returns a boolean if a field has been set.

### GetInstantCloneOperationTime

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneOperationTime() int64`

GetInstantCloneOperationTime returns the InstantCloneOperationTime field if non-nil, zero value otherwise.

### GetInstantCloneOperationTimeOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneOperationTimeOk() (*int64, bool)`

GetInstantCloneOperationTimeOk returns a tuple with the InstantCloneOperationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantCloneOperationTime

`func (o *FarmProvisioningStatusInfoV2) SetInstantCloneOperationTime(v int64)`

SetInstantCloneOperationTime sets InstantCloneOperationTime field to given value.

### HasInstantCloneOperationTime

`func (o *FarmProvisioningStatusInfoV2) HasInstantCloneOperationTime() bool`

HasInstantCloneOperationTime returns a boolean if a field has been set.

### GetInstantClonePendingImStreamId

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImStreamId() string`

GetInstantClonePendingImStreamId returns the InstantClonePendingImStreamId field if non-nil, zero value otherwise.

### GetInstantClonePendingImStreamIdOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImStreamIdOk() (*string, bool)`

GetInstantClonePendingImStreamIdOk returns a tuple with the InstantClonePendingImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImStreamId

`func (o *FarmProvisioningStatusInfoV2) SetInstantClonePendingImStreamId(v string)`

SetInstantClonePendingImStreamId sets InstantClonePendingImStreamId field to given value.

### HasInstantClonePendingImStreamId

`func (o *FarmProvisioningStatusInfoV2) HasInstantClonePendingImStreamId() bool`

HasInstantClonePendingImStreamId returns a boolean if a field has been set.

### GetInstantClonePendingImTagId

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImTagId() string`

GetInstantClonePendingImTagId returns the InstantClonePendingImTagId field if non-nil, zero value otherwise.

### GetInstantClonePendingImTagIdOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImTagIdOk() (*string, bool)`

GetInstantClonePendingImTagIdOk returns a tuple with the InstantClonePendingImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImTagId

`func (o *FarmProvisioningStatusInfoV2) SetInstantClonePendingImTagId(v string)`

SetInstantClonePendingImTagId sets InstantClonePendingImTagId field to given value.

### HasInstantClonePendingImTagId

`func (o *FarmProvisioningStatusInfoV2) HasInstantClonePendingImTagId() bool`

HasInstantClonePendingImTagId returns a boolean if a field has been set.

### GetInstantClonePendingImageError

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageError() string`

GetInstantClonePendingImageError returns the InstantClonePendingImageError field if non-nil, zero value otherwise.

### GetInstantClonePendingImageErrorOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageErrorOk() (*string, bool)`

GetInstantClonePendingImageErrorOk returns a tuple with the InstantClonePendingImageError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageError

`func (o *FarmProvisioningStatusInfoV2) SetInstantClonePendingImageError(v string)`

SetInstantClonePendingImageError sets InstantClonePendingImageError field to given value.

### HasInstantClonePendingImageError

`func (o *FarmProvisioningStatusInfoV2) HasInstantClonePendingImageError() bool`

HasInstantClonePendingImageError returns a boolean if a field has been set.

### GetInstantClonePendingImageParentVmId

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageParentVmId() string`

GetInstantClonePendingImageParentVmId returns the InstantClonePendingImageParentVmId field if non-nil, zero value otherwise.

### GetInstantClonePendingImageParentVmIdOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageParentVmIdOk() (*string, bool)`

GetInstantClonePendingImageParentVmIdOk returns a tuple with the InstantClonePendingImageParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageParentVmId

`func (o *FarmProvisioningStatusInfoV2) SetInstantClonePendingImageParentVmId(v string)`

SetInstantClonePendingImageParentVmId sets InstantClonePendingImageParentVmId field to given value.

### HasInstantClonePendingImageParentVmId

`func (o *FarmProvisioningStatusInfoV2) HasInstantClonePendingImageParentVmId() bool`

HasInstantClonePendingImageParentVmId returns a boolean if a field has been set.

### GetInstantClonePendingImageProgress

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageProgress() int32`

GetInstantClonePendingImageProgress returns the InstantClonePendingImageProgress field if non-nil, zero value otherwise.

### GetInstantClonePendingImageProgressOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageProgressOk() (*int32, bool)`

GetInstantClonePendingImageProgressOk returns a tuple with the InstantClonePendingImageProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageProgress

`func (o *FarmProvisioningStatusInfoV2) SetInstantClonePendingImageProgress(v int32)`

SetInstantClonePendingImageProgress sets InstantClonePendingImageProgress field to given value.

### HasInstantClonePendingImageProgress

`func (o *FarmProvisioningStatusInfoV2) HasInstantClonePendingImageProgress() bool`

HasInstantClonePendingImageProgress returns a boolean if a field has been set.

### GetInstantClonePendingImageSnapshotId

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageSnapshotId() string`

GetInstantClonePendingImageSnapshotId returns the InstantClonePendingImageSnapshotId field if non-nil, zero value otherwise.

### GetInstantClonePendingImageSnapshotIdOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageSnapshotIdOk() (*string, bool)`

GetInstantClonePendingImageSnapshotIdOk returns a tuple with the InstantClonePendingImageSnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageSnapshotId

`func (o *FarmProvisioningStatusInfoV2) SetInstantClonePendingImageSnapshotId(v string)`

SetInstantClonePendingImageSnapshotId sets InstantClonePendingImageSnapshotId field to given value.

### HasInstantClonePendingImageSnapshotId

`func (o *FarmProvisioningStatusInfoV2) HasInstantClonePendingImageSnapshotId() bool`

HasInstantClonePendingImageSnapshotId returns a boolean if a field has been set.

### GetInstantClonePendingImageState

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageState() string`

GetInstantClonePendingImageState returns the InstantClonePendingImageState field if non-nil, zero value otherwise.

### GetInstantClonePendingImageStateOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantClonePendingImageStateOk() (*string, bool)`

GetInstantClonePendingImageStateOk returns a tuple with the InstantClonePendingImageState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageState

`func (o *FarmProvisioningStatusInfoV2) SetInstantClonePendingImageState(v string)`

SetInstantClonePendingImageState sets InstantClonePendingImageState field to given value.

### HasInstantClonePendingImageState

`func (o *FarmProvisioningStatusInfoV2) HasInstantClonePendingImageState() bool`

HasInstantClonePendingImageState returns a boolean if a field has been set.

### GetInstantCloneScheduledMaintenanceData

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneScheduledMaintenanceData() FarmScheduledMaintenanceInfo`

GetInstantCloneScheduledMaintenanceData returns the InstantCloneScheduledMaintenanceData field if non-nil, zero value otherwise.

### GetInstantCloneScheduledMaintenanceDataOk

`func (o *FarmProvisioningStatusInfoV2) GetInstantCloneScheduledMaintenanceDataOk() (*FarmScheduledMaintenanceInfo, bool)`

GetInstantCloneScheduledMaintenanceDataOk returns a tuple with the InstantCloneScheduledMaintenanceData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantCloneScheduledMaintenanceData

`func (o *FarmProvisioningStatusInfoV2) SetInstantCloneScheduledMaintenanceData(v FarmScheduledMaintenanceInfo)`

SetInstantCloneScheduledMaintenanceData sets InstantCloneScheduledMaintenanceData field to given value.

### HasInstantCloneScheduledMaintenanceData

`func (o *FarmProvisioningStatusInfoV2) HasInstantCloneScheduledMaintenanceData() bool`

HasInstantCloneScheduledMaintenanceData returns a boolean if a field has been set.

### GetLastProvisioningError

`func (o *FarmProvisioningStatusInfoV2) GetLastProvisioningError() string`

GetLastProvisioningError returns the LastProvisioningError field if non-nil, zero value otherwise.

### GetLastProvisioningErrorOk

`func (o *FarmProvisioningStatusInfoV2) GetLastProvisioningErrorOk() (*string, bool)`

GetLastProvisioningErrorOk returns a tuple with the LastProvisioningError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastProvisioningError

`func (o *FarmProvisioningStatusInfoV2) SetLastProvisioningError(v string)`

SetLastProvisioningError sets LastProvisioningError field to given value.

### HasLastProvisioningError

`func (o *FarmProvisioningStatusInfoV2) HasLastProvisioningError() bool`

HasLastProvisioningError returns a boolean if a field has been set.

### GetLastProvisioningErrorTime

`func (o *FarmProvisioningStatusInfoV2) GetLastProvisioningErrorTime() int64`

GetLastProvisioningErrorTime returns the LastProvisioningErrorTime field if non-nil, zero value otherwise.

### GetLastProvisioningErrorTimeOk

`func (o *FarmProvisioningStatusInfoV2) GetLastProvisioningErrorTimeOk() (*int64, bool)`

GetLastProvisioningErrorTimeOk returns a tuple with the LastProvisioningErrorTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastProvisioningErrorTime

`func (o *FarmProvisioningStatusInfoV2) SetLastProvisioningErrorTime(v int64)`

SetLastProvisioningErrorTime sets LastProvisioningErrorTime field to given value.

### HasLastProvisioningErrorTime

`func (o *FarmProvisioningStatusInfoV2) HasLastProvisioningErrorTime() bool`

HasLastProvisioningErrorTime returns a boolean if a field has been set.

### GetPendingComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningStatusInfoV2) GetPendingComputeProfileNumCoresPerSocket() int32`

GetPendingComputeProfileNumCoresPerSocket returns the PendingComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetPendingComputeProfileNumCoresPerSocketOk

`func (o *FarmProvisioningStatusInfoV2) GetPendingComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetPendingComputeProfileNumCoresPerSocketOk returns a tuple with the PendingComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningStatusInfoV2) SetPendingComputeProfileNumCoresPerSocket(v int32)`

SetPendingComputeProfileNumCoresPerSocket sets PendingComputeProfileNumCoresPerSocket field to given value.

### HasPendingComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningStatusInfoV2) HasPendingComputeProfileNumCoresPerSocket() bool`

HasPendingComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetPendingComputeProfileNumCpus

`func (o *FarmProvisioningStatusInfoV2) GetPendingComputeProfileNumCpus() int32`

GetPendingComputeProfileNumCpus returns the PendingComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetPendingComputeProfileNumCpusOk

`func (o *FarmProvisioningStatusInfoV2) GetPendingComputeProfileNumCpusOk() (*int32, bool)`

GetPendingComputeProfileNumCpusOk returns a tuple with the PendingComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingComputeProfileNumCpus

`func (o *FarmProvisioningStatusInfoV2) SetPendingComputeProfileNumCpus(v int32)`

SetPendingComputeProfileNumCpus sets PendingComputeProfileNumCpus field to given value.

### HasPendingComputeProfileNumCpus

`func (o *FarmProvisioningStatusInfoV2) HasPendingComputeProfileNumCpus() bool`

HasPendingComputeProfileNumCpus returns a boolean if a field has been set.

### GetPendingComputeProfileRamMb

`func (o *FarmProvisioningStatusInfoV2) GetPendingComputeProfileRamMb() int32`

GetPendingComputeProfileRamMb returns the PendingComputeProfileRamMb field if non-nil, zero value otherwise.

### GetPendingComputeProfileRamMbOk

`func (o *FarmProvisioningStatusInfoV2) GetPendingComputeProfileRamMbOk() (*int32, bool)`

GetPendingComputeProfileRamMbOk returns a tuple with the PendingComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingComputeProfileRamMb

`func (o *FarmProvisioningStatusInfoV2) SetPendingComputeProfileRamMb(v int32)`

SetPendingComputeProfileRamMb sets PendingComputeProfileRamMb field to given value.

### HasPendingComputeProfileRamMb

`func (o *FarmProvisioningStatusInfoV2) HasPendingComputeProfileRamMb() bool`

HasPendingComputeProfileRamMb returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


