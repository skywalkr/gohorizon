# AppVolumesManagerMonitorInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionServers** | Pointer to [**[]AppVolumesManagerMonitorConnectionServer**](AppVolumesManagerMonitorConnectionServer.md) | Information about the App volumes Manager connections from each of the connection servers. | [optional] 
**Description** | Pointer to **string** | App volumes Manager Connection description. * SUCCESS: No problem detected. * PROBLEM: Problem detected in connecting to App Volumes Manager. | [optional] 
**Id** | Pointer to **string** | Unique ID of the App volumes Manager. | [optional] 
**Status** | Pointer to **string** | Combined status of the App volumes Manager with respect to all the CS. Set to OK if App volumes Manager is connected with all CS. * ERROR: There has been no contact from the App Volumes Manager. * OK: The App Volumes Manager is working as expected. | [optional] 
**Url** | Pointer to **string** | App volumes Manager url. | [optional] 
**Version** | Pointer to **string** | App volumes Manager version. | [optional] 

## Methods

### NewAppVolumesManagerMonitorInfo

`func NewAppVolumesManagerMonitorInfo() *AppVolumesManagerMonitorInfo`

NewAppVolumesManagerMonitorInfo instantiates a new AppVolumesManagerMonitorInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppVolumesManagerMonitorInfoWithDefaults

`func NewAppVolumesManagerMonitorInfoWithDefaults() *AppVolumesManagerMonitorInfo`

NewAppVolumesManagerMonitorInfoWithDefaults instantiates a new AppVolumesManagerMonitorInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionServers

`func (o *AppVolumesManagerMonitorInfo) GetConnectionServers() []AppVolumesManagerMonitorConnectionServer`

GetConnectionServers returns the ConnectionServers field if non-nil, zero value otherwise.

### GetConnectionServersOk

`func (o *AppVolumesManagerMonitorInfo) GetConnectionServersOk() (*[]AppVolumesManagerMonitorConnectionServer, bool)`

GetConnectionServersOk returns a tuple with the ConnectionServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionServers

`func (o *AppVolumesManagerMonitorInfo) SetConnectionServers(v []AppVolumesManagerMonitorConnectionServer)`

SetConnectionServers sets ConnectionServers field to given value.

### HasConnectionServers

`func (o *AppVolumesManagerMonitorInfo) HasConnectionServers() bool`

HasConnectionServers returns a boolean if a field has been set.

### GetDescription

`func (o *AppVolumesManagerMonitorInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AppVolumesManagerMonitorInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AppVolumesManagerMonitorInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AppVolumesManagerMonitorInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *AppVolumesManagerMonitorInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppVolumesManagerMonitorInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppVolumesManagerMonitorInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppVolumesManagerMonitorInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetStatus

`func (o *AppVolumesManagerMonitorInfo) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AppVolumesManagerMonitorInfo) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AppVolumesManagerMonitorInfo) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AppVolumesManagerMonitorInfo) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUrl

`func (o *AppVolumesManagerMonitorInfo) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *AppVolumesManagerMonitorInfo) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *AppVolumesManagerMonitorInfo) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *AppVolumesManagerMonitorInfo) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetVersion

`func (o *AppVolumesManagerMonitorInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *AppVolumesManagerMonitorInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *AppVolumesManagerMonitorInfo) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *AppVolumesManagerMonitorInfo) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


