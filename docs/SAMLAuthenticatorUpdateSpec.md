# SAMLAuthenticatorUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdministratorUrl** | Pointer to **string** | The administrator URL for this SAML authenticator. This must specify a protocol (scheme) of http or https. | [optional] 
**Certificate** | Pointer to **string** | SAML Authenticator certificate. | [optional] 
**CertificateType** | Pointer to **string** | Type of Certificate. * PEM: PEM encoded certificate type * UNKNOWN: Unknown certificate type | [optional] 
**Description** | Pointer to **string** | The description of this SAML authenticator. | [optional] 
**Label** | **string** | The label for this SAML authenticator. It must be unique among all other SAML authenticators. | 
**MetadataUrl** | Pointer to **string** | The metadata URL that this SAML authenticator uses to fetch metadata. This must specify a protocol (scheme) of https. It must be unique among all other SAML authenticators. This is required if authenticator_type is set to DYNAMIC. | [optional] 
**PasswordMode** | Pointer to **string** | Indicates how password present in SAML assertion is handled if True SSO is triggered. This is required if the trigger_mode is set to ENABLE_ALWAYS or REQUIRE_ALWAYS. * REMOVE: Remove any passwords. * PASSTHRU: Pass through any passwords. * ERROR: Error if there is a password. | [optional] 
**StaticMetadata** | Pointer to **string** | The static metadata of a SAML authenticator which contains an entity id, signing keys, and encryption keys for processing SAML authentication. This property is required if authenticator_type is set to STATIC. | [optional] 
**TriggerMode** | **string** | Indicates how True SSO is triggered on sessions using this authenticator. * DISABLED: Do not use True SSO. * ENABLE_IF_NO_PASSWORD: If no password is supplied, use a valid (domain matching) connector if it exists. * REQUIRE_IF_NO_PASSWORD: If no password is supplied, use and require a valid (domain matching) connector. * ENABLE_ALWAYS: Regardless of a password, use a valid (domain matching) connector if it exists. * REQUIRE_ALWAYS: Regardless of a password, use and require a valid (domain matching) connector. | 

## Methods

### NewSAMLAuthenticatorUpdateSpec

`func NewSAMLAuthenticatorUpdateSpec(label string, triggerMode string, ) *SAMLAuthenticatorUpdateSpec`

NewSAMLAuthenticatorUpdateSpec instantiates a new SAMLAuthenticatorUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSAMLAuthenticatorUpdateSpecWithDefaults

`func NewSAMLAuthenticatorUpdateSpecWithDefaults() *SAMLAuthenticatorUpdateSpec`

NewSAMLAuthenticatorUpdateSpecWithDefaults instantiates a new SAMLAuthenticatorUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdministratorUrl

`func (o *SAMLAuthenticatorUpdateSpec) GetAdministratorUrl() string`

GetAdministratorUrl returns the AdministratorUrl field if non-nil, zero value otherwise.

### GetAdministratorUrlOk

`func (o *SAMLAuthenticatorUpdateSpec) GetAdministratorUrlOk() (*string, bool)`

GetAdministratorUrlOk returns a tuple with the AdministratorUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministratorUrl

`func (o *SAMLAuthenticatorUpdateSpec) SetAdministratorUrl(v string)`

SetAdministratorUrl sets AdministratorUrl field to given value.

### HasAdministratorUrl

`func (o *SAMLAuthenticatorUpdateSpec) HasAdministratorUrl() bool`

HasAdministratorUrl returns a boolean if a field has been set.

### GetCertificate

`func (o *SAMLAuthenticatorUpdateSpec) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *SAMLAuthenticatorUpdateSpec) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *SAMLAuthenticatorUpdateSpec) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *SAMLAuthenticatorUpdateSpec) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### GetCertificateType

`func (o *SAMLAuthenticatorUpdateSpec) GetCertificateType() string`

GetCertificateType returns the CertificateType field if non-nil, zero value otherwise.

### GetCertificateTypeOk

`func (o *SAMLAuthenticatorUpdateSpec) GetCertificateTypeOk() (*string, bool)`

GetCertificateTypeOk returns a tuple with the CertificateType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateType

`func (o *SAMLAuthenticatorUpdateSpec) SetCertificateType(v string)`

SetCertificateType sets CertificateType field to given value.

### HasCertificateType

`func (o *SAMLAuthenticatorUpdateSpec) HasCertificateType() bool`

HasCertificateType returns a boolean if a field has been set.

### GetDescription

`func (o *SAMLAuthenticatorUpdateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SAMLAuthenticatorUpdateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SAMLAuthenticatorUpdateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SAMLAuthenticatorUpdateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLabel

`func (o *SAMLAuthenticatorUpdateSpec) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *SAMLAuthenticatorUpdateSpec) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *SAMLAuthenticatorUpdateSpec) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetMetadataUrl

`func (o *SAMLAuthenticatorUpdateSpec) GetMetadataUrl() string`

GetMetadataUrl returns the MetadataUrl field if non-nil, zero value otherwise.

### GetMetadataUrlOk

`func (o *SAMLAuthenticatorUpdateSpec) GetMetadataUrlOk() (*string, bool)`

GetMetadataUrlOk returns a tuple with the MetadataUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataUrl

`func (o *SAMLAuthenticatorUpdateSpec) SetMetadataUrl(v string)`

SetMetadataUrl sets MetadataUrl field to given value.

### HasMetadataUrl

`func (o *SAMLAuthenticatorUpdateSpec) HasMetadataUrl() bool`

HasMetadataUrl returns a boolean if a field has been set.

### GetPasswordMode

`func (o *SAMLAuthenticatorUpdateSpec) GetPasswordMode() string`

GetPasswordMode returns the PasswordMode field if non-nil, zero value otherwise.

### GetPasswordModeOk

`func (o *SAMLAuthenticatorUpdateSpec) GetPasswordModeOk() (*string, bool)`

GetPasswordModeOk returns a tuple with the PasswordMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordMode

`func (o *SAMLAuthenticatorUpdateSpec) SetPasswordMode(v string)`

SetPasswordMode sets PasswordMode field to given value.

### HasPasswordMode

`func (o *SAMLAuthenticatorUpdateSpec) HasPasswordMode() bool`

HasPasswordMode returns a boolean if a field has been set.

### GetStaticMetadata

`func (o *SAMLAuthenticatorUpdateSpec) GetStaticMetadata() string`

GetStaticMetadata returns the StaticMetadata field if non-nil, zero value otherwise.

### GetStaticMetadataOk

`func (o *SAMLAuthenticatorUpdateSpec) GetStaticMetadataOk() (*string, bool)`

GetStaticMetadataOk returns a tuple with the StaticMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticMetadata

`func (o *SAMLAuthenticatorUpdateSpec) SetStaticMetadata(v string)`

SetStaticMetadata sets StaticMetadata field to given value.

### HasStaticMetadata

`func (o *SAMLAuthenticatorUpdateSpec) HasStaticMetadata() bool`

HasStaticMetadata returns a boolean if a field has been set.

### GetTriggerMode

`func (o *SAMLAuthenticatorUpdateSpec) GetTriggerMode() string`

GetTriggerMode returns the TriggerMode field if non-nil, zero value otherwise.

### GetTriggerModeOk

`func (o *SAMLAuthenticatorUpdateSpec) GetTriggerModeOk() (*string, bool)`

GetTriggerModeOk returns a tuple with the TriggerMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerMode

`func (o *SAMLAuthenticatorUpdateSpec) SetTriggerMode(v string)`

SetTriggerMode sets TriggerMode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


