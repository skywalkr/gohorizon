# HeldVMInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MachineId** | Pointer to **string** | Unique virtual center moid representing the virtual machine. | [optional] 
**MachineState** | Pointer to **string** | Machine state * PROVISIONING: The machine is being provisioned. * PROVISIONING_ERROR: An error occurred during provisioning. * WAITING_FOR_AGENT: Horizon Connection Server is waiting to establish communication with Horizon Agent for one of these cases - a virtual machine in a manual desktop pool, unmanaged machine or RDS server. * CUSTOMIZING: The machine which is from an automated desktop pool is being customized after provisioning. * DELETING: The machine is marked for deletion. * MAINTENANCE: The machine is in maintenance mode. Users cannot log in or use the machine. * ERROR: An unknown error occurred in the machine. * PROVISIONED: The machine is powered off or suspended. * AGENT_UNREACHABLE: Horizon Connection Server cannot establish communication with Horizon Agent on the machine. * UNASSIGNED_USER_CONNECTED: A user other than the assigned user is logged in to the machine in a dedicated desktop pool. * CONNECTED: The machine is in an active session and has an active connection to a Horizon client. * UNASSIGNED_USER_DISCONNECTED: A user other than the assigned user is logged in and disconnected from the machine in a dedicated desktop pool. * DISCONNECTED: The machine is in an active session, but it is disconnected from the Horizon client. * AGENT_ERROR_STARTUP_IN_PROGRESS: Horizon Agent has started on the machine, but other required services such as the display protocol are still starting. * AGENT_ERROR_DISABLED: Horizon Agent is disabled. * AGENT_ERROR_INVALID_IP: Horizon Agent has an invalid IP address. * AGENT_ERROR_NEEDS_REBOOT: Horizon Agent needs reboot. * AGENT_ERROR_PROTOCOL_FAILURE: Protocol such as BLAST, RDP or PCoIP is not enabled. * AGENT_CONFIG_ERROR: The Remote Desktop Services role is not enabled on the windows server. * AGENT_DRAIN_MODE: RDS host is configured for drain mode. New connections are currently disabled. * AGENT_DRAIN_UNTIL_RESTART: RDS host is configured for drain-until-restart mode. * ALREADY_USED: The machine is configured to have only one session which is currently in progress and cannot accept new sessions. * AVAILABLE: The machine is powered on and ready for active connections. * IN_PROGRESS: There is a machine operation in progress. * DISABLED: The machine is disabled. * DISABLE_IN_PROGRESS: Disabled Horizon Connection Server still has some Horizon brokered sessions. It can still accept re-connections. * VALIDATING: The Horizon Connection Server is synchronizing state information with the agent. * UNKNOWN: Could not determine the state of the machine. | [optional] 
**Name** | Pointer to **string** | VM name. | [optional] 

## Methods

### NewHeldVMInfo

`func NewHeldVMInfo() *HeldVMInfo`

NewHeldVMInfo instantiates a new HeldVMInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHeldVMInfoWithDefaults

`func NewHeldVMInfoWithDefaults() *HeldVMInfo`

NewHeldVMInfoWithDefaults instantiates a new HeldVMInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMachineId

`func (o *HeldVMInfo) GetMachineId() string`

GetMachineId returns the MachineId field if non-nil, zero value otherwise.

### GetMachineIdOk

`func (o *HeldVMInfo) GetMachineIdOk() (*string, bool)`

GetMachineIdOk returns a tuple with the MachineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineId

`func (o *HeldVMInfo) SetMachineId(v string)`

SetMachineId sets MachineId field to given value.

### HasMachineId

`func (o *HeldVMInfo) HasMachineId() bool`

HasMachineId returns a boolean if a field has been set.

### GetMachineState

`func (o *HeldVMInfo) GetMachineState() string`

GetMachineState returns the MachineState field if non-nil, zero value otherwise.

### GetMachineStateOk

`func (o *HeldVMInfo) GetMachineStateOk() (*string, bool)`

GetMachineStateOk returns a tuple with the MachineState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineState

`func (o *HeldVMInfo) SetMachineState(v string)`

SetMachineState sets MachineState field to given value.

### HasMachineState

`func (o *HeldVMInfo) HasMachineState() bool`

HasMachineState returns a boolean if a field has been set.

### GetName

`func (o *HeldVMInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *HeldVMInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *HeldVMInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *HeldVMInfo) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


