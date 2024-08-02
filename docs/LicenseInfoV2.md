# LicenseInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentAutoUpgradeEnabled** | Pointer to **bool** | Indicates whether agent auto upgrade is enabled. | [optional] 
**ApplicationPoolLaunchEnabled** | Pointer to **bool** | Whether application pool launch is enabled. | [optional] 
**DesktopPoolLaunchEnabled** | Pointer to **bool** | Whether desktop pool launch is enabled. | [optional] 
**ExpirationTime** | Pointer to **int64** | The expiration date of the license. Caller should have permission to GLOBAL_CONFIG_VIEW privilege for this field to be populated. | [optional] 
**GracePeriodDays** | Pointer to **int32** | The grace period in days. Caller should have permission to GLOBAL_CONFIG_VIEW privilege for this field to be populated. | [optional] 
**HelpDeskEnabled** | Pointer to **bool** | Whether help desk is enabled. | [optional] 
**InstantCloneEnabled** | Pointer to **bool** | Whether instant clone is enabled. | [optional] 
**LicenseEdition** | Pointer to **string** | The license edition. Caller should have permission to GLOBAL_CONFIG_VIEW privilege for this field to be populated. * ENTERPRISE_CONCURRENT_USER: VMware Enterprise. * HORIZON_ADVANCED_CONCURRENT_USER: VMware Horizon Advanced (Concurrent User). * HORIZON_ADVANCED_NAMED_USER: VMware Horizon Advanced (Named User). * HORIZON_APPS_ADVANCED_CONCURRENT_USER: Mware Horizon Apps 7 Advanced (Concurrent User). * HORIZON_APPS_ADVANCED_NAMED_USER: VMware Horizon Apps 7 Advanced (Named User). * HORIZON_APPS_STANDARD_CONCURRENT_USER: VMware Horizon Apps 7 Standard  (Concurrent User). * HORIZON_APPS_STANDARD_NAMED_USER: VMware Horizon Apps 7 Standard (Named User). * HORIZON_ENTERPRISE_CONCURRENT_USER: Horizon Enterprise (Concurrent User). * HORIZON_ENTERPRISE_NAMED_USER: Horizon Enterprise (Named User). * HORIZON_STANDARD_CONCURRENT_USER: VMware Horizon Standard  (Concurrent User). * WS1_ENTERPRISE_NAMED_USER: Workspace ONE Enterprise. * WS1_ENTERPRISE_WITH_VDI_NAMED_USER: Workspace ONE Enterprise with VDI. | [optional] 
**LicenseHealth** | Pointer to **string** | The license health. The property will only be set when license_mode is set to SUBSCRIPTION. Caller should have permission to GLOBAL_CONFIG_VIEW privilege for this field to be populated. * GREEN: License is not expired and license update is missed but not more than 7 days. * RED: License is expired. * YELLOW: License is not expired and license update is missed for more than 7 days. | [optional] 
**LicenseKey** | Pointer to **string** | The license key in partially redacted form. Caller should have permission to GLOBAL_CONFIG_VIEW privilege for this field to be populated. | [optional] 
**LicenseMode** | Pointer to **string** | The license mode used. Caller should have permission to GLOBAL_CONFIG_VIEW privilege for this field to be populated. * DEFAULT: Perpetual license is in use. * PERPETUAL_ONLY: Perpetual license is in use. * SUBSCRIPTION: Cloud subscription license is in use. | [optional] 
**Licensed** | Pointer to **bool** | Whether the horizon is licensed. | [optional] 
**SessionCollaborationEnabled** | Pointer to **bool** | Whether session collaboration is enabled. | [optional] 
**SubscriptionSliceExpiry** | Pointer to **int64** | The expiry of subscription slice. The property will only be set  when license_mode is set to SUBSCRIPTION. Caller should have permission to GLOBAL_CONFIG_VIEW privilege for this field to be populated. | [optional] 
**UsageModel** | Pointer to **string** | TThe usage model for this license. * CONCURRENT_USER: The is the license usage model for a standalone install. * NAMED_USER: This is the license usage model for an install as part of a suite. | [optional] 

## Methods

### NewLicenseInfoV2

`func NewLicenseInfoV2() *LicenseInfoV2`

NewLicenseInfoV2 instantiates a new LicenseInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseInfoV2WithDefaults

`func NewLicenseInfoV2WithDefaults() *LicenseInfoV2`

NewLicenseInfoV2WithDefaults instantiates a new LicenseInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentAutoUpgradeEnabled

`func (o *LicenseInfoV2) GetAgentAutoUpgradeEnabled() bool`

GetAgentAutoUpgradeEnabled returns the AgentAutoUpgradeEnabled field if non-nil, zero value otherwise.

### GetAgentAutoUpgradeEnabledOk

`func (o *LicenseInfoV2) GetAgentAutoUpgradeEnabledOk() (*bool, bool)`

GetAgentAutoUpgradeEnabledOk returns a tuple with the AgentAutoUpgradeEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentAutoUpgradeEnabled

`func (o *LicenseInfoV2) SetAgentAutoUpgradeEnabled(v bool)`

SetAgentAutoUpgradeEnabled sets AgentAutoUpgradeEnabled field to given value.

### HasAgentAutoUpgradeEnabled

`func (o *LicenseInfoV2) HasAgentAutoUpgradeEnabled() bool`

HasAgentAutoUpgradeEnabled returns a boolean if a field has been set.

### GetApplicationPoolLaunchEnabled

`func (o *LicenseInfoV2) GetApplicationPoolLaunchEnabled() bool`

GetApplicationPoolLaunchEnabled returns the ApplicationPoolLaunchEnabled field if non-nil, zero value otherwise.

### GetApplicationPoolLaunchEnabledOk

`func (o *LicenseInfoV2) GetApplicationPoolLaunchEnabledOk() (*bool, bool)`

GetApplicationPoolLaunchEnabledOk returns a tuple with the ApplicationPoolLaunchEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationPoolLaunchEnabled

`func (o *LicenseInfoV2) SetApplicationPoolLaunchEnabled(v bool)`

SetApplicationPoolLaunchEnabled sets ApplicationPoolLaunchEnabled field to given value.

### HasApplicationPoolLaunchEnabled

`func (o *LicenseInfoV2) HasApplicationPoolLaunchEnabled() bool`

HasApplicationPoolLaunchEnabled returns a boolean if a field has been set.

### GetDesktopPoolLaunchEnabled

`func (o *LicenseInfoV2) GetDesktopPoolLaunchEnabled() bool`

GetDesktopPoolLaunchEnabled returns the DesktopPoolLaunchEnabled field if non-nil, zero value otherwise.

### GetDesktopPoolLaunchEnabledOk

`func (o *LicenseInfoV2) GetDesktopPoolLaunchEnabledOk() (*bool, bool)`

GetDesktopPoolLaunchEnabledOk returns a tuple with the DesktopPoolLaunchEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktopPoolLaunchEnabled

`func (o *LicenseInfoV2) SetDesktopPoolLaunchEnabled(v bool)`

SetDesktopPoolLaunchEnabled sets DesktopPoolLaunchEnabled field to given value.

### HasDesktopPoolLaunchEnabled

`func (o *LicenseInfoV2) HasDesktopPoolLaunchEnabled() bool`

HasDesktopPoolLaunchEnabled returns a boolean if a field has been set.

### GetExpirationTime

`func (o *LicenseInfoV2) GetExpirationTime() int64`

GetExpirationTime returns the ExpirationTime field if non-nil, zero value otherwise.

### GetExpirationTimeOk

`func (o *LicenseInfoV2) GetExpirationTimeOk() (*int64, bool)`

GetExpirationTimeOk returns a tuple with the ExpirationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationTime

`func (o *LicenseInfoV2) SetExpirationTime(v int64)`

SetExpirationTime sets ExpirationTime field to given value.

### HasExpirationTime

`func (o *LicenseInfoV2) HasExpirationTime() bool`

HasExpirationTime returns a boolean if a field has been set.

### GetGracePeriodDays

`func (o *LicenseInfoV2) GetGracePeriodDays() int32`

GetGracePeriodDays returns the GracePeriodDays field if non-nil, zero value otherwise.

### GetGracePeriodDaysOk

`func (o *LicenseInfoV2) GetGracePeriodDaysOk() (*int32, bool)`

GetGracePeriodDaysOk returns a tuple with the GracePeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGracePeriodDays

`func (o *LicenseInfoV2) SetGracePeriodDays(v int32)`

SetGracePeriodDays sets GracePeriodDays field to given value.

### HasGracePeriodDays

`func (o *LicenseInfoV2) HasGracePeriodDays() bool`

HasGracePeriodDays returns a boolean if a field has been set.

### GetHelpDeskEnabled

`func (o *LicenseInfoV2) GetHelpDeskEnabled() bool`

GetHelpDeskEnabled returns the HelpDeskEnabled field if non-nil, zero value otherwise.

### GetHelpDeskEnabledOk

`func (o *LicenseInfoV2) GetHelpDeskEnabledOk() (*bool, bool)`

GetHelpDeskEnabledOk returns a tuple with the HelpDeskEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelpDeskEnabled

`func (o *LicenseInfoV2) SetHelpDeskEnabled(v bool)`

SetHelpDeskEnabled sets HelpDeskEnabled field to given value.

### HasHelpDeskEnabled

`func (o *LicenseInfoV2) HasHelpDeskEnabled() bool`

HasHelpDeskEnabled returns a boolean if a field has been set.

### GetInstantCloneEnabled

`func (o *LicenseInfoV2) GetInstantCloneEnabled() bool`

GetInstantCloneEnabled returns the InstantCloneEnabled field if non-nil, zero value otherwise.

### GetInstantCloneEnabledOk

`func (o *LicenseInfoV2) GetInstantCloneEnabledOk() (*bool, bool)`

GetInstantCloneEnabledOk returns a tuple with the InstantCloneEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstantCloneEnabled

`func (o *LicenseInfoV2) SetInstantCloneEnabled(v bool)`

SetInstantCloneEnabled sets InstantCloneEnabled field to given value.

### HasInstantCloneEnabled

`func (o *LicenseInfoV2) HasInstantCloneEnabled() bool`

HasInstantCloneEnabled returns a boolean if a field has been set.

### GetLicenseEdition

`func (o *LicenseInfoV2) GetLicenseEdition() string`

GetLicenseEdition returns the LicenseEdition field if non-nil, zero value otherwise.

### GetLicenseEditionOk

`func (o *LicenseInfoV2) GetLicenseEditionOk() (*string, bool)`

GetLicenseEditionOk returns a tuple with the LicenseEdition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseEdition

`func (o *LicenseInfoV2) SetLicenseEdition(v string)`

SetLicenseEdition sets LicenseEdition field to given value.

### HasLicenseEdition

`func (o *LicenseInfoV2) HasLicenseEdition() bool`

HasLicenseEdition returns a boolean if a field has been set.

### GetLicenseHealth

`func (o *LicenseInfoV2) GetLicenseHealth() string`

GetLicenseHealth returns the LicenseHealth field if non-nil, zero value otherwise.

### GetLicenseHealthOk

`func (o *LicenseInfoV2) GetLicenseHealthOk() (*string, bool)`

GetLicenseHealthOk returns a tuple with the LicenseHealth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseHealth

`func (o *LicenseInfoV2) SetLicenseHealth(v string)`

SetLicenseHealth sets LicenseHealth field to given value.

### HasLicenseHealth

`func (o *LicenseInfoV2) HasLicenseHealth() bool`

HasLicenseHealth returns a boolean if a field has been set.

### GetLicenseKey

`func (o *LicenseInfoV2) GetLicenseKey() string`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *LicenseInfoV2) GetLicenseKeyOk() (*string, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *LicenseInfoV2) SetLicenseKey(v string)`

SetLicenseKey sets LicenseKey field to given value.

### HasLicenseKey

`func (o *LicenseInfoV2) HasLicenseKey() bool`

HasLicenseKey returns a boolean if a field has been set.

### GetLicenseMode

`func (o *LicenseInfoV2) GetLicenseMode() string`

GetLicenseMode returns the LicenseMode field if non-nil, zero value otherwise.

### GetLicenseModeOk

`func (o *LicenseInfoV2) GetLicenseModeOk() (*string, bool)`

GetLicenseModeOk returns a tuple with the LicenseMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseMode

`func (o *LicenseInfoV2) SetLicenseMode(v string)`

SetLicenseMode sets LicenseMode field to given value.

### HasLicenseMode

`func (o *LicenseInfoV2) HasLicenseMode() bool`

HasLicenseMode returns a boolean if a field has been set.

### GetLicensed

`func (o *LicenseInfoV2) GetLicensed() bool`

GetLicensed returns the Licensed field if non-nil, zero value otherwise.

### GetLicensedOk

`func (o *LicenseInfoV2) GetLicensedOk() (*bool, bool)`

GetLicensedOk returns a tuple with the Licensed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicensed

`func (o *LicenseInfoV2) SetLicensed(v bool)`

SetLicensed sets Licensed field to given value.

### HasLicensed

`func (o *LicenseInfoV2) HasLicensed() bool`

HasLicensed returns a boolean if a field has been set.

### GetSessionCollaborationEnabled

`func (o *LicenseInfoV2) GetSessionCollaborationEnabled() bool`

GetSessionCollaborationEnabled returns the SessionCollaborationEnabled field if non-nil, zero value otherwise.

### GetSessionCollaborationEnabledOk

`func (o *LicenseInfoV2) GetSessionCollaborationEnabledOk() (*bool, bool)`

GetSessionCollaborationEnabledOk returns a tuple with the SessionCollaborationEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionCollaborationEnabled

`func (o *LicenseInfoV2) SetSessionCollaborationEnabled(v bool)`

SetSessionCollaborationEnabled sets SessionCollaborationEnabled field to given value.

### HasSessionCollaborationEnabled

`func (o *LicenseInfoV2) HasSessionCollaborationEnabled() bool`

HasSessionCollaborationEnabled returns a boolean if a field has been set.

### GetSubscriptionSliceExpiry

`func (o *LicenseInfoV2) GetSubscriptionSliceExpiry() int64`

GetSubscriptionSliceExpiry returns the SubscriptionSliceExpiry field if non-nil, zero value otherwise.

### GetSubscriptionSliceExpiryOk

`func (o *LicenseInfoV2) GetSubscriptionSliceExpiryOk() (*int64, bool)`

GetSubscriptionSliceExpiryOk returns a tuple with the SubscriptionSliceExpiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionSliceExpiry

`func (o *LicenseInfoV2) SetSubscriptionSliceExpiry(v int64)`

SetSubscriptionSliceExpiry sets SubscriptionSliceExpiry field to given value.

### HasSubscriptionSliceExpiry

`func (o *LicenseInfoV2) HasSubscriptionSliceExpiry() bool`

HasSubscriptionSliceExpiry returns a boolean if a field has been set.

### GetUsageModel

`func (o *LicenseInfoV2) GetUsageModel() string`

GetUsageModel returns the UsageModel field if non-nil, zero value otherwise.

### GetUsageModelOk

`func (o *LicenseInfoV2) GetUsageModelOk() (*string, bool)`

GetUsageModelOk returns a tuple with the UsageModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageModel

`func (o *LicenseInfoV2) SetUsageModel(v string)`

SetUsageModel sets UsageModel field to given value.

### HasUsageModel

`func (o *LicenseInfoV2) HasUsageModel() bool`

HasUsageModel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


