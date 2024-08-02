# ApplicationPoolInfoV4

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessGroupId** | Pointer to **string** | Access groups can organize the entities (like application pools, desktop pools) in the organization. They can also be used for delegated administration. For application pool, this is the same as that of the farm or desktop pool that the application pool belongs to.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**AntiAffinityData** | Pointer to [**ApplicationAntiAffinityData**](ApplicationAntiAffinityData.md) |  | [optional] 
**AvmShortcutId** | Pointer to **string** | Shortcut ID of AVM managed application. | [optional] 
**CategoryFolderName** | Pointer to **string** | Name of the category folder in the user&#39;s OS containing a shortcut to the application. Unset if the application does not belong to a category. | [optional] 
**CloudBrokered** | Pointer to **bool** | Indicates whether the application pool is cloud brokered.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**CsRestrictionTags** | Pointer to **[]string** | Connection server restrictions. Application pool can be accessed from only those connection server instances that have a matching tag in this list. Null or empty list means that the application pool can be accessed from any connection server. | [optional] 
**CustomizedIconIds** | Pointer to **[]string** | List of customized icon IDs associated with the application which the user has configured. | [optional] 
**Description** | Pointer to **string** | Notes about the application pool.&lt;br&gt;Supported Filters: &#39;Equals&#39;, &#39;StartsWith&#39; and &#39;Contains&#39;. | [optional] 
**DesktopPoolId** | Pointer to **string** | ID of the desktop pool from which this application pool is created. Either this or farm id will be set.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**DisplayName** | Pointer to **string** | The display name is the name that users will see when they connect to view client. If the display name is left blank, it defaults to name.&lt;br&gt;Supported Filters: &#39;Equals&#39;, &#39;StartsWith&#39; and &#39;Contains&#39;. | [optional] 
**EnableClientRestrictions** | Pointer to **bool** | Indicates whether client restrictions are to be applied to application pool. Currently it is valid for application pool created from farm.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**EnablePreLaunch** | Pointer to **bool** | Whether to pre-launch the application.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**Enabled** | Pointer to **bool** | Indicates whether the application pool is enabled.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**ExecutablePath** | Pointer to **string** | Path to application executable.&lt;br&gt;Supported Filters: &#39;Equals&#39;, &#39;StartsWith&#39;, &#39;EndsWith&#39; and &#39;Contains&#39;. | [optional] 
**FarmId** | Pointer to **string** | ID of the farm from which this application pool is created. Either this or desktop pool id will be set.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**GlobalApplicationEntitlementId** | Pointer to **string** | Global application entitlement for this application pool. Caller should have permission to FEDERATED_LDAP_VIEW privilege for this field to be populated or to use in filter.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**IconIds** | Pointer to **[]string** | List of icon IDs associated with the application which are fetched from the agent. | [optional] 
**Id** | Pointer to **string** | Unique ID representing application pool.&lt;br&gt;Supported Filters: &#39;Equals&#39;. | [optional] 
**MaxMultiSessions** | Pointer to **int32** | Maximum number of multi-sessions a user can have in this application pool. This property is required if multi-session mode is set to \&quot;ENABLED_DEFAULT_OFF\&quot;, \&quot;ENABLED_DEFAULT_ON\&quot;, or \&quot;ENABLED_ENFORCED\&quot; | [optional] 
**MultiSessionMode** | Pointer to **string** | Multi-session mode for the application pool. An application launched in multi-session mode does not support reconnect behavior when user logs in from a different client instance. Multi-session mode should be disabled when pre-launch is enabled.&lt;br&gt;Supported Filters: &#39;Equals&#39;. * DISABLED: Multi-session is not supported for this application. * ENABLED_DEFAULT_OFF: Multi-session is supported for this application but is disabled by default. The client would need to explicitly request multi-session launch, if wanted. If a legacy client is used, this will always result in a single-session application launch. * ENABLED_DEFAULT_ON: Multi-session mode is supported for this application and is enabled by default. The client can request explicitly for single-session launch, if wanted. If a legacy client is used, this will always result in a multi-session application launch. * ENABLED_ENFORCED: Multi-session is supported for this application and it is enforced. The client can not select to launch this application as a single-session application. | [optional] 
**Name** | Pointer to **string** | The application name is the unique identifier used to identify this application pool. This property must contain only alphanumerics, underscores, and dashes. The maximum length is 64 characters.&lt;br&gt;Supported Filters: &#39;Equals&#39;, &#39;StartsWith&#39; and &#39;Contains&#39;. | [optional] 
**Parameters** | Pointer to **string** | Parameters to pass to application when launching. | [optional] 
**Publisher** | Pointer to **string** | Application publisher.&lt;br&gt;Supported Filters: &#39;Equals&#39;, &#39;StartsWith&#39; and &#39;Contains&#39;. | [optional] 
**ShortcutLocations** | Pointer to **[]string** | Locations of the category folder in the user&#39;s OS containing a shortcut to the application. The value must be set if category folder name is provided. | [optional] 
**StartFolder** | Pointer to **string** | Starting folder for application. | [optional] 
**SupportedFileTypesData** | Pointer to [**ApplicationSupportedFileTypesData**](ApplicationSupportedFileTypesData.md) |  | [optional] 
**Version** | Pointer to **string** | Application version.&lt;br&gt;Supported Filters: &#39;Equals&#39;, &#39;StartsWith&#39; and &#39;Contains&#39;. | [optional] 

## Methods

### NewApplicationPoolInfoV4

`func NewApplicationPoolInfoV4() *ApplicationPoolInfoV4`

NewApplicationPoolInfoV4 instantiates a new ApplicationPoolInfoV4 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationPoolInfoV4WithDefaults

`func NewApplicationPoolInfoV4WithDefaults() *ApplicationPoolInfoV4`

NewApplicationPoolInfoV4WithDefaults instantiates a new ApplicationPoolInfoV4 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessGroupId

`func (o *ApplicationPoolInfoV4) GetAccessGroupId() string`

GetAccessGroupId returns the AccessGroupId field if non-nil, zero value otherwise.

### GetAccessGroupIdOk

`func (o *ApplicationPoolInfoV4) GetAccessGroupIdOk() (*string, bool)`

GetAccessGroupIdOk returns a tuple with the AccessGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessGroupId

`func (o *ApplicationPoolInfoV4) SetAccessGroupId(v string)`

SetAccessGroupId sets AccessGroupId field to given value.

### HasAccessGroupId

`func (o *ApplicationPoolInfoV4) HasAccessGroupId() bool`

HasAccessGroupId returns a boolean if a field has been set.

### GetAntiAffinityData

`func (o *ApplicationPoolInfoV4) GetAntiAffinityData() ApplicationAntiAffinityData`

GetAntiAffinityData returns the AntiAffinityData field if non-nil, zero value otherwise.

### GetAntiAffinityDataOk

`func (o *ApplicationPoolInfoV4) GetAntiAffinityDataOk() (*ApplicationAntiAffinityData, bool)`

GetAntiAffinityDataOk returns a tuple with the AntiAffinityData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAntiAffinityData

`func (o *ApplicationPoolInfoV4) SetAntiAffinityData(v ApplicationAntiAffinityData)`

SetAntiAffinityData sets AntiAffinityData field to given value.

### HasAntiAffinityData

`func (o *ApplicationPoolInfoV4) HasAntiAffinityData() bool`

HasAntiAffinityData returns a boolean if a field has been set.

### GetAvmShortcutId

`func (o *ApplicationPoolInfoV4) GetAvmShortcutId() string`

GetAvmShortcutId returns the AvmShortcutId field if non-nil, zero value otherwise.

### GetAvmShortcutIdOk

`func (o *ApplicationPoolInfoV4) GetAvmShortcutIdOk() (*string, bool)`

GetAvmShortcutIdOk returns a tuple with the AvmShortcutId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvmShortcutId

`func (o *ApplicationPoolInfoV4) SetAvmShortcutId(v string)`

SetAvmShortcutId sets AvmShortcutId field to given value.

### HasAvmShortcutId

`func (o *ApplicationPoolInfoV4) HasAvmShortcutId() bool`

HasAvmShortcutId returns a boolean if a field has been set.

### GetCategoryFolderName

`func (o *ApplicationPoolInfoV4) GetCategoryFolderName() string`

GetCategoryFolderName returns the CategoryFolderName field if non-nil, zero value otherwise.

### GetCategoryFolderNameOk

`func (o *ApplicationPoolInfoV4) GetCategoryFolderNameOk() (*string, bool)`

GetCategoryFolderNameOk returns a tuple with the CategoryFolderName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryFolderName

`func (o *ApplicationPoolInfoV4) SetCategoryFolderName(v string)`

SetCategoryFolderName sets CategoryFolderName field to given value.

### HasCategoryFolderName

`func (o *ApplicationPoolInfoV4) HasCategoryFolderName() bool`

HasCategoryFolderName returns a boolean if a field has been set.

### GetCloudBrokered

`func (o *ApplicationPoolInfoV4) GetCloudBrokered() bool`

GetCloudBrokered returns the CloudBrokered field if non-nil, zero value otherwise.

### GetCloudBrokeredOk

`func (o *ApplicationPoolInfoV4) GetCloudBrokeredOk() (*bool, bool)`

GetCloudBrokeredOk returns a tuple with the CloudBrokered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudBrokered

`func (o *ApplicationPoolInfoV4) SetCloudBrokered(v bool)`

SetCloudBrokered sets CloudBrokered field to given value.

### HasCloudBrokered

`func (o *ApplicationPoolInfoV4) HasCloudBrokered() bool`

HasCloudBrokered returns a boolean if a field has been set.

### GetCsRestrictionTags

`func (o *ApplicationPoolInfoV4) GetCsRestrictionTags() []string`

GetCsRestrictionTags returns the CsRestrictionTags field if non-nil, zero value otherwise.

### GetCsRestrictionTagsOk

`func (o *ApplicationPoolInfoV4) GetCsRestrictionTagsOk() (*[]string, bool)`

GetCsRestrictionTagsOk returns a tuple with the CsRestrictionTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCsRestrictionTags

`func (o *ApplicationPoolInfoV4) SetCsRestrictionTags(v []string)`

SetCsRestrictionTags sets CsRestrictionTags field to given value.

### HasCsRestrictionTags

`func (o *ApplicationPoolInfoV4) HasCsRestrictionTags() bool`

HasCsRestrictionTags returns a boolean if a field has been set.

### GetCustomizedIconIds

`func (o *ApplicationPoolInfoV4) GetCustomizedIconIds() []string`

GetCustomizedIconIds returns the CustomizedIconIds field if non-nil, zero value otherwise.

### GetCustomizedIconIdsOk

`func (o *ApplicationPoolInfoV4) GetCustomizedIconIdsOk() (*[]string, bool)`

GetCustomizedIconIdsOk returns a tuple with the CustomizedIconIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomizedIconIds

`func (o *ApplicationPoolInfoV4) SetCustomizedIconIds(v []string)`

SetCustomizedIconIds sets CustomizedIconIds field to given value.

### HasCustomizedIconIds

`func (o *ApplicationPoolInfoV4) HasCustomizedIconIds() bool`

HasCustomizedIconIds returns a boolean if a field has been set.

### GetDescription

`func (o *ApplicationPoolInfoV4) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ApplicationPoolInfoV4) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ApplicationPoolInfoV4) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ApplicationPoolInfoV4) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDesktopPoolId

`func (o *ApplicationPoolInfoV4) GetDesktopPoolId() string`

GetDesktopPoolId returns the DesktopPoolId field if non-nil, zero value otherwise.

### GetDesktopPoolIdOk

`func (o *ApplicationPoolInfoV4) GetDesktopPoolIdOk() (*string, bool)`

GetDesktopPoolIdOk returns a tuple with the DesktopPoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktopPoolId

`func (o *ApplicationPoolInfoV4) SetDesktopPoolId(v string)`

SetDesktopPoolId sets DesktopPoolId field to given value.

### HasDesktopPoolId

`func (o *ApplicationPoolInfoV4) HasDesktopPoolId() bool`

HasDesktopPoolId returns a boolean if a field has been set.

### GetDisplayName

`func (o *ApplicationPoolInfoV4) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *ApplicationPoolInfoV4) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *ApplicationPoolInfoV4) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *ApplicationPoolInfoV4) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetEnableClientRestrictions

`func (o *ApplicationPoolInfoV4) GetEnableClientRestrictions() bool`

GetEnableClientRestrictions returns the EnableClientRestrictions field if non-nil, zero value otherwise.

### GetEnableClientRestrictionsOk

`func (o *ApplicationPoolInfoV4) GetEnableClientRestrictionsOk() (*bool, bool)`

GetEnableClientRestrictionsOk returns a tuple with the EnableClientRestrictions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableClientRestrictions

`func (o *ApplicationPoolInfoV4) SetEnableClientRestrictions(v bool)`

SetEnableClientRestrictions sets EnableClientRestrictions field to given value.

### HasEnableClientRestrictions

`func (o *ApplicationPoolInfoV4) HasEnableClientRestrictions() bool`

HasEnableClientRestrictions returns a boolean if a field has been set.

### GetEnablePreLaunch

`func (o *ApplicationPoolInfoV4) GetEnablePreLaunch() bool`

GetEnablePreLaunch returns the EnablePreLaunch field if non-nil, zero value otherwise.

### GetEnablePreLaunchOk

`func (o *ApplicationPoolInfoV4) GetEnablePreLaunchOk() (*bool, bool)`

GetEnablePreLaunchOk returns a tuple with the EnablePreLaunch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnablePreLaunch

`func (o *ApplicationPoolInfoV4) SetEnablePreLaunch(v bool)`

SetEnablePreLaunch sets EnablePreLaunch field to given value.

### HasEnablePreLaunch

`func (o *ApplicationPoolInfoV4) HasEnablePreLaunch() bool`

HasEnablePreLaunch returns a boolean if a field has been set.

### GetEnabled

`func (o *ApplicationPoolInfoV4) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ApplicationPoolInfoV4) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ApplicationPoolInfoV4) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ApplicationPoolInfoV4) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetExecutablePath

`func (o *ApplicationPoolInfoV4) GetExecutablePath() string`

GetExecutablePath returns the ExecutablePath field if non-nil, zero value otherwise.

### GetExecutablePathOk

`func (o *ApplicationPoolInfoV4) GetExecutablePathOk() (*string, bool)`

GetExecutablePathOk returns a tuple with the ExecutablePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutablePath

`func (o *ApplicationPoolInfoV4) SetExecutablePath(v string)`

SetExecutablePath sets ExecutablePath field to given value.

### HasExecutablePath

`func (o *ApplicationPoolInfoV4) HasExecutablePath() bool`

HasExecutablePath returns a boolean if a field has been set.

### GetFarmId

`func (o *ApplicationPoolInfoV4) GetFarmId() string`

GetFarmId returns the FarmId field if non-nil, zero value otherwise.

### GetFarmIdOk

`func (o *ApplicationPoolInfoV4) GetFarmIdOk() (*string, bool)`

GetFarmIdOk returns a tuple with the FarmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFarmId

`func (o *ApplicationPoolInfoV4) SetFarmId(v string)`

SetFarmId sets FarmId field to given value.

### HasFarmId

`func (o *ApplicationPoolInfoV4) HasFarmId() bool`

HasFarmId returns a boolean if a field has been set.

### GetGlobalApplicationEntitlementId

`func (o *ApplicationPoolInfoV4) GetGlobalApplicationEntitlementId() string`

GetGlobalApplicationEntitlementId returns the GlobalApplicationEntitlementId field if non-nil, zero value otherwise.

### GetGlobalApplicationEntitlementIdOk

`func (o *ApplicationPoolInfoV4) GetGlobalApplicationEntitlementIdOk() (*string, bool)`

GetGlobalApplicationEntitlementIdOk returns a tuple with the GlobalApplicationEntitlementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalApplicationEntitlementId

`func (o *ApplicationPoolInfoV4) SetGlobalApplicationEntitlementId(v string)`

SetGlobalApplicationEntitlementId sets GlobalApplicationEntitlementId field to given value.

### HasGlobalApplicationEntitlementId

`func (o *ApplicationPoolInfoV4) HasGlobalApplicationEntitlementId() bool`

HasGlobalApplicationEntitlementId returns a boolean if a field has been set.

### GetIconIds

`func (o *ApplicationPoolInfoV4) GetIconIds() []string`

GetIconIds returns the IconIds field if non-nil, zero value otherwise.

### GetIconIdsOk

`func (o *ApplicationPoolInfoV4) GetIconIdsOk() (*[]string, bool)`

GetIconIdsOk returns a tuple with the IconIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconIds

`func (o *ApplicationPoolInfoV4) SetIconIds(v []string)`

SetIconIds sets IconIds field to given value.

### HasIconIds

`func (o *ApplicationPoolInfoV4) HasIconIds() bool`

HasIconIds returns a boolean if a field has been set.

### GetId

`func (o *ApplicationPoolInfoV4) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApplicationPoolInfoV4) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApplicationPoolInfoV4) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ApplicationPoolInfoV4) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMaxMultiSessions

`func (o *ApplicationPoolInfoV4) GetMaxMultiSessions() int32`

GetMaxMultiSessions returns the MaxMultiSessions field if non-nil, zero value otherwise.

### GetMaxMultiSessionsOk

`func (o *ApplicationPoolInfoV4) GetMaxMultiSessionsOk() (*int32, bool)`

GetMaxMultiSessionsOk returns a tuple with the MaxMultiSessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxMultiSessions

`func (o *ApplicationPoolInfoV4) SetMaxMultiSessions(v int32)`

SetMaxMultiSessions sets MaxMultiSessions field to given value.

### HasMaxMultiSessions

`func (o *ApplicationPoolInfoV4) HasMaxMultiSessions() bool`

HasMaxMultiSessions returns a boolean if a field has been set.

### GetMultiSessionMode

`func (o *ApplicationPoolInfoV4) GetMultiSessionMode() string`

GetMultiSessionMode returns the MultiSessionMode field if non-nil, zero value otherwise.

### GetMultiSessionModeOk

`func (o *ApplicationPoolInfoV4) GetMultiSessionModeOk() (*string, bool)`

GetMultiSessionModeOk returns a tuple with the MultiSessionMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiSessionMode

`func (o *ApplicationPoolInfoV4) SetMultiSessionMode(v string)`

SetMultiSessionMode sets MultiSessionMode field to given value.

### HasMultiSessionMode

`func (o *ApplicationPoolInfoV4) HasMultiSessionMode() bool`

HasMultiSessionMode returns a boolean if a field has been set.

### GetName

`func (o *ApplicationPoolInfoV4) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApplicationPoolInfoV4) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApplicationPoolInfoV4) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ApplicationPoolInfoV4) HasName() bool`

HasName returns a boolean if a field has been set.

### GetParameters

`func (o *ApplicationPoolInfoV4) GetParameters() string`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *ApplicationPoolInfoV4) GetParametersOk() (*string, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *ApplicationPoolInfoV4) SetParameters(v string)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *ApplicationPoolInfoV4) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### GetPublisher

`func (o *ApplicationPoolInfoV4) GetPublisher() string`

GetPublisher returns the Publisher field if non-nil, zero value otherwise.

### GetPublisherOk

`func (o *ApplicationPoolInfoV4) GetPublisherOk() (*string, bool)`

GetPublisherOk returns a tuple with the Publisher field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublisher

`func (o *ApplicationPoolInfoV4) SetPublisher(v string)`

SetPublisher sets Publisher field to given value.

### HasPublisher

`func (o *ApplicationPoolInfoV4) HasPublisher() bool`

HasPublisher returns a boolean if a field has been set.

### GetShortcutLocations

`func (o *ApplicationPoolInfoV4) GetShortcutLocations() []string`

GetShortcutLocations returns the ShortcutLocations field if non-nil, zero value otherwise.

### GetShortcutLocationsOk

`func (o *ApplicationPoolInfoV4) GetShortcutLocationsOk() (*[]string, bool)`

GetShortcutLocationsOk returns a tuple with the ShortcutLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcutLocations

`func (o *ApplicationPoolInfoV4) SetShortcutLocations(v []string)`

SetShortcutLocations sets ShortcutLocations field to given value.

### HasShortcutLocations

`func (o *ApplicationPoolInfoV4) HasShortcutLocations() bool`

HasShortcutLocations returns a boolean if a field has been set.

### GetStartFolder

`func (o *ApplicationPoolInfoV4) GetStartFolder() string`

GetStartFolder returns the StartFolder field if non-nil, zero value otherwise.

### GetStartFolderOk

`func (o *ApplicationPoolInfoV4) GetStartFolderOk() (*string, bool)`

GetStartFolderOk returns a tuple with the StartFolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartFolder

`func (o *ApplicationPoolInfoV4) SetStartFolder(v string)`

SetStartFolder sets StartFolder field to given value.

### HasStartFolder

`func (o *ApplicationPoolInfoV4) HasStartFolder() bool`

HasStartFolder returns a boolean if a field has been set.

### GetSupportedFileTypesData

`func (o *ApplicationPoolInfoV4) GetSupportedFileTypesData() ApplicationSupportedFileTypesData`

GetSupportedFileTypesData returns the SupportedFileTypesData field if non-nil, zero value otherwise.

### GetSupportedFileTypesDataOk

`func (o *ApplicationPoolInfoV4) GetSupportedFileTypesDataOk() (*ApplicationSupportedFileTypesData, bool)`

GetSupportedFileTypesDataOk returns a tuple with the SupportedFileTypesData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedFileTypesData

`func (o *ApplicationPoolInfoV4) SetSupportedFileTypesData(v ApplicationSupportedFileTypesData)`

SetSupportedFileTypesData sets SupportedFileTypesData field to given value.

### HasSupportedFileTypesData

`func (o *ApplicationPoolInfoV4) HasSupportedFileTypesData() bool`

HasSupportedFileTypesData returns a boolean if a field has been set.

### GetVersion

`func (o *ApplicationPoolInfoV4) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ApplicationPoolInfoV4) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ApplicationPoolInfoV4) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ApplicationPoolInfoV4) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


