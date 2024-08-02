# AgentInstallerPackageInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BuildNumber** | Pointer to **string** | Build number of the installer. | [optional] 
**Id** | Pointer to **string** | Unique identifier for this agent installer package. | [optional] 
**Url** | Pointer to **string** | URL of the installer executable. | [optional] 
**Version** | Pointer to **string** | Version of the installer MSI. | [optional] 

## Methods

### NewAgentInstallerPackageInfo

`func NewAgentInstallerPackageInfo() *AgentInstallerPackageInfo`

NewAgentInstallerPackageInfo instantiates a new AgentInstallerPackageInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentInstallerPackageInfoWithDefaults

`func NewAgentInstallerPackageInfoWithDefaults() *AgentInstallerPackageInfo`

NewAgentInstallerPackageInfoWithDefaults instantiates a new AgentInstallerPackageInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBuildNumber

`func (o *AgentInstallerPackageInfo) GetBuildNumber() string`

GetBuildNumber returns the BuildNumber field if non-nil, zero value otherwise.

### GetBuildNumberOk

`func (o *AgentInstallerPackageInfo) GetBuildNumberOk() (*string, bool)`

GetBuildNumberOk returns a tuple with the BuildNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildNumber

`func (o *AgentInstallerPackageInfo) SetBuildNumber(v string)`

SetBuildNumber sets BuildNumber field to given value.

### HasBuildNumber

`func (o *AgentInstallerPackageInfo) HasBuildNumber() bool`

HasBuildNumber returns a boolean if a field has been set.

### GetId

`func (o *AgentInstallerPackageInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentInstallerPackageInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentInstallerPackageInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AgentInstallerPackageInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUrl

`func (o *AgentInstallerPackageInfo) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *AgentInstallerPackageInfo) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *AgentInstallerPackageInfo) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *AgentInstallerPackageInfo) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetVersion

`func (o *AgentInstallerPackageInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *AgentInstallerPackageInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *AgentInstallerPackageInfo) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *AgentInstallerPackageInfo) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


