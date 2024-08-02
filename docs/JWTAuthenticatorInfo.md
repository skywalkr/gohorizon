# JWTAuthenticatorInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | The description of this JWT authenticator. | [optional] 
**Id** | Pointer to **string** | Unique ID of this JWT authenticator. | [optional] 
**Issuer** | Pointer to **string** | The issuer of this JWT authenticator. The configured value is matched against the \&quot;iss\&quot; claim of the JWT. | [optional] 
**Name** | Pointer to **string** | The name of this JWT authenticator. | [optional] 
**PublicKeys** | Pointer to **[]string** | The stored public keys for this JWT authenticator. | [optional] 
**Url** | Pointer to **string** | The URL to fetch the public keys for this authenticator. | [optional] 

## Methods

### NewJWTAuthenticatorInfo

`func NewJWTAuthenticatorInfo() *JWTAuthenticatorInfo`

NewJWTAuthenticatorInfo instantiates a new JWTAuthenticatorInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJWTAuthenticatorInfoWithDefaults

`func NewJWTAuthenticatorInfoWithDefaults() *JWTAuthenticatorInfo`

NewJWTAuthenticatorInfoWithDefaults instantiates a new JWTAuthenticatorInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *JWTAuthenticatorInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *JWTAuthenticatorInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *JWTAuthenticatorInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *JWTAuthenticatorInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *JWTAuthenticatorInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *JWTAuthenticatorInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *JWTAuthenticatorInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *JWTAuthenticatorInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIssuer

`func (o *JWTAuthenticatorInfo) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *JWTAuthenticatorInfo) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *JWTAuthenticatorInfo) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.

### HasIssuer

`func (o *JWTAuthenticatorInfo) HasIssuer() bool`

HasIssuer returns a boolean if a field has been set.

### GetName

`func (o *JWTAuthenticatorInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *JWTAuthenticatorInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *JWTAuthenticatorInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *JWTAuthenticatorInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPublicKeys

`func (o *JWTAuthenticatorInfo) GetPublicKeys() []string`

GetPublicKeys returns the PublicKeys field if non-nil, zero value otherwise.

### GetPublicKeysOk

`func (o *JWTAuthenticatorInfo) GetPublicKeysOk() (*[]string, bool)`

GetPublicKeysOk returns a tuple with the PublicKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicKeys

`func (o *JWTAuthenticatorInfo) SetPublicKeys(v []string)`

SetPublicKeys sets PublicKeys field to given value.

### HasPublicKeys

`func (o *JWTAuthenticatorInfo) HasPublicKeys() bool`

HasPublicKeys returns a boolean if a field has been set.

### GetUrl

`func (o *JWTAuthenticatorInfo) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *JWTAuthenticatorInfo) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *JWTAuthenticatorInfo) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *JWTAuthenticatorInfo) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


