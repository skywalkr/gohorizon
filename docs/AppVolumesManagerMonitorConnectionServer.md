# AppVolumesManagerMonitorConnectionServer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Connection server host name or IP address. | [optional] 
**Status** | Pointer to **string** | Status of the App Volumes Manager Connection with respect to this Connection Server. * ERROR: There has been no contact from the App Volumes Manager. * OK: The App Volumes Manager is working as expected. | [optional] 

## Methods

### NewAppVolumesManagerMonitorConnectionServer

`func NewAppVolumesManagerMonitorConnectionServer() *AppVolumesManagerMonitorConnectionServer`

NewAppVolumesManagerMonitorConnectionServer instantiates a new AppVolumesManagerMonitorConnectionServer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppVolumesManagerMonitorConnectionServerWithDefaults

`func NewAppVolumesManagerMonitorConnectionServerWithDefaults() *AppVolumesManagerMonitorConnectionServer`

NewAppVolumesManagerMonitorConnectionServerWithDefaults instantiates a new AppVolumesManagerMonitorConnectionServer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *AppVolumesManagerMonitorConnectionServer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AppVolumesManagerMonitorConnectionServer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AppVolumesManagerMonitorConnectionServer) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AppVolumesManagerMonitorConnectionServer) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *AppVolumesManagerMonitorConnectionServer) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AppVolumesManagerMonitorConnectionServer) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AppVolumesManagerMonitorConnectionServer) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AppVolumesManagerMonitorConnectionServer) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


