# DesktopPoolCreateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessGroupId** | Pointer to **string** | Access groups can organize the entities such as desktop pools in the organization. They can also be used for delegated administration. &lt;br&gt; This property is required for all the pools except for RDS desktop pool, which will be inherited from the corresponding Farm. | [optional] 
**AllowMultipleUserAssignments** | Pointer to **bool** | Applicable To: Dedicated manual and automated desktop pools with manual user assignment with default value as false.&lt;br&gt;Whether assignment of multiple users to a single machine is allowed.&lt;br&gt;If this is true then automatic_user_assignment should be false. &lt;br&gt; | [optional] 
**AllowRdsPoolMultiSessionPerUser** | Pointer to **bool** | Applicable To: RDS desktop pools with default value as false.&lt;br&gt;Indicates whether multiple sessions are allowed per user for this pool.For other desktop pools, allow_multiple_sessions_per_user from session_settings will be applicable. &lt;br&gt; | [optional] 
**AutomaticUserAssignment** | Pointer to **bool** | Automatic assignment of a user the first time they access the machine.&lt;br&gt;This property is applicable if user_assignment is set to DEDICATED with default value as true.&lt;br&gt; | [optional] 
**CategoryFolderName** | Pointer to **string** | Name of the category folder in the user&#39;s OS containing a shortcut to the desktop pool.Will be unset if the desktop does not belong to a category.This property defines valid folder names with a max length of 64 characters and up to 4 subdirectory levels.The subdirectories can be specified using a backslash, e.g. (dir1\\dir2\\dir3\\dir4). Folder names can&#39;t start orend with a backslash nor can there be 2 or more backslashes together. Combinations such as(\\dir1, dir1\\dir2\\, dir1\\\\\\dir2, dir1\\\\\\\\\\dir2) are invalid. The windows reserved keywords(CON, PRN, NUL, AUX, COM1 - COM9, LPT1 - LPT9 etc.) are not allowed in subdirectory names. | [optional] 
**CloudAssigned** | Pointer to **bool** | Indicates whether this desktop is assigned to a workspace in Horizon Cloud Services.&lt;br&gt;This can be set to true from cloud session only and only when cloud_managed is set to true.&lt;br&gt;Default value is false. &lt;br&gt; | [optional] 
**CloudBrokered** | Pointer to **bool** | Applicable To: RDS Desktop Pools with default value as false. | [optional] 
**CloudManaged** | Pointer to **bool** | Indicates whether this desktop is managed by Horizon Cloud Services. This can be set to false only when cloud_assigned is set to false.&lt;br&gt;Default value is false. &lt;br&gt;This property cannot be set to true, if any of the conditions are satisfied: &lt;br&gt;user is provided.&lt;br&gt;enabled is false.&lt;br&gt;supported_session_type is not DESKTOP.&lt;br&gt;global_entitlement is set.&lt;br&gt;user_assignment is DEDICATED and automatic_user_assignment is false. &lt;br&gt;Local entitlements are configured. &lt;br&gt;Any of the machines in the pool have users assigned. &lt;br&gt;cs_restriction_tags is not set. &lt;br&gt;Desktop pool type is MANUAL. | [optional] 
**CsRestrictionTags** | Pointer to **[]string** | List of Connection server restriction tags to which the access to the desktop pool is restricted. If this property is not set it indicates that desktop pool can be accessed from any connection server. | [optional] 
**CustomizationSettings** | Pointer to [**DesktopPoolCustomizationSettingsCreateSpec**](DesktopPoolCustomizationSettingsCreateSpec.md) |  | [optional] 
**Description** | Pointer to **string** | Description of the desktop pool. | [optional] 
**DisplayAssignedMachineName** | Pointer to **bool** | Applicable To: Dedicated desktop pools with default value as false.&lt;br&gt;Indicates whether users should see the hostname of the machine assigned to them instead of display_name when they connect using Horizon Client. If no machine is assigned to the user then \&quot;display_name (No machine assigned)\&quot; will be displayed in the client.&lt;br&gt; | [optional] 
**DisplayMachineAlias** | Pointer to **bool** | Applicable To: Dedicated desktop pools with default value as false.&lt;br&gt; If no machine is assigned to the user then \&quot;displayName No machine assigned)\&quot; will be displayed in the Horizon client. If both display_assigned_machine_name and this property is set to true, machine alias of the assigned machine is displayed if the user has machine alias set. Otherwise hostname will be displayed. | [optional] 
**DisplayName** | Pointer to **string** | Display name of the desktop pool. If the display name is left blank, it defaults to name. | [optional] 
**DisplayProtocolSettings** | Pointer to [**DesktopPoolDisplayProtocolSettingsCreateSpec**](DesktopPoolDisplayProtocolSettingsCreateSpec.md) |  | [optional] 
**EnableClientRestrictions** | Pointer to **bool** | Client restrictions to be applied to the desktop pool.&lt;br&gt;Default value is false. | [optional] 
**EnableProvisioning** | Pointer to **bool** | Applicable To: Automated desktop pools with default value as true.&lt;br&gt;Indicates whether provisioning is enabled.&lt;br&gt; | [optional] 
**Enabled** | Pointer to **bool** | Indicates whether the desktop pool is enabled for brokering. Default value is true. | [optional] 
**FarmId** | Pointer to **string** | Applicable To: RDS Desktop pool.&lt;br&gt;Farm is needed to create RDS desktop pool. This is required for RDS desktop pools.This Farm must not already be associated with another RDS desktop. | [optional] 
**Machines** | Pointer to **[]string** | Applicable To: Manual desktop pools. &lt;br&gt;List of machines to add to this desktop pool during creation. | [optional] 
**Name** | **string** | Name of the desktop pool. This property must contain only alphanumerics, underscores and dashes. | 
**NamingMethod** | Pointer to **string** | Applicable To: Automated desktop pool.&lt;br&gt;Naming method for the desktop pool. This is required for Automated desktop pools. * SPECIFIED: List of specified names. All provisioning is done up-front. * PATTERN: Naming pattern. | [optional] 
**Nics** | Pointer to [**[]DesktopPoolNetworkInterfaceCardSettingsCreateSpec**](DesktopPoolNetworkInterfaceCardSettingsCreateSpec.md) | Network interface card settings for machines provisioned for this desktop. | [optional] 
**PatternNamingSettings** | Pointer to [**DesktopPoolVirtualMachinePatternNamingSettingsCreateSpec**](DesktopPoolVirtualMachinePatternNamingSettingsCreateSpec.md) |  | [optional] 
**ProvisioningSettings** | Pointer to [**DesktopPoolProvisioningSettingsCreateSpecV2**](DesktopPoolProvisioningSettingsCreateSpecV2.md) |  | [optional] 
**SessionSettings** | Pointer to [**DesktopPoolSessionSettingsCreateSpec**](DesktopPoolSessionSettingsCreateSpec.md) |  | [optional] 
**SessionType** | Pointer to **string** | Applicable To: Managed desktop pools with default value as DESKTOP.&lt;br&gt; Supported session types for this desktop pool. If this property is set to APPLICATION then this desktop pool can be used for application pool creation. This will be useful when the machines in the pool support application remoting. * DESKTOP: Only desktop sessions are supported. * APPLICATION: Only application sessions are supported. * DESKTOP_AND_APPLICATION: Both desktop and application sessions are supported. | [optional] 
**ShortcutLocationsV2** | Pointer to **[]string** | Locations of the category folder in the user&#39;s OS containing a shortcut to the desktop pool. This is required if the category_folder_name is set. | [optional] 
**Source** | Pointer to **string** | Applicable To: Manual and Automated desktop pools.&lt;br&gt;Source of the Machines in this Desktop Pool. This is required for Manual and Automated desktop pools.&lt;br&gt; * INSTANT_CLONE: The Desktop Pool uses instant clone technology for provisioning the machines. Applicable for AUTOMATED type desktop pools. * LINKED_CLONE: The Desktop Pool uses linked clone technology for provisioning the machines. Applicable for AUTOMATED type desktop pools. * VIRTUAL_CENTER: The Desktop Pool uses Virtual Center as source for provisioning the machines. Applicable for AUTOMATED and MANUAL type desktop pools. * RDS: The Desktop Pool is backed by Farm. The Farm used in this Desktop Pool can be of any Source. * UNMANAGED: The Desktop Pool holds the non-vCenter source machines that includes physical computers, blade PCs and non-vCenter servers. Applicable for MANUAL type desktop pools. | [optional] 
**SpecificNamingSettings** | Pointer to [**DesktopPoolVirtualMachineSpecifiedNamingSettingsCreateSpec**](DesktopPoolVirtualMachineSpecifiedNamingSettingsCreateSpec.md) |  | [optional] 
**StopProvisioningOnError** | Pointer to **bool** | Applicable for Automated pools only with default value as true. | [optional] 
**StorageSettings** | Pointer to [**DesktopPoolStorageSettingsCreateSpec**](DesktopPoolStorageSettingsCreateSpec.md) |  | [optional] 
**TransparentPageSharingScope** | Pointer to **string** | Applicable To: Managed Manual and Automated desktop pools with default value as VM.&lt;br&gt;Transparent page sharing scope for this Desktop Pool. * VM: Inter-VM page sharing is not permitted. * DESKTOP_POOL: Inter-VM page sharing among VMs belonging to the same Desktop pool is permitted. * POD: Inter-VM page sharing among VMs belonging to the same Pod is permitted. * GLOBAL: Inter-VM page sharing among all VMs on the same host is permitted. | [optional] 
**Type** | **string** | Type of the Desktop Pool. * AUTOMATED: Automated Desktop Pool. * MANUAL: Manual Desktop Pool. * RDS: RDS Desktop Pool. | 
**UserAssignment** | Pointer to **string** | Applicable To: Automated and Manual Desktop pools. User assignment scheme. This is required for Automated and Manual Desktop Pools.&lt;br&gt; * DEDICATED: With dedicated assignment, a user returns to the same machine at each session. * FLOATING: With floating assignment, a user may return to one of the available machines for the next session. | [optional] 
**VcenterId** | Pointer to **string** | ID of the virtual center server. &lt;br&gt;This is required for all desktop pool except Unmanaged Manual and RDS desktop pool. &lt;br&gt; | [optional] 
**ViewStorageAcceleratorSettings** | Pointer to [**DesktopPoolViewStorageAcceleratorSettingsCreateSpec**](DesktopPoolViewStorageAcceleratorSettingsCreateSpec.md) |  | [optional] 

## Methods

### NewDesktopPoolCreateSpecV2

`func NewDesktopPoolCreateSpecV2(name string, type_ string, ) *DesktopPoolCreateSpecV2`

NewDesktopPoolCreateSpecV2 instantiates a new DesktopPoolCreateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesktopPoolCreateSpecV2WithDefaults

`func NewDesktopPoolCreateSpecV2WithDefaults() *DesktopPoolCreateSpecV2`

NewDesktopPoolCreateSpecV2WithDefaults instantiates a new DesktopPoolCreateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessGroupId

`func (o *DesktopPoolCreateSpecV2) GetAccessGroupId() string`

GetAccessGroupId returns the AccessGroupId field if non-nil, zero value otherwise.

### GetAccessGroupIdOk

`func (o *DesktopPoolCreateSpecV2) GetAccessGroupIdOk() (*string, bool)`

GetAccessGroupIdOk returns a tuple with the AccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessGroupId

`func (o *DesktopPoolCreateSpecV2) SetAccessGroupId(v string)`

SetAccessGroupId sets AccessGroupId field to given value.

### HasAccessGroupId

`func (o *DesktopPoolCreateSpecV2) HasAccessGroupId() bool`

HasAccessGroupId returns a boolean if a field has been set.

### GetAllowMultipleUserAssignments

`func (o *DesktopPoolCreateSpecV2) GetAllowMultipleUserAssignments() bool`

GetAllowMultipleUserAssignments returns the AllowMultipleUserAssignments field if non-nil, zero value otherwise.

### GetAllowMultipleUserAssignmentsOk

`func (o *DesktopPoolCreateSpecV2) GetAllowMultipleUserAssignmentsOk() (*bool, bool)`

GetAllowMultipleUserAssignmentsOk returns a tuple with the AllowMultipleUserAssignments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowMultipleUserAssignments

`func (o *DesktopPoolCreateSpecV2) SetAllowMultipleUserAssignments(v bool)`

SetAllowMultipleUserAssignments sets AllowMultipleUserAssignments field to given value.

### HasAllowMultipleUserAssignments

`func (o *DesktopPoolCreateSpecV2) HasAllowMultipleUserAssignments() bool`

HasAllowMultipleUserAssignments returns a boolean if a field has been set.

### GetAllowRdsPoolMultiSessionPerUser

`func (o *DesktopPoolCreateSpecV2) GetAllowRdsPoolMultiSessionPerUser() bool`

GetAllowRdsPoolMultiSessionPerUser returns the AllowRdsPoolMultiSessionPerUser field if non-nil, zero value otherwise.

### GetAllowRdsPoolMultiSessionPerUserOk

`func (o *DesktopPoolCreateSpecV2) GetAllowRdsPoolMultiSessionPerUserOk() (*bool, bool)`

GetAllowRdsPoolMultiSessionPerUserOk returns a tuple with the AllowRdsPoolMultiSessionPerUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowRdsPoolMultiSessionPerUser

`func (o *DesktopPoolCreateSpecV2) SetAllowRdsPoolMultiSessionPerUser(v bool)`

SetAllowRdsPoolMultiSessionPerUser sets AllowRdsPoolMultiSessionPerUser field to given value.

### HasAllowRdsPoolMultiSessionPerUser

`func (o *DesktopPoolCreateSpecV2) HasAllowRdsPoolMultiSessionPerUser() bool`

HasAllowRdsPoolMultiSessionPerUser returns a boolean if a field has been set.

### GetAutomaticUserAssignment

`func (o *DesktopPoolCreateSpecV2) GetAutomaticUserAssignment() bool`

GetAutomaticUserAssignment returns the AutomaticUserAssignment field if non-nil, zero value otherwise.

### GetAutomaticUserAssignmentOk

`func (o *DesktopPoolCreateSpecV2) GetAutomaticUserAssignmentOk() (*bool, bool)`

GetAutomaticUserAssignmentOk returns a tuple with the AutomaticUserAssignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomaticUserAssignment

`func (o *DesktopPoolCreateSpecV2) SetAutomaticUserAssignment(v bool)`

SetAutomaticUserAssignment sets AutomaticUserAssignment field to given value.

### HasAutomaticUserAssignment

`func (o *DesktopPoolCreateSpecV2) HasAutomaticUserAssignment() bool`

HasAutomaticUserAssignment returns a boolean if a field has been set.

### GetCategoryFolderName

`func (o *DesktopPoolCreateSpecV2) GetCategoryFolderName() string`

GetCategoryFolderName returns the CategoryFolderName field if non-nil, zero value otherwise.

### GetCategoryFolderNameOk

`func (o *DesktopPoolCreateSpecV2) GetCategoryFolderNameOk() (*string, bool)`

GetCategoryFolderNameOk returns a tuple with the CategoryFolderName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryFolderName

`func (o *DesktopPoolCreateSpecV2) SetCategoryFolderName(v string)`

SetCategoryFolderName sets CategoryFolderName field to given value.

### HasCategoryFolderName

`func (o *DesktopPoolCreateSpecV2) HasCategoryFolderName() bool`

HasCategoryFolderName returns a boolean if a field has been set.

### GetCloudAssigned

`func (o *DesktopPoolCreateSpecV2) GetCloudAssigned() bool`

GetCloudAssigned returns the CloudAssigned field if non-nil, zero value otherwise.

### GetCloudAssignedOk

`func (o *DesktopPoolCreateSpecV2) GetCloudAssignedOk() (*bool, bool)`

GetCloudAssignedOk returns a tuple with the CloudAssigned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudAssigned

`func (o *DesktopPoolCreateSpecV2) SetCloudAssigned(v bool)`

SetCloudAssigned sets CloudAssigned field to given value.

### HasCloudAssigned

`func (o *DesktopPoolCreateSpecV2) HasCloudAssigned() bool`

HasCloudAssigned returns a boolean if a field has been set.

### GetCloudBrokered

`func (o *DesktopPoolCreateSpecV2) GetCloudBrokered() bool`

GetCloudBrokered returns the CloudBrokered field if non-nil, zero value otherwise.

### GetCloudBrokeredOk

`func (o *DesktopPoolCreateSpecV2) GetCloudBrokeredOk() (*bool, bool)`

GetCloudBrokeredOk returns a tuple with the CloudBrokered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudBrokered

`func (o *DesktopPoolCreateSpecV2) SetCloudBrokered(v bool)`

SetCloudBrokered sets CloudBrokered field to given value.

### HasCloudBrokered

`func (o *DesktopPoolCreateSpecV2) HasCloudBrokered() bool`

HasCloudBrokered returns a boolean if a field has been set.

### GetCloudManaged

`func (o *DesktopPoolCreateSpecV2) GetCloudManaged() bool`

GetCloudManaged returns the CloudManaged field if non-nil, zero value otherwise.

### GetCloudManagedOk

`func (o *DesktopPoolCreateSpecV2) GetCloudManagedOk() (*bool, bool)`

GetCloudManagedOk returns a tuple with the CloudManaged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudManaged

`func (o *DesktopPoolCreateSpecV2) SetCloudManaged(v bool)`

SetCloudManaged sets CloudManaged field to given value.

### HasCloudManaged

`func (o *DesktopPoolCreateSpecV2) HasCloudManaged() bool`

HasCloudManaged returns a boolean if a field has been set.

### GetCsRestrictionTags

`func (o *DesktopPoolCreateSpecV2) GetCsRestrictionTags() []string`

GetCsRestrictionTags returns the CsRestrictionTags field if non-nil, zero value otherwise.

### GetCsRestrictionTagsOk

`func (o *DesktopPoolCreateSpecV2) GetCsRestrictionTagsOk() (*[]string, bool)`

GetCsRestrictionTagsOk returns a tuple with the CsRestrictionTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCsRestrictionTags

`func (o *DesktopPoolCreateSpecV2) SetCsRestrictionTags(v []string)`

SetCsRestrictionTags sets CsRestrictionTags field to given value.

### HasCsRestrictionTags

`func (o *DesktopPoolCreateSpecV2) HasCsRestrictionTags() bool`

HasCsRestrictionTags returns a boolean if a field has been set.

### GetCustomizationSettings

`func (o *DesktopPoolCreateSpecV2) GetCustomizationSettings() DesktopPoolCustomizationSettingsCreateSpec`

GetCustomizationSettings returns the CustomizationSettings field if non-nil, zero value otherwise.

### GetCustomizationSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetCustomizationSettingsOk() (*DesktopPoolCustomizationSettingsCreateSpec, bool)`

GetCustomizationSettingsOk returns a tuple with the CustomizationSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomizationSettings

`func (o *DesktopPoolCreateSpecV2) SetCustomizationSettings(v DesktopPoolCustomizationSettingsCreateSpec)`

SetCustomizationSettings sets CustomizationSettings field to given value.

### HasCustomizationSettings

`func (o *DesktopPoolCreateSpecV2) HasCustomizationSettings() bool`

HasCustomizationSettings returns a boolean if a field has been set.

### GetDescription

`func (o *DesktopPoolCreateSpecV2) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DesktopPoolCreateSpecV2) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DesktopPoolCreateSpecV2) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DesktopPoolCreateSpecV2) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDisplayAssignedMachineName

`func (o *DesktopPoolCreateSpecV2) GetDisplayAssignedMachineName() bool`

GetDisplayAssignedMachineName returns the DisplayAssignedMachineName field if non-nil, zero value otherwise.

### GetDisplayAssignedMachineNameOk

`func (o *DesktopPoolCreateSpecV2) GetDisplayAssignedMachineNameOk() (*bool, bool)`

GetDisplayAssignedMachineNameOk returns a tuple with the DisplayAssignedMachineName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayAssignedMachineName

`func (o *DesktopPoolCreateSpecV2) SetDisplayAssignedMachineName(v bool)`

SetDisplayAssignedMachineName sets DisplayAssignedMachineName field to given value.

### HasDisplayAssignedMachineName

`func (o *DesktopPoolCreateSpecV2) HasDisplayAssignedMachineName() bool`

HasDisplayAssignedMachineName returns a boolean if a field has been set.

### GetDisplayMachineAlias

`func (o *DesktopPoolCreateSpecV2) GetDisplayMachineAlias() bool`

GetDisplayMachineAlias returns the DisplayMachineAlias field if non-nil, zero value otherwise.

### GetDisplayMachineAliasOk

`func (o *DesktopPoolCreateSpecV2) GetDisplayMachineAliasOk() (*bool, bool)`

GetDisplayMachineAliasOk returns a tuple with the DisplayMachineAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayMachineAlias

`func (o *DesktopPoolCreateSpecV2) SetDisplayMachineAlias(v bool)`

SetDisplayMachineAlias sets DisplayMachineAlias field to given value.

### HasDisplayMachineAlias

`func (o *DesktopPoolCreateSpecV2) HasDisplayMachineAlias() bool`

HasDisplayMachineAlias returns a boolean if a field has been set.

### GetDisplayName

`func (o *DesktopPoolCreateSpecV2) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *DesktopPoolCreateSpecV2) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *DesktopPoolCreateSpecV2) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *DesktopPoolCreateSpecV2) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetDisplayProtocolSettings

`func (o *DesktopPoolCreateSpecV2) GetDisplayProtocolSettings() DesktopPoolDisplayProtocolSettingsCreateSpec`

GetDisplayProtocolSettings returns the DisplayProtocolSettings field if non-nil, zero value otherwise.

### GetDisplayProtocolSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetDisplayProtocolSettingsOk() (*DesktopPoolDisplayProtocolSettingsCreateSpec, bool)`

GetDisplayProtocolSettingsOk returns a tuple with the DisplayProtocolSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayProtocolSettings

`func (o *DesktopPoolCreateSpecV2) SetDisplayProtocolSettings(v DesktopPoolDisplayProtocolSettingsCreateSpec)`

SetDisplayProtocolSettings sets DisplayProtocolSettings field to given value.

### HasDisplayProtocolSettings

`func (o *DesktopPoolCreateSpecV2) HasDisplayProtocolSettings() bool`

HasDisplayProtocolSettings returns a boolean if a field has been set.

### GetEnableClientRestrictions

`func (o *DesktopPoolCreateSpecV2) GetEnableClientRestrictions() bool`

GetEnableClientRestrictions returns the EnableClientRestrictions field if non-nil, zero value otherwise.

### GetEnableClientRestrictionsOk

`func (o *DesktopPoolCreateSpecV2) GetEnableClientRestrictionsOk() (*bool, bool)`

GetEnableClientRestrictionsOk returns a tuple with the EnableClientRestrictions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableClientRestrictions

`func (o *DesktopPoolCreateSpecV2) SetEnableClientRestrictions(v bool)`

SetEnableClientRestrictions sets EnableClientRestrictions field to given value.

### HasEnableClientRestrictions

`func (o *DesktopPoolCreateSpecV2) HasEnableClientRestrictions() bool`

HasEnableClientRestrictions returns a boolean if a field has been set.

### GetEnableProvisioning

`func (o *DesktopPoolCreateSpecV2) GetEnableProvisioning() bool`

GetEnableProvisioning returns the EnableProvisioning field if non-nil, zero value otherwise.

### GetEnableProvisioningOk

`func (o *DesktopPoolCreateSpecV2) GetEnableProvisioningOk() (*bool, bool)`

GetEnableProvisioningOk returns a tuple with the EnableProvisioning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableProvisioning

`func (o *DesktopPoolCreateSpecV2) SetEnableProvisioning(v bool)`

SetEnableProvisioning sets EnableProvisioning field to given value.

### HasEnableProvisioning

`func (o *DesktopPoolCreateSpecV2) HasEnableProvisioning() bool`

HasEnableProvisioning returns a boolean if a field has been set.

### GetEnabled

`func (o *DesktopPoolCreateSpecV2) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DesktopPoolCreateSpecV2) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DesktopPoolCreateSpecV2) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *DesktopPoolCreateSpecV2) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetFarmId

`func (o *DesktopPoolCreateSpecV2) GetFarmId() string`

GetFarmId returns the FarmId field if non-nil, zero value otherwise.

### GetFarmIdOk

`func (o *DesktopPoolCreateSpecV2) GetFarmIdOk() (*string, bool)`

GetFarmIdOk returns a tuple with the FarmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFarmId

`func (o *DesktopPoolCreateSpecV2) SetFarmId(v string)`

SetFarmId sets FarmId field to given value.

### HasFarmId

`func (o *DesktopPoolCreateSpecV2) HasFarmId() bool`

HasFarmId returns a boolean if a field has been set.

### GetMachines

`func (o *DesktopPoolCreateSpecV2) GetMachines() []string`

GetMachines returns the Machines field if non-nil, zero value otherwise.

### GetMachinesOk

`func (o *DesktopPoolCreateSpecV2) GetMachinesOk() (*[]string, bool)`

GetMachinesOk returns a tuple with the Machines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachines

`func (o *DesktopPoolCreateSpecV2) SetMachines(v []string)`

SetMachines sets Machines field to given value.

### HasMachines

`func (o *DesktopPoolCreateSpecV2) HasMachines() bool`

HasMachines returns a boolean if a field has been set.

### GetName

`func (o *DesktopPoolCreateSpecV2) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DesktopPoolCreateSpecV2) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DesktopPoolCreateSpecV2) SetName(v string)`

SetName sets Name field to given value.


### GetNamingMethod

`func (o *DesktopPoolCreateSpecV2) GetNamingMethod() string`

GetNamingMethod returns the NamingMethod field if non-nil, zero value otherwise.

### GetNamingMethodOk

`func (o *DesktopPoolCreateSpecV2) GetNamingMethodOk() (*string, bool)`

GetNamingMethodOk returns a tuple with the NamingMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNamingMethod

`func (o *DesktopPoolCreateSpecV2) SetNamingMethod(v string)`

SetNamingMethod sets NamingMethod field to given value.

### HasNamingMethod

`func (o *DesktopPoolCreateSpecV2) HasNamingMethod() bool`

HasNamingMethod returns a boolean if a field has been set.

### GetNics

`func (o *DesktopPoolCreateSpecV2) GetNics() []DesktopPoolNetworkInterfaceCardSettingsCreateSpec`

GetNics returns the Nics field if non-nil, zero value otherwise.

### GetNicsOk

`func (o *DesktopPoolCreateSpecV2) GetNicsOk() (*[]DesktopPoolNetworkInterfaceCardSettingsCreateSpec, bool)`

GetNicsOk returns a tuple with the Nics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNics

`func (o *DesktopPoolCreateSpecV2) SetNics(v []DesktopPoolNetworkInterfaceCardSettingsCreateSpec)`

SetNics sets Nics field to given value.

### HasNics

`func (o *DesktopPoolCreateSpecV2) HasNics() bool`

HasNics returns a boolean if a field has been set.

### GetPatternNamingSettings

`func (o *DesktopPoolCreateSpecV2) GetPatternNamingSettings() DesktopPoolVirtualMachinePatternNamingSettingsCreateSpec`

GetPatternNamingSettings returns the PatternNamingSettings field if non-nil, zero value otherwise.

### GetPatternNamingSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetPatternNamingSettingsOk() (*DesktopPoolVirtualMachinePatternNamingSettingsCreateSpec, bool)`

GetPatternNamingSettingsOk returns a tuple with the PatternNamingSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatternNamingSettings

`func (o *DesktopPoolCreateSpecV2) SetPatternNamingSettings(v DesktopPoolVirtualMachinePatternNamingSettingsCreateSpec)`

SetPatternNamingSettings sets PatternNamingSettings field to given value.

### HasPatternNamingSettings

`func (o *DesktopPoolCreateSpecV2) HasPatternNamingSettings() bool`

HasPatternNamingSettings returns a boolean if a field has been set.

### GetProvisioningSettings

`func (o *DesktopPoolCreateSpecV2) GetProvisioningSettings() DesktopPoolProvisioningSettingsCreateSpecV2`

GetProvisioningSettings returns the ProvisioningSettings field if non-nil, zero value otherwise.

### GetProvisioningSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetProvisioningSettingsOk() (*DesktopPoolProvisioningSettingsCreateSpecV2, bool)`

GetProvisioningSettingsOk returns a tuple with the ProvisioningSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvisioningSettings

`func (o *DesktopPoolCreateSpecV2) SetProvisioningSettings(v DesktopPoolProvisioningSettingsCreateSpecV2)`

SetProvisioningSettings sets ProvisioningSettings field to given value.

### HasProvisioningSettings

`func (o *DesktopPoolCreateSpecV2) HasProvisioningSettings() bool`

HasProvisioningSettings returns a boolean if a field has been set.

### GetSessionSettings

`func (o *DesktopPoolCreateSpecV2) GetSessionSettings() DesktopPoolSessionSettingsCreateSpec`

GetSessionSettings returns the SessionSettings field if non-nil, zero value otherwise.

### GetSessionSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetSessionSettingsOk() (*DesktopPoolSessionSettingsCreateSpec, bool)`

GetSessionSettingsOk returns a tuple with the SessionSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionSettings

`func (o *DesktopPoolCreateSpecV2) SetSessionSettings(v DesktopPoolSessionSettingsCreateSpec)`

SetSessionSettings sets SessionSettings field to given value.

### HasSessionSettings

`func (o *DesktopPoolCreateSpecV2) HasSessionSettings() bool`

HasSessionSettings returns a boolean if a field has been set.

### GetSessionType

`func (o *DesktopPoolCreateSpecV2) GetSessionType() string`

GetSessionType returns the SessionType field if non-nil, zero value otherwise.

### GetSessionTypeOk

`func (o *DesktopPoolCreateSpecV2) GetSessionTypeOk() (*string, bool)`

GetSessionTypeOk returns a tuple with the SessionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionType

`func (o *DesktopPoolCreateSpecV2) SetSessionType(v string)`

SetSessionType sets SessionType field to given value.

### HasSessionType

`func (o *DesktopPoolCreateSpecV2) HasSessionType() bool`

HasSessionType returns a boolean if a field has been set.

### GetShortcutLocationsV2

`func (o *DesktopPoolCreateSpecV2) GetShortcutLocationsV2() []string`

GetShortcutLocationsV2 returns the ShortcutLocationsV2 field if non-nil, zero value otherwise.

### GetShortcutLocationsV2Ok

`func (o *DesktopPoolCreateSpecV2) GetShortcutLocationsV2Ok() (*[]string, bool)`

GetShortcutLocationsV2Ok returns a tuple with the ShortcutLocationsV2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcutLocationsV2

`func (o *DesktopPoolCreateSpecV2) SetShortcutLocationsV2(v []string)`

SetShortcutLocationsV2 sets ShortcutLocationsV2 field to given value.

### HasShortcutLocationsV2

`func (o *DesktopPoolCreateSpecV2) HasShortcutLocationsV2() bool`

HasShortcutLocationsV2 returns a boolean if a field has been set.

### GetSource

`func (o *DesktopPoolCreateSpecV2) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *DesktopPoolCreateSpecV2) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *DesktopPoolCreateSpecV2) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *DesktopPoolCreateSpecV2) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetSpecificNamingSettings

`func (o *DesktopPoolCreateSpecV2) GetSpecificNamingSettings() DesktopPoolVirtualMachineSpecifiedNamingSettingsCreateSpec`

GetSpecificNamingSettings returns the SpecificNamingSettings field if non-nil, zero value otherwise.

### GetSpecificNamingSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetSpecificNamingSettingsOk() (*DesktopPoolVirtualMachineSpecifiedNamingSettingsCreateSpec, bool)`

GetSpecificNamingSettingsOk returns a tuple with the SpecificNamingSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecificNamingSettings

`func (o *DesktopPoolCreateSpecV2) SetSpecificNamingSettings(v DesktopPoolVirtualMachineSpecifiedNamingSettingsCreateSpec)`

SetSpecificNamingSettings sets SpecificNamingSettings field to given value.

### HasSpecificNamingSettings

`func (o *DesktopPoolCreateSpecV2) HasSpecificNamingSettings() bool`

HasSpecificNamingSettings returns a boolean if a field has been set.

### GetStopProvisioningOnError

`func (o *DesktopPoolCreateSpecV2) GetStopProvisioningOnError() bool`

GetStopProvisioningOnError returns the StopProvisioningOnError field if non-nil, zero value otherwise.

### GetStopProvisioningOnErrorOk

`func (o *DesktopPoolCreateSpecV2) GetStopProvisioningOnErrorOk() (*bool, bool)`

GetStopProvisioningOnErrorOk returns a tuple with the StopProvisioningOnError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopProvisioningOnError

`func (o *DesktopPoolCreateSpecV2) SetStopProvisioningOnError(v bool)`

SetStopProvisioningOnError sets StopProvisioningOnError field to given value.

### HasStopProvisioningOnError

`func (o *DesktopPoolCreateSpecV2) HasStopProvisioningOnError() bool`

HasStopProvisioningOnError returns a boolean if a field has been set.

### GetStorageSettings

`func (o *DesktopPoolCreateSpecV2) GetStorageSettings() DesktopPoolStorageSettingsCreateSpec`

GetStorageSettings returns the StorageSettings field if non-nil, zero value otherwise.

### GetStorageSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetStorageSettingsOk() (*DesktopPoolStorageSettingsCreateSpec, bool)`

GetStorageSettingsOk returns a tuple with the StorageSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageSettings

`func (o *DesktopPoolCreateSpecV2) SetStorageSettings(v DesktopPoolStorageSettingsCreateSpec)`

SetStorageSettings sets StorageSettings field to given value.

### HasStorageSettings

`func (o *DesktopPoolCreateSpecV2) HasStorageSettings() bool`

HasStorageSettings returns a boolean if a field has been set.

### GetTransparentPageSharingScope

`func (o *DesktopPoolCreateSpecV2) GetTransparentPageSharingScope() string`

GetTransparentPageSharingScope returns the TransparentPageSharingScope field if non-nil, zero value otherwise.

### GetTransparentPageSharingScopeOk

`func (o *DesktopPoolCreateSpecV2) GetTransparentPageSharingScopeOk() (*string, bool)`

GetTransparentPageSharingScopeOk returns a tuple with the TransparentPageSharingScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransparentPageSharingScope

`func (o *DesktopPoolCreateSpecV2) SetTransparentPageSharingScope(v string)`

SetTransparentPageSharingScope sets TransparentPageSharingScope field to given value.

### HasTransparentPageSharingScope

`func (o *DesktopPoolCreateSpecV2) HasTransparentPageSharingScope() bool`

HasTransparentPageSharingScope returns a boolean if a field has been set.

### GetType

`func (o *DesktopPoolCreateSpecV2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DesktopPoolCreateSpecV2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DesktopPoolCreateSpecV2) SetType(v string)`

SetType sets Type field to given value.


### GetUserAssignment

`func (o *DesktopPoolCreateSpecV2) GetUserAssignment() string`

GetUserAssignment returns the UserAssignment field if non-nil, zero value otherwise.

### GetUserAssignmentOk

`func (o *DesktopPoolCreateSpecV2) GetUserAssignmentOk() (*string, bool)`

GetUserAssignmentOk returns a tuple with the UserAssignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAssignment

`func (o *DesktopPoolCreateSpecV2) SetUserAssignment(v string)`

SetUserAssignment sets UserAssignment field to given value.

### HasUserAssignment

`func (o *DesktopPoolCreateSpecV2) HasUserAssignment() bool`

HasUserAssignment returns a boolean if a field has been set.

### GetVcenterId

`func (o *DesktopPoolCreateSpecV2) GetVcenterId() string`

GetVcenterId returns the VcenterId field if non-nil, zero value otherwise.

### GetVcenterIdOk

`func (o *DesktopPoolCreateSpecV2) GetVcenterIdOk() (*string, bool)`

GetVcenterIdOk returns a tuple with the VcenterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVcenterId

`func (o *DesktopPoolCreateSpecV2) SetVcenterId(v string)`

SetVcenterId sets VcenterId field to given value.

### HasVcenterId

`func (o *DesktopPoolCreateSpecV2) HasVcenterId() bool`

HasVcenterId returns a boolean if a field has been set.

### GetViewStorageAcceleratorSettings

`func (o *DesktopPoolCreateSpecV2) GetViewStorageAcceleratorSettings() DesktopPoolViewStorageAcceleratorSettingsCreateSpec`

GetViewStorageAcceleratorSettings returns the ViewStorageAcceleratorSettings field if non-nil, zero value otherwise.

### GetViewStorageAcceleratorSettingsOk

`func (o *DesktopPoolCreateSpecV2) GetViewStorageAcceleratorSettingsOk() (*DesktopPoolViewStorageAcceleratorSettingsCreateSpec, bool)`

GetViewStorageAcceleratorSettingsOk returns a tuple with the ViewStorageAcceleratorSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViewStorageAcceleratorSettings

`func (o *DesktopPoolCreateSpecV2) SetViewStorageAcceleratorSettings(v DesktopPoolViewStorageAcceleratorSettingsCreateSpec)`

SetViewStorageAcceleratorSettings sets ViewStorageAcceleratorSettings field to given value.

### HasViewStorageAcceleratorSettings

`func (o *DesktopPoolCreateSpecV2) HasViewStorageAcceleratorSettings() bool`

HasViewStorageAcceleratorSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


