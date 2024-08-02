# ConnectionServerLdapBackupSpec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FrequencyTime** | **string** | Ldap Backup Frequency. * HOUR_1: Backup every 1 hour. * HOUR_6: Backup every 6 hours. * HOUR_12: Backup every 12 hours. * DAY_1: Backup every 1 day. * DAY_2: Backup every 2 days. * WEEK_1: Backup every 1 week. * WEEK_2: Backup every 2 weeks. * HOUR_0: Never Backup. | 
**LdapBackupFolder** | **string** | Location of the backup folder. | 
**MaxNumber** | **int32** | Maximum number of backups. | 
**TimeOffset** | **int32** | Ldap backup time offset in minutes | 

## Methods

### NewConnectionServerLdapBackupSpec

`func NewConnectionServerLdapBackupSpec(frequencyTime string, ldapBackupFolder string, maxNumber int32, timeOffset int32, ) *ConnectionServerLdapBackupSpec`

NewConnectionServerLdapBackupSpec instantiates a new ConnectionServerLdapBackupSpec object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerLdapBackupSpecWithDefaults

`func NewConnectionServerLdapBackupSpecWithDefaults() *ConnectionServerLdapBackupSpec`

NewConnectionServerLdapBackupSpecWithDefaults instantiates a new ConnectionServerLdapBackupSpec object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrequencyTime

`func (o *ConnectionServerLdapBackupSpec) GetFrequencyTime() string`

GetFrequencyTime returns the FrequencyTime field if non-nil, zero value otherwise.

### GetFrequencyTimeOk

`func (o *ConnectionServerLdapBackupSpec) GetFrequencyTimeOk() (*string, bool)`

GetFrequencyTimeOk returns a tuple with the FrequencyTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyTime

`func (o *ConnectionServerLdapBackupSpec) SetFrequencyTime(v string)`

SetFrequencyTime sets FrequencyTime field to given value.


### GetLdapBackupFolder

`func (o *ConnectionServerLdapBackupSpec) GetLdapBackupFolder() string`

GetLdapBackupFolder returns the LdapBackupFolder field if non-nil, zero value otherwise.

### GetLdapBackupFolderOk

`func (o *ConnectionServerLdapBackupSpec) GetLdapBackupFolderOk() (*string, bool)`

GetLdapBackupFolderOk returns a tuple with the LdapBackupFolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLdapBackupFolder

`func (o *ConnectionServerLdapBackupSpec) SetLdapBackupFolder(v string)`

SetLdapBackupFolder sets LdapBackupFolder field to given value.


### GetMaxNumber

`func (o *ConnectionServerLdapBackupSpec) GetMaxNumber() int32`

GetMaxNumber returns the MaxNumber field if non-nil, zero value otherwise.

### GetMaxNumberOk

`func (o *ConnectionServerLdapBackupSpec) GetMaxNumberOk() (*int32, bool)`

GetMaxNumberOk returns a tuple with the MaxNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNumber

`func (o *ConnectionServerLdapBackupSpec) SetMaxNumber(v int32)`

SetMaxNumber sets MaxNumber field to given value.


### GetTimeOffset

`func (o *ConnectionServerLdapBackupSpec) GetTimeOffset() int32`

GetTimeOffset returns the TimeOffset field if non-nil, zero value otherwise.

### GetTimeOffsetOk

`func (o *ConnectionServerLdapBackupSpec) GetTimeOffsetOk() (*int32, bool)`

GetTimeOffsetOk returns a tuple with the TimeOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeOffset

`func (o *ConnectionServerLdapBackupSpec) SetTimeOffset(v int32)`

SetTimeOffset sets TimeOffset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


