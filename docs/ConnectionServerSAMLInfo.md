# ConnectionServerSAMLInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SamlAuthenticatorIds** | Pointer to **[]string** | List of SamlAuthenticators to use. | [optional] 
**SamlSupport** | Pointer to **string** | SAML support option. * DISABLED: Indicates that the SAML support is disabled. * MULTI_ENABLED: Indicates that the SAML multi auth support is enabled. * MULTI_REQUIRED: Indicates that the SAML multi auth support is mandatory. | [optional] 
**WorkspaceOneBlockOldClients** | Pointer to **bool** | Block old clients that don&#39;t support Workspace ONE mode. | [optional] 
**WorkspaceOneHostName** | Pointer to **string** | The hostname of the Workspace ONE Server. | [optional] 
**WorkspaceOneModeEnabled** | Pointer to **bool** | Indicates whether Workspace ONE mode is enabled. | [optional] 

## Methods

### NewConnectionServerSAMLInfo

`func NewConnectionServerSAMLInfo() *ConnectionServerSAMLInfo`

NewConnectionServerSAMLInfo instantiates a new ConnectionServerSAMLInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerSAMLInfoWithDefaults

`func NewConnectionServerSAMLInfoWithDefaults() *ConnectionServerSAMLInfo`

NewConnectionServerSAMLInfoWithDefaults instantiates a new ConnectionServerSAMLInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSamlAuthenticatorIds

`func (o *ConnectionServerSAMLInfo) GetSamlAuthenticatorIds() []string`

GetSamlAuthenticatorIds returns the SamlAuthenticatorIds field if non-nil, zero value otherwise.

### GetSamlAuthenticatorIdsOk

`func (o *ConnectionServerSAMLInfo) GetSamlAuthenticatorIdsOk() (*[]string, bool)`

GetSamlAuthenticatorIdsOk returns a tuple with the SamlAuthenticatorIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamlAuthenticatorIds

`func (o *ConnectionServerSAMLInfo) SetSamlAuthenticatorIds(v []string)`

SetSamlAuthenticatorIds sets SamlAuthenticatorIds field to given value.

### HasSamlAuthenticatorIds

`func (o *ConnectionServerSAMLInfo) HasSamlAuthenticatorIds() bool`

HasSamlAuthenticatorIds returns a boolean if a field has been set.

### GetSamlSupport

`func (o *ConnectionServerSAMLInfo) GetSamlSupport() string`

GetSamlSupport returns the SamlSupport field if non-nil, zero value otherwise.

### GetSamlSupportOk

`func (o *ConnectionServerSAMLInfo) GetSamlSupportOk() (*string, bool)`

GetSamlSupportOk returns a tuple with the SamlSupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamlSupport

`func (o *ConnectionServerSAMLInfo) SetSamlSupport(v string)`

SetSamlSupport sets SamlSupport field to given value.

### HasSamlSupport

`func (o *ConnectionServerSAMLInfo) HasSamlSupport() bool`

HasSamlSupport returns a boolean if a field has been set.

### GetWorkspaceOneBlockOldClients

`func (o *ConnectionServerSAMLInfo) GetWorkspaceOneBlockOldClients() bool`

GetWorkspaceOneBlockOldClients returns the WorkspaceOneBlockOldClients field if non-nil, zero value otherwise.

### GetWorkspaceOneBlockOldClientsOk

`func (o *ConnectionServerSAMLInfo) GetWorkspaceOneBlockOldClientsOk() (*bool, bool)`

GetWorkspaceOneBlockOldClientsOk returns a tuple with the WorkspaceOneBlockOldClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceOneBlockOldClients

`func (o *ConnectionServerSAMLInfo) SetWorkspaceOneBlockOldClients(v bool)`

SetWorkspaceOneBlockOldClients sets WorkspaceOneBlockOldClients field to given value.

### HasWorkspaceOneBlockOldClients

`func (o *ConnectionServerSAMLInfo) HasWorkspaceOneBlockOldClients() bool`

HasWorkspaceOneBlockOldClients returns a boolean if a field has been set.

### GetWorkspaceOneHostName

`func (o *ConnectionServerSAMLInfo) GetWorkspaceOneHostName() string`

GetWorkspaceOneHostName returns the WorkspaceOneHostName field if non-nil, zero value otherwise.

### GetWorkspaceOneHostNameOk

`func (o *ConnectionServerSAMLInfo) GetWorkspaceOneHostNameOk() (*string, bool)`

GetWorkspaceOneHostNameOk returns a tuple with the WorkspaceOneHostName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceOneHostName

`func (o *ConnectionServerSAMLInfo) SetWorkspaceOneHostName(v string)`

SetWorkspaceOneHostName sets WorkspaceOneHostName field to given value.

### HasWorkspaceOneHostName

`func (o *ConnectionServerSAMLInfo) HasWorkspaceOneHostName() bool`

HasWorkspaceOneHostName returns a boolean if a field has been set.

### GetWorkspaceOneModeEnabled

`func (o *ConnectionServerSAMLInfo) GetWorkspaceOneModeEnabled() bool`

GetWorkspaceOneModeEnabled returns the WorkspaceOneModeEnabled field if non-nil, zero value otherwise.

### GetWorkspaceOneModeEnabledOk

`func (o *ConnectionServerSAMLInfo) GetWorkspaceOneModeEnabledOk() (*bool, bool)`

GetWorkspaceOneModeEnabledOk returns a tuple with the WorkspaceOneModeEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceOneModeEnabled

`func (o *ConnectionServerSAMLInfo) SetWorkspaceOneModeEnabled(v bool)`

SetWorkspaceOneModeEnabled sets WorkspaceOneModeEnabled field to given value.

### HasWorkspaceOneModeEnabled

`func (o *ConnectionServerSAMLInfo) HasWorkspaceOneModeEnabled() bool`

HasWorkspaceOneModeEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


