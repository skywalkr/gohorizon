# JWTAuthenticatorCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The description of this JWT authenticator. | [optional] 
**Issuer** | **string** | The issuer of this JWT authenticator. The configured value is matched against the \&quot;iss\&quot; claim of the JWT. | 
**Name** | **string** | The name of the JWT authenticator. It must be unique among all other JWT authenticators. | 
**PublicKeys** | Pointer to **[]string** | The publicKeys as Json strings for this JWT authenticator. If \&quot;publicKeys\&quot; is blank, then \&quot;url\&quot; must not be blank. | [optional] 
**Url** | Pointer to **string** | The URL to fetch the public keys for this authenticator. If \&quot;url\&quot; is blank, then \&quot;publicKeys\&quot; must not be blank. | [optional] 

## Methods

### NewJWTAuthenticatorCreateSpec

`func NewJWTAuthenticatorCreateSpec(issuer string, name string, ) *JWTAuthenticatorCreateSpec`

NewJWTAuthenticatorCreateSpec instantiates a new JWTAuthenticatorCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJWTAuthenticatorCreateSpecWithDefaults

`func NewJWTAuthenticatorCreateSpecWithDefaults() *JWTAuthenticatorCreateSpec`

NewJWTAuthenticatorCreateSpecWithDefaults instantiates a new JWTAuthenticatorCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *JWTAuthenticatorCreateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JWTAuthenticatorCreateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JWTAuthenticatorCreateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JWTAuthenticatorCreateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIssuer

`func (o *JWTAuthenticatorCreateSpec) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *JWTAuthenticatorCreateSpec) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *JWTAuthenticatorCreateSpec) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.


### GetName

`func (o *JWTAuthenticatorCreateSpec) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *JWTAuthenticatorCreateSpec) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *JWTAuthenticatorCreateSpec) SetName(v string)`

SetName sets Name field to given value.


### GetPublicKeys

`func (o *JWTAuthenticatorCreateSpec) GetPublicKeys() []string`

GetPublicKeys returns the PublicKeys field if non-nil, zero value otherwise.

### GetPublicKeysOk

`func (o *JWTAuthenticatorCreateSpec) GetPublicKeysOk() (*[]string, bool)`

GetPublicKeysOk returns a tuple with the PublicKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicKeys

`func (o *JWTAuthenticatorCreateSpec) SetPublicKeys(v []string)`

SetPublicKeys sets PublicKeys field to given value.

### HasPublicKeys

`func (o *JWTAuthenticatorCreateSpec) HasPublicKeys() bool`

HasPublicKeys returns a boolean if a field has been set.

### GetUrl

`func (o *JWTAuthenticatorCreateSpec) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *JWTAuthenticatorCreateSpec) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *JWTAuthenticatorCreateSpec) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *JWTAuthenticatorCreateSpec) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


