# FarmAutomatedSettingsCreateSpecV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomizationSettings** | [**FarmCustomizationSettingsCreateSpecV2**](FarmCustomizationSettingsCreateSpecV2.md) |  | 
**EnableProvisioning** | Pointer to **bool** | Indicates whether to enable provisioning immediately. Default value is true. | [optional] 
**MaxSessionType** | **string** | RDS Server type for max sessions. * UNLIMITED: The RDS Server has an unlimited number of sessions. * LIMITED: The RDS Server has a limited number of sessions. | 
**MaxSessions** | Pointer to **int32** | Maximum number of sessions allowed for RDS Server. This is required if max_session_type is set to LIMITED. | [optional] 
**MinReadyVms** | Pointer to **int32** | Minimum number of ready (provisioned) RDS Servers during Instant clone maintenance operations. Use this setting to perform machine maintenance operations in a rolling fashion. Increasing this count may decrease the concurrency for Instant clone maintenance operations for the automated farm. Default value is 0. | [optional] 
**Nics** | Pointer to [**[]FarmNetworkInterfaceCardSettingsCreateSpec**](FarmNetworkInterfaceCardSettingsCreateSpec.md) | Network interface card settings for RDS Servers provisioned for this farm. A NIC may appear at most once in these settings and must be present on this RDS Server&#39;s parent&#39;s snapshot. Not all NICs need be configured. Any that are not will use default settings. | [optional] 
**PatternNamingSettings** | [**FarmRDSServersPatternNamingSettingsCreateSpec**](FarmRDSServersPatternNamingSettingsCreateSpec.md) |  | 
**ProvisioningSettings** | [**FarmProvisioningSettingsCreateSpecV2**](FarmProvisioningSettingsCreateSpecV2.md) |  | 
**StopProvisioningOnError** | Pointer to **bool** | Indicates whether provisioning on all VMs stops on error. Default value is true. | [optional] 
**StorageSettings** | [**FarmStorageSettingsCreateSpec**](FarmStorageSettingsCreateSpec.md) |  | 
**TransparentPageSharingScope** | Pointer to **string** | Transparent page sharing scope for the farm. Default value is VM. * VM: Inter-VM page sharing is not permitted. * FARM: Inter-VM page sharing among VMs belonging to the same automated farm is permitted. * POD: Inter-VM page sharing among VMs belonging to the same Pod is permitted. * GLOBAL: Inter-VM page sharing among all VMs on the same host is permitted. | [optional] 
**VcenterId** | **string** | ID of the virtual center server. | 

## Methods

### NewFarmAutomatedSettingsCreateSpecV3

`func NewFarmAutomatedSettingsCreateSpecV3(customizationSettings FarmCustomizationSettingsCreateSpecV2, maxSessionType string, patternNamingSettings FarmRDSServersPatternNamingSettingsCreateSpec, provisioningSettings FarmProvisioningSettingsCreateSpecV2, storageSettings FarmStorageSettingsCreateSpec, vcenterId string, ) *FarmAutomatedSettingsCreateSpecV3`

NewFarmAutomatedSettingsCreateSpecV3 instantiates a new FarmAutomatedSettingsCreateSpecV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFarmAutomatedSettingsCreateSpecV3WithDefaults

`func NewFarmAutomatedSettingsCreateSpecV3WithDefaults() *FarmAutomatedSettingsCreateSpecV3`

NewFarmAutomatedSettingsCreateSpecV3WithDefaults instantiates a new FarmAutomatedSettingsCreateSpecV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomizationSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) GetCustomizationSettings() FarmCustomizationSettingsCreateSpecV2`

GetCustomizationSettings returns the CustomizationSettings field if non-nil, zero value otherwise.

### GetCustomizationSettingsOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetCustomizationSettingsOk() (*FarmCustomizationSettingsCreateSpecV2, bool)`

GetCustomizationSettingsOk returns a tuple with the CustomizationSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomizationSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) SetCustomizationSettings(v FarmCustomizationSettingsCreateSpecV2)`

SetCustomizationSettings sets CustomizationSettings field to given value.


### GetEnableProvisioning

`func (o *FarmAutomatedSettingsCreateSpecV3) GetEnableProvisioning() bool`

GetEnableProvisioning returns the EnableProvisioning field if non-nil, zero value otherwise.

### GetEnableProvisioningOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetEnableProvisioningOk() (*bool, bool)`

GetEnableProvisioningOk returns a tuple with the EnableProvisioning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableProvisioning

`func (o *FarmAutomatedSettingsCreateSpecV3) SetEnableProvisioning(v bool)`

SetEnableProvisioning sets EnableProvisioning field to given value.

### HasEnableProvisioning

`func (o *FarmAutomatedSettingsCreateSpecV3) HasEnableProvisioning() bool`

HasEnableProvisioning returns a boolean if a field has been set.

### GetMaxSessionType

`func (o *FarmAutomatedSettingsCreateSpecV3) GetMaxSessionType() string`

GetMaxSessionType returns the MaxSessionType field if non-nil, zero value otherwise.

### GetMaxSessionTypeOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetMaxSessionTypeOk() (*string, bool)`

GetMaxSessionTypeOk returns a tuple with the MaxSessionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSessionType

`func (o *FarmAutomatedSettingsCreateSpecV3) SetMaxSessionType(v string)`

SetMaxSessionType sets MaxSessionType field to given value.


### GetMaxSessions

`func (o *FarmAutomatedSettingsCreateSpecV3) GetMaxSessions() int32`

GetMaxSessions returns the MaxSessions field if non-nil, zero value otherwise.

### GetMaxSessionsOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetMaxSessionsOk() (*int32, bool)`

GetMaxSessionsOk returns a tuple with the MaxSessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSessions

`func (o *FarmAutomatedSettingsCreateSpecV3) SetMaxSessions(v int32)`

SetMaxSessions sets MaxSessions field to given value.

### HasMaxSessions

`func (o *FarmAutomatedSettingsCreateSpecV3) HasMaxSessions() bool`

HasMaxSessions returns a boolean if a field has been set.

### GetMinReadyVms

`func (o *FarmAutomatedSettingsCreateSpecV3) GetMinReadyVms() int32`

GetMinReadyVms returns the MinReadyVms field if non-nil, zero value otherwise.

### GetMinReadyVmsOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetMinReadyVmsOk() (*int32, bool)`

GetMinReadyVmsOk returns a tuple with the MinReadyVms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinReadyVms

`func (o *FarmAutomatedSettingsCreateSpecV3) SetMinReadyVms(v int32)`

SetMinReadyVms sets MinReadyVms field to given value.

### HasMinReadyVms

`func (o *FarmAutomatedSettingsCreateSpecV3) HasMinReadyVms() bool`

HasMinReadyVms returns a boolean if a field has been set.

### GetNics

`func (o *FarmAutomatedSettingsCreateSpecV3) GetNics() []FarmNetworkInterfaceCardSettingsCreateSpec`

GetNics returns the Nics field if non-nil, zero value otherwise.

### GetNicsOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetNicsOk() (*[]FarmNetworkInterfaceCardSettingsCreateSpec, bool)`

GetNicsOk returns a tuple with the Nics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNics

`func (o *FarmAutomatedSettingsCreateSpecV3) SetNics(v []FarmNetworkInterfaceCardSettingsCreateSpec)`

SetNics sets Nics field to given value.

### HasNics

`func (o *FarmAutomatedSettingsCreateSpecV3) HasNics() bool`

HasNics returns a boolean if a field has been set.

### GetPatternNamingSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) GetPatternNamingSettings() FarmRDSServersPatternNamingSettingsCreateSpec`

GetPatternNamingSettings returns the PatternNamingSettings field if non-nil, zero value otherwise.

### GetPatternNamingSettingsOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetPatternNamingSettingsOk() (*FarmRDSServersPatternNamingSettingsCreateSpec, bool)`

GetPatternNamingSettingsOk returns a tuple with the PatternNamingSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatternNamingSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) SetPatternNamingSettings(v FarmRDSServersPatternNamingSettingsCreateSpec)`

SetPatternNamingSettings sets PatternNamingSettings field to given value.


### GetProvisioningSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) GetProvisioningSettings() FarmProvisioningSettingsCreateSpecV2`

GetProvisioningSettings returns the ProvisioningSettings field if non-nil, zero value otherwise.

### GetProvisioningSettingsOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetProvisioningSettingsOk() (*FarmProvisioningSettingsCreateSpecV2, bool)`

GetProvisioningSettingsOk returns a tuple with the ProvisioningSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvisioningSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) SetProvisioningSettings(v FarmProvisioningSettingsCreateSpecV2)`

SetProvisioningSettings sets ProvisioningSettings field to given value.


### GetStopProvisioningOnError

`func (o *FarmAutomatedSettingsCreateSpecV3) GetStopProvisioningOnError() bool`

GetStopProvisioningOnError returns the StopProvisioningOnError field if non-nil, zero value otherwise.

### GetStopProvisioningOnErrorOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetStopProvisioningOnErrorOk() (*bool, bool)`

GetStopProvisioningOnErrorOk returns a tuple with the StopProvisioningOnError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopProvisioningOnError

`func (o *FarmAutomatedSettingsCreateSpecV3) SetStopProvisioningOnError(v bool)`

SetStopProvisioningOnError sets StopProvisioningOnError field to given value.

### HasStopProvisioningOnError

`func (o *FarmAutomatedSettingsCreateSpecV3) HasStopProvisioningOnError() bool`

HasStopProvisioningOnError returns a boolean if a field has been set.

### GetStorageSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) GetStorageSettings() FarmStorageSettingsCreateSpec`

GetStorageSettings returns the StorageSettings field if non-nil, zero value otherwise.

### GetStorageSettingsOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetStorageSettingsOk() (*FarmStorageSettingsCreateSpec, bool)`

GetStorageSettingsOk returns a tuple with the StorageSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageSettings

`func (o *FarmAutomatedSettingsCreateSpecV3) SetStorageSettings(v FarmStorageSettingsCreateSpec)`

SetStorageSettings sets StorageSettings field to given value.


### GetTransparentPageSharingScope

`func (o *FarmAutomatedSettingsCreateSpecV3) GetTransparentPageSharingScope() string`

GetTransparentPageSharingScope returns the TransparentPageSharingScope field if non-nil, zero value otherwise.

### GetTransparentPageSharingScopeOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetTransparentPageSharingScopeOk() (*string, bool)`

GetTransparentPageSharingScopeOk returns a tuple with the TransparentPageSharingScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransparentPageSharingScope

`func (o *FarmAutomatedSettingsCreateSpecV3) SetTransparentPageSharingScope(v string)`

SetTransparentPageSharingScope sets TransparentPageSharingScope field to given value.

### HasTransparentPageSharingScope

`func (o *FarmAutomatedSettingsCreateSpecV3) HasTransparentPageSharingScope() bool`

HasTransparentPageSharingScope returns a boolean if a field has been set.

### GetVcenterId

`func (o *FarmAutomatedSettingsCreateSpecV3) GetVcenterId() string`

GetVcenterId returns the VcenterId field if non-nil, zero value otherwise.

### GetVcenterIdOk

`func (o *FarmAutomatedSettingsCreateSpecV3) GetVcenterIdOk() (*string, bool)`

GetVcenterIdOk returns a tuple with the VcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVcenterId

`func (o *FarmAutomatedSettingsCreateSpecV3) SetVcenterId(v string)`

SetVcenterId sets VcenterId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


