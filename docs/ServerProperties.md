# ServerProperties

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CipherSuites** | Pointer to **[]string** | List of cipher suites of server. | [optional] 
**NamedGroups** | Pointer to **[]string** | List of named groups of server. | [optional] 
**SignatureAlgorithms** | Pointer to **[]string** | List of signature algorithms of server. | [optional] 
**ThumbprintAlgorithms** | Pointer to **[]string** | List of thumbprint algorithms of server. | [optional] 

## Methods

### NewServerProperties

`func NewServerProperties() *ServerProperties`

NewServerProperties instantiates a new ServerProperties object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerPropertiesWithDefaults

`func NewServerPropertiesWithDefaults() *ServerProperties`

NewServerPropertiesWithDefaults instantiates a new ServerProperties object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCipherSuites

`func (o *ServerProperties) GetCipherSuites() []string`

GetCipherSuites returns the CipherSuites field if non-nil, zero value otherwise.

### GetCipherSuitesOk

`func (o *ServerProperties) GetCipherSuitesOk() (*[]string, bool)`

GetCipherSuitesOk returns a tuple with the CipherSuites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCipherSuites

`func (o *ServerProperties) SetCipherSuites(v []string)`

SetCipherSuites sets CipherSuites field to given value.

### HasCipherSuites

`func (o *ServerProperties) HasCipherSuites() bool`

HasCipherSuites returns a boolean if a field has been set.

### GetNamedGroups

`func (o *ServerProperties) GetNamedGroups() []string`

GetNamedGroups returns the NamedGroups field if non-nil, zero value otherwise.

### GetNamedGroupsOk

`func (o *ServerProperties) GetNamedGroupsOk() (*[]string, bool)`

GetNamedGroupsOk returns a tuple with the NamedGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNamedGroups

`func (o *ServerProperties) SetNamedGroups(v []string)`

SetNamedGroups sets NamedGroups field to given value.

### HasNamedGroups

`func (o *ServerProperties) HasNamedGroups() bool`

HasNamedGroups returns a boolean if a field has been set.

### GetSignatureAlgorithms

`func (o *ServerProperties) GetSignatureAlgorithms() []string`

GetSignatureAlgorithms returns the SignatureAlgorithms field if non-nil, zero value otherwise.

### GetSignatureAlgorithmsOk

`func (o *ServerProperties) GetSignatureAlgorithmsOk() (*[]string, bool)`

GetSignatureAlgorithmsOk returns a tuple with the SignatureAlgorithms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureAlgorithms

`func (o *ServerProperties) SetSignatureAlgorithms(v []string)`

SetSignatureAlgorithms sets SignatureAlgorithms field to given value.

### HasSignatureAlgorithms

`func (o *ServerProperties) HasSignatureAlgorithms() bool`

HasSignatureAlgorithms returns a boolean if a field has been set.

### GetThumbprintAlgorithms

`func (o *ServerProperties) GetThumbprintAlgorithms() []string`

GetThumbprintAlgorithms returns the ThumbprintAlgorithms field if non-nil, zero value otherwise.

### GetThumbprintAlgorithmsOk

`func (o *ServerProperties) GetThumbprintAlgorithmsOk() (*[]string, bool)`

GetThumbprintAlgorithmsOk returns a tuple with the ThumbprintAlgorithms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbprintAlgorithms

`func (o *ServerProperties) SetThumbprintAlgorithms(v []string)`

SetThumbprintAlgorithms sets ThumbprintAlgorithms field to given value.

### HasThumbprintAlgorithms

`func (o *ServerProperties) HasThumbprintAlgorithms() bool`

HasThumbprintAlgorithms returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


