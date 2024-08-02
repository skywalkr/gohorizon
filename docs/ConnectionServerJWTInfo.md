# ConnectionServerJWTInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JwtAuthenticatorIds** | Pointer to **[]string** | List of configured JWT authenticators for this Connection Server. | [optional] 
**JwtSupport** | Pointer to **string** | JWT support option. * DISABLED: Indicates that the JWT support is disabled. * MULTI_ENABLED: Indicates that the JWT multi-auth support is enabled. * MULTI_REQUIRED: Indicates that the JWT multi-auth support is mandatory. | [optional] 

## Methods

### NewConnectionServerJWTInfo

`func NewConnectionServerJWTInfo() *ConnectionServerJWTInfo`

NewConnectionServerJWTInfo instantiates a new ConnectionServerJWTInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerJWTInfoWithDefaults

`func NewConnectionServerJWTInfoWithDefaults() *ConnectionServerJWTInfo`

NewConnectionServerJWTInfoWithDefaults instantiates a new ConnectionServerJWTInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJwtAuthenticatorIds

`func (o *ConnectionServerJWTInfo) GetJwtAuthenticatorIds() []string`

GetJwtAuthenticatorIds returns the JwtAuthenticatorIds field if non-nil, zero value otherwise.

### GetJwtAuthenticatorIdsOk

`func (o *ConnectionServerJWTInfo) GetJwtAuthenticatorIdsOk() (*[]string, bool)`

GetJwtAuthenticatorIdsOk returns a tuple with the JwtAuthenticatorIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtAuthenticatorIds

`func (o *ConnectionServerJWTInfo) SetJwtAuthenticatorIds(v []string)`

SetJwtAuthenticatorIds sets JwtAuthenticatorIds field to given value.

### HasJwtAuthenticatorIds

`func (o *ConnectionServerJWTInfo) HasJwtAuthenticatorIds() bool`

HasJwtAuthenticatorIds returns a boolean if a field has been set.

### GetJwtSupport

`func (o *ConnectionServerJWTInfo) GetJwtSupport() string`

GetJwtSupport returns the JwtSupport field if non-nil, zero value otherwise.

### GetJwtSupportOk

`func (o *ConnectionServerJWTInfo) GetJwtSupportOk() (*string, bool)`

GetJwtSupportOk returns a tuple with the JwtSupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtSupport

`func (o *ConnectionServerJWTInfo) SetJwtSupport(v string)`

SetJwtSupport sets JwtSupport field to given value.

### HasJwtSupport

`func (o *ConnectionServerJWTInfo) HasJwtSupport() bool`

HasJwtSupport returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


