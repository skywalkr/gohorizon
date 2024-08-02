# FarmProvisioningSettingsCreateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseSnapshotId** | Pointer to **string** | Current image snapshot for instant clone farm. | [optional] 
**ComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the number of cores per socket for the CPU in the compute profile to be configured on clones. If set, both compute_profile_num_cpus and compute_profile_ram_mb need to be set.  | [optional] 
**ComputeProfileNumCpus** | Pointer to **int32** | Indicates the number of CPUs in the compute profile to be configured on clones. If set, this must be a multiple of compute_profile_num_cores_per_socket. | [optional] 
**ComputeProfileRamMb** | Pointer to **int32** | Indicates the RAM in MB in the compute profile to be configured on clones. | [optional] 
**DatacenterId** | **string** | Datacenter within which the farm is configured | 
**HostOrClusterId** | **string** | Host or cluster where the machines are deployed in. For Instant clone farms it can be only be a cluster id. | 
**ImStreamId** | Pointer to **string** | Image management stream used in the farm. This is required if parent_vm_id and base_snapshot_id are not set. | [optional] 
**ImTagId** | Pointer to **string** | Image management tag used in the farm. This is required if im_stream_id is set. | [optional] 
**ParentVmId** | Pointer to **string** | Current VM image for instant clone farm. | [optional] 
**ResourcePoolId** | **string** | Resource pool to deploy the RDS Servers. | 
**VmFolderId** | **string** | VM folder to deploy the RDS Servers to. | 

## Methods

### NewFarmProvisioningSettingsCreateSpecV2

`func NewFarmProvisioningSettingsCreateSpecV2(datacenterId string, hostOrClusterId string, resourcePoolId string, vmFolderId string, ) *FarmProvisioningSettingsCreateSpecV2`

NewFarmProvisioningSettingsCreateSpecV2 instantiates a new FarmProvisioningSettingsCreateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmProvisioningSettingsCreateSpecV2WithDefaults

`func NewFarmProvisioningSettingsCreateSpecV2WithDefaults() *FarmProvisioningSettingsCreateSpecV2`

NewFarmProvisioningSettingsCreateSpecV2WithDefaults instantiates a new FarmProvisioningSettingsCreateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseSnapshotId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetBaseSnapshotId() string`

GetBaseSnapshotId returns the BaseSnapshotId field if non-nil, zero value otherwise.

### GetBaseSnapshotIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetBaseSnapshotIdOk() (*string, bool)`

GetBaseSnapshotIdOk returns a tuple with the BaseSnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSnapshotId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetBaseSnapshotId(v string)`

SetBaseSnapshotId sets BaseSnapshotId field to given value.

### HasBaseSnapshotId

`func (o *FarmProvisioningSettingsCreateSpecV2) HasBaseSnapshotId() bool`

HasBaseSnapshotId returns a boolean if a field has been set.

### GetComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningSettingsCreateSpecV2) GetComputeProfileNumCoresPerSocket() int32`

GetComputeProfileNumCoresPerSocket returns the ComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetComputeProfileNumCoresPerSocketOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetComputeProfileNumCoresPerSocketOk returns a tuple with the ComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningSettingsCreateSpecV2) SetComputeProfileNumCoresPerSocket(v int32)`

SetComputeProfileNumCoresPerSocket sets ComputeProfileNumCoresPerSocket field to given value.

### HasComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningSettingsCreateSpecV2) HasComputeProfileNumCoresPerSocket() bool`

HasComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetComputeProfileNumCpus

`func (o *FarmProvisioningSettingsCreateSpecV2) GetComputeProfileNumCpus() int32`

GetComputeProfileNumCpus returns the ComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetComputeProfileNumCpusOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetComputeProfileNumCpusOk() (*int32, bool)`

GetComputeProfileNumCpusOk returns a tuple with the ComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCpus

`func (o *FarmProvisioningSettingsCreateSpecV2) SetComputeProfileNumCpus(v int32)`

SetComputeProfileNumCpus sets ComputeProfileNumCpus field to given value.

### HasComputeProfileNumCpus

`func (o *FarmProvisioningSettingsCreateSpecV2) HasComputeProfileNumCpus() bool`

HasComputeProfileNumCpus returns a boolean if a field has been set.

### GetComputeProfileRamMb

`func (o *FarmProvisioningSettingsCreateSpecV2) GetComputeProfileRamMb() int32`

GetComputeProfileRamMb returns the ComputeProfileRamMb field if non-nil, zero value otherwise.

### GetComputeProfileRamMbOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetComputeProfileRamMbOk() (*int32, bool)`

GetComputeProfileRamMbOk returns a tuple with the ComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileRamMb

`func (o *FarmProvisioningSettingsCreateSpecV2) SetComputeProfileRamMb(v int32)`

SetComputeProfileRamMb sets ComputeProfileRamMb field to given value.

### HasComputeProfileRamMb

`func (o *FarmProvisioningSettingsCreateSpecV2) HasComputeProfileRamMb() bool`

HasComputeProfileRamMb returns a boolean if a field has been set.

### GetDatacenterId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetDatacenterId() string`

GetDatacenterId returns the DatacenterId field if non-nil, zero value otherwise.

### GetDatacenterIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetDatacenterIdOk() (*string, bool)`

GetDatacenterIdOk returns a tuple with the DatacenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatacenterId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetDatacenterId(v string)`

SetDatacenterId sets DatacenterId field to given value.


### GetHostOrClusterId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetHostOrClusterId() string`

GetHostOrClusterId returns the HostOrClusterId field if non-nil, zero value otherwise.

### GetHostOrClusterIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetHostOrClusterIdOk() (*string, bool)`

GetHostOrClusterIdOk returns a tuple with the HostOrClusterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostOrClusterId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetHostOrClusterId(v string)`

SetHostOrClusterId sets HostOrClusterId field to given value.


### GetImStreamId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetImStreamId() string`

GetImStreamId returns the ImStreamId field if non-nil, zero value otherwise.

### GetImStreamIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetImStreamIdOk() (*string, bool)`

GetImStreamIdOk returns a tuple with the ImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImStreamId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetImStreamId(v string)`

SetImStreamId sets ImStreamId field to given value.

### HasImStreamId

`func (o *FarmProvisioningSettingsCreateSpecV2) HasImStreamId() bool`

HasImStreamId returns a boolean if a field has been set.

### GetImTagId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetImTagId() string`

GetImTagId returns the ImTagId field if non-nil, zero value otherwise.

### GetImTagIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetImTagIdOk() (*string, bool)`

GetImTagIdOk returns a tuple with the ImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImTagId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetImTagId(v string)`

SetImTagId sets ImTagId field to given value.

### HasImTagId

`func (o *FarmProvisioningSettingsCreateSpecV2) HasImTagId() bool`

HasImTagId returns a boolean if a field has been set.

### GetParentVmId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetParentVmId() string`

GetParentVmId returns the ParentVmId field if non-nil, zero value otherwise.

### GetParentVmIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetParentVmIdOk() (*string, bool)`

GetParentVmIdOk returns a tuple with the ParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentVmId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetParentVmId(v string)`

SetParentVmId sets ParentVmId field to given value.

### HasParentVmId

`func (o *FarmProvisioningSettingsCreateSpecV2) HasParentVmId() bool`

HasParentVmId returns a boolean if a field has been set.

### GetResourcePoolId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetResourcePoolId() string`

GetResourcePoolId returns the ResourcePoolId field if non-nil, zero value otherwise.

### GetResourcePoolIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetResourcePoolIdOk() (*string, bool)`

GetResourcePoolIdOk returns a tuple with the ResourcePoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourcePoolId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetResourcePoolId(v string)`

SetResourcePoolId sets ResourcePoolId field to given value.


### GetVmFolderId

`func (o *FarmProvisioningSettingsCreateSpecV2) GetVmFolderId() string`

GetVmFolderId returns the VmFolderId field if non-nil, zero value otherwise.

### GetVmFolderIdOk

`func (o *FarmProvisioningSettingsCreateSpecV2) GetVmFolderIdOk() (*string, bool)`

GetVmFolderIdOk returns a tuple with the VmFolderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVmFolderId

`func (o *FarmProvisioningSettingsCreateSpecV2) SetVmFolderId(v string)`

SetVmFolderId sets VmFolderId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


