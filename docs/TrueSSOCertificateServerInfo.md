# TrueSSOCertificateServerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertificateServerName** | Pointer to **string** | Unique (common) name of this certificate server. | [optional] 
**CertificateServerNetworkAddress** | Pointer to **string** | DNS name network address of this certificate server. | [optional] 
**CertificateStatus** | Pointer to **string** | The status of the certificate server&#39;s certificate. * VALID: The certificate is valid. * NOT_YET_VALID: The certificate is not yet valid. * UNKNOWN: The certificate status is unknown. A certificate server with a certificate with this status cannot be used in connector creation. * INVALID: The certificate is corrupt or unable to be used. A certificate server with a certificate with this status cannot be used in connector creation. * EXPIRED: The certificate has expired. A certificate server with a certificate with this status cannot be used in connector creation. * NOT_TRUSTED: The certificate is not in the NTAuth (Enterprise) store. A certificate server with a certificate with this status cannot be used in connector creation. | [optional] 
**ConnectionStatus** | Pointer to **string** | The status of the enrollment server&#39;s connection to the certificate server. * CONNECTED: The enrollment server is connected to the certificate server. * CONNECTED_DEGRADED: The enrollment server has connected to the certificate server, but the certificate server is in a degraded state. Either the database is loading and it can&#39;t yet issue certificates (for up to 20 seconds) OR the last request took an excessive time to complete (more than 1000 milliseconds). * SERVICE_UNAVAILABLE: The enrollment server can connect to the certificate server, but the service is unavailable. A certificate server with a service in this status cannot be used in connector creation. * DISCONNECTED: The enrollment server is not connected to the certificate server. | [optional] 
**ConnectionStatusReason** | Pointer to **string** | Additional non-localized explanation of the connection status. | [optional] 
**TemplateNames** | Pointer to **[]string** | Collection of certificate template names available to this certificate server. | [optional] 

## Methods

### NewTrueSSOCertificateServerInfo

`func NewTrueSSOCertificateServerInfo() *TrueSSOCertificateServerInfo`

NewTrueSSOCertificateServerInfo instantiates a new TrueSSOCertificateServerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrueSSOCertificateServerInfoWithDefaults

`func NewTrueSSOCertificateServerInfoWithDefaults() *TrueSSOCertificateServerInfo`

NewTrueSSOCertificateServerInfoWithDefaults instantiates a new TrueSSOCertificateServerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificateServerName

`func (o *TrueSSOCertificateServerInfo) GetCertificateServerName() string`

GetCertificateServerName returns the CertificateServerName field if non-nil, zero value otherwise.

### GetCertificateServerNameOk

`func (o *TrueSSOCertificateServerInfo) GetCertificateServerNameOk() (*string, bool)`

GetCertificateServerNameOk returns a tuple with the CertificateServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateServerName

`func (o *TrueSSOCertificateServerInfo) SetCertificateServerName(v string)`

SetCertificateServerName sets CertificateServerName field to given value.

### HasCertificateServerName

`func (o *TrueSSOCertificateServerInfo) HasCertificateServerName() bool`

HasCertificateServerName returns a boolean if a field has been set.

### GetCertificateServerNetworkAddress

`func (o *TrueSSOCertificateServerInfo) GetCertificateServerNetworkAddress() string`

GetCertificateServerNetworkAddress returns the CertificateServerNetworkAddress field if non-nil, zero value otherwise.

### GetCertificateServerNetworkAddressOk

`func (o *TrueSSOCertificateServerInfo) GetCertificateServerNetworkAddressOk() (*string, bool)`

GetCertificateServerNetworkAddressOk returns a tuple with the CertificateServerNetworkAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateServerNetworkAddress

`func (o *TrueSSOCertificateServerInfo) SetCertificateServerNetworkAddress(v string)`

SetCertificateServerNetworkAddress sets CertificateServerNetworkAddress field to given value.

### HasCertificateServerNetworkAddress

`func (o *TrueSSOCertificateServerInfo) HasCertificateServerNetworkAddress() bool`

HasCertificateServerNetworkAddress returns a boolean if a field has been set.

### GetCertificateStatus

`func (o *TrueSSOCertificateServerInfo) GetCertificateStatus() string`

GetCertificateStatus returns the CertificateStatus field if non-nil, zero value otherwise.

### GetCertificateStatusOk

`func (o *TrueSSOCertificateServerInfo) GetCertificateStatusOk() (*string, bool)`

GetCertificateStatusOk returns a tuple with the CertificateStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateStatus

`func (o *TrueSSOCertificateServerInfo) SetCertificateStatus(v string)`

SetCertificateStatus sets CertificateStatus field to given value.

### HasCertificateStatus

`func (o *TrueSSOCertificateServerInfo) HasCertificateStatus() bool`

HasCertificateStatus returns a boolean if a field has been set.

### GetConnectionStatus

`func (o *TrueSSOCertificateServerInfo) GetConnectionStatus() string`

GetConnectionStatus returns the ConnectionStatus field if non-nil, zero value otherwise.

### GetConnectionStatusOk

`func (o *TrueSSOCertificateServerInfo) GetConnectionStatusOk() (*string, bool)`

GetConnectionStatusOk returns a tuple with the ConnectionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionStatus

`func (o *TrueSSOCertificateServerInfo) SetConnectionStatus(v string)`

SetConnectionStatus sets ConnectionStatus field to given value.

### HasConnectionStatus

`func (o *TrueSSOCertificateServerInfo) HasConnectionStatus() bool`

HasConnectionStatus returns a boolean if a field has been set.

### GetConnectionStatusReason

`func (o *TrueSSOCertificateServerInfo) GetConnectionStatusReason() string`

GetConnectionStatusReason returns the ConnectionStatusReason field if non-nil, zero value otherwise.

### GetConnectionStatusReasonOk

`func (o *TrueSSOCertificateServerInfo) GetConnectionStatusReasonOk() (*string, bool)`

GetConnectionStatusReasonOk returns a tuple with the ConnectionStatusReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionStatusReason

`func (o *TrueSSOCertificateServerInfo) SetConnectionStatusReason(v string)`

SetConnectionStatusReason sets ConnectionStatusReason field to given value.

### HasConnectionStatusReason

`func (o *TrueSSOCertificateServerInfo) HasConnectionStatusReason() bool`

HasConnectionStatusReason returns a boolean if a field has been set.

### GetTemplateNames

`func (o *TrueSSOCertificateServerInfo) GetTemplateNames() []string`

GetTemplateNames returns the TemplateNames field if non-nil, zero value otherwise.

### GetTemplateNamesOk

`func (o *TrueSSOCertificateServerInfo) GetTemplateNamesOk() (*[]string, bool)`

GetTemplateNamesOk returns a tuple with the TemplateNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateNames

`func (o *TrueSSOCertificateServerInfo) SetTemplateNames(v []string)`

SetTemplateNames sets TemplateNames field to given value.

### HasTemplateNames

`func (o *TrueSSOCertificateServerInfo) HasTemplateNames() bool`

HasTemplateNames returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


