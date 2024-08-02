# GSSAPIAuthenticatorInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowLegacyClients** | Pointer to **bool** | Indicates whether the legacy Horizon clients will be allowed to use login as current user. | [optional] 
**AllowNtlmFallback** | Pointer to **bool** | Indicates whether NTLM is allowed for GSSAPI authentication. When the client does not have access to the domain controllers in the hosted environment kerberos authentication fails, clients can fall back to NTLM authentication if allowNTLMFallback is set to true. | [optional] 
**ConnectionServers** | Pointer to **[]string** | The list of Connection Servers for which this GSSAPI authenticator is enabled. | [optional] 
**EnableLoginAsCurrentUser** | Pointer to **bool** | Indicates whether the login as current user is enabled or not. | [optional] 
**EnforceChannelBindings** | Pointer to **bool** | Indicates whether channel bindings is supported or not. | [optional] 
**Id** | Pointer to **string** | Unique ID representing this GSSAPI Authenticator. | [optional] 
**TriggerMode** | Pointer to **string** | Indicates True SSO trigger mode on sessions using this authenticator. * DISABLED: Do not use True SSO. * OPTIONAL: If no SSO credentials are provided then use True SSO otherwise use the supplied SSO credentials. * ENABLED: Always use True SSO even if client supplied SSO credentials. | [optional] 

## Methods

### NewGSSAPIAuthenticatorInfo

`func NewGSSAPIAuthenticatorInfo() *GSSAPIAuthenticatorInfo`

NewGSSAPIAuthenticatorInfo instantiates a new GSSAPIAuthenticatorInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGSSAPIAuthenticatorInfoWithDefaults

`func NewGSSAPIAuthenticatorInfoWithDefaults() *GSSAPIAuthenticatorInfo`

NewGSSAPIAuthenticatorInfoWithDefaults instantiates a new GSSAPIAuthenticatorInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowLegacyClients

`func (o *GSSAPIAuthenticatorInfo) GetAllowLegacyClients() bool`

GetAllowLegacyClients returns the AllowLegacyClients field if non-nil, zero value otherwise.

### GetAllowLegacyClientsOk

`func (o *GSSAPIAuthenticatorInfo) GetAllowLegacyClientsOk() (*bool, bool)`

GetAllowLegacyClientsOk returns a tuple with the AllowLegacyClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLegacyClients

`func (o *GSSAPIAuthenticatorInfo) SetAllowLegacyClients(v bool)`

SetAllowLegacyClients sets AllowLegacyClients field to given value.

### HasAllowLegacyClients

`func (o *GSSAPIAuthenticatorInfo) HasAllowLegacyClients() bool`

HasAllowLegacyClients returns a boolean if a field has been set.

### GetAllowNtlmFallback

`func (o *GSSAPIAuthenticatorInfo) GetAllowNtlmFallback() bool`

GetAllowNtlmFallback returns the AllowNtlmFallback field if non-nil, zero value otherwise.

### GetAllowNtlmFallbackOk

`func (o *GSSAPIAuthenticatorInfo) GetAllowNtlmFallbackOk() (*bool, bool)`

GetAllowNtlmFallbackOk returns a tuple with the AllowNtlmFallback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowNtlmFallback

`func (o *GSSAPIAuthenticatorInfo) SetAllowNtlmFallback(v bool)`

SetAllowNtlmFallback sets AllowNtlmFallback field to given value.

### HasAllowNtlmFallback

`func (o *GSSAPIAuthenticatorInfo) HasAllowNtlmFallback() bool`

HasAllowNtlmFallback returns a boolean if a field has been set.

### GetConnectionServers

`func (o *GSSAPIAuthenticatorInfo) GetConnectionServers() []string`

GetConnectionServers returns the ConnectionServers field if non-nil, zero value otherwise.

### GetConnectionServersOk

`func (o *GSSAPIAuthenticatorInfo) GetConnectionServersOk() (*[]string, bool)`

GetConnectionServersOk returns a tuple with the ConnectionServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionServers

`func (o *GSSAPIAuthenticatorInfo) SetConnectionServers(v []string)`

SetConnectionServers sets ConnectionServers field to given value.

### HasConnectionServers

`func (o *GSSAPIAuthenticatorInfo) HasConnectionServers() bool`

HasConnectionServers returns a boolean if a field has been set.

### GetEnableLoginAsCurrentUser

`func (o *GSSAPIAuthenticatorInfo) GetEnableLoginAsCurrentUser() bool`

GetEnableLoginAsCurrentUser returns the EnableLoginAsCurrentUser field if non-nil, zero value otherwise.

### GetEnableLoginAsCurrentUserOk

`func (o *GSSAPIAuthenticatorInfo) GetEnableLoginAsCurrentUserOk() (*bool, bool)`

GetEnableLoginAsCurrentUserOk returns a tuple with the EnableLoginAsCurrentUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableLoginAsCurrentUser

`func (o *GSSAPIAuthenticatorInfo) SetEnableLoginAsCurrentUser(v bool)`

SetEnableLoginAsCurrentUser sets EnableLoginAsCurrentUser field to given value.

### HasEnableLoginAsCurrentUser

`func (o *GSSAPIAuthenticatorInfo) HasEnableLoginAsCurrentUser() bool`

HasEnableLoginAsCurrentUser returns a boolean if a field has been set.

### GetEnforceChannelBindings

`func (o *GSSAPIAuthenticatorInfo) GetEnforceChannelBindings() bool`

GetEnforceChannelBindings returns the EnforceChannelBindings field if non-nil, zero value otherwise.

### GetEnforceChannelBindingsOk

`func (o *GSSAPIAuthenticatorInfo) GetEnforceChannelBindingsOk() (*bool, bool)`

GetEnforceChannelBindingsOk returns a tuple with the EnforceChannelBindings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnforceChannelBindings

`func (o *GSSAPIAuthenticatorInfo) SetEnforceChannelBindings(v bool)`

SetEnforceChannelBindings sets EnforceChannelBindings field to given value.

### HasEnforceChannelBindings

`func (o *GSSAPIAuthenticatorInfo) HasEnforceChannelBindings() bool`

HasEnforceChannelBindings returns a boolean if a field has been set.

### GetId

`func (o *GSSAPIAuthenticatorInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GSSAPIAuthenticatorInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GSSAPIAuthenticatorInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GSSAPIAuthenticatorInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTriggerMode

`func (o *GSSAPIAuthenticatorInfo) GetTriggerMode() string`

GetTriggerMode returns the TriggerMode field if non-nil, zero value otherwise.

### GetTriggerModeOk

`func (o *GSSAPIAuthenticatorInfo) GetTriggerModeOk() (*string, bool)`

GetTriggerModeOk returns a tuple with the TriggerMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerMode

`func (o *GSSAPIAuthenticatorInfo) SetTriggerMode(v string)`

SetTriggerMode sets TriggerMode field to given value.

### HasTriggerMode

`func (o *GSSAPIAuthenticatorInfo) HasTriggerMode() bool`

HasTriggerMode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


