# AppVolumesApplicationInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvmShortcutId** | Pointer to **string** | Shortcut ID of AVM managed application. | [optional] 
**ExecutablePath** | Pointer to **string** | Path to application executable. | [optional] 
**FileTypes** | Pointer to [**[]ApplicationFileTypeData**](ApplicationFileTypeData.md) | Set of file types reported by the application as supported. If unset, this application does not present any file type support. | [optional] 
**Name** | Pointer to **string** | Application name information, as sent by RDSServer/machine during application discovery. | [optional] 
**OtherFileTypes** | Pointer to [**[]ApplicationOtherFileTypeData**](ApplicationOtherFileTypeData.md) | This represents the different file types reported by Application that can be passed from horizon agent to horizon client via connection server. If unset, this application does not present any other file type support. | [optional] 
**Publisher** | Pointer to **string** | Application publisher | [optional] 
**Version** | Pointer to **string** | Application version. | [optional] 

## Methods

### NewAppVolumesApplicationInfo

`func NewAppVolumesApplicationInfo() *AppVolumesApplicationInfo`

NewAppVolumesApplicationInfo instantiates a new AppVolumesApplicationInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppVolumesApplicationInfoWithDefaults

`func NewAppVolumesApplicationInfoWithDefaults() *AppVolumesApplicationInfo`

NewAppVolumesApplicationInfoWithDefaults instantiates a new AppVolumesApplicationInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvmShortcutId

`func (o *AppVolumesApplicationInfo) GetAvmShortcutId() string`

GetAvmShortcutId returns the AvmShortcutId field if non-nil, zero value otherwise.

### GetAvmShortcutIdOk

`func (o *AppVolumesApplicationInfo) GetAvmShortcutIdOk() (*string, bool)`

GetAvmShortcutIdOk returns a tuple with the AvmShortcutId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvmShortcutId

`func (o *AppVolumesApplicationInfo) SetAvmShortcutId(v string)`

SetAvmShortcutId sets AvmShortcutId field to given value.

### HasAvmShortcutId

`func (o *AppVolumesApplicationInfo) HasAvmShortcutId() bool`

HasAvmShortcutId returns a boolean if a field has been set.

### GetExecutablePath

`func (o *AppVolumesApplicationInfo) GetExecutablePath() string`

GetExecutablePath returns the ExecutablePath field if non-nil, zero value otherwise.

### GetExecutablePathOk

`func (o *AppVolumesApplicationInfo) GetExecutablePathOk() (*string, bool)`

GetExecutablePathOk returns a tuple with the ExecutablePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutablePath

`func (o *AppVolumesApplicationInfo) SetExecutablePath(v string)`

SetExecutablePath sets ExecutablePath field to given value.

### HasExecutablePath

`func (o *AppVolumesApplicationInfo) HasExecutablePath() bool`

HasExecutablePath returns a boolean if a field has been set.

### GetFileTypes

`func (o *AppVolumesApplicationInfo) GetFileTypes() []ApplicationFileTypeData`

GetFileTypes returns the FileTypes field if non-nil, zero value otherwise.

### GetFileTypesOk

`func (o *AppVolumesApplicationInfo) GetFileTypesOk() (*[]ApplicationFileTypeData, bool)`

GetFileTypesOk returns a tuple with the FileTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileTypes

`func (o *AppVolumesApplicationInfo) SetFileTypes(v []ApplicationFileTypeData)`

SetFileTypes sets FileTypes field to given value.

### HasFileTypes

`func (o *AppVolumesApplicationInfo) HasFileTypes() bool`

HasFileTypes returns a boolean if a field has been set.

### GetName

`func (o *AppVolumesApplicationInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AppVolumesApplicationInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AppVolumesApplicationInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AppVolumesApplicationInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetOtherFileTypes

`func (o *AppVolumesApplicationInfo) GetOtherFileTypes() []ApplicationOtherFileTypeData`

GetOtherFileTypes returns the OtherFileTypes field if non-nil, zero value otherwise.

### GetOtherFileTypesOk

`func (o *AppVolumesApplicationInfo) GetOtherFileTypesOk() (*[]ApplicationOtherFileTypeData, bool)`

GetOtherFileTypesOk returns a tuple with the OtherFileTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherFileTypes

`func (o *AppVolumesApplicationInfo) SetOtherFileTypes(v []ApplicationOtherFileTypeData)`

SetOtherFileTypes sets OtherFileTypes field to given value.

### HasOtherFileTypes

`func (o *AppVolumesApplicationInfo) HasOtherFileTypes() bool`

HasOtherFileTypes returns a boolean if a field has been set.

### GetPublisher

`func (o *AppVolumesApplicationInfo) GetPublisher() string`

GetPublisher returns the Publisher field if non-nil, zero value otherwise.

### GetPublisherOk

`func (o *AppVolumesApplicationInfo) GetPublisherOk() (*string, bool)`

GetPublisherOk returns a tuple with the Publisher field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublisher

`func (o *AppVolumesApplicationInfo) SetPublisher(v string)`

SetPublisher sets Publisher field to given value.

### HasPublisher

`func (o *AppVolumesApplicationInfo) HasPublisher() bool`

HasPublisher returns a boolean if a field has been set.

### GetVersion

`func (o *AppVolumesApplicationInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *AppVolumesApplicationInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *AppVolumesApplicationInfo) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *AppVolumesApplicationInfo) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


