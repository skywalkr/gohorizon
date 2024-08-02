# AgentUpgradeTaskInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentInstallerPackageId** | Pointer to **string** | ID of the agent installer package. | [optional] 
**CancelledMachineOrRdsServerIds** | Pointer to **[]string** | Machines or RDS servers for which upgrade has been cancelled. | [optional] 
**EndTime** | Pointer to **int64** | Agent upgrade end time. | [optional] 
**FailedMachineOrRdsServerIds** | Pointer to **[]string** | Machines or RDS servers for which upgrade has failed. | [optional] 
**Id** | Pointer to **string** | Task ID of the agent upgrade. | [optional] 
**InProgressMachineOrRdsServerIds** | Pointer to **[]string** | Machines or RDS servers for which upgrade are in progress. | [optional] 
**NotStartedMachineOrRdsServerIds** | Pointer to **[]string** | Machines or RDS servers for which upgrade has not started. | [optional] 
**Operation** | Pointer to **string** | The current agent upgrade task operation. | [optional] 
**SkippedMachineOrRdsServerIds** | Pointer to **[]string** | Machines or RDS servers for which upgrade has skipped. | [optional] 
**StartTime** | Pointer to **int64** | Agent upgrade start time. | [optional] 
**State** | Pointer to **string** | The state of an agent upgrade task. | [optional] 
**SucceededMachineOrRdsServerIds** | Pointer to **[]string** | Machines or RDS servers for which upgrade has succeeded. | [optional] 

## Methods

### NewAgentUpgradeTaskInfo

`func NewAgentUpgradeTaskInfo() *AgentUpgradeTaskInfo`

NewAgentUpgradeTaskInfo instantiates a new AgentUpgradeTaskInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentUpgradeTaskInfoWithDefaults

`func NewAgentUpgradeTaskInfoWithDefaults() *AgentUpgradeTaskInfo`

NewAgentUpgradeTaskInfoWithDefaults instantiates a new AgentUpgradeTaskInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentInstallerPackageId

`func (o *AgentUpgradeTaskInfo) GetAgentInstallerPackageId() string`

GetAgentInstallerPackageId returns the AgentInstallerPackageId field if non-nil, zero value otherwise.

### GetAgentInstallerPackageIdOk

`func (o *AgentUpgradeTaskInfo) GetAgentInstallerPackageIdOk() (*string, bool)`

GetAgentInstallerPackageIdOk returns a tuple with the AgentInstallerPackageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentInstallerPackageId

`func (o *AgentUpgradeTaskInfo) SetAgentInstallerPackageId(v string)`

SetAgentInstallerPackageId sets AgentInstallerPackageId field to given value.

### HasAgentInstallerPackageId

`func (o *AgentUpgradeTaskInfo) HasAgentInstallerPackageId() bool`

HasAgentInstallerPackageId returns a boolean if a field has been set.

### GetCancelledMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) GetCancelledMachineOrRdsServerIds() []string`

GetCancelledMachineOrRdsServerIds returns the CancelledMachineOrRdsServerIds field if non-nil, zero value otherwise.

### GetCancelledMachineOrRdsServerIdsOk

`func (o *AgentUpgradeTaskInfo) GetCancelledMachineOrRdsServerIdsOk() (*[]string, bool)`

GetCancelledMachineOrRdsServerIdsOk returns a tuple with the CancelledMachineOrRdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelledMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) SetCancelledMachineOrRdsServerIds(v []string)`

SetCancelledMachineOrRdsServerIds sets CancelledMachineOrRdsServerIds field to given value.

### HasCancelledMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) HasCancelledMachineOrRdsServerIds() bool`

HasCancelledMachineOrRdsServerIds returns a boolean if a field has been set.

### GetEndTime

`func (o *AgentUpgradeTaskInfo) GetEndTime() int64`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *AgentUpgradeTaskInfo) GetEndTimeOk() (*int64, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *AgentUpgradeTaskInfo) SetEndTime(v int64)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *AgentUpgradeTaskInfo) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### GetFailedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) GetFailedMachineOrRdsServerIds() []string`

GetFailedMachineOrRdsServerIds returns the FailedMachineOrRdsServerIds field if non-nil, zero value otherwise.

### GetFailedMachineOrRdsServerIdsOk

`func (o *AgentUpgradeTaskInfo) GetFailedMachineOrRdsServerIdsOk() (*[]string, bool)`

GetFailedMachineOrRdsServerIdsOk returns a tuple with the FailedMachineOrRdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) SetFailedMachineOrRdsServerIds(v []string)`

SetFailedMachineOrRdsServerIds sets FailedMachineOrRdsServerIds field to given value.

### HasFailedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) HasFailedMachineOrRdsServerIds() bool`

HasFailedMachineOrRdsServerIds returns a boolean if a field has been set.

### GetId

`func (o *AgentUpgradeTaskInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentUpgradeTaskInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentUpgradeTaskInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AgentUpgradeTaskInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInProgressMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) GetInProgressMachineOrRdsServerIds() []string`

GetInProgressMachineOrRdsServerIds returns the InProgressMachineOrRdsServerIds field if non-nil, zero value otherwise.

### GetInProgressMachineOrRdsServerIdsOk

`func (o *AgentUpgradeTaskInfo) GetInProgressMachineOrRdsServerIdsOk() (*[]string, bool)`

GetInProgressMachineOrRdsServerIdsOk returns a tuple with the InProgressMachineOrRdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInProgressMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) SetInProgressMachineOrRdsServerIds(v []string)`

SetInProgressMachineOrRdsServerIds sets InProgressMachineOrRdsServerIds field to given value.

### HasInProgressMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) HasInProgressMachineOrRdsServerIds() bool`

HasInProgressMachineOrRdsServerIds returns a boolean if a field has been set.

### GetNotStartedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) GetNotStartedMachineOrRdsServerIds() []string`

GetNotStartedMachineOrRdsServerIds returns the NotStartedMachineOrRdsServerIds field if non-nil, zero value otherwise.

### GetNotStartedMachineOrRdsServerIdsOk

`func (o *AgentUpgradeTaskInfo) GetNotStartedMachineOrRdsServerIdsOk() (*[]string, bool)`

GetNotStartedMachineOrRdsServerIdsOk returns a tuple with the NotStartedMachineOrRdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotStartedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) SetNotStartedMachineOrRdsServerIds(v []string)`

SetNotStartedMachineOrRdsServerIds sets NotStartedMachineOrRdsServerIds field to given value.

### HasNotStartedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) HasNotStartedMachineOrRdsServerIds() bool`

HasNotStartedMachineOrRdsServerIds returns a boolean if a field has been set.

### GetOperation

`func (o *AgentUpgradeTaskInfo) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AgentUpgradeTaskInfo) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AgentUpgradeTaskInfo) SetOperation(v string)`

SetOperation sets Operation field to given value.

### HasOperation

`func (o *AgentUpgradeTaskInfo) HasOperation() bool`

HasOperation returns a boolean if a field has been set.

### GetSkippedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) GetSkippedMachineOrRdsServerIds() []string`

GetSkippedMachineOrRdsServerIds returns the SkippedMachineOrRdsServerIds field if non-nil, zero value otherwise.

### GetSkippedMachineOrRdsServerIdsOk

`func (o *AgentUpgradeTaskInfo) GetSkippedMachineOrRdsServerIdsOk() (*[]string, bool)`

GetSkippedMachineOrRdsServerIdsOk returns a tuple with the SkippedMachineOrRdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkippedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) SetSkippedMachineOrRdsServerIds(v []string)`

SetSkippedMachineOrRdsServerIds sets SkippedMachineOrRdsServerIds field to given value.

### HasSkippedMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) HasSkippedMachineOrRdsServerIds() bool`

HasSkippedMachineOrRdsServerIds returns a boolean if a field has been set.

### GetStartTime

`func (o *AgentUpgradeTaskInfo) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *AgentUpgradeTaskInfo) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *AgentUpgradeTaskInfo) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *AgentUpgradeTaskInfo) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### GetState

`func (o *AgentUpgradeTaskInfo) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AgentUpgradeTaskInfo) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AgentUpgradeTaskInfo) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *AgentUpgradeTaskInfo) HasState() bool`

HasState returns a boolean if a field has been set.

### GetSucceededMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) GetSucceededMachineOrRdsServerIds() []string`

GetSucceededMachineOrRdsServerIds returns the SucceededMachineOrRdsServerIds field if non-nil, zero value otherwise.

### GetSucceededMachineOrRdsServerIdsOk

`func (o *AgentUpgradeTaskInfo) GetSucceededMachineOrRdsServerIdsOk() (*[]string, bool)`

GetSucceededMachineOrRdsServerIdsOk returns a tuple with the SucceededMachineOrRdsServerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSucceededMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) SetSucceededMachineOrRdsServerIds(v []string)`

SetSucceededMachineOrRdsServerIds sets SucceededMachineOrRdsServerIds field to given value.

### HasSucceededMachineOrRdsServerIds

`func (o *AgentUpgradeTaskInfo) HasSucceededMachineOrRdsServerIds() bool`

HasSucceededMachineOrRdsServerIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


