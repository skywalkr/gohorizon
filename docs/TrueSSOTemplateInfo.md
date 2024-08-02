# TrueSSOTemplateInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HashAlgorithm** | Pointer to **string** | Hash algorithm used in the certificate signing request. * SHA1: SHA-1 hashing algorithm. * SHA256: SHA-256 hashing algorithm. * SHA384: SHA-384 hashing algorithm. * SHA512: SHA-512 hashing algorithm. | [optional] 
**MinimumKeyLength** | Pointer to **int32** | Minimum key-length of the private/public key associated with the certificate. | [optional] 
**TemplateName** | Pointer to **string** | Unique name for this template. | [optional] 
**TemplateStatus** | Pointer to **string** | The status of this template. * SUPPORTED_OPTIMAL: This template has the optimal properties for TrueSSO. * SUPPORTED_NOT_OPTIMAL: This template does not have the ideal properties for TrueSSO. * UNKNOWN: This status of this template is unknown. A template with this status cannot be used in connector creation. * NO_CAPABILITY: This template is not configured to perform TrueSSO. A template with this status cannot be used in connector creation. * INVALID: This template is smart card logon enabled, but some setting is invalid. A template with this status cannot be used in connector creation. * MANUAL: This template is smart card logon enabled, but manual enrollment is needed. A template with this status cannot be used in connector creation. * UNSUITABLE: This template is smart card logon enabled, but is unsuitable. A template with this status cannot be used in connector creation. | [optional] 
**TemplateStatusReason** | Pointer to **string** | Additional non-localized explanation of the status. | [optional] 
**ValiditySeconds** | Pointer to **int64** | Length of time, in seconds, that certificates issues with this template remain valid. | [optional] 

## Methods

### NewTrueSSOTemplateInfo

`func NewTrueSSOTemplateInfo() *TrueSSOTemplateInfo`

NewTrueSSOTemplateInfo instantiates a new TrueSSOTemplateInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrueSSOTemplateInfoWithDefaults

`func NewTrueSSOTemplateInfoWithDefaults() *TrueSSOTemplateInfo`

NewTrueSSOTemplateInfoWithDefaults instantiates a new TrueSSOTemplateInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHashAlgorithm

`func (o *TrueSSOTemplateInfo) GetHashAlgorithm() string`

GetHashAlgorithm returns the HashAlgorithm field if non-nil, zero value otherwise.

### GetHashAlgorithmOk

`func (o *TrueSSOTemplateInfo) GetHashAlgorithmOk() (*string, bool)`

GetHashAlgorithmOk returns a tuple with the HashAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashAlgorithm

`func (o *TrueSSOTemplateInfo) SetHashAlgorithm(v string)`

SetHashAlgorithm sets HashAlgorithm field to given value.

### HasHashAlgorithm

`func (o *TrueSSOTemplateInfo) HasHashAlgorithm() bool`

HasHashAlgorithm returns a boolean if a field has been set.

### GetMinimumKeyLength

`func (o *TrueSSOTemplateInfo) GetMinimumKeyLength() int32`

GetMinimumKeyLength returns the MinimumKeyLength field if non-nil, zero value otherwise.

### GetMinimumKeyLengthOk

`func (o *TrueSSOTemplateInfo) GetMinimumKeyLengthOk() (*int32, bool)`

GetMinimumKeyLengthOk returns a tuple with the MinimumKeyLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumKeyLength

`func (o *TrueSSOTemplateInfo) SetMinimumKeyLength(v int32)`

SetMinimumKeyLength sets MinimumKeyLength field to given value.

### HasMinimumKeyLength

`func (o *TrueSSOTemplateInfo) HasMinimumKeyLength() bool`

HasMinimumKeyLength returns a boolean if a field has been set.

### GetTemplateName

`func (o *TrueSSOTemplateInfo) GetTemplateName() string`

GetTemplateName returns the TemplateName field if non-nil, zero value otherwise.

### GetTemplateNameOk

`func (o *TrueSSOTemplateInfo) GetTemplateNameOk() (*string, bool)`

GetTemplateNameOk returns a tuple with the TemplateName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateName

`func (o *TrueSSOTemplateInfo) SetTemplateName(v string)`

SetTemplateName sets TemplateName field to given value.

### HasTemplateName

`func (o *TrueSSOTemplateInfo) HasTemplateName() bool`

HasTemplateName returns a boolean if a field has been set.

### GetTemplateStatus

`func (o *TrueSSOTemplateInfo) GetTemplateStatus() string`

GetTemplateStatus returns the TemplateStatus field if non-nil, zero value otherwise.

### GetTemplateStatusOk

`func (o *TrueSSOTemplateInfo) GetTemplateStatusOk() (*string, bool)`

GetTemplateStatusOk returns a tuple with the TemplateStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateStatus

`func (o *TrueSSOTemplateInfo) SetTemplateStatus(v string)`

SetTemplateStatus sets TemplateStatus field to given value.

### HasTemplateStatus

`func (o *TrueSSOTemplateInfo) HasTemplateStatus() bool`

HasTemplateStatus returns a boolean if a field has been set.

### GetTemplateStatusReason

`func (o *TrueSSOTemplateInfo) GetTemplateStatusReason() string`

GetTemplateStatusReason returns the TemplateStatusReason field if non-nil, zero value otherwise.

### GetTemplateStatusReasonOk

`func (o *TrueSSOTemplateInfo) GetTemplateStatusReasonOk() (*string, bool)`

GetTemplateStatusReasonOk returns a tuple with the TemplateStatusReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateStatusReason

`func (o *TrueSSOTemplateInfo) SetTemplateStatusReason(v string)`

SetTemplateStatusReason sets TemplateStatusReason field to given value.

### HasTemplateStatusReason

`func (o *TrueSSOTemplateInfo) HasTemplateStatusReason() bool`

HasTemplateStatusReason returns a boolean if a field has been set.

### GetValiditySeconds

`func (o *TrueSSOTemplateInfo) GetValiditySeconds() int64`

GetValiditySeconds returns the ValiditySeconds field if non-nil, zero value otherwise.

### GetValiditySecondsOk

`func (o *TrueSSOTemplateInfo) GetValiditySecondsOk() (*int64, bool)`

GetValiditySecondsOk returns a tuple with the ValiditySeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValiditySeconds

`func (o *TrueSSOTemplateInfo) SetValiditySeconds(v int64)`

SetValiditySeconds sets ValiditySeconds field to given value.

### HasValiditySeconds

`func (o *TrueSSOTemplateInfo) HasValiditySeconds() bool`

HasValiditySeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


