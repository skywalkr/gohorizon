# ServerSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | Pointer to **[]string** | Password to use for the connection. This property is not required if the server is already added. | [optional] 
**Port** | Pointer to **int32** | Port of the server to connect to. | [optional] 
**ServerName** | Pointer to **string** | Url of the server without the protocol prefix. | [optional] 
**Username** | Pointer to **string** | User name to use for the connection. | [optional] 

## Methods

### NewServerSpec

`func NewServerSpec() *ServerSpec`

NewServerSpec instantiates a new ServerSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerSpecWithDefaults

`func NewServerSpecWithDefaults() *ServerSpec`

NewServerSpecWithDefaults instantiates a new ServerSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *ServerSpec) GetPassword() []string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *ServerSpec) GetPasswordOk() (*[]string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *ServerSpec) SetPassword(v []string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *ServerSpec) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetPort

`func (o *ServerSpec) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *ServerSpec) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *ServerSpec) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *ServerSpec) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetServerName

`func (o *ServerSpec) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *ServerSpec) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *ServerSpec) SetServerName(v string)`

SetServerName sets ServerName field to given value.

### HasServerName

`func (o *ServerSpec) HasServerName() bool`

HasServerName returns a boolean if a field has been set.

### GetUsername

`func (o *ServerSpec) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *ServerSpec) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *ServerSpec) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *ServerSpec) HasUsername() bool`

HasUsername returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


