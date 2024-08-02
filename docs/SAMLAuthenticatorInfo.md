# SAMLAuthenticatorInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdministratorUrl** | Pointer to **string** | The administrator URL for the SAML authenticator. | [optional] 
**AuthenticatorType** | Pointer to **string** | The type of SAML authenticator. * STATIC: Static SAML Authenticator, which contains SAML metadata. * DYNAMIC: Dynamic SAML Authenticator fetches metadata dynamically using a provided URL. | [optional] 
**Certificate** | Pointer to **string** | SAML Authenticator certificate. | [optional] 
**CertificateType** | Pointer to **string** | Type of Certificate. * PEM: PEM encoded certificate type * UNKNOWN: Unknown certificate type | [optional] 
**Description** | Pointer to **string** | The description of this SAML authenticator. | [optional] 
**Id** | Pointer to **string** | Unique ID representing this SAML Authenticator. | [optional] 
**Label** | Pointer to **string** | The label for this SAML authenticator. | [optional] 
**MetadataUrl** | Pointer to **string** | The metadata URL of the SAML Authenticator. | [optional] 
**PasswordMode** | Pointer to **string** | Indicates how password present in SAML assertion is handled if True SSO is triggered. * REMOVE: Remove any passwords. * PASSTHRU: Pass through any passwords. * ERROR: Error if there is a password. | [optional] 
**StaticMetadata** | Pointer to **string** | The static metadata of a SAML authenticator which contains an entity id, signing keys, and encryption keys for processing SAML authentication. | [optional] 
**TriggerMode** | Pointer to **string** | Indicates how True SSO is triggered on sessions using this authenticator. * DISABLED: Do not use True SSO. * ENABLE_IF_NO_PASSWORD: If no password is supplied, use a valid (domain matching) connector if it exists. * REQUIRE_IF_NO_PASSWORD: If no password is supplied, use and require a valid (domain matching) connector. * ENABLE_ALWAYS: Regardless of a password, use a valid (domain matching) connector if it exists. * REQUIRE_ALWAYS: Regardless of a password, use and require a valid (domain matching) connector. | [optional] 

## Methods

### NewSAMLAuthenticatorInfo

`func NewSAMLAuthenticatorInfo() *SAMLAuthenticatorInfo`

NewSAMLAuthenticatorInfo instantiates a new SAMLAuthenticatorInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSAMLAuthenticatorInfoWithDefaults

`func NewSAMLAuthenticatorInfoWithDefaults() *SAMLAuthenticatorInfo`

NewSAMLAuthenticatorInfoWithDefaults instantiates a new SAMLAuthenticatorInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdministratorUrl

`func (o *SAMLAuthenticatorInfo) GetAdministratorUrl() string`

GetAdministratorUrl returns the AdministratorUrl field if non-nil, zero value otherwise.

### GetAdministratorUrlOk

`func (o *SAMLAuthenticatorInfo) GetAdministratorUrlOk() (*string, bool)`

GetAdministratorUrlOk returns a tuple with the AdministratorUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministratorUrl

`func (o *SAMLAuthenticatorInfo) SetAdministratorUrl(v string)`

SetAdministratorUrl sets AdministratorUrl field to given value.

### HasAdministratorUrl

`func (o *SAMLAuthenticatorInfo) HasAdministratorUrl() bool`

HasAdministratorUrl returns a boolean if a field has been set.

### GetAuthenticatorType

`func (o *SAMLAuthenticatorInfo) GetAuthenticatorType() string`

GetAuthenticatorType returns the AuthenticatorType field if non-nil, zero value otherwise.

### GetAuthenticatorTypeOk

`func (o *SAMLAuthenticatorInfo) GetAuthenticatorTypeOk() (*string, bool)`

GetAuthenticatorTypeOk returns a tuple with the AuthenticatorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticatorType

`func (o *SAMLAuthenticatorInfo) SetAuthenticatorType(v string)`

SetAuthenticatorType sets AuthenticatorType field to given value.

### HasAuthenticatorType

`func (o *SAMLAuthenticatorInfo) HasAuthenticatorType() bool`

HasAuthenticatorType returns a boolean if a field has been set.

### GetCertificate

`func (o *SAMLAuthenticatorInfo) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *SAMLAuthenticatorInfo) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *SAMLAuthenticatorInfo) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *SAMLAuthenticatorInfo) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### GetCertificateType

`func (o *SAMLAuthenticatorInfo) GetCertificateType() string`

GetCertificateType returns the CertificateType field if non-nil, zero value otherwise.

### GetCertificateTypeOk

`func (o *SAMLAuthenticatorInfo) GetCertificateTypeOk() (*string, bool)`

GetCertificateTypeOk returns a tuple with the CertificateType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateType

`func (o *SAMLAuthenticatorInfo) SetCertificateType(v string)`

SetCertificateType sets CertificateType field to given value.

### HasCertificateType

`func (o *SAMLAuthenticatorInfo) HasCertificateType() bool`

HasCertificateType returns a boolean if a field has been set.

### GetDescription

`func (o *SAMLAuthenticatorInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SAMLAuthenticatorInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SAMLAuthenticatorInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SAMLAuthenticatorInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *SAMLAuthenticatorInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SAMLAuthenticatorInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SAMLAuthenticatorInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SAMLAuthenticatorInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLabel

`func (o *SAMLAuthenticatorInfo) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *SAMLAuthenticatorInfo) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *SAMLAuthenticatorInfo) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *SAMLAuthenticatorInfo) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetMetadataUrl

`func (o *SAMLAuthenticatorInfo) GetMetadataUrl() string`

GetMetadataUrl returns the MetadataUrl field if non-nil, zero value otherwise.

### GetMetadataUrlOk

`func (o *SAMLAuthenticatorInfo) GetMetadataUrlOk() (*string, bool)`

GetMetadataUrlOk returns a tuple with the MetadataUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataUrl

`func (o *SAMLAuthenticatorInfo) SetMetadataUrl(v string)`

SetMetadataUrl sets MetadataUrl field to given value.

### HasMetadataUrl

`func (o *SAMLAuthenticatorInfo) HasMetadataUrl() bool`

HasMetadataUrl returns a boolean if a field has been set.

### GetPasswordMode

`func (o *SAMLAuthenticatorInfo) GetPasswordMode() string`

GetPasswordMode returns the PasswordMode field if non-nil, zero value otherwise.

### GetPasswordModeOk

`func (o *SAMLAuthenticatorInfo) GetPasswordModeOk() (*string, bool)`

GetPasswordModeOk returns a tuple with the PasswordMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordMode

`func (o *SAMLAuthenticatorInfo) SetPasswordMode(v string)`

SetPasswordMode sets PasswordMode field to given value.

### HasPasswordMode

`func (o *SAMLAuthenticatorInfo) HasPasswordMode() bool`

HasPasswordMode returns a boolean if a field has been set.

### GetStaticMetadata

`func (o *SAMLAuthenticatorInfo) GetStaticMetadata() string`

GetStaticMetadata returns the StaticMetadata field if non-nil, zero value otherwise.

### GetStaticMetadataOk

`func (o *SAMLAuthenticatorInfo) GetStaticMetadataOk() (*string, bool)`

GetStaticMetadataOk returns a tuple with the StaticMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaticMetadata

`func (o *SAMLAuthenticatorInfo) SetStaticMetadata(v string)`

SetStaticMetadata sets StaticMetadata field to given value.

### HasStaticMetadata

`func (o *SAMLAuthenticatorInfo) HasStaticMetadata() bool`

HasStaticMetadata returns a boolean if a field has been set.

### GetTriggerMode

`func (o *SAMLAuthenticatorInfo) GetTriggerMode() string`

GetTriggerMode returns the TriggerMode field if non-nil, zero value otherwise.

### GetTriggerModeOk

`func (o *SAMLAuthenticatorInfo) GetTriggerModeOk() (*string, bool)`

GetTriggerModeOk returns a tuple with the TriggerMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerMode

`func (o *SAMLAuthenticatorInfo) SetTriggerMode(v string)`

SetTriggerMode sets TriggerMode field to given value.

### HasTriggerMode

`func (o *SAMLAuthenticatorInfo) HasTriggerMode() bool`

HasTriggerMode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


