# APIError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorKey** | Pointer to **string** | Error key configured in message bundle. | [optional] 
**ErrorMessage** | Pointer to **string** | Error message translated in user&#39;s locale. | [optional] 

## Methods

### NewAPIError

`func NewAPIError() *APIError`

NewAPIError instantiates a new APIError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAPIErrorWithDefaults

`func NewAPIErrorWithDefaults() *APIError`

NewAPIErrorWithDefaults instantiates a new APIError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorKey

`func (o *APIError) GetErrorKey() string`

GetErrorKey returns the ErrorKey field if non-nil, zero value otherwise.

### GetErrorKeyOk

`func (o *APIError) GetErrorKeyOk() (*string, bool)`

GetErrorKeyOk returns a tuple with the ErrorKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorKey

`func (o *APIError) SetErrorKey(v string)`

SetErrorKey sets ErrorKey field to given value.

### HasErrorKey

`func (o *APIError) HasErrorKey() bool`

HasErrorKey returns a boolean if a field has been set.

### GetErrorMessage

`func (o *APIError) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *APIError) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *APIError) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *APIError) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


