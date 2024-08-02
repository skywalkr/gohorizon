# BaseVMInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DatacenterId** | Pointer to **string** | Datacenter id for this VM. | [optional] 
**Id** | Pointer to **string** | Unique ID representing a VM. | [optional] 
**IncompatibleReasons** | Pointer to **[]string** | Reasons that may preclude this BaseVM from having its snapshots used in linked or instant clone desktop or farm creation. | [optional] 
**Name** | Pointer to **string** | VM name. | [optional] 
**NetworkType** | Pointer to **string** | Type of network base VM belongs to. * STANDARD_NETWORK: Standard network. * OPAQUE_NETWORK: Opaque network. * DISTRUBUTED_VIRTUAL_PORT_GROUP: DVS port group. | [optional] 
**NumNics** | Pointer to **int32** | Number of network interface cards in a VM. | [optional] 
**OperatingSystem** | Pointer to **string** | Operating system. * UNKNOWN: Unknown * WINDOWS_XP: Windows XP * WINDOWS_VISTA: Windows Vista * WINDOWS_7: Windows 7 * WINDOWS_8: Windows 8 * WINDOWS_10: Windows 10 * WINDOWS_11: Windows 11 * WINDOWS_SERVER_2003: Windows Server 2003 * WINDOWS_SERVER_2008: Windows Server 2008 * WINDOWS_SERVER_2008_R2: Windows Server 2008 R2 * WINDOWS_SERVER_2012: Windows Server 2012 * WINDOWS_SERVER_2012_R2: Windows Server 2012 R2 * WINDOWS_SERVER_2016_OR_ABOVE: Windows Server 2016 or above * LINUX_OTHER: Linux (other) * LINUX_SERVER_OTHER: Linux server (other) * LINUX_UBUNTU: Linux (Ubuntu) * LINUX_RHEL: Linux (Red Hat Enterprise) * LINUX_SUSE: Linux (Suse) * LINUX_CENTOS: Linux (CentOS) | [optional] 
**OperatingSystemDisplayName** | Pointer to **string** | Operating system display name from Virtual Center. | [optional] 
**Path** | Pointer to **string** | VM path. | [optional] 
**VcenterId** | Pointer to **string** | Virtual Center id for this VM. | [optional] 

## Methods

### NewBaseVMInfoV2

`func NewBaseVMInfoV2() *BaseVMInfoV2`

NewBaseVMInfoV2 instantiates a new BaseVMInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBaseVMInfoV2WithDefaults

`func NewBaseVMInfoV2WithDefaults() *BaseVMInfoV2`

NewBaseVMInfoV2WithDefaults instantiates a new BaseVMInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDatacenterId

`func (o *BaseVMInfoV2) GetDatacenterId() string`

GetDatacenterId returns the DatacenterId field if non-nil, zero value otherwise.

### GetDatacenterIdOk

`func (o *BaseVMInfoV2) GetDatacenterIdOk() (*string, bool)`

GetDatacenterIdOk returns a tuple with the DatacenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatacenterId

`func (o *BaseVMInfoV2) SetDatacenterId(v string)`

SetDatacenterId sets DatacenterId field to given value.

### HasDatacenterId

`func (o *BaseVMInfoV2) HasDatacenterId() bool`

HasDatacenterId returns a boolean if a field has been set.

### GetId

`func (o *BaseVMInfoV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BaseVMInfoV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BaseVMInfoV2) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *BaseVMInfoV2) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIncompatibleReasons

`func (o *BaseVMInfoV2) GetIncompatibleReasons() []string`

GetIncompatibleReasons returns the IncompatibleReasons field if non-nil, zero value otherwise.

### GetIncompatibleReasonsOk

`func (o *BaseVMInfoV2) GetIncompatibleReasonsOk() (*[]string, bool)`

GetIncompatibleReasonsOk returns a tuple with the IncompatibleReasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompatibleReasons

`func (o *BaseVMInfoV2) SetIncompatibleReasons(v []string)`

SetIncompatibleReasons sets IncompatibleReasons field to given value.

### HasIncompatibleReasons

`func (o *BaseVMInfoV2) HasIncompatibleReasons() bool`

HasIncompatibleReasons returns a boolean if a field has been set.

### GetName

`func (o *BaseVMInfoV2) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BaseVMInfoV2) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BaseVMInfoV2) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *BaseVMInfoV2) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNetworkType

`func (o *BaseVMInfoV2) GetNetworkType() string`

GetNetworkType returns the NetworkType field if non-nil, zero value otherwise.

### GetNetworkTypeOk

`func (o *BaseVMInfoV2) GetNetworkTypeOk() (*string, bool)`

GetNetworkTypeOk returns a tuple with the NetworkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkType

`func (o *BaseVMInfoV2) SetNetworkType(v string)`

SetNetworkType sets NetworkType field to given value.

### HasNetworkType

`func (o *BaseVMInfoV2) HasNetworkType() bool`

HasNetworkType returns a boolean if a field has been set.

### GetNumNics

`func (o *BaseVMInfoV2) GetNumNics() int32`

GetNumNics returns the NumNics field if non-nil, zero value otherwise.

### GetNumNicsOk

`func (o *BaseVMInfoV2) GetNumNicsOk() (*int32, bool)`

GetNumNicsOk returns a tuple with the NumNics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumNics

`func (o *BaseVMInfoV2) SetNumNics(v int32)`

SetNumNics sets NumNics field to given value.

### HasNumNics

`func (o *BaseVMInfoV2) HasNumNics() bool`

HasNumNics returns a boolean if a field has been set.

### GetOperatingSystem

`func (o *BaseVMInfoV2) GetOperatingSystem() string`

GetOperatingSystem returns the OperatingSystem field if non-nil, zero value otherwise.

### GetOperatingSystemOk

`func (o *BaseVMInfoV2) GetOperatingSystemOk() (*string, bool)`

GetOperatingSystemOk returns a tuple with the OperatingSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatingSystem

`func (o *BaseVMInfoV2) SetOperatingSystem(v string)`

SetOperatingSystem sets OperatingSystem field to given value.

### HasOperatingSystem

`func (o *BaseVMInfoV2) HasOperatingSystem() bool`

HasOperatingSystem returns a boolean if a field has been set.

### GetOperatingSystemDisplayName

`func (o *BaseVMInfoV2) GetOperatingSystemDisplayName() string`

GetOperatingSystemDisplayName returns the OperatingSystemDisplayName field if non-nil, zero value otherwise.

### GetOperatingSystemDisplayNameOk

`func (o *BaseVMInfoV2) GetOperatingSystemDisplayNameOk() (*string, bool)`

GetOperatingSystemDisplayNameOk returns a tuple with the OperatingSystemDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatingSystemDisplayName

`func (o *BaseVMInfoV2) SetOperatingSystemDisplayName(v string)`

SetOperatingSystemDisplayName sets OperatingSystemDisplayName field to given value.

### HasOperatingSystemDisplayName

`func (o *BaseVMInfoV2) HasOperatingSystemDisplayName() bool`

HasOperatingSystemDisplayName returns a boolean if a field has been set.

### GetPath

`func (o *BaseVMInfoV2) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *BaseVMInfoV2) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *BaseVMInfoV2) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *BaseVMInfoV2) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetVcenterId

`func (o *BaseVMInfoV2) GetVcenterId() string`

GetVcenterId returns the VcenterId field if non-nil, zero value otherwise.

### GetVcenterIdOk

`func (o *BaseVMInfoV2) GetVcenterIdOk() (*string, bool)`

GetVcenterIdOk returns a tuple with the VcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVcenterId

`func (o *BaseVMInfoV2) SetVcenterId(v string)`

SetVcenterId sets VcenterId field to given value.

### HasVcenterId

`func (o *BaseVMInfoV2) HasVcenterId() bool`

HasVcenterId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


