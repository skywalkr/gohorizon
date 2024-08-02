# PrivilegeInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Name of the privilege. * ADMINISTRATOR: Full administrator privilege, including Multi-Datacenter View configuration. This is a non-selectable privilege. * ADMINISTRATOR_VIEW: Full read only administrator privilege, including Multi-Datacenter View configuration. This is a non-selectable privilege. * VC_CONFIG_VIEW: Manage vCenter Configuration (Read Only). * LOG_COLLECTION: Collect Operation Logs. * FORENSICS: Manage Forensics Operations. * MANAGE_CERTIFICATES: Manage Certificates. * LOCAL_ADMINISTRATOR: Full administrator privilege, except to Multi-Datacenter View configuration and to manage roles and privileges. This is a non-selectable privilege. * LOCAL_ADMINISTRATOR_VIEW: Full read only administrator privilege, except to Multi-Datacenter View configuration. This is a non-selectable privilege. * INVENTORY_ADMINISTRATOR: Access to all inventory objects. This is a non-selectable privilege. * INVENTORY_ADMINISTRATOR_VIEW: Read only access to all inventory objects. This is a non-selectable privilege. * HELPDESK_ADMINISTRATOR: Manage Help Desk. This is a non-selectable privilege. * HELPDESK_ADMINISTRATOR_VIEW: Manage Help Desk (Read only). * FEDERATED_LDAP_MANAGE: Manage Pod Federation.  * FEDERATED_LDAP_VIEW: Manage Global LDAP (Read only). This is a non-selectable privilege. * FEDERATED_SESSIONS_MANAGE: Manage Federated Sessions. * FEDERATED_SESSIONS_VIEW: Manage Federated Sessions (Read only). This is a non-selectable privilege. * GLOBAL_ADMINISTRATOR: Manage Global Configuration. This is a non-selectable privilege. * GLOBAL_ADMINISTRATOR_VIEW: Manage Global Configuration (Read only). This is a non-selectable privilege. * GLOBAL_ADMIN_UI_INTERACTIVE: Can log into View Administrator. This is a non-selectable privilege. * GLOBAL_ADMIN_SDK_INTERACTIVE: Can run all command line utilities and PowerShell commands. This is a non-selectable privilege. * GLOBAL_MACHINE_REGISTER: Register non-vCenter machine sources such as Windows Terminal Servers and physical PCs. * GLOBAL_ROLE_PERMISSION_MANAGEMENT: Add, modify, and delete administrator roles and permissions. * GLOBAL_ROLE_MANAGEMENT: Add, modify, and delete administrator roles. This is a non-selectable privilege. * GLOBAL_ROLE_VIEW: Read only access to administrator roles. This is a non-selectable privilege. * GLOBAL_PERMISSION_VIEW: Read only access to administrator permissions. This is a non-selectable privilege. * GLOBAL_PERMISSION_MANAGEMENT: Add, modify, and delete administrator permissions. This is a non-selectable privilege. * GLOBAL_CONFIG_VIEW: Read only access to global (non-inventory) policy, configuration, and RDS server settings, except administrator roles and permissions and global (Multi-Datacenter View) LDAP. This is a non-selectable privilege. * GLOBAL_CONFIG_MANAGEMENT: View and change global (non-inventory) policy, configuration, and RDS server settings, except for administrator roles and permissions. * FOLDER_MANAGEMENT: Add, modify, and delete access groups. * FOLDER_VIEW: Read only access to access groups. This is a non-selectable privilege. * POOL_VIEW: Read only access to desktop pools, farms, applications, their local sessions, and their machines. This is a non-selectable privilege. * POOL_MANAGEMENT: Add, modify, and delete desktop pools, applications and farms. Add and remove machines from desktop pools. * POOL_ENABLE: Enable and disable desktop pools, farms, and applications. * POOL_ENTITLE: Add and remove desktop pool and application entitlements. * POOL_SVI_IMAGE_MANAGEMENT: Schedule push image, schedule maintenance and change default image for desktop pool and farm. * MACHINE_VIEW: Read only access to machines and their local sessions. This is a non-selectable privilege. * MACHINE_MANAGEMENT: Perform all machine and session-related commands. * MACHINE_REBOOT: Reset local machines. * MACHINE_MANAGE_VDI_SESSION: Disconnect, logoff, and send messages to local sessions. * MACHINE_MANAGE_OFFLINE_SESSION: Roll back offline sessions and initiate replications. * MACHINE_USER_MANAGEMENT: Assign and un-assign users for machines, Update machine aliases for machines. * MACHINE_MAINTENANCE: Put machine in and out of maintenance mode. * MANAGE_REMOTE_PROCESS: Manage Remote Processes and Applications. * REMOTE_ASSISTANCE: Remote Assistance to Remote desktop pool. * GLOBAL_CVP_REGISTER: Global CVP Register. This is a non-selectable privilege. * GLOBAL_CVP_PUBLICATION: Global CVP Publication. This is a non-selectable privilege. * CVP_INTERACTIVE: CVP Interactive. This is a non-selectable privilege. * CVP_VIEW: CVP View. This is a non-selectable privilege. * CVP_MANAGEMENT: CVP Management.This is a non-selectable privilege. * CVP_OWNERSHIP: CVP Ownership.This is a non-selectable privilege. * API_SMART_CARD_BYPASS: Allows API&#39;s credential based login when smart card authentication mode is REQUIRED. * UNKNOWN_PRIVILEGE: Unknown Privilege type. This is a non-selectable privilege. | [optional] 
**SubPrivileges** | Pointer to **[]string** | List of sub-privileges. | [optional] 

## Methods

### NewPrivilegeInfo

`func NewPrivilegeInfo() *PrivilegeInfo`

NewPrivilegeInfo instantiates a new PrivilegeInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPrivilegeInfoWithDefaults

`func NewPrivilegeInfoWithDefaults() *PrivilegeInfo`

NewPrivilegeInfoWithDefaults instantiates a new PrivilegeInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PrivilegeInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PrivilegeInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PrivilegeInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PrivilegeInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSubPrivileges

`func (o *PrivilegeInfo) GetSubPrivileges() []string`

GetSubPrivileges returns the SubPrivileges field if non-nil, zero value otherwise.

### GetSubPrivilegesOk

`func (o *PrivilegeInfo) GetSubPrivilegesOk() (*[]string, bool)`

GetSubPrivilegesOk returns a tuple with the SubPrivileges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubPrivileges

`func (o *PrivilegeInfo) SetSubPrivileges(v []string)`

SetSubPrivileges sets SubPrivileges field to given value.

### HasSubPrivileges

`func (o *PrivilegeInfo) HasSubPrivileges() bool`

HasSubPrivileges returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


