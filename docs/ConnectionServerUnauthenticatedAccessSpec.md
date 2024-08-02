# ConnectionServerUnauthenticatedAccessSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlockUnsupportedClients** | Pointer to **bool** | Block older clients which don&#39;t support client puzzles  to prevent DOS attack on RDSH servers for Unauthenticated Access. | [optional] 
**ClientPuzzleDifficulty** | Pointer to **int32** | Client puzzle difficulty for DoS attack prevention for Unauthenticated Access.  Higher difficulty might increase login time and affect user experience. This property has a default value of 21 | [optional] 
**DefaultUnauthUserId** | Pointer to **string** | Default user for unauthenticated access in this connection server. | [optional] 
**Enabled** | **bool** | Indicates whether unauthenticated access is enabled in this connection server. | 
**UserIdleTimeout** | Pointer to **int32** | Unauthenticated Access user idle session timeout in minutes. | [optional] 

## Methods

### NewConnectionServerUnauthenticatedAccessSpec

`func NewConnectionServerUnauthenticatedAccessSpec(enabled bool, ) *ConnectionServerUnauthenticatedAccessSpec`

NewConnectionServerUnauthenticatedAccessSpec instantiates a new ConnectionServerUnauthenticatedAccessSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerUnauthenticatedAccessSpecWithDefaults

`func NewConnectionServerUnauthenticatedAccessSpecWithDefaults() *ConnectionServerUnauthenticatedAccessSpec`

NewConnectionServerUnauthenticatedAccessSpecWithDefaults instantiates a new ConnectionServerUnauthenticatedAccessSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlockUnsupportedClients

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetBlockUnsupportedClients() bool`

GetBlockUnsupportedClients returns the BlockUnsupportedClients field if non-nil, zero value otherwise.

### GetBlockUnsupportedClientsOk

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetBlockUnsupportedClientsOk() (*bool, bool)`

GetBlockUnsupportedClientsOk returns a tuple with the BlockUnsupportedClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockUnsupportedClients

`func (o *ConnectionServerUnauthenticatedAccessSpec) SetBlockUnsupportedClients(v bool)`

SetBlockUnsupportedClients sets BlockUnsupportedClients field to given value.

### HasBlockUnsupportedClients

`func (o *ConnectionServerUnauthenticatedAccessSpec) HasBlockUnsupportedClients() bool`

HasBlockUnsupportedClients returns a boolean if a field has been set.

### GetClientPuzzleDifficulty

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetClientPuzzleDifficulty() int32`

GetClientPuzzleDifficulty returns the ClientPuzzleDifficulty field if non-nil, zero value otherwise.

### GetClientPuzzleDifficultyOk

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetClientPuzzleDifficultyOk() (*int32, bool)`

GetClientPuzzleDifficultyOk returns a tuple with the ClientPuzzleDifficulty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientPuzzleDifficulty

`func (o *ConnectionServerUnauthenticatedAccessSpec) SetClientPuzzleDifficulty(v int32)`

SetClientPuzzleDifficulty sets ClientPuzzleDifficulty field to given value.

### HasClientPuzzleDifficulty

`func (o *ConnectionServerUnauthenticatedAccessSpec) HasClientPuzzleDifficulty() bool`

HasClientPuzzleDifficulty returns a boolean if a field has been set.

### GetDefaultUnauthUserId

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetDefaultUnauthUserId() string`

GetDefaultUnauthUserId returns the DefaultUnauthUserId field if non-nil, zero value otherwise.

### GetDefaultUnauthUserIdOk

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetDefaultUnauthUserIdOk() (*string, bool)`

GetDefaultUnauthUserIdOk returns a tuple with the DefaultUnauthUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultUnauthUserId

`func (o *ConnectionServerUnauthenticatedAccessSpec) SetDefaultUnauthUserId(v string)`

SetDefaultUnauthUserId sets DefaultUnauthUserId field to given value.

### HasDefaultUnauthUserId

`func (o *ConnectionServerUnauthenticatedAccessSpec) HasDefaultUnauthUserId() bool`

HasDefaultUnauthUserId returns a boolean if a field has been set.

### GetEnabled

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ConnectionServerUnauthenticatedAccessSpec) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetUserIdleTimeout

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetUserIdleTimeout() int32`

GetUserIdleTimeout returns the UserIdleTimeout field if non-nil, zero value otherwise.

### GetUserIdleTimeoutOk

`func (o *ConnectionServerUnauthenticatedAccessSpec) GetUserIdleTimeoutOk() (*int32, bool)`

GetUserIdleTimeoutOk returns a tuple with the UserIdleTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserIdleTimeout

`func (o *ConnectionServerUnauthenticatedAccessSpec) SetUserIdleTimeout(v int32)`

SetUserIdleTimeout sets UserIdleTimeout field to given value.

### HasUserIdleTimeout

`func (o *ConnectionServerUnauthenticatedAccessSpec) HasUserIdleTimeout() bool`

HasUserIdleTimeout returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


