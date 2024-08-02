# SettingsUpdateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FeatureSettings** | Pointer to [**FeatureSettingsUpdateSpec**](FeatureSettingsUpdateSpec.md) |  | [optional] 
**GeneralSettings** | Pointer to [**GeneralSettingsUpdateSpecV2**](GeneralSettingsUpdateSpecV2.md) |  | [optional] 
**SecuritySettings** | Pointer to [**SecuritySettingsUpdateSpec**](SecuritySettingsUpdateSpec.md) |  | [optional] 

## Methods

### NewSettingsUpdateSpecV2

`func NewSettingsUpdateSpecV2() *SettingsUpdateSpecV2`

NewSettingsUpdateSpecV2 instantiates a new SettingsUpdateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSettingsUpdateSpecV2WithDefaults

`func NewSettingsUpdateSpecV2WithDefaults() *SettingsUpdateSpecV2`

NewSettingsUpdateSpecV2WithDefaults instantiates a new SettingsUpdateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatureSettings

`func (o *SettingsUpdateSpecV2) GetFeatureSettings() FeatureSettingsUpdateSpec`

GetFeatureSettings returns the FeatureSettings field if non-nil, zero value otherwise.

### GetFeatureSettingsOk

`func (o *SettingsUpdateSpecV2) GetFeatureSettingsOk() (*FeatureSettingsUpdateSpec, bool)`

GetFeatureSettingsOk returns a tuple with the FeatureSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureSettings

`func (o *SettingsUpdateSpecV2) SetFeatureSettings(v FeatureSettingsUpdateSpec)`

SetFeatureSettings sets FeatureSettings field to given value.

### HasFeatureSettings

`func (o *SettingsUpdateSpecV2) HasFeatureSettings() bool`

HasFeatureSettings returns a boolean if a field has been set.

### GetGeneralSettings

`func (o *SettingsUpdateSpecV2) GetGeneralSettings() GeneralSettingsUpdateSpecV2`

GetGeneralSettings returns the GeneralSettings field if non-nil, zero value otherwise.

### GetGeneralSettingsOk

`func (o *SettingsUpdateSpecV2) GetGeneralSettingsOk() (*GeneralSettingsUpdateSpecV2, bool)`

GetGeneralSettingsOk returns a tuple with the GeneralSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneralSettings

`func (o *SettingsUpdateSpecV2) SetGeneralSettings(v GeneralSettingsUpdateSpecV2)`

SetGeneralSettings sets GeneralSettings field to given value.

### HasGeneralSettings

`func (o *SettingsUpdateSpecV2) HasGeneralSettings() bool`

HasGeneralSettings returns a boolean if a field has been set.

### GetSecuritySettings

`func (o *SettingsUpdateSpecV2) GetSecuritySettings() SecuritySettingsUpdateSpec`

GetSecuritySettings returns the SecuritySettings field if non-nil, zero value otherwise.

### GetSecuritySettingsOk

`func (o *SettingsUpdateSpecV2) GetSecuritySettingsOk() (*SecuritySettingsUpdateSpec, bool)`

GetSecuritySettingsOk returns a tuple with the SecuritySettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecuritySettings

`func (o *SettingsUpdateSpecV2) SetSecuritySettings(v SecuritySettingsUpdateSpec)`

SetSecuritySettings sets SecuritySettings field to given value.

### HasSecuritySettings

`func (o *SettingsUpdateSpecV2) HasSecuritySettings() bool`

HasSecuritySettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


