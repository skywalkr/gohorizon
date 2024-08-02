# LocalAccessGroupInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deletable** | Pointer to **bool** | Indicates whether this access group can be deleted. | [optional] 
**Description** | Pointer to **string** | Access group description. | [optional] 
**Id** | Pointer to **string** | Unique ID representing this access group. | [optional] 
**Name** | Pointer to **string** | Access group name. | [optional] 
**PermissionIds** | Pointer to **[]string** | List of permission ids associated with the access group | [optional] 

## Methods

### NewLocalAccessGroupInfoV2

`func NewLocalAccessGroupInfoV2() *LocalAccessGroupInfoV2`

NewLocalAccessGroupInfoV2 instantiates a new LocalAccessGroupInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocalAccessGroupInfoV2WithDefaults

`func NewLocalAccessGroupInfoV2WithDefaults() *LocalAccessGroupInfoV2`

NewLocalAccessGroupInfoV2WithDefaults instantiates a new LocalAccessGroupInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeletable

`func (o *LocalAccessGroupInfoV2) GetDeletable() bool`

GetDeletable returns the Deletable field if non-nil, zero value otherwise.

### GetDeletableOk

`func (o *LocalAccessGroupInfoV2) GetDeletableOk() (*bool, bool)`

GetDeletableOk returns a tuple with the Deletable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletable

`func (o *LocalAccessGroupInfoV2) SetDeletable(v bool)`

SetDeletable sets Deletable field to given value.

### HasDeletable

`func (o *LocalAccessGroupInfoV2) HasDeletable() bool`

HasDeletable returns a boolean if a field has been set.

### GetDescription

`func (o *LocalAccessGroupInfoV2) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LocalAccessGroupInfoV2) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LocalAccessGroupInfoV2) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LocalAccessGroupInfoV2) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *LocalAccessGroupInfoV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LocalAccessGroupInfoV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LocalAccessGroupInfoV2) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *LocalAccessGroupInfoV2) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *LocalAccessGroupInfoV2) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LocalAccessGroupInfoV2) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LocalAccessGroupInfoV2) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *LocalAccessGroupInfoV2) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPermissionIds

`func (o *LocalAccessGroupInfoV2) GetPermissionIds() []string`

GetPermissionIds returns the PermissionIds field if non-nil, zero value otherwise.

### GetPermissionIdsOk

`func (o *LocalAccessGroupInfoV2) GetPermissionIdsOk() (*[]string, bool)`

GetPermissionIdsOk returns a tuple with the PermissionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionIds

`func (o *LocalAccessGroupInfoV2) SetPermissionIds(v []string)`

SetPermissionIds sets PermissionIds field to given value.

### HasPermissionIds

`func (o *LocalAccessGroupInfoV2) HasPermissionIds() bool`

HasPermissionIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


