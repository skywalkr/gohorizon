# FarmProvisioningSettingsInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseSnapshotId** | Pointer to **string** | Current image snapshot for instant clone farm. | [optional] 
**ComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the number of cores per socket for the CPU in the compute profile configured on clones. | [optional] 
**ComputeProfileNumCpus** | Pointer to **int32** | Indicates the number of CPUs in the compute profile configured on clones. | [optional] 
**ComputeProfileRamMb** | Pointer to **int32** | Indicates the RAM in MB in the compute profile configured on clones. | [optional] 
**DatacenterId** | Pointer to **string** | Datacenter within which the farm is configured | [optional] 
**HostOrClusterId** | Pointer to **string** | Host or cluster where the machines are deployed in. | [optional] 
**ImStreamId** | Pointer to **string** | Image management stream used in the farm.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**ImTagId** | Pointer to **string** | Image management tag used in the farm.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**ParentVmId** | Pointer to **string** | Current VM image for instant clone farm. | [optional] 
**ResourcePoolId** | Pointer to **string** | Resource pool to deploy the RDS Servers. | [optional] 
**VmFolderId** | Pointer to **string** | VM folder to deploy the RDS Servers to. | [optional] 

## Methods

### NewFarmProvisioningSettingsInfoV2

`func NewFarmProvisioningSettingsInfoV2() *FarmProvisioningSettingsInfoV2`

NewFarmProvisioningSettingsInfoV2 instantiates a new FarmProvisioningSettingsInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmProvisioningSettingsInfoV2WithDefaults

`func NewFarmProvisioningSettingsInfoV2WithDefaults() *FarmProvisioningSettingsInfoV2`

NewFarmProvisioningSettingsInfoV2WithDefaults instantiates a new FarmProvisioningSettingsInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseSnapshotId

`func (o *FarmProvisioningSettingsInfoV2) GetBaseSnapshotId() string`

GetBaseSnapshotId returns the BaseSnapshotId field if non-nil, zero value otherwise.

### GetBaseSnapshotIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetBaseSnapshotIdOk() (*string, bool)`

GetBaseSnapshotIdOk returns a tuple with the BaseSnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSnapshotId

`func (o *FarmProvisioningSettingsInfoV2) SetBaseSnapshotId(v string)`

SetBaseSnapshotId sets BaseSnapshotId field to given value.

### HasBaseSnapshotId

`func (o *FarmProvisioningSettingsInfoV2) HasBaseSnapshotId() bool`

HasBaseSnapshotId returns a boolean if a field has been set.

### GetComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningSettingsInfoV2) GetComputeProfileNumCoresPerSocket() int32`

GetComputeProfileNumCoresPerSocket returns the ComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetComputeProfileNumCoresPerSocketOk

`func (o *FarmProvisioningSettingsInfoV2) GetComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetComputeProfileNumCoresPerSocketOk returns a tuple with the ComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningSettingsInfoV2) SetComputeProfileNumCoresPerSocket(v int32)`

SetComputeProfileNumCoresPerSocket sets ComputeProfileNumCoresPerSocket field to given value.

### HasComputeProfileNumCoresPerSocket

`func (o *FarmProvisioningSettingsInfoV2) HasComputeProfileNumCoresPerSocket() bool`

HasComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetComputeProfileNumCpus

`func (o *FarmProvisioningSettingsInfoV2) GetComputeProfileNumCpus() int32`

GetComputeProfileNumCpus returns the ComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetComputeProfileNumCpusOk

`func (o *FarmProvisioningSettingsInfoV2) GetComputeProfileNumCpusOk() (*int32, bool)`

GetComputeProfileNumCpusOk returns a tuple with the ComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCpus

`func (o *FarmProvisioningSettingsInfoV2) SetComputeProfileNumCpus(v int32)`

SetComputeProfileNumCpus sets ComputeProfileNumCpus field to given value.

### HasComputeProfileNumCpus

`func (o *FarmProvisioningSettingsInfoV2) HasComputeProfileNumCpus() bool`

HasComputeProfileNumCpus returns a boolean if a field has been set.

### GetComputeProfileRamMb

`func (o *FarmProvisioningSettingsInfoV2) GetComputeProfileRamMb() int32`

GetComputeProfileRamMb returns the ComputeProfileRamMb field if non-nil, zero value otherwise.

### GetComputeProfileRamMbOk

`func (o *FarmProvisioningSettingsInfoV2) GetComputeProfileRamMbOk() (*int32, bool)`

GetComputeProfileRamMbOk returns a tuple with the ComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileRamMb

`func (o *FarmProvisioningSettingsInfoV2) SetComputeProfileRamMb(v int32)`

SetComputeProfileRamMb sets ComputeProfileRamMb field to given value.

### HasComputeProfileRamMb

`func (o *FarmProvisioningSettingsInfoV2) HasComputeProfileRamMb() bool`

HasComputeProfileRamMb returns a boolean if a field has been set.

### GetDatacenterId

`func (o *FarmProvisioningSettingsInfoV2) GetDatacenterId() string`

GetDatacenterId returns the DatacenterId field if non-nil, zero value otherwise.

### GetDatacenterIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetDatacenterIdOk() (*string, bool)`

GetDatacenterIdOk returns a tuple with the DatacenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatacenterId

`func (o *FarmProvisioningSettingsInfoV2) SetDatacenterId(v string)`

SetDatacenterId sets DatacenterId field to given value.

### HasDatacenterId

`func (o *FarmProvisioningSettingsInfoV2) HasDatacenterId() bool`

HasDatacenterId returns a boolean if a field has been set.

### GetHostOrClusterId

`func (o *FarmProvisioningSettingsInfoV2) GetHostOrClusterId() string`

GetHostOrClusterId returns the HostOrClusterId field if non-nil, zero value otherwise.

### GetHostOrClusterIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetHostOrClusterIdOk() (*string, bool)`

GetHostOrClusterIdOk returns a tuple with the HostOrClusterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostOrClusterId

`func (o *FarmProvisioningSettingsInfoV2) SetHostOrClusterId(v string)`

SetHostOrClusterId sets HostOrClusterId field to given value.

### HasHostOrClusterId

`func (o *FarmProvisioningSettingsInfoV2) HasHostOrClusterId() bool`

HasHostOrClusterId returns a boolean if a field has been set.

### GetImStreamId

`func (o *FarmProvisioningSettingsInfoV2) GetImStreamId() string`

GetImStreamId returns the ImStreamId field if non-nil, zero value otherwise.

### GetImStreamIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetImStreamIdOk() (*string, bool)`

GetImStreamIdOk returns a tuple with the ImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImStreamId

`func (o *FarmProvisioningSettingsInfoV2) SetImStreamId(v string)`

SetImStreamId sets ImStreamId field to given value.

### HasImStreamId

`func (o *FarmProvisioningSettingsInfoV2) HasImStreamId() bool`

HasImStreamId returns a boolean if a field has been set.

### GetImTagId

`func (o *FarmProvisioningSettingsInfoV2) GetImTagId() string`

GetImTagId returns the ImTagId field if non-nil, zero value otherwise.

### GetImTagIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetImTagIdOk() (*string, bool)`

GetImTagIdOk returns a tuple with the ImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImTagId

`func (o *FarmProvisioningSettingsInfoV2) SetImTagId(v string)`

SetImTagId sets ImTagId field to given value.

### HasImTagId

`func (o *FarmProvisioningSettingsInfoV2) HasImTagId() bool`

HasImTagId returns a boolean if a field has been set.

### GetParentVmId

`func (o *FarmProvisioningSettingsInfoV2) GetParentVmId() string`

GetParentVmId returns the ParentVmId field if non-nil, zero value otherwise.

### GetParentVmIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetParentVmIdOk() (*string, bool)`

GetParentVmIdOk returns a tuple with the ParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentVmId

`func (o *FarmProvisioningSettingsInfoV2) SetParentVmId(v string)`

SetParentVmId sets ParentVmId field to given value.

### HasParentVmId

`func (o *FarmProvisioningSettingsInfoV2) HasParentVmId() bool`

HasParentVmId returns a boolean if a field has been set.

### GetResourcePoolId

`func (o *FarmProvisioningSettingsInfoV2) GetResourcePoolId() string`

GetResourcePoolId returns the ResourcePoolId field if non-nil, zero value otherwise.

### GetResourcePoolIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetResourcePoolIdOk() (*string, bool)`

GetResourcePoolIdOk returns a tuple with the ResourcePoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourcePoolId

`func (o *FarmProvisioningSettingsInfoV2) SetResourcePoolId(v string)`

SetResourcePoolId sets ResourcePoolId field to given value.

### HasResourcePoolId

`func (o *FarmProvisioningSettingsInfoV2) HasResourcePoolId() bool`

HasResourcePoolId returns a boolean if a field has been set.

### GetVmFolderId

`func (o *FarmProvisioningSettingsInfoV2) GetVmFolderId() string`

GetVmFolderId returns the VmFolderId field if non-nil, zero value otherwise.

### GetVmFolderIdOk

`func (o *FarmProvisioningSettingsInfoV2) GetVmFolderIdOk() (*string, bool)`

GetVmFolderIdOk returns a tuple with the VmFolderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVmFolderId

`func (o *FarmProvisioningSettingsInfoV2) SetVmFolderId(v string)`

SetVmFolderId sets VmFolderId field to given value.

### HasVmFolderId

`func (o *FarmProvisioningSettingsInfoV2) HasVmFolderId() bool`

HasVmFolderId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


