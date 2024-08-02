# SettingsInfoV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FeatureSettings** | Pointer to [**FeatureSettings**](FeatureSettings.md) |  | [optional] 
**GeneralSettings** | Pointer to [**GeneralSettingsV3**](GeneralSettingsV3.md) |  | [optional] 
**SecuritySettings** | Pointer to [**SecuritySettingsV2**](SecuritySettingsV2.md) |  | [optional] 

## Methods

### NewSettingsInfoV3

`func NewSettingsInfoV3() *SettingsInfoV3`

NewSettingsInfoV3 instantiates a new SettingsInfoV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSettingsInfoV3WithDefaults

`func NewSettingsInfoV3WithDefaults() *SettingsInfoV3`

NewSettingsInfoV3WithDefaults instantiates a new SettingsInfoV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatureSettings

`func (o *SettingsInfoV3) GetFeatureSettings() FeatureSettings`

GetFeatureSettings returns the FeatureSettings field if non-nil, zero value otherwise.

### GetFeatureSettingsOk

`func (o *SettingsInfoV3) GetFeatureSettingsOk() (*FeatureSettings, bool)`

GetFeatureSettingsOk returns a tuple with the FeatureSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureSettings

`func (o *SettingsInfoV3) SetFeatureSettings(v FeatureSettings)`

SetFeatureSettings sets FeatureSettings field to given value.

### HasFeatureSettings

`func (o *SettingsInfoV3) HasFeatureSettings() bool`

HasFeatureSettings returns a boolean if a field has been set.

### GetGeneralSettings

`func (o *SettingsInfoV3) GetGeneralSettings() GeneralSettingsV3`

GetGeneralSettings returns the GeneralSettings field if non-nil, zero value otherwise.

### GetGeneralSettingsOk

`func (o *SettingsInfoV3) GetGeneralSettingsOk() (*GeneralSettingsV3, bool)`

GetGeneralSettingsOk returns a tuple with the GeneralSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneralSettings

`func (o *SettingsInfoV3) SetGeneralSettings(v GeneralSettingsV3)`

SetGeneralSettings sets GeneralSettings field to given value.

### HasGeneralSettings

`func (o *SettingsInfoV3) HasGeneralSettings() bool`

HasGeneralSettings returns a boolean if a field has been set.

### GetSecuritySettings

`func (o *SettingsInfoV3) GetSecuritySettings() SecuritySettingsV2`

GetSecuritySettings returns the SecuritySettings field if non-nil, zero value otherwise.

### GetSecuritySettingsOk

`func (o *SettingsInfoV3) GetSecuritySettingsOk() (*SecuritySettingsV2, bool)`

GetSecuritySettingsOk returns a tuple with the SecuritySettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecuritySettings

`func (o *SettingsInfoV3) SetSecuritySettings(v SecuritySettingsV2)`

SetSecuritySettings sets SecuritySettings field to given value.

### HasSecuritySettings

`func (o *SettingsInfoV3) HasSecuritySettings() bool`

HasSecuritySettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


