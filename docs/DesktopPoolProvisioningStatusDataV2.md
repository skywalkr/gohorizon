# DesktopPoolProvisioningStatusDataV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstantCloneCurrentImageState** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;This represents the state of the current image of this instant clone desktop pool. * READY: This is the state of the current image after successful completion of creation operation. At this stage the current image is ready to be used to create the instant clones. Please note that this state is also reached from UNPUBLISHING state on successful completion of editing of cluster or editing of datastore(s) operations. * FAILED: This is the state of the current image if instant clone delete operation has failed or timed out. * PENDING_UNPUBLISH: This is the state of the current image before instant clone delete or cluster edit or datastore(s) edit operation(s) begins. * UNPUBLISHING: This is the transient state of the current image when instant clone delete or cluster edit or datastore(s) edit operation(s) is going on. | [optional] 
**InstantCloneOperation** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;The operation that this instant clone desktop pool is undergoing. * NONE: There is no current operation on the desktop pool. * INITIAL_PUBLISH: The desktop pool has just been created and is undergoing initial publishing. * SCHEDULE_PUSH_IMAGE: The push operation is scheduled on the desktop pool. * CANCEL_SCHEDULED_PUSH_IMAGE: The scheduled push operation on the desktop pool is being cancelled. * INFRASTRUCTURE_CHANGE: A cluster or datastore change operation was requested for the desktop pool. * FINAL_UNPUBLISH: A desktop pool has been deleted and is undergoing final unpublishing. | [optional] 
**InstantClonePendingImStreamId** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;Pending image management stream for instant clone desktop pools.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**InstantClonePendingImTagId** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;Pending image management tag for instant clone desktop pools&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**InstantClonePendingImageError** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;This represents the error message if publishing of push image operation is failed. | [optional] 
**InstantClonePendingImageParentVmId** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;Pending base image VM for instant clone desktop pools. This is used to return the information about the parent VM of the pending Image. | [optional] 
**InstantClonePendingImageProgress** | Pointer to **int32** | Applicable To: instant clone automated desktop pools.&lt;br&gt;This represents the pending image publish progress in percentage for an instant clone desktop pool. | [optional] 
**InstantClonePendingImageSnapshotId** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;Pending base image snapshot for instant clone desktop pools. This is used to return the information about the snapshot of the pending image. | [optional] 
**InstantClonePendingImageState** | Pointer to **string** | Applicable To: instant clone automated desktop pools.&lt;br&gt;This represents the state of the pending image of this instant clone desktop pool. This will be null when there is no pending image for the desktop pool. * PENDING_PUBLISH: This is the initial transient state of the pending image before instant clone creation operation has started. * PUBLISHING: This is the transient state of the pending image when creation of instant clone operation is going on. * UNPUBLISHING: This is the transient state of the pending image when instant clone delete or cluster edit or datastore(s) edit operation(s) is going on. * READY: This is the state of the pending image after successful publish of the pending image and before that image has been upgraded to the current image. This is normally seen after successful publish for a push image which has been scheduled to trigger at a later time. * FAILED: This is the state of the pending image if creation of instant clone operation has failed or timed out. * READY_HELD: This is the state of the pending image after performing a selective resync operation, in which the image may be applied to some VMs in the desktop pool/farm. | [optional] 
**InstantClonePushImageSettings** | Pointer to [**DesktopPoolInstantClonePushImageSettings**](DesktopPoolInstantClonePushImageSettings.md) |  | [optional] 
**LastProvisioningError** | Pointer to **string** | String message detailing the last provisioning error on this desktop pool while stop_provisioning_on_error is enabled. This will be cleared when enable_provisioning is updated to true. | [optional] 
**LastProvisioningErrorTime** | Pointer to **int64** | Time the last provisioning error occurred on this desktop while stop_provisioning_on_error is enabled. This will be cleared when enable_provisioning is updated to true. Measured as epoch time. | [optional] 
**PendingComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the pending number of cores per socket for the CPU in the compute profile configured on clones. | [optional] 
**PendingComputeProfileNumCpus** | Pointer to **int32** | Indicates the pending number of CPUs in the compute profile configured on clones. | [optional] 
**PendingComputeProfileRamMb** | Pointer to **int32** | Indicates the pending RAM in MB in the compute profile configured on clones. | [optional] 

## Methods

### NewDesktopPoolProvisioningStatusDataV2

`func NewDesktopPoolProvisioningStatusDataV2() *DesktopPoolProvisioningStatusDataV2`

NewDesktopPoolProvisioningStatusDataV2 instantiates a new DesktopPoolProvisioningStatusDataV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesktopPoolProvisioningStatusDataV2WithDefaults

`func NewDesktopPoolProvisioningStatusDataV2WithDefaults() *DesktopPoolProvisioningStatusDataV2`

NewDesktopPoolProvisioningStatusDataV2WithDefaults instantiates a new DesktopPoolProvisioningStatusDataV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstantCloneCurrentImageState

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantCloneCurrentImageState() string`

GetInstantCloneCurrentImageState returns the InstantCloneCurrentImageState field if non-nil, zero value otherwise.

### GetInstantCloneCurrentImageStateOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantCloneCurrentImageStateOk() (*string, bool)`

GetInstantCloneCurrentImageStateOk returns a tuple with the InstantCloneCurrentImageState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantCloneCurrentImageState

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantCloneCurrentImageState(v string)`

SetInstantCloneCurrentImageState sets InstantCloneCurrentImageState field to given value.

### HasInstantCloneCurrentImageState

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantCloneCurrentImageState() bool`

HasInstantCloneCurrentImageState returns a boolean if a field has been set.

### GetInstantCloneOperation

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantCloneOperation() string`

GetInstantCloneOperation returns the InstantCloneOperation field if non-nil, zero value otherwise.

### GetInstantCloneOperationOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantCloneOperationOk() (*string, bool)`

GetInstantCloneOperationOk returns a tuple with the InstantCloneOperation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantCloneOperation

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantCloneOperation(v string)`

SetInstantCloneOperation sets InstantCloneOperation field to given value.

### HasInstantCloneOperation

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantCloneOperation() bool`

HasInstantCloneOperation returns a boolean if a field has been set.

### GetInstantClonePendingImStreamId

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImStreamId() string`

GetInstantClonePendingImStreamId returns the InstantClonePendingImStreamId field if non-nil, zero value otherwise.

### GetInstantClonePendingImStreamIdOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImStreamIdOk() (*string, bool)`

GetInstantClonePendingImStreamIdOk returns a tuple with the InstantClonePendingImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImStreamId

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePendingImStreamId(v string)`

SetInstantClonePendingImStreamId sets InstantClonePendingImStreamId field to given value.

### HasInstantClonePendingImStreamId

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePendingImStreamId() bool`

HasInstantClonePendingImStreamId returns a boolean if a field has been set.

### GetInstantClonePendingImTagId

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImTagId() string`

GetInstantClonePendingImTagId returns the InstantClonePendingImTagId field if non-nil, zero value otherwise.

### GetInstantClonePendingImTagIdOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImTagIdOk() (*string, bool)`

GetInstantClonePendingImTagIdOk returns a tuple with the InstantClonePendingImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImTagId

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePendingImTagId(v string)`

SetInstantClonePendingImTagId sets InstantClonePendingImTagId field to given value.

### HasInstantClonePendingImTagId

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePendingImTagId() bool`

HasInstantClonePendingImTagId returns a boolean if a field has been set.

### GetInstantClonePendingImageError

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageError() string`

GetInstantClonePendingImageError returns the InstantClonePendingImageError field if non-nil, zero value otherwise.

### GetInstantClonePendingImageErrorOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageErrorOk() (*string, bool)`

GetInstantClonePendingImageErrorOk returns a tuple with the InstantClonePendingImageError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageError

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePendingImageError(v string)`

SetInstantClonePendingImageError sets InstantClonePendingImageError field to given value.

### HasInstantClonePendingImageError

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePendingImageError() bool`

HasInstantClonePendingImageError returns a boolean if a field has been set.

### GetInstantClonePendingImageParentVmId

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageParentVmId() string`

GetInstantClonePendingImageParentVmId returns the InstantClonePendingImageParentVmId field if non-nil, zero value otherwise.

### GetInstantClonePendingImageParentVmIdOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageParentVmIdOk() (*string, bool)`

GetInstantClonePendingImageParentVmIdOk returns a tuple with the InstantClonePendingImageParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageParentVmId

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePendingImageParentVmId(v string)`

SetInstantClonePendingImageParentVmId sets InstantClonePendingImageParentVmId field to given value.

### HasInstantClonePendingImageParentVmId

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePendingImageParentVmId() bool`

HasInstantClonePendingImageParentVmId returns a boolean if a field has been set.

### GetInstantClonePendingImageProgress

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageProgress() int32`

GetInstantClonePendingImageProgress returns the InstantClonePendingImageProgress field if non-nil, zero value otherwise.

### GetInstantClonePendingImageProgressOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageProgressOk() (*int32, bool)`

GetInstantClonePendingImageProgressOk returns a tuple with the InstantClonePendingImageProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageProgress

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePendingImageProgress(v int32)`

SetInstantClonePendingImageProgress sets InstantClonePendingImageProgress field to given value.

### HasInstantClonePendingImageProgress

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePendingImageProgress() bool`

HasInstantClonePendingImageProgress returns a boolean if a field has been set.

### GetInstantClonePendingImageSnapshotId

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageSnapshotId() string`

GetInstantClonePendingImageSnapshotId returns the InstantClonePendingImageSnapshotId field if non-nil, zero value otherwise.

### GetInstantClonePendingImageSnapshotIdOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageSnapshotIdOk() (*string, bool)`

GetInstantClonePendingImageSnapshotIdOk returns a tuple with the InstantClonePendingImageSnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageSnapshotId

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePendingImageSnapshotId(v string)`

SetInstantClonePendingImageSnapshotId sets InstantClonePendingImageSnapshotId field to given value.

### HasInstantClonePendingImageSnapshotId

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePendingImageSnapshotId() bool`

HasInstantClonePendingImageSnapshotId returns a boolean if a field has been set.

### GetInstantClonePendingImageState

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageState() string`

GetInstantClonePendingImageState returns the InstantClonePendingImageState field if non-nil, zero value otherwise.

### GetInstantClonePendingImageStateOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePendingImageStateOk() (*string, bool)`

GetInstantClonePendingImageStateOk returns a tuple with the InstantClonePendingImageState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePendingImageState

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePendingImageState(v string)`

SetInstantClonePendingImageState sets InstantClonePendingImageState field to given value.

### HasInstantClonePendingImageState

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePendingImageState() bool`

HasInstantClonePendingImageState returns a boolean if a field has been set.

### GetInstantClonePushImageSettings

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePushImageSettings() DesktopPoolInstantClonePushImageSettings`

GetInstantClonePushImageSettings returns the InstantClonePushImageSettings field if non-nil, zero value otherwise.

### GetInstantClonePushImageSettingsOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetInstantClonePushImageSettingsOk() (*DesktopPoolInstantClonePushImageSettings, bool)`

GetInstantClonePushImageSettingsOk returns a tuple with the InstantClonePushImageSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantClonePushImageSettings

`func (o *DesktopPoolProvisioningStatusDataV2) SetInstantClonePushImageSettings(v DesktopPoolInstantClonePushImageSettings)`

SetInstantClonePushImageSettings sets InstantClonePushImageSettings field to given value.

### HasInstantClonePushImageSettings

`func (o *DesktopPoolProvisioningStatusDataV2) HasInstantClonePushImageSettings() bool`

HasInstantClonePushImageSettings returns a boolean if a field has been set.

### GetLastProvisioningError

`func (o *DesktopPoolProvisioningStatusDataV2) GetLastProvisioningError() string`

GetLastProvisioningError returns the LastProvisioningError field if non-nil, zero value otherwise.

### GetLastProvisioningErrorOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetLastProvisioningErrorOk() (*string, bool)`

GetLastProvisioningErrorOk returns a tuple with the LastProvisioningError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastProvisioningError

`func (o *DesktopPoolProvisioningStatusDataV2) SetLastProvisioningError(v string)`

SetLastProvisioningError sets LastProvisioningError field to given value.

### HasLastProvisioningError

`func (o *DesktopPoolProvisioningStatusDataV2) HasLastProvisioningError() bool`

HasLastProvisioningError returns a boolean if a field has been set.

### GetLastProvisioningErrorTime

`func (o *DesktopPoolProvisioningStatusDataV2) GetLastProvisioningErrorTime() int64`

GetLastProvisioningErrorTime returns the LastProvisioningErrorTime field if non-nil, zero value otherwise.

### GetLastProvisioningErrorTimeOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetLastProvisioningErrorTimeOk() (*int64, bool)`

GetLastProvisioningErrorTimeOk returns a tuple with the LastProvisioningErrorTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastProvisioningErrorTime

`func (o *DesktopPoolProvisioningStatusDataV2) SetLastProvisioningErrorTime(v int64)`

SetLastProvisioningErrorTime sets LastProvisioningErrorTime field to given value.

### HasLastProvisioningErrorTime

`func (o *DesktopPoolProvisioningStatusDataV2) HasLastProvisioningErrorTime() bool`

HasLastProvisioningErrorTime returns a boolean if a field has been set.

### GetPendingComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningStatusDataV2) GetPendingComputeProfileNumCoresPerSocket() int32`

GetPendingComputeProfileNumCoresPerSocket returns the PendingComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetPendingComputeProfileNumCoresPerSocketOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetPendingComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetPendingComputeProfileNumCoresPerSocketOk returns a tuple with the PendingComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningStatusDataV2) SetPendingComputeProfileNumCoresPerSocket(v int32)`

SetPendingComputeProfileNumCoresPerSocket sets PendingComputeProfileNumCoresPerSocket field to given value.

### HasPendingComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningStatusDataV2) HasPendingComputeProfileNumCoresPerSocket() bool`

HasPendingComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetPendingComputeProfileNumCpus

`func (o *DesktopPoolProvisioningStatusDataV2) GetPendingComputeProfileNumCpus() int32`

GetPendingComputeProfileNumCpus returns the PendingComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetPendingComputeProfileNumCpusOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetPendingComputeProfileNumCpusOk() (*int32, bool)`

GetPendingComputeProfileNumCpusOk returns a tuple with the PendingComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingComputeProfileNumCpus

`func (o *DesktopPoolProvisioningStatusDataV2) SetPendingComputeProfileNumCpus(v int32)`

SetPendingComputeProfileNumCpus sets PendingComputeProfileNumCpus field to given value.

### HasPendingComputeProfileNumCpus

`func (o *DesktopPoolProvisioningStatusDataV2) HasPendingComputeProfileNumCpus() bool`

HasPendingComputeProfileNumCpus returns a boolean if a field has been set.

### GetPendingComputeProfileRamMb

`func (o *DesktopPoolProvisioningStatusDataV2) GetPendingComputeProfileRamMb() int32`

GetPendingComputeProfileRamMb returns the PendingComputeProfileRamMb field if non-nil, zero value otherwise.

### GetPendingComputeProfileRamMbOk

`func (o *DesktopPoolProvisioningStatusDataV2) GetPendingComputeProfileRamMbOk() (*int32, bool)`

GetPendingComputeProfileRamMbOk returns a tuple with the PendingComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingComputeProfileRamMb

`func (o *DesktopPoolProvisioningStatusDataV2) SetPendingComputeProfileRamMb(v int32)`

SetPendingComputeProfileRamMb sets PendingComputeProfileRamMb field to given value.

### HasPendingComputeProfileRamMb

`func (o *DesktopPoolProvisioningStatusDataV2) HasPendingComputeProfileRamMb() bool`

HasPendingComputeProfileRamMb returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


