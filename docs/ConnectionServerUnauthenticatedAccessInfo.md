# ConnectionServerUnauthenticatedAccessInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlockUnsupportedClients** | Pointer to **bool** | Block older clients which don&#39;t support client puzzles  to prevent DOS attack on RDSH servers for Unauthenticated Access. | [optional] 
**ClientPuzzleDifficulty** | Pointer to **int32** | Client puzzle difficulty for DoS attack prevention for Unauthenticated Access.  Higher difficulty might increase login time and affect user experience. | [optional] 
**DefaultUnauthUserId** | Pointer to **string** | Default user for unauthenticated access in this connection server. | [optional] 
**Enabled** | Pointer to **bool** | Indicates whether unauthenticated access is enabled in this connection server. | [optional] 
**UserIdleTimeout** | Pointer to **int32** | Unauthenticated Access user idle session timeout in minutes. | [optional] 

## Methods

### NewConnectionServerUnauthenticatedAccessInfo

`func NewConnectionServerUnauthenticatedAccessInfo() *ConnectionServerUnauthenticatedAccessInfo`

NewConnectionServerUnauthenticatedAccessInfo instantiates a new ConnectionServerUnauthenticatedAccessInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerUnauthenticatedAccessInfoWithDefaults

`func NewConnectionServerUnauthenticatedAccessInfoWithDefaults() *ConnectionServerUnauthenticatedAccessInfo`

NewConnectionServerUnauthenticatedAccessInfoWithDefaults instantiates a new ConnectionServerUnauthenticatedAccessInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlockUnsupportedClients

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetBlockUnsupportedClients() bool`

GetBlockUnsupportedClients returns the BlockUnsupportedClients field if non-nil, zero value otherwise.

### GetBlockUnsupportedClientsOk

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetBlockUnsupportedClientsOk() (*bool, bool)`

GetBlockUnsupportedClientsOk returns a tuple with the BlockUnsupportedClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockUnsupportedClients

`func (o *ConnectionServerUnauthenticatedAccessInfo) SetBlockUnsupportedClients(v bool)`

SetBlockUnsupportedClients sets BlockUnsupportedClients field to given value.

### HasBlockUnsupportedClients

`func (o *ConnectionServerUnauthenticatedAccessInfo) HasBlockUnsupportedClients() bool`

HasBlockUnsupportedClients returns a boolean if a field has been set.

### GetClientPuzzleDifficulty

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetClientPuzzleDifficulty() int32`

GetClientPuzzleDifficulty returns the ClientPuzzleDifficulty field if non-nil, zero value otherwise.

### GetClientPuzzleDifficultyOk

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetClientPuzzleDifficultyOk() (*int32, bool)`

GetClientPuzzleDifficultyOk returns a tuple with the ClientPuzzleDifficulty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientPuzzleDifficulty

`func (o *ConnectionServerUnauthenticatedAccessInfo) SetClientPuzzleDifficulty(v int32)`

SetClientPuzzleDifficulty sets ClientPuzzleDifficulty field to given value.

### HasClientPuzzleDifficulty

`func (o *ConnectionServerUnauthenticatedAccessInfo) HasClientPuzzleDifficulty() bool`

HasClientPuzzleDifficulty returns a boolean if a field has been set.

### GetDefaultUnauthUserId

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetDefaultUnauthUserId() string`

GetDefaultUnauthUserId returns the DefaultUnauthUserId field if non-nil, zero value otherwise.

### GetDefaultUnauthUserIdOk

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetDefaultUnauthUserIdOk() (*string, bool)`

GetDefaultUnauthUserIdOk returns a tuple with the DefaultUnauthUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultUnauthUserId

`func (o *ConnectionServerUnauthenticatedAccessInfo) SetDefaultUnauthUserId(v string)`

SetDefaultUnauthUserId sets DefaultUnauthUserId field to given value.

### HasDefaultUnauthUserId

`func (o *ConnectionServerUnauthenticatedAccessInfo) HasDefaultUnauthUserId() bool`

HasDefaultUnauthUserId returns a boolean if a field has been set.

### GetEnabled

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ConnectionServerUnauthenticatedAccessInfo) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ConnectionServerUnauthenticatedAccessInfo) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetUserIdleTimeout

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetUserIdleTimeout() int32`

GetUserIdleTimeout returns the UserIdleTimeout field if non-nil, zero value otherwise.

### GetUserIdleTimeoutOk

`func (o *ConnectionServerUnauthenticatedAccessInfo) GetUserIdleTimeoutOk() (*int32, bool)`

GetUserIdleTimeoutOk returns a tuple with the UserIdleTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserIdleTimeout

`func (o *ConnectionServerUnauthenticatedAccessInfo) SetUserIdleTimeout(v int32)`

SetUserIdleTimeout sets UserIdleTimeout field to given value.

### HasUserIdleTimeout

`func (o *ConnectionServerUnauthenticatedAccessInfo) HasUserIdleTimeout() bool`

HasUserIdleTimeout returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


