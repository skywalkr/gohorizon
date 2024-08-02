# SecurityConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientProperties** | Pointer to [**ClientProperties**](ClientProperties.md) |  | [optional] 
**ServerProperties** | Pointer to [**ServerProperties**](ServerProperties.md) |  | [optional] 

## Methods

### NewSecurityConfiguration

`func NewSecurityConfiguration() *SecurityConfiguration`

NewSecurityConfiguration instantiates a new SecurityConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecurityConfigurationWithDefaults

`func NewSecurityConfigurationWithDefaults() *SecurityConfiguration`

NewSecurityConfigurationWithDefaults instantiates a new SecurityConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientProperties

`func (o *SecurityConfiguration) GetClientProperties() ClientProperties`

GetClientProperties returns the ClientProperties field if non-nil, zero value otherwise.

### GetClientPropertiesOk

`func (o *SecurityConfiguration) GetClientPropertiesOk() (*ClientProperties, bool)`

GetClientPropertiesOk returns a tuple with the ClientProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientProperties

`func (o *SecurityConfiguration) SetClientProperties(v ClientProperties)`

SetClientProperties sets ClientProperties field to given value.

### HasClientProperties

`func (o *SecurityConfiguration) HasClientProperties() bool`

HasClientProperties returns a boolean if a field has been set.

### GetServerProperties

`func (o *SecurityConfiguration) GetServerProperties() ServerProperties`

GetServerProperties returns the ServerProperties field if non-nil, zero value otherwise.

### GetServerPropertiesOk

`func (o *SecurityConfiguration) GetServerPropertiesOk() (*ServerProperties, bool)`

GetServerPropertiesOk returns a tuple with the ServerProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerProperties

`func (o *SecurityConfiguration) SetServerProperties(v ServerProperties)`

SetServerProperties sets ServerProperties field to given value.

### HasServerProperties

`func (o *SecurityConfiguration) HasServerProperties() bool`

HasServerProperties returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


