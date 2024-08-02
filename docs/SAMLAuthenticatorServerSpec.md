# SAMLAuthenticatorServerSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdministratorUrl** | Pointer to **string** | The administrator URL for the SAML authenticator. | [optional] 
**MetadataUrl** | Pointer to **string** | The metadata URL of the SAML Authenticator. | [optional] 

## Methods

### NewSAMLAuthenticatorServerSpec

`func NewSAMLAuthenticatorServerSpec() *SAMLAuthenticatorServerSpec`

NewSAMLAuthenticatorServerSpec instantiates a new SAMLAuthenticatorServerSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSAMLAuthenticatorServerSpecWithDefaults

`func NewSAMLAuthenticatorServerSpecWithDefaults() *SAMLAuthenticatorServerSpec`

NewSAMLAuthenticatorServerSpecWithDefaults instantiates a new SAMLAuthenticatorServerSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdministratorUrl

`func (o *SAMLAuthenticatorServerSpec) GetAdministratorUrl() string`

GetAdministratorUrl returns the AdministratorUrl field if non-nil, zero value otherwise.

### GetAdministratorUrlOk

`func (o *SAMLAuthenticatorServerSpec) GetAdministratorUrlOk() (*string, bool)`

GetAdministratorUrlOk returns a tuple with the AdministratorUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministratorUrl

`func (o *SAMLAuthenticatorServerSpec) SetAdministratorUrl(v string)`

SetAdministratorUrl sets AdministratorUrl field to given value.

### HasAdministratorUrl

`func (o *SAMLAuthenticatorServerSpec) HasAdministratorUrl() bool`

HasAdministratorUrl returns a boolean if a field has been set.

### GetMetadataUrl

`func (o *SAMLAuthenticatorServerSpec) GetMetadataUrl() string`

GetMetadataUrl returns the MetadataUrl field if non-nil, zero value otherwise.

### GetMetadataUrlOk

`func (o *SAMLAuthenticatorServerSpec) GetMetadataUrlOk() (*string, bool)`

GetMetadataUrlOk returns a tuple with the MetadataUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataUrl

`func (o *SAMLAuthenticatorServerSpec) SetMetadataUrl(v string)`

SetMetadataUrl sets MetadataUrl field to given value.

### HasMetadataUrl

`func (o *SAMLAuthenticatorServerSpec) HasMetadataUrl() bool`

HasMetadataUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


