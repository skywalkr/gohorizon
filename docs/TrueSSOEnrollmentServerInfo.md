# TrueSSOEnrollmentServerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectorIds** | Pointer to **[]string** | TrueSSO connectors, if any, associated with this enrollment server. | [optional] 
**Domains** | Pointer to [**[]TrueSSOCertificateDomainInfo**](TrueSSOCertificateDomainInfo.md) | Collection of domain data available to this enrollment server. | [optional] 
**Id** | Pointer to **string** | Unique ID representing this TrueSSO Enrollment Server. | [optional] 
**Name** | Pointer to **string** | Name of this enrollment server. | [optional] 
**NetworkAddress** | Pointer to **string** | DNS name network address of this enrollment server. | [optional] 
**Status** | Pointer to **string** | The status of this enrollment server. * ONLINE: The connection to the enrollment server is working properly. * OFFLINE: The enrollment server is not responding. An enrollment server with this status cannot be used in connector creation. | [optional] 
**Version** | Pointer to **string** | Version number of this enrollment server. | [optional] 

## Methods

### NewTrueSSOEnrollmentServerInfo

`func NewTrueSSOEnrollmentServerInfo() *TrueSSOEnrollmentServerInfo`

NewTrueSSOEnrollmentServerInfo instantiates a new TrueSSOEnrollmentServerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrueSSOEnrollmentServerInfoWithDefaults

`func NewTrueSSOEnrollmentServerInfoWithDefaults() *TrueSSOEnrollmentServerInfo`

NewTrueSSOEnrollmentServerInfoWithDefaults instantiates a new TrueSSOEnrollmentServerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectorIds

`func (o *TrueSSOEnrollmentServerInfo) GetConnectorIds() []string`

GetConnectorIds returns the ConnectorIds field if non-nil, zero value otherwise.

### GetConnectorIdsOk

`func (o *TrueSSOEnrollmentServerInfo) GetConnectorIdsOk() (*[]string, bool)`

GetConnectorIdsOk returns a tuple with the ConnectorIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorIds

`func (o *TrueSSOEnrollmentServerInfo) SetConnectorIds(v []string)`

SetConnectorIds sets ConnectorIds field to given value.

### HasConnectorIds

`func (o *TrueSSOEnrollmentServerInfo) HasConnectorIds() bool`

HasConnectorIds returns a boolean if a field has been set.

### GetDomains

`func (o *TrueSSOEnrollmentServerInfo) GetDomains() []TrueSSOCertificateDomainInfo`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *TrueSSOEnrollmentServerInfo) GetDomainsOk() (*[]TrueSSOCertificateDomainInfo, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *TrueSSOEnrollmentServerInfo) SetDomains(v []TrueSSOCertificateDomainInfo)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *TrueSSOEnrollmentServerInfo) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### GetId

`func (o *TrueSSOEnrollmentServerInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TrueSSOEnrollmentServerInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TrueSSOEnrollmentServerInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *TrueSSOEnrollmentServerInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *TrueSSOEnrollmentServerInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TrueSSOEnrollmentServerInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TrueSSOEnrollmentServerInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TrueSSOEnrollmentServerInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNetworkAddress

`func (o *TrueSSOEnrollmentServerInfo) GetNetworkAddress() string`

GetNetworkAddress returns the NetworkAddress field if non-nil, zero value otherwise.

### GetNetworkAddressOk

`func (o *TrueSSOEnrollmentServerInfo) GetNetworkAddressOk() (*string, bool)`

GetNetworkAddressOk returns a tuple with the NetworkAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkAddress

`func (o *TrueSSOEnrollmentServerInfo) SetNetworkAddress(v string)`

SetNetworkAddress sets NetworkAddress field to given value.

### HasNetworkAddress

`func (o *TrueSSOEnrollmentServerInfo) HasNetworkAddress() bool`

HasNetworkAddress returns a boolean if a field has been set.

### GetStatus

`func (o *TrueSSOEnrollmentServerInfo) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TrueSSOEnrollmentServerInfo) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TrueSSOEnrollmentServerInfo) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TrueSSOEnrollmentServerInfo) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetVersion

`func (o *TrueSSOEnrollmentServerInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *TrueSSOEnrollmentServerInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *TrueSSOEnrollmentServerInfo) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *TrueSSOEnrollmentServerInfo) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


