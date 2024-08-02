# TrueSSOCertificateDomainInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CertificateServers** | Pointer to [**[]TrueSSOCertificateServerInfo**](TrueSSOCertificateServerInfo.md) | Collection of certificate server data available to this domain. | [optional] 
**DnsName** | Pointer to **string** | DNS name of the domain. | [optional] 
**DomainId** | Pointer to **string** | Id of the domain. | [optional] 
**DomainStatus** | Pointer to **string** | The status of this domain to the enrollment server. * READY: The domain is ready. * CREATED: The domain is created. * INITIALIZED: The domain is initialized. * CONNECTING: The domain is connecting. * ASSOCIATED: This domain has been associated with a Forest, but we do not yet have a connection to this domain. We have no means of syncing objects for this forest from this domain, so it may only operate as long as there is another domain in the same forest that we can synchronize with. * STOPPING: The domain is stopping. A domain with this status cannot be used in connector creation. * FAILED: The domain is failed. A domain with this status cannot be used in connector creation. * UNKNOWN: The domain status is unknown. A domain with this status cannot be used in connector creation. | [optional] 
**DomainStatusReason** | Pointer to **string** | Additional non-localized explanation of the domain status. | [optional] 
**EnrollmentCertificateStatus** | Pointer to **string** | The status of the enrollment server&#39;s certificate for this domain&#39;s forest. * VALID: A valid enrollment certificate for this domain&#39;s forest is installed on the enrollment server. * NOT_VALID: No valid enrollment certificate for this domain&#39;s forest is installed on the enrollment server, or it may have expired. An enrollment server with this status cannot be used in connector creation. | [optional] 
**ForestDnsName** | Pointer to **string** | DNS name of the domain&#39;s forest, if any. | [optional] 
**ReplicationStatus** | Pointer to **string** | This domain&#39;s forest&#39;s replication status with the domain controller. * OK: The enrollment server has read the enrollment properties at least once and is successfully able to update them periodically. * DEGRADED: The enrollment server has read the enrollment properties at least once, but has not been able to reach a domain controller for some time. * PENDING: he enrollment server has not yet read the enrollment properties from a domain controller. * FAILED: The enrollment server has read the enrollment properties at least once but either has not been able to reach a domain controller for an extended time or another issue exists. An enrollment server with this status cannot be used in connector creation. | [optional] 
**ReplicationStatusReason** | Pointer to **string** | Additional non-localized explanation of the replication status. | [optional] 
**Templates** | Pointer to [**[]TrueSSOTemplateInfo**](TrueSSOTemplateInfo.md) | Collection of certificate template data available to certificate servers on this domain. Not all certificate servers may have access to all of these templates. | [optional] 

## Methods

### NewTrueSSOCertificateDomainInfo

`func NewTrueSSOCertificateDomainInfo() *TrueSSOCertificateDomainInfo`

NewTrueSSOCertificateDomainInfo instantiates a new TrueSSOCertificateDomainInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrueSSOCertificateDomainInfoWithDefaults

`func NewTrueSSOCertificateDomainInfoWithDefaults() *TrueSSOCertificateDomainInfo`

NewTrueSSOCertificateDomainInfoWithDefaults instantiates a new TrueSSOCertificateDomainInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificateServers

`func (o *TrueSSOCertificateDomainInfo) GetCertificateServers() []TrueSSOCertificateServerInfo`

GetCertificateServers returns the CertificateServers field if non-nil, zero value otherwise.

### GetCertificateServersOk

`func (o *TrueSSOCertificateDomainInfo) GetCertificateServersOk() (*[]TrueSSOCertificateServerInfo, bool)`

GetCertificateServersOk returns a tuple with the CertificateServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateServers

`func (o *TrueSSOCertificateDomainInfo) SetCertificateServers(v []TrueSSOCertificateServerInfo)`

SetCertificateServers sets CertificateServers field to given value.

### HasCertificateServers

`func (o *TrueSSOCertificateDomainInfo) HasCertificateServers() bool`

HasCertificateServers returns a boolean if a field has been set.

### GetDnsName

`func (o *TrueSSOCertificateDomainInfo) GetDnsName() string`

GetDnsName returns the DnsName field if non-nil, zero value otherwise.

### GetDnsNameOk

`func (o *TrueSSOCertificateDomainInfo) GetDnsNameOk() (*string, bool)`

GetDnsNameOk returns a tuple with the DnsName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsName

`func (o *TrueSSOCertificateDomainInfo) SetDnsName(v string)`

SetDnsName sets DnsName field to given value.

### HasDnsName

`func (o *TrueSSOCertificateDomainInfo) HasDnsName() bool`

HasDnsName returns a boolean if a field has been set.

### GetDomainId

`func (o *TrueSSOCertificateDomainInfo) GetDomainId() string`

GetDomainId returns the DomainId field if non-nil, zero value otherwise.

### GetDomainIdOk

`func (o *TrueSSOCertificateDomainInfo) GetDomainIdOk() (*string, bool)`

GetDomainIdOk returns a tuple with the DomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainId

`func (o *TrueSSOCertificateDomainInfo) SetDomainId(v string)`

SetDomainId sets DomainId field to given value.

### HasDomainId

`func (o *TrueSSOCertificateDomainInfo) HasDomainId() bool`

HasDomainId returns a boolean if a field has been set.

### GetDomainStatus

`func (o *TrueSSOCertificateDomainInfo) GetDomainStatus() string`

GetDomainStatus returns the DomainStatus field if non-nil, zero value otherwise.

### GetDomainStatusOk

`func (o *TrueSSOCertificateDomainInfo) GetDomainStatusOk() (*string, bool)`

GetDomainStatusOk returns a tuple with the DomainStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainStatus

`func (o *TrueSSOCertificateDomainInfo) SetDomainStatus(v string)`

SetDomainStatus sets DomainStatus field to given value.

### HasDomainStatus

`func (o *TrueSSOCertificateDomainInfo) HasDomainStatus() bool`

HasDomainStatus returns a boolean if a field has been set.

### GetDomainStatusReason

`func (o *TrueSSOCertificateDomainInfo) GetDomainStatusReason() string`

GetDomainStatusReason returns the DomainStatusReason field if non-nil, zero value otherwise.

### GetDomainStatusReasonOk

`func (o *TrueSSOCertificateDomainInfo) GetDomainStatusReasonOk() (*string, bool)`

GetDomainStatusReasonOk returns a tuple with the DomainStatusReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainStatusReason

`func (o *TrueSSOCertificateDomainInfo) SetDomainStatusReason(v string)`

SetDomainStatusReason sets DomainStatusReason field to given value.

### HasDomainStatusReason

`func (o *TrueSSOCertificateDomainInfo) HasDomainStatusReason() bool`

HasDomainStatusReason returns a boolean if a field has been set.

### GetEnrollmentCertificateStatus

`func (o *TrueSSOCertificateDomainInfo) GetEnrollmentCertificateStatus() string`

GetEnrollmentCertificateStatus returns the EnrollmentCertificateStatus field if non-nil, zero value otherwise.

### GetEnrollmentCertificateStatusOk

`func (o *TrueSSOCertificateDomainInfo) GetEnrollmentCertificateStatusOk() (*string, bool)`

GetEnrollmentCertificateStatusOk returns a tuple with the EnrollmentCertificateStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrollmentCertificateStatus

`func (o *TrueSSOCertificateDomainInfo) SetEnrollmentCertificateStatus(v string)`

SetEnrollmentCertificateStatus sets EnrollmentCertificateStatus field to given value.

### HasEnrollmentCertificateStatus

`func (o *TrueSSOCertificateDomainInfo) HasEnrollmentCertificateStatus() bool`

HasEnrollmentCertificateStatus returns a boolean if a field has been set.

### GetForestDnsName

`func (o *TrueSSOCertificateDomainInfo) GetForestDnsName() string`

GetForestDnsName returns the ForestDnsName field if non-nil, zero value otherwise.

### GetForestDnsNameOk

`func (o *TrueSSOCertificateDomainInfo) GetForestDnsNameOk() (*string, bool)`

GetForestDnsNameOk returns a tuple with the ForestDnsName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForestDnsName

`func (o *TrueSSOCertificateDomainInfo) SetForestDnsName(v string)`

SetForestDnsName sets ForestDnsName field to given value.

### HasForestDnsName

`func (o *TrueSSOCertificateDomainInfo) HasForestDnsName() bool`

HasForestDnsName returns a boolean if a field has been set.

### GetReplicationStatus

`func (o *TrueSSOCertificateDomainInfo) GetReplicationStatus() string`

GetReplicationStatus returns the ReplicationStatus field if non-nil, zero value otherwise.

### GetReplicationStatusOk

`func (o *TrueSSOCertificateDomainInfo) GetReplicationStatusOk() (*string, bool)`

GetReplicationStatusOk returns a tuple with the ReplicationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplicationStatus

`func (o *TrueSSOCertificateDomainInfo) SetReplicationStatus(v string)`

SetReplicationStatus sets ReplicationStatus field to given value.

### HasReplicationStatus

`func (o *TrueSSOCertificateDomainInfo) HasReplicationStatus() bool`

HasReplicationStatus returns a boolean if a field has been set.

### GetReplicationStatusReason

`func (o *TrueSSOCertificateDomainInfo) GetReplicationStatusReason() string`

GetReplicationStatusReason returns the ReplicationStatusReason field if non-nil, zero value otherwise.

### GetReplicationStatusReasonOk

`func (o *TrueSSOCertificateDomainInfo) GetReplicationStatusReasonOk() (*string, bool)`

GetReplicationStatusReasonOk returns a tuple with the ReplicationStatusReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplicationStatusReason

`func (o *TrueSSOCertificateDomainInfo) SetReplicationStatusReason(v string)`

SetReplicationStatusReason sets ReplicationStatusReason field to given value.

### HasReplicationStatusReason

`func (o *TrueSSOCertificateDomainInfo) HasReplicationStatusReason() bool`

HasReplicationStatusReason returns a boolean if a field has been set.

### GetTemplates

`func (o *TrueSSOCertificateDomainInfo) GetTemplates() []TrueSSOTemplateInfo`

GetTemplates returns the Templates field if non-nil, zero value otherwise.

### GetTemplatesOk

`func (o *TrueSSOCertificateDomainInfo) GetTemplatesOk() (*[]TrueSSOTemplateInfo, bool)`

GetTemplatesOk returns a tuple with the Templates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplates

`func (o *TrueSSOCertificateDomainInfo) SetTemplates(v []TrueSSOTemplateInfo)`

SetTemplates sets Templates field to given value.

### HasTemplates

`func (o *TrueSSOCertificateDomainInfo) HasTemplates() bool`

HasTemplates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


