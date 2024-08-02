# AppVolumesManagerUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | **[]string** | Password of the account. | 
**Port** | Pointer to **int32** | Port of the app volumes manager to connect to. | [optional] 
**ServerName** | **string** | App Volumes Manager&#39;s server name or IP address. | 
**Username** | **string** | Username to login to App Volumes Manager | 

## Methods

### NewAppVolumesManagerUpdateSpec

`func NewAppVolumesManagerUpdateSpec(password []string, serverName string, username string, ) *AppVolumesManagerUpdateSpec`

NewAppVolumesManagerUpdateSpec instantiates a new AppVolumesManagerUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppVolumesManagerUpdateSpecWithDefaults

`func NewAppVolumesManagerUpdateSpecWithDefaults() *AppVolumesManagerUpdateSpec`

NewAppVolumesManagerUpdateSpecWithDefaults instantiates a new AppVolumesManagerUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *AppVolumesManagerUpdateSpec) GetPassword() []string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *AppVolumesManagerUpdateSpec) GetPasswordOk() (*[]string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *AppVolumesManagerUpdateSpec) SetPassword(v []string)`

SetPassword sets Password field to given value.


### GetPort

`func (o *AppVolumesManagerUpdateSpec) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *AppVolumesManagerUpdateSpec) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *AppVolumesManagerUpdateSpec) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *AppVolumesManagerUpdateSpec) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetServerName

`func (o *AppVolumesManagerUpdateSpec) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *AppVolumesManagerUpdateSpec) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *AppVolumesManagerUpdateSpec) SetServerName(v string)`

SetServerName sets ServerName field to given value.


### GetUsername

`func (o *AppVolumesManagerUpdateSpec) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *AppVolumesManagerUpdateSpec) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *AppVolumesManagerUpdateSpec) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


