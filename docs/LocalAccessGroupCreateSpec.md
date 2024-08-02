# LocalAccessGroupCreateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | Access group description. | [optional] 
**Name** | **string** | Access group name. This property must contain only alphanumerics, underscores, and dashes. | 

## Methods

### NewLocalAccessGroupCreateSpec

`func NewLocalAccessGroupCreateSpec(name string, ) *LocalAccessGroupCreateSpec`

NewLocalAccessGroupCreateSpec instantiates a new LocalAccessGroupCreateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocalAccessGroupCreateSpecWithDefaults

`func NewLocalAccessGroupCreateSpecWithDefaults() *LocalAccessGroupCreateSpec`

NewLocalAccessGroupCreateSpecWithDefaults instantiates a new LocalAccessGroupCreateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *LocalAccessGroupCreateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LocalAccessGroupCreateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LocalAccessGroupCreateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LocalAccessGroupCreateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetName

`func (o *LocalAccessGroupCreateSpec) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LocalAccessGroupCreateSpec) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LocalAccessGroupCreateSpec) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


