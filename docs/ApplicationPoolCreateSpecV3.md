# ApplicationPoolCreateSpecV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AntiAffinityData** | Pointer to [**ApplicationAntiAffinityData**](ApplicationAntiAffinityData.md) |  | [optional] 
**AvmShortcutId** | Pointer to **string** | Shortcut ID of AVM managed application. | [optional] 
**CategoryFolderName** | Pointer to **string** | Name of the category folder in the user&#39;s OS containing a shortcut to the application. Unset if the application does not belong to a category. | [optional] 
**CloudBrokered** | Pointer to **bool** | Indicates whether the application pool is cloud brokered. Default value is false.&lt;br&gt; | [optional] 
**CsRestrictionTags** | Pointer to **[]string** | Connection server restrictions. Application pool can be accessed from only those connection server instances that have a matching tag in this list. Null or empty list means that the application pool can be accessed from any connection server. | [optional] 
**Description** | Pointer to **string** | Notes about the application pool. | [optional] 
**DesktopPoolId** | Pointer to **string** | ID of the desktop pool from which this application pool is to be created. Once an application pool is created from a desktop pool, it is always associated with that desktop pool, and cannot be removed from the desktop pool, or added to another desktop pool. Either this or farm id should be set. | [optional] 
**DisplayName** | Pointer to **string** | The display name is the name that users will see in Horizon client. If the display name is left blank, it defaults to name. | [optional] 
**EnableClientRestrictions** | Pointer to **bool** | Indicates whether client restrictions are to be applied to application pool. Currently it is valid for application pool created from farm. Default value is false. | [optional] 
**EnablePreLaunch** | Pointer to **bool** | Whether to pre-launch the application. Default value is false. | [optional] 
**Enabled** | Pointer to **bool** | Indicates whether the application pool is enabled. Default value is true | [optional] 
**ExecutablePath** | **string** | Path to application executable. | 
**FarmId** | Pointer to **string** | ID of the farm from which this application pool is to be created. Once an application pool is created from a farm, it is always associated with that farm, and cannot be removed from the farm, or added to another farm. Either this or desktop pool id should be set. | [optional] 
**MaxMultiSessions** | Pointer to **int32** | Maximum number of multi-sessions a user can have in this application pool. This property is required if multi-session mode is set to \&quot;ENABLED_DEFAULT_OFF\&quot;, \&quot;ENABLED_DEFAULT_ON\&quot;, or \&quot;ENABLED_ENFORCED\&quot;Default value is 1. | [optional] 
**MultiSessionMode** | Pointer to **string** | Multi-session mode for the application pool. An application launched in multi-session mode does not support reconnect behavior when user logs in from a different client instance. Multi-session mode should be disabled when pre-launch is enabled.Default value is \&quot;DISABLED\&quot; * DISABLED: Multi-session is not supported for this application. * ENABLED_DEFAULT_OFF: Multi-session is supported for this application but is disabled by default. The client would need to explicitly request multi-session launch, if wanted. If a legacy client is used, this will always result in a single-session application launch. * ENABLED_DEFAULT_ON: Multi-session mode is supported for this application and is enabled by default. The client can request explicitly for single-session launch, if wanted. If a legacy client is used, this will always result in a multi-session application launch. * ENABLED_ENFORCED: Multi-session is supported for this application and it is enforced. The client can not select to launch this application as a single-session application. | [optional] 
**Name** | **string** | The application pool name is the unique identifier used to identify this application pool. This property must contain only alphanumerics, underscores, and dashes. The maximum length is 64 characters. | 
**Parameters** | Pointer to **string** | Parameters to pass to application when launching. | [optional] 
**Publisher** | Pointer to **string** | Application publisher | [optional] 
**ShortcutLocations** | Pointer to **[]string** | Locations of the category folder in the user&#39;s OS containing a shortcut to the desktop. The value must be set if category folder name is provided. | [optional] 
**StartFolder** | Pointer to **string** | Starting folder for application | [optional] 
**SupportedFileTypesData** | Pointer to [**ApplicationSupportedFileTypesData**](ApplicationSupportedFileTypesData.md) |  | [optional] 
**Version** | Pointer to **string** | Application version. | [optional] 

## Methods

### NewApplicationPoolCreateSpecV3

`func NewApplicationPoolCreateSpecV3(executablePath string, name string, ) *ApplicationPoolCreateSpecV3`

NewApplicationPoolCreateSpecV3 instantiates a new ApplicationPoolCreateSpecV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationPoolCreateSpecV3WithDefaults

`func NewApplicationPoolCreateSpecV3WithDefaults() *ApplicationPoolCreateSpecV3`

NewApplicationPoolCreateSpecV3WithDefaults instantiates a new ApplicationPoolCreateSpecV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAntiAffinityData

`func (o *ApplicationPoolCreateSpecV3) GetAntiAffinityData() ApplicationAntiAffinityData`

GetAntiAffinityData returns the AntiAffinityData field if non-nil, zero value otherwise.

### GetAntiAffinityDataOk

`func (o *ApplicationPoolCreateSpecV3) GetAntiAffinityDataOk() (*ApplicationAntiAffinityData, bool)`

GetAntiAffinityDataOk returns a tuple with the AntiAffinityData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAntiAffinityData

`func (o *ApplicationPoolCreateSpecV3) SetAntiAffinityData(v ApplicationAntiAffinityData)`

SetAntiAffinityData sets AntiAffinityData field to given value.

### HasAntiAffinityData

`func (o *ApplicationPoolCreateSpecV3) HasAntiAffinityData() bool`

HasAntiAffinityData returns a boolean if a field has been set.

### GetAvmShortcutId

`func (o *ApplicationPoolCreateSpecV3) GetAvmShortcutId() string`

GetAvmShortcutId returns the AvmShortcutId field if non-nil, zero value otherwise.

### GetAvmShortcutIdOk

`func (o *ApplicationPoolCreateSpecV3) GetAvmShortcutIdOk() (*string, bool)`

GetAvmShortcutIdOk returns a tuple with the AvmShortcutId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvmShortcutId

`func (o *ApplicationPoolCreateSpecV3) SetAvmShortcutId(v string)`

SetAvmShortcutId sets AvmShortcutId field to given value.

### HasAvmShortcutId

`func (o *ApplicationPoolCreateSpecV3) HasAvmShortcutId() bool`

HasAvmShortcutId returns a boolean if a field has been set.

### GetCategoryFolderName

`func (o *ApplicationPoolCreateSpecV3) GetCategoryFolderName() string`

GetCategoryFolderName returns the CategoryFolderName field if non-nil, zero value otherwise.

### GetCategoryFolderNameOk

`func (o *ApplicationPoolCreateSpecV3) GetCategoryFolderNameOk() (*string, bool)`

GetCategoryFolderNameOk returns a tuple with the CategoryFolderName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryFolderName

`func (o *ApplicationPoolCreateSpecV3) SetCategoryFolderName(v string)`

SetCategoryFolderName sets CategoryFolderName field to given value.

### HasCategoryFolderName

`func (o *ApplicationPoolCreateSpecV3) HasCategoryFolderName() bool`

HasCategoryFolderName returns a boolean if a field has been set.

### GetCloudBrokered

`func (o *ApplicationPoolCreateSpecV3) GetCloudBrokered() bool`

GetCloudBrokered returns the CloudBrokered field if non-nil, zero value otherwise.

### GetCloudBrokeredOk

`func (o *ApplicationPoolCreateSpecV3) GetCloudBrokeredOk() (*bool, bool)`

GetCloudBrokeredOk returns a tuple with the CloudBrokered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudBrokered

`func (o *ApplicationPoolCreateSpecV3) SetCloudBrokered(v bool)`

SetCloudBrokered sets CloudBrokered field to given value.

### HasCloudBrokered

`func (o *ApplicationPoolCreateSpecV3) HasCloudBrokered() bool`

HasCloudBrokered returns a boolean if a field has been set.

### GetCsRestrictionTags

`func (o *ApplicationPoolCreateSpecV3) GetCsRestrictionTags() []string`

GetCsRestrictionTags returns the CsRestrictionTags field if non-nil, zero value otherwise.

### GetCsRestrictionTagsOk

`func (o *ApplicationPoolCreateSpecV3) GetCsRestrictionTagsOk() (*[]string, bool)`

GetCsRestrictionTagsOk returns a tuple with the CsRestrictionTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCsRestrictionTags

`func (o *ApplicationPoolCreateSpecV3) SetCsRestrictionTags(v []string)`

SetCsRestrictionTags sets CsRestrictionTags field to given value.

### HasCsRestrictionTags

`func (o *ApplicationPoolCreateSpecV3) HasCsRestrictionTags() bool`

HasCsRestrictionTags returns a boolean if a field has been set.

### GetDescription

`func (o *ApplicationPoolCreateSpecV3) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ApplicationPoolCreateSpecV3) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ApplicationPoolCreateSpecV3) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ApplicationPoolCreateSpecV3) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDesktopPoolId

`func (o *ApplicationPoolCreateSpecV3) GetDesktopPoolId() string`

GetDesktopPoolId returns the DesktopPoolId field if non-nil, zero value otherwise.

### GetDesktopPoolIdOk

`func (o *ApplicationPoolCreateSpecV3) GetDesktopPoolIdOk() (*string, bool)`

GetDesktopPoolIdOk returns a tuple with the DesktopPoolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktopPoolId

`func (o *ApplicationPoolCreateSpecV3) SetDesktopPoolId(v string)`

SetDesktopPoolId sets DesktopPoolId field to given value.

### HasDesktopPoolId

`func (o *ApplicationPoolCreateSpecV3) HasDesktopPoolId() bool`

HasDesktopPoolId returns a boolean if a field has been set.

### GetDisplayName

`func (o *ApplicationPoolCreateSpecV3) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *ApplicationPoolCreateSpecV3) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *ApplicationPoolCreateSpecV3) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *ApplicationPoolCreateSpecV3) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetEnableClientRestrictions

`func (o *ApplicationPoolCreateSpecV3) GetEnableClientRestrictions() bool`

GetEnableClientRestrictions returns the EnableClientRestrictions field if non-nil, zero value otherwise.

### GetEnableClientRestrictionsOk

`func (o *ApplicationPoolCreateSpecV3) GetEnableClientRestrictionsOk() (*bool, bool)`

GetEnableClientRestrictionsOk returns a tuple with the EnableClientRestrictions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableClientRestrictions

`func (o *ApplicationPoolCreateSpecV3) SetEnableClientRestrictions(v bool)`

SetEnableClientRestrictions sets EnableClientRestrictions field to given value.

### HasEnableClientRestrictions

`func (o *ApplicationPoolCreateSpecV3) HasEnableClientRestrictions() bool`

HasEnableClientRestrictions returns a boolean if a field has been set.

### GetEnablePreLaunch

`func (o *ApplicationPoolCreateSpecV3) GetEnablePreLaunch() bool`

GetEnablePreLaunch returns the EnablePreLaunch field if non-nil, zero value otherwise.

### GetEnablePreLaunchOk

`func (o *ApplicationPoolCreateSpecV3) GetEnablePreLaunchOk() (*bool, bool)`

GetEnablePreLaunchOk returns a tuple with the EnablePreLaunch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnablePreLaunch

`func (o *ApplicationPoolCreateSpecV3) SetEnablePreLaunch(v bool)`

SetEnablePreLaunch sets EnablePreLaunch field to given value.

### HasEnablePreLaunch

`func (o *ApplicationPoolCreateSpecV3) HasEnablePreLaunch() bool`

HasEnablePreLaunch returns a boolean if a field has been set.

### GetEnabled

`func (o *ApplicationPoolCreateSpecV3) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ApplicationPoolCreateSpecV3) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ApplicationPoolCreateSpecV3) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ApplicationPoolCreateSpecV3) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetExecutablePath

`func (o *ApplicationPoolCreateSpecV3) GetExecutablePath() string`

GetExecutablePath returns the ExecutablePath field if non-nil, zero value otherwise.

### GetExecutablePathOk

`func (o *ApplicationPoolCreateSpecV3) GetExecutablePathOk() (*string, bool)`

GetExecutablePathOk returns a tuple with the ExecutablePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutablePath

`func (o *ApplicationPoolCreateSpecV3) SetExecutablePath(v string)`

SetExecutablePath sets ExecutablePath field to given value.


### GetFarmId

`func (o *ApplicationPoolCreateSpecV3) GetFarmId() string`

GetFarmId returns the FarmId field if non-nil, zero value otherwise.

### GetFarmIdOk

`func (o *ApplicationPoolCreateSpecV3) GetFarmIdOk() (*string, bool)`

GetFarmIdOk returns a tuple with the FarmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFarmId

`func (o *ApplicationPoolCreateSpecV3) SetFarmId(v string)`

SetFarmId sets FarmId field to given value.

### HasFarmId

`func (o *ApplicationPoolCreateSpecV3) HasFarmId() bool`

HasFarmId returns a boolean if a field has been set.

### GetMaxMultiSessions

`func (o *ApplicationPoolCreateSpecV3) GetMaxMultiSessions() int32`

GetMaxMultiSessions returns the MaxMultiSessions field if non-nil, zero value otherwise.

### GetMaxMultiSessionsOk

`func (o *ApplicationPoolCreateSpecV3) GetMaxMultiSessionsOk() (*int32, bool)`

GetMaxMultiSessionsOk returns a tuple with the MaxMultiSessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxMultiSessions

`func (o *ApplicationPoolCreateSpecV3) SetMaxMultiSessions(v int32)`

SetMaxMultiSessions sets MaxMultiSessions field to given value.

### HasMaxMultiSessions

`func (o *ApplicationPoolCreateSpecV3) HasMaxMultiSessions() bool`

HasMaxMultiSessions returns a boolean if a field has been set.

### GetMultiSessionMode

`func (o *ApplicationPoolCreateSpecV3) GetMultiSessionMode() string`

GetMultiSessionMode returns the MultiSessionMode field if non-nil, zero value otherwise.

### GetMultiSessionModeOk

`func (o *ApplicationPoolCreateSpecV3) GetMultiSessionModeOk() (*string, bool)`

GetMultiSessionModeOk returns a tuple with the MultiSessionMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiSessionMode

`func (o *ApplicationPoolCreateSpecV3) SetMultiSessionMode(v string)`

SetMultiSessionMode sets MultiSessionMode field to given value.

### HasMultiSessionMode

`func (o *ApplicationPoolCreateSpecV3) HasMultiSessionMode() bool`

HasMultiSessionMode returns a boolean if a field has been set.

### GetName

`func (o *ApplicationPoolCreateSpecV3) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApplicationPoolCreateSpecV3) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApplicationPoolCreateSpecV3) SetName(v string)`

SetName sets Name field to given value.


### GetParameters

`func (o *ApplicationPoolCreateSpecV3) GetParameters() string`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *ApplicationPoolCreateSpecV3) GetParametersOk() (*string, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *ApplicationPoolCreateSpecV3) SetParameters(v string)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *ApplicationPoolCreateSpecV3) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### GetPublisher

`func (o *ApplicationPoolCreateSpecV3) GetPublisher() string`

GetPublisher returns the Publisher field if non-nil, zero value otherwise.

### GetPublisherOk

`func (o *ApplicationPoolCreateSpecV3) GetPublisherOk() (*string, bool)`

GetPublisherOk returns a tuple with the Publisher field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublisher

`func (o *ApplicationPoolCreateSpecV3) SetPublisher(v string)`

SetPublisher sets Publisher field to given value.

### HasPublisher

`func (o *ApplicationPoolCreateSpecV3) HasPublisher() bool`

HasPublisher returns a boolean if a field has been set.

### GetShortcutLocations

`func (o *ApplicationPoolCreateSpecV3) GetShortcutLocations() []string`

GetShortcutLocations returns the ShortcutLocations field if non-nil, zero value otherwise.

### GetShortcutLocationsOk

`func (o *ApplicationPoolCreateSpecV3) GetShortcutLocationsOk() (*[]string, bool)`

GetShortcutLocationsOk returns a tuple with the ShortcutLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcutLocations

`func (o *ApplicationPoolCreateSpecV3) SetShortcutLocations(v []string)`

SetShortcutLocations sets ShortcutLocations field to given value.

### HasShortcutLocations

`func (o *ApplicationPoolCreateSpecV3) HasShortcutLocations() bool`

HasShortcutLocations returns a boolean if a field has been set.

### GetStartFolder

`func (o *ApplicationPoolCreateSpecV3) GetStartFolder() string`

GetStartFolder returns the StartFolder field if non-nil, zero value otherwise.

### GetStartFolderOk

`func (o *ApplicationPoolCreateSpecV3) GetStartFolderOk() (*string, bool)`

GetStartFolderOk returns a tuple with the StartFolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartFolder

`func (o *ApplicationPoolCreateSpecV3) SetStartFolder(v string)`

SetStartFolder sets StartFolder field to given value.

### HasStartFolder

`func (o *ApplicationPoolCreateSpecV3) HasStartFolder() bool`

HasStartFolder returns a boolean if a field has been set.

### GetSupportedFileTypesData

`func (o *ApplicationPoolCreateSpecV3) GetSupportedFileTypesData() ApplicationSupportedFileTypesData`

GetSupportedFileTypesData returns the SupportedFileTypesData field if non-nil, zero value otherwise.

### GetSupportedFileTypesDataOk

`func (o *ApplicationPoolCreateSpecV3) GetSupportedFileTypesDataOk() (*ApplicationSupportedFileTypesData, bool)`

GetSupportedFileTypesDataOk returns a tuple with the SupportedFileTypesData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedFileTypesData

`func (o *ApplicationPoolCreateSpecV3) SetSupportedFileTypesData(v ApplicationSupportedFileTypesData)`

SetSupportedFileTypesData sets SupportedFileTypesData field to given value.

### HasSupportedFileTypesData

`func (o *ApplicationPoolCreateSpecV3) HasSupportedFileTypesData() bool`

HasSupportedFileTypesData returns a boolean if a field has been set.

### GetVersion

`func (o *ApplicationPoolCreateSpecV3) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ApplicationPoolCreateSpecV3) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ApplicationPoolCreateSpecV3) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ApplicationPoolCreateSpecV3) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


