# CertificateInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertificateUsage** | Pointer to **string** | Indicates how the certificate would be used. * MACHINE: vdm certificates | [optional] 
**DnssubjectAlternativeNames** | Pointer to **[]string** |  | [optional] 
**InUse** | Pointer to **bool** | Indicates whether certificate is currently used by server or not. | [optional] 
**InvalidReasons** | Pointer to **[]string** | Indicates the reason for invalid certificate. | [optional] 
**IsValid** | Pointer to **bool** | Indicates whether certificate is valid or not. | [optional] 
**IssuerName** | Pointer to **string** | Issuer name of certificate. | [optional] 
**SerialNumber** | Pointer to **string** | Serial number of certificate. | [optional] 
**Sha1Thumbprint** | Pointer to **string** | SHA1 thumbprint of certificate. | [optional] 
**SignatureAlgorithm** | Pointer to **string** | Signature algorithm of certificate. | [optional] 
**SubjectName** | Pointer to **string** | Subject name of certificate. | [optional] 
**ValidFrom** | Pointer to **string** | Certificate valid from. Numeric version of ISO 8601 format. | [optional] 
**ValidUntil** | Pointer to **string** | Certificate valid until. Numeric version of ISO 8601 format. | [optional] 

## Methods

### NewCertificateInfo

`func NewCertificateInfo() *CertificateInfo`

NewCertificateInfo instantiates a new CertificateInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCertificateInfoWithDefaults

`func NewCertificateInfoWithDefaults() *CertificateInfo`

NewCertificateInfoWithDefaults instantiates a new CertificateInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificateUsage

`func (o *CertificateInfo) GetCertificateUsage() string`

GetCertificateUsage returns the CertificateUsage field if non-nil, zero value otherwise.

### GetCertificateUsageOk

`func (o *CertificateInfo) GetCertificateUsageOk() (*string, bool)`

GetCertificateUsageOk returns a tuple with the CertificateUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateUsage

`func (o *CertificateInfo) SetCertificateUsage(v string)`

SetCertificateUsage sets CertificateUsage field to given value.

### HasCertificateUsage

`func (o *CertificateInfo) HasCertificateUsage() bool`

HasCertificateUsage returns a boolean if a field has been set.

### GetDnssubjectAlternativeNames

`func (o *CertificateInfo) GetDnssubjectAlternativeNames() []string`

GetDnssubjectAlternativeNames returns the DnssubjectAlternativeNames field if non-nil, zero value otherwise.

### GetDnssubjectAlternativeNamesOk

`func (o *CertificateInfo) GetDnssubjectAlternativeNamesOk() (*[]string, bool)`

GetDnssubjectAlternativeNamesOk returns a tuple with the DnssubjectAlternativeNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnssubjectAlternativeNames

`func (o *CertificateInfo) SetDnssubjectAlternativeNames(v []string)`

SetDnssubjectAlternativeNames sets DnssubjectAlternativeNames field to given value.

### HasDnssubjectAlternativeNames

`func (o *CertificateInfo) HasDnssubjectAlternativeNames() bool`

HasDnssubjectAlternativeNames returns a boolean if a field has been set.

### GetInUse

`func (o *CertificateInfo) GetInUse() bool`

GetInUse returns the InUse field if non-nil, zero value otherwise.

### GetInUseOk

`func (o *CertificateInfo) GetInUseOk() (*bool, bool)`

GetInUseOk returns a tuple with the InUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInUse

`func (o *CertificateInfo) SetInUse(v bool)`

SetInUse sets InUse field to given value.

### HasInUse

`func (o *CertificateInfo) HasInUse() bool`

HasInUse returns a boolean if a field has been set.

### GetInvalidReasons

`func (o *CertificateInfo) GetInvalidReasons() []string`

GetInvalidReasons returns the InvalidReasons field if non-nil, zero value otherwise.

### GetInvalidReasonsOk

`func (o *CertificateInfo) GetInvalidReasonsOk() (*[]string, bool)`

GetInvalidReasonsOk returns a tuple with the InvalidReasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidReasons

`func (o *CertificateInfo) SetInvalidReasons(v []string)`

SetInvalidReasons sets InvalidReasons field to given value.

### HasInvalidReasons

`func (o *CertificateInfo) HasInvalidReasons() bool`

HasInvalidReasons returns a boolean if a field has been set.

### GetIsValid

`func (o *CertificateInfo) GetIsValid() bool`

GetIsValid returns the IsValid field if non-nil, zero value otherwise.

### GetIsValidOk

`func (o *CertificateInfo) GetIsValidOk() (*bool, bool)`

GetIsValidOk returns a tuple with the IsValid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsValid

`func (o *CertificateInfo) SetIsValid(v bool)`

SetIsValid sets IsValid field to given value.

### HasIsValid

`func (o *CertificateInfo) HasIsValid() bool`

HasIsValid returns a boolean if a field has been set.

### GetIssuerName

`func (o *CertificateInfo) GetIssuerName() string`

GetIssuerName returns the IssuerName field if non-nil, zero value otherwise.

### GetIssuerNameOk

`func (o *CertificateInfo) GetIssuerNameOk() (*string, bool)`

GetIssuerNameOk returns a tuple with the IssuerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuerName

`func (o *CertificateInfo) SetIssuerName(v string)`

SetIssuerName sets IssuerName field to given value.

### HasIssuerName

`func (o *CertificateInfo) HasIssuerName() bool`

HasIssuerName returns a boolean if a field has been set.

### GetSerialNumber

`func (o *CertificateInfo) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *CertificateInfo) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *CertificateInfo) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *CertificateInfo) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetSha1Thumbprint

`func (o *CertificateInfo) GetSha1Thumbprint() string`

GetSha1Thumbprint returns the Sha1Thumbprint field if non-nil, zero value otherwise.

### GetSha1ThumbprintOk

`func (o *CertificateInfo) GetSha1ThumbprintOk() (*string, bool)`

GetSha1ThumbprintOk returns a tuple with the Sha1Thumbprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1Thumbprint

`func (o *CertificateInfo) SetSha1Thumbprint(v string)`

SetSha1Thumbprint sets Sha1Thumbprint field to given value.

### HasSha1Thumbprint

`func (o *CertificateInfo) HasSha1Thumbprint() bool`

HasSha1Thumbprint returns a boolean if a field has been set.

### GetSignatureAlgorithm

`func (o *CertificateInfo) GetSignatureAlgorithm() string`

GetSignatureAlgorithm returns the SignatureAlgorithm field if non-nil, zero value otherwise.

### GetSignatureAlgorithmOk

`func (o *CertificateInfo) GetSignatureAlgorithmOk() (*string, bool)`

GetSignatureAlgorithmOk returns a tuple with the SignatureAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureAlgorithm

`func (o *CertificateInfo) SetSignatureAlgorithm(v string)`

SetSignatureAlgorithm sets SignatureAlgorithm field to given value.

### HasSignatureAlgorithm

`func (o *CertificateInfo) HasSignatureAlgorithm() bool`

HasSignatureAlgorithm returns a boolean if a field has been set.

### GetSubjectName

`func (o *CertificateInfo) GetSubjectName() string`

GetSubjectName returns the SubjectName field if non-nil, zero value otherwise.

### GetSubjectNameOk

`func (o *CertificateInfo) GetSubjectNameOk() (*string, bool)`

GetSubjectNameOk returns a tuple with the SubjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectName

`func (o *CertificateInfo) SetSubjectName(v string)`

SetSubjectName sets SubjectName field to given value.

### HasSubjectName

`func (o *CertificateInfo) HasSubjectName() bool`

HasSubjectName returns a boolean if a field has been set.

### GetValidFrom

`func (o *CertificateInfo) GetValidFrom() string`

GetValidFrom returns the ValidFrom field if non-nil, zero value otherwise.

### GetValidFromOk

`func (o *CertificateInfo) GetValidFromOk() (*string, bool)`

GetValidFromOk returns a tuple with the ValidFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidFrom

`func (o *CertificateInfo) SetValidFrom(v string)`

SetValidFrom sets ValidFrom field to given value.

### HasValidFrom

`func (o *CertificateInfo) HasValidFrom() bool`

HasValidFrom returns a boolean if a field has been set.

### GetValidUntil

`func (o *CertificateInfo) GetValidUntil() string`

GetValidUntil returns the ValidUntil field if non-nil, zero value otherwise.

### GetValidUntilOk

`func (o *CertificateInfo) GetValidUntilOk() (*string, bool)`

GetValidUntilOk returns a tuple with the ValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidUntil

`func (o *CertificateInfo) SetValidUntil(v string)`

SetValidUntil sets ValidUntil field to given value.

### HasValidUntil

`func (o *CertificateInfo) HasValidUntil() bool`

HasValidUntil returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


