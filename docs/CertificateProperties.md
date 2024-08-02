# CertificateProperties

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KeyLength** | Pointer to **int32** | Certificate generation SSO Key length. | [optional] 
**Validity** | Pointer to **int32** | Certificate generation SSO key validity period in days. | [optional] 

## Methods

### NewCertificateProperties

`func NewCertificateProperties() *CertificateProperties`

NewCertificateProperties instantiates a new CertificateProperties object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCertificatePropertiesWithDefaults

`func NewCertificatePropertiesWithDefaults() *CertificateProperties`

NewCertificatePropertiesWithDefaults instantiates a new CertificateProperties object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKeyLength

`func (o *CertificateProperties) GetKeyLength() int32`

GetKeyLength returns the KeyLength field if non-nil, zero value otherwise.

### GetKeyLengthOk

`func (o *CertificateProperties) GetKeyLengthOk() (*int32, bool)`

GetKeyLengthOk returns a tuple with the KeyLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyLength

`func (o *CertificateProperties) SetKeyLength(v int32)`

SetKeyLength sets KeyLength field to given value.

### HasKeyLength

`func (o *CertificateProperties) HasKeyLength() bool`

HasKeyLength returns a boolean if a field has been set.

### GetValidity

`func (o *CertificateProperties) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *CertificateProperties) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *CertificateProperties) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *CertificateProperties) HasValidity() bool`

HasValidity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


