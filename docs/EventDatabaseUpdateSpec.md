# EventDatabaseUpdateSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdminEventsCount** | Pointer to **int32** | The number of events administrator can see in the admin console. It has a default value of 2000. | [optional] 
**ClassifyEventsAsNewForDays** | Pointer to **int32** | Events will be marked as new for a time based on the value. Must be between 1 and 3 days. | [optional] 
**DatabaseName** | **string** | Name of the database on the database server to use for storing events. Note that this database must exist on the server or the values cannot be saved. | 
**Password** | **[]string** | Password to use for the event database connection. | 
**Port** | **int32** | Port number on the database server to which Horizon will send events. | 
**QueryTimeoutSeconds** | Pointer to **int32** | Query execution timeout in seconds. It has a default value of 120 seconds. | [optional] 
**ServerName** | **string** | The server that hosts the database which will be used to store events. | 
**ShowEventsForTime** | Pointer to **string** | Events will be shown in the Horizon Admin console for a time based on this value. It has a default value of 3 months. * ONE_WEEK: One week. * TWO_WEEKS: Two weeks. * THREE_WEEKS: Three weeks. * ONE_MONTH: One month. * TWO_MONTHS: Two months. * THREE_MONTHS: Three months. * SIX_MONTHS: Six months. | [optional] 
**TablePrefix** | Pointer to **string** | If present, all tables for this instance will start with this prefix. This allows multiple brokers to use the same events database without trampling on other broker data. This property must start with a letter, may only contain letters, numbers, and the characters @, $, #, and _, and may not be longer than 6 characters. | [optional] 
**TimingProfilerDataLongevityDays** | Pointer to **int32** | Timing Profiler data will be kept in database for a time based on the value. Must be between 1 and 7 days. Timing Profiler Data will not be stored in Event DB. It has a default value of 7. | [optional] 
**Type** | **string** | The type of database to use for the event database. * ORACLE: An Oracle database. * SQL_SERVER: A SQL server database. * POSTGRESQL: A PostgreSQL database. | 
**Username** | **string** | Username to use for the connection to the event database. | 

## Methods

### NewEventDatabaseUpdateSpec

`func NewEventDatabaseUpdateSpec(databaseName string, password []string, port int32, serverName string, type_ string, username string, ) *EventDatabaseUpdateSpec`

NewEventDatabaseUpdateSpec instantiates a new EventDatabaseUpdateSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventDatabaseUpdateSpecWithDefaults

`func NewEventDatabaseUpdateSpecWithDefaults() *EventDatabaseUpdateSpec`

NewEventDatabaseUpdateSpecWithDefaults instantiates a new EventDatabaseUpdateSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdminEventsCount

`func (o *EventDatabaseUpdateSpec) GetAdminEventsCount() int32`

GetAdminEventsCount returns the AdminEventsCount field if non-nil, zero value otherwise.

### GetAdminEventsCountOk

`func (o *EventDatabaseUpdateSpec) GetAdminEventsCountOk() (*int32, bool)`

GetAdminEventsCountOk returns a tuple with the AdminEventsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminEventsCount

`func (o *EventDatabaseUpdateSpec) SetAdminEventsCount(v int32)`

SetAdminEventsCount sets AdminEventsCount field to given value.

### HasAdminEventsCount

`func (o *EventDatabaseUpdateSpec) HasAdminEventsCount() bool`

HasAdminEventsCount returns a boolean if a field has been set.

### GetClassifyEventsAsNewForDays

`func (o *EventDatabaseUpdateSpec) GetClassifyEventsAsNewForDays() int32`

GetClassifyEventsAsNewForDays returns the ClassifyEventsAsNewForDays field if non-nil, zero value otherwise.

### GetClassifyEventsAsNewForDaysOk

`func (o *EventDatabaseUpdateSpec) GetClassifyEventsAsNewForDaysOk() (*int32, bool)`

GetClassifyEventsAsNewForDaysOk returns a tuple with the ClassifyEventsAsNewForDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassifyEventsAsNewForDays

`func (o *EventDatabaseUpdateSpec) SetClassifyEventsAsNewForDays(v int32)`

SetClassifyEventsAsNewForDays sets ClassifyEventsAsNewForDays field to given value.

### HasClassifyEventsAsNewForDays

`func (o *EventDatabaseUpdateSpec) HasClassifyEventsAsNewForDays() bool`

HasClassifyEventsAsNewForDays returns a boolean if a field has been set.

### GetDatabaseName

`func (o *EventDatabaseUpdateSpec) GetDatabaseName() string`

GetDatabaseName returns the DatabaseName field if non-nil, zero value otherwise.

### GetDatabaseNameOk

`func (o *EventDatabaseUpdateSpec) GetDatabaseNameOk() (*string, bool)`

GetDatabaseNameOk returns a tuple with the DatabaseName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseName

`func (o *EventDatabaseUpdateSpec) SetDatabaseName(v string)`

SetDatabaseName sets DatabaseName field to given value.


### GetPassword

`func (o *EventDatabaseUpdateSpec) GetPassword() []string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *EventDatabaseUpdateSpec) GetPasswordOk() (*[]string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *EventDatabaseUpdateSpec) SetPassword(v []string)`

SetPassword sets Password field to given value.


### GetPort

`func (o *EventDatabaseUpdateSpec) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *EventDatabaseUpdateSpec) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *EventDatabaseUpdateSpec) SetPort(v int32)`

SetPort sets Port field to given value.


### GetQueryTimeoutSeconds

`func (o *EventDatabaseUpdateSpec) GetQueryTimeoutSeconds() int32`

GetQueryTimeoutSeconds returns the QueryTimeoutSeconds field if non-nil, zero value otherwise.

### GetQueryTimeoutSecondsOk

`func (o *EventDatabaseUpdateSpec) GetQueryTimeoutSecondsOk() (*int32, bool)`

GetQueryTimeoutSecondsOk returns a tuple with the QueryTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueryTimeoutSeconds

`func (o *EventDatabaseUpdateSpec) SetQueryTimeoutSeconds(v int32)`

SetQueryTimeoutSeconds sets QueryTimeoutSeconds field to given value.

### HasQueryTimeoutSeconds

`func (o *EventDatabaseUpdateSpec) HasQueryTimeoutSeconds() bool`

HasQueryTimeoutSeconds returns a boolean if a field has been set.

### GetServerName

`func (o *EventDatabaseUpdateSpec) GetServerName() string`

GetServerName returns the ServerName field if non-nil, zero value otherwise.

### GetServerNameOk

`func (o *EventDatabaseUpdateSpec) GetServerNameOk() (*string, bool)`

GetServerNameOk returns a tuple with the ServerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerName

`func (o *EventDatabaseUpdateSpec) SetServerName(v string)`

SetServerName sets ServerName field to given value.


### GetShowEventsForTime

`func (o *EventDatabaseUpdateSpec) GetShowEventsForTime() string`

GetShowEventsForTime returns the ShowEventsForTime field if non-nil, zero value otherwise.

### GetShowEventsForTimeOk

`func (o *EventDatabaseUpdateSpec) GetShowEventsForTimeOk() (*string, bool)`

GetShowEventsForTimeOk returns a tuple with the ShowEventsForTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowEventsForTime

`func (o *EventDatabaseUpdateSpec) SetShowEventsForTime(v string)`

SetShowEventsForTime sets ShowEventsForTime field to given value.

### HasShowEventsForTime

`func (o *EventDatabaseUpdateSpec) HasShowEventsForTime() bool`

HasShowEventsForTime returns a boolean if a field has been set.

### GetTablePrefix

`func (o *EventDatabaseUpdateSpec) GetTablePrefix() string`

GetTablePrefix returns the TablePrefix field if non-nil, zero value otherwise.

### GetTablePrefixOk

`func (o *EventDatabaseUpdateSpec) GetTablePrefixOk() (*string, bool)`

GetTablePrefixOk returns a tuple with the TablePrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTablePrefix

`func (o *EventDatabaseUpdateSpec) SetTablePrefix(v string)`

SetTablePrefix sets TablePrefix field to given value.

### HasTablePrefix

`func (o *EventDatabaseUpdateSpec) HasTablePrefix() bool`

HasTablePrefix returns a boolean if a field has been set.

### GetTimingProfilerDataLongevityDays

`func (o *EventDatabaseUpdateSpec) GetTimingProfilerDataLongevityDays() int32`

GetTimingProfilerDataLongevityDays returns the TimingProfilerDataLongevityDays field if non-nil, zero value otherwise.

### GetTimingProfilerDataLongevityDaysOk

`func (o *EventDatabaseUpdateSpec) GetTimingProfilerDataLongevityDaysOk() (*int32, bool)`

GetTimingProfilerDataLongevityDaysOk returns a tuple with the TimingProfilerDataLongevityDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimingProfilerDataLongevityDays

`func (o *EventDatabaseUpdateSpec) SetTimingProfilerDataLongevityDays(v int32)`

SetTimingProfilerDataLongevityDays sets TimingProfilerDataLongevityDays field to given value.

### HasTimingProfilerDataLongevityDays

`func (o *EventDatabaseUpdateSpec) HasTimingProfilerDataLongevityDays() bool`

HasTimingProfilerDataLongevityDays returns a boolean if a field has been set.

### GetType

`func (o *EventDatabaseUpdateSpec) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EventDatabaseUpdateSpec) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EventDatabaseUpdateSpec) SetType(v string)`

SetType sets Type field to given value.


### GetUsername

`func (o *EventDatabaseUpdateSpec) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *EventDatabaseUpdateSpec) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *EventDatabaseUpdateSpec) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


