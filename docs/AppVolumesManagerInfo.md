# AppVolumesManagerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique Id of the App Volumes Manager. | [optional] 
**Port** | Pointer to **int32** | Port of the App Volumes Manager to connect to. | [optional] 
**ServerName** | Pointer to **string** | App Volumes Manager&#39;s server name or IP address. | [optional] 
**Username** | Pointer to **string** | Username to login to App Volumes Manager. | [optional] 

## Methods

### NewAppVolumesManagerInfo

`func NewAppVolumesManagerInfo() *AppVolumesManagerInfo`

NewAppVolumesManagerInfo instantiates a new AppVolumesManagerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppVolumesManagerInfoWithDefaults

`func NewAppVolumesManagerInfoWithDefaults() *AppVolumesManagerInfo`

NewAppVolumesManagerInfoWithDefaults instantiates a new AppVolumesManagerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppVolumesManagerInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppVolumesManagerInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppVolumesManagerInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppVolumesManagerInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPort

`func (o *AppVolumesManagerInfo) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *AppVolumesManagerInfo) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *AppVolumesManagerInfo) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *AppVolumesManagerInfo) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetServerName

`func (o *AppVolumesManagerInfo) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *AppVolumesManagerInfo) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *AppVolumesManagerInfo) SetServerName(v string)`

SetServerName sets ServerName field to given value.

### HasServerName

`func (o *AppVolumesManagerInfo) HasServerName() bool`

HasServerName returns a boolean if a field has been set.

### GetUsername

`func (o *AppVolumesManagerInfo) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *AppVolumesManagerInfo) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *AppVolumesManagerInfo) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *AppVolumesManagerInfo) HasUsername() bool`

HasUsername returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


