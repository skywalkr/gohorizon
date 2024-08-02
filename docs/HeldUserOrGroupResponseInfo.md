# HeldUserOrGroupResponseInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdUserOrGroupId** | Pointer to **string** | Unique SID representing held user or group. | [optional] 
**Errors** | Pointer to [**[]APIError**](APIError.md) | List of error objects containing error key and error message. | [optional] 
**MachinesData** | Pointer to [**[]HeldVMInfo**](HeldVMInfo.md) | List of objects containing information related to held Virtual Machines. | [optional] 
**StatusCode** | Pointer to **int32** | Response HTTP status code of the operation. | [optional] 
**Timestamp** | Pointer to **int64** | Timestamp in milliseconds when the operation failed. Measured as epoch time. | [optional] 

## Methods

### NewHeldUserOrGroupResponseInfo

`func NewHeldUserOrGroupResponseInfo() *HeldUserOrGroupResponseInfo`

NewHeldUserOrGroupResponseInfo instantiates a new HeldUserOrGroupResponseInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHeldUserOrGroupResponseInfoWithDefaults

`func NewHeldUserOrGroupResponseInfoWithDefaults() *HeldUserOrGroupResponseInfo`

NewHeldUserOrGroupResponseInfoWithDefaults instantiates a new HeldUserOrGroupResponseInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdUserOrGroupId

`func (o *HeldUserOrGroupResponseInfo) GetAdUserOrGroupId() string`

GetAdUserOrGroupId returns the AdUserOrGroupId field if non-nil, zero value otherwise.

### GetAdUserOrGroupIdOk

`func (o *HeldUserOrGroupResponseInfo) GetAdUserOrGroupIdOk() (*string, bool)`

GetAdUserOrGroupIdOk returns a tuple with the AdUserOrGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdUserOrGroupId

`func (o *HeldUserOrGroupResponseInfo) SetAdUserOrGroupId(v string)`

SetAdUserOrGroupId sets AdUserOrGroupId field to given value.

### HasAdUserOrGroupId

`func (o *HeldUserOrGroupResponseInfo) HasAdUserOrGroupId() bool`

HasAdUserOrGroupId returns a boolean if a field has been set.

### GetErrors

`func (o *HeldUserOrGroupResponseInfo) GetErrors() []APIError`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *HeldUserOrGroupResponseInfo) GetErrorsOk() (*[]APIError, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *HeldUserOrGroupResponseInfo) SetErrors(v []APIError)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *HeldUserOrGroupResponseInfo) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetMachinesData

`func (o *HeldUserOrGroupResponseInfo) GetMachinesData() []HeldVMInfo`

GetMachinesData returns the MachinesData field if non-nil, zero value otherwise.

### GetMachinesDataOk

`func (o *HeldUserOrGroupResponseInfo) GetMachinesDataOk() (*[]HeldVMInfo, bool)`

GetMachinesDataOk returns a tuple with the MachinesData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachinesData

`func (o *HeldUserOrGroupResponseInfo) SetMachinesData(v []HeldVMInfo)`

SetMachinesData sets MachinesData field to given value.

### HasMachinesData

`func (o *HeldUserOrGroupResponseInfo) HasMachinesData() bool`

HasMachinesData returns a boolean if a field has been set.

### GetStatusCode

`func (o *HeldUserOrGroupResponseInfo) GetStatusCode() int32`

GetStatusCode returns the StatusCode field if non-nil, zero value otherwise.

### GetStatusCodeOk

`func (o *HeldUserOrGroupResponseInfo) GetStatusCodeOk() (*int32, bool)`

GetStatusCodeOk returns a tuple with the StatusCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusCode

`func (o *HeldUserOrGroupResponseInfo) SetStatusCode(v int32)`

SetStatusCode sets StatusCode field to given value.

### HasStatusCode

`func (o *HeldUserOrGroupResponseInfo) HasStatusCode() bool`

HasStatusCode returns a boolean if a field has been set.

### GetTimestamp

`func (o *HeldUserOrGroupResponseInfo) GetTimestamp() int64`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *HeldUserOrGroupResponseInfo) GetTimestampOk() (*int64, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *HeldUserOrGroupResponseInfo) SetTimestamp(v int64)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *HeldUserOrGroupResponseInfo) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


