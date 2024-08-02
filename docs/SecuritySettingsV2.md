# SecuritySettingsV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClusterPublicKey** | Pointer to **string** | The Base 64 encoded public key of the cluster in PEM format. | [optional] 
**ClusterPublicKeyId** | Pointer to **string** | Key Id to identify the cluster&#39;s active key pair. | [optional] 
**DataRecoveryPasswordConfigured** | Pointer to **bool** | Indicates whether the backup recovery password has been configured. | [optional] 
**DisallowEnhancedSecurityMode** | Pointer to **bool** | If true, Enhanced message security mode is disallowed (FIPS mode only). If set when Enhanced message security mode is in force, this will cause an automatic transition to Enabled mode.  | [optional] 
**MessageSecurityMode** | Pointer to **string** | Determines if signing and verification of the JMS messages passed between Horizon components takes place. * DISABLED: Message security mode is disabled. * MIXED: Message security mode is enabled but not enforced. * ENABLED: Message security mode is enabled. Unsigned messages are rejected by Horizon components. * ENHANCED: Message Security mode is Enhanced. Message signing and validation is performed based on the current Security Level and desktop Message Security mode. | [optional] 
**MessageSecurityStatus** | Pointer to **string** | The status of the JMS message security. This tracks the application of changes to messageSecurityMode. * NOTSET: The cluster is performing at the specified message security mode. * ENHANCED: The Cluster is in Enhanced message security mode. * WAITING_FOR_BUS_RESTARTS: The cluster is waiting for the bus restart The cluster is waiting for a bus restart to transition to ENHANCED messagesecurity mode or from ENHANCED message security mode . * PENDING_ENHANCED: The cluster is propagating the change to ENHANCED message security mode to all nodes. * LEAVING_ENHANCED: The cluster is leaving the ENHANCED message security mode. * PREPARING_ENHANCED: The cluster is preparing to go in Enhanced mode. * DISABLED: Message security mode is disabled. * MIXED: Message security mode is enabled but not enforced. * ENABLED: Message security mode is enabled. Unsigned messages are rejected by Horizon components. | [optional] 
**ReAuthSecureTunnelAfterInterruption** | Pointer to **bool** | Determines if user credentials must be re-authenticated after a network interruption when Horizon clients use secure tunnel connections to Horizon resources. When you select this setting, if a secure tunnel connection ends during a session, Horizon Client requires the user to re-authenticate before reconnecting. | [optional] 

## Methods

### NewSecuritySettingsV2

`func NewSecuritySettingsV2() *SecuritySettingsV2`

NewSecuritySettingsV2 instantiates a new SecuritySettingsV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecuritySettingsV2WithDefaults

`func NewSecuritySettingsV2WithDefaults() *SecuritySettingsV2`

NewSecuritySettingsV2WithDefaults instantiates a new SecuritySettingsV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClusterPublicKey

`func (o *SecuritySettingsV2) GetClusterPublicKey() string`

GetClusterPublicKey returns the ClusterPublicKey field if non-nil, zero value otherwise.

### GetClusterPublicKeyOk

`func (o *SecuritySettingsV2) GetClusterPublicKeyOk() (*string, bool)`

GetClusterPublicKeyOk returns a tuple with the ClusterPublicKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterPublicKey

`func (o *SecuritySettingsV2) SetClusterPublicKey(v string)`

SetClusterPublicKey sets ClusterPublicKey field to given value.

### HasClusterPublicKey

`func (o *SecuritySettingsV2) HasClusterPublicKey() bool`

HasClusterPublicKey returns a boolean if a field has been set.

### GetClusterPublicKeyId

`func (o *SecuritySettingsV2) GetClusterPublicKeyId() string`

GetClusterPublicKeyId returns the ClusterPublicKeyId field if non-nil, zero value otherwise.

### GetClusterPublicKeyIdOk

`func (o *SecuritySettingsV2) GetClusterPublicKeyIdOk() (*string, bool)`

GetClusterPublicKeyIdOk returns a tuple with the ClusterPublicKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterPublicKeyId

`func (o *SecuritySettingsV2) SetClusterPublicKeyId(v string)`

SetClusterPublicKeyId sets ClusterPublicKeyId field to given value.

### HasClusterPublicKeyId

`func (o *SecuritySettingsV2) HasClusterPublicKeyId() bool`

HasClusterPublicKeyId returns a boolean if a field has been set.

### GetDataRecoveryPasswordConfigured

`func (o *SecuritySettingsV2) GetDataRecoveryPasswordConfigured() bool`

GetDataRecoveryPasswordConfigured returns the DataRecoveryPasswordConfigured field if non-nil, zero value otherwise.

### GetDataRecoveryPasswordConfiguredOk

`func (o *SecuritySettingsV2) GetDataRecoveryPasswordConfiguredOk() (*bool, bool)`

GetDataRecoveryPasswordConfiguredOk returns a tuple with the DataRecoveryPasswordConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataRecoveryPasswordConfigured

`func (o *SecuritySettingsV2) SetDataRecoveryPasswordConfigured(v bool)`

SetDataRecoveryPasswordConfigured sets DataRecoveryPasswordConfigured field to given value.

### HasDataRecoveryPasswordConfigured

`func (o *SecuritySettingsV2) HasDataRecoveryPasswordConfigured() bool`

HasDataRecoveryPasswordConfigured returns a boolean if a field has been set.

### GetDisallowEnhancedSecurityMode

`func (o *SecuritySettingsV2) GetDisallowEnhancedSecurityMode() bool`

GetDisallowEnhancedSecurityMode returns the DisallowEnhancedSecurityMode field if non-nil, zero value otherwise.

### GetDisallowEnhancedSecurityModeOk

`func (o *SecuritySettingsV2) GetDisallowEnhancedSecurityModeOk() (*bool, bool)`

GetDisallowEnhancedSecurityModeOk returns a tuple with the DisallowEnhancedSecurityMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisallowEnhancedSecurityMode

`func (o *SecuritySettingsV2) SetDisallowEnhancedSecurityMode(v bool)`

SetDisallowEnhancedSecurityMode sets DisallowEnhancedSecurityMode field to given value.

### HasDisallowEnhancedSecurityMode

`func (o *SecuritySettingsV2) HasDisallowEnhancedSecurityMode() bool`

HasDisallowEnhancedSecurityMode returns a boolean if a field has been set.

### GetMessageSecurityMode

`func (o *SecuritySettingsV2) GetMessageSecurityMode() string`

GetMessageSecurityMode returns the MessageSecurityMode field if non-nil, zero value otherwise.

### GetMessageSecurityModeOk

`func (o *SecuritySettingsV2) GetMessageSecurityModeOk() (*string, bool)`

GetMessageSecurityModeOk returns a tuple with the MessageSecurityMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageSecurityMode

`func (o *SecuritySettingsV2) SetMessageSecurityMode(v string)`

SetMessageSecurityMode sets MessageSecurityMode field to given value.

### HasMessageSecurityMode

`func (o *SecuritySettingsV2) HasMessageSecurityMode() bool`

HasMessageSecurityMode returns a boolean if a field has been set.

### GetMessageSecurityStatus

`func (o *SecuritySettingsV2) GetMessageSecurityStatus() string`

GetMessageSecurityStatus returns the MessageSecurityStatus field if non-nil, zero value otherwise.

### GetMessageSecurityStatusOk

`func (o *SecuritySettingsV2) GetMessageSecurityStatusOk() (*string, bool)`

GetMessageSecurityStatusOk returns a tuple with the MessageSecurityStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageSecurityStatus

`func (o *SecuritySettingsV2) SetMessageSecurityStatus(v string)`

SetMessageSecurityStatus sets MessageSecurityStatus field to given value.

### HasMessageSecurityStatus

`func (o *SecuritySettingsV2) HasMessageSecurityStatus() bool`

HasMessageSecurityStatus returns a boolean if a field has been set.

### GetReAuthSecureTunnelAfterInterruption

`func (o *SecuritySettingsV2) GetReAuthSecureTunnelAfterInterruption() bool`

GetReAuthSecureTunnelAfterInterruption returns the ReAuthSecureTunnelAfterInterruption field if non-nil, zero value otherwise.

### GetReAuthSecureTunnelAfterInterruptionOk

`func (o *SecuritySettingsV2) GetReAuthSecureTunnelAfterInterruptionOk() (*bool, bool)`

GetReAuthSecureTunnelAfterInterruptionOk returns a tuple with the ReAuthSecureTunnelAfterInterruption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReAuthSecureTunnelAfterInterruption

`func (o *SecuritySettingsV2) SetReAuthSecureTunnelAfterInterruption(v bool)`

SetReAuthSecureTunnelAfterInterruption sets ReAuthSecureTunnelAfterInterruption field to given value.

### HasReAuthSecureTunnelAfterInterruption

`func (o *SecuritySettingsV2) HasReAuthSecureTunnelAfterInterruption() bool`

HasReAuthSecureTunnelAfterInterruption returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


