# PreLogonSettingsInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiSessionTimeoutMinutes** | Pointer to **int32** | Determines how long (in minutes) a refresh token is valid for and an idle View API session continues before the session times out.  | [optional] 
**ConsoleSessionTimeoutMinutes** | Pointer to **int32** | Determines how long an idle admin console session continues before the session times out. | [optional] 
**DisplayPreLoginAdminBanner** | Pointer to **bool** | Enable/disable pre login message pop up before logging into Horizon admin console | [optional] 
**EnableUserNameCaching** | Pointer to **bool** | UI Client provide &#39;remember me&#39; option when this is set to true | [optional] 
**PreLoginAdminBannerHeader** | Pointer to **string** | The warning pop up header to be displayed before logging into Horizon admin console, if pre login message pop up is activated for the same. | [optional] 
**PreLoginAdminBannerMessage** | Pointer to **string** | The warning pop up message to be displayed before logging into Horizon admin console, if pre login message pop up is activated for the same. | [optional] 

## Methods

### NewPreLogonSettingsInfo

`func NewPreLogonSettingsInfo() *PreLogonSettingsInfo`

NewPreLogonSettingsInfo instantiates a new PreLogonSettingsInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPreLogonSettingsInfoWithDefaults

`func NewPreLogonSettingsInfoWithDefaults() *PreLogonSettingsInfo`

NewPreLogonSettingsInfoWithDefaults instantiates a new PreLogonSettingsInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiSessionTimeoutMinutes

`func (o *PreLogonSettingsInfo) GetApiSessionTimeoutMinutes() int32`

GetApiSessionTimeoutMinutes returns the ApiSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetApiSessionTimeoutMinutesOk

`func (o *PreLogonSettingsInfo) GetApiSessionTimeoutMinutesOk() (*int32, bool)`

GetApiSessionTimeoutMinutesOk returns a tuple with the ApiSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiSessionTimeoutMinutes

`func (o *PreLogonSettingsInfo) SetApiSessionTimeoutMinutes(v int32)`

SetApiSessionTimeoutMinutes sets ApiSessionTimeoutMinutes field to given value.

### HasApiSessionTimeoutMinutes

`func (o *PreLogonSettingsInfo) HasApiSessionTimeoutMinutes() bool`

HasApiSessionTimeoutMinutes returns a boolean if a field has been set.

### GetConsoleSessionTimeoutMinutes

`func (o *PreLogonSettingsInfo) GetConsoleSessionTimeoutMinutes() int32`

GetConsoleSessionTimeoutMinutes returns the ConsoleSessionTimeoutMinutes field if non-nil, zero value otherwise.

### GetConsoleSessionTimeoutMinutesOk

`func (o *PreLogonSettingsInfo) GetConsoleSessionTimeoutMinutesOk() (*int32, bool)`

GetConsoleSessionTimeoutMinutesOk returns a tuple with the ConsoleSessionTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsoleSessionTimeoutMinutes

`func (o *PreLogonSettingsInfo) SetConsoleSessionTimeoutMinutes(v int32)`

SetConsoleSessionTimeoutMinutes sets ConsoleSessionTimeoutMinutes field to given value.

### HasConsoleSessionTimeoutMinutes

`func (o *PreLogonSettingsInfo) HasConsoleSessionTimeoutMinutes() bool`

HasConsoleSessionTimeoutMinutes returns a boolean if a field has been set.

### GetDisplayPreLoginAdminBanner

`func (o *PreLogonSettingsInfo) GetDisplayPreLoginAdminBanner() bool`

GetDisplayPreLoginAdminBanner returns the DisplayPreLoginAdminBanner field if non-nil, zero value otherwise.

### GetDisplayPreLoginAdminBannerOk

`func (o *PreLogonSettingsInfo) GetDisplayPreLoginAdminBannerOk() (*bool, bool)`

GetDisplayPreLoginAdminBannerOk returns a tuple with the DisplayPreLoginAdminBanner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayPreLoginAdminBanner

`func (o *PreLogonSettingsInfo) SetDisplayPreLoginAdminBanner(v bool)`

SetDisplayPreLoginAdminBanner sets DisplayPreLoginAdminBanner field to given value.

### HasDisplayPreLoginAdminBanner

`func (o *PreLogonSettingsInfo) HasDisplayPreLoginAdminBanner() bool`

HasDisplayPreLoginAdminBanner returns a boolean if a field has been set.

### GetEnableUserNameCaching

`func (o *PreLogonSettingsInfo) GetEnableUserNameCaching() bool`

GetEnableUserNameCaching returns the EnableUserNameCaching field if non-nil, zero value otherwise.

### GetEnableUserNameCachingOk

`func (o *PreLogonSettingsInfo) GetEnableUserNameCachingOk() (*bool, bool)`

GetEnableUserNameCachingOk returns a tuple with the EnableUserNameCaching field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableUserNameCaching

`func (o *PreLogonSettingsInfo) SetEnableUserNameCaching(v bool)`

SetEnableUserNameCaching sets EnableUserNameCaching field to given value.

### HasEnableUserNameCaching

`func (o *PreLogonSettingsInfo) HasEnableUserNameCaching() bool`

HasEnableUserNameCaching returns a boolean if a field has been set.

### GetPreLoginAdminBannerHeader

`func (o *PreLogonSettingsInfo) GetPreLoginAdminBannerHeader() string`

GetPreLoginAdminBannerHeader returns the PreLoginAdminBannerHeader field if non-nil, zero value otherwise.

### GetPreLoginAdminBannerHeaderOk

`func (o *PreLogonSettingsInfo) GetPreLoginAdminBannerHeaderOk() (*string, bool)`

GetPreLoginAdminBannerHeaderOk returns a tuple with the PreLoginAdminBannerHeader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreLoginAdminBannerHeader

`func (o *PreLogonSettingsInfo) SetPreLoginAdminBannerHeader(v string)`

SetPreLoginAdminBannerHeader sets PreLoginAdminBannerHeader field to given value.

### HasPreLoginAdminBannerHeader

`func (o *PreLogonSettingsInfo) HasPreLoginAdminBannerHeader() bool`

HasPreLoginAdminBannerHeader returns a boolean if a field has been set.

### GetPreLoginAdminBannerMessage

`func (o *PreLogonSettingsInfo) GetPreLoginAdminBannerMessage() string`

GetPreLoginAdminBannerMessage returns the PreLoginAdminBannerMessage field if non-nil, zero value otherwise.

### GetPreLoginAdminBannerMessageOk

`func (o *PreLogonSettingsInfo) GetPreLoginAdminBannerMessageOk() (*string, bool)`

GetPreLoginAdminBannerMessageOk returns a tuple with the PreLoginAdminBannerMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreLoginAdminBannerMessage

`func (o *PreLogonSettingsInfo) SetPreLoginAdminBannerMessage(v string)`

SetPreLoginAdminBannerMessage sets PreLoginAdminBannerMessage field to given value.

### HasPreLoginAdminBannerMessage

`func (o *PreLogonSettingsInfo) HasPreLoginAdminBannerMessage() bool`

HasPreLoginAdminBannerMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


