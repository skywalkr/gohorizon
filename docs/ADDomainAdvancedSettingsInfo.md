# ADDomainAdvancedSettingsInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdDomainAutoDiscovery** | Pointer to **bool** | Auto discovers domain controllers. Auto discovery, AD domain controllers and preferred site name are mutually exclusive. Only one of them can be defined at a time. Default value is true. | [optional] 
**AdDomainContext** | Pointer to **string** | Active directory domain Context. | [optional] 
**AdDomainControllers** | Pointer to **[]string** | One or more AD domain controllers. Auto discovery, AD domain controllers and preferred site name are mutually exclusive.  Only one of them can be defined at a time. | [optional] 
**AdDomainPreferredSite** | Pointer to **string** | ADDomain preferred domain site. Auto discovery, AD domain controllers and preferred site name are mutually exclusive. Only one of them can be defined at a time. | [optional] 
**Port** | Pointer to **int32** | Port of the server to connect to. | [optional] 

## Methods

### NewADDomainAdvancedSettingsInfo

`func NewADDomainAdvancedSettingsInfo() *ADDomainAdvancedSettingsInfo`

NewADDomainAdvancedSettingsInfo instantiates a new ADDomainAdvancedSettingsInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewADDomainAdvancedSettingsInfoWithDefaults

`func NewADDomainAdvancedSettingsInfoWithDefaults() *ADDomainAdvancedSettingsInfo`

NewADDomainAdvancedSettingsInfoWithDefaults instantiates a new ADDomainAdvancedSettingsInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdDomainAutoDiscovery

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainAutoDiscovery() bool`

GetAdDomainAutoDiscovery returns the AdDomainAutoDiscovery field if non-nil, zero value otherwise.

### GetAdDomainAutoDiscoveryOk

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainAutoDiscoveryOk() (*bool, bool)`

GetAdDomainAutoDiscoveryOk returns a tuple with the AdDomainAutoDiscovery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdDomainAutoDiscovery

`func (o *ADDomainAdvancedSettingsInfo) SetAdDomainAutoDiscovery(v bool)`

SetAdDomainAutoDiscovery sets AdDomainAutoDiscovery field to given value.

### HasAdDomainAutoDiscovery

`func (o *ADDomainAdvancedSettingsInfo) HasAdDomainAutoDiscovery() bool`

HasAdDomainAutoDiscovery returns a boolean if a field has been set.

### GetAdDomainContext

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainContext() string`

GetAdDomainContext returns the AdDomainContext field if non-nil, zero value otherwise.

### GetAdDomainContextOk

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainContextOk() (*string, bool)`

GetAdDomainContextOk returns a tuple with the AdDomainContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdDomainContext

`func (o *ADDomainAdvancedSettingsInfo) SetAdDomainContext(v string)`

SetAdDomainContext sets AdDomainContext field to given value.

### HasAdDomainContext

`func (o *ADDomainAdvancedSettingsInfo) HasAdDomainContext() bool`

HasAdDomainContext returns a boolean if a field has been set.

### GetAdDomainControllers

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainControllers() []string`

GetAdDomainControllers returns the AdDomainControllers field if non-nil, zero value otherwise.

### GetAdDomainControllersOk

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainControllersOk() (*[]string, bool)`

GetAdDomainControllersOk returns a tuple with the AdDomainControllers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdDomainControllers

`func (o *ADDomainAdvancedSettingsInfo) SetAdDomainControllers(v []string)`

SetAdDomainControllers sets AdDomainControllers field to given value.

### HasAdDomainControllers

`func (o *ADDomainAdvancedSettingsInfo) HasAdDomainControllers() bool`

HasAdDomainControllers returns a boolean if a field has been set.

### GetAdDomainPreferredSite

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainPreferredSite() string`

GetAdDomainPreferredSite returns the AdDomainPreferredSite field if non-nil, zero value otherwise.

### GetAdDomainPreferredSiteOk

`func (o *ADDomainAdvancedSettingsInfo) GetAdDomainPreferredSiteOk() (*string, bool)`

GetAdDomainPreferredSiteOk returns a tuple with the AdDomainPreferredSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdDomainPreferredSite

`func (o *ADDomainAdvancedSettingsInfo) SetAdDomainPreferredSite(v string)`

SetAdDomainPreferredSite sets AdDomainPreferredSite field to given value.

### HasAdDomainPreferredSite

`func (o *ADDomainAdvancedSettingsInfo) HasAdDomainPreferredSite() bool`

HasAdDomainPreferredSite returns a boolean if a field has been set.

### GetPort

`func (o *ADDomainAdvancedSettingsInfo) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *ADDomainAdvancedSettingsInfo) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *ADDomainAdvancedSettingsInfo) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *ADDomainAdvancedSettingsInfo) HasPort() bool`

HasPort returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


