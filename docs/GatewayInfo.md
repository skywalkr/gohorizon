# GatewayInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **string** | Gateway host name or IP address. | [optional] 
**Id** | Pointer to **string** | Unique ID of the Gateway. | [optional] 
**Internal** | Pointer to **bool** | Indicates whether the gateway is internal. | [optional] 
**Name** | Pointer to **string** | Gateway name. | [optional] 
**Type** | Pointer to **string** | Type of the Gateway. * UAG: Unified Access Gateway type. * F5: F5 Gateway type. * SG: SG type is for Security Server. * SG_COHOSTED: SG-cohosted type is for Cohosted CS as gateway. * UNKNOWN: Unknown type. | [optional] 
**Version** | Pointer to **string** | Version of the Gateway. | [optional] 

## Methods

### NewGatewayInfo

`func NewGatewayInfo() *GatewayInfo`

NewGatewayInfo instantiates a new GatewayInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGatewayInfoWithDefaults

`func NewGatewayInfoWithDefaults() *GatewayInfo`

NewGatewayInfoWithDefaults instantiates a new GatewayInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *GatewayInfo) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *GatewayInfo) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *GatewayInfo) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *GatewayInfo) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetId

`func (o *GatewayInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GatewayInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GatewayInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GatewayInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetInternal

`func (o *GatewayInfo) GetInternal() bool`

GetInternal returns the Internal field if non-nil, zero value otherwise.

### GetInternalOk

`func (o *GatewayInfo) GetInternalOk() (*bool, bool)`

GetInternalOk returns a tuple with the Internal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternal

`func (o *GatewayInfo) SetInternal(v bool)`

SetInternal sets Internal field to given value.

### HasInternal

`func (o *GatewayInfo) HasInternal() bool`

HasInternal returns a boolean if a field has been set.

### GetName

`func (o *GatewayInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GatewayInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GatewayInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GatewayInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *GatewayInfo) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GatewayInfo) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GatewayInfo) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *GatewayInfo) HasType() bool`

HasType returns a boolean if a field has been set.

### GetVersion

`func (o *GatewayInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *GatewayInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *GatewayInfo) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *GatewayInfo) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


