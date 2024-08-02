# RADIUSServerUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingPort** | **int32** | The accounting port of the RADIUS authentication server. | 
**AuthenticationPort** | **int32** | The authentication port of the RADIUS authentication server. Primary and secondary servers should not have both hostname and authentication port same. | 
**AuthenticationType** | **string** | The authentication type of the RADIUS authentication server. * PAP: Password authentication protocol. * CHAP: Challenge-handshake authentication protocol. * MSCHAP1: Microsoft challenge-handshake authentication protocol, version 1. * MSCHAP2: Microsoft challenge-handshake authentication protocol, version 2. * UNKNOWN: Indicates Auth type is unkonwn. | 
**Hostname** | **string** | The hostname of the RADIUS authentication server. Primary and secondary servers should not have both hostname and authentication port same. | 
**MaxAttempts** | **int32** | The maximum number of authentication attempts for the RADIUS authentication server. | 
**PrimaryRadiusServer** | **bool** | Indicates whether it is a primary RADIUS authentication server. There must be exactly one primary RADIUS server i.e. with primary_radius_server set to true. | 
**RealmPrefix** | Pointer to **string** | The realm prefix of the RADIUS authentication server. | [optional] 
**RealmSuffix** | Pointer to **string** | The realm suffix of the RADIUS authentication server. | [optional] 
**ServerTimeoutSeconds** | **int32** | The server timeout (in seconds) of the RADIUS authentication server. | 
**SharedSecret** | **[]string** | The shared secret of the RADIUS authentication server. | 

## Methods

### NewRADIUSServerUpdateSpec

`func NewRADIUSServerUpdateSpec(accountingPort int32, authenticationPort int32, authenticationType string, hostname string, maxAttempts int32, primaryRadiusServer bool, serverTimeoutSeconds int32, sharedSecret []string, ) *RADIUSServerUpdateSpec`

NewRADIUSServerUpdateSpec instantiates a new RADIUSServerUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRADIUSServerUpdateSpecWithDefaults

`func NewRADIUSServerUpdateSpecWithDefaults() *RADIUSServerUpdateSpec`

NewRADIUSServerUpdateSpecWithDefaults instantiates a new RADIUSServerUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingPort

`func (o *RADIUSServerUpdateSpec) GetAccountingPort() int32`

GetAccountingPort returns the AccountingPort field if non-nil, zero value otherwise.

### GetAccountingPortOk

`func (o *RADIUSServerUpdateSpec) GetAccountingPortOk() (*int32, bool)`

GetAccountingPortOk returns a tuple with the AccountingPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingPort

`func (o *RADIUSServerUpdateSpec) SetAccountingPort(v int32)`

SetAccountingPort sets AccountingPort field to given value.


### GetAuthenticationPort

`func (o *RADIUSServerUpdateSpec) GetAuthenticationPort() int32`

GetAuthenticationPort returns the AuthenticationPort field if non-nil, zero value otherwise.

### GetAuthenticationPortOk

`func (o *RADIUSServerUpdateSpec) GetAuthenticationPortOk() (*int32, bool)`

GetAuthenticationPortOk returns a tuple with the AuthenticationPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticationPort

`func (o *RADIUSServerUpdateSpec) SetAuthenticationPort(v int32)`

SetAuthenticationPort sets AuthenticationPort field to given value.


### GetAuthenticationType

`func (o *RADIUSServerUpdateSpec) GetAuthenticationType() string`

GetAuthenticationType returns the AuthenticationType field if non-nil, zero value otherwise.

### GetAuthenticationTypeOk

`func (o *RADIUSServerUpdateSpec) GetAuthenticationTypeOk() (*string, bool)`

GetAuthenticationTypeOk returns a tuple with the AuthenticationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticationType

`func (o *RADIUSServerUpdateSpec) SetAuthenticationType(v string)`

SetAuthenticationType sets AuthenticationType field to given value.


### GetHostname

`func (o *RADIUSServerUpdateSpec) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *RADIUSServerUpdateSpec) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *RADIUSServerUpdateSpec) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### GetMaxAttempts

`func (o *RADIUSServerUpdateSpec) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *RADIUSServerUpdateSpec) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *RADIUSServerUpdateSpec) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.


### GetPrimaryRadiusServer

`func (o *RADIUSServerUpdateSpec) GetPrimaryRadiusServer() bool`

GetPrimaryRadiusServer returns the PrimaryRadiusServer field if non-nil, zero value otherwise.

### GetPrimaryRadiusServerOk

`func (o *RADIUSServerUpdateSpec) GetPrimaryRadiusServerOk() (*bool, bool)`

GetPrimaryRadiusServerOk returns a tuple with the PrimaryRadiusServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryRadiusServer

`func (o *RADIUSServerUpdateSpec) SetPrimaryRadiusServer(v bool)`

SetPrimaryRadiusServer sets PrimaryRadiusServer field to given value.


### GetRealmPrefix

`func (o *RADIUSServerUpdateSpec) GetRealmPrefix() string`

GetRealmPrefix returns the RealmPrefix field if non-nil, zero value otherwise.

### GetRealmPrefixOk

`func (o *RADIUSServerUpdateSpec) GetRealmPrefixOk() (*string, bool)`

GetRealmPrefixOk returns a tuple with the RealmPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealmPrefix

`func (o *RADIUSServerUpdateSpec) SetRealmPrefix(v string)`

SetRealmPrefix sets RealmPrefix field to given value.

### HasRealmPrefix

`func (o *RADIUSServerUpdateSpec) HasRealmPrefix() bool`

HasRealmPrefix returns a boolean if a field has been set.

### GetRealmSuffix

`func (o *RADIUSServerUpdateSpec) GetRealmSuffix() string`

GetRealmSuffix returns the RealmSuffix field if non-nil, zero value otherwise.

### GetRealmSuffixOk

`func (o *RADIUSServerUpdateSpec) GetRealmSuffixOk() (*string, bool)`

GetRealmSuffixOk returns a tuple with the RealmSuffix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealmSuffix

`func (o *RADIUSServerUpdateSpec) SetRealmSuffix(v string)`

SetRealmSuffix sets RealmSuffix field to given value.

### HasRealmSuffix

`func (o *RADIUSServerUpdateSpec) HasRealmSuffix() bool`

HasRealmSuffix returns a boolean if a field has been set.

### GetServerTimeoutSeconds

`func (o *RADIUSServerUpdateSpec) GetServerTimeoutSeconds() int32`

GetServerTimeoutSeconds returns the ServerTimeoutSeconds field if non-nil, zero value otherwise.

### GetServerTimeoutSecondsOk

`func (o *RADIUSServerUpdateSpec) GetServerTimeoutSecondsOk() (*int32, bool)`

GetServerTimeoutSecondsOk returns a tuple with the ServerTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerTimeoutSeconds

`func (o *RADIUSServerUpdateSpec) SetServerTimeoutSeconds(v int32)`

SetServerTimeoutSeconds sets ServerTimeoutSeconds field to given value.


### GetSharedSecret

`func (o *RADIUSServerUpdateSpec) GetSharedSecret() []string`

GetSharedSecret returns the SharedSecret field if non-nil, zero value otherwise.

### GetSharedSecretOk

`func (o *RADIUSServerUpdateSpec) GetSharedSecretOk() (*[]string, bool)`

GetSharedSecretOk returns a tuple with the SharedSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedSecret

`func (o *RADIUSServerUpdateSpec) SetSharedSecret(v []string)`

SetSharedSecret sets SharedSecret field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


