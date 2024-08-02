# RADIUSServerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingPort** | Pointer to **int32** | The accounting port of the RADIUS authentication server. | [optional] 
**AuthenticationPort** | Pointer to **int32** | The authentication port of the RADIUS authentication server. | [optional] 
**AuthenticationType** | Pointer to **string** | The authentication type of the RADIUS authentication server. * PAP: Password authentication protocol. * CHAP: Challenge-handshake authentication protocol. * MSCHAP1: Microsoft challenge-handshake authentication protocol, version 1. * MSCHAP2: Microsoft challenge-handshake authentication protocol, version 2. * UNKNOWN: Indicates Auth type is unkonwn. | [optional] 
**Hostname** | Pointer to **string** | The hostname of the RADIUS authentication server. | [optional] 
**MaxAttempts** | Pointer to **int32** | The maximum number of authentication attempts for the RADIUS authentication server. | [optional] 
**PrimaryRadiusServer** | Pointer to **bool** | Indicates whether it is a primary RADIUS authentication server. | [optional] 
**RealmPrefix** | Pointer to **string** | The realm prefix of the RADIUS authentication server. | [optional] 
**RealmSuffix** | Pointer to **string** | The realm suffix of the RADIUS authentication server. | [optional] 
**ServerTimeoutSeconds** | Pointer to **int32** | The server timeout (in seconds) of the RADIUS authentication server. | [optional] 

## Methods

### NewRADIUSServerInfo

`func NewRADIUSServerInfo() *RADIUSServerInfo`

NewRADIUSServerInfo instantiates a new RADIUSServerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRADIUSServerInfoWithDefaults

`func NewRADIUSServerInfoWithDefaults() *RADIUSServerInfo`

NewRADIUSServerInfoWithDefaults instantiates a new RADIUSServerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingPort

`func (o *RADIUSServerInfo) GetAccountingPort() int32`

GetAccountingPort returns the AccountingPort field if non-nil, zero value otherwise.

### GetAccountingPortOk

`func (o *RADIUSServerInfo) GetAccountingPortOk() (*int32, bool)`

GetAccountingPortOk returns a tuple with the AccountingPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingPort

`func (o *RADIUSServerInfo) SetAccountingPort(v int32)`

SetAccountingPort sets AccountingPort field to given value.

### HasAccountingPort

`func (o *RADIUSServerInfo) HasAccountingPort() bool`

HasAccountingPort returns a boolean if a field has been set.

### GetAuthenticationPort

`func (o *RADIUSServerInfo) GetAuthenticationPort() int32`

GetAuthenticationPort returns the AuthenticationPort field if non-nil, zero value otherwise.

### GetAuthenticationPortOk

`func (o *RADIUSServerInfo) GetAuthenticationPortOk() (*int32, bool)`

GetAuthenticationPortOk returns a tuple with the AuthenticationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticationPort

`func (o *RADIUSServerInfo) SetAuthenticationPort(v int32)`

SetAuthenticationPort sets AuthenticationPort field to given value.

### HasAuthenticationPort

`func (o *RADIUSServerInfo) HasAuthenticationPort() bool`

HasAuthenticationPort returns a boolean if a field has been set.

### GetAuthenticationType

`func (o *RADIUSServerInfo) GetAuthenticationType() string`

GetAuthenticationType returns the AuthenticationType field if non-nil, zero value otherwise.

### GetAuthenticationTypeOk

`func (o *RADIUSServerInfo) GetAuthenticationTypeOk() (*string, bool)`

GetAuthenticationTypeOk returns a tuple with the AuthenticationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticationType

`func (o *RADIUSServerInfo) SetAuthenticationType(v string)`

SetAuthenticationType sets AuthenticationType field to given value.

### HasAuthenticationType

`func (o *RADIUSServerInfo) HasAuthenticationType() bool`

HasAuthenticationType returns a boolean if a field has been set.

### GetHostname

`func (o *RADIUSServerInfo) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *RADIUSServerInfo) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *RADIUSServerInfo) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *RADIUSServerInfo) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### GetMaxAttempts

`func (o *RADIUSServerInfo) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *RADIUSServerInfo) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *RADIUSServerInfo) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.

### HasMaxAttempts

`func (o *RADIUSServerInfo) HasMaxAttempts() bool`

HasMaxAttempts returns a boolean if a field has been set.

### GetPrimaryRadiusServer

`func (o *RADIUSServerInfo) GetPrimaryRadiusServer() bool`

GetPrimaryRadiusServer returns the PrimaryRadiusServer field if non-nil, zero value otherwise.

### GetPrimaryRadiusServerOk

`func (o *RADIUSServerInfo) GetPrimaryRadiusServerOk() (*bool, bool)`

GetPrimaryRadiusServerOk returns a tuple with the PrimaryRadiusServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryRadiusServer

`func (o *RADIUSServerInfo) SetPrimaryRadiusServer(v bool)`

SetPrimaryRadiusServer sets PrimaryRadiusServer field to given value.

### HasPrimaryRadiusServer

`func (o *RADIUSServerInfo) HasPrimaryRadiusServer() bool`

HasPrimaryRadiusServer returns a boolean if a field has been set.

### GetRealmPrefix

`func (o *RADIUSServerInfo) GetRealmPrefix() string`

GetRealmPrefix returns the RealmPrefix field if non-nil, zero value otherwise.

### GetRealmPrefixOk

`func (o *RADIUSServerInfo) GetRealmPrefixOk() (*string, bool)`

GetRealmPrefixOk returns a tuple with the RealmPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealmPrefix

`func (o *RADIUSServerInfo) SetRealmPrefix(v string)`

SetRealmPrefix sets RealmPrefix field to given value.

### HasRealmPrefix

`func (o *RADIUSServerInfo) HasRealmPrefix() bool`

HasRealmPrefix returns a boolean if a field has been set.

### GetRealmSuffix

`func (o *RADIUSServerInfo) GetRealmSuffix() string`

GetRealmSuffix returns the RealmSuffix field if non-nil, zero value otherwise.

### GetRealmSuffixOk

`func (o *RADIUSServerInfo) GetRealmSuffixOk() (*string, bool)`

GetRealmSuffixOk returns a tuple with the RealmSuffix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealmSuffix

`func (o *RADIUSServerInfo) SetRealmSuffix(v string)`

SetRealmSuffix sets RealmSuffix field to given value.

### HasRealmSuffix

`func (o *RADIUSServerInfo) HasRealmSuffix() bool`

HasRealmSuffix returns a boolean if a field has been set.

### GetServerTimeoutSeconds

`func (o *RADIUSServerInfo) GetServerTimeoutSeconds() int32`

GetServerTimeoutSeconds returns the ServerTimeoutSeconds field if non-nil, zero value otherwise.

### GetServerTimeoutSecondsOk

`func (o *RADIUSServerInfo) GetServerTimeoutSecondsOk() (*int32, bool)`

GetServerTimeoutSecondsOk returns a tuple with the ServerTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerTimeoutSeconds

`func (o *RADIUSServerInfo) SetServerTimeoutSeconds(v int32)`

SetServerTimeoutSeconds sets ServerTimeoutSeconds field to given value.

### HasServerTimeoutSeconds

`func (o *RADIUSServerInfo) HasServerTimeoutSeconds() bool`

HasServerTimeoutSeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


