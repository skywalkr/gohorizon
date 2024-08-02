# MachineAgentUpgradeSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentInstallerPackageId** | Pointer to **string** | ID of the agent installer package. | [optional] 
**CustomInstallParameters** | Pointer to **string** | Indicates any parameters to be used by the agent for silent install. | [optional] 
**EndTime** | **int64** | Agent upgrade end time. | 
**MachineIds** | **[]string** | Machine Ids representing the machines to be upgraded. | 
**SkipForLoggedInUsers** | Pointer to **bool** | Indicates whether to skip agent upgrade for logged in users. | [optional] 
**StartTime** | **int64** | Agent upgrade start time. | 

## Methods

### NewMachineAgentUpgradeSpec

`func NewMachineAgentUpgradeSpec(endTime int64, machineIds []string, startTime int64, ) *MachineAgentUpgradeSpec`

NewMachineAgentUpgradeSpec instantiates a new MachineAgentUpgradeSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMachineAgentUpgradeSpecWithDefaults

`func NewMachineAgentUpgradeSpecWithDefaults() *MachineAgentUpgradeSpec`

NewMachineAgentUpgradeSpecWithDefaults instantiates a new MachineAgentUpgradeSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentInstallerPackageId

`func (o *MachineAgentUpgradeSpec) GetAgentInstallerPackageId() string`

GetAgentInstallerPackageId returns the AgentInstallerPackageId field if non-nil, zero value otherwise.

### GetAgentInstallerPackageIdOk

`func (o *MachineAgentUpgradeSpec) GetAgentInstallerPackageIdOk() (*string, bool)`

GetAgentInstallerPackageIdOk returns a tuple with the AgentInstallerPackageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentInstallerPackageId

`func (o *MachineAgentUpgradeSpec) SetAgentInstallerPackageId(v string)`

SetAgentInstallerPackageId sets AgentInstallerPackageId field to given value.

### HasAgentInstallerPackageId

`func (o *MachineAgentUpgradeSpec) HasAgentInstallerPackageId() bool`

HasAgentInstallerPackageId returns a boolean if a field has been set.

### GetCustomInstallParameters

`func (o *MachineAgentUpgradeSpec) GetCustomInstallParameters() string`

GetCustomInstallParameters returns the CustomInstallParameters field if non-nil, zero value otherwise.

### GetCustomInstallParametersOk

`func (o *MachineAgentUpgradeSpec) GetCustomInstallParametersOk() (*string, bool)`

GetCustomInstallParametersOk returns a tuple with the CustomInstallParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomInstallParameters

`func (o *MachineAgentUpgradeSpec) SetCustomInstallParameters(v string)`

SetCustomInstallParameters sets CustomInstallParameters field to given value.

### HasCustomInstallParameters

`func (o *MachineAgentUpgradeSpec) HasCustomInstallParameters() bool`

HasCustomInstallParameters returns a boolean if a field has been set.

### GetEndTime

`func (o *MachineAgentUpgradeSpec) GetEndTime() int64`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *MachineAgentUpgradeSpec) GetEndTimeOk() (*int64, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *MachineAgentUpgradeSpec) SetEndTime(v int64)`

SetEndTime sets EndTime field to given value.


### GetMachineIds

`func (o *MachineAgentUpgradeSpec) GetMachineIds() []string`

GetMachineIds returns the MachineIds field if non-nil, zero value otherwise.

### GetMachineIdsOk

`func (o *MachineAgentUpgradeSpec) GetMachineIdsOk() (*[]string, bool)`

GetMachineIdsOk returns a tuple with the MachineIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineIds

`func (o *MachineAgentUpgradeSpec) SetMachineIds(v []string)`

SetMachineIds sets MachineIds field to given value.


### GetSkipForLoggedInUsers

`func (o *MachineAgentUpgradeSpec) GetSkipForLoggedInUsers() bool`

GetSkipForLoggedInUsers returns the SkipForLoggedInUsers field if non-nil, zero value otherwise.

### GetSkipForLoggedInUsersOk

`func (o *MachineAgentUpgradeSpec) GetSkipForLoggedInUsersOk() (*bool, bool)`

GetSkipForLoggedInUsersOk returns a tuple with the SkipForLoggedInUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipForLoggedInUsers

`func (o *MachineAgentUpgradeSpec) SetSkipForLoggedInUsers(v bool)`

SetSkipForLoggedInUsers sets SkipForLoggedInUsers field to given value.

### HasSkipForLoggedInUsers

`func (o *MachineAgentUpgradeSpec) HasSkipForLoggedInUsers() bool`

HasSkipForLoggedInUsers returns a boolean if a field has been set.

### GetStartTime

`func (o *MachineAgentUpgradeSpec) GetStartTime() int64`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *MachineAgentUpgradeSpec) GetStartTimeOk() (*int64, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *MachineAgentUpgradeSpec) SetStartTime(v int64)`

SetStartTime sets StartTime field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


