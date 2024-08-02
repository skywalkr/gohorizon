# AdminUserOrGroupPreferencesUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminTimeoutInMinutes** | Pointer to **int32** | UI console session timeout preference in minutes for Horizon Console. | [optional] 
**GridPreferences** | Pointer to **map[string][]string** | Grid preferences for data grids on Horizon Console. | [optional] 

## Methods

### NewAdminUserOrGroupPreferencesUpdateSpec

`func NewAdminUserOrGroupPreferencesUpdateSpec() *AdminUserOrGroupPreferencesUpdateSpec`

NewAdminUserOrGroupPreferencesUpdateSpec instantiates a new AdminUserOrGroupPreferencesUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminUserOrGroupPreferencesUpdateSpecWithDefaults

`func NewAdminUserOrGroupPreferencesUpdateSpecWithDefaults() *AdminUserOrGroupPreferencesUpdateSpec`

NewAdminUserOrGroupPreferencesUpdateSpecWithDefaults instantiates a new AdminUserOrGroupPreferencesUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminTimeoutInMinutes

`func (o *AdminUserOrGroupPreferencesUpdateSpec) GetAdminTimeoutInMinutes() int32`

GetAdminTimeoutInMinutes returns the AdminTimeoutInMinutes field if non-nil, zero value otherwise.

### GetAdminTimeoutInMinutesOk

`func (o *AdminUserOrGroupPreferencesUpdateSpec) GetAdminTimeoutInMinutesOk() (*int32, bool)`

GetAdminTimeoutInMinutesOk returns a tuple with the AdminTimeoutInMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminTimeoutInMinutes

`func (o *AdminUserOrGroupPreferencesUpdateSpec) SetAdminTimeoutInMinutes(v int32)`

SetAdminTimeoutInMinutes sets AdminTimeoutInMinutes field to given value.

### HasAdminTimeoutInMinutes

`func (o *AdminUserOrGroupPreferencesUpdateSpec) HasAdminTimeoutInMinutes() bool`

HasAdminTimeoutInMinutes returns a boolean if a field has been set.

### GetGridPreferences

`func (o *AdminUserOrGroupPreferencesUpdateSpec) GetGridPreferences() map[string][]string`

GetGridPreferences returns the GridPreferences field if non-nil, zero value otherwise.

### GetGridPreferencesOk

`func (o *AdminUserOrGroupPreferencesUpdateSpec) GetGridPreferencesOk() (*map[string][]string, bool)`

GetGridPreferencesOk returns a tuple with the GridPreferences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGridPreferences

`func (o *AdminUserOrGroupPreferencesUpdateSpec) SetGridPreferences(v map[string][]string)`

SetGridPreferences sets GridPreferences field to given value.

### HasGridPreferences

`func (o *AdminUserOrGroupPreferencesUpdateSpec) HasGridPreferences() bool`

HasGridPreferences returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


