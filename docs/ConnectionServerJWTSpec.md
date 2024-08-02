# ConnectionServerJWTSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JwtAuthenticatorIds** | Pointer to **[]string** | List of JWT authenticators to be configured for this Connection Server. | [optional] 
**JwtSupport** | Pointer to **string** | JWT support option. Possible values are \&quot;DISABLED\&quot;, \&quot;MULTI_ENABLED\&quot;, \&quot;MULTI_REQUIRED\&quot;. If not present,default is \&quot;DISABLED\&quot;. * DISABLED: Indicates that the JWT support is disabled. * MULTI_ENABLED: Indicates that the JWT multi-auth support is enabled. * MULTI_REQUIRED: Indicates that the JWT multi-auth support is mandatory. | [optional] 

## Methods

### NewConnectionServerJWTSpec

`func NewConnectionServerJWTSpec() *ConnectionServerJWTSpec`

NewConnectionServerJWTSpec instantiates a new ConnectionServerJWTSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerJWTSpecWithDefaults

`func NewConnectionServerJWTSpecWithDefaults() *ConnectionServerJWTSpec`

NewConnectionServerJWTSpecWithDefaults instantiates a new ConnectionServerJWTSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJwtAuthenticatorIds

`func (o *ConnectionServerJWTSpec) GetJwtAuthenticatorIds() []string`

GetJwtAuthenticatorIds returns the JwtAuthenticatorIds field if non-nil, zero value otherwise.

### GetJwtAuthenticatorIdsOk

`func (o *ConnectionServerJWTSpec) GetJwtAuthenticatorIdsOk() (*[]string, bool)`

GetJwtAuthenticatorIdsOk returns a tuple with the JwtAuthenticatorIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtAuthenticatorIds

`func (o *ConnectionServerJWTSpec) SetJwtAuthenticatorIds(v []string)`

SetJwtAuthenticatorIds sets JwtAuthenticatorIds field to given value.

### HasJwtAuthenticatorIds

`func (o *ConnectionServerJWTSpec) HasJwtAuthenticatorIds() bool`

HasJwtAuthenticatorIds returns a boolean if a field has been set.

### GetJwtSupport

`func (o *ConnectionServerJWTSpec) GetJwtSupport() string`

GetJwtSupport returns the JwtSupport field if non-nil, zero value otherwise.

### GetJwtSupportOk

`func (o *ConnectionServerJWTSpec) GetJwtSupportOk() (*string, bool)`

GetJwtSupportOk returns a tuple with the JwtSupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtSupport

`func (o *ConnectionServerJWTSpec) SetJwtSupport(v string)`

SetJwtSupport sets JwtSupport field to given value.

### HasJwtSupport

`func (o *ConnectionServerJWTSpec) HasJwtSupport() bool`

HasJwtSupport returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


