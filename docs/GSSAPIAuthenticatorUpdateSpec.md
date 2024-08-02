# GSSAPIAuthenticatorUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowLegacyClients** | **bool** | Indicates whether the legacy Horizon clients will be allowed to use login as current user. | 
**AllowNtlmFallback** | **bool** | Indicates whether NTLM is allowed for GSSAPI authentication. When the client does not have access to the domain controllers in the hosted environment kerberos authentication fails, clients can fall back to NTLM authentication if allowNTLMFallback is set to true. | 
**EnableLoginAsCurrentUser** | **bool** | Indicates whether the login as current user is enabled or not. | 
**EnforceChannelBindings** | **bool** | Indicates whether channel bindings is supported or not. | 
**TriggerMode** | **string** | Indicates True SSO trigger mode on sessions using this authenticator. * DISABLED: Do not use True SSO. * OPTIONAL: If no SSO credentials are provided then use True SSO otherwise use the supplied SSO credentials. * ENABLED: Always use True SSO even if client supplied SSO credentials. | 

## Methods

### NewGSSAPIAuthenticatorUpdateSpec

`func NewGSSAPIAuthenticatorUpdateSpec(allowLegacyClients bool, allowNtlmFallback bool, enableLoginAsCurrentUser bool, enforceChannelBindings bool, triggerMode string, ) *GSSAPIAuthenticatorUpdateSpec`

NewGSSAPIAuthenticatorUpdateSpec instantiates a new GSSAPIAuthenticatorUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGSSAPIAuthenticatorUpdateSpecWithDefaults

`func NewGSSAPIAuthenticatorUpdateSpecWithDefaults() *GSSAPIAuthenticatorUpdateSpec`

NewGSSAPIAuthenticatorUpdateSpecWithDefaults instantiates a new GSSAPIAuthenticatorUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowLegacyClients

`func (o *GSSAPIAuthenticatorUpdateSpec) GetAllowLegacyClients() bool`

GetAllowLegacyClients returns the AllowLegacyClients field if non-nil, zero value otherwise.

### GetAllowLegacyClientsOk

`func (o *GSSAPIAuthenticatorUpdateSpec) GetAllowLegacyClientsOk() (*bool, bool)`

GetAllowLegacyClientsOk returns a tuple with the AllowLegacyClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLegacyClients

`func (o *GSSAPIAuthenticatorUpdateSpec) SetAllowLegacyClients(v bool)`

SetAllowLegacyClients sets AllowLegacyClients field to given value.


### GetAllowNtlmFallback

`func (o *GSSAPIAuthenticatorUpdateSpec) GetAllowNtlmFallback() bool`

GetAllowNtlmFallback returns the AllowNtlmFallback field if non-nil, zero value otherwise.

### GetAllowNtlmFallbackOk

`func (o *GSSAPIAuthenticatorUpdateSpec) GetAllowNtlmFallbackOk() (*bool, bool)`

GetAllowNtlmFallbackOk returns a tuple with the AllowNtlmFallback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowNtlmFallback

`func (o *GSSAPIAuthenticatorUpdateSpec) SetAllowNtlmFallback(v bool)`

SetAllowNtlmFallback sets AllowNtlmFallback field to given value.


### GetEnableLoginAsCurrentUser

`func (o *GSSAPIAuthenticatorUpdateSpec) GetEnableLoginAsCurrentUser() bool`

GetEnableLoginAsCurrentUser returns the EnableLoginAsCurrentUser field if non-nil, zero value otherwise.

### GetEnableLoginAsCurrentUserOk

`func (o *GSSAPIAuthenticatorUpdateSpec) GetEnableLoginAsCurrentUserOk() (*bool, bool)`

GetEnableLoginAsCurrentUserOk returns a tuple with the EnableLoginAsCurrentUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableLoginAsCurrentUser

`func (o *GSSAPIAuthenticatorUpdateSpec) SetEnableLoginAsCurrentUser(v bool)`

SetEnableLoginAsCurrentUser sets EnableLoginAsCurrentUser field to given value.


### GetEnforceChannelBindings

`func (o *GSSAPIAuthenticatorUpdateSpec) GetEnforceChannelBindings() bool`

GetEnforceChannelBindings returns the EnforceChannelBindings field if non-nil, zero value otherwise.

### GetEnforceChannelBindingsOk

`func (o *GSSAPIAuthenticatorUpdateSpec) GetEnforceChannelBindingsOk() (*bool, bool)`

GetEnforceChannelBindingsOk returns a tuple with the EnforceChannelBindings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnforceChannelBindings

`func (o *GSSAPIAuthenticatorUpdateSpec) SetEnforceChannelBindings(v bool)`

SetEnforceChannelBindings sets EnforceChannelBindings field to given value.


### GetTriggerMode

`func (o *GSSAPIAuthenticatorUpdateSpec) GetTriggerMode() string`

GetTriggerMode returns the TriggerMode field if non-nil, zero value otherwise.

### GetTriggerModeOk

`func (o *GSSAPIAuthenticatorUpdateSpec) GetTriggerModeOk() (*string, bool)`

GetTriggerModeOk returns a tuple with the TriggerMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerMode

`func (o *GSSAPIAuthenticatorUpdateSpec) SetTriggerMode(v string)`

SetTriggerMode sets TriggerMode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


