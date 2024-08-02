# SecurityConfigInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertificateProperties** | Pointer to [**CertificateProperties**](CertificateProperties.md) |  | [optional] 
**ConnectionServerSecurityConfig** | Pointer to [**SecurityConfiguration**](SecurityConfiguration.md) |  | [optional] 
**SecureGatewaySecurityConfig** | Pointer to [**SecurityConfiguration**](SecurityConfiguration.md) |  | [optional] 

## Methods

### NewSecurityConfigInfo

`func NewSecurityConfigInfo() *SecurityConfigInfo`

NewSecurityConfigInfo instantiates a new SecurityConfigInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecurityConfigInfoWithDefaults

`func NewSecurityConfigInfoWithDefaults() *SecurityConfigInfo`

NewSecurityConfigInfoWithDefaults instantiates a new SecurityConfigInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificateProperties

`func (o *SecurityConfigInfo) GetCertificateProperties() CertificateProperties`

GetCertificateProperties returns the CertificateProperties field if non-nil, zero value otherwise.

### GetCertificatePropertiesOk

`func (o *SecurityConfigInfo) GetCertificatePropertiesOk() (*CertificateProperties, bool)`

GetCertificatePropertiesOk returns a tuple with the CertificateProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateProperties

`func (o *SecurityConfigInfo) SetCertificateProperties(v CertificateProperties)`

SetCertificateProperties sets CertificateProperties field to given value.

### HasCertificateProperties

`func (o *SecurityConfigInfo) HasCertificateProperties() bool`

HasCertificateProperties returns a boolean if a field has been set.

### GetConnectionServerSecurityConfig

`func (o *SecurityConfigInfo) GetConnectionServerSecurityConfig() SecurityConfiguration`

GetConnectionServerSecurityConfig returns the ConnectionServerSecurityConfig field if non-nil, zero value otherwise.

### GetConnectionServerSecurityConfigOk

`func (o *SecurityConfigInfo) GetConnectionServerSecurityConfigOk() (*SecurityConfiguration, bool)`

GetConnectionServerSecurityConfigOk returns a tuple with the ConnectionServerSecurityConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionServerSecurityConfig

`func (o *SecurityConfigInfo) SetConnectionServerSecurityConfig(v SecurityConfiguration)`

SetConnectionServerSecurityConfig sets ConnectionServerSecurityConfig field to given value.

### HasConnectionServerSecurityConfig

`func (o *SecurityConfigInfo) HasConnectionServerSecurityConfig() bool`

HasConnectionServerSecurityConfig returns a boolean if a field has been set.

### GetSecureGatewaySecurityConfig

`func (o *SecurityConfigInfo) GetSecureGatewaySecurityConfig() SecurityConfiguration`

GetSecureGatewaySecurityConfig returns the SecureGatewaySecurityConfig field if non-nil, zero value otherwise.

### GetSecureGatewaySecurityConfigOk

`func (o *SecurityConfigInfo) GetSecureGatewaySecurityConfigOk() (*SecurityConfiguration, bool)`

GetSecureGatewaySecurityConfigOk returns a tuple with the SecureGatewaySecurityConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecureGatewaySecurityConfig

`func (o *SecurityConfigInfo) SetSecureGatewaySecurityConfig(v SecurityConfiguration)`

SetSecureGatewaySecurityConfig sets SecureGatewaySecurityConfig field to given value.

### HasSecureGatewaySecurityConfig

`func (o *SecurityConfigInfo) HasSecureGatewaySecurityConfig() bool`

HasSecureGatewaySecurityConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


