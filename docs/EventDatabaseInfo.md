# EventDatabaseInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminEventsCount** | Pointer to **int32** | The number of events administrator can see in the admin console. | [optional] 
**ClassifyEventsAsNewForDays** | Pointer to **int32** | Events will be marked as new for a time based on the value. | [optional] 
**DatabaseName** | Pointer to **string** | Name of the database on the database server to use for storing events. Note that this database must exist on the server or the values cannot be saved. | [optional] 
**EventDatabaseConfigured** | Pointer to **bool** | Indicates if the event database has been configured or not. | [optional] 
**Port** | Pointer to **int32** | Port number on the database server to which Horizon will send events. | [optional] 
**QueryTimeoutSeconds** | Pointer to **int32** | Query execution timeout in seconds. | [optional] 
**ServerName** | Pointer to **string** | The server that hosts the database which will be used to store events. | [optional] 
**ShowEventsForTime** | Pointer to **string** | Events will be shown in the Horizon Admin console for a time based on this value. * ONE_WEEK: One week. * TWO_WEEKS: Two weeks. * THREE_WEEKS: Three weeks. * ONE_MONTH: One month. * TWO_MONTHS: Two months. * THREE_MONTHS: Three months. * SIX_MONTHS: Six months. | [optional] 
**TablePrefix** | Pointer to **string** | If present, all tables for this instance will start with this prefix. This allows multiple brokers to use the same events database without trampling on other broker data. | [optional] 
**TimingProfilerDataLongevityDays** | Pointer to **int32** | Timing Profiler data will be kept in database for a time based on the value. Timing Profiler Data will not be stored in Event DB. | [optional] 
**Type** | Pointer to **string** | The type of database to use for the event database. * ORACLE: An Oracle database. * SQL_SERVER: A SQL server database. * POSTGRESQL: A PostgreSQL database. | [optional] 
**Username** | Pointer to **string** | Username to use for the connection to the event database. | [optional] 

## Methods

### NewEventDatabaseInfo

`func NewEventDatabaseInfo() *EventDatabaseInfo`

NewEventDatabaseInfo instantiates a new EventDatabaseInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventDatabaseInfoWithDefaults

`func NewEventDatabaseInfoWithDefaults() *EventDatabaseInfo`

NewEventDatabaseInfoWithDefaults instantiates a new EventDatabaseInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminEventsCount

`func (o *EventDatabaseInfo) GetAdminEventsCount() int32`

GetAdminEventsCount returns the AdminEventsCount field if non-nil, zero value otherwise.

### GetAdminEventsCountOk

`func (o *EventDatabaseInfo) GetAdminEventsCountOk() (*int32, bool)`

GetAdminEventsCountOk returns a tuple with the AdminEventsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminEventsCount

`func (o *EventDatabaseInfo) SetAdminEventsCount(v int32)`

SetAdminEventsCount sets AdminEventsCount field to given value.

### HasAdminEventsCount

`func (o *EventDatabaseInfo) HasAdminEventsCount() bool`

HasAdminEventsCount returns a boolean if a field has been set.

### GetClassifyEventsAsNewForDays

`func (o *EventDatabaseInfo) GetClassifyEventsAsNewForDays() int32`

GetClassifyEventsAsNewForDays returns the ClassifyEventsAsNewForDays field if non-nil, zero value otherwise.

### GetClassifyEventsAsNewForDaysOk

`func (o *EventDatabaseInfo) GetClassifyEventsAsNewForDaysOk() (*int32, bool)`

GetClassifyEventsAsNewForDaysOk returns a tuple with the ClassifyEventsAsNewForDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassifyEventsAsNewForDays

`func (o *EventDatabaseInfo) SetClassifyEventsAsNewForDays(v int32)`

SetClassifyEventsAsNewForDays sets ClassifyEventsAsNewForDays field to given value.

### HasClassifyEventsAsNewForDays

`func (o *EventDatabaseInfo) HasClassifyEventsAsNewForDays() bool`

HasClassifyEventsAsNewForDays returns a boolean if a field has been set.

### GetDatabaseName

`func (o *EventDatabaseInfo) GetDatabaseName() string`

GetDatabaseName returns the DatabaseName field if non-nil, zero value otherwise.

### GetDatabaseNameOk

`func (o *EventDatabaseInfo) GetDatabaseNameOk() (*string, bool)`

GetDatabaseNameOk returns a tuple with the DatabaseName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseName

`func (o *EventDatabaseInfo) SetDatabaseName(v string)`

SetDatabaseName sets DatabaseName field to given value.

### HasDatabaseName

`func (o *EventDatabaseInfo) HasDatabaseName() bool`

HasDatabaseName returns a boolean if a field has been set.

### GetEventDatabaseConfigured

`func (o *EventDatabaseInfo) GetEventDatabaseConfigured() bool`

GetEventDatabaseConfigured returns the EventDatabaseConfigured field if non-nil, zero value otherwise.

### GetEventDatabaseConfiguredOk

`func (o *EventDatabaseInfo) GetEventDatabaseConfiguredOk() (*bool, bool)`

GetEventDatabaseConfiguredOk returns a tuple with the EventDatabaseConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventDatabaseConfigured

`func (o *EventDatabaseInfo) SetEventDatabaseConfigured(v bool)`

SetEventDatabaseConfigured sets EventDatabaseConfigured field to given value.

### HasEventDatabaseConfigured

`func (o *EventDatabaseInfo) HasEventDatabaseConfigured() bool`

HasEventDatabaseConfigured returns a boolean if a field has been set.

### GetPort

`func (o *EventDatabaseInfo) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *EventDatabaseInfo) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *EventDatabaseInfo) SetPort(v int32)`

SetPort sets Port field to given value.

### HasPort

`func (o *EventDatabaseInfo) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetQueryTimeoutSeconds

`func (o *EventDatabaseInfo) GetQueryTimeoutSeconds() int32`

GetQueryTimeoutSeconds returns the QueryTimeoutSeconds field if non-nil, zero value otherwise.

### GetQueryTimeoutSecondsOk

`func (o *EventDatabaseInfo) GetQueryTimeoutSecondsOk() (*int32, bool)`

GetQueryTimeoutSecondsOk returns a tuple with the QueryTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueryTimeoutSeconds

`func (o *EventDatabaseInfo) SetQueryTimeoutSeconds(v int32)`

SetQueryTimeoutSeconds sets QueryTimeoutSeconds field to given value.

### HasQueryTimeoutSeconds

`func (o *EventDatabaseInfo) HasQueryTimeoutSeconds() bool`

HasQueryTimeoutSeconds returns a boolean if a field has been set.

### GetServerName

`func (o *EventDatabaseInfo) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *EventDatabaseInfo) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *EventDatabaseInfo) SetServerName(v string)`

SetServerName sets ServerName field to given value.

### HasServerName

`func (o *EventDatabaseInfo) HasServerName() bool`

HasServerName returns a boolean if a field has been set.

### GetShowEventsForTime

`func (o *EventDatabaseInfo) GetShowEventsForTime() string`

GetShowEventsForTime returns the ShowEventsForTime field if non-nil, zero value otherwise.

### GetShowEventsForTimeOk

`func (o *EventDatabaseInfo) GetShowEventsForTimeOk() (*string, bool)`

GetShowEventsForTimeOk returns a tuple with the ShowEventsForTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowEventsForTime

`func (o *EventDatabaseInfo) SetShowEventsForTime(v string)`

SetShowEventsForTime sets ShowEventsForTime field to given value.

### HasShowEventsForTime

`func (o *EventDatabaseInfo) HasShowEventsForTime() bool`

HasShowEventsForTime returns a boolean if a field has been set.

### GetTablePrefix

`func (o *EventDatabaseInfo) GetTablePrefix() string`

GetTablePrefix returns the TablePrefix field if non-nil, zero value otherwise.

### GetTablePrefixOk

`func (o *EventDatabaseInfo) GetTablePrefixOk() (*string, bool)`

GetTablePrefixOk returns a tuple with the TablePrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTablePrefix

`func (o *EventDatabaseInfo) SetTablePrefix(v string)`

SetTablePrefix sets TablePrefix field to given value.

### HasTablePrefix

`func (o *EventDatabaseInfo) HasTablePrefix() bool`

HasTablePrefix returns a boolean if a field has been set.

### GetTimingProfilerDataLongevityDays

`func (o *EventDatabaseInfo) GetTimingProfilerDataLongevityDays() int32`

GetTimingProfilerDataLongevityDays returns the TimingProfilerDataLongevityDays field if non-nil, zero value otherwise.

### GetTimingProfilerDataLongevityDaysOk

`func (o *EventDatabaseInfo) GetTimingProfilerDataLongevityDaysOk() (*int32, bool)`

GetTimingProfilerDataLongevityDaysOk returns a tuple with the TimingProfilerDataLongevityDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimingProfilerDataLongevityDays

`func (o *EventDatabaseInfo) SetTimingProfilerDataLongevityDays(v int32)`

SetTimingProfilerDataLongevityDays sets TimingProfilerDataLongevityDays field to given value.

### HasTimingProfilerDataLongevityDays

`func (o *EventDatabaseInfo) HasTimingProfilerDataLongevityDays() bool`

HasTimingProfilerDataLongevityDays returns a boolean if a field has been set.

### GetType

`func (o *EventDatabaseInfo) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EventDatabaseInfo) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EventDatabaseInfo) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *EventDatabaseInfo) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUsername

`func (o *EventDatabaseInfo) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *EventDatabaseInfo) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *EventDatabaseInfo) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *EventDatabaseInfo) HasUsername() bool`

HasUsername returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


