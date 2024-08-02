# CEIPInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompanySize** | Pointer to **string** | The size of the company. * SIZE_1_100: Company size between 1 and 100. * SIZE_101_500: Company size between 101 and 500. * SIZE_501_1000: Company size between 501 and 1000. * SIZE_1001_5000: Company size between 1001 and 5000. * SIZE_5001_10000: Company size between 5001 and 10000. * SIZE_10001: Company size greater than 10000. | [optional] 
**Enabled** | Pointer to **bool** | Indicates whether to send information to VMware. | [optional] 
**Geolocation** | Pointer to **string** | The geolocation of the company. | [optional] 
**Vertical** | Pointer to **string** | The vertical of the company. | [optional] 

## Methods

### NewCEIPInfo

`func NewCEIPInfo() *CEIPInfo`

NewCEIPInfo instantiates a new CEIPInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCEIPInfoWithDefaults

`func NewCEIPInfoWithDefaults() *CEIPInfo`

NewCEIPInfoWithDefaults instantiates a new CEIPInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompanySize

`func (o *CEIPInfo) GetCompanySize() string`

GetCompanySize returns the CompanySize field if non-nil, zero value otherwise.

### GetCompanySizeOk

`func (o *CEIPInfo) GetCompanySizeOk() (*string, bool)`

GetCompanySizeOk returns a tuple with the CompanySize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanySize

`func (o *CEIPInfo) SetCompanySize(v string)`

SetCompanySize sets CompanySize field to given value.

### HasCompanySize

`func (o *CEIPInfo) HasCompanySize() bool`

HasCompanySize returns a boolean if a field has been set.

### GetEnabled

`func (o *CEIPInfo) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CEIPInfo) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CEIPInfo) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CEIPInfo) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetGeolocation

`func (o *CEIPInfo) GetGeolocation() string`

GetGeolocation returns the Geolocation field if non-nil, zero value otherwise.

### GetGeolocationOk

`func (o *CEIPInfo) GetGeolocationOk() (*string, bool)`

GetGeolocationOk returns a tuple with the Geolocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeolocation

`func (o *CEIPInfo) SetGeolocation(v string)`

SetGeolocation sets Geolocation field to given value.

### HasGeolocation

`func (o *CEIPInfo) HasGeolocation() bool`

HasGeolocation returns a boolean if a field has been set.

### GetVertical

`func (o *CEIPInfo) GetVertical() string`

GetVertical returns the Vertical field if non-nil, zero value otherwise.

### GetVerticalOk

`func (o *CEIPInfo) GetVerticalOk() (*string, bool)`

GetVerticalOk returns a tuple with the Vertical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVertical

`func (o *CEIPInfo) SetVertical(v string)`

SetVertical sets Vertical field to given value.

### HasVertical

`func (o *CEIPInfo) HasVertical() bool`

HasVertical returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


