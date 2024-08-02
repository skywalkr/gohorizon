# LicenseModeSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LicenseMode** | **string** | The license mode used. * DEFAULT: Perpetual license is in use. * PERPETUAL_ONLY: Perpetual license is in use. * SUBSCRIPTION: Cloud subscription license is in use. | 

## Methods

### NewLicenseModeSpec

`func NewLicenseModeSpec(licenseMode string, ) *LicenseModeSpec`

NewLicenseModeSpec instantiates a new LicenseModeSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseModeSpecWithDefaults

`func NewLicenseModeSpecWithDefaults() *LicenseModeSpec`

NewLicenseModeSpecWithDefaults instantiates a new LicenseModeSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLicenseMode

`func (o *LicenseModeSpec) GetLicenseMode() string`

GetLicenseMode returns the LicenseMode field if non-nil, zero value otherwise.

### GetLicenseModeOk

`func (o *LicenseModeSpec) GetLicenseModeOk() (*string, bool)`

GetLicenseModeOk returns a tuple with the LicenseMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseMode

`func (o *LicenseModeSpec) SetLicenseMode(v string)`

SetLicenseMode sets LicenseMode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


