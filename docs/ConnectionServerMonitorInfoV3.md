# ConnectionServerMonitorInfoV3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Certificate** | Pointer to [**CertificateMonitorInfo**](CertificateMonitorInfo.md) |  | [optional] 
**ConnectionCount** | Pointer to **int32** | Number of connections to this Connection Server. | [optional] 
**CsReplications** | Pointer to [**[]ConnectionServerMonitorCSReplication**](ConnectionServerMonitorCSReplication.md) | Connection Server replication status with respect to the Peer Connection Servers in the same cluster. | [optional] 
**DefaultCertificate** | Pointer to **bool** | Indicates whether server has the default certificate. | [optional] 
**Details** | Pointer to [**ConnectionServerMonitorDetails**](ConnectionServerMonitorDetails.md) |  | [optional] 
**Id** | Pointer to **string** | Unique ID of the Connection Server. | [optional] 
**LastUpdatedTimestamp** | Pointer to **int64** | The timestamp in milliseconds when the last update was obtained. Measured as epoch time. | [optional] 
**Name** | Pointer to **string** | Connection Server host name or IP address. | [optional] 
**Services** | Pointer to [**[]ConnectionServerMonitorServiceStatus**](ConnectionServerMonitorServiceStatus.md) | Connection Server related Windows services information. | [optional] 
**SessionProtocolData** | Pointer to [**[]ConnectionServerSessionProtocolData**](ConnectionServerSessionProtocolData.md) | PCoIP, RDP or BLAST protocol sessions details when clients connect directly to the connection server. | [optional] 
**SessionThreshold** | Pointer to **int32** | The maximum number of connections allowed for the connection server through the Horizon client. If all of the secure gateways (HTTP(S)/PCOIP/BLAST) are enabled, this field denotes the maximum number of connections allowed for the connection server.If none of the secure gateways(HTTP(S)/PCOIP/BLAST) are enabled, sessionThreshold value will not be set. | [optional] 
**Status** | Pointer to **string** | Status of the Connection Server. * OK: The Connection Server is working properly. * ERROR: Error occurred when connecting to Connection Server. * NOT_RESPONDING: The Connection Server is not responding. * UNKNOWN: Status of Connection Server is unknown. * RESTART_REQUIRED: Connection Server needs a Restart. | [optional] 
**TunnelConnectionCount** | Pointer to **int32** | Number of connections tunneled through this Connection Server. | [optional] 
**UnrecognizedPcoipRequestsCount** | Pointer to **int32** | Number of unrecognized PCoIP secure gateway requests. | [optional] 
**UnrecognizedTunnelRequestsCount** | Pointer to **int32** | Number of unrecognized tunnel requests. | [optional] 
**UnrecognizedXmlapiRequestsCount** | Pointer to **int32** | Number of unrecognized XML API requests. | [optional] 

## Methods

### NewConnectionServerMonitorInfoV3

`func NewConnectionServerMonitorInfoV3() *ConnectionServerMonitorInfoV3`

NewConnectionServerMonitorInfoV3 instantiates a new ConnectionServerMonitorInfoV3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerMonitorInfoV3WithDefaults

`func NewConnectionServerMonitorInfoV3WithDefaults() *ConnectionServerMonitorInfoV3`

NewConnectionServerMonitorInfoV3WithDefaults instantiates a new ConnectionServerMonitorInfoV3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificate

`func (o *ConnectionServerMonitorInfoV3) GetCertificate() CertificateMonitorInfo`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *ConnectionServerMonitorInfoV3) GetCertificateOk() (*CertificateMonitorInfo, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *ConnectionServerMonitorInfoV3) SetCertificate(v CertificateMonitorInfo)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *ConnectionServerMonitorInfoV3) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### GetConnectionCount

`func (o *ConnectionServerMonitorInfoV3) GetConnectionCount() int32`

GetConnectionCount returns the ConnectionCount field if non-nil, zero value otherwise.

### GetConnectionCountOk

`func (o *ConnectionServerMonitorInfoV3) GetConnectionCountOk() (*int32, bool)`

GetConnectionCountOk returns a tuple with the ConnectionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionCount

`func (o *ConnectionServerMonitorInfoV3) SetConnectionCount(v int32)`

SetConnectionCount sets ConnectionCount field to given value.

### HasConnectionCount

`func (o *ConnectionServerMonitorInfoV3) HasConnectionCount() bool`

HasConnectionCount returns a boolean if a field has been set.

### GetCsReplications

`func (o *ConnectionServerMonitorInfoV3) GetCsReplications() []ConnectionServerMonitorCSReplication`

GetCsReplications returns the CsReplications field if non-nil, zero value otherwise.

### GetCsReplicationsOk

`func (o *ConnectionServerMonitorInfoV3) GetCsReplicationsOk() (*[]ConnectionServerMonitorCSReplication, bool)`

GetCsReplicationsOk returns a tuple with the CsReplications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCsReplications

`func (o *ConnectionServerMonitorInfoV3) SetCsReplications(v []ConnectionServerMonitorCSReplication)`

SetCsReplications sets CsReplications field to given value.

### HasCsReplications

`func (o *ConnectionServerMonitorInfoV3) HasCsReplications() bool`

HasCsReplications returns a boolean if a field has been set.

### GetDefaultCertificate

`func (o *ConnectionServerMonitorInfoV3) GetDefaultCertificate() bool`

GetDefaultCertificate returns the DefaultCertificate field if non-nil, zero value otherwise.

### GetDefaultCertificateOk

`func (o *ConnectionServerMonitorInfoV3) GetDefaultCertificateOk() (*bool, bool)`

GetDefaultCertificateOk returns a tuple with the DefaultCertificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultCertificate

`func (o *ConnectionServerMonitorInfoV3) SetDefaultCertificate(v bool)`

SetDefaultCertificate sets DefaultCertificate field to given value.

### HasDefaultCertificate

`func (o *ConnectionServerMonitorInfoV3) HasDefaultCertificate() bool`

HasDefaultCertificate returns a boolean if a field has been set.

### GetDetails

`func (o *ConnectionServerMonitorInfoV3) GetDetails() ConnectionServerMonitorDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ConnectionServerMonitorInfoV3) GetDetailsOk() (*ConnectionServerMonitorDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ConnectionServerMonitorInfoV3) SetDetails(v ConnectionServerMonitorDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ConnectionServerMonitorInfoV3) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetId

`func (o *ConnectionServerMonitorInfoV3) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConnectionServerMonitorInfoV3) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConnectionServerMonitorInfoV3) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ConnectionServerMonitorInfoV3) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLastUpdatedTimestamp

`func (o *ConnectionServerMonitorInfoV3) GetLastUpdatedTimestamp() int64`

GetLastUpdatedTimestamp returns the LastUpdatedTimestamp field if non-nil, zero value otherwise.

### GetLastUpdatedTimestampOk

`func (o *ConnectionServerMonitorInfoV3) GetLastUpdatedTimestampOk() (*int64, bool)`

GetLastUpdatedTimestampOk returns a tuple with the LastUpdatedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedTimestamp

`func (o *ConnectionServerMonitorInfoV3) SetLastUpdatedTimestamp(v int64)`

SetLastUpdatedTimestamp sets LastUpdatedTimestamp field to given value.

### HasLastUpdatedTimestamp

`func (o *ConnectionServerMonitorInfoV3) HasLastUpdatedTimestamp() bool`

HasLastUpdatedTimestamp returns a boolean if a field has been set.

### GetName

`func (o *ConnectionServerMonitorInfoV3) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConnectionServerMonitorInfoV3) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConnectionServerMonitorInfoV3) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ConnectionServerMonitorInfoV3) HasName() bool`

HasName returns a boolean if a field has been set.

### GetServices

`func (o *ConnectionServerMonitorInfoV3) GetServices() []ConnectionServerMonitorServiceStatus`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *ConnectionServerMonitorInfoV3) GetServicesOk() (*[]ConnectionServerMonitorServiceStatus, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *ConnectionServerMonitorInfoV3) SetServices(v []ConnectionServerMonitorServiceStatus)`

SetServices sets Services field to given value.

### HasServices

`func (o *ConnectionServerMonitorInfoV3) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetSessionProtocolData

`func (o *ConnectionServerMonitorInfoV3) GetSessionProtocolData() []ConnectionServerSessionProtocolData`

GetSessionProtocolData returns the SessionProtocolData field if non-nil, zero value otherwise.

### GetSessionProtocolDataOk

`func (o *ConnectionServerMonitorInfoV3) GetSessionProtocolDataOk() (*[]ConnectionServerSessionProtocolData, bool)`

GetSessionProtocolDataOk returns a tuple with the SessionProtocolData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionProtocolData

`func (o *ConnectionServerMonitorInfoV3) SetSessionProtocolData(v []ConnectionServerSessionProtocolData)`

SetSessionProtocolData sets SessionProtocolData field to given value.

### HasSessionProtocolData

`func (o *ConnectionServerMonitorInfoV3) HasSessionProtocolData() bool`

HasSessionProtocolData returns a boolean if a field has been set.

### GetSessionThreshold

`func (o *ConnectionServerMonitorInfoV3) GetSessionThreshold() int32`

GetSessionThreshold returns the SessionThreshold field if non-nil, zero value otherwise.

### GetSessionThresholdOk

`func (o *ConnectionServerMonitorInfoV3) GetSessionThresholdOk() (*int32, bool)`

GetSessionThresholdOk returns a tuple with the SessionThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionThreshold

`func (o *ConnectionServerMonitorInfoV3) SetSessionThreshold(v int32)`

SetSessionThreshold sets SessionThreshold field to given value.

### HasSessionThreshold

`func (o *ConnectionServerMonitorInfoV3) HasSessionThreshold() bool`

HasSessionThreshold returns a boolean if a field has been set.

### GetStatus

`func (o *ConnectionServerMonitorInfoV3) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ConnectionServerMonitorInfoV3) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ConnectionServerMonitorInfoV3) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ConnectionServerMonitorInfoV3) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTunnelConnectionCount

`func (o *ConnectionServerMonitorInfoV3) GetTunnelConnectionCount() int32`

GetTunnelConnectionCount returns the TunnelConnectionCount field if non-nil, zero value otherwise.

### GetTunnelConnectionCountOk

`func (o *ConnectionServerMonitorInfoV3) GetTunnelConnectionCountOk() (*int32, bool)`

GetTunnelConnectionCountOk returns a tuple with the TunnelConnectionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTunnelConnectionCount

`func (o *ConnectionServerMonitorInfoV3) SetTunnelConnectionCount(v int32)`

SetTunnelConnectionCount sets TunnelConnectionCount field to given value.

### HasTunnelConnectionCount

`func (o *ConnectionServerMonitorInfoV3) HasTunnelConnectionCount() bool`

HasTunnelConnectionCount returns a boolean if a field has been set.

### GetUnrecognizedPcoipRequestsCount

`func (o *ConnectionServerMonitorInfoV3) GetUnrecognizedPcoipRequestsCount() int32`

GetUnrecognizedPcoipRequestsCount returns the UnrecognizedPcoipRequestsCount field if non-nil, zero value otherwise.

### GetUnrecognizedPcoipRequestsCountOk

`func (o *ConnectionServerMonitorInfoV3) GetUnrecognizedPcoipRequestsCountOk() (*int32, bool)`

GetUnrecognizedPcoipRequestsCountOk returns a tuple with the UnrecognizedPcoipRequestsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrecognizedPcoipRequestsCount

`func (o *ConnectionServerMonitorInfoV3) SetUnrecognizedPcoipRequestsCount(v int32)`

SetUnrecognizedPcoipRequestsCount sets UnrecognizedPcoipRequestsCount field to given value.

### HasUnrecognizedPcoipRequestsCount

`func (o *ConnectionServerMonitorInfoV3) HasUnrecognizedPcoipRequestsCount() bool`

HasUnrecognizedPcoipRequestsCount returns a boolean if a field has been set.

### GetUnrecognizedTunnelRequestsCount

`func (o *ConnectionServerMonitorInfoV3) GetUnrecognizedTunnelRequestsCount() int32`

GetUnrecognizedTunnelRequestsCount returns the UnrecognizedTunnelRequestsCount field if non-nil, zero value otherwise.

### GetUnrecognizedTunnelRequestsCountOk

`func (o *ConnectionServerMonitorInfoV3) GetUnrecognizedTunnelRequestsCountOk() (*int32, bool)`

GetUnrecognizedTunnelRequestsCountOk returns a tuple with the UnrecognizedTunnelRequestsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrecognizedTunnelRequestsCount

`func (o *ConnectionServerMonitorInfoV3) SetUnrecognizedTunnelRequestsCount(v int32)`

SetUnrecognizedTunnelRequestsCount sets UnrecognizedTunnelRequestsCount field to given value.

### HasUnrecognizedTunnelRequestsCount

`func (o *ConnectionServerMonitorInfoV3) HasUnrecognizedTunnelRequestsCount() bool`

HasUnrecognizedTunnelRequestsCount returns a boolean if a field has been set.

### GetUnrecognizedXmlapiRequestsCount

`func (o *ConnectionServerMonitorInfoV3) GetUnrecognizedXmlapiRequestsCount() int32`

GetUnrecognizedXmlapiRequestsCount returns the UnrecognizedXmlapiRequestsCount field if non-nil, zero value otherwise.

### GetUnrecognizedXmlapiRequestsCountOk

`func (o *ConnectionServerMonitorInfoV3) GetUnrecognizedXmlapiRequestsCountOk() (*int32, bool)`

GetUnrecognizedXmlapiRequestsCountOk returns a tuple with the UnrecognizedXmlapiRequestsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnrecognizedXmlapiRequestsCount

`func (o *ConnectionServerMonitorInfoV3) SetUnrecognizedXmlapiRequestsCount(v int32)`

SetUnrecognizedXmlapiRequestsCount sets UnrecognizedXmlapiRequestsCount field to given value.

### HasUnrecognizedXmlapiRequestsCount

`func (o *ConnectionServerMonitorInfoV3) HasUnrecognizedXmlapiRequestsCount() bool`

HasUnrecognizedXmlapiRequestsCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


