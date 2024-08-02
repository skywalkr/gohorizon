# RestrictedClientDataV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlockSpecificVersions** | Pointer to **[]string** | Blocks specific versions of Horizon Client connections. | [optional] 
**Type** | Pointer to **string** | The type of Horizon Client. * WINDOWS: The client is the Horizon Client for Windows. * MAC: The client is the Horizon Client for MacOS. * HTMLACCESS: The client is a Web client. * LINUX: The client is the Horizon Client for Linux. * IOS: The client is the Horizon Client for IOS devices. * ANDROID: The client is the Horizon Client for Android. * WINSTORE: The client is the Horizon Client for Windows 10 UWP. * CHROME: The client is the Horizon Client for Chrome Native OS. * OTHER: Client type is other. | [optional] 
**Version** | Pointer to **string** | Blocks versions of Horizon Client connections which are older than the specified version. | [optional] 
**WarnSpecificVersions** | Pointer to **[]string** | Warns specific versions of Horizon Client connections. | [optional] 

## Methods

### NewRestrictedClientDataV2

`func NewRestrictedClientDataV2() *RestrictedClientDataV2`

NewRestrictedClientDataV2 instantiates a new RestrictedClientDataV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRestrictedClientDataV2WithDefaults

`func NewRestrictedClientDataV2WithDefaults() *RestrictedClientDataV2`

NewRestrictedClientDataV2WithDefaults instantiates a new RestrictedClientDataV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlockSpecificVersions

`func (o *RestrictedClientDataV2) GetBlockSpecificVersions() []string`

GetBlockSpecificVersions returns the BlockSpecificVersions field if non-nil, zero value otherwise.

### GetBlockSpecificVersionsOk

`func (o *RestrictedClientDataV2) GetBlockSpecificVersionsOk() (*[]string, bool)`

GetBlockSpecificVersionsOk returns a tuple with the BlockSpecificVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockSpecificVersions

`func (o *RestrictedClientDataV2) SetBlockSpecificVersions(v []string)`

SetBlockSpecificVersions sets BlockSpecificVersions field to given value.

### HasBlockSpecificVersions

`func (o *RestrictedClientDataV2) HasBlockSpecificVersions() bool`

HasBlockSpecificVersions returns a boolean if a field has been set.

### GetType

`func (o *RestrictedClientDataV2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RestrictedClientDataV2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RestrictedClientDataV2) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RestrictedClientDataV2) HasType() bool`

HasType returns a boolean if a field has been set.

### GetVersion

`func (o *RestrictedClientDataV2) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *RestrictedClientDataV2) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *RestrictedClientDataV2) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *RestrictedClientDataV2) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetWarnSpecificVersions

`func (o *RestrictedClientDataV2) GetWarnSpecificVersions() []string`

GetWarnSpecificVersions returns the WarnSpecificVersions field if non-nil, zero value otherwise.

### GetWarnSpecificVersionsOk

`func (o *RestrictedClientDataV2) GetWarnSpecificVersionsOk() (*[]string, bool)`

GetWarnSpecificVersionsOk returns a tuple with the WarnSpecificVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnSpecificVersions

`func (o *RestrictedClientDataV2) SetWarnSpecificVersions(v []string)`

SetWarnSpecificVersions sets WarnSpecificVersions field to given value.

### HasWarnSpecificVersions

`func (o *RestrictedClientDataV2) HasWarnSpecificVersions() bool`

HasWarnSpecificVersions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


