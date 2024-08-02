# FarmAutomatedSettingsInfoV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomizationSettings** | Pointer to [**FarmCustomizationSettingsInfoV2**](FarmCustomizationSettingsInfoV2.md) |  | [optional] 
**EnableProvisioning** | Pointer to **bool** | Indicates whether to enable provisioning immediately.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**ImageSource** | Pointer to **string** | Source of image used in the farm.&lt;br&gt;Supported Filters: &#39;Equals&#39;. * VIRTUAL_CENTER: Image was created in virtual center. * IMAGE_CATALOG: Image was created in image catalog. | [optional] 
**MaxSessionType** | Pointer to **string** | RDS Server type for max sessions. * UNLIMITED: The RDS Server has an unlimited number of sessions. * LIMITED: The RDS Server has a limited number of sessions. | [optional] 
**MaxSessions** | Pointer to **int32** | Maximum number of sessions allowed for RDS Server. This is set when max_session_type is LIMITED. | [optional] 
**MinReadyVms** | Pointer to **int32** | Minimum number of ready (provisioned) RDS Servers during Instant clone maintenance operations. Use this setting to perform machine maintenance operations in a rolling fashion. Increasing this count may decrease the concurrency for Instant clone maintenance operations for the automated farm. | [optional] 
**Nics** | Pointer to [**[]FarmNetworkInterfaceCardSettingsInfo**](FarmNetworkInterfaceCardSettingsInfo.md) | Network interface card settings for RDS Servers provisioned for this farm. A NIC may appear at most once in these settings and must be present on this RDS Server&#39;s parent&#39;s snapshot. Not all NICs need be configured. Any that are not will use default settings. | [optional] 
**OperatingSystem** | Pointer to **string** | The guest operating system. * UNKNOWN: Unknown * WINDOWS_SERVER_2003: Windows Server 2003 * WINDOWS_SERVER_2008: Windows Server 2008 * WINDOWS_SERVER_2008_R2: Windows Server 2008 R2 * WINDOWS_SERVER_2012: Windows Server 2012 * WINDOWS_SERVER_2012_R2: Windows Server 2012 R2 * WINDOWS_SERVER_2016_OR_ABOVE: Windows Server 2016 or above * LINUX_SERVER_OTHER: Linux Server (other) | [optional] 
**OperatingSystemArchitecture** | Pointer to **string** | The guest operating system architecture. * UNKNOWN: Operating System cannot be determined. * BIT_32: 32 bit Operating System Architecture. * BIT_64: 64 bit Operating System Architecture. | [optional] 
**PatternNamingSettings** | Pointer to [**FarmRDSServersPatternNamingSettingsInfo**](FarmRDSServersPatternNamingSettingsInfo.md) |  | [optional] 
**ProvisioningSettings** | Pointer to [**FarmProvisioningSettingsInfoV2**](FarmProvisioningSettingsInfoV2.md) |  | [optional] 
**ProvisioningStatusData** | Pointer to [**FarmProvisioningStatusInfoV2**](FarmProvisioningStatusInfoV2.md) |  | [optional] 
**StopProvisioningOnError** | Pointer to **bool** | Indicates whether provisioning on all VMs stops on error. | [optional] 
**StorageSettings** | Pointer to [**FarmStorageSettingsInfo**](FarmStorageSettingsInfo.md) |  | [optional] 
**TransparentPageSharingScope** | Pointer to **string** | Transparent page sharing scope for the farm. * VM: Inter-VM page sharing is not permitted. * FARM: Inter-VM page sharing among VMs belonging to the same automated farm is permitted. * POD: Inter-VM page sharing among VMs belonging to the same Pod is permitted. * GLOBAL: Inter-VM page sharing among all VMs on the same host is permitted. | [optional] 
**VcenterId** | Pointer to **string** | ID of the virtual center server.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 

## Methods

### NewFarmAutomatedSettingsInfoV3

`func NewFarmAutomatedSettingsInfoV3() *FarmAutomatedSettingsInfoV3`

NewFarmAutomatedSettingsInfoV3 instantiates a new FarmAutomatedSettingsInfoV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmAutomatedSettingsInfoV3WithDefaults

`func NewFarmAutomatedSettingsInfoV3WithDefaults() *FarmAutomatedSettingsInfoV3`

NewFarmAutomatedSettingsInfoV3WithDefaults instantiates a new FarmAutomatedSettingsInfoV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomizationSettings

`func (o *FarmAutomatedSettingsInfoV3) GetCustomizationSettings() FarmCustomizationSettingsInfoV2`

GetCustomizationSettings returns the CustomizationSettings field if non-nil, zero value otherwise.

### GetCustomizationSettingsOk

`func (o *FarmAutomatedSettingsInfoV3) GetCustomizationSettingsOk() (*FarmCustomizationSettingsInfoV2, bool)`

GetCustomizationSettingsOk returns a tuple with the CustomizationSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomizationSettings

`func (o *FarmAutomatedSettingsInfoV3) SetCustomizationSettings(v FarmCustomizationSettingsInfoV2)`

SetCustomizationSettings sets CustomizationSettings field to given value.

### HasCustomizationSettings

`func (o *FarmAutomatedSettingsInfoV3) HasCustomizationSettings() bool`

HasCustomizationSettings returns a boolean if a field has been set.

### GetEnableProvisioning

`func (o *FarmAutomatedSettingsInfoV3) GetEnableProvisioning() bool`

GetEnableProvisioning returns the EnableProvisioning field if non-nil, zero value otherwise.

### GetEnableProvisioningOk

`func (o *FarmAutomatedSettingsInfoV3) GetEnableProvisioningOk() (*bool, bool)`

GetEnableProvisioningOk returns a tuple with the EnableProvisioning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableProvisioning

`func (o *FarmAutomatedSettingsInfoV3) SetEnableProvisioning(v bool)`

SetEnableProvisioning sets EnableProvisioning field to given value.

### HasEnableProvisioning

`func (o *FarmAutomatedSettingsInfoV3) HasEnableProvisioning() bool`

HasEnableProvisioning returns a boolean if a field has been set.

### GetImageSource

`func (o *FarmAutomatedSettingsInfoV3) GetImageSource() string`

GetImageSource returns the ImageSource field if non-nil, zero value otherwise.

### GetImageSourceOk

`func (o *FarmAutomatedSettingsInfoV3) GetImageSourceOk() (*string, bool)`

GetImageSourceOk returns a tuple with the ImageSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageSource

`func (o *FarmAutomatedSettingsInfoV3) SetImageSource(v string)`

SetImageSource sets ImageSource field to given value.

### HasImageSource

`func (o *FarmAutomatedSettingsInfoV3) HasImageSource() bool`

HasImageSource returns a boolean if a field has been set.

### GetMaxSessionType

`func (o *FarmAutomatedSettingsInfoV3) GetMaxSessionType() string`

GetMaxSessionType returns the MaxSessionType field if non-nil, zero value otherwise.

### GetMaxSessionTypeOk

`func (o *FarmAutomatedSettingsInfoV3) GetMaxSessionTypeOk() (*string, bool)`

GetMaxSessionTypeOk returns a tuple with the MaxSessionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSessionType

`func (o *FarmAutomatedSettingsInfoV3) SetMaxSessionType(v string)`

SetMaxSessionType sets MaxSessionType field to given value.

### HasMaxSessionType

`func (o *FarmAutomatedSettingsInfoV3) HasMaxSessionType() bool`

HasMaxSessionType returns a boolean if a field has been set.

### GetMaxSessions

`func (o *FarmAutomatedSettingsInfoV3) GetMaxSessions() int32`

GetMaxSessions returns the MaxSessions field if non-nil, zero value otherwise.

### GetMaxSessionsOk

`func (o *FarmAutomatedSettingsInfoV3) GetMaxSessionsOk() (*int32, bool)`

GetMaxSessionsOk returns a tuple with the MaxSessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSessions

`func (o *FarmAutomatedSettingsInfoV3) SetMaxSessions(v int32)`

SetMaxSessions sets MaxSessions field to given value.

### HasMaxSessions

`func (o *FarmAutomatedSettingsInfoV3) HasMaxSessions() bool`

HasMaxSessions returns a boolean if a field has been set.

### GetMinReadyVms

`func (o *FarmAutomatedSettingsInfoV3) GetMinReadyVms() int32`

GetMinReadyVms returns the MinReadyVms field if non-nil, zero value otherwise.

### GetMinReadyVmsOk

`func (o *FarmAutomatedSettingsInfoV3) GetMinReadyVmsOk() (*int32, bool)`

GetMinReadyVmsOk returns a tuple with the MinReadyVms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinReadyVms

`func (o *FarmAutomatedSettingsInfoV3) SetMinReadyVms(v int32)`

SetMinReadyVms sets MinReadyVms field to given value.

### HasMinReadyVms

`func (o *FarmAutomatedSettingsInfoV3) HasMinReadyVms() bool`

HasMinReadyVms returns a boolean if a field has been set.

### GetNics

`func (o *FarmAutomatedSettingsInfoV3) GetNics() []FarmNetworkInterfaceCardSettingsInfo`

GetNics returns the Nics field if non-nil, zero value otherwise.

### GetNicsOk

`func (o *FarmAutomatedSettingsInfoV3) GetNicsOk() (*[]FarmNetworkInterfaceCardSettingsInfo, bool)`

GetNicsOk returns a tuple with the Nics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNics

`func (o *FarmAutomatedSettingsInfoV3) SetNics(v []FarmNetworkInterfaceCardSettingsInfo)`

SetNics sets Nics field to given value.

### HasNics

`func (o *FarmAutomatedSettingsInfoV3) HasNics() bool`

HasNics returns a boolean if a field has been set.

### GetOperatingSystem

`func (o *FarmAutomatedSettingsInfoV3) GetOperatingSystem() string`

GetOperatingSystem returns the OperatingSystem field if non-nil, zero value otherwise.

### GetOperatingSystemOk

`func (o *FarmAutomatedSettingsInfoV3) GetOperatingSystemOk() (*string, bool)`

GetOperatingSystemOk returns a tuple with the OperatingSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatingSystem

`func (o *FarmAutomatedSettingsInfoV3) SetOperatingSystem(v string)`

SetOperatingSystem sets OperatingSystem field to given value.

### HasOperatingSystem

`func (o *FarmAutomatedSettingsInfoV3) HasOperatingSystem() bool`

HasOperatingSystem returns a boolean if a field has been set.

### GetOperatingSystemArchitecture

`func (o *FarmAutomatedSettingsInfoV3) GetOperatingSystemArchitecture() string`

GetOperatingSystemArchitecture returns the OperatingSystemArchitecture field if non-nil, zero value otherwise.

### GetOperatingSystemArchitectureOk

`func (o *FarmAutomatedSettingsInfoV3) GetOperatingSystemArchitectureOk() (*string, bool)`

GetOperatingSystemArchitectureOk returns a tuple with the OperatingSystemArchitecture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatingSystemArchitecture

`func (o *FarmAutomatedSettingsInfoV3) SetOperatingSystemArchitecture(v string)`

SetOperatingSystemArchitecture sets OperatingSystemArchitecture field to given value.

### HasOperatingSystemArchitecture

`func (o *FarmAutomatedSettingsInfoV3) HasOperatingSystemArchitecture() bool`

HasOperatingSystemArchitecture returns a boolean if a field has been set.

### GetPatternNamingSettings

`func (o *FarmAutomatedSettingsInfoV3) GetPatternNamingSettings() FarmRDSServersPatternNamingSettingsInfo`

GetPatternNamingSettings returns the PatternNamingSettings field if non-nil, zero value otherwise.

### GetPatternNamingSettingsOk

`func (o *FarmAutomatedSettingsInfoV3) GetPatternNamingSettingsOk() (*FarmRDSServersPatternNamingSettingsInfo, bool)`

GetPatternNamingSettingsOk returns a tuple with the PatternNamingSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatternNamingSettings

`func (o *FarmAutomatedSettingsInfoV3) SetPatternNamingSettings(v FarmRDSServersPatternNamingSettingsInfo)`

SetPatternNamingSettings sets PatternNamingSettings field to given value.

### HasPatternNamingSettings

`func (o *FarmAutomatedSettingsInfoV3) HasPatternNamingSettings() bool`

HasPatternNamingSettings returns a boolean if a field has been set.

### GetProvisioningSettings

`func (o *FarmAutomatedSettingsInfoV3) GetProvisioningSettings() FarmProvisioningSettingsInfoV2`

GetProvisioningSettings returns the ProvisioningSettings field if non-nil, zero value otherwise.

### GetProvisioningSettingsOk

`func (o *FarmAutomatedSettingsInfoV3) GetProvisioningSettingsOk() (*FarmProvisioningSettingsInfoV2, bool)`

GetProvisioningSettingsOk returns a tuple with the ProvisioningSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvisioningSettings

`func (o *FarmAutomatedSettingsInfoV3) SetProvisioningSettings(v FarmProvisioningSettingsInfoV2)`

SetProvisioningSettings sets ProvisioningSettings field to given value.

### HasProvisioningSettings

`func (o *FarmAutomatedSettingsInfoV3) HasProvisioningSettings() bool`

HasProvisioningSettings returns a boolean if a field has been set.

### GetProvisioningStatusData

`func (o *FarmAutomatedSettingsInfoV3) GetProvisioningStatusData() FarmProvisioningStatusInfoV2`

GetProvisioningStatusData returns the ProvisioningStatusData field if non-nil, zero value otherwise.

### GetProvisioningStatusDataOk

`func (o *FarmAutomatedSettingsInfoV3) GetProvisioningStatusDataOk() (*FarmProvisioningStatusInfoV2, bool)`

GetProvisioningStatusDataOk returns a tuple with the ProvisioningStatusData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvisioningStatusData

`func (o *FarmAutomatedSettingsInfoV3) SetProvisioningStatusData(v FarmProvisioningStatusInfoV2)`

SetProvisioningStatusData sets ProvisioningStatusData field to given value.

### HasProvisioningStatusData

`func (o *FarmAutomatedSettingsInfoV3) HasProvisioningStatusData() bool`

HasProvisioningStatusData returns a boolean if a field has been set.

### GetStopProvisioningOnError

`func (o *FarmAutomatedSettingsInfoV3) GetStopProvisioningOnError() bool`

GetStopProvisioningOnError returns the StopProvisioningOnError field if non-nil, zero value otherwise.

### GetStopProvisioningOnErrorOk

`func (o *FarmAutomatedSettingsInfoV3) GetStopProvisioningOnErrorOk() (*bool, bool)`

GetStopProvisioningOnErrorOk returns a tuple with the StopProvisioningOnError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopProvisioningOnError

`func (o *FarmAutomatedSettingsInfoV3) SetStopProvisioningOnError(v bool)`

SetStopProvisioningOnError sets StopProvisioningOnError field to given value.

### HasStopProvisioningOnError

`func (o *FarmAutomatedSettingsInfoV3) HasStopProvisioningOnError() bool`

HasStopProvisioningOnError returns a boolean if a field has been set.

### GetStorageSettings

`func (o *FarmAutomatedSettingsInfoV3) GetStorageSettings() FarmStorageSettingsInfo`

GetStorageSettings returns the StorageSettings field if non-nil, zero value otherwise.

### GetStorageSettingsOk

`func (o *FarmAutomatedSettingsInfoV3) GetStorageSettingsOk() (*FarmStorageSettingsInfo, bool)`

GetStorageSettingsOk returns a tuple with the StorageSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageSettings

`func (o *FarmAutomatedSettingsInfoV3) SetStorageSettings(v FarmStorageSettingsInfo)`

SetStorageSettings sets StorageSettings field to given value.

### HasStorageSettings

`func (o *FarmAutomatedSettingsInfoV3) HasStorageSettings() bool`

HasStorageSettings returns a boolean if a field has been set.

### GetTransparentPageSharingScope

`func (o *FarmAutomatedSettingsInfoV3) GetTransparentPageSharingScope() string`

GetTransparentPageSharingScope returns the TransparentPageSharingScope field if non-nil, zero value otherwise.

### GetTransparentPageSharingScopeOk

`func (o *FarmAutomatedSettingsInfoV3) GetTransparentPageSharingScopeOk() (*string, bool)`

GetTransparentPageSharingScopeOk returns a tuple with the TransparentPageSharingScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransparentPageSharingScope

`func (o *FarmAutomatedSettingsInfoV3) SetTransparentPageSharingScope(v string)`

SetTransparentPageSharingScope sets TransparentPageSharingScope field to given value.

### HasTransparentPageSharingScope

`func (o *FarmAutomatedSettingsInfoV3) HasTransparentPageSharingScope() bool`

HasTransparentPageSharingScope returns a boolean if a field has been set.

### GetVcenterId

`func (o *FarmAutomatedSettingsInfoV3) GetVcenterId() string`

GetVcenterId returns the VcenterId field if non-nil, zero value otherwise.

### GetVcenterIdOk

`func (o *FarmAutomatedSettingsInfoV3) GetVcenterIdOk() (*string, bool)`

GetVcenterIdOk returns a tuple with the VcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVcenterId

`func (o *FarmAutomatedSettingsInfoV3) SetVcenterId(v string)`

SetVcenterId sets VcenterId field to given value.

### HasVcenterId

`func (o *FarmAutomatedSettingsInfoV3) HasVcenterId() bool`

HasVcenterId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


