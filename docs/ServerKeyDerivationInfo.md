# ServerKeyDerivationInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientReferenceId** | Pointer to **string** | Client reference identifier which is required to be passed as query param to login api, to enable decryption of encrypted sensitive information. | [optional] 
**Identifier** | Pointer to **string** | Identifier as Base64 encoded binary data. | [optional] 
**Proof** | Pointer to **string** | Proof as Base64 encoded binary data. | [optional] 
**PublicKey** | Pointer to **string** | Diffie Hellman public key as Base64 encoded binary data. | [optional] 
**Scheme** | Pointer to **string** | Selected scheme for key derivation. * SCHEME_AES1: Diffie Hellman algo used by low power clients. * SCHEME_AES2: Diffie Hellman algo used by high power clients. * SCHEME_EC_AES1: Elliptic-curve Diffie Hellman algo used by low power clients. * SCHEME_EC_AES2: Elliptic-curve Diffie Hellman algo used by high power clients. | [optional] 

## Methods

### NewServerKeyDerivationInfo

`func NewServerKeyDerivationInfo() *ServerKeyDerivationInfo`

NewServerKeyDerivationInfo instantiates a new ServerKeyDerivationInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerKeyDerivationInfoWithDefaults

`func NewServerKeyDerivationInfoWithDefaults() *ServerKeyDerivationInfo`

NewServerKeyDerivationInfoWithDefaults instantiates a new ServerKeyDerivationInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientReferenceId

`func (o *ServerKeyDerivationInfo) GetClientReferenceId() string`

GetClientReferenceId returns the ClientReferenceId field if non-nil, zero value otherwise.

### GetClientReferenceIdOk

`func (o *ServerKeyDerivationInfo) GetClientReferenceIdOk() (*string, bool)`

GetClientReferenceIdOk returns a tuple with the ClientReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReferenceId

`func (o *ServerKeyDerivationInfo) SetClientReferenceId(v string)`

SetClientReferenceId sets ClientReferenceId field to given value.

### HasClientReferenceId

`func (o *ServerKeyDerivationInfo) HasClientReferenceId() bool`

HasClientReferenceId returns a boolean if a field has been set.

### GetIdentifier

`func (o *ServerKeyDerivationInfo) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ServerKeyDerivationInfo) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ServerKeyDerivationInfo) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *ServerKeyDerivationInfo) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### GetProof

`func (o *ServerKeyDerivationInfo) GetProof() string`

GetProof returns the Proof field if non-nil, zero value otherwise.

### GetProofOk

`func (o *ServerKeyDerivationInfo) GetProofOk() (*string, bool)`

GetProofOk returns a tuple with the Proof field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProof

`func (o *ServerKeyDerivationInfo) SetProof(v string)`

SetProof sets Proof field to given value.

### HasProof

`func (o *ServerKeyDerivationInfo) HasProof() bool`

HasProof returns a boolean if a field has been set.

### GetPublicKey

`func (o *ServerKeyDerivationInfo) GetPublicKey() string`

GetPublicKey returns the PublicKey field if non-nil, zero value otherwise.

### GetPublicKeyOk

`func (o *ServerKeyDerivationInfo) GetPublicKeyOk() (*string, bool)`

GetPublicKeyOk returns a tuple with the PublicKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicKey

`func (o *ServerKeyDerivationInfo) SetPublicKey(v string)`

SetPublicKey sets PublicKey field to given value.

### HasPublicKey

`func (o *ServerKeyDerivationInfo) HasPublicKey() bool`

HasPublicKey returns a boolean if a field has been set.

### GetScheme

`func (o *ServerKeyDerivationInfo) GetScheme() string`

GetScheme returns the Scheme field if non-nil, zero value otherwise.

### GetSchemeOk

`func (o *ServerKeyDerivationInfo) GetSchemeOk() (*string, bool)`

GetSchemeOk returns a tuple with the Scheme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheme

`func (o *ServerKeyDerivationInfo) SetScheme(v string)`

SetScheme sets Scheme field to given value.

### HasScheme

`func (o *ServerKeyDerivationInfo) HasScheme() bool`

HasScheme returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


