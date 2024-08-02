# JWTAuthenticatorUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The description of this JWT authenticator. | [optional] 
**Issuer** | **string** | The issuer of this JWT authenticator. The configured value is matched against the \&quot;iss\&quot; claim of the JWT. | 
**Name** | **string** | The name of the JWT authenticator. It must be unique among all other JWT authenticators. | 
**PublicKeys** | Pointer to **[]string** | The publicKeys as Json strings for this JWT authenticator. If \&quot;publicKeys\&quot; is blank, then \&quot;url\&quot; must not be blank. | [optional] 
**Url** | Pointer to **string** | The URL to fetch the public keys for this authenticator. If \&quot;url\&quot; is blank, then \&quot;publicKeys\&quot; must not be blank. | [optional] 

## Methods

### NewJWTAuthenticatorUpdateSpec

`func NewJWTAuthenticatorUpdateSpec(issuer string, name string, ) *JWTAuthenticatorUpdateSpec`

NewJWTAuthenticatorUpdateSpec instantiates a new JWTAuthenticatorUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJWTAuthenticatorUpdateSpecWithDefaults

`func NewJWTAuthenticatorUpdateSpecWithDefaults() *JWTAuthenticatorUpdateSpec`

NewJWTAuthenticatorUpdateSpecWithDefaults instantiates a new JWTAuthenticatorUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *JWTAuthenticatorUpdateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JWTAuthenticatorUpdateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JWTAuthenticatorUpdateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JWTAuthenticatorUpdateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIssuer

`func (o *JWTAuthenticatorUpdateSpec) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *JWTAuthenticatorUpdateSpec) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *JWTAuthenticatorUpdateSpec) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.


### GetName

`func (o *JWTAuthenticatorUpdateSpec) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *JWTAuthenticatorUpdateSpec) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *JWTAuthenticatorUpdateSpec) SetName(v string)`

SetName sets Name field to given value.


### GetPublicKeys

`func (o *JWTAuthenticatorUpdateSpec) GetPublicKeys() []string`

GetPublicKeys returns the PublicKeys field if non-nil, zero value otherwise.

### GetPublicKeysOk

`func (o *JWTAuthenticatorUpdateSpec) GetPublicKeysOk() (*[]string, bool)`

GetPublicKeysOk returns a tuple with the PublicKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicKeys

`func (o *JWTAuthenticatorUpdateSpec) SetPublicKeys(v []string)`

SetPublicKeys sets PublicKeys field to given value.

### HasPublicKeys

`func (o *JWTAuthenticatorUpdateSpec) HasPublicKeys() bool`

HasPublicKeys returns a boolean if a field has been set.

### GetUrl

`func (o *JWTAuthenticatorUpdateSpec) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *JWTAuthenticatorUpdateSpec) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *JWTAuthenticatorUpdateSpec) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *JWTAuthenticatorUpdateSpec) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


