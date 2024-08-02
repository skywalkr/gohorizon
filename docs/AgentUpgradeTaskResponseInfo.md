# AgentUpgradeTaskResponseInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Details** | Pointer to [**[]BulkItemResponseInfo**](BulkItemResponseInfo.md) | List of BulkItemResponseInfo corresponding to each machine id in the action operation. | [optional] 
**TaskId** | Pointer to **string** | Unique ID representing the task. | [optional] 

## Methods

### NewAgentUpgradeTaskResponseInfo

`func NewAgentUpgradeTaskResponseInfo() *AgentUpgradeTaskResponseInfo`

NewAgentUpgradeTaskResponseInfo instantiates a new AgentUpgradeTaskResponseInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentUpgradeTaskResponseInfoWithDefaults

`func NewAgentUpgradeTaskResponseInfoWithDefaults() *AgentUpgradeTaskResponseInfo`

NewAgentUpgradeTaskResponseInfoWithDefaults instantiates a new AgentUpgradeTaskResponseInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDetails

`func (o *AgentUpgradeTaskResponseInfo) GetDetails() []BulkItemResponseInfo`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *AgentUpgradeTaskResponseInfo) GetDetailsOk() (*[]BulkItemResponseInfo, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *AgentUpgradeTaskResponseInfo) SetDetails(v []BulkItemResponseInfo)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *AgentUpgradeTaskResponseInfo) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetTaskId

`func (o *AgentUpgradeTaskResponseInfo) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *AgentUpgradeTaskResponseInfo) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *AgentUpgradeTaskResponseInfo) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.

### HasTaskId

`func (o *AgentUpgradeTaskResponseInfo) HasTaskId() bool`

HasTaskId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


