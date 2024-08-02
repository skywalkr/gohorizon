# CertificateData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowAdminOverride** | Pointer to **bool** | Indicates if admin override is allowed. | [optional] 
**Certificate** | Pointer to **string** | The certificate in string form. | [optional] 
**CertificateEncoding** | Pointer to **string** | The encoding of the certificate. | [optional] 
**InvalidReasons** | Pointer to **[]string** | The reason(s) why the certificate could not be validated. | [optional] 
**SslCertThumbprint** | Pointer to **string** | A digest of the certificate. | [optional] 
**SslCertThumbprintAlgorithm** | Pointer to **string** | Algorithm used to compute the thumbprint. | [optional] 
**Valid** | Pointer to **bool** | Indicates if certificate is valid. | [optional] 

## Methods

### NewCertificateData

`func NewCertificateData() *CertificateData`

NewCertificateData instantiates a new CertificateData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCertificateDataWithDefaults

`func NewCertificateDataWithDefaults() *CertificateData`

NewCertificateDataWithDefaults instantiates a new CertificateData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowAdminOverride

`func (o *CertificateData) GetAllowAdminOverride() bool`

GetAllowAdminOverride returns the AllowAdminOverride field if non-nil, zero value otherwise.

### GetAllowAdminOverrideOk

`func (o *CertificateData) GetAllowAdminOverrideOk() (*bool, bool)`

GetAllowAdminOverrideOk returns a tuple with the AllowAdminOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowAdminOverride

`func (o *CertificateData) SetAllowAdminOverride(v bool)`

SetAllowAdminOverride sets AllowAdminOverride field to given value.

### HasAllowAdminOverride

`func (o *CertificateData) HasAllowAdminOverride() bool`

HasAllowAdminOverride returns a boolean if a field has been set.

### GetCertificate

`func (o *CertificateData) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *CertificateData) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *CertificateData) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *CertificateData) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### GetCertificateEncoding

`func (o *CertificateData) GetCertificateEncoding() string`

GetCertificateEncoding returns the CertificateEncoding field if non-nil, zero value otherwise.

### GetCertificateEncodingOk

`func (o *CertificateData) GetCertificateEncodingOk() (*string, bool)`

GetCertificateEncodingOk returns a tuple with the CertificateEncoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateEncoding

`func (o *CertificateData) SetCertificateEncoding(v string)`

SetCertificateEncoding sets CertificateEncoding field to given value.

### HasCertificateEncoding

`func (o *CertificateData) HasCertificateEncoding() bool`

HasCertificateEncoding returns a boolean if a field has been set.

### GetInvalidReasons

`func (o *CertificateData) GetInvalidReasons() []string`

GetInvalidReasons returns the InvalidReasons field if non-nil, zero value otherwise.

### GetInvalidReasonsOk

`func (o *CertificateData) GetInvalidReasonsOk() (*[]string, bool)`

GetInvalidReasonsOk returns a tuple with the InvalidReasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidReasons

`func (o *CertificateData) SetInvalidReasons(v []string)`

SetInvalidReasons sets InvalidReasons field to given value.

### HasInvalidReasons

`func (o *CertificateData) HasInvalidReasons() bool`

HasInvalidReasons returns a boolean if a field has been set.

### GetSslCertThumbprint

`func (o *CertificateData) GetSslCertThumbprint() string`

GetSslCertThumbprint returns the SslCertThumbprint field if non-nil, zero value otherwise.

### GetSslCertThumbprintOk

`func (o *CertificateData) GetSslCertThumbprintOk() (*string, bool)`

GetSslCertThumbprintOk returns a tuple with the SslCertThumbprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSslCertThumbprint

`func (o *CertificateData) SetSslCertThumbprint(v string)`

SetSslCertThumbprint sets SslCertThumbprint field to given value.

### HasSslCertThumbprint

`func (o *CertificateData) HasSslCertThumbprint() bool`

HasSslCertThumbprint returns a boolean if a field has been set.

### GetSslCertThumbprintAlgorithm

`func (o *CertificateData) GetSslCertThumbprintAlgorithm() string`

GetSslCertThumbprintAlgorithm returns the SslCertThumbprintAlgorithm field if non-nil, zero value otherwise.

### GetSslCertThumbprintAlgorithmOk

`func (o *CertificateData) GetSslCertThumbprintAlgorithmOk() (*string, bool)`

GetSslCertThumbprintAlgorithmOk returns a tuple with the SslCertThumbprintAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSslCertThumbprintAlgorithm

`func (o *CertificateData) SetSslCertThumbprintAlgorithm(v string)`

SetSslCertThumbprintAlgorithm sets SslCertThumbprintAlgorithm field to given value.

### HasSslCertThumbprintAlgorithm

`func (o *CertificateData) HasSslCertThumbprintAlgorithm() bool`

HasSslCertThumbprintAlgorithm returns a boolean if a field has been set.

### GetValid

`func (o *CertificateData) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *CertificateData) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *CertificateData) SetValid(v bool)`

SetValid sets Valid field to given value.

### HasValid

`func (o *CertificateData) HasValid() bool`

HasValid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


