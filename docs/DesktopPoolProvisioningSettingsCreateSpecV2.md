# DesktopPoolProvisioningSettingsCreateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddVirtualTpm** | Pointer to **bool** | Indicates whether to add Virtual TPM device. &lt;br&gt; Default value is false. | [optional] 
**BaseSnapshotId** | Pointer to **string** | This property can be set only when source is set to INSTANT_CLONE, vm_template_id is unset and parent_vm_id is set. | [optional] 
**ComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the number of cores per socket for the CPU in the compute profile to be configured on clones. If set, both compute_profile_num_cpus and compute_profile_ram_mb need to be set.  | [optional] 
**ComputeProfileNumCpus** | Pointer to **int32** | Indicates the number of CPUs in the compute profile to be configured on clones. If set, this must be a multiple of compute_profile_num_cores_per_socket. | [optional] 
**ComputeProfileRamMb** | Pointer to **int32** | Indicates the RAM in MB in the compute profile to be configured on clones. | [optional] 
**DatacenterId** | Pointer to **string** | Datacenter within which the desktop pool is configured. | [optional] 
**HostOrClusterId** | **string** | Host or cluster where the machines are deployed in. &lt;br&gt; For Instant clone desktops it can only be set to a cluster id. &lt;br&gt; | 
**ImStreamId** | Pointer to **string** | Applicable To: Automated desktop pools.&lt;br&gt;This is required when vm_template_id, parent_vm_id and base_snapshot_id are not set. | [optional] 
**ImTagId** | Pointer to **string** | Applicable To: Automated desktop pools.&lt;br&gt;This is required when im_stream_Id is set. | [optional] 
**ParentVmId** | Pointer to **string** | This property can be set only when source is set to INSTANT_CLONE. | [optional] 
**ResourcePoolId** | **string** | Resource pool to deploy the machines. | 
**VmFolderId** | **string** | VM folder where the machines are deployed to. | 
**VmTemplateId** | Pointer to **string** | Applicable To: Full clone desktop pools.&lt;br&gt;This is required if parent_vm_id and base_snapshot_id are not set. &lt;br&gt; | [optional] 

## Methods

### NewDesktopPoolProvisioningSettingsCreateSpecV2

`func NewDesktopPoolProvisioningSettingsCreateSpecV2(hostOrClusterId string, resourcePoolId string, vmFolderId string, ) *DesktopPoolProvisioningSettingsCreateSpecV2`

NewDesktopPoolProvisioningSettingsCreateSpecV2 instantiates a new DesktopPoolProvisioningSettingsCreateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesktopPoolProvisioningSettingsCreateSpecV2WithDefaults

`func NewDesktopPoolProvisioningSettingsCreateSpecV2WithDefaults() *DesktopPoolProvisioningSettingsCreateSpecV2`

NewDesktopPoolProvisioningSettingsCreateSpecV2WithDefaults instantiates a new DesktopPoolProvisioningSettingsCreateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddVirtualTpm

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetAddVirtualTpm() bool`

GetAddVirtualTpm returns the AddVirtualTpm field if non-nil, zero value otherwise.

### GetAddVirtualTpmOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetAddVirtualTpmOk() (*bool, bool)`

GetAddVirtualTpmOk returns a tuple with the AddVirtualTpm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddVirtualTpm

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetAddVirtualTpm(v bool)`

SetAddVirtualTpm sets AddVirtualTpm field to given value.

### HasAddVirtualTpm

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasAddVirtualTpm() bool`

HasAddVirtualTpm returns a boolean if a field has been set.

### GetBaseSnapshotId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetBaseSnapshotId() string`

GetBaseSnapshotId returns the BaseSnapshotId field if non-nil, zero value otherwise.

### GetBaseSnapshotIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetBaseSnapshotIdOk() (*string, bool)`

GetBaseSnapshotIdOk returns a tuple with the BaseSnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSnapshotId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetBaseSnapshotId(v string)`

SetBaseSnapshotId sets BaseSnapshotId field to given value.

### HasBaseSnapshotId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasBaseSnapshotId() bool`

HasBaseSnapshotId returns a boolean if a field has been set.

### GetComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetComputeProfileNumCoresPerSocket() int32`

GetComputeProfileNumCoresPerSocket returns the ComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetComputeProfileNumCoresPerSocketOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetComputeProfileNumCoresPerSocketOk returns a tuple with the ComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetComputeProfileNumCoresPerSocket(v int32)`

SetComputeProfileNumCoresPerSocket sets ComputeProfileNumCoresPerSocket field to given value.

### HasComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasComputeProfileNumCoresPerSocket() bool`

HasComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetComputeProfileNumCpus

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetComputeProfileNumCpus() int32`

GetComputeProfileNumCpus returns the ComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetComputeProfileNumCpusOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetComputeProfileNumCpusOk() (*int32, bool)`

GetComputeProfileNumCpusOk returns a tuple with the ComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCpus

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetComputeProfileNumCpus(v int32)`

SetComputeProfileNumCpus sets ComputeProfileNumCpus field to given value.

### HasComputeProfileNumCpus

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasComputeProfileNumCpus() bool`

HasComputeProfileNumCpus returns a boolean if a field has been set.

### GetComputeProfileRamMb

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetComputeProfileRamMb() int32`

GetComputeProfileRamMb returns the ComputeProfileRamMb field if non-nil, zero value otherwise.

### GetComputeProfileRamMbOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetComputeProfileRamMbOk() (*int32, bool)`

GetComputeProfileRamMbOk returns a tuple with the ComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileRamMb

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetComputeProfileRamMb(v int32)`

SetComputeProfileRamMb sets ComputeProfileRamMb field to given value.

### HasComputeProfileRamMb

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasComputeProfileRamMb() bool`

HasComputeProfileRamMb returns a boolean if a field has been set.

### GetDatacenterId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetDatacenterId() string`

GetDatacenterId returns the DatacenterId field if non-nil, zero value otherwise.

### GetDatacenterIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetDatacenterIdOk() (*string, bool)`

GetDatacenterIdOk returns a tuple with the DatacenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatacenterId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetDatacenterId(v string)`

SetDatacenterId sets DatacenterId field to given value.

### HasDatacenterId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasDatacenterId() bool`

HasDatacenterId returns a boolean if a field has been set.

### GetHostOrClusterId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetHostOrClusterId() string`

GetHostOrClusterId returns the HostOrClusterId field if non-nil, zero value otherwise.

### GetHostOrClusterIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetHostOrClusterIdOk() (*string, bool)`

GetHostOrClusterIdOk returns a tuple with the HostOrClusterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostOrClusterId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetHostOrClusterId(v string)`

SetHostOrClusterId sets HostOrClusterId field to given value.


### GetImStreamId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetImStreamId() string`

GetImStreamId returns the ImStreamId field if non-nil, zero value otherwise.

### GetImStreamIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetImStreamIdOk() (*string, bool)`

GetImStreamIdOk returns a tuple with the ImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImStreamId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetImStreamId(v string)`

SetImStreamId sets ImStreamId field to given value.

### HasImStreamId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasImStreamId() bool`

HasImStreamId returns a boolean if a field has been set.

### GetImTagId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetImTagId() string`

GetImTagId returns the ImTagId field if non-nil, zero value otherwise.

### GetImTagIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetImTagIdOk() (*string, bool)`

GetImTagIdOk returns a tuple with the ImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImTagId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetImTagId(v string)`

SetImTagId sets ImTagId field to given value.

### HasImTagId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasImTagId() bool`

HasImTagId returns a boolean if a field has been set.

### GetParentVmId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetParentVmId() string`

GetParentVmId returns the ParentVmId field if non-nil, zero value otherwise.

### GetParentVmIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetParentVmIdOk() (*string, bool)`

GetParentVmIdOk returns a tuple with the ParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentVmId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetParentVmId(v string)`

SetParentVmId sets ParentVmId field to given value.

### HasParentVmId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasParentVmId() bool`

HasParentVmId returns a boolean if a field has been set.

### GetResourcePoolId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetResourcePoolId() string`

GetResourcePoolId returns the ResourcePoolId field if non-nil, zero value otherwise.

### GetResourcePoolIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetResourcePoolIdOk() (*string, bool)`

GetResourcePoolIdOk returns a tuple with the ResourcePoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourcePoolId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetResourcePoolId(v string)`

SetResourcePoolId sets ResourcePoolId field to given value.


### GetVmFolderId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetVmFolderId() string`

GetVmFolderId returns the VmFolderId field if non-nil, zero value otherwise.

### GetVmFolderIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetVmFolderIdOk() (*string, bool)`

GetVmFolderIdOk returns a tuple with the VmFolderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVmFolderId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetVmFolderId(v string)`

SetVmFolderId sets VmFolderId field to given value.


### GetVmTemplateId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetVmTemplateId() string`

GetVmTemplateId returns the VmTemplateId field if non-nil, zero value otherwise.

### GetVmTemplateIdOk

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) GetVmTemplateIdOk() (*string, bool)`

GetVmTemplateIdOk returns a tuple with the VmTemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVmTemplateId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) SetVmTemplateId(v string)`

SetVmTemplateId sets VmTemplateId field to given value.

### HasVmTemplateId

`func (o *DesktopPoolProvisioningSettingsCreateSpecV2) HasVmTemplateId() bool`

HasVmTemplateId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


