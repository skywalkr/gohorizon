# NetworkInterfaceCardInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique ID representing the network interface card. | [optional] 
**MacAddress** | Pointer to **string** | Network interface card MAC address. | [optional] 
**Name** | Pointer to **string** | Network interface card name. | [optional] 
**NetworkType** | Pointer to **string** | Type of network interface card. * NETWORK: Standard network. * OPAQUE_NETWORK: Opaque network. * DISTRUBUTED_VIRTUAL_PORT_GROUP: DVS Port group. | [optional] 

## Methods

### NewNetworkInterfaceCardInfoV2

`func NewNetworkInterfaceCardInfoV2() *NetworkInterfaceCardInfoV2`

NewNetworkInterfaceCardInfoV2 instantiates a new NetworkInterfaceCardInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkInterfaceCardInfoV2WithDefaults

`func NewNetworkInterfaceCardInfoV2WithDefaults() *NetworkInterfaceCardInfoV2`

NewNetworkInterfaceCardInfoV2WithDefaults instantiates a new NetworkInterfaceCardInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *NetworkInterfaceCardInfoV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NetworkInterfaceCardInfoV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NetworkInterfaceCardInfoV2) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *NetworkInterfaceCardInfoV2) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMacAddress

`func (o *NetworkInterfaceCardInfoV2) GetMacAddress() string`

GetMacAddress returns the MacAddress field if non-nil, zero value otherwise.

### GetMacAddressOk

`func (o *NetworkInterfaceCardInfoV2) GetMacAddressOk() (*string, bool)`

GetMacAddressOk returns a tuple with the MacAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMacAddress

`func (o *NetworkInterfaceCardInfoV2) SetMacAddress(v string)`

SetMacAddress sets MacAddress field to given value.

### HasMacAddress

`func (o *NetworkInterfaceCardInfoV2) HasMacAddress() bool`

HasMacAddress returns a boolean if a field has been set.

### GetName

`func (o *NetworkInterfaceCardInfoV2) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *NetworkInterfaceCardInfoV2) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *NetworkInterfaceCardInfoV2) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *NetworkInterfaceCardInfoV2) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNetworkType

`func (o *NetworkInterfaceCardInfoV2) GetNetworkType() string`

GetNetworkType returns the NetworkType field if non-nil, zero value otherwise.

### GetNetworkTypeOk

`func (o *NetworkInterfaceCardInfoV2) GetNetworkTypeOk() (*string, bool)`

GetNetworkTypeOk returns a tuple with the NetworkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkType

`func (o *NetworkInterfaceCardInfoV2) SetNetworkType(v string)`

SetNetworkType sets NetworkType field to given value.

### HasNetworkType

`func (o *NetworkInterfaceCardInfoV2) HasNetworkType() bool`

HasNetworkType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


