# ConnectionServerInfoV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuxillaryExternalPcoipIpv4Address** | Pointer to **string** | This is set only if external_pcoip_url is set and contains a host part that represents an IPv6 address or DNS name.  As legacy clients may not support IPv6 or DNS names for external PCoIP URLs, this IPv4 address, if set, will be presented to them as an alternative. The same port will be used and should not be specified.  If bypass_pcoip_gateway is set to true, this property will not be set. | [optional] 
**BypassAppBlastGateway** | Pointer to **bool** | Indicates whether a bypassing blast secure gateway is enabled for this connection server instance.  If this is set to true, web browsers make direct connections to Horizon machines bypassing connection server. | [optional] 
**BypassPcoipGateway** | Pointer to **bool** | Indicates whether the PCoIP traffic bypasses the secure gateway. | [optional] 
**BypassTunnel** | Pointer to **bool** | Indicates whether a secure tunnel on this connection server instance is enabled.  If this is set to false, a secure tunnel on this Connection Server instance is enabled and horizon clents can connect to desktop pools through the secure tunnel,  which carries RDP and other data over HTTPS. PCoIP and HTML Access connections use separate secure gateways. | [optional] 
**ClusterName** | Pointer to **string** | Cluster name. | [optional] 
**DirectHtmlabsg** | Pointer to **bool** | Indicates whether only HTML clients use blast secure gateway for this connection server instance.  This property will not be set if bypass_appblast_gateway is set to false. | [optional] 
**DiscloseServicePrincipalName** | Pointer to **bool** | Indicates whether the connection server&#39;s service principal name will be sent to the client prior to the user authentication.When set to true Connection Server discloses its service principal name to the client. | [optional] 
**EnableSmartCardUserNameHint** | Pointer to **bool** | Indicates whether username hints for smart card is enabled. | [optional] 
**Enabled** | Pointer to **bool** | Indicate whether the connection server is enabled. A disabled connection server will not accept connection requests from Horizon Clients. | [optional] 
**ExternalAppblastUrl** | Pointer to **string** | The Blast External URL enables browser access to Horizon machines through this connection server instance.  To enable Blast, you must install HTML Access.  The Blast External URL must not be load balanced.  If bypass_appblast_gateway is set to true, this property will not be set. | [optional] 
**ExternalPcoipUrl** | Pointer to **string** | Horizon Clients use the PCoIP External URL to establish a PCoIP connection through this Connection Server instance.  The PCoIP External URL must not be load balanced.  If bypass_pcoip_gateway is set to true, this property will not be set. | [optional] 
**ExternalUrl** | Pointer to **string** | Horizon Clients use the External URL to establish a secure tunnel to this Connection Server instance.  If a server name is specified, it must be resolvable by each Horizon Client.  The External URL must not be load balanced.  If bypass_tunnel is set to true, this property will not be set. | [optional] 
**FipsModeEnabled** | Pointer to **bool** | Indicates whether this server has FIPS mode enabled. | [optional] 
**Fqhn** | Pointer to **string** | Fully qualified host name. | [optional] 
**GssApiinfo** | Pointer to [**ConnectionServerGSSAPIInfo**](ConnectionServerGSSAPIInfo.md) |  | [optional] 
**HasBlastGatewaySupport** | Pointer to **bool** | Indicates whether Blast gateway is supported or not. | [optional] 
**HasPcoipGatewaySupport** | Pointer to **bool** | Indicates whether PCoIP gateway is supported or not. | [optional] 
**HostRedirection** | Pointer to **bool** | Indicates whether connection server supports HTTP host redirection. | [optional] 
**Id** | Pointer to **string** | Unique Id of the Connection Server. | [optional] 
**IpMode** | Pointer to **string** | Indicates the Connection Server IP environment. * IPv4: The ip mode is IPv4. * IPv6: The ip mode is IPv6. | [optional] 
**JwtInfo** | Pointer to [**ConnectionServerJWTInfo**](ConnectionServerJWTInfo.md) |  | [optional] 
**LdapBackupInfo** | Pointer to [**ConnectionServerLdapBackupInfo**](ConnectionServerLdapBackupInfo.md) |  | [optional] 
**LoadBalancerHosts** | Pointer to **[]string** | List of load balancer host names or IP address. | [optional] 
**LocalConnectionServer** | Pointer to **bool** | Indicates whether this is the local connection server that handled the connection server service request. | [optional] 
**LogoffWhenRemoveSmartCard** | Pointer to **bool** | Indicates whether user is logged off on removal of Smart Card. | [optional] 
**MessageSecurityEnhancedModeSupported** | Pointer to **bool** | Indicates whether ENHANCED message security mode is currently supported by this Connection Server. | [optional] 
**MsgSecurityPublicKey** | Pointer to **string** | The JMS message security public key. | [optional] 
**Name** | Pointer to **string** | Name of the Connection Server. | [optional] 
**RadiusInfo** | Pointer to [**ConnectionServerRADIUSInfo**](ConnectionServerRADIUSInfo.md) |  | [optional] 
**RouterSslThumbprints** | Pointer to **[]string** | The JMS router SSL thumbprints | [optional] 
**RsaSecureIdInfo** | Pointer to [**ConnectionServerRSASecureIdInfo**](ConnectionServerRSASecureIdInfo.md) |  | [optional] 
**SamlInfo** | Pointer to [**ConnectionServerSAMLInfo**](ConnectionServerSAMLInfo.md) |  | [optional] 
**ServerUrl** | Pointer to **string** | General URL for the connection server. | [optional] 
**SmartCardSupport** | Pointer to **string** | Smart Card support option. * OPTIONAL: Indicates that the SmartCard usage is optional. * REQUIRED: Indicates that the SmartCard usage is necessary. * OFF: Indicates that the SmartCard usage is not allowed. | [optional] 
**SmartCardSupportForAdmin** | Pointer to **string** | Indicates Smart card authentication configuration for administrators to login. * OPTIONAL: Indicates that the SmartCard usage is optional. * REQUIRED: Indicates that the SmartCard usage is necessary. * OFF: Indicates that the SmartCard usage is not allowed. | [optional] 
**Tags** | Pointer to **[]string** | Tags to restrict accessibility to desktop pools through this server. | [optional] 
**UnauthenticatedAccessInfo** | Pointer to [**ConnectionServerUnauthenticatedAccessInfo**](ConnectionServerUnauthenticatedAccessInfo.md) |  | [optional] 
**Version** | Pointer to **string** | Version attribute to indicate functionalities supported by current connection server. | [optional] 

## Methods

### NewConnectionServerInfoV2

`func NewConnectionServerInfoV2() *ConnectionServerInfoV2`

NewConnectionServerInfoV2 instantiates a new ConnectionServerInfoV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServerInfoV2WithDefaults

`func NewConnectionServerInfoV2WithDefaults() *ConnectionServerInfoV2`

NewConnectionServerInfoV2WithDefaults instantiates a new ConnectionServerInfoV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuxillaryExternalPcoipIpv4Address

`func (o *ConnectionServerInfoV2) GetAuxillaryExternalPcoipIpv4Address() string`

GetAuxillaryExternalPcoipIpv4Address returns the AuxillaryExternalPcoipIpv4Address field if non-nil, zero value otherwise.

### GetAuxillaryExternalPcoipIpv4AddressOk

`func (o *ConnectionServerInfoV2) GetAuxillaryExternalPcoipIpv4AddressOk() (*string, bool)`

GetAuxillaryExternalPcoipIpv4AddressOk returns a tuple with the AuxillaryExternalPcoipIpv4Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuxillaryExternalPcoipIpv4Address

`func (o *ConnectionServerInfoV2) SetAuxillaryExternalPcoipIpv4Address(v string)`

SetAuxillaryExternalPcoipIpv4Address sets AuxillaryExternalPcoipIpv4Address field to given value.

### HasAuxillaryExternalPcoipIpv4Address

`func (o *ConnectionServerInfoV2) HasAuxillaryExternalPcoipIpv4Address() bool`

HasAuxillaryExternalPcoipIpv4Address returns a boolean if a field has been set.

### GetBypassAppBlastGateway

`func (o *ConnectionServerInfoV2) GetBypassAppBlastGateway() bool`

GetBypassAppBlastGateway returns the BypassAppBlastGateway field if non-nil, zero value otherwise.

### GetBypassAppBlastGatewayOk

`func (o *ConnectionServerInfoV2) GetBypassAppBlastGatewayOk() (*bool, bool)`

GetBypassAppBlastGatewayOk returns a tuple with the BypassAppBlastGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBypassAppBlastGateway

`func (o *ConnectionServerInfoV2) SetBypassAppBlastGateway(v bool)`

SetBypassAppBlastGateway sets BypassAppBlastGateway field to given value.

### HasBypassAppBlastGateway

`func (o *ConnectionServerInfoV2) HasBypassAppBlastGateway() bool`

HasBypassAppBlastGateway returns a boolean if a field has been set.

### GetBypassPcoipGateway

`func (o *ConnectionServerInfoV2) GetBypassPcoipGateway() bool`

GetBypassPcoipGateway returns the BypassPcoipGateway field if non-nil, zero value otherwise.

### GetBypassPcoipGatewayOk

`func (o *ConnectionServerInfoV2) GetBypassPcoipGatewayOk() (*bool, bool)`

GetBypassPcoipGatewayOk returns a tuple with the BypassPcoipGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBypassPcoipGateway

`func (o *ConnectionServerInfoV2) SetBypassPcoipGateway(v bool)`

SetBypassPcoipGateway sets BypassPcoipGateway field to given value.

### HasBypassPcoipGateway

`func (o *ConnectionServerInfoV2) HasBypassPcoipGateway() bool`

HasBypassPcoipGateway returns a boolean if a field has been set.

### GetBypassTunnel

`func (o *ConnectionServerInfoV2) GetBypassTunnel() bool`

GetBypassTunnel returns the BypassTunnel field if non-nil, zero value otherwise.

### GetBypassTunnelOk

`func (o *ConnectionServerInfoV2) GetBypassTunnelOk() (*bool, bool)`

GetBypassTunnelOk returns a tuple with the BypassTunnel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBypassTunnel

`func (o *ConnectionServerInfoV2) SetBypassTunnel(v bool)`

SetBypassTunnel sets BypassTunnel field to given value.

### HasBypassTunnel

`func (o *ConnectionServerInfoV2) HasBypassTunnel() bool`

HasBypassTunnel returns a boolean if a field has been set.

### GetClusterName

`func (o *ConnectionServerInfoV2) GetClusterName() string`

GetClusterName returns the ClusterName field if non-nil, zero value otherwise.

### GetClusterNameOk

`func (o *ConnectionServerInfoV2) GetClusterNameOk() (*string, bool)`

GetClusterNameOk returns a tuple with the ClusterName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterName

`func (o *ConnectionServerInfoV2) SetClusterName(v string)`

SetClusterName sets ClusterName field to given value.

### HasClusterName

`func (o *ConnectionServerInfoV2) HasClusterName() bool`

HasClusterName returns a boolean if a field has been set.

### GetDirectHtmlabsg

`func (o *ConnectionServerInfoV2) GetDirectHtmlabsg() bool`

GetDirectHtmlabsg returns the DirectHtmlabsg field if non-nil, zero value otherwise.

### GetDirectHtmlabsgOk

`func (o *ConnectionServerInfoV2) GetDirectHtmlabsgOk() (*bool, bool)`

GetDirectHtmlabsgOk returns a tuple with the DirectHtmlabsg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectHtmlabsg

`func (o *ConnectionServerInfoV2) SetDirectHtmlabsg(v bool)`

SetDirectHtmlabsg sets DirectHtmlabsg field to given value.

### HasDirectHtmlabsg

`func (o *ConnectionServerInfoV2) HasDirectHtmlabsg() bool`

HasDirectHtmlabsg returns a boolean if a field has been set.

### GetDiscloseServicePrincipalName

`func (o *ConnectionServerInfoV2) GetDiscloseServicePrincipalName() bool`

GetDiscloseServicePrincipalName returns the DiscloseServicePrincipalName field if non-nil, zero value otherwise.

### GetDiscloseServicePrincipalNameOk

`func (o *ConnectionServerInfoV2) GetDiscloseServicePrincipalNameOk() (*bool, bool)`

GetDiscloseServicePrincipalNameOk returns a tuple with the DiscloseServicePrincipalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscloseServicePrincipalName

`func (o *ConnectionServerInfoV2) SetDiscloseServicePrincipalName(v bool)`

SetDiscloseServicePrincipalName sets DiscloseServicePrincipalName field to given value.

### HasDiscloseServicePrincipalName

`func (o *ConnectionServerInfoV2) HasDiscloseServicePrincipalName() bool`

HasDiscloseServicePrincipalName returns a boolean if a field has been set.

### GetEnableSmartCardUserNameHint

`func (o *ConnectionServerInfoV2) GetEnableSmartCardUserNameHint() bool`

GetEnableSmartCardUserNameHint returns the EnableSmartCardUserNameHint field if non-nil, zero value otherwise.

### GetEnableSmartCardUserNameHintOk

`func (o *ConnectionServerInfoV2) GetEnableSmartCardUserNameHintOk() (*bool, bool)`

GetEnableSmartCardUserNameHintOk returns a tuple with the EnableSmartCardUserNameHint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableSmartCardUserNameHint

`func (o *ConnectionServerInfoV2) SetEnableSmartCardUserNameHint(v bool)`

SetEnableSmartCardUserNameHint sets EnableSmartCardUserNameHint field to given value.

### HasEnableSmartCardUserNameHint

`func (o *ConnectionServerInfoV2) HasEnableSmartCardUserNameHint() bool`

HasEnableSmartCardUserNameHint returns a boolean if a field has been set.

### GetEnabled

`func (o *ConnectionServerInfoV2) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ConnectionServerInfoV2) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ConnectionServerInfoV2) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ConnectionServerInfoV2) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetExternalAppblastUrl

`func (o *ConnectionServerInfoV2) GetExternalAppblastUrl() string`

GetExternalAppblastUrl returns the ExternalAppblastUrl field if non-nil, zero value otherwise.

### GetExternalAppblastUrlOk

`func (o *ConnectionServerInfoV2) GetExternalAppblastUrlOk() (*string, bool)`

GetExternalAppblastUrlOk returns a tuple with the ExternalAppblastUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalAppblastUrl

`func (o *ConnectionServerInfoV2) SetExternalAppblastUrl(v string)`

SetExternalAppblastUrl sets ExternalAppblastUrl field to given value.

### HasExternalAppblastUrl

`func (o *ConnectionServerInfoV2) HasExternalAppblastUrl() bool`

HasExternalAppblastUrl returns a boolean if a field has been set.

### GetExternalPcoipUrl

`func (o *ConnectionServerInfoV2) GetExternalPcoipUrl() string`

GetExternalPcoipUrl returns the ExternalPcoipUrl field if non-nil, zero value otherwise.

### GetExternalPcoipUrlOk

`func (o *ConnectionServerInfoV2) GetExternalPcoipUrlOk() (*string, bool)`

GetExternalPcoipUrlOk returns a tuple with the ExternalPcoipUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalPcoipUrl

`func (o *ConnectionServerInfoV2) SetExternalPcoipUrl(v string)`

SetExternalPcoipUrl sets ExternalPcoipUrl field to given value.

### HasExternalPcoipUrl

`func (o *ConnectionServerInfoV2) HasExternalPcoipUrl() bool`

HasExternalPcoipUrl returns a boolean if a field has been set.

### GetExternalUrl

`func (o *ConnectionServerInfoV2) GetExternalUrl() string`

GetExternalUrl returns the ExternalUrl field if non-nil, zero value otherwise.

### GetExternalUrlOk

`func (o *ConnectionServerInfoV2) GetExternalUrlOk() (*string, bool)`

GetExternalUrlOk returns a tuple with the ExternalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalUrl

`func (o *ConnectionServerInfoV2) SetExternalUrl(v string)`

SetExternalUrl sets ExternalUrl field to given value.

### HasExternalUrl

`func (o *ConnectionServerInfoV2) HasExternalUrl() bool`

HasExternalUrl returns a boolean if a field has been set.

### GetFipsModeEnabled

`func (o *ConnectionServerInfoV2) GetFipsModeEnabled() bool`

GetFipsModeEnabled returns the FipsModeEnabled field if non-nil, zero value otherwise.

### GetFipsModeEnabledOk

`func (o *ConnectionServerInfoV2) GetFipsModeEnabledOk() (*bool, bool)`

GetFipsModeEnabledOk returns a tuple with the FipsModeEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFipsModeEnabled

`func (o *ConnectionServerInfoV2) SetFipsModeEnabled(v bool)`

SetFipsModeEnabled sets FipsModeEnabled field to given value.

### HasFipsModeEnabled

`func (o *ConnectionServerInfoV2) HasFipsModeEnabled() bool`

HasFipsModeEnabled returns a boolean if a field has been set.

### GetFqhn

`func (o *ConnectionServerInfoV2) GetFqhn() string`

GetFqhn returns the Fqhn field if non-nil, zero value otherwise.

### GetFqhnOk

`func (o *ConnectionServerInfoV2) GetFqhnOk() (*string, bool)`

GetFqhnOk returns a tuple with the Fqhn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFqhn

`func (o *ConnectionServerInfoV2) SetFqhn(v string)`

SetFqhn sets Fqhn field to given value.

### HasFqhn

`func (o *ConnectionServerInfoV2) HasFqhn() bool`

HasFqhn returns a boolean if a field has been set.

### GetGssApiinfo

`func (o *ConnectionServerInfoV2) GetGssApiinfo() ConnectionServerGSSAPIInfo`

GetGssApiinfo returns the GssApiinfo field if non-nil, zero value otherwise.

### GetGssApiinfoOk

`func (o *ConnectionServerInfoV2) GetGssApiinfoOk() (*ConnectionServerGSSAPIInfo, bool)`

GetGssApiinfoOk returns a tuple with the GssApiinfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGssApiinfo

`func (o *ConnectionServerInfoV2) SetGssApiinfo(v ConnectionServerGSSAPIInfo)`

SetGssApiinfo sets GssApiinfo field to given value.

### HasGssApiinfo

`func (o *ConnectionServerInfoV2) HasGssApiinfo() bool`

HasGssApiinfo returns a boolean if a field has been set.

### GetHasBlastGatewaySupport

`func (o *ConnectionServerInfoV2) GetHasBlastGatewaySupport() bool`

GetHasBlastGatewaySupport returns the HasBlastGatewaySupport field if non-nil, zero value otherwise.

### GetHasBlastGatewaySupportOk

`func (o *ConnectionServerInfoV2) GetHasBlastGatewaySupportOk() (*bool, bool)`

GetHasBlastGatewaySupportOk returns a tuple with the HasBlastGatewaySupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasBlastGatewaySupport

`func (o *ConnectionServerInfoV2) SetHasBlastGatewaySupport(v bool)`

SetHasBlastGatewaySupport sets HasBlastGatewaySupport field to given value.

### HasHasBlastGatewaySupport

`func (o *ConnectionServerInfoV2) HasHasBlastGatewaySupport() bool`

HasHasBlastGatewaySupport returns a boolean if a field has been set.

### GetHasPcoipGatewaySupport

`func (o *ConnectionServerInfoV2) GetHasPcoipGatewaySupport() bool`

GetHasPcoipGatewaySupport returns the HasPcoipGatewaySupport field if non-nil, zero value otherwise.

### GetHasPcoipGatewaySupportOk

`func (o *ConnectionServerInfoV2) GetHasPcoipGatewaySupportOk() (*bool, bool)`

GetHasPcoipGatewaySupportOk returns a tuple with the HasPcoipGatewaySupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasPcoipGatewaySupport

`func (o *ConnectionServerInfoV2) SetHasPcoipGatewaySupport(v bool)`

SetHasPcoipGatewaySupport sets HasPcoipGatewaySupport field to given value.

### HasHasPcoipGatewaySupport

`func (o *ConnectionServerInfoV2) HasHasPcoipGatewaySupport() bool`

HasHasPcoipGatewaySupport returns a boolean if a field has been set.

### GetHostRedirection

`func (o *ConnectionServerInfoV2) GetHostRedirection() bool`

GetHostRedirection returns the HostRedirection field if non-nil, zero value otherwise.

### GetHostRedirectionOk

`func (o *ConnectionServerInfoV2) GetHostRedirectionOk() (*bool, bool)`

GetHostRedirectionOk returns a tuple with the HostRedirection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostRedirection

`func (o *ConnectionServerInfoV2) SetHostRedirection(v bool)`

SetHostRedirection sets HostRedirection field to given value.

### HasHostRedirection

`func (o *ConnectionServerInfoV2) HasHostRedirection() bool`

HasHostRedirection returns a boolean if a field has been set.

### GetId

`func (o *ConnectionServerInfoV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConnectionServerInfoV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConnectionServerInfoV2) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ConnectionServerInfoV2) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIpMode

`func (o *ConnectionServerInfoV2) GetIpMode() string`

GetIpMode returns the IpMode field if non-nil, zero value otherwise.

### GetIpModeOk

`func (o *ConnectionServerInfoV2) GetIpModeOk() (*string, bool)`

GetIpModeOk returns a tuple with the IpMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpMode

`func (o *ConnectionServerInfoV2) SetIpMode(v string)`

SetIpMode sets IpMode field to given value.

### HasIpMode

`func (o *ConnectionServerInfoV2) HasIpMode() bool`

HasIpMode returns a boolean if a field has been set.

### GetJwtInfo

`func (o *ConnectionServerInfoV2) GetJwtInfo() ConnectionServerJWTInfo`

GetJwtInfo returns the JwtInfo field if non-nil, zero value otherwise.

### GetJwtInfoOk

`func (o *ConnectionServerInfoV2) GetJwtInfoOk() (*ConnectionServerJWTInfo, bool)`

GetJwtInfoOk returns a tuple with the JwtInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtInfo

`func (o *ConnectionServerInfoV2) SetJwtInfo(v ConnectionServerJWTInfo)`

SetJwtInfo sets JwtInfo field to given value.

### HasJwtInfo

`func (o *ConnectionServerInfoV2) HasJwtInfo() bool`

HasJwtInfo returns a boolean if a field has been set.

### GetLdapBackupInfo

`func (o *ConnectionServerInfoV2) GetLdapBackupInfo() ConnectionServerLdapBackupInfo`

GetLdapBackupInfo returns the LdapBackupInfo field if non-nil, zero value otherwise.

### GetLdapBackupInfoOk

`func (o *ConnectionServerInfoV2) GetLdapBackupInfoOk() (*ConnectionServerLdapBackupInfo, bool)`

GetLdapBackupInfoOk returns a tuple with the LdapBackupInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLdapBackupInfo

`func (o *ConnectionServerInfoV2) SetLdapBackupInfo(v ConnectionServerLdapBackupInfo)`

SetLdapBackupInfo sets LdapBackupInfo field to given value.

### HasLdapBackupInfo

`func (o *ConnectionServerInfoV2) HasLdapBackupInfo() bool`

HasLdapBackupInfo returns a boolean if a field has been set.

### GetLoadBalancerHosts

`func (o *ConnectionServerInfoV2) GetLoadBalancerHosts() []string`

GetLoadBalancerHosts returns the LoadBalancerHosts field if non-nil, zero value otherwise.

### GetLoadBalancerHostsOk

`func (o *ConnectionServerInfoV2) GetLoadBalancerHostsOk() (*[]string, bool)`

GetLoadBalancerHostsOk returns a tuple with the LoadBalancerHosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadBalancerHosts

`func (o *ConnectionServerInfoV2) SetLoadBalancerHosts(v []string)`

SetLoadBalancerHosts sets LoadBalancerHosts field to given value.

### HasLoadBalancerHosts

`func (o *ConnectionServerInfoV2) HasLoadBalancerHosts() bool`

HasLoadBalancerHosts returns a boolean if a field has been set.

### GetLocalConnectionServer

`func (o *ConnectionServerInfoV2) GetLocalConnectionServer() bool`

GetLocalConnectionServer returns the LocalConnectionServer field if non-nil, zero value otherwise.

### GetLocalConnectionServerOk

`func (o *ConnectionServerInfoV2) GetLocalConnectionServerOk() (*bool, bool)`

GetLocalConnectionServerOk returns a tuple with the LocalConnectionServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalConnectionServer

`func (o *ConnectionServerInfoV2) SetLocalConnectionServer(v bool)`

SetLocalConnectionServer sets LocalConnectionServer field to given value.

### HasLocalConnectionServer

`func (o *ConnectionServerInfoV2) HasLocalConnectionServer() bool`

HasLocalConnectionServer returns a boolean if a field has been set.

### GetLogoffWhenRemoveSmartCard

`func (o *ConnectionServerInfoV2) GetLogoffWhenRemoveSmartCard() bool`

GetLogoffWhenRemoveSmartCard returns the LogoffWhenRemoveSmartCard field if non-nil, zero value otherwise.

### GetLogoffWhenRemoveSmartCardOk

`func (o *ConnectionServerInfoV2) GetLogoffWhenRemoveSmartCardOk() (*bool, bool)`

GetLogoffWhenRemoveSmartCardOk returns a tuple with the LogoffWhenRemoveSmartCard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoffWhenRemoveSmartCard

`func (o *ConnectionServerInfoV2) SetLogoffWhenRemoveSmartCard(v bool)`

SetLogoffWhenRemoveSmartCard sets LogoffWhenRemoveSmartCard field to given value.

### HasLogoffWhenRemoveSmartCard

`func (o *ConnectionServerInfoV2) HasLogoffWhenRemoveSmartCard() bool`

HasLogoffWhenRemoveSmartCard returns a boolean if a field has been set.

### GetMessageSecurityEnhancedModeSupported

`func (o *ConnectionServerInfoV2) GetMessageSecurityEnhancedModeSupported() bool`

GetMessageSecurityEnhancedModeSupported returns the MessageSecurityEnhancedModeSupported field if non-nil, zero value otherwise.

### GetMessageSecurityEnhancedModeSupportedOk

`func (o *ConnectionServerInfoV2) GetMessageSecurityEnhancedModeSupportedOk() (*bool, bool)`

GetMessageSecurityEnhancedModeSupportedOk returns a tuple with the MessageSecurityEnhancedModeSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageSecurityEnhancedModeSupported

`func (o *ConnectionServerInfoV2) SetMessageSecurityEnhancedModeSupported(v bool)`

SetMessageSecurityEnhancedModeSupported sets MessageSecurityEnhancedModeSupported field to given value.

### HasMessageSecurityEnhancedModeSupported

`func (o *ConnectionServerInfoV2) HasMessageSecurityEnhancedModeSupported() bool`

HasMessageSecurityEnhancedModeSupported returns a boolean if a field has been set.

### GetMsgSecurityPublicKey

`func (o *ConnectionServerInfoV2) GetMsgSecurityPublicKey() string`

GetMsgSecurityPublicKey returns the MsgSecurityPublicKey field if non-nil, zero value otherwise.

### GetMsgSecurityPublicKeyOk

`func (o *ConnectionServerInfoV2) GetMsgSecurityPublicKeyOk() (*string, bool)`

GetMsgSecurityPublicKeyOk returns a tuple with the MsgSecurityPublicKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsgSecurityPublicKey

`func (o *ConnectionServerInfoV2) SetMsgSecurityPublicKey(v string)`

SetMsgSecurityPublicKey sets MsgSecurityPublicKey field to given value.

### HasMsgSecurityPublicKey

`func (o *ConnectionServerInfoV2) HasMsgSecurityPublicKey() bool`

HasMsgSecurityPublicKey returns a boolean if a field has been set.

### GetName

`func (o *ConnectionServerInfoV2) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConnectionServerInfoV2) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConnectionServerInfoV2) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ConnectionServerInfoV2) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRadiusInfo

`func (o *ConnectionServerInfoV2) GetRadiusInfo() ConnectionServerRADIUSInfo`

GetRadiusInfo returns the RadiusInfo field if non-nil, zero value otherwise.

### GetRadiusInfoOk

`func (o *ConnectionServerInfoV2) GetRadiusInfoOk() (*ConnectionServerRADIUSInfo, bool)`

GetRadiusInfoOk returns a tuple with the RadiusInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadiusInfo

`func (o *ConnectionServerInfoV2) SetRadiusInfo(v ConnectionServerRADIUSInfo)`

SetRadiusInfo sets RadiusInfo field to given value.

### HasRadiusInfo

`func (o *ConnectionServerInfoV2) HasRadiusInfo() bool`

HasRadiusInfo returns a boolean if a field has been set.

### GetRouterSslThumbprints

`func (o *ConnectionServerInfoV2) GetRouterSslThumbprints() []string`

GetRouterSslThumbprints returns the RouterSslThumbprints field if non-nil, zero value otherwise.

### GetRouterSslThumbprintsOk

`func (o *ConnectionServerInfoV2) GetRouterSslThumbprintsOk() (*[]string, bool)`

GetRouterSslThumbprintsOk returns a tuple with the RouterSslThumbprints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouterSslThumbprints

`func (o *ConnectionServerInfoV2) SetRouterSslThumbprints(v []string)`

SetRouterSslThumbprints sets RouterSslThumbprints field to given value.

### HasRouterSslThumbprints

`func (o *ConnectionServerInfoV2) HasRouterSslThumbprints() bool`

HasRouterSslThumbprints returns a boolean if a field has been set.

### GetRsaSecureIdInfo

`func (o *ConnectionServerInfoV2) GetRsaSecureIdInfo() ConnectionServerRSASecureIdInfo`

GetRsaSecureIdInfo returns the RsaSecureIdInfo field if non-nil, zero value otherwise.

### GetRsaSecureIdInfoOk

`func (o *ConnectionServerInfoV2) GetRsaSecureIdInfoOk() (*ConnectionServerRSASecureIdInfo, bool)`

GetRsaSecureIdInfoOk returns a tuple with the RsaSecureIdInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRsaSecureIdInfo

`func (o *ConnectionServerInfoV2) SetRsaSecureIdInfo(v ConnectionServerRSASecureIdInfo)`

SetRsaSecureIdInfo sets RsaSecureIdInfo field to given value.

### HasRsaSecureIdInfo

`func (o *ConnectionServerInfoV2) HasRsaSecureIdInfo() bool`

HasRsaSecureIdInfo returns a boolean if a field has been set.

### GetSamlInfo

`func (o *ConnectionServerInfoV2) GetSamlInfo() ConnectionServerSAMLInfo`

GetSamlInfo returns the SamlInfo field if non-nil, zero value otherwise.

### GetSamlInfoOk

`func (o *ConnectionServerInfoV2) GetSamlInfoOk() (*ConnectionServerSAMLInfo, bool)`

GetSamlInfoOk returns a tuple with the SamlInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamlInfo

`func (o *ConnectionServerInfoV2) SetSamlInfo(v ConnectionServerSAMLInfo)`

SetSamlInfo sets SamlInfo field to given value.

### HasSamlInfo

`func (o *ConnectionServerInfoV2) HasSamlInfo() bool`

HasSamlInfo returns a boolean if a field has been set.

### GetServerUrl

`func (o *ConnectionServerInfoV2) GetServerUrl() string`

GetServerUrl returns the ServerUrl field if non-nil, zero value otherwise.

### GetServerUrlOk

`func (o *ConnectionServerInfoV2) GetServerUrlOk() (*string, bool)`

GetServerUrlOk returns a tuple with the ServerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerUrl

`func (o *ConnectionServerInfoV2) SetServerUrl(v string)`

SetServerUrl sets ServerUrl field to given value.

### HasServerUrl

`func (o *ConnectionServerInfoV2) HasServerUrl() bool`

HasServerUrl returns a boolean if a field has been set.

### GetSmartCardSupport

`func (o *ConnectionServerInfoV2) GetSmartCardSupport() string`

GetSmartCardSupport returns the SmartCardSupport field if non-nil, zero value otherwise.

### GetSmartCardSupportOk

`func (o *ConnectionServerInfoV2) GetSmartCardSupportOk() (*string, bool)`

GetSmartCardSupportOk returns a tuple with the SmartCardSupport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartCardSupport

`func (o *ConnectionServerInfoV2) SetSmartCardSupport(v string)`

SetSmartCardSupport sets SmartCardSupport field to given value.

### HasSmartCardSupport

`func (o *ConnectionServerInfoV2) HasSmartCardSupport() bool`

HasSmartCardSupport returns a boolean if a field has been set.

### GetSmartCardSupportForAdmin

`func (o *ConnectionServerInfoV2) GetSmartCardSupportForAdmin() string`

GetSmartCardSupportForAdmin returns the SmartCardSupportForAdmin field if non-nil, zero value otherwise.

### GetSmartCardSupportForAdminOk

`func (o *ConnectionServerInfoV2) GetSmartCardSupportForAdminOk() (*string, bool)`

GetSmartCardSupportForAdminOk returns a tuple with the SmartCardSupportForAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartCardSupportForAdmin

`func (o *ConnectionServerInfoV2) SetSmartCardSupportForAdmin(v string)`

SetSmartCardSupportForAdmin sets SmartCardSupportForAdmin field to given value.

### HasSmartCardSupportForAdmin

`func (o *ConnectionServerInfoV2) HasSmartCardSupportForAdmin() bool`

HasSmartCardSupportForAdmin returns a boolean if a field has been set.

### GetTags

`func (o *ConnectionServerInfoV2) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ConnectionServerInfoV2) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ConnectionServerInfoV2) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ConnectionServerInfoV2) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetUnauthenticatedAccessInfo

`func (o *ConnectionServerInfoV2) GetUnauthenticatedAccessInfo() ConnectionServerUnauthenticatedAccessInfo`

GetUnauthenticatedAccessInfo returns the UnauthenticatedAccessInfo field if non-nil, zero value otherwise.

### GetUnauthenticatedAccessInfoOk

`func (o *ConnectionServerInfoV2) GetUnauthenticatedAccessInfoOk() (*ConnectionServerUnauthenticatedAccessInfo, bool)`

GetUnauthenticatedAccessInfoOk returns a tuple with the UnauthenticatedAccessInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnauthenticatedAccessInfo

`func (o *ConnectionServerInfoV2) SetUnauthenticatedAccessInfo(v ConnectionServerUnauthenticatedAccessInfo)`

SetUnauthenticatedAccessInfo sets UnauthenticatedAccessInfo field to given value.

### HasUnauthenticatedAccessInfo

`func (o *ConnectionServerInfoV2) HasUnauthenticatedAccessInfo() bool`

HasUnauthenticatedAccessInfo returns a boolean if a field has been set.

### GetVersion

`func (o *ConnectionServerInfoV2) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ConnectionServerInfoV2) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ConnectionServerInfoV2) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ConnectionServerInfoV2) HasVersion() bool`

HasVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


