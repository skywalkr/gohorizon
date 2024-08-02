# ADContainerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rdn** | Pointer to **string** | The rdn of the active directory container, relative to the root of the domain. | [optional] 

## Methods

### NewADContainerInfo

`func NewADContainerInfo() *ADContainerInfo`

NewADContainerInfo instantiates a new ADContainerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewADContainerInfoWithDefaults

`func NewADContainerInfoWithDefaults() *ADContainerInfo`

NewADContainerInfoWithDefaults instantiates a new ADContainerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRdn

`func (o *ADContainerInfo) GetRdn() string`

GetRdn returns the Rdn field if non-nil, zero value otherwise.

### GetRdnOk

`func (o *ADContainerInfo) GetRdnOk() (*string, bool)`

GetRdnOk returns a tuple with the Rdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRdn

`func (o *ADContainerInfo) SetRdn(v string)`

SetRdn sets Rdn field to given value.

### HasRdn

`func (o *ADContainerInfo) HasRdn() bool`

HasRdn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


