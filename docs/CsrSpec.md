# CsrSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertificateUsage** | **string** | Indicates the type of certificate based on usage. * MACHINE: vdm certificates | 
**DnsSubjectAlternativeNames** | Pointer to **[]string** | Subject alternative DNS names. | [optional] 
**SubjectName** | **string** | Subject name. | 

## Methods

### NewCsrSpec

`func NewCsrSpec(certificateUsage string, subjectName string, ) *CsrSpec`

NewCsrSpec instantiates a new CsrSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCsrSpecWithDefaults

`func NewCsrSpecWithDefaults() *CsrSpec`

NewCsrSpecWithDefaults instantiates a new CsrSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificateUsage

`func (o *CsrSpec) GetCertificateUsage() string`

GetCertificateUsage returns the CertificateUsage field if non-nil, zero value otherwise.

### GetCertificateUsageOk

`func (o *CsrSpec) GetCertificateUsageOk() (*string, bool)`

GetCertificateUsageOk returns a tuple with the CertificateUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateUsage

`func (o *CsrSpec) SetCertificateUsage(v string)`

SetCertificateUsage sets CertificateUsage field to given value.


### GetDnsSubjectAlternativeNames

`func (o *CsrSpec) GetDnsSubjectAlternativeNames() []string`

GetDnsSubjectAlternativeNames returns the DnsSubjectAlternativeNames field if non-nil, zero value otherwise.

### GetDnsSubjectAlternativeNamesOk

`func (o *CsrSpec) GetDnsSubjectAlternativeNamesOk() (*[]string, bool)`

GetDnsSubjectAlternativeNamesOk returns a tuple with the DnsSubjectAlternativeNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsSubjectAlternativeNames

`func (o *CsrSpec) SetDnsSubjectAlternativeNames(v []string)`

SetDnsSubjectAlternativeNames sets DnsSubjectAlternativeNames field to given value.

### HasDnsSubjectAlternativeNames

`func (o *CsrSpec) HasDnsSubjectAlternativeNames() bool`

HasDnsSubjectAlternativeNames returns a boolean if a field has been set.

### GetSubjectName

`func (o *CsrSpec) GetSubjectName() string`

GetSubjectName returns the SubjectName field if non-nil, zero value otherwise.

### GetSubjectNameOk

`func (o *CsrSpec) GetSubjectNameOk() (*string, bool)`

GetSubjectNameOk returns a tuple with the SubjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectName

`func (o *CsrSpec) SetSubjectName(v string)`

SetSubjectName sets SubjectName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


