# ConnectionServerLdapBackupInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BackupInProgress** | Pointer to **bool** |  | [optional] 
**FrequencyTime** | Pointer to **string** | Ldap Backup Frequency. * HOUR_1: Backup every 1 hour. * HOUR_6: Backup every 6 hours. * HOUR_12: Backup every 12 hours. * DAY_1: Backup every 1 day. * DAY_2: Backup every 2 days. * WEEK_1: Backup every 1 week. * WEEK_2: Backup every 2 weeks. * HOUR_0: Never Backup. | [optional] 
**LastLdapBackupStatus** | Pointer to **string** | Last Ldap Backup Status. * OK: Indicates that the status is OK. * DISK_FULL: Indicates that Disk is full for LDAP to be backed up. * UNABLE_TO_CREATE_DIR: Indicates that unable to create directory. * ERROR_UNKNOWN: Indicates that the error is unknown. | [optional] 
**LastLdapBackupTime** | Pointer to **int64** | Last Ldap Backup Time. | [optional] 
**LdapBackupFolder** | Pointer to **string** | Location of the backup folder. | [optional] 
**MaxNumber** | Pointer to **int32** | Maximum number of backups. | [optional] 
**TimeOffset** | Pointer to **int32** | Ldap backup time offset in minutes | [optional] 

## Methods

### NewConnectionServerLdapBackupInfo

`func NewConnectionServerLdapBackupInfo() *ConnectionServerLdapBackupInfo`

NewConnectionServerLdapBackupInfo instantiates a new ConnectionServerLdapBackupInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerLdapBackupInfoWithDefaults

`func NewConnectionServerLdapBackupInfoWithDefaults() *ConnectionServerLdapBackupInfo`

NewConnectionServerLdapBackupInfoWithDefaults instantiates a new ConnectionServerLdapBackupInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackupInProgress

`func (o *ConnectionServerLdapBackupInfo) GetBackupInProgress() bool`

GetBackupInProgress returns the BackupInProgress field if non-nil, zero value otherwise.

### GetBackupInProgressOk

`func (o *ConnectionServerLdapBackupInfo) GetBackupInProgressOk() (*bool, bool)`

GetBackupInProgressOk returns a tuple with the BackupInProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupInProgress

`func (o *ConnectionServerLdapBackupInfo) SetBackupInProgress(v bool)`

SetBackupInProgress sets BackupInProgress field to given value.

### HasBackupInProgress

`func (o *ConnectionServerLdapBackupInfo) HasBackupInProgress() bool`

HasBackupInProgress returns a boolean if a field has been set.

### GetFrequencyTime

`func (o *ConnectionServerLdapBackupInfo) GetFrequencyTime() string`

GetFrequencyTime returns the FrequencyTime field if non-nil, zero value otherwise.

### GetFrequencyTimeOk

`func (o *ConnectionServerLdapBackupInfo) GetFrequencyTimeOk() (*string, bool)`

GetFrequencyTimeOk returns a tuple with the FrequencyTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyTime

`func (o *ConnectionServerLdapBackupInfo) SetFrequencyTime(v string)`

SetFrequencyTime sets FrequencyTime field to given value.

### HasFrequencyTime

`func (o *ConnectionServerLdapBackupInfo) HasFrequencyTime() bool`

HasFrequencyTime returns a boolean if a field has been set.

### GetLastLdapBackupStatus

`func (o *ConnectionServerLdapBackupInfo) GetLastLdapBackupStatus() string`

GetLastLdapBackupStatus returns the LastLdapBackupStatus field if non-nil, zero value otherwise.

### GetLastLdapBackupStatusOk

`func (o *ConnectionServerLdapBackupInfo) GetLastLdapBackupStatusOk() (*string, bool)`

GetLastLdapBackupStatusOk returns a tuple with the LastLdapBackupStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLdapBackupStatus

`func (o *ConnectionServerLdapBackupInfo) SetLastLdapBackupStatus(v string)`

SetLastLdapBackupStatus sets LastLdapBackupStatus field to given value.

### HasLastLdapBackupStatus

`func (o *ConnectionServerLdapBackupInfo) HasLastLdapBackupStatus() bool`

HasLastLdapBackupStatus returns a boolean if a field has been set.

### GetLastLdapBackupTime

`func (o *ConnectionServerLdapBackupInfo) GetLastLdapBackupTime() int64`

GetLastLdapBackupTime returns the LastLdapBackupTime field if non-nil, zero value otherwise.

### GetLastLdapBackupTimeOk

`func (o *ConnectionServerLdapBackupInfo) GetLastLdapBackupTimeOk() (*int64, bool)`

GetLastLdapBackupTimeOk returns a tuple with the LastLdapBackupTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLdapBackupTime

`func (o *ConnectionServerLdapBackupInfo) SetLastLdapBackupTime(v int64)`

SetLastLdapBackupTime sets LastLdapBackupTime field to given value.

### HasLastLdapBackupTime

`func (o *ConnectionServerLdapBackupInfo) HasLastLdapBackupTime() bool`

HasLastLdapBackupTime returns a boolean if a field has been set.

### GetLdapBackupFolder

`func (o *ConnectionServerLdapBackupInfo) GetLdapBackupFolder() string`

GetLdapBackupFolder returns the LdapBackupFolder field if non-nil, zero value otherwise.

### GetLdapBackupFolderOk

`func (o *ConnectionServerLdapBackupInfo) GetLdapBackupFolderOk() (*string, bool)`

GetLdapBackupFolderOk returns a tuple with the LdapBackupFolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLdapBackupFolder

`func (o *ConnectionServerLdapBackupInfo) SetLdapBackupFolder(v string)`

SetLdapBackupFolder sets LdapBackupFolder field to given value.

### HasLdapBackupFolder

`func (o *ConnectionServerLdapBackupInfo) HasLdapBackupFolder() bool`

HasLdapBackupFolder returns a boolean if a field has been set.

### GetMaxNumber

`func (o *ConnectionServerLdapBackupInfo) GetMaxNumber() int32`

GetMaxNumber returns the MaxNumber field if non-nil, zero value otherwise.

### GetMaxNumberOk

`func (o *ConnectionServerLdapBackupInfo) GetMaxNumberOk() (*int32, bool)`

GetMaxNumberOk returns a tuple with the MaxNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNumber

`func (o *ConnectionServerLdapBackupInfo) SetMaxNumber(v int32)`

SetMaxNumber sets MaxNumber field to given value.

### HasMaxNumber

`func (o *ConnectionServerLdapBackupInfo) HasMaxNumber() bool`

HasMaxNumber returns a boolean if a field has been set.

### GetTimeOffset

`func (o *ConnectionServerLdapBackupInfo) GetTimeOffset() int32`

GetTimeOffset returns the TimeOffset field if non-nil, zero value otherwise.

### GetTimeOffsetOk

`func (o *ConnectionServerLdapBackupInfo) GetTimeOffsetOk() (*int32, bool)`

GetTimeOffsetOk returns a tuple with the TimeOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeOffset

`func (o *ConnectionServerLdapBackupInfo) SetTimeOffset(v int32)`

SetTimeOffset sets TimeOffset field to given value.

### HasTimeOffset

`func (o *ConnectionServerLdapBackupInfo) HasTimeOffset() bool`

HasTimeOffset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


