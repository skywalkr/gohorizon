# ConnectionServerUpdateSpecV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuxillaryExternalPcoipIpv4Address** | Pointer to **string** | This can be set only if external_pcoip_url is set and contains a host part that represents an IPv6 address or DNS name.  As legacy clients may not support IPv6 or DNS names for external PCoIP URLs, this IPv4 address, if set, will be presented to them as an alternative. The same port will be used and should not be specified.  If bypass_pcoip_gateway is set to true, this property will be ignored. | [optional] 
**BypassAppBlastGateway** | **bool** | Indicates whether a bypassing blast secure gateway is enabled for this connection server instance.  If this is set to true, web browsers make direct connections to Horizon machines bypassing connection server. | 
**BypassPcoipGateway** | **bool** | Indicates whether the PCoIP traffic bypasses the secure gateway. | 
**BypassTunnel** | Pointer to **bool** | Indicates whether a secure tunnel on this connection server instance is enabled.  If this is set to false, a secure tunnel on this Connection Server instance is enabled and horizon clents can connect to desktop pools through the secure tunnel,  which carries RDP and other data over HTTPS. PCoIP and HTML Access connections use separate secure gateways. | [optional] 
**DirectHtmlabsg** | Pointer to **bool** | Indicates whether only HTML clients use blast secure gateway for this connection server instance.  This property will not be set if bypass_appblast_gateway is set to false. | [optional] 
**DiscloseServicePrincipalName** | **bool** | Indicates whether the connection server&#39;s service principal name will be sent to the client prior to the user authentication.When set to true Connection Server discloses its service principal name to the client. | 
**EnableSmartCardUserNameHint** | Pointer to **bool** | Indicates whether username hints for smart card is enabled. | [optional] 
**Enabled** | **bool** | Indicate whether the connection server is enabled. A disabled connection server will not accept connection requests from Horizon Clients. | 
**ExternalAppblastUrl** | Pointer to **string** | The Blast External URL enables browser access to Horizon machines through this connection server instance.  To enable Blast, you must install HTML Access.  The Blast External URL must not be load balanced.  If bypass_appblast_gateway is set to true, this property will be ignored. | [optional] 
**ExternalPcoipUrl** | Pointer to **string** | Horizon Clients use the PCoIP External URL to establish a PCoIP connection through this Connection Server instance.  The PCoIP External URL must not be load balanced.  If bypass_pcoip_gateway is set to true, this property will be ignored. | [optional] 
**ExternalUrl** | Pointer to **string** | Horizon Clients use the External URL to establish a secure tunnel to this Connection Server instance.  If a server name is specified, it must be resolvable by each Horizon Client.  The External URL must not be load balanced.  If bypass_tunnel is set to true, this property will be ignored. | [optional] 
**GssApiinfo** | [**ConnectionServerGSSAPISpec**](ConnectionServerGSSAPISpec.md) |  | 
**HostRedirection** | **bool** | Indicates whether connection server supports HTTP host redirection. | 
**JwtInfo** | Pointer to [**ConnectionServerJWTSpec**](ConnectionServerJWTSpec.md) |  | [optional] 
**LdapBackupInfo** | Pointer to [**ConnectionServerLdapBackupSpec**](ConnectionServerLdapBackupSpec.md) |  | [optional] 
**LogoffWhenRemoveSmartCard** | Pointer to **bool** | Indicates whether user is logged off on removal of Smart Card. | [optional] 
**RadiusInfo** | [**ConnectionServerRADIUSSpec**](ConnectionServerRADIUSSpec.md) |  | 
**RsaSecureIdInfo** | [**ConnectionServerRSASecureIdSpec**](ConnectionServerRSASecureIdSpec.md) |  | 
**SamlInfo** | [**ConnectionServerSAMLSpec**](ConnectionServerSAMLSpec.md) |  | 
**SmartCardSupport** | **string** | Indicates whether the smart card is supported for client or not * OPTIONAL: Indicates that the SmartCard usage is optional. * REQUIRED: Indicates that the SmartCard usage is necessary. * OFF: Indicates that the SmartCard usage is not allowed. | 
**SmartCardSupportForAdmin** | **string** | Indicates Smart card authentication configuration for administrators to login. * OPTIONAL: Indicates that the SmartCard usage is optional. * REQUIRED: Indicates that the SmartCard usage is necessary. * OFF: Indicates that the SmartCard usage is not allowed. | 
**Tags** | Pointer to **[]string** | Tags to restrict accessibility to desktop pools through this server. | [optional] 
**UnauthenticatedAccessInfo** | [**ConnectionServerUnauthenticatedAccessSpec**](ConnectionServerUnauthenticatedAccessSpec.md) |  | 

## Methods

### NewConnectionServerUpdateSpecV2

`func NewConnectionServerUpdateSpecV2(bypassAppBlastGateway bool, bypassPcoipGateway bool, discloseServicePrincipalName bool, enabled bool, gssApiinfo ConnectionServerGSSAPISpec, hostRedirection bool, radiusInfo ConnectionServerRADIUSSpec, rsaSecureIdInfo ConnectionServerRSASecureIdSpec, samlInfo ConnectionServerSAMLSpec, smartCardSupport string, smartCardSupportForAdmin string, unauthenticatedAccessInfo ConnectionServerUnauthenticatedAccessSpec, ) *ConnectionServerUpdateSpecV2`

NewConnectionServerUpdateSpecV2 instantiates a new ConnectionServerUpdateSpecV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerUpdateSpecV2WithDefaults

`func NewConnectionServerUpdateSpecV2WithDefaults() *ConnectionServerUpdateSpecV2`

NewConnectionServerUpdateSpecV2WithDefaults instantiates a new ConnectionServerUpdateSpecV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuxillaryExternalPcoipIpv4Address

`func (o *ConnectionServerUpdateSpecV2) GetAuxillaryExternalPcoipIpv4Address() string`

GetAuxillaryExternalPcoipIpv4Address returns the AuxillaryExternalPcoipIpv4Address field if non-nil, zero value otherwise.

### GetAuxillaryExternalPcoipIpv4AddressOk

`func (o *ConnectionServerUpdateSpecV2) GetAuxillaryExternalPcoipIpv4AddressOk() (*string, bool)`

GetAuxillaryExternalPcoipIpv4AddressOk returns a tuple with the AuxillaryExternalPcoipIpv4Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuxillaryExternalPcoipIpv4Address

`func (o *ConnectionServerUpdateSpecV2) SetAuxillaryExternalPcoipIpv4Address(v string)`

SetAuxillaryExternalPcoipIpv4Address sets AuxillaryExternalPcoipIpv4Address field to given value.

### HasAuxillaryExternalPcoipIpv4Address

`func (o *ConnectionServerUpdateSpecV2) HasAuxillaryExternalPcoipIpv4Address() bool`

HasAuxillaryExternalPcoipIpv4Address returns a boolean if a field has been set.

### GetBypassAppBlastGateway

`func (o *ConnectionServerUpdateSpecV2) GetBypassAppBlastGateway() bool`

GetBypassAppBlastGateway returns the BypassAppBlastGateway field if non-nil, zero value otherwise.

### GetBypassAppBlastGatewayOk

`func (o *ConnectionServerUpdateSpecV2) GetBypassAppBlastGatewayOk() (*bool, bool)`

GetBypassAppBlastGatewayOk returns a tuple with the BypassAppBlastGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBypassAppBlastGateway

`func (o *ConnectionServerUpdateSpecV2) SetBypassAppBlastGateway(v bool)`

SetBypassAppBlastGateway sets BypassAppBlastGateway field to given value.


### GetBypassPcoipGateway

`func (o *ConnectionServerUpdateSpecV2) GetBypassPcoipGateway() bool`

GetBypassPcoipGateway returns the BypassPcoipGateway field if non-nil, zero value otherwise.

### GetBypassPcoipGatewayOk

`func (o *ConnectionServerUpdateSpecV2) GetBypassPcoipGatewayOk() (*bool, bool)`

GetBypassPcoipGatewayOk returns a tuple with the BypassPcoipGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBypassPcoipGateway

`func (o *ConnectionServerUpdateSpecV2) SetBypassPcoipGateway(v bool)`

SetBypassPcoipGateway sets BypassPcoipGateway field to given value.


### GetBypassTunnel

`func (o *ConnectionServerUpdateSpecV2) GetBypassTunnel() bool`

GetBypassTunnel returns the BypassTunnel field if non-nil, zero value otherwise.

### GetBypassTunnelOk

`func (o *ConnectionServerUpdateSpecV2) GetBypassTunnelOk() (*bool, bool)`

GetBypassTunnelOk returns a tuple with the BypassTunnel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBypassTunnel

`func (o *ConnectionServerUpdateSpecV2) SetBypassTunnel(v bool)`

SetBypassTunnel sets BypassTunnel field to given value.

### HasBypassTunnel

`func (o *ConnectionServerUpdateSpecV2) HasBypassTunnel() bool`

HasBypassTunnel returns a boolean if a field has been set.

### GetDirectHtmlabsg

`func (o *ConnectionServerUpdateSpecV2) GetDirectHtmlabsg() bool`

GetDirectHtmlabsg returns the DirectHtmlabsg field if non-nil, zero value otherwise.

### GetDirectHtmlabsgOk

`func (o *ConnectionServerUpdateSpecV2) GetDirectHtmlabsgOk() (*bool, bool)`

GetDirectHtmlabsgOk returns a tuple with the DirectHtmlabsg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectHtmlabsg

`func (o *ConnectionServerUpdateSpecV2) SetDirectHtmlabsg(v bool)`

SetDirectHtmlabsg sets DirectHtmlabsg field to given value.

### HasDirectHtmlabsg

`func (o *ConnectionServerUpdateSpecV2) HasDirectHtmlabsg() bool`

HasDirectHtmlabsg returns a boolean if a field has been set.

### GetDiscloseServicePrincipalName

`func (o *ConnectionServerUpdateSpecV2) GetDiscloseServicePrincipalName() bool`

GetDiscloseServicePrincipalName returns the DiscloseServicePrincipalName field if non-nil, zero value otherwise.

### GetDiscloseServicePrincipalNameOk

`func (o *ConnectionServerUpdateSpecV2) GetDiscloseServicePrincipalNameOk() (*bool, bool)`

GetDiscloseServicePrincipalNameOk returns a tuple with the DiscloseServicePrincipalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscloseServicePrincipalName

`func (o *ConnectionServerUpdateSpecV2) SetDiscloseServicePrincipalName(v bool)`

SetDiscloseServicePrincipalName sets DiscloseServicePrincipalName field to given value.


### GetEnableSmartCardUserNameHint

`func (o *ConnectionServerUpdateSpecV2) GetEnableSmartCardUserNameHint() bool`

GetEnableSmartCardUserNameHint returns the EnableSmartCardUserNameHint field if non-nil, zero value otherwise.

### GetEnableSmartCardUserNameHintOk

`func (o *ConnectionServerUpdateSpecV2) GetEnableSmartCardUserNameHintOk() (*bool, bool)`

GetEnableSmartCardUserNameHintOk returns a tuple with the EnableSmartCardUserNameHint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableSmartCardUserNameHint

`func (o *ConnectionServerUpdateSpecV2) SetEnableSmartCardUserNameHint(v bool)`

SetEnableSmartCardUserNameHint sets EnableSmartCardUserNameHint field to given value.

### HasEnableSmartCardUserNameHint

`func (o *ConnectionServerUpdateSpecV2) HasEnableSmartCardUserNameHint() bool`

HasEnableSmartCardUserNameHint returns a boolean if a field has been set.

### GetEnabled

`func (o *ConnectionServerUpdateSpecV2) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ConnectionServerUpdateSpecV2) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ConnectionServerUpdateSpecV2) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetExternalAppblastUrl

`func (o *ConnectionServerUpdateSpecV2) GetExternalAppblastUrl() string`

GetExternalAppblastUrl returns the ExternalAppblastUrl field if non-nil, zero value otherwise.

### GetExternalAppblastUrlOk

`func (o *ConnectionServerUpdateSpecV2) GetExternalAppblastUrlOk() (*string, bool)`

GetExternalAppblastUrlOk returns a tuple with the ExternalAppblastUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalAppblastUrl

`func (o *ConnectionServerUpdateSpecV2) SetExternalAppblastUrl(v string)`

SetExternalAppblastUrl sets ExternalAppblastUrl field to given value.

### HasExternalAppblastUrl

`func (o *ConnectionServerUpdateSpecV2) HasExternalAppblastUrl() bool`

HasExternalAppblastUrl returns a boolean if a field has been set.

### GetExternalPcoipUrl

`func (o *ConnectionServerUpdateSpecV2) GetExternalPcoipUrl() string`

GetExternalPcoipUrl returns the ExternalPcoipUrl field if non-nil, zero value otherwise.

### GetExternalPcoipUrlOk

`func (o *ConnectionServerUpdateSpecV2) GetExternalPcoipUrlOk() (*string, bool)`

GetExternalPcoipUrlOk returns a tuple with the ExternalPcoipUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalPcoipUrl

`func (o *ConnectionServerUpdateSpecV2) SetExternalPcoipUrl(v string)`

SetExternalPcoipUrl sets ExternalPcoipUrl field to given value.

### HasExternalPcoipUrl

`func (o *ConnectionServerUpdateSpecV2) HasExternalPcoipUrl() bool`

HasExternalPcoipUrl returns a boolean if a field has been set.

### GetExternalUrl

`func (o *ConnectionServerUpdateSpecV2) GetExternalUrl() string`

GetExternalUrl returns the ExternalUrl field if non-nil, zero value otherwise.

### GetExternalUrlOk

`func (o *ConnectionServerUpdateSpecV2) GetExternalUrlOk() (*string, bool)`

GetExternalUrlOk returns a tuple with the ExternalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalUrl

`func (o *ConnectionServerUpdateSpecV2) SetExternalUrl(v string)`

SetExternalUrl sets ExternalUrl field to given value.

### HasExternalUrl

`func (o *ConnectionServerUpdateSpecV2) HasExternalUrl() bool`

HasExternalUrl returns a boolean if a field has been set.

### GetGssApiinfo

`func (o *ConnectionServerUpdateSpecV2) GetGssApiinfo() ConnectionServerGSSAPISpec`

GetGssApiinfo returns the GssApiinfo field if non-nil, zero value otherwise.

### GetGssApiinfoOk

`func (o *ConnectionServerUpdateSpecV2) GetGssApiinfoOk() (*ConnectionServerGSSAPISpec, bool)`

GetGssApiinfoOk returns a tuple with the GssApiinfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGssApiinfo

`func (o *ConnectionServerUpdateSpecV2) SetGssApiinfo(v ConnectionServerGSSAPISpec)`

SetGssApiinfo sets GssApiinfo field to given value.


### GetHostRedirection

`func (o *ConnectionServerUpdateSpecV2) GetHostRedirection() bool`

GetHostRedirection returns the HostRedirection field if non-nil, zero value otherwise.

### GetHostRedirectionOk

`func (o *ConnectionServerUpdateSpecV2) GetHostRedirectionOk() (*bool, bool)`

GetHostRedirectionOk returns a tuple with the HostRedirection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostRedirection

`func (o *ConnectionServerUpdateSpecV2) SetHostRedirection(v bool)`

SetHostRedirection sets HostRedirection field to given value.


### GetJwtInfo

`func (o *ConnectionServerUpdateSpecV2) GetJwtInfo() ConnectionServerJWTSpec`

GetJwtInfo returns the JwtInfo field if non-nil, zero value otherwise.

### GetJwtInfoOk

`func (o *ConnectionServerUpdateSpecV2) GetJwtInfoOk() (*ConnectionServerJWTSpec, bool)`

GetJwtInfoOk returns a tuple with the JwtInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtInfo

`func (o *ConnectionServerUpdateSpecV2) SetJwtInfo(v ConnectionServerJWTSpec)`

SetJwtInfo sets JwtInfo field to given value.

### HasJwtInfo

`func (o *ConnectionServerUpdateSpecV2) HasJwtInfo() bool`

HasJwtInfo returns a boolean if a field has been set.

### GetLdapBackupInfo

`func (o *ConnectionServerUpdateSpecV2) GetLdapBackupInfo() ConnectionServerLdapBackupSpec`

GetLdapBackupInfo returns the LdapBackupInfo field if non-nil, zero value otherwise.

### GetLdapBackupInfoOk

`func (o *ConnectionServerUpdateSpecV2) GetLdapBackupInfoOk() (*ConnectionServerLdapBackupSpec, bool)`

GetLdapBackupInfoOk returns a tuple with the LdapBackupInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLdapBackupInfo

`func (o *ConnectionServerUpdateSpecV2) SetLdapBackupInfo(v ConnectionServerLdapBackupSpec)`

SetLdapBackupInfo sets LdapBackupInfo field to given value.

### HasLdapBackupInfo

`func (o *ConnectionServerUpdateSpecV2) HasLdapBackupInfo() bool`

HasLdapBackupInfo returns a boolean if a field has been set.

### GetLogoffWhenRemoveSmartCard

`func (o *ConnectionServerUpdateSpecV2) GetLogoffWhenRemoveSmartCard() bool`

GetLogoffWhenRemoveSmartCard returns the LogoffWhenRemoveSmartCard field if non-nil, zero value otherwise.

### GetLogoffWhenRemoveSmartCardOk

`func (o *ConnectionServerUpdateSpecV2) GetLogoffWhenRemoveSmartCardOk() (*bool, bool)`

GetLogoffWhenRemoveSmartCardOk returns a tuple with the LogoffWhenRemoveSmartCard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoffWhenRemoveSmartCard

`func (o *ConnectionServerUpdateSpecV2) SetLogoffWhenRemoveSmartCard(v bool)`

SetLogoffWhenRemoveSmartCard sets LogoffWhenRemoveSmartCard field to given value.

### HasLogoffWhenRemoveSmartCard

`func (o *ConnectionServerUpdateSpecV2) HasLogoffWhenRemoveSmartCard() bool`

HasLogoffWhenRemoveSmartCard returns a boolean if a field has been set.

### GetRadiusInfo

`func (o *ConnectionServerUpdateSpecV2) GetRadiusInfo() ConnectionServerRADIUSSpec`

GetRadiusInfo returns the RadiusInfo field if non-nil, zero value otherwise.

### GetRadiusInfoOk

`func (o *ConnectionServerUpdateSpecV2) GetRadiusInfoOk() (*ConnectionServerRADIUSSpec, bool)`

GetRadiusInfoOk returns a tuple with the RadiusInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusInfo

`func (o *ConnectionServerUpdateSpecV2) SetRadiusInfo(v ConnectionServerRADIUSSpec)`

SetRadiusInfo sets RadiusInfo field to given value.


### GetRsaSecureIdInfo

`func (o *ConnectionServerUpdateSpecV2) GetRsaSecureIdInfo() ConnectionServerRSASecureIdSpec`

GetRsaSecureIdInfo returns the RsaSecureIdInfo field if non-nil, zero value otherwise.

### GetRsaSecureIdInfoOk

`func (o *ConnectionServerUpdateSpecV2) GetRsaSecureIdInfoOk() (*ConnectionServerRSASecureIdSpec, bool)`

GetRsaSecureIdInfoOk returns a tuple with the RsaSecureIdInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRsaSecureIdInfo

`func (o *ConnectionServerUpdateSpecV2) SetRsaSecureIdInfo(v ConnectionServerRSASecureIdSpec)`

SetRsaSecureIdInfo sets RsaSecureIdInfo field to given value.


### GetSamlInfo

`func (o *ConnectionServerUpdateSpecV2) GetSamlInfo() ConnectionServerSAMLSpec`

GetSamlInfo returns the SamlInfo field if non-nil, zero value otherwise.

### GetSamlInfoOk

`func (o *ConnectionServerUpdateSpecV2) GetSamlInfoOk() (*ConnectionServerSAMLSpec, bool)`

GetSamlInfoOk returns a tuple with the SamlInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamlInfo

`func (o *ConnectionServerUpdateSpecV2) SetSamlInfo(v ConnectionServerSAMLSpec)`

SetSamlInfo sets SamlInfo field to given value.


### GetSmartCardSupport

`func (o *ConnectionServerUpdateSpecV2) GetSmartCardSupport() string`

GetSmartCardSupport returns the SmartCardSupport field if non-nil, zero value otherwise.

### GetSmartCardSupportOk

`func (o *ConnectionServerUpdateSpecV2) GetSmartCardSupportOk() (*string, bool)`

GetSmartCardSupportOk returns a tuple with the SmartCardSupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartCardSupport

`func (o *ConnectionServerUpdateSpecV2) SetSmartCardSupport(v string)`

SetSmartCardSupport sets SmartCardSupport field to given value.


### GetSmartCardSupportForAdmin

`func (o *ConnectionServerUpdateSpecV2) GetSmartCardSupportForAdmin() string`

GetSmartCardSupportForAdmin returns the SmartCardSupportForAdmin field if non-nil, zero value otherwise.

### GetSmartCardSupportForAdminOk

`func (o *ConnectionServerUpdateSpecV2) GetSmartCardSupportForAdminOk() (*string, bool)`

GetSmartCardSupportForAdminOk returns a tuple with the SmartCardSupportForAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartCardSupportForAdmin

`func (o *ConnectionServerUpdateSpecV2) SetSmartCardSupportForAdmin(v string)`

SetSmartCardSupportForAdmin sets SmartCardSupportForAdmin field to given value.


### GetTags

`func (o *ConnectionServerUpdateSpecV2) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ConnectionServerUpdateSpecV2) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ConnectionServerUpdateSpecV2) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ConnectionServerUpdateSpecV2) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetUnauthenticatedAccessInfo

`func (o *ConnectionServerUpdateSpecV2) GetUnauthenticatedAccessInfo() ConnectionServerUnauthenticatedAccessSpec`

GetUnauthenticatedAccessInfo returns the UnauthenticatedAccessInfo field if non-nil, zero value otherwise.

### GetUnauthenticatedAccessInfoOk

`func (o *ConnectionServerUpdateSpecV2) GetUnauthenticatedAccessInfoOk() (*ConnectionServerUnauthenticatedAccessSpec, bool)`

GetUnauthenticatedAccessInfoOk returns a tuple with the UnauthenticatedAccessInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnauthenticatedAccessInfo

`func (o *ConnectionServerUpdateSpecV2) SetUnauthenticatedAccessInfo(v ConnectionServerUnauthenticatedAccessSpec)`

SetUnauthenticatedAccessInfo sets UnauthenticatedAccessInfo field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


