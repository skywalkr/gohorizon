# DesktopPoolProvisioningSettingsV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddVirtualTpm** | Pointer to **bool** | Whether to add Virtual TPM device. | [optional] 
**BaseSnapshotId** | Pointer to **string** | Applicable To: Linked/instant clone automated desktop pools.&lt;br&gt;Base image snapshot for linked clone desktop pool and current image snapshot for instant clone desktop pool. | [optional] 
**ComputeProfileNumCoresPerSocket** | Pointer to **int32** | Indicates the number of cores per socket for the CPU in the compute profile configured on clones. | [optional] 
**ComputeProfileNumCpus** | Pointer to **int32** | Indicates the number of CPUs in the compute profile configured on clones. | [optional] 
**ComputeProfileRamMb** | Pointer to **int32** | Indicates the RAM in MB in the compute profile configured on clones. | [optional] 
**DatacenterId** | Pointer to **string** | Datacenter within which the desktop pool is configured. | [optional] 
**HostOrClusterId** | Pointer to **string** | Host or cluster where the machines are deployed in. | [optional] 
**ImStreamId** | Pointer to **string** | Applicable To: Full/instant clone automated desktop pools.&lt;br&gt;Image management stream used in desktop pool when Image Management feature is enabled.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**ImTagId** | Pointer to **string** | Applicable To: Full/instant clone automated desktop pools.&lt;br&gt;Image management tag associated with the selected image management stream which is used in desktop pool when Image Management feature is enabled.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**MinReadyVmsOnVcomposerMaintenance** | Pointer to **int32** | Applicable To: Linked clone automated desktop pools.&lt;br&gt;Minimum number of ready (provisioned) machines during View Composer maintenance operations. | [optional] 
**ParentVmId** | Pointer to **string** | Applicable To: Linked/instant clone automated desktop pools.&lt;br&gt;Base image VM for linked clone desktop pool and current image for instant clone desktop pool. | [optional] 
**ResourcePoolId** | Pointer to **string** | Resource pool to deploy the machines. | [optional] 
**VmFolderId** | Pointer to **string** | VM folder where the machines are deployed to. | [optional] 
**VmTemplateId** | Pointer to **string** | Applicable To: Full clone automated desktop pools.&lt;br&gt;Template from which full clone machines are deployed. | [optional] 

## Methods

### NewDesktopPoolProvisioningSettingsV2

`func NewDesktopPoolProvisioningSettingsV2() *DesktopPoolProvisioningSettingsV2`

NewDesktopPoolProvisioningSettingsV2 instantiates a new DesktopPoolProvisioningSettingsV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesktopPoolProvisioningSettingsV2WithDefaults

`func NewDesktopPoolProvisioningSettingsV2WithDefaults() *DesktopPoolProvisioningSettingsV2`

NewDesktopPoolProvisioningSettingsV2WithDefaults instantiates a new DesktopPoolProvisioningSettingsV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddVirtualTpm

`func (o *DesktopPoolProvisioningSettingsV2) GetAddVirtualTpm() bool`

GetAddVirtualTpm returns the AddVirtualTpm field if non-nil, zero value otherwise.

### GetAddVirtualTpmOk

`func (o *DesktopPoolProvisioningSettingsV2) GetAddVirtualTpmOk() (*bool, bool)`

GetAddVirtualTpmOk returns a tuple with the AddVirtualTpm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddVirtualTpm

`func (o *DesktopPoolProvisioningSettingsV2) SetAddVirtualTpm(v bool)`

SetAddVirtualTpm sets AddVirtualTpm field to given value.

### HasAddVirtualTpm

`func (o *DesktopPoolProvisioningSettingsV2) HasAddVirtualTpm() bool`

HasAddVirtualTpm returns a boolean if a field has been set.

### GetBaseSnapshotId

`func (o *DesktopPoolProvisioningSettingsV2) GetBaseSnapshotId() string`

GetBaseSnapshotId returns the BaseSnapshotId field if non-nil, zero value otherwise.

### GetBaseSnapshotIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetBaseSnapshotIdOk() (*string, bool)`

GetBaseSnapshotIdOk returns a tuple with the BaseSnapshotId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSnapshotId

`func (o *DesktopPoolProvisioningSettingsV2) SetBaseSnapshotId(v string)`

SetBaseSnapshotId sets BaseSnapshotId field to given value.

### HasBaseSnapshotId

`func (o *DesktopPoolProvisioningSettingsV2) HasBaseSnapshotId() bool`

HasBaseSnapshotId returns a boolean if a field has been set.

### GetComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningSettingsV2) GetComputeProfileNumCoresPerSocket() int32`

GetComputeProfileNumCoresPerSocket returns the ComputeProfileNumCoresPerSocket field if non-nil, zero value otherwise.

### GetComputeProfileNumCoresPerSocketOk

`func (o *DesktopPoolProvisioningSettingsV2) GetComputeProfileNumCoresPerSocketOk() (*int32, bool)`

GetComputeProfileNumCoresPerSocketOk returns a tuple with the ComputeProfileNumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningSettingsV2) SetComputeProfileNumCoresPerSocket(v int32)`

SetComputeProfileNumCoresPerSocket sets ComputeProfileNumCoresPerSocket field to given value.

### HasComputeProfileNumCoresPerSocket

`func (o *DesktopPoolProvisioningSettingsV2) HasComputeProfileNumCoresPerSocket() bool`

HasComputeProfileNumCoresPerSocket returns a boolean if a field has been set.

### GetComputeProfileNumCpus

`func (o *DesktopPoolProvisioningSettingsV2) GetComputeProfileNumCpus() int32`

GetComputeProfileNumCpus returns the ComputeProfileNumCpus field if non-nil, zero value otherwise.

### GetComputeProfileNumCpusOk

`func (o *DesktopPoolProvisioningSettingsV2) GetComputeProfileNumCpusOk() (*int32, bool)`

GetComputeProfileNumCpusOk returns a tuple with the ComputeProfileNumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileNumCpus

`func (o *DesktopPoolProvisioningSettingsV2) SetComputeProfileNumCpus(v int32)`

SetComputeProfileNumCpus sets ComputeProfileNumCpus field to given value.

### HasComputeProfileNumCpus

`func (o *DesktopPoolProvisioningSettingsV2) HasComputeProfileNumCpus() bool`

HasComputeProfileNumCpus returns a boolean if a field has been set.

### GetComputeProfileRamMb

`func (o *DesktopPoolProvisioningSettingsV2) GetComputeProfileRamMb() int32`

GetComputeProfileRamMb returns the ComputeProfileRamMb field if non-nil, zero value otherwise.

### GetComputeProfileRamMbOk

`func (o *DesktopPoolProvisioningSettingsV2) GetComputeProfileRamMbOk() (*int32, bool)`

GetComputeProfileRamMbOk returns a tuple with the ComputeProfileRamMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeProfileRamMb

`func (o *DesktopPoolProvisioningSettingsV2) SetComputeProfileRamMb(v int32)`

SetComputeProfileRamMb sets ComputeProfileRamMb field to given value.

### HasComputeProfileRamMb

`func (o *DesktopPoolProvisioningSettingsV2) HasComputeProfileRamMb() bool`

HasComputeProfileRamMb returns a boolean if a field has been set.

### GetDatacenterId

`func (o *DesktopPoolProvisioningSettingsV2) GetDatacenterId() string`

GetDatacenterId returns the DatacenterId field if non-nil, zero value otherwise.

### GetDatacenterIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetDatacenterIdOk() (*string, bool)`

GetDatacenterIdOk returns a tuple with the DatacenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatacenterId

`func (o *DesktopPoolProvisioningSettingsV2) SetDatacenterId(v string)`

SetDatacenterId sets DatacenterId field to given value.

### HasDatacenterId

`func (o *DesktopPoolProvisioningSettingsV2) HasDatacenterId() bool`

HasDatacenterId returns a boolean if a field has been set.

### GetHostOrClusterId

`func (o *DesktopPoolProvisioningSettingsV2) GetHostOrClusterId() string`

GetHostOrClusterId returns the HostOrClusterId field if non-nil, zero value otherwise.

### GetHostOrClusterIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetHostOrClusterIdOk() (*string, bool)`

GetHostOrClusterIdOk returns a tuple with the HostOrClusterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostOrClusterId

`func (o *DesktopPoolProvisioningSettingsV2) SetHostOrClusterId(v string)`

SetHostOrClusterId sets HostOrClusterId field to given value.

### HasHostOrClusterId

`func (o *DesktopPoolProvisioningSettingsV2) HasHostOrClusterId() bool`

HasHostOrClusterId returns a boolean if a field has been set.

### GetImStreamId

`func (o *DesktopPoolProvisioningSettingsV2) GetImStreamId() string`

GetImStreamId returns the ImStreamId field if non-nil, zero value otherwise.

### GetImStreamIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetImStreamIdOk() (*string, bool)`

GetImStreamIdOk returns a tuple with the ImStreamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImStreamId

`func (o *DesktopPoolProvisioningSettingsV2) SetImStreamId(v string)`

SetImStreamId sets ImStreamId field to given value.

### HasImStreamId

`func (o *DesktopPoolProvisioningSettingsV2) HasImStreamId() bool`

HasImStreamId returns a boolean if a field has been set.

### GetImTagId

`func (o *DesktopPoolProvisioningSettingsV2) GetImTagId() string`

GetImTagId returns the ImTagId field if non-nil, zero value otherwise.

### GetImTagIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetImTagIdOk() (*string, bool)`

GetImTagIdOk returns a tuple with the ImTagId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImTagId

`func (o *DesktopPoolProvisioningSettingsV2) SetImTagId(v string)`

SetImTagId sets ImTagId field to given value.

### HasImTagId

`func (o *DesktopPoolProvisioningSettingsV2) HasImTagId() bool`

HasImTagId returns a boolean if a field has been set.

### GetMinReadyVmsOnVcomposerMaintenance

`func (o *DesktopPoolProvisioningSettingsV2) GetMinReadyVmsOnVcomposerMaintenance() int32`

GetMinReadyVmsOnVcomposerMaintenance returns the MinReadyVmsOnVcomposerMaintenance field if non-nil, zero value otherwise.

### GetMinReadyVmsOnVcomposerMaintenanceOk

`func (o *DesktopPoolProvisioningSettingsV2) GetMinReadyVmsOnVcomposerMaintenanceOk() (*int32, bool)`

GetMinReadyVmsOnVcomposerMaintenanceOk returns a tuple with the MinReadyVmsOnVcomposerMaintenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinReadyVmsOnVcomposerMaintenance

`func (o *DesktopPoolProvisioningSettingsV2) SetMinReadyVmsOnVcomposerMaintenance(v int32)`

SetMinReadyVmsOnVcomposerMaintenance sets MinReadyVmsOnVcomposerMaintenance field to given value.

### HasMinReadyVmsOnVcomposerMaintenance

`func (o *DesktopPoolProvisioningSettingsV2) HasMinReadyVmsOnVcomposerMaintenance() bool`

HasMinReadyVmsOnVcomposerMaintenance returns a boolean if a field has been set.

### GetParentVmId

`func (o *DesktopPoolProvisioningSettingsV2) GetParentVmId() string`

GetParentVmId returns the ParentVmId field if non-nil, zero value otherwise.

### GetParentVmIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetParentVmIdOk() (*string, bool)`

GetParentVmIdOk returns a tuple with the ParentVmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentVmId

`func (o *DesktopPoolProvisioningSettingsV2) SetParentVmId(v string)`

SetParentVmId sets ParentVmId field to given value.

### HasParentVmId

`func (o *DesktopPoolProvisioningSettingsV2) HasParentVmId() bool`

HasParentVmId returns a boolean if a field has been set.

### GetResourcePoolId

`func (o *DesktopPoolProvisioningSettingsV2) GetResourcePoolId() string`

GetResourcePoolId returns the ResourcePoolId field if non-nil, zero value otherwise.

### GetResourcePoolIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetResourcePoolIdOk() (*string, bool)`

GetResourcePoolIdOk returns a tuple with the ResourcePoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourcePoolId

`func (o *DesktopPoolProvisioningSettingsV2) SetResourcePoolId(v string)`

SetResourcePoolId sets ResourcePoolId field to given value.

### HasResourcePoolId

`func (o *DesktopPoolProvisioningSettingsV2) HasResourcePoolId() bool`

HasResourcePoolId returns a boolean if a field has been set.

### GetVmFolderId

`func (o *DesktopPoolProvisioningSettingsV2) GetVmFolderId() string`

GetVmFolderId returns the VmFolderId field if non-nil, zero value otherwise.

### GetVmFolderIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetVmFolderIdOk() (*string, bool)`

GetVmFolderIdOk returns a tuple with the VmFolderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVmFolderId

`func (o *DesktopPoolProvisioningSettingsV2) SetVmFolderId(v string)`

SetVmFolderId sets VmFolderId field to given value.

### HasVmFolderId

`func (o *DesktopPoolProvisioningSettingsV2) HasVmFolderId() bool`

HasVmFolderId returns a boolean if a field has been set.

### GetVmTemplateId

`func (o *DesktopPoolProvisioningSettingsV2) GetVmTemplateId() string`

GetVmTemplateId returns the VmTemplateId field if non-nil, zero value otherwise.

### GetVmTemplateIdOk

`func (o *DesktopPoolProvisioningSettingsV2) GetVmTemplateIdOk() (*string, bool)`

GetVmTemplateIdOk returns a tuple with the VmTemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVmTemplateId

`func (o *DesktopPoolProvisioningSettingsV2) SetVmTemplateId(v string)`

SetVmTemplateId sets VmTemplateId field to given value.

### HasVmTemplateId

`func (o *DesktopPoolProvisioningSettingsV2) HasVmTemplateId() bool`

HasVmTemplateId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


