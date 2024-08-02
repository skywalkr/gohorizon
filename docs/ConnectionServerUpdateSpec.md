# ConnectionServerUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JwtInfo** | Pointer to [**ConnectionServerJWTSpec**](ConnectionServerJWTSpec.md) |  | [optional] 

## Methods

### NewConnectionServerUpdateSpec

`func NewConnectionServerUpdateSpec() *ConnectionServerUpdateSpec`

NewConnectionServerUpdateSpec instantiates a new ConnectionServerUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerUpdateSpecWithDefaults

`func NewConnectionServerUpdateSpecWithDefaults() *ConnectionServerUpdateSpec`

NewConnectionServerUpdateSpecWithDefaults instantiates a new ConnectionServerUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJwtInfo

`func (o *ConnectionServerUpdateSpec) GetJwtInfo() ConnectionServerJWTSpec`

GetJwtInfo returns the JwtInfo field if non-nil, zero value otherwise.

### GetJwtInfoOk

`func (o *ConnectionServerUpdateSpec) GetJwtInfoOk() (*ConnectionServerJWTSpec, bool)`

GetJwtInfoOk returns a tuple with the JwtInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtInfo

`func (o *ConnectionServerUpdateSpec) SetJwtInfo(v ConnectionServerJWTSpec)`

SetJwtInfo sets JwtInfo field to given value.

### HasJwtInfo

`func (o *ConnectionServerUpdateSpec) HasJwtInfo() bool`

HasJwtInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


