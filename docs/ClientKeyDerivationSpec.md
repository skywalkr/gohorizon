# ClientKeyDerivationSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Identifier as Base64 encoded binary data. | 
**Nonce** | **string** | Nonce as Base64 encoded binary data. | 
**PublicKey** | **string** | Diffie Hellman public key as Base64 encoded binary data. | 
**SupportedSchemes** | **[]string** | List of client supported schemes for key derivation. | 

## Methods

### NewClientKeyDerivationSpec

`func NewClientKeyDerivationSpec(identifier string, nonce string, publicKey string, supportedSchemes []string, ) *ClientKeyDerivationSpec`

NewClientKeyDerivationSpec instantiates a new ClientKeyDerivationSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientKeyDerivationSpecWithDefaults

`func NewClientKeyDerivationSpecWithDefaults() *ClientKeyDerivationSpec`

NewClientKeyDerivationSpecWithDefaults instantiates a new ClientKeyDerivationSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *ClientKeyDerivationSpec) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ClientKeyDerivationSpec) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ClientKeyDerivationSpec) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetNonce

`func (o *ClientKeyDerivationSpec) GetNonce() string`

GetNonce returns the Nonce field if non-nil, zero value otherwise.

### GetNonceOk

`func (o *ClientKeyDerivationSpec) GetNonceOk() (*string, bool)`

GetNonceOk returns a tuple with the Nonce field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonce

`func (o *ClientKeyDerivationSpec) SetNonce(v string)`

SetNonce sets Nonce field to given value.


### GetPublicKey

`func (o *ClientKeyDerivationSpec) GetPublicKey() string`

GetPublicKey returns the PublicKey field if non-nil, zero value otherwise.

### GetPublicKeyOk

`func (o *ClientKeyDerivationSpec) GetPublicKeyOk() (*string, bool)`

GetPublicKeyOk returns a tuple with the PublicKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicKey

`func (o *ClientKeyDerivationSpec) SetPublicKey(v string)`

SetPublicKey sets PublicKey field to given value.


### GetSupportedSchemes

`func (o *ClientKeyDerivationSpec) GetSupportedSchemes() []string`

GetSupportedSchemes returns the SupportedSchemes field if non-nil, zero value otherwise.

### GetSupportedSchemesOk

`func (o *ClientKeyDerivationSpec) GetSupportedSchemesOk() (*[]string, bool)`

GetSupportedSchemesOk returns a tuple with the SupportedSchemes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedSchemes

`func (o *ClientKeyDerivationSpec) SetSupportedSchemes(v []string)`

SetSupportedSchemes sets SupportedSchemes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


