# CertificateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertificateChain** | **string** | Certificate chain. | 
**CertificatePassword** | Pointer to **[]string** | Password for pfx certificate type. | [optional] 
**CertificateUsage** | **string** | Indicates the type of certificate based on usage. * MACHINE: vdm certificates | 
**Format** | **string** | Certificate Type. | 

## Methods

### NewCertificateSpec

`func NewCertificateSpec(certificateChain string, certificateUsage string, format string, ) *CertificateSpec`

NewCertificateSpec instantiates a new CertificateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCertificateSpecWithDefaults

`func NewCertificateSpecWithDefaults() *CertificateSpec`

NewCertificateSpecWithDefaults instantiates a new CertificateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificateChain

`func (o *CertificateSpec) GetCertificateChain() string`

GetCertificateChain returns the CertificateChain field if non-nil, zero value otherwise.

### GetCertificateChainOk

`func (o *CertificateSpec) GetCertificateChainOk() (*string, bool)`

GetCertificateChainOk returns a tuple with the CertificateChain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateChain

`func (o *CertificateSpec) SetCertificateChain(v string)`

SetCertificateChain sets CertificateChain field to given value.


### GetCertificatePassword

`func (o *CertificateSpec) GetCertificatePassword() []string`

GetCertificatePassword returns the CertificatePassword field if non-nil, zero value otherwise.

### GetCertificatePasswordOk

`func (o *CertificateSpec) GetCertificatePasswordOk() (*[]string, bool)`

GetCertificatePasswordOk returns a tuple with the CertificatePassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificatePassword

`func (o *CertificateSpec) SetCertificatePassword(v []string)`

SetCertificatePassword sets CertificatePassword field to given value.

### HasCertificatePassword

`func (o *CertificateSpec) HasCertificatePassword() bool`

HasCertificatePassword returns a boolean if a field has been set.

### GetCertificateUsage

`func (o *CertificateSpec) GetCertificateUsage() string`

GetCertificateUsage returns the CertificateUsage field if non-nil, zero value otherwise.

### GetCertificateUsageOk

`func (o *CertificateSpec) GetCertificateUsageOk() (*string, bool)`

GetCertificateUsageOk returns a tuple with the CertificateUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateUsage

`func (o *CertificateSpec) SetCertificateUsage(v string)`

SetCertificateUsage sets CertificateUsage field to given value.


### GetFormat

`func (o *CertificateSpec) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *CertificateSpec) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *CertificateSpec) SetFormat(v string)`

SetFormat sets Format field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


