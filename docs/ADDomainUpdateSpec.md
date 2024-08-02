# ADDomainUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdDomainAdvancedSettings** | [**ADDomainAdvancedSettings**](ADDomainAdvancedSettings.md) |  | 
**PrimaryAccount** | [**ADDomainServiceAccountSpec**](ADDomainServiceAccountSpec.md) |  | 

## Methods

### NewADDomainUpdateSpec

`func NewADDomainUpdateSpec(adDomainAdvancedSettings ADDomainAdvancedSettings, primaryAccount ADDomainServiceAccountSpec, ) *ADDomainUpdateSpec`

NewADDomainUpdateSpec instantiates a new ADDomainUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewADDomainUpdateSpecWithDefaults

`func NewADDomainUpdateSpecWithDefaults() *ADDomainUpdateSpec`

NewADDomainUpdateSpecWithDefaults instantiates a new ADDomainUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdDomainAdvancedSettings

`func (o *ADDomainUpdateSpec) GetAdDomainAdvancedSettings() ADDomainAdvancedSettings`

GetAdDomainAdvancedSettings returns the AdDomainAdvancedSettings field if non-nil, zero value otherwise.

### GetAdDomainAdvancedSettingsOk

`func (o *ADDomainUpdateSpec) GetAdDomainAdvancedSettingsOk() (*ADDomainAdvancedSettings, bool)`

GetAdDomainAdvancedSettingsOk returns a tuple with the AdDomainAdvancedSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdDomainAdvancedSettings

`func (o *ADDomainUpdateSpec) SetAdDomainAdvancedSettings(v ADDomainAdvancedSettings)`

SetAdDomainAdvancedSettings sets AdDomainAdvancedSettings field to given value.


### GetPrimaryAccount

`func (o *ADDomainUpdateSpec) GetPrimaryAccount() ADDomainServiceAccountSpec`

GetPrimaryAccount returns the PrimaryAccount field if non-nil, zero value otherwise.

### GetPrimaryAccountOk

`func (o *ADDomainUpdateSpec) GetPrimaryAccountOk() (*ADDomainServiceAccountSpec, bool)`

GetPrimaryAccountOk returns a tuple with the PrimaryAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryAccount

`func (o *ADDomainUpdateSpec) SetPrimaryAccount(v ADDomainServiceAccountSpec)`

SetPrimaryAccount sets PrimaryAccount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


