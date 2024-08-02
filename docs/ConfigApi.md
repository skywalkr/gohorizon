# \ConfigAPI

All URIs are relative to *http://localhost/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddAppVolumesManager**](ConfigAPI.md#AddAppVolumesManager) | **Post** /config/v1/app-volumes-manager | Add the app volumes manager
[**AssignFarms**](ConfigAPI.md#AssignFarms) | **Post** /config/v1/app-volumes-manager/{id}/action/assign-farms | Assign Farms to App Volumes Manager
[**ClearEventDatabase**](ConfigAPI.md#ClearEventDatabase) | **Post** /config/v1/event-database/action/clear | Deletes event database configuration.
[**CreateFederationAccessGroup**](ConfigAPI.md#CreateFederationAccessGroup) | **Post** /config/v1/federation-access-groups | Creates federation access group.
[**CreateGSSAPIAuthenticator**](ConfigAPI.md#CreateGSSAPIAuthenticator) | **Post** /config/v1/gssapi-authenticators | Creates a GSSAPI authenticator.
[**CreateICDomainAccount**](ConfigAPI.md#CreateICDomainAccount) | **Post** /config/v1/ic-domain-accounts | Creates instant clone domain account.
[**CreateIMAsset**](ConfigAPI.md#CreateIMAsset) | **Post** /config/v1/im-assets | Creates image management asset.
[**CreateIMAssets**](ConfigAPI.md#CreateIMAssets) | **Post** /config/v1/im-assets/action/bulk-create | Creates one or more image management assets. Each of the index of result in the response, correspond to the index of the original asset.
[**CreateIMStream**](ConfigAPI.md#CreateIMStream) | **Post** /config/v1/im-streams | Creates image management stream.
[**CreateIMStreams**](ConfigAPI.md#CreateIMStreams) | **Post** /config/v1/im-streams/action/bulk-create | Creates one or more image management streams. Each of the index of result in the response, correspond to the index of the original stream.
[**CreateIMTag**](ConfigAPI.md#CreateIMTag) | **Post** /config/v1/im-tags | Creates image management tag.
[**CreateIMTags**](ConfigAPI.md#CreateIMTags) | **Post** /config/v1/im-tags/action/bulk-create | Creates one or more image management tags. Each of the index of result in the response, correspond to the index of the original tag.
[**CreateIMVersion**](ConfigAPI.md#CreateIMVersion) | **Post** /config/v1/im-versions | Creates image management version.
[**CreateIMVersions**](ConfigAPI.md#CreateIMVersions) | **Post** /config/v1/im-versions/action/bulk-create | Creates one or more image management versions. Each of the index of result in the response, correspond to the index of the original version.
[**CreateJWTAuthenticator**](ConfigAPI.md#CreateJWTAuthenticator) | **Post** /config/v1/jwt-authenticators | Creates a JWT authenticator.
[**CreateLocalAccessGroup**](ConfigAPI.md#CreateLocalAccessGroup) | **Post** /config/v1/local-access-groups | Creates local access group.
[**CreatePermissions**](ConfigAPI.md#CreatePermissions) | **Post** /config/v1/permissions | Creates permissions in bulk.
[**CreateRADIUSAuthenticator**](ConfigAPI.md#CreateRADIUSAuthenticator) | **Post** /config/v1/radius-authenticators | Creates a RADIUS Authenticator.
[**CreateRole**](ConfigAPI.md#CreateRole) | **Post** /config/v1/roles | Creates a role.
[**CreateSAMLAuthenticator**](ConfigAPI.md#CreateSAMLAuthenticator) | **Post** /config/v1/saml-authenticators | Creates a SAML authenticator.
[**CreateUnauthenticatedAccessUser**](ConfigAPI.md#CreateUnauthenticatedAccessUser) | **Post** /config/v1/unauthenticated-access-users | Creates a specified unauthenticated access user in the environment.
[**DeleteAppVolumesManager**](ConfigAPI.md#DeleteAppVolumesManager) | **Delete** /config/v1/app-volumes-manager/{id} | deletes the given app volumes manager
[**DeleteFederationAccessGroup**](ConfigAPI.md#DeleteFederationAccessGroup) | **Delete** /config/v1/federation-access-groups/{id} | Deletes a federation access group.
[**DeleteGSSAPIAuthenticator**](ConfigAPI.md#DeleteGSSAPIAuthenticator) | **Delete** /config/v1/gssapi-authenticators/{id} | Deletes a GSSAPI Authenticator.
[**DeleteICDomainAccount**](ConfigAPI.md#DeleteICDomainAccount) | **Delete** /config/v1/ic-domain-accounts/{id} | Deletes instant clone domain account.
[**DeleteIMAsset**](ConfigAPI.md#DeleteIMAsset) | **Delete** /config/v1/im-assets/{id} | Deletes image management asset.
[**DeleteIMStream**](ConfigAPI.md#DeleteIMStream) | **Delete** /config/v1/im-streams/{id} | Deletes image management stream.
[**DeleteIMTag**](ConfigAPI.md#DeleteIMTag) | **Delete** /config/v1/im-tags/{id} | Deletes image management tag.
[**DeleteIMVersion**](ConfigAPI.md#DeleteIMVersion) | **Delete** /config/v1/im-versions/{id} | Deletes image management version.
[**DeleteJWTAuthenticator**](ConfigAPI.md#DeleteJWTAuthenticator) | **Delete** /config/v1/jwt-authenticators/{id} | Deletes the given JWT authenticator.
[**DeleteLocalAccessGroup**](ConfigAPI.md#DeleteLocalAccessGroup) | **Delete** /config/v1/local-access-groups/{id} | Deletes a local access group.
[**DeletePermissions**](ConfigAPI.md#DeletePermissions) | **Delete** /config/v1/permissions | Deletes permissions in bulk.
[**DeleteRADIUSAuthenticator**](ConfigAPI.md#DeleteRADIUSAuthenticator) | **Delete** /config/v1/radius-authenticators/{id} | Deletes the given RADIUS Authenticator.
[**DeleteRole**](ConfigAPI.md#DeleteRole) | **Delete** /config/v1/roles/{id} | Deletes a role.
[**DeleteSAMLAuthenticator**](ConfigAPI.md#DeleteSAMLAuthenticator) | **Delete** /config/v1/saml-authenticators/{id} | Deletes a SAML Authenticator.
[**DeleteUnauthenticatedAccessUser**](ConfigAPI.md#DeleteUnauthenticatedAccessUser) | **Delete** /config/v1/unauthenticated-access-users/{id} | Deletes a specified unauthenticated access user in the environment.
[**DisableConnectionServers**](ConfigAPI.md#DisableConnectionServers) | **Post** /config/v1/connection-servers/action/disable | Disables the given list of connection server ids.
[**EnableConnectionServers**](ConfigAPI.md#EnableConnectionServers) | **Post** /config/v1/connection-servers/action/enable | Enables the given list of connection server ids.
[**GenerateCSR**](ConfigAPI.md#GenerateCSR) | **Post** /config/v1/connection-servers/action/generate-csr | Generate Certificate Signing Request(CSR).
[**GetAdminUsersOrGroupsPermissions**](ConfigAPI.md#GetAdminUsersOrGroupsPermissions) | **Get** /config/v1/admin-users-or-groups/permissions | Gets permission information for logged in admin user or group.
[**GetAppVolumesManager**](ConfigAPI.md#GetAppVolumesManager) | **Get** /config/v1/app-volumes-manager/{id} | Retrieves information about an app volumes manager.
[**GetCEIPInfo**](ConfigAPI.md#GetCEIPInfo) | **Get** /config/v1/ceip | Get the CEIP Information.
[**GetConnectionServer**](ConfigAPI.md#GetConnectionServer) | **Get** /config/v1/connection-servers/{id} | Retrieves information about a connection server.
[**GetConnectionServerV2**](ConfigAPI.md#GetConnectionServerV2) | **Get** /config/v2/connection-servers/{id} | Retrieves information about a connection server.
[**GetEnrollmentServer**](ConfigAPI.md#GetEnrollmentServer) | **Get** /config/v1/true-sso-enrollment-servers/{id} | Retrieves information about a paired TrueSSO Enrollment Server.
[**GetEnvironment**](ConfigAPI.md#GetEnvironment) | **Get** /config/v1/environment-properties | Retrieves the environment settings.
[**GetEnvironmentV2**](ConfigAPI.md#GetEnvironmentV2) | **Get** /config/v2/environment-properties | Retrieves the environment settings.
[**GetEventDatabase**](ConfigAPI.md#GetEventDatabase) | **Get** /config/v1/event-database | Returns information about event database configured.
[**GetFeatureSettings**](ConfigAPI.md#GetFeatureSettings) | **Get** /config/v1/settings/feature | Retrieves the feature settings.
[**GetFederationAccessGroup**](ConfigAPI.md#GetFederationAccessGroup) | **Get** /config/v1/federation-access-groups/{id} | Retrieves a federation access group.
[**GetFederationAccessGroupV2**](ConfigAPI.md#GetFederationAccessGroupV2) | **Get** /config/v2/federation-access-groups/{id} | Retrieves a federation access group.
[**GetGSSAPIAuthenticator**](ConfigAPI.md#GetGSSAPIAuthenticator) | **Get** /config/v1/gssapi-authenticators/{id} | Retrieves information about a GSSAPI Authenticator.
[**GetGateway**](ConfigAPI.md#GetGateway) | **Get** /config/v1/gateways/{id} | Retrieves information about a registered gateway.
[**GetGeneralSettings**](ConfigAPI.md#GetGeneralSettings) | **Get** /config/v1/settings/general | Retrieves the general settings.
[**GetGeneralSettingsV2**](ConfigAPI.md#GetGeneralSettingsV2) | **Get** /config/v2/settings/general | Retrieves the general settings.
[**GetGeneralSettingsV3**](ConfigAPI.md#GetGeneralSettingsV3) | **Get** /config/v3/settings/general | Retrieves the general settings.
[**GetICDomainAccount**](ConfigAPI.md#GetICDomainAccount) | **Get** /config/v1/ic-domain-accounts/{id} | Gets instant clone domain account.
[**GetIMAsset**](ConfigAPI.md#GetIMAsset) | **Get** /config/v1/im-assets/{id} | Gets image management asset.
[**GetIMStream**](ConfigAPI.md#GetIMStream) | **Get** /config/v1/im-streams/{id} | Gets image management stream.
[**GetIMTag**](ConfigAPI.md#GetIMTag) | **Get** /config/v1/im-tags/{id} | Gets image management tag.
[**GetIMVersion**](ConfigAPI.md#GetIMVersion) | **Get** /config/v1/im-versions/{id} | Gets image management version.
[**GetJWTAuthenticator**](ConfigAPI.md#GetJWTAuthenticator) | **Get** /config/v1/jwt-authenticators/{id} | Retrieves information about the given JWT authenticator.
[**GetLocalAccessGroup**](ConfigAPI.md#GetLocalAccessGroup) | **Get** /config/v1/local-access-groups/{id} | Retrieves a local access group.
[**GetLocalAccessGroupV2**](ConfigAPI.md#GetLocalAccessGroupV2) | **Get** /config/v2/local-access-groups/{id} | Retrieves a local access group.
[**GetPermission**](ConfigAPI.md#GetPermission) | **Get** /config/v1/permissions/{id} | Retrieves a permission.
[**GetPreLogonSettings**](ConfigAPI.md#GetPreLogonSettings) | **Get** /config/v1/pre-logon-settings | Gets the pre logon settings.
[**GetPreferences**](ConfigAPI.md#GetPreferences) | **Get** /config/v1/admin-users-or-groups/preferences | Gets Horizon Console preferences for the logged in administrator.
[**GetRADIUSAuthenticator**](ConfigAPI.md#GetRADIUSAuthenticator) | **Get** /config/v1/radius-authenticators/{id} | Retrieves information about a RADIUS Authenticator.
[**GetRole**](ConfigAPI.md#GetRole) | **Get** /config/v1/roles/{id} | Retrieves a role.
[**GetSAMLAuthenticator**](ConfigAPI.md#GetSAMLAuthenticator) | **Get** /config/v1/saml-authenticators/{id} | Retrieves information about a SAML authenticator.
[**GetSecurityConfigurationInfo**](ConfigAPI.md#GetSecurityConfigurationInfo) | **Get** /config/v1/connection-servers/security-configuration | Retrieves the security configuration of connection server and secure gateway
[**GetSecuritySettings**](ConfigAPI.md#GetSecuritySettings) | **Get** /config/v1/settings/security | Retrieves the security settings.
[**GetSecuritySettingsV2**](ConfigAPI.md#GetSecuritySettingsV2) | **Get** /config/v2/settings/security | Retrieves the security settings.
[**GetSettings**](ConfigAPI.md#GetSettings) | **Get** /config/v1/settings | Retrieves the configuration settings.
[**GetSettingsV2**](ConfigAPI.md#GetSettingsV2) | **Get** /config/v2/settings | Retrieves the configuration settings.
[**GetSettingsV3**](ConfigAPI.md#GetSettingsV3) | **Get** /config/v3/settings | Retrieves the configuration settings.
[**GetUnauthenticatedAccessUser**](ConfigAPI.md#GetUnauthenticatedAccessUser) | **Get** /config/v1/unauthenticated-access-users/{id} | Retrieves a specified unauthenticated access user in the environment.
[**ImportCertificate**](ConfigAPI.md#ImportCertificate) | **Post** /config/v1/connection-servers/action/import-certificate | Import the SSL certificate to connection server&#39;s personal certificate store.
[**ListAppVolumesManagers**](ConfigAPI.md#ListAppVolumesManagers) | **Get** /config/v1/app-volumes-manager | Lists the configured app volumes managers.
[**ListCertificateInfos**](ConfigAPI.md#ListCertificateInfos) | **Get** /config/v1/connection-servers/certificates | Retrieves the certificate details.
[**ListConnectionServers**](ConfigAPI.md#ListConnectionServers) | **Get** /config/v1/connection-servers | Lists the connection servers.
[**ListConnectionServersV2**](ConfigAPI.md#ListConnectionServersV2) | **Get** /config/v2/connection-servers | Lists the connection servers.
[**ListEnrollmentServers**](ConfigAPI.md#ListEnrollmentServers) | **Get** /config/v1/true-sso-enrollment-servers | Lists the paired TrueSSO Enrollment Servers.
[**ListFederationAccessGroups**](ConfigAPI.md#ListFederationAccessGroups) | **Get** /config/v1/federation-access-groups | Lists all federation access groups.
[**ListFederationAccessGroupsV2**](ConfigAPI.md#ListFederationAccessGroupsV2) | **Get** /config/v2/federation-access-groups | Lists all federation access groups.
[**ListGSSAPIAuthenticators**](ConfigAPI.md#ListGSSAPIAuthenticators) | **Get** /config/v1/gssapi-authenticators | Lists the configured GSSAPI Authenticators.
[**ListGateways**](ConfigAPI.md#ListGateways) | **Get** /config/v1/gateways | Lists the registered gateways.
[**ListICDomainAccounts**](ConfigAPI.md#ListICDomainAccounts) | **Get** /config/v1/ic-domain-accounts | Lists instant clone domain accounts of the environment.
[**ListIMAssets**](ConfigAPI.md#ListIMAssets) | **Get** /config/v1/im-assets | Lists image management assets.
[**ListIMStreams**](ConfigAPI.md#ListIMStreams) | **Get** /config/v1/im-streams | Lists image management streams.
[**ListIMTags**](ConfigAPI.md#ListIMTags) | **Get** /config/v1/im-tags | Lists image management tags.
[**ListIMVersions**](ConfigAPI.md#ListIMVersions) | **Get** /config/v1/im-versions | Lists image management versions.
[**ListJWTAuthenticators**](ConfigAPI.md#ListJWTAuthenticators) | **Get** /config/v1/jwt-authenticators | Lists the configured JWT authenticators.
[**ListLicenses**](ConfigAPI.md#ListLicenses) | **Get** /config/v1/licenses | Lists all licenses.
[**ListLicensesV2**](ConfigAPI.md#ListLicensesV2) | **Get** /config/v2/licenses | Lists all licenses.
[**ListLocalAccessGroups**](ConfigAPI.md#ListLocalAccessGroups) | **Get** /config/v1/local-access-groups | Lists all local access groups.
[**ListLocalAccessGroupsV2**](ConfigAPI.md#ListLocalAccessGroupsV2) | **Get** /config/v2/local-access-groups | Lists all local access groups.
[**ListPermissions**](ConfigAPI.md#ListPermissions) | **Get** /config/v1/permissions | Lists all permissions.
[**ListRADIUSAuthenticators**](ConfigAPI.md#ListRADIUSAuthenticators) | **Get** /config/v1/radius-authenticators | Lists the configured RADIUS Authenticators.
[**ListRCXServers**](ConfigAPI.md#ListRCXServers) | **Get** /config/v1/rcx/servers | Lists RCX servers of the cluster.
[**ListRoles**](ConfigAPI.md#ListRoles) | **Get** /config/v1/roles | Lists all roles.
[**ListSAMLAuthenticators**](ConfigAPI.md#ListSAMLAuthenticators) | **Get** /config/v1/saml-authenticators | Lists the configured SAML authenticators.
[**ListSelectablePrivileges**](ConfigAPI.md#ListSelectablePrivileges) | **Get** /config/v1/privileges | Lists all selectable privileges.
[**ListUnauthenticatedAccessUsers**](ConfigAPI.md#ListUnauthenticatedAccessUsers) | **Get** /config/v1/unauthenticated-access-users | Lists unauthenticated access users in the environment.
[**ListUsersOrGroupsLocalSummary**](ConfigAPI.md#ListUsersOrGroupsLocalSummary) | **Get** /config/v1/users-or-groups-local-summary | Lists local summary info of users or groups.
[**ListVCInfo**](ConfigAPI.md#ListVCInfo) | **Get** /config/v1/virtual-centers | Lists Virtual Centers configured in the environment.
[**ListVCInfoV2**](ConfigAPI.md#ListVCInfoV2) | **Get** /config/v2/virtual-centers | Lists Virtual Centers configured in the environment.
[**MarkDatastoresForArchival**](ConfigAPI.md#MarkDatastoresForArchival) | **Post** /config/v1/virtual-centers/{id}/action/mark-datastores-for-archival | Sets archival datastore paths for the vCenter.
[**PushCertificates**](ConfigAPI.md#PushCertificates) | **Post** /config/v1/app-volumes-manager/{id}/action/push-certificates | Push cluster certificates to App Volumes Manager
[**RegisterRCXClient**](ConfigAPI.md#RegisterRCXClient) | **Post** /config/v1/rcx/clients | Registers the RCX client
[**SetLicenseMode**](ConfigAPI.md#SetLicenseMode) | **Post** /config/v1/licenses/action/set-mode | Set the License Mode
[**UnassignFarms**](ConfigAPI.md#UnassignFarms) | **Post** /config/v1/app-volumes-manager/action/unassign-farms | Unassign Farms to App Volumes Manager
[**UnregisterRCXClient**](ConfigAPI.md#UnregisterRCXClient) | **Delete** /config/v1/rcx/clients/{id} | Unregisters the given RCX Client
[**UpdateAppVolumesManager**](ConfigAPI.md#UpdateAppVolumesManager) | **Put** /config/v1/app-volumes-manager/{id} | Updates the given app volumes manager.
[**UpdateConnectionServer**](ConfigAPI.md#UpdateConnectionServer) | **Put** /config/v1/connection-servers/{id} | Updates the settings of the given Connection Server.
[**UpdateConnectionServerV2**](ConfigAPI.md#UpdateConnectionServerV2) | **Put** /config/v2/connection-servers/{id} | Updates the settings of the given Connection Server.
[**UpdateEventDatabase**](ConfigAPI.md#UpdateEventDatabase) | **Put** /config/v1/event-database | Updates event database configuration.
[**UpdateFeatureSettings**](ConfigAPI.md#UpdateFeatureSettings) | **Put** /config/v1/settings/feature | Updates the feature settings.
[**UpdateGSSAPIAuthenticator**](ConfigAPI.md#UpdateGSSAPIAuthenticator) | **Put** /config/v1/gssapi-authenticators/{id} | Updates a GSSAPI Authenticator.
[**UpdateGeneralSettings**](ConfigAPI.md#UpdateGeneralSettings) | **Put** /config/v1/settings/general | Updates the general settings.
[**UpdateGeneralSettingsV2**](ConfigAPI.md#UpdateGeneralSettingsV2) | **Put** /config/v2/settings/general | Updates the general settings.
[**UpdateGeneralSettingsV3**](ConfigAPI.md#UpdateGeneralSettingsV3) | **Put** /config/v3/settings/general | Updates the general settings.
[**UpdateICDomainAccount**](ConfigAPI.md#UpdateICDomainAccount) | **Put** /config/v1/ic-domain-accounts/{id} | Updates instant clone domain account.
[**UpdateIMAsset**](ConfigAPI.md#UpdateIMAsset) | **Put** /config/v1/im-assets/{id} | Updates image management asset.
[**UpdateIMStream**](ConfigAPI.md#UpdateIMStream) | **Put** /config/v1/im-streams/{id} | Updates image management stream.
[**UpdateIMTag**](ConfigAPI.md#UpdateIMTag) | **Put** /config/v1/im-tags/{id} | Updates image management tag.
[**UpdateIMVersion**](ConfigAPI.md#UpdateIMVersion) | **Put** /config/v1/im-versions/{id} | Updates image management version.
[**UpdateJWTAuthenticator**](ConfigAPI.md#UpdateJWTAuthenticator) | **Put** /config/v1/jwt-authenticators/{id} | Updates the given JWT authenticator.
[**UpdatePreferences**](ConfigAPI.md#UpdatePreferences) | **Put** /config/v1/admin-users-or-groups/preferences | Updates the Horizon Console preferences for the logged in administrator.
[**UpdateRADIUSAuthenticator**](ConfigAPI.md#UpdateRADIUSAuthenticator) | **Put** /config/v1/radius-authenticators/{id} | Updates the given RADIUS Authenticator.
[**UpdateRCXClient**](ConfigAPI.md#UpdateRCXClient) | **Put** /config/v1/rcx/clients/{id} | Updates the given RCX client.
[**UpdateRole**](ConfigAPI.md#UpdateRole) | **Put** /config/v1/roles/{id} | Updates a role.
[**UpdateSAMLAuthenticator**](ConfigAPI.md#UpdateSAMLAuthenticator) | **Put** /config/v1/saml-authenticators/{id} | Updates a SAML Authenticator.
[**UpdateSecuritySettings**](ConfigAPI.md#UpdateSecuritySettings) | **Put** /config/v1/settings/security | Updates the security settings.
[**UpdateSettings**](ConfigAPI.md#UpdateSettings) | **Put** /config/v1/settings | Updates the configuration settings.
[**UpdateSettingsV2**](ConfigAPI.md#UpdateSettingsV2) | **Put** /config/v2/settings | Updates the configuration settings.
[**UpdateSettingsV3**](ConfigAPI.md#UpdateSettingsV3) | **Put** /config/v3/settings | Updates the configuration settings.
[**ValidateSAMLCertificate**](ConfigAPI.md#ValidateSAMLCertificate) | **Post** /config/v1/saml-authenticators/action/validate-certificate | Validates SAML Authenticator certificate.
[**ValidateVirtualCenterCertificate**](ConfigAPI.md#ValidateVirtualCenterCertificate) | **Post** /config/v1/virtual-centers/action/validate-certificate | Validates Virtual Center certificate.



## AddAppVolumesManager

> AddAppVolumesManager(ctx).Body(body).Execute()

Add the app volumes manager



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewAppVolumesManagerCreateSpec([]string{"Password_example"}, "avm.example.com", "administrator") // AppVolumesManagerCreateSpec | App volumes manager object to be added.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.AddAppVolumesManager(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.AddAppVolumesManager``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddAppVolumesManagerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AppVolumesManagerCreateSpec**](AppVolumesManagerCreateSpec.md) | App volumes manager object to be added. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AssignFarms

> []BulkItemResponseInfo AssignFarms(ctx, id).FarmIds(farmIds).Execute()

Assign Farms to App Volumes Manager



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | App volumes manager ID
	farmIds := []string{"Property_example"} // []string | List of farm Ids to be assigned with App Volumes manager

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.AssignFarms(context.Background(), id).FarmIds(farmIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.AssignFarms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AssignFarms`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.AssignFarms`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | App volumes manager ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiAssignFarmsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **farmIds** | **[]string** | List of farm Ids to be assigned with App Volumes manager | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClearEventDatabase

> ClearEventDatabase(ctx).Execute()

Deletes event database configuration.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.ClearEventDatabase(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ClearEventDatabase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiClearEventDatabaseRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateFederationAccessGroup

> CreateFederationAccessGroup(ctx).Body(body).Execute()

Creates federation access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewFederationAccessGroupCreateSpec("Sales") // FederationAccessGroupCreateSpec | Federation access group object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateFederationAccessGroup(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateFederationAccessGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateFederationAccessGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**FederationAccessGroupCreateSpec**](FederationAccessGroupCreateSpec.md) | Federation access group object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateGSSAPIAuthenticator

> CreateGSSAPIAuthenticator(ctx).Spec(spec).Execute()

Creates a GSSAPI authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	spec := *openapiclient.NewGSSAPIAuthenticatorCreateSpec(true, true, []string{"ConnectionServerIds_example"}, true, true, "ENABLED") // GSSAPIAuthenticatorCreateSpec | GSSAPI Authenticator specification

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateGSSAPIAuthenticator(context.Background()).Spec(spec).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateGSSAPIAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateGSSAPIAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **spec** | [**GSSAPIAuthenticatorCreateSpec**](GSSAPIAuthenticatorCreateSpec.md) | GSSAPI Authenticator specification | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateICDomainAccount

> CreateICDomainAccount(ctx).Body(body).Execute()

Creates instant clone domain account.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewInstantCloneDomainAccountCreateSpec("S-1-5-21-1085031214-1563985344-725345543", []string{"Password_example"}, "testuser") // InstantCloneDomainAccountCreateSpec | Instant clone domain account object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateICDomainAccount(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateICDomainAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateICDomainAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**InstantCloneDomainAccountCreateSpec**](InstantCloneDomainAccountCreateSpec.md) | Instant clone domain account object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMAsset

> CreateIMAsset(ctx).Body(body).Execute()

Creates image management asset.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewImageManagementAssetCreateSpec("INSTANT_CLONE", "abc16e8f-9ba0-4789-a5dd-6880f32c52df", "6f85b3a5-e7d0-4ad6-a1e3-37168dd1ed51", "RDSH_APPS", "AVAILABLE", "f148f3e8-db0e-4abb-9c33-7e5205ccd360") // ImageManagementAssetCreateSpec | Image management asset object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateIMAsset(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ImageManagementAssetCreateSpec**](ImageManagementAssetCreateSpec.md) | Image management asset object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMAssets

> []BulkItemResponseInfo CreateIMAssets(ctx).Body(body).Execute()

Creates one or more image management assets. Each of the index of result in the response, correspond to the index of the original asset.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []openapiclient.ImageManagementAssetCreateSpec{*openapiclient.NewImageManagementAssetCreateSpec("INSTANT_CLONE", "abc16e8f-9ba0-4789-a5dd-6880f32c52df", "6f85b3a5-e7d0-4ad6-a1e3-37168dd1ed51", "RDSH_APPS", "AVAILABLE", "f148f3e8-db0e-4abb-9c33-7e5205ccd360")} // []ImageManagementAssetCreateSpec | List of Image management asset object to be created in bulk.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.CreateIMAssets(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateIMAssets`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.CreateIMAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**[]ImageManagementAssetCreateSpec**](ImageManagementAssetCreateSpec.md) | List of Image management asset object to be created in bulk. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMStream

> CreateIMStream(ctx).Body(body).Execute()

Creates image management stream.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewImageManagementStreamCreateSpec("Win10", "WINDOWS_10", "MARKET_PLACE", "AVAILABLE") // ImageManagementStreamCreateSpec | Image management stream object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateIMStream(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ImageManagementStreamCreateSpec**](ImageManagementStreamCreateSpec.md) | Image management stream object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMStreams

> []BulkItemResponseInfo CreateIMStreams(ctx).Body(body).Execute()

Creates one or more image management streams. Each of the index of result in the response, correspond to the index of the original stream.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []openapiclient.ImageManagementStreamCreateSpec{*openapiclient.NewImageManagementStreamCreateSpec("Win10", "WINDOWS_10", "MARKET_PLACE", "AVAILABLE")} // []ImageManagementStreamCreateSpec | List of Image management stream object to be created in bulk.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.CreateIMStreams(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMStreams``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateIMStreams`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.CreateIMStreams`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMStreamsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**[]ImageManagementStreamCreateSpec**](ImageManagementStreamCreateSpec.md) | List of Image management stream object to be created in bulk. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMTag

> CreateIMTag(ctx).Body(body).Execute()

Creates image management tag.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewImageManagementTagCreateSpec("abc16e8f-9ba0-4789-a5dd-6880f32c52df", "6f85b3a5-e7d0-4ad6-a1e3-37168dd1ed51", "PROD") // ImageManagementTagCreateSpec | Image management tag object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateIMTag(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMTag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMTagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ImageManagementTagCreateSpec**](ImageManagementTagCreateSpec.md) | Image management tag object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMTags

> []BulkItemResponseInfo CreateIMTags(ctx).Body(body).Execute()

Creates one or more image management tags. Each of the index of result in the response, correspond to the index of the original tag.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []openapiclient.ImageManagementTagCreateSpec{*openapiclient.NewImageManagementTagCreateSpec("abc16e8f-9ba0-4789-a5dd-6880f32c52df", "6f85b3a5-e7d0-4ad6-a1e3-37168dd1ed51", "PROD")} // []ImageManagementTagCreateSpec | List of Image management tag object to be created in bulk.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.CreateIMTags(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateIMTags`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.CreateIMTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**[]ImageManagementTagCreateSpec**](ImageManagementTagCreateSpec.md) | List of Image management tag object to be created in bulk. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMVersion

> CreateIMVersion(ctx).Body(body).Execute()

Creates image management version.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewImageManagementVersionCreateSpec("abc16e8f-9ba0-4789-a5dd-6880f32c52df", "v1", "AVAILABLE") // ImageManagementVersionCreateSpec | Image management version object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateIMVersion(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ImageManagementVersionCreateSpec**](ImageManagementVersionCreateSpec.md) | Image management version object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateIMVersions

> []BulkItemResponseInfo CreateIMVersions(ctx).Body(body).Execute()

Creates one or more image management versions. Each of the index of result in the response, correspond to the index of the original version.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []openapiclient.ImageManagementVersionCreateSpec{*openapiclient.NewImageManagementVersionCreateSpec("abc16e8f-9ba0-4789-a5dd-6880f32c52df", "v1", "AVAILABLE")} // []ImageManagementVersionCreateSpec | List of Image management version object to be created in bulk.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.CreateIMVersions(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateIMVersions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateIMVersions`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.CreateIMVersions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIMVersionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**[]ImageManagementVersionCreateSpec**](ImageManagementVersionCreateSpec.md) | List of Image management version object to be created in bulk. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateJWTAuthenticator

> CreateJWTAuthenticator(ctx).Body(body).Execute()

Creates a JWT authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewJWTAuthenticatorCreateSpec("portal", "Jwt Authenticator") // JWTAuthenticatorCreateSpec | JWT authenticator object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateJWTAuthenticator(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateJWTAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateJWTAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**JWTAuthenticatorCreateSpec**](JWTAuthenticatorCreateSpec.md) | JWT authenticator object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateLocalAccessGroup

> CreateLocalAccessGroup(ctx).Body(body).Execute()

Creates local access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewLocalAccessGroupCreateSpec("Sales") // LocalAccessGroupCreateSpec | Local access group object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateLocalAccessGroup(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateLocalAccessGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateLocalAccessGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**LocalAccessGroupCreateSpec**](LocalAccessGroupCreateSpec.md) | Local access group object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreatePermissions

> []BulkItemResponseInfo CreatePermissions(ctx).Body(body).Execute()

Creates permissions in bulk.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []openapiclient.PermissionCreateSpec{*openapiclient.NewPermissionCreateSpec("S-1-5-21-1042673909-920613684-1833544874-512", "9b50589d-818f-40c2-9ced-161d0f1d67dd")} // []PermissionCreateSpec | List of Permission objects to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.CreatePermissions(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreatePermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePermissions`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.CreatePermissions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**[]PermissionCreateSpec**](PermissionCreateSpec.md) | List of Permission objects to be created. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateRADIUSAuthenticator

> CreateRADIUSAuthenticator(ctx).Body(body).Execute()

Creates a RADIUS Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewRADIUSAuthenticatorCreateSpec("radius-auth-lablel", []openapiclient.RADIUSServerCreateSpec{*openapiclient.NewRADIUSServerCreateSpec(int32(1813), int32(1812), "PAP", "10.109.69.213", int32(5), int32(4), []string{"SharedSecret_example"})}) // RADIUSAuthenticatorCreateSpec | RADIUS authenticator object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateRADIUSAuthenticator(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateRADIUSAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRADIUSAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**RADIUSAuthenticatorCreateSpec**](RADIUSAuthenticatorCreateSpec.md) | RADIUS authenticator object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateRole

> CreateRole(ctx).Body(body).Execute()

Creates a role.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewRoleCreateSpec("Custom", []string{"Privileges_example"}) // RoleCreateSpec | Role object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateRole(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateRole``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRoleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**RoleCreateSpec**](RoleCreateSpec.md) | Role object to be created. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateSAMLAuthenticator

> CreateSAMLAuthenticator(ctx).Spec(spec).Execute()

Creates a SAML authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	spec := *openapiclient.NewSAMLAuthenticatorCreateSpec("DYNAMIC", "vidm.example.com") // SAMLAuthenticatorCreateSpec | SAML Authenticator specification

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateSAMLAuthenticator(context.Background()).Spec(spec).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateSAMLAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSAMLAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **spec** | [**SAMLAuthenticatorCreateSpec**](SAMLAuthenticatorCreateSpec.md) | SAML Authenticator specification | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateUnauthenticatedAccessUser

> CreateUnauthenticatedAccessUser(ctx).Spec(spec).Execute()

Creates a specified unauthenticated access user in the environment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	spec := *openapiclient.NewUnauthenticatedAccessUserCreateSpec("S-1-5-21-1111111111-2222222222-3333333333-500") // UnauthenticatedAccessUserCreateSpec | Unauthenticated access user specification

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.CreateUnauthenticatedAccessUser(context.Background()).Spec(spec).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.CreateUnauthenticatedAccessUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateUnauthenticatedAccessUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **spec** | [**UnauthenticatedAccessUserCreateSpec**](UnauthenticatedAccessUserCreateSpec.md) | Unauthenticated access user specification | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppVolumesManager

> DeleteAppVolumesManager(ctx, id).Execute()

deletes the given app volumes manager



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteAppVolumesManager(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteAppVolumesManager``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAppVolumesManagerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteFederationAccessGroup

> DeleteFederationAccessGroup(ctx, id).Execute()

Deletes a federation access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteFederationAccessGroup(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteFederationAccessGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteFederationAccessGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteGSSAPIAuthenticator

> DeleteGSSAPIAuthenticator(ctx, id).Forced(forced).Execute()

Deletes a GSSAPI Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	forced := false // bool | Indicates to delete GSSAPIAuthenticator forcibly If passed as \"true\", then GSSAPIAuthenticator is deleted forcibly, even if it is being used by any of the connection server If passed as  \"false\" then if GSSAPIAuthenticator is used by any of the connection server error message will be rendered (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteGSSAPIAuthenticator(context.Background(), id).Forced(forced).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteGSSAPIAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteGSSAPIAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **forced** | **bool** | Indicates to delete GSSAPIAuthenticator forcibly If passed as \&quot;true\&quot;, then GSSAPIAuthenticator is deleted forcibly, even if it is being used by any of the connection server If passed as  \&quot;false\&quot; then if GSSAPIAuthenticator is used by any of the connection server error message will be rendered | [default to false]

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteICDomainAccount

> DeleteICDomainAccount(ctx, id).Execute()

Deletes instant clone domain account.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteICDomainAccount(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteICDomainAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteICDomainAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteIMAsset

> DeleteIMAsset(ctx, id).Execute()

Deletes image management asset.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteIMAsset(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteIMAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteIMAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteIMStream

> DeleteIMStream(ctx, id).Execute()

Deletes image management stream.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteIMStream(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteIMStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteIMStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteIMTag

> DeleteIMTag(ctx, id).Execute()

Deletes image management tag.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteIMTag(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteIMTag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteIMTagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteIMVersion

> DeleteIMVersion(ctx, id).Execute()

Deletes image management version.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteIMVersion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteIMVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteIMVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteJWTAuthenticator

> DeleteJWTAuthenticator(ctx, id).Execute()

Deletes the given JWT authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteJWTAuthenticator(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteJWTAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteJWTAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteLocalAccessGroup

> DeleteLocalAccessGroup(ctx, id).Execute()

Deletes a local access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteLocalAccessGroup(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteLocalAccessGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteLocalAccessGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePermissions

> []BulkItemResponseInfo DeletePermissions(ctx).Body(body).Execute()

Deletes permissions in bulk.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []string{"Property_example"} // []string | List of Permission ids to be deleted.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.DeletePermissions(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeletePermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePermissions`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.DeletePermissions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeletePermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | List of Permission ids to be deleted. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteRADIUSAuthenticator

> DeleteRADIUSAuthenticator(ctx, id).Execute()

Deletes the given RADIUS Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteRADIUSAuthenticator(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteRADIUSAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteRADIUSAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteRole

> DeleteRole(ctx, id).Execute()

Deletes a role.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteRole(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteRole``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteRoleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteSAMLAuthenticator

> DeleteSAMLAuthenticator(ctx, id).Execute()

Deletes a SAML Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteSAMLAuthenticator(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteSAMLAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteSAMLAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteUnauthenticatedAccessUser

> DeleteUnauthenticatedAccessUser(ctx, id).Execute()

Deletes a specified unauthenticated access user in the environment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | ID of the unauthenticated access user

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.DeleteUnauthenticatedAccessUser(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DeleteUnauthenticatedAccessUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the unauthenticated access user | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUnauthenticatedAccessUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisableConnectionServers

> []BulkItemResponseInfo DisableConnectionServers(ctx).Body(body).Execute()

Disables the given list of connection server ids.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []string{"Property_example"} // []string | List of connection server ids to be disabled.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.DisableConnectionServers(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.DisableConnectionServers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisableConnectionServers`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.DisableConnectionServers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDisableConnectionServersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | List of connection server ids to be disabled. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EnableConnectionServers

> []BulkItemResponseInfo EnableConnectionServers(ctx).Body(body).Execute()

Enables the given list of connection server ids.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := []string{"Property_example"} // []string | List of connection server ids to be enabled.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.EnableConnectionServers(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.EnableConnectionServers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EnableConnectionServers`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.EnableConnectionServers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEnableConnectionServersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | List of connection server ids to be enabled. | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateCSR

> CsrGenerateResponseInfo GenerateCSR(ctx).Body(body).Execute()

Generate Certificate Signing Request(CSR).



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewCsrSpec("MACHINE", "CN=Horizon-server.example.local, OU=VMware Horizon View default certificate, O=VMware, S=California, C=CALIFORNIA") // CsrSpec | CSR Spec.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GenerateCSR(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GenerateCSR``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateCSR`: CsrGenerateResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GenerateCSR`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateCSRRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CsrSpec**](CsrSpec.md) | CSR Spec. | 

### Return type

[**CsrGenerateResponseInfo**](CsrGenerateResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAdminUsersOrGroupsPermissions

> AdminUserOrGroupPermissionsInfo GetAdminUsersOrGroupsPermissions(ctx).Execute()

Gets permission information for logged in admin user or group.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetAdminUsersOrGroupsPermissions(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetAdminUsersOrGroupsPermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAdminUsersOrGroupsPermissions`: AdminUserOrGroupPermissionsInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetAdminUsersOrGroupsPermissions`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAdminUsersOrGroupsPermissionsRequest struct via the builder pattern


### Return type

[**AdminUserOrGroupPermissionsInfo**](AdminUserOrGroupPermissionsInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppVolumesManager

> AppVolumesManagerInfo GetAppVolumesManager(ctx, id).Execute()

Retrieves information about an app volumes manager.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetAppVolumesManager(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetAppVolumesManager``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppVolumesManager`: AppVolumesManagerInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetAppVolumesManager`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppVolumesManagerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppVolumesManagerInfo**](AppVolumesManagerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCEIPInfo

> CEIPInfo GetCEIPInfo(ctx).Execute()

Get the CEIP Information.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetCEIPInfo(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetCEIPInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCEIPInfo`: CEIPInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetCEIPInfo`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCEIPInfoRequest struct via the builder pattern


### Return type

[**CEIPInfo**](CEIPInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConnectionServer

> ConnectionServerInfo GetConnectionServer(ctx, id).Execute()

Retrieves information about a connection server.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetConnectionServer(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetConnectionServer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnectionServer`: ConnectionServerInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetConnectionServer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionServerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConnectionServerInfo**](ConnectionServerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConnectionServerV2

> ConnectionServerInfoV2 GetConnectionServerV2(ctx, id).Execute()

Retrieves information about a connection server.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetConnectionServerV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetConnectionServerV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnectionServerV2`: ConnectionServerInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetConnectionServerV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionServerV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConnectionServerInfoV2**](ConnectionServerInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEnrollmentServer

> TrueSSOEnrollmentServerInfo GetEnrollmentServer(ctx, id).Execute()

Retrieves information about a paired TrueSSO Enrollment Server.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetEnrollmentServer(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetEnrollmentServer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEnrollmentServer`: TrueSSOEnrollmentServerInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetEnrollmentServer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEnrollmentServerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TrueSSOEnrollmentServerInfo**](TrueSSOEnrollmentServerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEnvironment

> EnvironmentInfo GetEnvironment(ctx).Execute()

Retrieves the environment settings.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetEnvironment(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetEnvironment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEnvironment`: EnvironmentInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetEnvironment`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetEnvironmentRequest struct via the builder pattern


### Return type

[**EnvironmentInfo**](EnvironmentInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEnvironmentV2

> EnvironmentInfoV2 GetEnvironmentV2(ctx).Execute()

Retrieves the environment settings.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetEnvironmentV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetEnvironmentV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEnvironmentV2`: EnvironmentInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetEnvironmentV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetEnvironmentV2Request struct via the builder pattern


### Return type

[**EnvironmentInfoV2**](EnvironmentInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEventDatabase

> EventDatabaseInfo GetEventDatabase(ctx).Execute()

Returns information about event database configured.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetEventDatabase(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetEventDatabase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEventDatabase`: EventDatabaseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetEventDatabase`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetEventDatabaseRequest struct via the builder pattern


### Return type

[**EventDatabaseInfo**](EventDatabaseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFeatureSettings

> FeatureSettings GetFeatureSettings(ctx).Execute()

Retrieves the feature settings.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetFeatureSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetFeatureSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFeatureSettings`: FeatureSettings
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetFeatureSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetFeatureSettingsRequest struct via the builder pattern


### Return type

[**FeatureSettings**](FeatureSettings.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFederationAccessGroup

> FederationAccessGroupInfo GetFederationAccessGroup(ctx, id).Execute()

Retrieves a federation access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetFederationAccessGroup(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetFederationAccessGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFederationAccessGroup`: FederationAccessGroupInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetFederationAccessGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFederationAccessGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FederationAccessGroupInfo**](FederationAccessGroupInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFederationAccessGroupV2

> FederationAccessGroupInfoV2 GetFederationAccessGroupV2(ctx, id).Execute()

Retrieves a federation access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetFederationAccessGroupV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetFederationAccessGroupV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFederationAccessGroupV2`: FederationAccessGroupInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetFederationAccessGroupV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFederationAccessGroupV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FederationAccessGroupInfoV2**](FederationAccessGroupInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGSSAPIAuthenticator

> GSSAPIAuthenticatorInfo GetGSSAPIAuthenticator(ctx, id).Execute()

Retrieves information about a GSSAPI Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetGSSAPIAuthenticator(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetGSSAPIAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGSSAPIAuthenticator`: GSSAPIAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetGSSAPIAuthenticator`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGSSAPIAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GSSAPIAuthenticatorInfo**](GSSAPIAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGateway

> GatewayInfo GetGateway(ctx, id).Execute()

Retrieves information about a registered gateway.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetGateway(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetGateway``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGateway`: GatewayInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetGateway`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGatewayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GatewayInfo**](GatewayInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGeneralSettings

> GeneralSettings GetGeneralSettings(ctx).Execute()

Retrieves the general settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetGeneralSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetGeneralSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGeneralSettings`: GeneralSettings
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetGeneralSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetGeneralSettingsRequest struct via the builder pattern


### Return type

[**GeneralSettings**](GeneralSettings.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGeneralSettingsV2

> GeneralSettingsV2 GetGeneralSettingsV2(ctx).Execute()

Retrieves the general settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetGeneralSettingsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetGeneralSettingsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGeneralSettingsV2`: GeneralSettingsV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetGeneralSettingsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetGeneralSettingsV2Request struct via the builder pattern


### Return type

[**GeneralSettingsV2**](GeneralSettingsV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGeneralSettingsV3

> GeneralSettingsV3 GetGeneralSettingsV3(ctx).Execute()

Retrieves the general settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetGeneralSettingsV3(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetGeneralSettingsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGeneralSettingsV3`: GeneralSettingsV3
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetGeneralSettingsV3`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetGeneralSettingsV3Request struct via the builder pattern


### Return type

[**GeneralSettingsV3**](GeneralSettingsV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetICDomainAccount

> InstantCloneDomainAccountInfo GetICDomainAccount(ctx, id).Execute()

Gets instant clone domain account.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetICDomainAccount(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetICDomainAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetICDomainAccount`: InstantCloneDomainAccountInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetICDomainAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetICDomainAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InstantCloneDomainAccountInfo**](InstantCloneDomainAccountInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIMAsset

> ImageManagementAssetInfo GetIMAsset(ctx, id).Execute()

Gets image management asset.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetIMAsset(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetIMAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIMAsset`: ImageManagementAssetInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetIMAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIMAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageManagementAssetInfo**](ImageManagementAssetInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIMStream

> ImageManagementStreamInfo GetIMStream(ctx, id).Execute()

Gets image management stream.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetIMStream(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetIMStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIMStream`: ImageManagementStreamInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetIMStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIMStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageManagementStreamInfo**](ImageManagementStreamInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIMTag

> ImageManagementTagInfo GetIMTag(ctx, id).Execute()

Gets image management tag.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetIMTag(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetIMTag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIMTag`: ImageManagementTagInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetIMTag`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIMTagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageManagementTagInfo**](ImageManagementTagInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIMVersion

> ImageManagementVersionInfo GetIMVersion(ctx, id).Execute()

Gets image management version.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetIMVersion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetIMVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIMVersion`: ImageManagementVersionInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetIMVersion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIMVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ImageManagementVersionInfo**](ImageManagementVersionInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJWTAuthenticator

> JWTAuthenticatorInfo GetJWTAuthenticator(ctx, id).Execute()

Retrieves information about the given JWT authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetJWTAuthenticator(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetJWTAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJWTAuthenticator`: JWTAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetJWTAuthenticator`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJWTAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JWTAuthenticatorInfo**](JWTAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLocalAccessGroup

> LocalAccessGroupInfo GetLocalAccessGroup(ctx, id).Execute()

Retrieves a local access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetLocalAccessGroup(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetLocalAccessGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLocalAccessGroup`: LocalAccessGroupInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetLocalAccessGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLocalAccessGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LocalAccessGroupInfo**](LocalAccessGroupInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLocalAccessGroupV2

> LocalAccessGroupInfoV2 GetLocalAccessGroupV2(ctx, id).Execute()

Retrieves a local access group.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetLocalAccessGroupV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetLocalAccessGroupV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLocalAccessGroupV2`: LocalAccessGroupInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetLocalAccessGroupV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLocalAccessGroupV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LocalAccessGroupInfoV2**](LocalAccessGroupInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPermission

> PermissionInfo GetPermission(ctx, id).Execute()

Retrieves a permission.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetPermission(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetPermission``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPermission`: PermissionInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetPermission`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPermissionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PermissionInfo**](PermissionInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPreLogonSettings

> PreLogonSettingsInfo GetPreLogonSettings(ctx).Execute()

Gets the pre logon settings.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetPreLogonSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetPreLogonSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPreLogonSettings`: PreLogonSettingsInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetPreLogonSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetPreLogonSettingsRequest struct via the builder pattern


### Return type

[**PreLogonSettingsInfo**](PreLogonSettingsInfo.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPreferences

> AdminUserOrGroupPreferencesInfo GetPreferences(ctx).Execute()

Gets Horizon Console preferences for the logged in administrator.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetPreferences(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetPreferences``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPreferences`: AdminUserOrGroupPreferencesInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetPreferences`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetPreferencesRequest struct via the builder pattern


### Return type

[**AdminUserOrGroupPreferencesInfo**](AdminUserOrGroupPreferencesInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRADIUSAuthenticator

> RADIUSAuthenticatorInfo GetRADIUSAuthenticator(ctx, id).Execute()

Retrieves information about a RADIUS Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetRADIUSAuthenticator(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetRADIUSAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRADIUSAuthenticator`: RADIUSAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetRADIUSAuthenticator`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRADIUSAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RADIUSAuthenticatorInfo**](RADIUSAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRole

> RoleInfo GetRole(ctx, id).Execute()

Retrieves a role.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetRole(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetRole``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRole`: RoleInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetRole`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRoleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RoleInfo**](RoleInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSAMLAuthenticator

> SAMLAuthenticatorInfo GetSAMLAuthenticator(ctx, id).Execute()

Retrieves information about a SAML authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetSAMLAuthenticator(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetSAMLAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSAMLAuthenticator`: SAMLAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetSAMLAuthenticator`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSAMLAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SAMLAuthenticatorInfo**](SAMLAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSecurityConfigurationInfo

> SecurityConfigInfo GetSecurityConfigurationInfo(ctx).Execute()

Retrieves the security configuration of connection server and secure gateway



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetSecurityConfigurationInfo(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetSecurityConfigurationInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSecurityConfigurationInfo`: SecurityConfigInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetSecurityConfigurationInfo`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSecurityConfigurationInfoRequest struct via the builder pattern


### Return type

[**SecurityConfigInfo**](SecurityConfigInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSecuritySettings

> SecuritySettings GetSecuritySettings(ctx).Execute()

Retrieves the security settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetSecuritySettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetSecuritySettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSecuritySettings`: SecuritySettings
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetSecuritySettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSecuritySettingsRequest struct via the builder pattern


### Return type

[**SecuritySettings**](SecuritySettings.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSecuritySettingsV2

> SecuritySettingsV2 GetSecuritySettingsV2(ctx).Execute()

Retrieves the security settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetSecuritySettingsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetSecuritySettingsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSecuritySettingsV2`: SecuritySettingsV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetSecuritySettingsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSecuritySettingsV2Request struct via the builder pattern


### Return type

[**SecuritySettingsV2**](SecuritySettingsV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSettings

> SettingsInfo GetSettings(ctx).Execute()

Retrieves the configuration settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSettings`: SettingsInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSettingsRequest struct via the builder pattern


### Return type

[**SettingsInfo**](SettingsInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSettingsV2

> SettingsInfoV2 GetSettingsV2(ctx).Execute()

Retrieves the configuration settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetSettingsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetSettingsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSettingsV2`: SettingsInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetSettingsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSettingsV2Request struct via the builder pattern


### Return type

[**SettingsInfoV2**](SettingsInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSettingsV3

> SettingsInfoV3 GetSettingsV3(ctx).Execute()

Retrieves the configuration settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetSettingsV3(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetSettingsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSettingsV3`: SettingsInfoV3
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetSettingsV3`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSettingsV3Request struct via the builder pattern


### Return type

[**SettingsInfoV3**](SettingsInfoV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUnauthenticatedAccessUser

> UnauthenticatedAccessUserInfo GetUnauthenticatedAccessUser(ctx, id).Execute()

Retrieves a specified unauthenticated access user in the environment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | ID of the unauthenticated access user

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.GetUnauthenticatedAccessUser(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.GetUnauthenticatedAccessUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUnauthenticatedAccessUser`: UnauthenticatedAccessUserInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.GetUnauthenticatedAccessUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the unauthenticated access user | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUnauthenticatedAccessUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UnauthenticatedAccessUserInfo**](UnauthenticatedAccessUserInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportCertificate

> ImportCertificate(ctx).Body(body).Execute()

Import the SSL certificate to connection server's personal certificate store.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewCertificateSpec(string(123), "MACHINE", "pem") // CertificateSpec | Certificate Spec.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.ImportCertificate(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ImportCertificate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiImportCertificateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CertificateSpec**](CertificateSpec.md) | Certificate Spec. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAppVolumesManagers

> []AppVolumesManagerInfo ListAppVolumesManagers(ctx).Execute()

Lists the configured app volumes managers.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListAppVolumesManagers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListAppVolumesManagers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAppVolumesManagers`: []AppVolumesManagerInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListAppVolumesManagers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListAppVolumesManagersRequest struct via the builder pattern


### Return type

[**[]AppVolumesManagerInfo**](AppVolumesManagerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCertificateInfos

> []CertificateInfo ListCertificateInfos(ctx).Execute()

Retrieves the certificate details.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListCertificateInfos(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListCertificateInfos``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCertificateInfos`: []CertificateInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListCertificateInfos`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListCertificateInfosRequest struct via the builder pattern


### Return type

[**[]CertificateInfo**](CertificateInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListConnectionServers

> []ConnectionServerInfo ListConnectionServers(ctx).Execute()

Lists the connection servers.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListConnectionServers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListConnectionServers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListConnectionServers`: []ConnectionServerInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListConnectionServers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListConnectionServersRequest struct via the builder pattern


### Return type

[**[]ConnectionServerInfo**](ConnectionServerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListConnectionServersV2

> []ConnectionServerInfoV2 ListConnectionServersV2(ctx).Execute()

Lists the connection servers.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListConnectionServersV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListConnectionServersV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListConnectionServersV2`: []ConnectionServerInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListConnectionServersV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListConnectionServersV2Request struct via the builder pattern


### Return type

[**[]ConnectionServerInfoV2**](ConnectionServerInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListEnrollmentServers

> []TrueSSOEnrollmentServerInfo ListEnrollmentServers(ctx).Execute()

Lists the paired TrueSSO Enrollment Servers.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListEnrollmentServers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListEnrollmentServers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListEnrollmentServers`: []TrueSSOEnrollmentServerInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListEnrollmentServers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListEnrollmentServersRequest struct via the builder pattern


### Return type

[**[]TrueSSOEnrollmentServerInfo**](TrueSSOEnrollmentServerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListFederationAccessGroups

> []FederationAccessGroupInfo ListFederationAccessGroups(ctx).Execute()

Lists all federation access groups.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListFederationAccessGroups(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListFederationAccessGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListFederationAccessGroups`: []FederationAccessGroupInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListFederationAccessGroups`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListFederationAccessGroupsRequest struct via the builder pattern


### Return type

[**[]FederationAccessGroupInfo**](FederationAccessGroupInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListFederationAccessGroupsV2

> []FederationAccessGroupInfoV2 ListFederationAccessGroupsV2(ctx).Execute()

Lists all federation access groups.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListFederationAccessGroupsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListFederationAccessGroupsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListFederationAccessGroupsV2`: []FederationAccessGroupInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListFederationAccessGroupsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListFederationAccessGroupsV2Request struct via the builder pattern


### Return type

[**[]FederationAccessGroupInfoV2**](FederationAccessGroupInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGSSAPIAuthenticators

> []GSSAPIAuthenticatorInfo ListGSSAPIAuthenticators(ctx).Execute()

Lists the configured GSSAPI Authenticators.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListGSSAPIAuthenticators(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListGSSAPIAuthenticators``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGSSAPIAuthenticators`: []GSSAPIAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListGSSAPIAuthenticators`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListGSSAPIAuthenticatorsRequest struct via the builder pattern


### Return type

[**[]GSSAPIAuthenticatorInfo**](GSSAPIAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGateways

> []GatewayInfo ListGateways(ctx).Execute()

Lists the registered gateways.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListGateways(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListGateways``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGateways`: []GatewayInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListGateways`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListGatewaysRequest struct via the builder pattern


### Return type

[**[]GatewayInfo**](GatewayInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListICDomainAccounts

> []InstantCloneDomainAccountInfo ListICDomainAccounts(ctx).Page(page).Size(size).Execute()

Lists instant clone domain accounts of the environment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	page := int32(1) // int32 | page, if passed should be > 0. (optional)
	size := int32(10) // int32 | size, if passed should be > 0. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListICDomainAccounts(context.Background()).Page(page).Size(size).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListICDomainAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListICDomainAccounts`: []InstantCloneDomainAccountInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListICDomainAccounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListICDomainAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | page, if passed should be &gt; 0. | 
 **size** | **int32** | size, if passed should be &gt; 0. | 

### Return type

[**[]InstantCloneDomainAccountInfo**](InstantCloneDomainAccountInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListIMAssets

> []ImageManagementAssetInfo ListIMAssets(ctx).ImVersionId(imVersionId).Execute()

Lists image management assets.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	imVersionId := "imVersionId_example" // string | Image management version ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListIMAssets(context.Background()).ImVersionId(imVersionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListIMAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListIMAssets`: []ImageManagementAssetInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListIMAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListIMAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **imVersionId** | **string** | Image management version ID | 

### Return type

[**[]ImageManagementAssetInfo**](ImageManagementAssetInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListIMStreams

> []ImageManagementStreamInfo ListIMStreams(ctx).Execute()

Lists image management streams.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListIMStreams(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListIMStreams``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListIMStreams`: []ImageManagementStreamInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListIMStreams`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListIMStreamsRequest struct via the builder pattern


### Return type

[**[]ImageManagementStreamInfo**](ImageManagementStreamInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListIMTags

> []ImageManagementTagInfo ListIMTags(ctx).ImStreamId(imStreamId).Execute()

Lists image management tags.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	imStreamId := "imStreamId_example" // string | Image management stream ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListIMTags(context.Background()).ImStreamId(imStreamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListIMTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListIMTags`: []ImageManagementTagInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListIMTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListIMTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **imStreamId** | **string** | Image management stream ID | 

### Return type

[**[]ImageManagementTagInfo**](ImageManagementTagInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListIMVersions

> []ImageManagementVersionInfo ListIMVersions(ctx).ImStreamId(imStreamId).Execute()

Lists image management versions.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	imStreamId := "imStreamId_example" // string | Image management stream ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListIMVersions(context.Background()).ImStreamId(imStreamId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListIMVersions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListIMVersions`: []ImageManagementVersionInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListIMVersions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListIMVersionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **imStreamId** | **string** | Image management stream ID | 

### Return type

[**[]ImageManagementVersionInfo**](ImageManagementVersionInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListJWTAuthenticators

> []JWTAuthenticatorInfo ListJWTAuthenticators(ctx).Execute()

Lists the configured JWT authenticators.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListJWTAuthenticators(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListJWTAuthenticators``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListJWTAuthenticators`: []JWTAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListJWTAuthenticators`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListJWTAuthenticatorsRequest struct via the builder pattern


### Return type

[**[]JWTAuthenticatorInfo**](JWTAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListLicenses

> []LicenseInfo ListLicenses(ctx).Execute()

Lists all licenses.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListLicenses(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListLicenses``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListLicenses`: []LicenseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListLicenses`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListLicensesRequest struct via the builder pattern


### Return type

[**[]LicenseInfo**](LicenseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListLicensesV2

> []LicenseInfoV2 ListLicensesV2(ctx).Execute()

Lists all licenses.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListLicensesV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListLicensesV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListLicensesV2`: []LicenseInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListLicensesV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListLicensesV2Request struct via the builder pattern


### Return type

[**[]LicenseInfoV2**](LicenseInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListLocalAccessGroups

> []LocalAccessGroupInfo ListLocalAccessGroups(ctx).Execute()

Lists all local access groups.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListLocalAccessGroups(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListLocalAccessGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListLocalAccessGroups`: []LocalAccessGroupInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListLocalAccessGroups`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListLocalAccessGroupsRequest struct via the builder pattern


### Return type

[**[]LocalAccessGroupInfo**](LocalAccessGroupInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListLocalAccessGroupsV2

> []LocalAccessGroupInfoV2 ListLocalAccessGroupsV2(ctx).Execute()

Lists all local access groups.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListLocalAccessGroupsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListLocalAccessGroupsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListLocalAccessGroupsV2`: []LocalAccessGroupInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListLocalAccessGroupsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListLocalAccessGroupsV2Request struct via the builder pattern


### Return type

[**[]LocalAccessGroupInfoV2**](LocalAccessGroupInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPermissions

> []PermissionInfo ListPermissions(ctx).Ids(ids).Execute()

Lists all permissions.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	ids := []string{"Inner_example"} // []string | Permission IDs (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListPermissions(context.Background()).Ids(ids).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListPermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPermissions`: []PermissionInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListPermissions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]string** | Permission IDs | 

### Return type

[**[]PermissionInfo**](PermissionInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRADIUSAuthenticators

> []RADIUSAuthenticatorInfo ListRADIUSAuthenticators(ctx).Execute()

Lists the configured RADIUS Authenticators.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListRADIUSAuthenticators(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListRADIUSAuthenticators``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRADIUSAuthenticators`: []RADIUSAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListRADIUSAuthenticators`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListRADIUSAuthenticatorsRequest struct via the builder pattern


### Return type

[**[]RADIUSAuthenticatorInfo**](RADIUSAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRCXServers

> []RCXServerInfo ListRCXServers(ctx).Execute()

Lists RCX servers of the cluster.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListRCXServers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListRCXServers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRCXServers`: []RCXServerInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListRCXServers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListRCXServersRequest struct via the builder pattern


### Return type

[**[]RCXServerInfo**](RCXServerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRoles

> []RoleInfo ListRoles(ctx).Execute()

Lists all roles.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListRoles(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRoles`: []RoleInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListRoles`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListRolesRequest struct via the builder pattern


### Return type

[**[]RoleInfo**](RoleInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSAMLAuthenticators

> []SAMLAuthenticatorInfo ListSAMLAuthenticators(ctx).Execute()

Lists the configured SAML authenticators.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListSAMLAuthenticators(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListSAMLAuthenticators``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSAMLAuthenticators`: []SAMLAuthenticatorInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListSAMLAuthenticators`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListSAMLAuthenticatorsRequest struct via the builder pattern


### Return type

[**[]SAMLAuthenticatorInfo**](SAMLAuthenticatorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSelectablePrivileges

> []PrivilegeInfo ListSelectablePrivileges(ctx).Execute()

Lists all selectable privileges.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListSelectablePrivileges(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListSelectablePrivileges``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSelectablePrivileges`: []PrivilegeInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListSelectablePrivileges`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListSelectablePrivilegesRequest struct via the builder pattern


### Return type

[**[]PrivilegeInfo**](PrivilegeInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListUnauthenticatedAccessUsers

> []UnauthenticatedAccessUserInfo ListUnauthenticatedAccessUsers(ctx).Execute()

Lists unauthenticated access users in the environment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListUnauthenticatedAccessUsers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListUnauthenticatedAccessUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListUnauthenticatedAccessUsers`: []UnauthenticatedAccessUserInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListUnauthenticatedAccessUsers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListUnauthenticatedAccessUsersRequest struct via the builder pattern


### Return type

[**[]UnauthenticatedAccessUserInfo**](UnauthenticatedAccessUserInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListUsersOrGroupsLocalSummary

> []UserOrGroupLocalSummaryInfo ListUsersOrGroupsLocalSummary(ctx).Filter(filter).Page(page).Size(size).Execute()

Lists local summary info of users or groups.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	filter := "{"type":"And", "filters":[{"type":"Equals", "name":"<>", "value":"<>"}] }" // string | filter expression built using fields with <b>'supported filters'</b> as described in output <b>model</b> schema of this API. (optional)
	page := int32(1) // int32 | page, if passed should be > 0. (optional)
	size := int32(10) // int32 | size, if passed should be > 0. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListUsersOrGroupsLocalSummary(context.Background()).Filter(filter).Page(page).Size(size).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListUsersOrGroupsLocalSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListUsersOrGroupsLocalSummary`: []UserOrGroupLocalSummaryInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListUsersOrGroupsLocalSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListUsersOrGroupsLocalSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** | filter expression built using fields with &lt;b&gt;&#39;supported filters&#39;&lt;/b&gt; as described in output &lt;b&gt;model&lt;/b&gt; schema of this API. | 
 **page** | **int32** | page, if passed should be &gt; 0. | 
 **size** | **int32** | size, if passed should be &gt; 0. | 

### Return type

[**[]UserOrGroupLocalSummaryInfo**](UserOrGroupLocalSummaryInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVCInfo

> []VirtualCenterInfo ListVCInfo(ctx).Execute()

Lists Virtual Centers configured in the environment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListVCInfo(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListVCInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVCInfo`: []VirtualCenterInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListVCInfo`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListVCInfoRequest struct via the builder pattern


### Return type

[**[]VirtualCenterInfo**](VirtualCenterInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVCInfoV2

> []VirtualCenterInfoV2 ListVCInfoV2(ctx).Execute()

Lists Virtual Centers configured in the environment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ListVCInfoV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ListVCInfoV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVCInfoV2`: []VirtualCenterInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ListVCInfoV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListVCInfoV2Request struct via the builder pattern


### Return type

[**[]VirtualCenterInfoV2**](VirtualCenterInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkDatastoresForArchival

> []BulkItemResponseInfo MarkDatastoresForArchival(ctx, id).HostOrClusterId(hostOrClusterId).Body(body).Execute()

Sets archival datastore paths for the vCenter.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	hostOrClusterId := "hostOrClusterId_example" // string | Host or Cluster ID
	id := "id_example" // string | id
	body := []string{"Property_example"} // []string | Set of datastore ids where archived vms will be saved

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.MarkDatastoresForArchival(context.Background(), id).HostOrClusterId(hostOrClusterId).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.MarkDatastoresForArchival``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkDatastoresForArchival`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.MarkDatastoresForArchival`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiMarkDatastoresForArchivalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hostOrClusterId** | **string** | Host or Cluster ID | 

 **body** | **[]string** | Set of datastore ids where archived vms will be saved | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PushCertificates

> PushCertificates(ctx, id).Execute()

Push cluster certificates to App Volumes Manager



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | App volumes manager ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.PushCertificates(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.PushCertificates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | App volumes manager ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPushCertificatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegisterRCXClient

> RegisterRCXClient(ctx).Body(body).Execute()

Registers the RCX client



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewRCXClientRegisterSpec("example.com", []openapiclient.CertificateThumbprint{*openapiclient.NewCertificateThumbprint("8f:92:9d:3b:a7:85:55:88:60:cd:e1:c8:1e:70:9a:8b:37:6d:a6:e6", "SHA_1")}) // RCXClientRegisterSpec | RCX client object to be registered.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.RegisterRCXClient(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.RegisterRCXClient``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterRCXClientRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**RCXClientRegisterSpec**](RCXClientRegisterSpec.md) | RCX client object to be registered. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetLicenseMode

> SetLicenseMode(ctx).Body(body).Execute()

Set the License Mode



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewLicenseModeSpec("SUBSCRIPTION") // LicenseModeSpec | The specification to set the license mode.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.SetLicenseMode(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.SetLicenseMode``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetLicenseModeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**LicenseModeSpec**](LicenseModeSpec.md) | The specification to set the license mode. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnassignFarms

> []BulkItemResponseInfo UnassignFarms(ctx).FarmIds(farmIds).Execute()

Unassign Farms to App Volumes Manager



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	farmIds := []string{"Property_example"} // []string | List of farm Ids to be unassigned with App Volumes manager

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.UnassignFarms(context.Background()).FarmIds(farmIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UnassignFarms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnassignFarms`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.UnassignFarms`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUnassignFarmsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **farmIds** | **[]string** | List of farm Ids to be unassigned with App Volumes manager | 

### Return type

[**[]BulkItemResponseInfo**](BulkItemResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnregisterRCXClient

> UnregisterRCXClient(ctx, id).Execute()

Unregisters the given RCX Client



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UnregisterRCXClient(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UnregisterRCXClient``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnregisterRCXClientRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppVolumesManager

> UpdateAppVolumesManager(ctx, id).Body(body).Execute()

Updates the given app volumes manager.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewAppVolumesManagerUpdateSpec([]string{"Password_example"}, "avm.example.com", "administrator") // AppVolumesManagerUpdateSpec | App volumes manager object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateAppVolumesManager(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateAppVolumesManager``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppVolumesManagerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**AppVolumesManagerUpdateSpec**](AppVolumesManagerUpdateSpec.md) | App volumes manager object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateConnectionServer

> UpdateConnectionServer(ctx, id).Body(body).Execute()

Updates the settings of the given Connection Server.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewConnectionServerUpdateSpec() // ConnectionServerUpdateSpec | Connection Server object whose settings need to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateConnectionServer(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateConnectionServer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateConnectionServerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ConnectionServerUpdateSpec**](ConnectionServerUpdateSpec.md) | Connection Server object whose settings need to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateConnectionServerV2

> UpdateConnectionServerV2(ctx, id).Body(body).Execute()

Updates the settings of the given Connection Server.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewConnectionServerUpdateSpecV2(false, true, false, true, *openapiclient.NewConnectionServerGSSAPISpec(false), false, *openapiclient.NewConnectionServerRADIUSSpec(false), *openapiclient.NewConnectionServerRSASecureIdSpec(false), *openapiclient.NewConnectionServerSAMLSpec("DISABLED"), "OFF", "OPTIONAL", *openapiclient.NewConnectionServerUnauthenticatedAccessSpec(false)) // ConnectionServerUpdateSpecV2 | Connection Server object whose settings need to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateConnectionServerV2(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateConnectionServerV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateConnectionServerV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ConnectionServerUpdateSpecV2**](ConnectionServerUpdateSpecV2.md) | Connection Server object whose settings need to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateEventDatabase

> UpdateEventDatabase(ctx).Body(body).Execute()

Updates event database configuration.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewEventDatabaseUpdateSpec("eventdb", []string{"Password_example"}, int32(1443), "eventdb.horizon.com", "SQL_SERVER", "administrator") // EventDatabaseUpdateSpec | Event database configuration to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateEventDatabase(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateEventDatabase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateEventDatabaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**EventDatabaseUpdateSpec**](EventDatabaseUpdateSpec.md) | Event database configuration to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateFeatureSettings

> UpdateFeatureSettings(ctx).Body(body).Execute()

Updates the feature settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewFeatureSettingsUpdateSpec() // FeatureSettingsUpdateSpec | Feature settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateFeatureSettings(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateFeatureSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateFeatureSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**FeatureSettingsUpdateSpec**](FeatureSettingsUpdateSpec.md) | Feature settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGSSAPIAuthenticator

> UpdateGSSAPIAuthenticator(ctx, id).Body(body).Execute()

Updates a GSSAPI Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewGSSAPIAuthenticatorUpdateSpec(true, true, true, true, "ENABLED") // GSSAPIAuthenticatorUpdateSpec | GSSAPIAuthenticator whose settings need to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateGSSAPIAuthenticator(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateGSSAPIAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGSSAPIAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**GSSAPIAuthenticatorUpdateSpec**](GSSAPIAuthenticatorUpdateSpec.md) | GSSAPIAuthenticator whose settings need to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGeneralSettings

> UpdateGeneralSettings(ctx).Body(body).Execute()

Updates the general settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewGeneralSettingsUpdateSpec("ENABLED", "NEVER", "TIMEOUT_AFTER", int32(300), "DISABLED_AFTER", false, false) // GeneralSettingsUpdateSpec | General settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateGeneralSettings(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateGeneralSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGeneralSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**GeneralSettingsUpdateSpec**](GeneralSettingsUpdateSpec.md) | General settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGeneralSettingsV2

> UpdateGeneralSettingsV2(ctx).Body(body).Execute()

Updates the general settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewGeneralSettingsUpdateSpecV2("ENABLED", "NEVER", "TIMEOUT_AFTER", int32(300), "DISABLED_AFTER", false, false) // GeneralSettingsUpdateSpecV2 | General settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateGeneralSettingsV2(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateGeneralSettingsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGeneralSettingsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**GeneralSettingsUpdateSpecV2**](GeneralSettingsUpdateSpecV2.md) | General settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGeneralSettingsV3

> UpdateGeneralSettingsV3(ctx).Body(body).Execute()

Updates the general settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewGeneralSettingsUpdateSpecV3("ENABLED", "NEVER", "TIMEOUT_AFTER", int32(300), false, "DISABLED_AFTER", false, false) // GeneralSettingsUpdateSpecV3 | General settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateGeneralSettingsV3(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateGeneralSettingsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGeneralSettingsV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**GeneralSettingsUpdateSpecV3**](GeneralSettingsUpdateSpecV3.md) | General settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateICDomainAccount

> UpdateICDomainAccount(ctx, id).Body(body).Execute()

Updates instant clone domain account.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewInstantCloneDomainAccountUpdateSpec([]string{"Password_example"}) // InstantCloneDomainAccountUpdateSpec | Instant clone domain account object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateICDomainAccount(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateICDomainAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateICDomainAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**InstantCloneDomainAccountUpdateSpec**](InstantCloneDomainAccountUpdateSpec.md) | Instant clone domain account object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateIMAsset

> UpdateIMAsset(ctx, id).Body(body).Execute()

Updates image management asset.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewImageManagementAssetUpdateSpec("INSTANT_CLONE", "RDSH_APPS", "AVAILABLE") // ImageManagementAssetUpdateSpec | Image management asset object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateIMAsset(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateIMAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateIMAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ImageManagementAssetUpdateSpec**](ImageManagementAssetUpdateSpec.md) | Image management asset object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateIMStream

> UpdateIMStream(ctx, id).Body(body).Execute()

Updates image management stream.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewImageManagementStreamUpdateSpec("Win10", "WINDOWS_10", "MARKET_PLACE", "AVAILABLE") // ImageManagementStreamUpdateSpec | Image management stream object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateIMStream(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateIMStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateIMStreamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ImageManagementStreamUpdateSpec**](ImageManagementStreamUpdateSpec.md) | Image management stream object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateIMTag

> UpdateIMTag(ctx, id).Body(body).Execute()

Updates image management tag.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewImageManagementTagUpdateSpec("7e85b3a5-e7d0-4ad6-a1e3-37168dd1ed62", "PROD") // ImageManagementTagUpdateSpec | Image management tag object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateIMTag(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateIMTag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateIMTagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ImageManagementTagUpdateSpec**](ImageManagementTagUpdateSpec.md) | Image management tag object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateIMVersion

> UpdateIMVersion(ctx, id).Body(body).Execute()

Updates image management version.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewImageManagementVersionUpdateSpec("v1", "AVAILABLE") // ImageManagementVersionUpdateSpec | Image management version object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateIMVersion(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateIMVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateIMVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ImageManagementVersionUpdateSpec**](ImageManagementVersionUpdateSpec.md) | Image management version object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateJWTAuthenticator

> UpdateJWTAuthenticator(ctx, id).Body(body).Execute()

Updates the given JWT authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewJWTAuthenticatorUpdateSpec("portal", "Jwt Authenticator") // JWTAuthenticatorUpdateSpec | JWT authenticator object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateJWTAuthenticator(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateJWTAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateJWTAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**JWTAuthenticatorUpdateSpec**](JWTAuthenticatorUpdateSpec.md) | JWT authenticator object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePreferences

> UpdatePreferences(ctx).UpdateSpec(updateSpec).Execute()

Updates the Horizon Console preferences for the logged in administrator.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	updateSpec := *openapiclient.NewAdminUserOrGroupPreferencesUpdateSpec() // AdminUserOrGroupPreferencesUpdateSpec | updateSpec

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdatePreferences(context.Background()).UpdateSpec(updateSpec).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdatePreferences``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePreferencesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateSpec** | [**AdminUserOrGroupPreferencesUpdateSpec**](AdminUserOrGroupPreferencesUpdateSpec.md) | updateSpec | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRADIUSAuthenticator

> UpdateRADIUSAuthenticator(ctx, id).Body(body).Execute()

Updates the given RADIUS Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewRADIUSAuthenticatorUpdateSpec("radius-auth-lablel", []openapiclient.RADIUSServerUpdateSpec{*openapiclient.NewRADIUSServerUpdateSpec(int32(1813), int32(1812), "PAP", "10.109.69.213", int32(5), true, int32(4), []string{"SharedSecret_example"})}) // RADIUSAuthenticatorUpdateSpec | RADIUS authenticator object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateRADIUSAuthenticator(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateRADIUSAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRADIUSAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**RADIUSAuthenticatorUpdateSpec**](RADIUSAuthenticatorUpdateSpec.md) | RADIUS authenticator object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRCXClient

> UpdateRCXClient(ctx, id).Body(body).Execute()

Updates the given RCX client.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewRCXClientUpdateSpec([]openapiclient.CertificateThumbprint{*openapiclient.NewCertificateThumbprint("8f:92:9d:3b:a7:85:55:88:60:cd:e1:c8:1e:70:9a:8b:37:6d:a6:e6", "SHA_1")}) // RCXClientUpdateSpec | RCX client object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateRCXClient(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateRCXClient``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRCXClientRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**RCXClientUpdateSpec**](RCXClientUpdateSpec.md) | RCX client object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRole

> UpdateRole(ctx, id).Body(body).Execute()

Updates a role.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewRoleUpdateSpec([]string{"Privileges_example"}) // RoleUpdateSpec | Role object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateRole(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateRole``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRoleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**RoleUpdateSpec**](RoleUpdateSpec.md) | Role object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSAMLAuthenticator

> UpdateSAMLAuthenticator(ctx, id).Body(body).Execute()

Updates a SAML Authenticator.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | id
	body := *openapiclient.NewSAMLAuthenticatorUpdateSpec("vidm.example.com", "DISABLED") // SAMLAuthenticatorUpdateSpec | SAML Authenticator object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateSAMLAuthenticator(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateSAMLAuthenticator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSAMLAuthenticatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**SAMLAuthenticatorUpdateSpec**](SAMLAuthenticatorUpdateSpec.md) | SAML Authenticator object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSecuritySettings

> UpdateSecuritySettings(ctx).Body(body).Execute()

Updates the security settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewSecuritySettingsUpdateSpec("ENABLED") // SecuritySettingsUpdateSpec | Security settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateSecuritySettings(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateSecuritySettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSecuritySettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SecuritySettingsUpdateSpec**](SecuritySettingsUpdateSpec.md) | Security settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSettings

> UpdateSettings(ctx).Body(body).Execute()

Updates the configuration settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewSettingsUpdateSpec() // SettingsUpdateSpec | Configuration settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateSettings(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SettingsUpdateSpec**](SettingsUpdateSpec.md) | Configuration settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSettingsV2

> UpdateSettingsV2(ctx).Body(body).Execute()

Updates the configuration settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewSettingsUpdateSpecV2() // SettingsUpdateSpecV2 | Configuration settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateSettingsV2(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateSettingsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSettingsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SettingsUpdateSpecV2**](SettingsUpdateSpecV2.md) | Configuration settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSettingsV3

> UpdateSettingsV3(ctx).Body(body).Execute()

Updates the configuration settings.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewSettingsUpdateSpecV3() // SettingsUpdateSpecV3 | Configuration settings object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ConfigAPI.UpdateSettingsV3(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.UpdateSettingsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSettingsV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SettingsUpdateSpecV3**](SettingsUpdateSpecV3.md) | Configuration settings object to be updated. | 

### Return type

 (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidateSAMLCertificate

> CertificateData ValidateSAMLCertificate(ctx).Body(body).Execute()

Validates SAML Authenticator certificate.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewSAMLAuthenticatorServerSpec() // SAMLAuthenticatorServerSpec | SAML Authenticator Server Spec.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ValidateSAMLCertificate(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ValidateSAMLCertificate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidateSAMLCertificate`: CertificateData
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ValidateSAMLCertificate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiValidateSAMLCertificateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SAMLAuthenticatorServerSpec**](SAMLAuthenticatorServerSpec.md) | SAML Authenticator Server Spec. | 

### Return type

[**CertificateData**](CertificateData.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidateVirtualCenterCertificate

> CertificateData ValidateVirtualCenterCertificate(ctx).Body(body).Execute()

Validates Virtual Center certificate.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := *openapiclient.NewServerSpec() // ServerSpec | Server Spec.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConfigAPI.ValidateVirtualCenterCertificate(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConfigAPI.ValidateVirtualCenterCertificate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidateVirtualCenterCertificate`: CertificateData
	fmt.Fprintf(os.Stdout, "Response from `ConfigAPI.ValidateVirtualCenterCertificate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiValidateVirtualCenterCertificateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ServerSpec**](ServerSpec.md) | Server Spec. | 

### Return type

[**CertificateData**](CertificateData.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

