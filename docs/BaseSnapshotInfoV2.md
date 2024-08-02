# BaseSnapshotInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedTimestamp** | Pointer to **int64** | Epoch time in milli seconds, when the VM snapshot was created. | [optional] 
**Description** | Pointer to **string** | Description of the VM snapshot. | [optional] 
**DiskSizeMb** | Pointer to **int64** | Sum of capacities of all the virtual disks in the VM snapshot, in MB. | [optional] 
**HardwareVersion** | Pointer to **int32** | VM snapshot hardware version | [optional] 
**Id** | Pointer to **string** | Unique ID representing the VM snapshot. | [optional] 
**IncompatibleReasons** | Pointer to **[]string** | Reasons that may preclude this VM snapshot from being used in linked/instant clone desktop pool or farm creation. | [optional] 
**MaxNumberOfMonitors** | Pointer to **int32** | Maximum number of monitors set in SVGA settings for the VM snapshot in vCenter. | [optional] 
**MaxResolutionOfAnyOneMonitor** | Pointer to **string** | Maximum resolution of any one monitor set in SVGA settings for the VM snapshot in vCenter. | [optional] 
**MemoryMb** | Pointer to **int32** | The physical memory size of VM snapshot, in MB | [optional] 
**MemoryReservationMb** | Pointer to **int64** | Amount of memory that is guaranteed available to the virtual machine, in MB. | [optional] 
**Name** | Pointer to **string** | VM snapshot name. | [optional] 
**NumCoresPerSocket** | Pointer to **int32** | Number of cores per socket present on the VM snapshot. | [optional] 
**NumCpus** | Pointer to **int32** | Number of CPUs present on the VM snapshot. | [optional] 
**Path** | Pointer to **string** | VM snapshot path. | [optional] 
**Renderer3d** | Pointer to **string** | Indicate how the virtual video device for the VM snapshot renders 3D graphics. Will be set only if VM snapshot supports 3D functions. * MANAGE_BY_VSPHERE_CLIENT: 3D rendering managed by vSphere Client. * AUTOMATIC: 3D rendering is automatic. * SOFTWARE: 3D rendering is software dependent. The software renderer is supported (at minimum) on virtual hardware version 8 in a vSphere 5.0 environment. * HARDWARE: 3D rendering is hardware dependent. The hardware-based renderer is supported (at minimum) on virtual hardware version 9 in a vSphere 5.1 environment. * DISABLED: 3D rendering is disabled. | [optional] 
**TotalVideoMemoryMb** | Pointer to **float64** | Total video memory in MB set in SVGA settings for the VM snapshot in vCenter. | [optional] 
**VcenterId** | Pointer to **string** | Virtual Center id for this VM snapshot. | [optional] 
**VgpuType** | Pointer to **string** | NVIDIA GRID vGPU type configured on this VM snapshot. | [optional] 

## Methods

### NewBaseSnapshotInfoV2

`func NewBaseSnapshotInfoV2() *BaseSnapshotInfoV2`

NewBaseSnapshotInfoV2 instantiates a new BaseSnapshotInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBaseSnapshotInfoV2WithDefaults

`func NewBaseSnapshotInfoV2WithDefaults() *BaseSnapshotInfoV2`

NewBaseSnapshotInfoV2WithDefaults instantiates a new BaseSnapshotInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedTimestamp

`func (o *BaseSnapshotInfoV2) GetCreatedTimestamp() int64`

GetCreatedTimestamp returns the CreatedTimestamp field if non-nil, zero value otherwise.

### GetCreatedTimestampOk

`func (o *BaseSnapshotInfoV2) GetCreatedTimestampOk() (*int64, bool)`

GetCreatedTimestampOk returns a tuple with the CreatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedTimestamp

`func (o *BaseSnapshotInfoV2) SetCreatedTimestamp(v int64)`

SetCreatedTimestamp sets CreatedTimestamp field to given value.

### HasCreatedTimestamp

`func (o *BaseSnapshotInfoV2) HasCreatedTimestamp() bool`

HasCreatedTimestamp returns a boolean if a field has been set.

### GetDescription

`func (o *BaseSnapshotInfoV2) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *BaseSnapshotInfoV2) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *BaseSnapshotInfoV2) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *BaseSnapshotInfoV2) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDiskSizeMb

`func (o *BaseSnapshotInfoV2) GetDiskSizeMb() int64`

GetDiskSizeMb returns the DiskSizeMb field if non-nil, zero value otherwise.

### GetDiskSizeMbOk

`func (o *BaseSnapshotInfoV2) GetDiskSizeMbOk() (*int64, bool)`

GetDiskSizeMbOk returns a tuple with the DiskSizeMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskSizeMb

`func (o *BaseSnapshotInfoV2) SetDiskSizeMb(v int64)`

SetDiskSizeMb sets DiskSizeMb field to given value.

### HasDiskSizeMb

`func (o *BaseSnapshotInfoV2) HasDiskSizeMb() bool`

HasDiskSizeMb returns a boolean if a field has been set.

### GetHardwareVersion

`func (o *BaseSnapshotInfoV2) GetHardwareVersion() int32`

GetHardwareVersion returns the HardwareVersion field if non-nil, zero value otherwise.

### GetHardwareVersionOk

`func (o *BaseSnapshotInfoV2) GetHardwareVersionOk() (*int32, bool)`

GetHardwareVersionOk returns a tuple with the HardwareVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHardwareVersion

`func (o *BaseSnapshotInfoV2) SetHardwareVersion(v int32)`

SetHardwareVersion sets HardwareVersion field to given value.

### HasHardwareVersion

`func (o *BaseSnapshotInfoV2) HasHardwareVersion() bool`

HasHardwareVersion returns a boolean if a field has been set.

### GetId

`func (o *BaseSnapshotInfoV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BaseSnapshotInfoV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BaseSnapshotInfoV2) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *BaseSnapshotInfoV2) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIncompatibleReasons

`func (o *BaseSnapshotInfoV2) GetIncompatibleReasons() []string`

GetIncompatibleReasons returns the IncompatibleReasons field if non-nil, zero value otherwise.

### GetIncompatibleReasonsOk

`func (o *BaseSnapshotInfoV2) GetIncompatibleReasonsOk() (*[]string, bool)`

GetIncompatibleReasonsOk returns a tuple with the IncompatibleReasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompatibleReasons

`func (o *BaseSnapshotInfoV2) SetIncompatibleReasons(v []string)`

SetIncompatibleReasons sets IncompatibleReasons field to given value.

### HasIncompatibleReasons

`func (o *BaseSnapshotInfoV2) HasIncompatibleReasons() bool`

HasIncompatibleReasons returns a boolean if a field has been set.

### GetMaxNumberOfMonitors

`func (o *BaseSnapshotInfoV2) GetMaxNumberOfMonitors() int32`

GetMaxNumberOfMonitors returns the MaxNumberOfMonitors field if non-nil, zero value otherwise.

### GetMaxNumberOfMonitorsOk

`func (o *BaseSnapshotInfoV2) GetMaxNumberOfMonitorsOk() (*int32, bool)`

GetMaxNumberOfMonitorsOk returns a tuple with the MaxNumberOfMonitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNumberOfMonitors

`func (o *BaseSnapshotInfoV2) SetMaxNumberOfMonitors(v int32)`

SetMaxNumberOfMonitors sets MaxNumberOfMonitors field to given value.

### HasMaxNumberOfMonitors

`func (o *BaseSnapshotInfoV2) HasMaxNumberOfMonitors() bool`

HasMaxNumberOfMonitors returns a boolean if a field has been set.

### GetMaxResolutionOfAnyOneMonitor

`func (o *BaseSnapshotInfoV2) GetMaxResolutionOfAnyOneMonitor() string`

GetMaxResolutionOfAnyOneMonitor returns the MaxResolutionOfAnyOneMonitor field if non-nil, zero value otherwise.

### GetMaxResolutionOfAnyOneMonitorOk

`func (o *BaseSnapshotInfoV2) GetMaxResolutionOfAnyOneMonitorOk() (*string, bool)`

GetMaxResolutionOfAnyOneMonitorOk returns a tuple with the MaxResolutionOfAnyOneMonitor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxResolutionOfAnyOneMonitor

`func (o *BaseSnapshotInfoV2) SetMaxResolutionOfAnyOneMonitor(v string)`

SetMaxResolutionOfAnyOneMonitor sets MaxResolutionOfAnyOneMonitor field to given value.

### HasMaxResolutionOfAnyOneMonitor

`func (o *BaseSnapshotInfoV2) HasMaxResolutionOfAnyOneMonitor() bool`

HasMaxResolutionOfAnyOneMonitor returns a boolean if a field has been set.

### GetMemoryMb

`func (o *BaseSnapshotInfoV2) GetMemoryMb() int32`

GetMemoryMb returns the MemoryMb field if non-nil, zero value otherwise.

### GetMemoryMbOk

`func (o *BaseSnapshotInfoV2) GetMemoryMbOk() (*int32, bool)`

GetMemoryMbOk returns a tuple with the MemoryMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryMb

`func (o *BaseSnapshotInfoV2) SetMemoryMb(v int32)`

SetMemoryMb sets MemoryMb field to given value.

### HasMemoryMb

`func (o *BaseSnapshotInfoV2) HasMemoryMb() bool`

HasMemoryMb returns a boolean if a field has been set.

### GetMemoryReservationMb

`func (o *BaseSnapshotInfoV2) GetMemoryReservationMb() int64`

GetMemoryReservationMb returns the MemoryReservationMb field if non-nil, zero value otherwise.

### GetMemoryReservationMbOk

`func (o *BaseSnapshotInfoV2) GetMemoryReservationMbOk() (*int64, bool)`

GetMemoryReservationMbOk returns a tuple with the MemoryReservationMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryReservationMb

`func (o *BaseSnapshotInfoV2) SetMemoryReservationMb(v int64)`

SetMemoryReservationMb sets MemoryReservationMb field to given value.

### HasMemoryReservationMb

`func (o *BaseSnapshotInfoV2) HasMemoryReservationMb() bool`

HasMemoryReservationMb returns a boolean if a field has been set.

### GetName

`func (o *BaseSnapshotInfoV2) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BaseSnapshotInfoV2) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BaseSnapshotInfoV2) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *BaseSnapshotInfoV2) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNumCoresPerSocket

`func (o *BaseSnapshotInfoV2) GetNumCoresPerSocket() int32`

GetNumCoresPerSocket returns the NumCoresPerSocket field if non-nil, zero value otherwise.

### GetNumCoresPerSocketOk

`func (o *BaseSnapshotInfoV2) GetNumCoresPerSocketOk() (*int32, bool)`

GetNumCoresPerSocketOk returns a tuple with the NumCoresPerSocket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumCoresPerSocket

`func (o *BaseSnapshotInfoV2) SetNumCoresPerSocket(v int32)`

SetNumCoresPerSocket sets NumCoresPerSocket field to given value.

### HasNumCoresPerSocket

`func (o *BaseSnapshotInfoV2) HasNumCoresPerSocket() bool`

HasNumCoresPerSocket returns a boolean if a field has been set.

### GetNumCpus

`func (o *BaseSnapshotInfoV2) GetNumCpus() int32`

GetNumCpus returns the NumCpus field if non-nil, zero value otherwise.

### GetNumCpusOk

`func (o *BaseSnapshotInfoV2) GetNumCpusOk() (*int32, bool)`

GetNumCpusOk returns a tuple with the NumCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumCpus

`func (o *BaseSnapshotInfoV2) SetNumCpus(v int32)`

SetNumCpus sets NumCpus field to given value.

### HasNumCpus

`func (o *BaseSnapshotInfoV2) HasNumCpus() bool`

HasNumCpus returns a boolean if a field has been set.

### GetPath

`func (o *BaseSnapshotInfoV2) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *BaseSnapshotInfoV2) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *BaseSnapshotInfoV2) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *BaseSnapshotInfoV2) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetRenderer3d

`func (o *BaseSnapshotInfoV2) GetRenderer3d() string`

GetRenderer3d returns the Renderer3d field if non-nil, zero value otherwise.

### GetRenderer3dOk

`func (o *BaseSnapshotInfoV2) GetRenderer3dOk() (*string, bool)`

GetRenderer3dOk returns a tuple with the Renderer3d field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenderer3d

`func (o *BaseSnapshotInfoV2) SetRenderer3d(v string)`

SetRenderer3d sets Renderer3d field to given value.

### HasRenderer3d

`func (o *BaseSnapshotInfoV2) HasRenderer3d() bool`

HasRenderer3d returns a boolean if a field has been set.

### GetTotalVideoMemoryMb

`func (o *BaseSnapshotInfoV2) GetTotalVideoMemoryMb() float64`

GetTotalVideoMemoryMb returns the TotalVideoMemoryMb field if non-nil, zero value otherwise.

### GetTotalVideoMemoryMbOk

`func (o *BaseSnapshotInfoV2) GetTotalVideoMemoryMbOk() (*float64, bool)`

GetTotalVideoMemoryMbOk returns a tuple with the TotalVideoMemoryMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalVideoMemoryMb

`func (o *BaseSnapshotInfoV2) SetTotalVideoMemoryMb(v float64)`

SetTotalVideoMemoryMb sets TotalVideoMemoryMb field to given value.

### HasTotalVideoMemoryMb

`func (o *BaseSnapshotInfoV2) HasTotalVideoMemoryMb() bool`

HasTotalVideoMemoryMb returns a boolean if a field has been set.

### GetVcenterId

`func (o *BaseSnapshotInfoV2) GetVcenterId() string`

GetVcenterId returns the VcenterId field if non-nil, zero value otherwise.

### GetVcenterIdOk

`func (o *BaseSnapshotInfoV2) GetVcenterIdOk() (*string, bool)`

GetVcenterIdOk returns a tuple with the VcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVcenterId

`func (o *BaseSnapshotInfoV2) SetVcenterId(v string)`

SetVcenterId sets VcenterId field to given value.

### HasVcenterId

`func (o *BaseSnapshotInfoV2) HasVcenterId() bool`

HasVcenterId returns a boolean if a field has been set.

### GetVgpuType

`func (o *BaseSnapshotInfoV2) GetVgpuType() string`

GetVgpuType returns the VgpuType field if non-nil, zero value otherwise.

### GetVgpuTypeOk

`func (o *BaseSnapshotInfoV2) GetVgpuTypeOk() (*string, bool)`

GetVgpuTypeOk returns a tuple with the VgpuType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVgpuType

`func (o *BaseSnapshotInfoV2) SetVgpuType(v string)`

SetVgpuType sets VgpuType field to given value.

### HasVgpuType

`func (o *BaseSnapshotInfoV2) HasVgpuType() bool`

HasVgpuType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


