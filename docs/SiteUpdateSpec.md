# SiteUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | Detailed description of the site. | [optional] 
**Name** | **string** | The name of the site. | 

## Methods

### NewSiteUpdateSpec

`func NewSiteUpdateSpec(name string, ) *SiteUpdateSpec`

NewSiteUpdateSpec instantiates a new SiteUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSiteUpdateSpecWithDefaults

`func NewSiteUpdateSpecWithDefaults() *SiteUpdateSpec`

NewSiteUpdateSpecWithDefaults instantiates a new SiteUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *SiteUpdateSpec) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SiteUpdateSpec) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SiteUpdateSpec) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SiteUpdateSpec) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetName

`func (o *SiteUpdateSpec) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SiteUpdateSpec) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SiteUpdateSpec) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


