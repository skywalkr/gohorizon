# GeneralSettingsV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationSsoTimeoutMinutes** | Pointer to **int32** | The time allowed to elapse after a user has authenticated before the application SSO credentials are locked unless the user&#39;s Horizon client supports idle sessions and the user remains active. | [optional] 
**ApplicationSsoTimeoutPolicy** | Pointer to **string** | Specifies the policy for the maximum time after which single sign on will be disabled for application sessions. * DISABLED_AFTER: Single sign on will be disabled after the specified number of minutes has elapsed since the user connected to Horizon Connection Server. * DISABLED: Single sign on is disabled. * ENABLED: Single sign on is enabled. | [optional] 
**BlockRestrictedClients** | Pointer to **bool** | Indicates whether Horizon Client Connections are to be blocked if client is not part of restricted_client_data. | [optional] 
**ClientIdleSessionTimeoutMinutes** | Pointer to **int32** | Determines how long a user can be idle before the Connection Server takes measure to protect the session. | [optional] 
**ClientIdleSessionTimeoutPolicy** | Pointer to **string** | Specifies the policy for the maximum time that a that a user can be idle before the Connection Server takes measure to protect the session. * TIMEOUT_AFTER: The timeout is set for a configurable time. * NEVER: The timeout has been disabled. | [optional] 
**ClientMaxSessionTimeoutMinutes** | Pointer to **int32** | Determines how long a user can keep a session open after logging in to the Connection Server. When a session times out, the session is terminated and the Horizon client is disconnected from the resource. This property has a default value of 600 and a minimum value of 5. This property is required if clientMaxSessionTimeoutPolicy is set to TIMEOUT_AFTER. | [optional] 
**ClientMaxSessionTimeoutPolicy** | Pointer to **string** | Client max session lifetime policy. This property has a default value of TIMEOUT_AFTER. A value of TIMEOUT_AFTER indicates that the Horizon client session times out after a configurable session length. A value of NEVER indicates that the Horizon client session will not time out and will only end due to inactivity. * TIMEOUT_AFTER: The timeout is set for a configurable time. * NEVER: The timeout has been disabled. | [optional] 
**ClientSessionTimeoutMinutes** | Pointer to **int32** | Determines the maximum length of time that a session will be kept active if there is no traffic between the Horizon client and the Connection Server. | [optional] 
**ConsoleSessionTimeoutMinutes** | Pointer to **int32** | Determines how long an idle admin console session continues before the session times out. | [optional] 
**DisplayPreLoginMessage** | Pointer to **bool** | Indicates whether to show a disclaimer or other message when the Horizon Client user logs in. This change will take effect on next login for each user. | [optional] 
**DisplayWarningBeforeForcedLogoff** | Pointer to **bool** | Indicates whether to display a warning message when users are forced to log off because a scheduled or immediate update such as a machine-refresh operation is about to start. | [optional] 
**EnableAutomaticStatusUpdates** | Pointer to **bool** | Enable updation of the global status of the application periodically. The Dashboard Information is also updated at regular intervals when Dashboard page is active. | [optional] 
**EnableCredentialCleanupForHtmlaccess** | Pointer to **bool** | Indicates whether to clean up session credentials when one tab connecting to remote machine/application is closed. | [optional] 
**EnableMultiFactorReAuthentication** | Pointer to **bool** | Enables 2 factor re-authentication after idle session timeout. | [optional] 
**EnableSendingDomainList** | Pointer to **bool** | Indicates whether the domain list will be sent to the Horizon client. Since domain list will be sent before user is authenticated with server, it could disclose domain information to external users. | [optional] 
**EnableServerInSingleUserMode** | Pointer to **bool** | Permits RDSServer operating systems to be used for non-RDS Machines. | [optional] 
**ForcedLogoffMessage** | Pointer to **string** | The warning to be displayed before logging off the user. | [optional] 
**ForcedLogoffTimeoutMinutes** | Pointer to **int32** | The time to wait after the warning is displayed and before logging off the user. | [optional] 
**HideDomainListInClient** | Pointer to **bool** | Whether to hide the list of domains in the Horizon client user interface. If value set to true, the user will need to provide a UPN (e.g. user@domain) or a logon name in the format domain\\\\user when logging in. | [optional] 
**HideServerInformationInClient** | Pointer to **bool** | Indicates whether to hide the server URL in the Horizon client user interface. | [optional] 
**MachineSsoTimeoutMinutes** | Pointer to **int32** | Single sign on will be disabled after the specified time has elapsed since the user connected to Connection Server. | [optional] 
**MachineSsoTimeoutPolicy** | Pointer to **string** | Specifies the policy for the maximum time after which single sign on will be disabled after a user connects to the Connection Server. * DISABLED_AFTER: Single sign on will be disabled after the specified number of minutes has elapsed since the user connected to Horizon Connection Server. * DISABLED: Single sign on is disabled. * ENABLED: Single sign on is enabled. | [optional] 
**PreLoginMessage** | Pointer to **string** | Displays a disclaimer or another message to Horizon Client users when they log in. No message will be displayed if this is not set. | [optional] 
**RestrictedClientDataV2** | Pointer to [**[]RestrictedClientDataV2**](RestrictedClientDataV2.md) | List of restricted Horizon Clients. | [optional] 
**RestrictedClientMessage** | Pointer to **string** | The message to be displayed to Horizon clients which are blocked by the Connection Server. | [optional] 
**RestrictedClientWarnMessage** | Pointer to **string** | The message to be displayed to Horizon clients which are not recommended by the Connection Server. | [optional] 
**StoreCalOnClient** | Pointer to **bool** | Determines whether or not to store the RDS Per Device Client Access License on Horizon client devices. This value can be true only if Store Client Access License on Connection Server is true. | [optional] 
**StoreCalOnConnectionServer** | Pointer to **bool** | Determines whether or not to store the RDS Per Device Client Access License on Connection Server. | [optional] 

## Methods

### NewGeneralSettingsV2

`func NewGeneralSettingsV2() *GeneralSettingsV2`

NewGeneralSettingsV2 instantiates a new GeneralSettingsV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeneralSettingsV2WithDefaults

`func NewGeneralSettingsV2WithDefaults() *GeneralSettingsV2`

NewGeneralSettingsV2WithDefaults instantiates a new GeneralSettingsV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationSsoTimeoutMinutes

`func (o *GeneralSettingsV2) GetApplicationSsoTimeoutMinutes() int32`

GetApplicationSsoTimeoutMinutes returns the ApplicationSsoTimeoutMinutes field if non-nil, zero value otherwise.

### GetApplicationSsoTimeoutMinutesOk

`func (o *GeneralSettingsV2) GetApplicationSsoTimeoutMinutesOk() (*int32, bool)`

GetApplicationSsoTimeoutMinutesOk returns a tuple with the ApplicationSsoTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationSsoTimeoutMinutes

`func (o *GeneralSettingsV2) SetApplicationSsoTimeoutMinutes(v int32)`

SetApplicationSsoTimeoutMinutes sets ApplicationSsoTimeoutMinutes field to given value.

### HasApplicationSsoTimeoutMinutes

`func (o *GeneralSettingsV2) HasApplicationSsoTimeoutMinutes() bool`

HasApplicationSsoTimeoutMinutes returns a boolean if a field has been set.

### GetApplicationSsoTimeoutPolicy

`func (o *GeneralSettingsV2) GetApplicationSsoTimeoutPolicy() string`

GetApplicationSsoTimeoutPolicy returns the ApplicationSsoTimeoutPolicy field if non-nil, zero value otherwise.

### GetApplicationSsoTimeoutPolicyOk

`func (o *GeneralSettingsV2) GetApplicationSsoTimeoutPolicyOk() (*string, bool)`

GetApplicationSsoTimeoutPolicyOk returns a tuple with the ApplicationSsoTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationSsoTimeoutPolicy

`func (o *GeneralSettingsV2) SetApplicationSsoTimeoutPolicy(v string)`

SetApplicationSsoTimeoutPolicy sets ApplicationSsoTimeoutPolicy field to given value.

### HasApplicationSsoTimeoutPolicy

`func (o *GeneralSettingsV2) HasApplicationSsoTimeoutPolicy() bool`

HasApplicationSsoTimeoutPolicy returns a boolean if a field has been set.

### GetBlockRestrictedClients

`func (o *GeneralSettingsV2) GetBlockRestrictedClients() bool`

GetBlockRestrictedClients returns the BlockRestrictedClients field if non-nil, zero value otherwise.

### GetBlockRestrictedClientsOk

`func (o *GeneralSettingsV2) GetBlockRestrictedClientsOk() (*bool, bool)`

GetBlockRestrictedClientsOk returns a tuple with the BlockRestrictedClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockRestrictedClients

`func (o *GeneralSettingsV2) SetBlockRestrictedClients(v bool)`

SetBlockRestrictedClients sets BlockRestrictedClients field to given value.

### HasBlockRestrictedClients

`func (o *GeneralSettingsV2) HasBlockRestrictedClients() bool`

HasBlockRestrictedClients returns a boolean if a field has been set.

### GetClientIdleSessionTimeoutMinutes

`func (o *GeneralSettingsV2) GetClientIdleSessionTimeoutMinutes() int32`

GetClientIdleSessionTimeoutMinutes returns the ClientIdleSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetClientIdleSessionTimeoutMinutesOk

`func (o *GeneralSettingsV2) GetClientIdleSessionTimeoutMinutesOk() (*int32, bool)`

GetClientIdleSessionTimeoutMinutesOk returns a tuple with the ClientIdleSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIdleSessionTimeoutMinutes

`func (o *GeneralSettingsV2) SetClientIdleSessionTimeoutMinutes(v int32)`

SetClientIdleSessionTimeoutMinutes sets ClientIdleSessionTimeoutMinutes field to given value.

### HasClientIdleSessionTimeoutMinutes

`func (o *GeneralSettingsV2) HasClientIdleSessionTimeoutMinutes() bool`

HasClientIdleSessionTimeoutMinutes returns a boolean if a field has been set.

### GetClientIdleSessionTimeoutPolicy

`func (o *GeneralSettingsV2) GetClientIdleSessionTimeoutPolicy() string`

GetClientIdleSessionTimeoutPolicy returns the ClientIdleSessionTimeoutPolicy field if non-nil, zero value otherwise.

### GetClientIdleSessionTimeoutPolicyOk

`func (o *GeneralSettingsV2) GetClientIdleSessionTimeoutPolicyOk() (*string, bool)`

GetClientIdleSessionTimeoutPolicyOk returns a tuple with the ClientIdleSessionTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIdleSessionTimeoutPolicy

`func (o *GeneralSettingsV2) SetClientIdleSessionTimeoutPolicy(v string)`

SetClientIdleSessionTimeoutPolicy sets ClientIdleSessionTimeoutPolicy field to given value.

### HasClientIdleSessionTimeoutPolicy

`func (o *GeneralSettingsV2) HasClientIdleSessionTimeoutPolicy() bool`

HasClientIdleSessionTimeoutPolicy returns a boolean if a field has been set.

### GetClientMaxSessionTimeoutMinutes

`func (o *GeneralSettingsV2) GetClientMaxSessionTimeoutMinutes() int32`

GetClientMaxSessionTimeoutMinutes returns the ClientMaxSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetClientMaxSessionTimeoutMinutesOk

`func (o *GeneralSettingsV2) GetClientMaxSessionTimeoutMinutesOk() (*int32, bool)`

GetClientMaxSessionTimeoutMinutesOk returns a tuple with the ClientMaxSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientMaxSessionTimeoutMinutes

`func (o *GeneralSettingsV2) SetClientMaxSessionTimeoutMinutes(v int32)`

SetClientMaxSessionTimeoutMinutes sets ClientMaxSessionTimeoutMinutes field to given value.

### HasClientMaxSessionTimeoutMinutes

`func (o *GeneralSettingsV2) HasClientMaxSessionTimeoutMinutes() bool`

HasClientMaxSessionTimeoutMinutes returns a boolean if a field has been set.

### GetClientMaxSessionTimeoutPolicy

`func (o *GeneralSettingsV2) GetClientMaxSessionTimeoutPolicy() string`

GetClientMaxSessionTimeoutPolicy returns the ClientMaxSessionTimeoutPolicy field if non-nil, zero value otherwise.

### GetClientMaxSessionTimeoutPolicyOk

`func (o *GeneralSettingsV2) GetClientMaxSessionTimeoutPolicyOk() (*string, bool)`

GetClientMaxSessionTimeoutPolicyOk returns a tuple with the ClientMaxSessionTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientMaxSessionTimeoutPolicy

`func (o *GeneralSettingsV2) SetClientMaxSessionTimeoutPolicy(v string)`

SetClientMaxSessionTimeoutPolicy sets ClientMaxSessionTimeoutPolicy field to given value.

### HasClientMaxSessionTimeoutPolicy

`func (o *GeneralSettingsV2) HasClientMaxSessionTimeoutPolicy() bool`

HasClientMaxSessionTimeoutPolicy returns a boolean if a field has been set.

### GetClientSessionTimeoutMinutes

`func (o *GeneralSettingsV2) GetClientSessionTimeoutMinutes() int32`

GetClientSessionTimeoutMinutes returns the ClientSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetClientSessionTimeoutMinutesOk

`func (o *GeneralSettingsV2) GetClientSessionTimeoutMinutesOk() (*int32, bool)`

GetClientSessionTimeoutMinutesOk returns a tuple with the ClientSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSessionTimeoutMinutes

`func (o *GeneralSettingsV2) SetClientSessionTimeoutMinutes(v int32)`

SetClientSessionTimeoutMinutes sets ClientSessionTimeoutMinutes field to given value.

### HasClientSessionTimeoutMinutes

`func (o *GeneralSettingsV2) HasClientSessionTimeoutMinutes() bool`

HasClientSessionTimeoutMinutes returns a boolean if a field has been set.

### GetConsoleSessionTimeoutMinutes

`func (o *GeneralSettingsV2) GetConsoleSessionTimeoutMinutes() int32`

GetConsoleSessionTimeoutMinutes returns the ConsoleSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetConsoleSessionTimeoutMinutesOk

`func (o *GeneralSettingsV2) GetConsoleSessionTimeoutMinutesOk() (*int32, bool)`

GetConsoleSessionTimeoutMinutesOk returns a tuple with the ConsoleSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsoleSessionTimeoutMinutes

`func (o *GeneralSettingsV2) SetConsoleSessionTimeoutMinutes(v int32)`

SetConsoleSessionTimeoutMinutes sets ConsoleSessionTimeoutMinutes field to given value.

### HasConsoleSessionTimeoutMinutes

`func (o *GeneralSettingsV2) HasConsoleSessionTimeoutMinutes() bool`

HasConsoleSessionTimeoutMinutes returns a boolean if a field has been set.

### GetDisplayPreLoginMessage

`func (o *GeneralSettingsV2) GetDisplayPreLoginMessage() bool`

GetDisplayPreLoginMessage returns the DisplayPreLoginMessage field if non-nil, zero value otherwise.

### GetDisplayPreLoginMessageOk

`func (o *GeneralSettingsV2) GetDisplayPreLoginMessageOk() (*bool, bool)`

GetDisplayPreLoginMessageOk returns a tuple with the DisplayPreLoginMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayPreLoginMessage

`func (o *GeneralSettingsV2) SetDisplayPreLoginMessage(v bool)`

SetDisplayPreLoginMessage sets DisplayPreLoginMessage field to given value.

### HasDisplayPreLoginMessage

`func (o *GeneralSettingsV2) HasDisplayPreLoginMessage() bool`

HasDisplayPreLoginMessage returns a boolean if a field has been set.

### GetDisplayWarningBeforeForcedLogoff

`func (o *GeneralSettingsV2) GetDisplayWarningBeforeForcedLogoff() bool`

GetDisplayWarningBeforeForcedLogoff returns the DisplayWarningBeforeForcedLogoff field if non-nil, zero value otherwise.

### GetDisplayWarningBeforeForcedLogoffOk

`func (o *GeneralSettingsV2) GetDisplayWarningBeforeForcedLogoffOk() (*bool, bool)`

GetDisplayWarningBeforeForcedLogoffOk returns a tuple with the DisplayWarningBeforeForcedLogoff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayWarningBeforeForcedLogoff

`func (o *GeneralSettingsV2) SetDisplayWarningBeforeForcedLogoff(v bool)`

SetDisplayWarningBeforeForcedLogoff sets DisplayWarningBeforeForcedLogoff field to given value.

### HasDisplayWarningBeforeForcedLogoff

`func (o *GeneralSettingsV2) HasDisplayWarningBeforeForcedLogoff() bool`

HasDisplayWarningBeforeForcedLogoff returns a boolean if a field has been set.

### GetEnableAutomaticStatusUpdates

`func (o *GeneralSettingsV2) GetEnableAutomaticStatusUpdates() bool`

GetEnableAutomaticStatusUpdates returns the EnableAutomaticStatusUpdates field if non-nil, zero value otherwise.

### GetEnableAutomaticStatusUpdatesOk

`func (o *GeneralSettingsV2) GetEnableAutomaticStatusUpdatesOk() (*bool, bool)`

GetEnableAutomaticStatusUpdatesOk returns a tuple with the EnableAutomaticStatusUpdates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableAutomaticStatusUpdates

`func (o *GeneralSettingsV2) SetEnableAutomaticStatusUpdates(v bool)`

SetEnableAutomaticStatusUpdates sets EnableAutomaticStatusUpdates field to given value.

### HasEnableAutomaticStatusUpdates

`func (o *GeneralSettingsV2) HasEnableAutomaticStatusUpdates() bool`

HasEnableAutomaticStatusUpdates returns a boolean if a field has been set.

### GetEnableCredentialCleanupForHtmlaccess

`func (o *GeneralSettingsV2) GetEnableCredentialCleanupForHtmlaccess() bool`

GetEnableCredentialCleanupForHtmlaccess returns the EnableCredentialCleanupForHtmlaccess field if non-nil, zero value otherwise.

### GetEnableCredentialCleanupForHtmlaccessOk

`func (o *GeneralSettingsV2) GetEnableCredentialCleanupForHtmlaccessOk() (*bool, bool)`

GetEnableCredentialCleanupForHtmlaccessOk returns a tuple with the EnableCredentialCleanupForHtmlaccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableCredentialCleanupForHtmlaccess

`func (o *GeneralSettingsV2) SetEnableCredentialCleanupForHtmlaccess(v bool)`

SetEnableCredentialCleanupForHtmlaccess sets EnableCredentialCleanupForHtmlaccess field to given value.

### HasEnableCredentialCleanupForHtmlaccess

`func (o *GeneralSettingsV2) HasEnableCredentialCleanupForHtmlaccess() bool`

HasEnableCredentialCleanupForHtmlaccess returns a boolean if a field has been set.

### GetEnableMultiFactorReAuthentication

`func (o *GeneralSettingsV2) GetEnableMultiFactorReAuthentication() bool`

GetEnableMultiFactorReAuthentication returns the EnableMultiFactorReAuthentication field if non-nil, zero value otherwise.

### GetEnableMultiFactorReAuthenticationOk

`func (o *GeneralSettingsV2) GetEnableMultiFactorReAuthenticationOk() (*bool, bool)`

GetEnableMultiFactorReAuthenticationOk returns a tuple with the EnableMultiFactorReAuthentication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableMultiFactorReAuthentication

`func (o *GeneralSettingsV2) SetEnableMultiFactorReAuthentication(v bool)`

SetEnableMultiFactorReAuthentication sets EnableMultiFactorReAuthentication field to given value.

### HasEnableMultiFactorReAuthentication

`func (o *GeneralSettingsV2) HasEnableMultiFactorReAuthentication() bool`

HasEnableMultiFactorReAuthentication returns a boolean if a field has been set.

### GetEnableSendingDomainList

`func (o *GeneralSettingsV2) GetEnableSendingDomainList() bool`

GetEnableSendingDomainList returns the EnableSendingDomainList field if non-nil, zero value otherwise.

### GetEnableSendingDomainListOk

`func (o *GeneralSettingsV2) GetEnableSendingDomainListOk() (*bool, bool)`

GetEnableSendingDomainListOk returns a tuple with the EnableSendingDomainList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableSendingDomainList

`func (o *GeneralSettingsV2) SetEnableSendingDomainList(v bool)`

SetEnableSendingDomainList sets EnableSendingDomainList field to given value.

### HasEnableSendingDomainList

`func (o *GeneralSettingsV2) HasEnableSendingDomainList() bool`

HasEnableSendingDomainList returns a boolean if a field has been set.

### GetEnableServerInSingleUserMode

`func (o *GeneralSettingsV2) GetEnableServerInSingleUserMode() bool`

GetEnableServerInSingleUserMode returns the EnableServerInSingleUserMode field if non-nil, zero value otherwise.

### GetEnableServerInSingleUserModeOk

`func (o *GeneralSettingsV2) GetEnableServerInSingleUserModeOk() (*bool, bool)`

GetEnableServerInSingleUserModeOk returns a tuple with the EnableServerInSingleUserMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableServerInSingleUserMode

`func (o *GeneralSettingsV2) SetEnableServerInSingleUserMode(v bool)`

SetEnableServerInSingleUserMode sets EnableServerInSingleUserMode field to given value.

### HasEnableServerInSingleUserMode

`func (o *GeneralSettingsV2) HasEnableServerInSingleUserMode() bool`

HasEnableServerInSingleUserMode returns a boolean if a field has been set.

### GetForcedLogoffMessage

`func (o *GeneralSettingsV2) GetForcedLogoffMessage() string`

GetForcedLogoffMessage returns the ForcedLogoffMessage field if non-nil, zero value otherwise.

### GetForcedLogoffMessageOk

`func (o *GeneralSettingsV2) GetForcedLogoffMessageOk() (*string, bool)`

GetForcedLogoffMessageOk returns a tuple with the ForcedLogoffMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForcedLogoffMessage

`func (o *GeneralSettingsV2) SetForcedLogoffMessage(v string)`

SetForcedLogoffMessage sets ForcedLogoffMessage field to given value.

### HasForcedLogoffMessage

`func (o *GeneralSettingsV2) HasForcedLogoffMessage() bool`

HasForcedLogoffMessage returns a boolean if a field has been set.

### GetForcedLogoffTimeoutMinutes

`func (o *GeneralSettingsV2) GetForcedLogoffTimeoutMinutes() int32`

GetForcedLogoffTimeoutMinutes returns the ForcedLogoffTimeoutMinutes field if non-nil, zero value otherwise.

### GetForcedLogoffTimeoutMinutesOk

`func (o *GeneralSettingsV2) GetForcedLogoffTimeoutMinutesOk() (*int32, bool)`

GetForcedLogoffTimeoutMinutesOk returns a tuple with the ForcedLogoffTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForcedLogoffTimeoutMinutes

`func (o *GeneralSettingsV2) SetForcedLogoffTimeoutMinutes(v int32)`

SetForcedLogoffTimeoutMinutes sets ForcedLogoffTimeoutMinutes field to given value.

### HasForcedLogoffTimeoutMinutes

`func (o *GeneralSettingsV2) HasForcedLogoffTimeoutMinutes() bool`

HasForcedLogoffTimeoutMinutes returns a boolean if a field has been set.

### GetHideDomainListInClient

`func (o *GeneralSettingsV2) GetHideDomainListInClient() bool`

GetHideDomainListInClient returns the HideDomainListInClient field if non-nil, zero value otherwise.

### GetHideDomainListInClientOk

`func (o *GeneralSettingsV2) GetHideDomainListInClientOk() (*bool, bool)`

GetHideDomainListInClientOk returns a tuple with the HideDomainListInClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHideDomainListInClient

`func (o *GeneralSettingsV2) SetHideDomainListInClient(v bool)`

SetHideDomainListInClient sets HideDomainListInClient field to given value.

### HasHideDomainListInClient

`func (o *GeneralSettingsV2) HasHideDomainListInClient() bool`

HasHideDomainListInClient returns a boolean if a field has been set.

### GetHideServerInformationInClient

`func (o *GeneralSettingsV2) GetHideServerInformationInClient() bool`

GetHideServerInformationInClient returns the HideServerInformationInClient field if non-nil, zero value otherwise.

### GetHideServerInformationInClientOk

`func (o *GeneralSettingsV2) GetHideServerInformationInClientOk() (*bool, bool)`

GetHideServerInformationInClientOk returns a tuple with the HideServerInformationInClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHideServerInformationInClient

`func (o *GeneralSettingsV2) SetHideServerInformationInClient(v bool)`

SetHideServerInformationInClient sets HideServerInformationInClient field to given value.

### HasHideServerInformationInClient

`func (o *GeneralSettingsV2) HasHideServerInformationInClient() bool`

HasHideServerInformationInClient returns a boolean if a field has been set.

### GetMachineSsoTimeoutMinutes

`func (o *GeneralSettingsV2) GetMachineSsoTimeoutMinutes() int32`

GetMachineSsoTimeoutMinutes returns the MachineSsoTimeoutMinutes field if non-nil, zero value otherwise.

### GetMachineSsoTimeoutMinutesOk

`func (o *GeneralSettingsV2) GetMachineSsoTimeoutMinutesOk() (*int32, bool)`

GetMachineSsoTimeoutMinutesOk returns a tuple with the MachineSsoTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineSsoTimeoutMinutes

`func (o *GeneralSettingsV2) SetMachineSsoTimeoutMinutes(v int32)`

SetMachineSsoTimeoutMinutes sets MachineSsoTimeoutMinutes field to given value.

### HasMachineSsoTimeoutMinutes

`func (o *GeneralSettingsV2) HasMachineSsoTimeoutMinutes() bool`

HasMachineSsoTimeoutMinutes returns a boolean if a field has been set.

### GetMachineSsoTimeoutPolicy

`func (o *GeneralSettingsV2) GetMachineSsoTimeoutPolicy() string`

GetMachineSsoTimeoutPolicy returns the MachineSsoTimeoutPolicy field if non-nil, zero value otherwise.

### GetMachineSsoTimeoutPolicyOk

`func (o *GeneralSettingsV2) GetMachineSsoTimeoutPolicyOk() (*string, bool)`

GetMachineSsoTimeoutPolicyOk returns a tuple with the MachineSsoTimeoutPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineSsoTimeoutPolicy

`func (o *GeneralSettingsV2) SetMachineSsoTimeoutPolicy(v string)`

SetMachineSsoTimeoutPolicy sets MachineSsoTimeoutPolicy field to given value.

### HasMachineSsoTimeoutPolicy

`func (o *GeneralSettingsV2) HasMachineSsoTimeoutPolicy() bool`

HasMachineSsoTimeoutPolicy returns a boolean if a field has been set.

### GetPreLoginMessage

`func (o *GeneralSettingsV2) GetPreLoginMessage() string`

GetPreLoginMessage returns the PreLoginMessage field if non-nil, zero value otherwise.

### GetPreLoginMessageOk

`func (o *GeneralSettingsV2) GetPreLoginMessageOk() (*string, bool)`

GetPreLoginMessageOk returns a tuple with the PreLoginMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreLoginMessage

`func (o *GeneralSettingsV2) SetPreLoginMessage(v string)`

SetPreLoginMessage sets PreLoginMessage field to given value.

### HasPreLoginMessage

`func (o *GeneralSettingsV2) HasPreLoginMessage() bool`

HasPreLoginMessage returns a boolean if a field has been set.

### GetRestrictedClientDataV2

`func (o *GeneralSettingsV2) GetRestrictedClientDataV2() []RestrictedClientDataV2`

GetRestrictedClientDataV2 returns the RestrictedClientDataV2 field if non-nil, zero value otherwise.

### GetRestrictedClientDataV2Ok

`func (o *GeneralSettingsV2) GetRestrictedClientDataV2Ok() (*[]RestrictedClientDataV2, bool)`

GetRestrictedClientDataV2Ok returns a tuple with the RestrictedClientDataV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictedClientDataV2

`func (o *GeneralSettingsV2) SetRestrictedClientDataV2(v []RestrictedClientDataV2)`

SetRestrictedClientDataV2 sets RestrictedClientDataV2 field to given value.

### HasRestrictedClientDataV2

`func (o *GeneralSettingsV2) HasRestrictedClientDataV2() bool`

HasRestrictedClientDataV2 returns a boolean if a field has been set.

### GetRestrictedClientMessage

`func (o *GeneralSettingsV2) GetRestrictedClientMessage() string`

GetRestrictedClientMessage returns the RestrictedClientMessage field if non-nil, zero value otherwise.

### GetRestrictedClientMessageOk

`func (o *GeneralSettingsV2) GetRestrictedClientMessageOk() (*string, bool)`

GetRestrictedClientMessageOk returns a tuple with the RestrictedClientMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictedClientMessage

`func (o *GeneralSettingsV2) SetRestrictedClientMessage(v string)`

SetRestrictedClientMessage sets RestrictedClientMessage field to given value.

### HasRestrictedClientMessage

`func (o *GeneralSettingsV2) HasRestrictedClientMessage() bool`

HasRestrictedClientMessage returns a boolean if a field has been set.

### GetRestrictedClientWarnMessage

`func (o *GeneralSettingsV2) GetRestrictedClientWarnMessage() string`

GetRestrictedClientWarnMessage returns the RestrictedClientWarnMessage field if non-nil, zero value otherwise.

### GetRestrictedClientWarnMessageOk

`func (o *GeneralSettingsV2) GetRestrictedClientWarnMessageOk() (*string, bool)`

GetRestrictedClientWarnMessageOk returns a tuple with the RestrictedClientWarnMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictedClientWarnMessage

`func (o *GeneralSettingsV2) SetRestrictedClientWarnMessage(v string)`

SetRestrictedClientWarnMessage sets RestrictedClientWarnMessage field to given value.

### HasRestrictedClientWarnMessage

`func (o *GeneralSettingsV2) HasRestrictedClientWarnMessage() bool`

HasRestrictedClientWarnMessage returns a boolean if a field has been set.

### GetStoreCalOnClient

`func (o *GeneralSettingsV2) GetStoreCalOnClient() bool`

GetStoreCalOnClient returns the StoreCalOnClient field if non-nil, zero value otherwise.

### GetStoreCalOnClientOk

`func (o *GeneralSettingsV2) GetStoreCalOnClientOk() (*bool, bool)`

GetStoreCalOnClientOk returns a tuple with the StoreCalOnClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreCalOnClient

`func (o *GeneralSettingsV2) SetStoreCalOnClient(v bool)`

SetStoreCalOnClient sets StoreCalOnClient field to given value.

### HasStoreCalOnClient

`func (o *GeneralSettingsV2) HasStoreCalOnClient() bool`

HasStoreCalOnClient returns a boolean if a field has been set.

### GetStoreCalOnConnectionServer

`func (o *GeneralSettingsV2) GetStoreCalOnConnectionServer() bool`

GetStoreCalOnConnectionServer returns the StoreCalOnConnectionServer field if non-nil, zero value otherwise.

### GetStoreCalOnConnectionServerOk

`func (o *GeneralSettingsV2) GetStoreCalOnConnectionServerOk() (*bool, bool)`

GetStoreCalOnConnectionServerOk returns a tuple with the StoreCalOnConnectionServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreCalOnConnectionServer

`func (o *GeneralSettingsV2) SetStoreCalOnConnectionServer(v bool)`

SetStoreCalOnConnectionServer sets StoreCalOnConnectionServer field to given value.

### HasStoreCalOnConnectionServer

`func (o *GeneralSettingsV2) HasStoreCalOnConnectionServer() bool`

HasStoreCalOnConnectionServer returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


