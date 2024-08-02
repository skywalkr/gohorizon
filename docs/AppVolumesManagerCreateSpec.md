# AppVolumesManagerCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | **[]string** | Password of the account. | 
**Port** | Pointer to **int32** | Port of the App Volumes manager to connect to. | [optional] 
**ServerName** | **string** | App Volumes Manager&#39;s server name or IP address. | 
**Username** | **string** | Username to login to App Volumes Manager | 

## Methods

### NewAppVolumesManagerCreateSpec

`func NewAppVolumesManagerCreateSpec(password []string, serverName string, username string, ) *AppVolumesManagerCreateSpec`

NewAppVolumesManagerCreateSpec instantiates a new AppVolumesManagerCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppVolumesManagerCreateSpecWithDefaults

`func NewAppVolumesManagerCreateSpecWithDefaults() *AppVolumesManagerCreateSpec`

NewAppVolumesManagerCreateSpecWithDefaults instantiates a new AppVolumesManagerCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *AppVolumesManagerCreateSpec) GetPassword() []string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *AppVolumesManagerCreateSpec) GetPasswordOk() (*[]string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *AppVolumesManagerCreateSpec) SetPassword(v []string)`

SetPassword sets Password field to given value.


### GetPort

`func (o *AppVolumesManagerCreateSpec) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *AppVolumesManagerCreateSpec) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *AppVolumesManagerCreateSpec) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *AppVolumesManagerCreateSpec) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetServerName

`func (o *AppVolumesManagerCreateSpec) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *AppVolumesManagerCreateSpec) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *AppVolumesManagerCreateSpec) SetServerName(v string)`

SetServerName sets ServerName field to given value.


### GetUsername

`func (o *AppVolumesManagerCreateSpec) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *AppVolumesManagerCreateSpec) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *AppVolumesManagerCreateSpec) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


