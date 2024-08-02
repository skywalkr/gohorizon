# ConnectionServerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique Id of the Connection Server. | [optional] 
**JwtInfo** | Pointer to [**ConnectionServerJWTInfo**](ConnectionServerJWTInfo.md) |  | [optional] 

## Methods

### NewConnectionServerInfo

`func NewConnectionServerInfo() *ConnectionServerInfo`

NewConnectionServerInfo instantiates a new ConnectionServerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerInfoWithDefaults

`func NewConnectionServerInfoWithDefaults() *ConnectionServerInfo`

NewConnectionServerInfoWithDefaults instantiates a new ConnectionServerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ConnectionServerInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConnectionServerInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConnectionServerInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ConnectionServerInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetJwtInfo

`func (o *ConnectionServerInfo) GetJwtInfo() ConnectionServerJWTInfo`

GetJwtInfo returns the JwtInfo field if non-nil, zero value otherwise.

### GetJwtInfoOk

`func (o *ConnectionServerInfo) GetJwtInfoOk() (*ConnectionServerJWTInfo, bool)`

GetJwtInfoOk returns a tuple with the JwtInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtInfo

`func (o *ConnectionServerInfo) SetJwtInfo(v ConnectionServerJWTInfo)`

SetJwtInfo sets JwtInfo field to given value.

### HasJwtInfo

`func (o *ConnectionServerInfo) HasJwtInfo() bool`

HasJwtInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


