# GatewayMonitorInfoV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveConnectionCount** | Pointer to **int32** | Number of active connections for the gateway. Includes PCoIP and BLAST connection counts. | [optional] 
**BlastConnectionCount** | Pointer to **int32** | Number of BLAST connections for the gateway. | [optional] 
**Details** | Pointer to [**GatewayMonitorDetails**](GatewayMonitorDetails.md) |  | [optional] 
**Id** | Pointer to **string** | Unique ID of the Gateway. | [optional] 
**LastUpdatedTimestamp** | Pointer to **int64** | The timestamp in milliseconds when the last update was obtained. Measured as epoch time. | [optional] 
**Name** | Pointer to **string** | Gateway name. | [optional] 
**PcoipConnectionCount** | Pointer to **int32** | Number of PCoIP connections for the gateway. | [optional] 
**Status** | Pointer to **string** | Status of the Gateway. * NOT_CONTACTED: There has been no contact from the gateway. * PROBLEM: The gateway has reported a problem. * STALE: Gateway is stale. Gateway will be marked as stale when Connection Server does not receive any request from the Gateway in last two successive intervals. * OK: The Gateway is working as expected. | [optional] 
**UnrecognizedPcoipRequestsCount** | Pointer to **int32** | Number of unrecognized PCoIP Secure Gateway requests. | [optional] 
**UnrecognizedTunnelRequestsCount** | Pointer to **int32** | Number of unrecognized Tunnel requests. | [optional] 
**UnrecognizedXmlapiRequestsCount** | Pointer to **int32** | Number of unrecognized XML API requests. | [optional] 

## Methods

### NewGatewayMonitorInfoV3

`func NewGatewayMonitorInfoV3() *GatewayMonitorInfoV3`

NewGatewayMonitorInfoV3 instantiates a new GatewayMonitorInfoV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGatewayMonitorInfoV3WithDefaults

`func NewGatewayMonitorInfoV3WithDefaults() *GatewayMonitorInfoV3`

NewGatewayMonitorInfoV3WithDefaults instantiates a new GatewayMonitorInfoV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveConnectionCount

`func (o *GatewayMonitorInfoV3) GetActiveConnectionCount() int32`

GetActiveConnectionCount returns the ActiveConnectionCount field if non-nil, zero value otherwise.

### GetActiveConnectionCountOk

`func (o *GatewayMonitorInfoV3) GetActiveConnectionCountOk() (*int32, bool)`

GetActiveConnectionCountOk returns a tuple with the ActiveConnectionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveConnectionCount

`func (o *GatewayMonitorInfoV3) SetActiveConnectionCount(v int32)`

SetActiveConnectionCount sets ActiveConnectionCount field to given value.

### HasActiveConnectionCount

`func (o *GatewayMonitorInfoV3) HasActiveConnectionCount() bool`

HasActiveConnectionCount returns a boolean if a field has been set.

### GetBlastConnectionCount

`func (o *GatewayMonitorInfoV3) GetBlastConnectionCount() int32`

GetBlastConnectionCount returns the BlastConnectionCount field if non-nil, zero value otherwise.

### GetBlastConnectionCountOk

`func (o *GatewayMonitorInfoV3) GetBlastConnectionCountOk() (*int32, bool)`

GetBlastConnectionCountOk returns a tuple with the BlastConnectionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlastConnectionCount

`func (o *GatewayMonitorInfoV3) SetBlastConnectionCount(v int32)`

SetBlastConnectionCount sets BlastConnectionCount field to given value.

### HasBlastConnectionCount

`func (o *GatewayMonitorInfoV3) HasBlastConnectionCount() bool`

HasBlastConnectionCount returns a boolean if a field has been set.

### GetDetails

`func (o *GatewayMonitorInfoV3) GetDetails() GatewayMonitorDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *GatewayMonitorInfoV3) GetDetailsOk() (*GatewayMonitorDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *GatewayMonitorInfoV3) SetDetails(v GatewayMonitorDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *GatewayMonitorInfoV3) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetId

`func (o *GatewayMonitorInfoV3) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GatewayMonitorInfoV3) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GatewayMonitorInfoV3) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GatewayMonitorInfoV3) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLastUpdatedTimestamp

`func (o *GatewayMonitorInfoV3) GetLastUpdatedTimestamp() int64`

GetLastUpdatedTimestamp returns the LastUpdatedTimestamp field if non-nil, zero value otherwise.

### GetLastUpdatedTimestampOk

`func (o *GatewayMonitorInfoV3) GetLastUpdatedTimestampOk() (*int64, bool)`

GetLastUpdatedTimestampOk returns a tuple with the LastUpdatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedTimestamp

`func (o *GatewayMonitorInfoV3) SetLastUpdatedTimestamp(v int64)`

SetLastUpdatedTimestamp sets LastUpdatedTimestamp field to given value.

### HasLastUpdatedTimestamp

`func (o *GatewayMonitorInfoV3) HasLastUpdatedTimestamp() bool`

HasLastUpdatedTimestamp returns a boolean if a field has been set.

### GetName

`func (o *GatewayMonitorInfoV3) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GatewayMonitorInfoV3) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GatewayMonitorInfoV3) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GatewayMonitorInfoV3) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPcoipConnectionCount

`func (o *GatewayMonitorInfoV3) GetPcoipConnectionCount() int32`

GetPcoipConnectionCount returns the PcoipConnectionCount field if non-nil, zero value otherwise.

### GetPcoipConnectionCountOk

`func (o *GatewayMonitorInfoV3) GetPcoipConnectionCountOk() (*int32, bool)`

GetPcoipConnectionCountOk returns a tuple with the PcoipConnectionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPcoipConnectionCount

`func (o *GatewayMonitorInfoV3) SetPcoipConnectionCount(v int32)`

SetPcoipConnectionCount sets PcoipConnectionCount field to given value.

### HasPcoipConnectionCount

`func (o *GatewayMonitorInfoV3) HasPcoipConnectionCount() bool`

HasPcoipConnectionCount returns a boolean if a field has been set.

### GetStatus

`func (o *GatewayMonitorInfoV3) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GatewayMonitorInfoV3) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GatewayMonitorInfoV3) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GatewayMonitorInfoV3) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUnrecognizedPcoipRequestsCount

`func (o *GatewayMonitorInfoV3) GetUnrecognizedPcoipRequestsCount() int32`

GetUnrecognizedPcoipRequestsCount returns the UnrecognizedPcoipRequestsCount field if non-nil, zero value otherwise.

### GetUnrecognizedPcoipRequestsCountOk

`func (o *GatewayMonitorInfoV3) GetUnrecognizedPcoipRequestsCountOk() (*int32, bool)`

GetUnrecognizedPcoipRequestsCountOk returns a tuple with the UnrecognizedPcoipRequestsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrecognizedPcoipRequestsCount

`func (o *GatewayMonitorInfoV3) SetUnrecognizedPcoipRequestsCount(v int32)`

SetUnrecognizedPcoipRequestsCount sets UnrecognizedPcoipRequestsCount field to given value.

### HasUnrecognizedPcoipRequestsCount

`func (o *GatewayMonitorInfoV3) HasUnrecognizedPcoipRequestsCount() bool`

HasUnrecognizedPcoipRequestsCount returns a boolean if a field has been set.

### GetUnrecognizedTunnelRequestsCount

`func (o *GatewayMonitorInfoV3) GetUnrecognizedTunnelRequestsCount() int32`

GetUnrecognizedTunnelRequestsCount returns the UnrecognizedTunnelRequestsCount field if non-nil, zero value otherwise.

### GetUnrecognizedTunnelRequestsCountOk

`func (o *GatewayMonitorInfoV3) GetUnrecognizedTunnelRequestsCountOk() (*int32, bool)`

GetUnrecognizedTunnelRequestsCountOk returns a tuple with the UnrecognizedTunnelRequestsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrecognizedTunnelRequestsCount

`func (o *GatewayMonitorInfoV3) SetUnrecognizedTunnelRequestsCount(v int32)`

SetUnrecognizedTunnelRequestsCount sets UnrecognizedTunnelRequestsCount field to given value.

### HasUnrecognizedTunnelRequestsCount

`func (o *GatewayMonitorInfoV3) HasUnrecognizedTunnelRequestsCount() bool`

HasUnrecognizedTunnelRequestsCount returns a boolean if a field has been set.

### GetUnrecognizedXmlapiRequestsCount

`func (o *GatewayMonitorInfoV3) GetUnrecognizedXmlapiRequestsCount() int32`

GetUnrecognizedXmlapiRequestsCount returns the UnrecognizedXmlapiRequestsCount field if non-nil, zero value otherwise.

### GetUnrecognizedXmlapiRequestsCountOk

`func (o *GatewayMonitorInfoV3) GetUnrecognizedXmlapiRequestsCountOk() (*int32, bool)`

GetUnrecognizedXmlapiRequestsCountOk returns a tuple with the UnrecognizedXmlapiRequestsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrecognizedXmlapiRequestsCount

`func (o *GatewayMonitorInfoV3) SetUnrecognizedXmlapiRequestsCount(v int32)`

SetUnrecognizedXmlapiRequestsCount sets UnrecognizedXmlapiRequestsCount field to given value.

### HasUnrecognizedXmlapiRequestsCount

`func (o *GatewayMonitorInfoV3) HasUnrecognizedXmlapiRequestsCount() bool`

HasUnrecognizedXmlapiRequestsCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


