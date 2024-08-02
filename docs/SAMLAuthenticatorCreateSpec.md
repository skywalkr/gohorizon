# SAMLAuthenticatorCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdministratorUrl** | Pointer to **string** | The administrator URL for this SAML authenticator. This must specify a protocol (scheme) of http or https. | [optional] 
**AuthenticatorType** | **string** | The type of SAML authenticator. * STATIC: Static SAML Authenticator, which contains SAML metadata. * DYNAMIC: Dynamic SAML Authenticator fetches metadata dynamically using a provided URL. | 
**Certificate** | Pointer to **string** | SAML Authenticator certificate. | [optional] 
**CertificateType** | Pointer to **string** | Type of Certificate. * PEM: PEM encoded certificate type * UNKNOWN: Unknown certificate type | [optional] 
**ConnectionServerIds** | Pointer to **[]string** | The list of Connection Servers for which this SAML authenticator is enabled. | [optional] 
**Description** | Pointer to **string** | The description of this SAML authenticator. | [optional] 
**Label** | **string** | The label for this SAML authenticator. It must be unique among all other SAML authenticators. | 
**MetadataUrl** | Pointer to **string** | The metadata URL that this SAML authenticator uses to fetch metadata. This must specify a protocol (scheme) of https. It must be unique among all other SAML authenticators. This is required if authenticator_type is set to DYNAMIC. | [optional] 
**PasswordMode** | Pointer to **string** | Indicates how password present in SAML assertion is handled if True SSO is triggered. This is required if the trigger_mode is set to ENABLE_ALWAYS or REQUIRE_ALWAYS. * REMOVE: Remove any passwords. * PASSTHRU: Pass through any passwords. * ERROR: Error if there is a password. | [optional] 
**StaticMetadata** | Pointer to **string** | The static metadata of a SAML authenticator which contains an entity id, signing keys, and encryption keys for processing SAML authentication. This property is required if authenticator_type is set to STATIC. | [optional] 
**TriggerMode** | Pointer to **string** | Indicates how True SSO is triggered on sessions using this authenticator. * DISABLED: Do not use True SSO. * ENABLE_IF_NO_PASSWORD: If no password is supplied, use a valid (domain matching) connector if it exists. * REQUIRE_IF_NO_PASSWORD: If no password is supplied, use and require a valid (domain matching) connector. * ENABLE_ALWAYS: Regardless of a password, use a valid (domain matching) connector if it exists. * REQUIRE_ALWAYS: Regardless of a password, use and require a valid (domain matching) connector. | [optional] 

## Methods

### NewSAMLAuthenticatorCreateSpec

`func NewSAMLAuthenticatorCreateSpec(authenticatorType string, label string, ) *SAMLAuthenticatorCreateSpec`

NewSAMLAuthenticatorCreateSpec instantiates a new SAMLAuthenticatorCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSAMLAuthenticatorCreateSpecWithDefaults

`func NewSAMLAuthenticatorCreateSpecWithDefaults() *SAMLAuthenticatorCreateSpec`

NewSAMLAuthenticatorCreateSpecWithDefaults instantiates a new SAMLAuthenticatorCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdministratorUrl

`func (o *SAMLAuthenticatorCreateSpec) GetAdministratorUrl() string`

GetAdministratorUrl returns the AdministratorUrl field if non-nil, zero value otherwise.

### GetAdministratorUrlOk

`func (o *SAMLAuthenticatorCreateSpec) GetAdministratorUrlOk() (*string, bool)`

GetAdministratorUrlOk returns a tuple with the AdministratorUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministratorUrl

`func (o *SAMLAuthenticatorCreateSpec) SetAdministratorUrl(v string)`

SetAdministratorUrl sets AdministratorUrl field to given value.

### HasAdministratorUrl

`func (o *SAMLAuthenticatorCreateSpec) HasAdministratorUrl() bool`

HasAdministratorUrl returns a boolean if a field has been set.

### GetAuthenticatorType

`func (o *SAMLAuthenticatorCreateSpec) GetAuthenticatorType() string`

GetAuthenticatorType returns the AuthenticatorType field if non-nil, zero value otherwise.

### GetAuthenticatorTypeOk

`func (o *SAMLAuthenticatorCreateSpec) GetAuthenticatorTypeOk() (*string, bool)`

GetAuthenticatorTypeOk returns a tuple with the AuthenticatorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticatorType

`func (o *SAMLAuthenticatorCreateSpec) SetAuthenticatorType(v string)`

SetAuthenticatorType sets AuthenticatorType field to given value.


### GetCertificate

`func (o *SAMLAuthenticatorCreateSpec) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *SAMLAuthenticatorCreateSpec) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *SAMLAuthenticatorCreateSpec) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *SAMLAuthenticatorCreateSpec) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### GetCertificateType

`func (o *SAMLAuthenticatorCreateSpec) GetCertificateType() string`

GetCertificateType returns the CertificateType field if non-nil, zero value otherwise.

### GetCertificateTypeOk

`func (o *SAMLAuthenticatorCreateSpec) GetCertificateTypeOk() (*string, bool)`

GetCertificateTypeOk returns a tuple with the CertificateType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateType

`func (o *SAMLAuthenticatorCreateSpec) SetCertificateType(v string)`

SetCertificateType sets CertificateType field to given value.

### HasCertificateType

`func (o *SAMLAuthenticatorCreateSpec) HasCertificateType() bool`

HasCertificateType returns a boolean if a field has been set.

### GetConnectionServerIds

`func (o *SAMLAuthenticatorCreateSpec) GetConnectionServerIds() []string`

GetConnectionServerIds returns the ConnectionServerIds field if non-nil, zero value otherwise.

### GetConnectionServerIdsOk

`func (o *SAMLAuthenticatorCreateSpec) GetConnectionServerIdsOk() (*[]string, bool)`

GetConnectionServerIdsOk returns a tuple with the ConnectionServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionServerIds

`func (o *SAMLAuthenticatorCreateSpec) SetConnectionServerIds(v []string)`

SetConnectionServerIds sets ConnectionServerIds field to given value.

### HasConnectionServerIds

`func (o *SAMLAuthenticatorCreateSpec) HasConnectionServerIds() bool`

HasConnectionServerIds returns a boolean if a field has been set.

### GetDescription

`func (o *SAMLAuthenticatorCreateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SAMLAuthenticatorCreateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SAMLAuthenticatorCreateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SAMLAuthenticatorCreateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLabel

`func (o *SAMLAuthenticatorCreateSpec) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *SAMLAuthenticatorCreateSpec) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *SAMLAuthenticatorCreateSpec) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetMetadataUrl

`func (o *SAMLAuthenticatorCreateSpec) GetMetadataUrl() string`

GetMetadataUrl returns the MetadataUrl field if non-nil, zero value otherwise.

### GetMetadataUrlOk

`func (o *SAMLAuthenticatorCreateSpec) GetMetadataUrlOk() (*string, bool)`

GetMetadataUrlOk returns a tuple with the MetadataUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataUrl

`func (o *SAMLAuthenticatorCreateSpec) SetMetadataUrl(v string)`

SetMetadataUrl sets MetadataUrl field to given value.

### HasMetadataUrl

`func (o *SAMLAuthenticatorCreateSpec) HasMetadataUrl() bool`

HasMetadataUrl returns a boolean if a field has been set.

### GetPasswordMode

`func (o *SAMLAuthenticatorCreateSpec) GetPasswordMode() string`

GetPasswordMode returns the PasswordMode field if non-nil, zero value otherwise.

### GetPasswordModeOk

`func (o *SAMLAuthenticatorCreateSpec) GetPasswordModeOk() (*string, bool)`

GetPasswordModeOk returns a tuple with the PasswordMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordMode

`func (o *SAMLAuthenticatorCreateSpec) SetPasswordMode(v string)`

SetPasswordMode sets PasswordMode field to given value.

### HasPasswordMode

`func (o *SAMLAuthenticatorCreateSpec) HasPasswordMode() bool`

HasPasswordMode returns a boolean if a field has been set.

### GetStaticMetadata

`func (o *SAMLAuthenticatorCreateSpec) GetStaticMetadata() string`

GetStaticMetadata returns the StaticMetadata field if non-nil, zero value otherwise.

### GetStaticMetadataOk

`func (o *SAMLAuthenticatorCreateSpec) GetStaticMetadataOk() (*string, bool)`

GetStaticMetadataOk returns a tuple with the StaticMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticMetadata

`func (o *SAMLAuthenticatorCreateSpec) SetStaticMetadata(v string)`

SetStaticMetadata sets StaticMetadata field to given value.

### HasStaticMetadata

`func (o *SAMLAuthenticatorCreateSpec) HasStaticMetadata() bool`

HasStaticMetadata returns a boolean if a field has been set.

### GetTriggerMode

`func (o *SAMLAuthenticatorCreateSpec) GetTriggerMode() string`

GetTriggerMode returns the TriggerMode field if non-nil, zero value otherwise.

### GetTriggerModeOk

`func (o *SAMLAuthenticatorCreateSpec) GetTriggerModeOk() (*string, bool)`

GetTriggerModeOk returns a tuple with the TriggerMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerMode

`func (o *SAMLAuthenticatorCreateSpec) SetTriggerMode(v string)`

SetTriggerMode sets TriggerMode field to given value.

### HasTriggerMode

`func (o *SAMLAuthenticatorCreateSpec) HasTriggerMode() bool`

HasTriggerMode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


