# \ExternalAPI

All URIs are relative to *http://localhost/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddAuxiliaryAccounts**](ExternalAPI.md#AddAuxiliaryAccounts) | **Post** /external/v1/ad-domains/{id}/action/add-auxiliary-accounts | Add auxiliary accounts to the untrusted domain
[**AuditEventsExtendedAttributes**](ExternalAPI.md#AuditEventsExtendedAttributes) | **Get** /external/v1/audit-events/extended-attributes | Get extended attributes of audit events
[**Bind**](ExternalAPI.md#Bind) | **Post** /external/v1/ad-domains/action/bind | Bind untrusted domain to the connection server.
[**BulkHoldUserOrGroup**](ExternalAPI.md#BulkHoldUserOrGroup) | **Post** /external/v1/ad-users-or-groups/action/hold | Put users on hold.
[**BulkHoldUserOrGroupV2**](ExternalAPI.md#BulkHoldUserOrGroupV2) | **Post** /external/v2/ad-users-or-groups/action/hold | Put users on hold.
[**BulkReleaseHoldUserOrGroup**](ExternalAPI.md#BulkReleaseHoldUserOrGroup) | **Post** /external/v1/ad-users-or-groups/action/release-hold | Release users from hold.
[**BulkReleaseHoldUserOrGroupV2**](ExternalAPI.md#BulkReleaseHoldUserOrGroupV2) | **Post** /external/v2/ad-users-or-groups/action/release-hold | Release users from hold.
[**ChangeUserPassword**](ExternalAPI.md#ChangeUserPassword) | **Post** /external/v1/ad-users-or-groups/action/change-user-password | Changes the password of AD User
[**ComputeSpaceRequirements**](ExternalAPI.md#ComputeSpaceRequirements) | **Post** /external/v1/datastores/action/compute-requirements | Computes the datastore space requirements for inventory resources.
[**DeleteAuxiliaryAccounts**](ExternalAPI.md#DeleteAuxiliaryAccounts) | **Post** /external/v1/ad-domains/{id}/action/delete-auxiliary-accounts | Specification to delete auxiliary accounts from the untrusted domain
[**GetADContainer**](ExternalAPI.md#GetADContainer) | **Get** /external/v1/ad-domains/{id}/ad-containers/{rdn} | Gets the AD container for specified domain.
[**GetADUserOrGroupInfo**](ExternalAPI.md#GetADUserOrGroupInfo) | **Get** /external/v1/ad-users-or-groups/{id} | Get information related to AD User or Group
[**GetDefaultADContainer**](ExternalAPI.md#GetDefaultADContainer) | **Get** /external/v1/ad-domains/{id}/ad-containers/default | Get default AD container for specified domain.
[**ListADContainers**](ExternalAPI.md#ListADContainers) | **Get** /external/v1/ad-domains/{id}/ad-containers | List active directory containers for a specific domain.
[**ListADDomains**](ExternalAPI.md#ListADDomains) | **Get** /external/v1/ad-domains | Lists information related to AD Domains of the environment.
[**ListADDomainsV2**](ExternalAPI.md#ListADDomainsV2) | **Get** /external/v2/ad-domains | Lists information related to AD Domains of the environment.
[**ListADDomainsV3**](ExternalAPI.md#ListADDomainsV3) | **Get** /external/v3/ad-domains | Lists information related to AD Domains of the environment.
[**ListADUserOrGroupSummary**](ExternalAPI.md#ListADUserOrGroupSummary) | **Get** /external/v1/ad-users-or-groups | Lists AD users or groups information.
[**ListAuditEvents**](ExternalAPI.md#ListAuditEvents) | **Get** /external/v1/audit-events | Lists the audit events.
[**ListBaseSnapshots**](ExternalAPI.md#ListBaseSnapshots) | **Get** /external/v1/base-snapshots | Lists all the VM snapshots from the vCenter for a given VM.
[**ListBaseSnapshotsV2**](ExternalAPI.md#ListBaseSnapshotsV2) | **Get** /external/v2/base-snapshots | Lists all the VM snapshots from the vCenter for a given VM.
[**ListBaseVMs**](ExternalAPI.md#ListBaseVMs) | **Get** /external/v1/base-vms | Lists all the VMs from a vCenter or a datacenter in that vCenter which may be suitable as snapshots for instant clone desktop pool or farm creation.
[**ListBaseVMsV2**](ExternalAPI.md#ListBaseVMsV2) | **Get** /external/v2/base-vms | Lists all the VMs from a vCenter or a datacenter in that vCenter which may be suitable as snapshots for instant clone desktop pool or farm creation.
[**ListCustomizationSpecs**](ExternalAPI.md#ListCustomizationSpecs) | **Get** /external/v1/customization-specifications | Lists all the customization specifications from the vCenter.
[**ListDatacenters**](ExternalAPI.md#ListDatacenters) | **Get** /external/v1/datacenters | Lists all the datacenters of a vCenter.
[**ListDatastoreClusters**](ExternalAPI.md#ListDatastoreClusters) | **Get** /external/v1/datastore-clusters | Lists all the datastore clusters from the vCenter for the given host or cluster.
[**ListDatastorePaths**](ExternalAPI.md#ListDatastorePaths) | **Get** /external/v1/datastore-paths | Lists all the folder paths within a Datastore from vCenter.
[**ListDomains**](ExternalAPI.md#ListDomains) | **Get** /external/v1/domains | Returns a map of domain NETBIOS name and dns name for domains which are configured on connection server.
[**ListHeldUsersOrGroups**](ExternalAPI.md#ListHeldUsersOrGroups) | **Get** /external/v1/ad-users-or-groups/held-users-or-groups | List information related to Held Users.
[**ListHostsOrClusters**](ExternalAPI.md#ListHostsOrClusters) | **Get** /external/v1/hosts-or-clusters | Lists all the hosts or clusters of the datacenter.
[**ListNetworkInterfaceCards**](ExternalAPI.md#ListNetworkInterfaceCards) | **Get** /external/v1/network-interface-cards | Returns a list of network interface cards (NICs) suitable for configuration on a desktop pool/farm.
[**ListNetworkInterfaceCardsV2**](ExternalAPI.md#ListNetworkInterfaceCardsV2) | **Get** /external/v2/network-interface-cards | Returns a list of network interface cards (NICs) suitable for configuration on a desktop pool/farm.
[**ListNetworkLabels**](ExternalAPI.md#ListNetworkLabels) | **Get** /external/v1/network-labels | Retrieves all network labels on the given host or cluster
[**ListResourcePools**](ExternalAPI.md#ListResourcePools) | **Get** /external/v1/resource-pools | Lists all the resource pools from the vCenter for the given host or cluster.
[**ListVMFolders**](ExternalAPI.md#ListVMFolders) | **Get** /external/v1/vm-folders | Lists all the VM folders from the vCenter for the given datacenter.
[**ListVMTemplates**](ExternalAPI.md#ListVMTemplates) | **Get** /external/v1/vm-templates | Lists all the VM templates from a vCenter or a datacenter for the given vCenter which may be suitable for full clone desktop pool creation.
[**ListVirtualMachines**](ExternalAPI.md#ListVirtualMachines) | **Get** /external/v1/virtual-machines | Lists all the VMs from a vCenter.
[**Listdatastores**](ExternalAPI.md#Listdatastores) | **Get** /external/v1/datastores | Lists all the datastores from the vCenter for the given host or cluster.
[**Unbind**](ExternalAPI.md#Unbind) | **Post** /external/v1/ad-domains/{id}/action/unbind | Unbind untrusted domain from the connection server.
[**Update**](ExternalAPI.md#Update) | **Post** /external/v1/ad-domains/{id}/action/update | Updates untrusted domain.
[**UpdateAuxiliaryAccounts**](ExternalAPI.md#UpdateAuxiliaryAccounts) | **Post** /external/v1/ad-domains/action/update-auxiliary-accounts | Update auxiliary accounts of the untrusted domain
[**ValidateADUserEncryptedCredentials**](ExternalAPI.md#ValidateADUserEncryptedCredentials) | **Post** /external/v1/ad-users-or-groups/action/validate-user-encrypted-credentials | Validates the encrypted credentials of AD User



## AddAuxiliaryAccounts

> []BulkItemResponseInfo AddAuxiliaryAccounts(ctx, id).Body(body).Execute()

Add auxiliary accounts to the untrusted domain



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
	body := *openapiclient.NewADDomainAuxiliaryAccountCreateSpec([]openapiclient.ADDomainServiceAccountSpec{*openapiclient.NewADDomainServiceAccountSpec([]string{"Password_example"}, "Administrator")}) // ADDomainAuxiliaryAccountCreateSpec | Specification of auxiliary accounts.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.AddAuxiliaryAccounts(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.AddAuxiliaryAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddAuxiliaryAccounts`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.AddAuxiliaryAccounts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddAuxiliaryAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ADDomainAuxiliaryAccountCreateSpec**](ADDomainAuxiliaryAccountCreateSpec.md) | Specification of auxiliary accounts. | 

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


## AuditEventsExtendedAttributes

> []AuditEventAttributeInfo AuditEventsExtendedAttributes(ctx).Ids(ids).Execute()

Get extended attributes of audit events

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
	ids := []int64{int64(123)} // []int64 | Audit Event IDs

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.AuditEventsExtendedAttributes(context.Background()).Ids(ids).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.AuditEventsExtendedAttributes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AuditEventsExtendedAttributes`: []AuditEventAttributeInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.AuditEventsExtendedAttributes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAuditEventsExtendedAttributesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]int64** | Audit Event IDs | 

### Return type

[**[]AuditEventAttributeInfo**](AuditEventAttributeInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Bind

> ADDomainBindInfo Bind(ctx).Body(body).Execute()

Bind untrusted domain to the connection server.



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
	body := *openapiclient.NewADDomainSpec(*openapiclient.NewADDomainAdvancedSettings("dc=abc,dc=com", int32(389)), "example.com", "EXAMPLE", *openapiclient.NewADDomainServiceAccountSpec([]string{"Password_example"}, "Administrator")) // ADDomainSpec | Specification of untrusted domain.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.Bind(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.Bind``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Bind`: ADDomainBindInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.Bind`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBindRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ADDomainSpec**](ADDomainSpec.md) | Specification of untrusted domain. | 

### Return type

[**ADDomainBindInfo**](ADDomainBindInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BulkHoldUserOrGroup

> []BulkItemResponseInfo BulkHoldUserOrGroup(ctx).Body(body).Execute()

Put users on hold.



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
	body := []string{"Property_example"} // []string | Set of AD user SIDs to put on hold.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.BulkHoldUserOrGroup(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.BulkHoldUserOrGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkHoldUserOrGroup`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.BulkHoldUserOrGroup`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkHoldUserOrGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | Set of AD user SIDs to put on hold. | 

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


## BulkHoldUserOrGroupV2

> []HeldUserOrGroupResponseInfo BulkHoldUserOrGroupV2(ctx).Body(body).Execute()

Put users on hold.



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
	body := []string{"Property_example"} // []string | Set of AD user SIDs to put on hold.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.BulkHoldUserOrGroupV2(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.BulkHoldUserOrGroupV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkHoldUserOrGroupV2`: []HeldUserOrGroupResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.BulkHoldUserOrGroupV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkHoldUserOrGroupV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | Set of AD user SIDs to put on hold. | 

### Return type

[**[]HeldUserOrGroupResponseInfo**](HeldUserOrGroupResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BulkReleaseHoldUserOrGroup

> []BulkItemResponseInfo BulkReleaseHoldUserOrGroup(ctx).Body(body).Execute()

Release users from hold.



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
	body := []string{"Property_example"} // []string | Set of AD user SIDs to release from hold.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.BulkReleaseHoldUserOrGroup(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.BulkReleaseHoldUserOrGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkReleaseHoldUserOrGroup`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.BulkReleaseHoldUserOrGroup`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkReleaseHoldUserOrGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | Set of AD user SIDs to release from hold. | 

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


## BulkReleaseHoldUserOrGroupV2

> []HeldUserOrGroupResponseInfo BulkReleaseHoldUserOrGroupV2(ctx).Body(body).Execute()

Release users from hold.



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
	body := []string{"Property_example"} // []string | Set of AD user SIDs to release from hold.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.BulkReleaseHoldUserOrGroupV2(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.BulkReleaseHoldUserOrGroupV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkReleaseHoldUserOrGroupV2`: []HeldUserOrGroupResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.BulkReleaseHoldUserOrGroupV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkReleaseHoldUserOrGroupV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | Set of AD user SIDs to release from hold. | 

### Return type

[**[]HeldUserOrGroupResponseInfo**](HeldUserOrGroupResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ChangeUserPassword

> ADUserInfo ChangeUserPassword(ctx).Body(body).Execute()

Changes the password of AD User



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
	body := *openapiclient.NewADUserChangePasswordSpec("ut0yGq7CbhtBUGfW3ngjkvjQ2cc=", "4TGdfggfwrrGUPSg4/JK/tYub7lUI8pGtyHd/ty5g8h5=", "9QYxpdXrcrOGPSSz1/K/pJu8QlYT7pDkaKg/rb3hlw4=", "Qvvjglg5iZinyuldroueo/hQFyqydMMDJPmfYGgIebqxbU9chJ9I8iM9SCBRHSkSW9y+RMQOfC", "testuser or testuser@example.com") // ADUserChangePasswordSpec | AD user password object to be changed.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ChangeUserPassword(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ChangeUserPassword``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ChangeUserPassword`: ADUserInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ChangeUserPassword`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChangeUserPasswordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ADUserChangePasswordSpec**](ADUserChangePasswordSpec.md) | AD user password object to be changed. | 

### Return type

[**ADUserInfo**](ADUserInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ComputeSpaceRequirements

> []DatastoreSpaceRequirementInfo ComputeSpaceRequirements(ctx).Body(body).Execute()

Computes the datastore space requirements for inventory resources.



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
	body := *openapiclient.NewDatastoreSpaceRequirementSpec(int32(123), "INSTANT_CLONE", "FARM", "ed3f92f3-0eef-4bf1-a405-de69f138d382") // DatastoreSpaceRequirementSpec | Datastore space requirement to be computed.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ComputeSpaceRequirements(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ComputeSpaceRequirements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ComputeSpaceRequirements`: []DatastoreSpaceRequirementInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ComputeSpaceRequirements`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiComputeSpaceRequirementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**DatastoreSpaceRequirementSpec**](DatastoreSpaceRequirementSpec.md) | Datastore space requirement to be computed. | 

### Return type

[**[]DatastoreSpaceRequirementInfo**](DatastoreSpaceRequirementInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAuxiliaryAccounts

> []BulkItemResponseInfo DeleteAuxiliaryAccounts(ctx, id).Body(body).Execute()

Specification to delete auxiliary accounts from the untrusted domain



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
	body := *openapiclient.NewADDomainAuxiliaryAccountDeleteSpec([]string{"AuxiliaryAccountIds_example"}) // ADDomainAuxiliaryAccountDeleteSpec | Auxiliary accounts to delete.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.DeleteAuxiliaryAccounts(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.DeleteAuxiliaryAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAuxiliaryAccounts`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.DeleteAuxiliaryAccounts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAuxiliaryAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ADDomainAuxiliaryAccountDeleteSpec**](ADDomainAuxiliaryAccountDeleteSpec.md) | Auxiliary accounts to delete. | 

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


## GetADContainer

> ADContainerInfo GetADContainer(ctx, id, rdn).Execute()

Gets the AD container for specified domain.



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
	id := "id_example" // string | AD Domain SID
	rdn := "rdn_example" // string | rdn of AD container in Base64URL encoded format.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.GetADContainer(context.Background(), id, rdn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.GetADContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetADContainer`: ADContainerInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.GetADContainer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | AD Domain SID | 
**rdn** | **string** | rdn of AD container in Base64URL encoded format. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetADContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ADContainerInfo**](ADContainerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetADUserOrGroupInfo

> ADUserOrGroupInfo GetADUserOrGroupInfo(ctx, id).Execute()

Get information related to AD User or Group

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
	resp, r, err := apiClient.ExternalAPI.GetADUserOrGroupInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.GetADUserOrGroupInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetADUserOrGroupInfo`: ADUserOrGroupInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.GetADUserOrGroupInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetADUserOrGroupInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ADUserOrGroupInfo**](ADUserOrGroupInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDefaultADContainer

> ADContainerInfo GetDefaultADContainer(ctx, id).Execute()

Get default AD container for specified domain.



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
	id := "id_example" // string | AD Domain SID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.GetDefaultADContainer(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.GetDefaultADContainer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDefaultADContainer`: ADContainerInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.GetDefaultADContainer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | AD Domain SID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDefaultADContainerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ADContainerInfo**](ADContainerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADContainers

> []ADContainerInfo ListADContainers(ctx, id).ContainerName(containerName).Rdn(rdn).SubTreeSearch(subTreeSearch).Execute()

List active directory containers for a specific domain.



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
	id := "id_example" // string | AD domain SID
	containerName := "containerName_example" // string | AD container name in Base64URL encoded format (optional)
	rdn := "rdn_example" // string | rdn of AD container in Base64URL encoded format (optional)
	subTreeSearch := false // bool | true to search subtree. Subtree search is only supported for rdn. (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListADContainers(context.Background(), id).ContainerName(containerName).Rdn(rdn).SubTreeSearch(subTreeSearch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListADContainers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADContainers`: []ADContainerInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListADContainers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | AD domain SID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListADContainersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **containerName** | **string** | AD container name in Base64URL encoded format | 
 **rdn** | **string** | rdn of AD container in Base64URL encoded format | 
 **subTreeSearch** | **bool** | true to search subtree. Subtree search is only supported for rdn. | [default to false]

### Return type

[**[]ADContainerInfo**](ADContainerInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADDomains

> []ADDomainInfo ListADDomains(ctx).Execute()

Lists information related to AD Domains of the environment.

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
	resp, r, err := apiClient.ExternalAPI.ListADDomains(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListADDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADDomains`: []ADDomainInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListADDomains`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListADDomainsRequest struct via the builder pattern


### Return type

[**[]ADDomainInfo**](ADDomainInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADDomainsV2

> []ADDomainInfoV2 ListADDomainsV2(ctx).Execute()

Lists information related to AD Domains of the environment.

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
	resp, r, err := apiClient.ExternalAPI.ListADDomainsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListADDomainsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADDomainsV2`: []ADDomainInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListADDomainsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListADDomainsV2Request struct via the builder pattern


### Return type

[**[]ADDomainInfoV2**](ADDomainInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADDomainsV3

> []ADDomainInfoV3 ListADDomainsV3(ctx).Execute()

Lists information related to AD Domains of the environment.

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
	resp, r, err := apiClient.ExternalAPI.ListADDomainsV3(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListADDomainsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADDomainsV3`: []ADDomainInfoV3
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListADDomainsV3`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListADDomainsV3Request struct via the builder pattern


### Return type

[**[]ADDomainInfoV3**](ADDomainInfoV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADUserOrGroupSummary

> []ADUserOrGroupSummary ListADUserOrGroupSummary(ctx).Filter(filter).GroupOnly(groupOnly).Page(page).Size(size).Execute()

Lists AD users or groups information.



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
	groupOnly := "groupOnly_example" // string | Presence of this query param indicates to filter only groups or only users.   If passed as \"true\", then only groups are returned.  If passed as \"false\", then only users are returned.  If not passed passed at all, then both types are returned. (optional)
	page := int32(1) // int32 | page, if passed should be > 0. (optional)
	size := int32(10) // int32 | size, if passed should be > 0. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListADUserOrGroupSummary(context.Background()).Filter(filter).GroupOnly(groupOnly).Page(page).Size(size).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListADUserOrGroupSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADUserOrGroupSummary`: []ADUserOrGroupSummary
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListADUserOrGroupSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListADUserOrGroupSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** | filter expression built using fields with &lt;b&gt;&#39;supported filters&#39;&lt;/b&gt; as described in output &lt;b&gt;model&lt;/b&gt; schema of this API. | 
 **groupOnly** | **string** | Presence of this query param indicates to filter only groups or only users.   If passed as \&quot;true\&quot;, then only groups are returned.  If passed as \&quot;false\&quot;, then only users are returned.  If not passed passed at all, then both types are returned. | 
 **page** | **int32** | page, if passed should be &gt; 0. | 
 **size** | **int32** | size, if passed should be &gt; 0. | 

### Return type

[**[]ADUserOrGroupSummary**](ADUserOrGroupSummary.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAuditEvents

> []AuditEventSummary ListAuditEvents(ctx).Filter(filter).Page(page).Size(size).Execute()

Lists the audit events.



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
	resp, r, err := apiClient.ExternalAPI.ListAuditEvents(context.Background()).Filter(filter).Page(page).Size(size).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListAuditEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAuditEvents`: []AuditEventSummary
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListAuditEvents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAuditEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** | filter expression built using fields with &lt;b&gt;&#39;supported filters&#39;&lt;/b&gt; as described in output &lt;b&gt;model&lt;/b&gt; schema of this API. | 
 **page** | **int32** | page, if passed should be &gt; 0. | 
 **size** | **int32** | size, if passed should be &gt; 0. | 

### Return type

[**[]AuditEventSummary**](AuditEventSummary.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBaseSnapshots

> []BaseSnapshotInfo ListBaseSnapshots(ctx).BaseVmId(baseVmId).VcenterId(vcenterId).Execute()

Lists all the VM snapshots from the vCenter for a given VM.



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
	baseVmId := "vm-1" // string | VM ID
	vcenterId := "d0325b13-2bf1-4fa4-b027-e780004f2d1e" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListBaseSnapshots(context.Background()).BaseVmId(baseVmId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListBaseSnapshots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBaseSnapshots`: []BaseSnapshotInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListBaseSnapshots`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListBaseSnapshotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **baseVmId** | **string** | VM ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]BaseSnapshotInfo**](BaseSnapshotInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBaseSnapshotsV2

> []BaseSnapshotInfoV2 ListBaseSnapshotsV2(ctx).BaseVmId(baseVmId).VcenterId(vcenterId).Execute()

Lists all the VM snapshots from the vCenter for a given VM.



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
	baseVmId := "vm-1" // string | VM ID
	vcenterId := "d0325b13-2bf1-4fa4-b027-e780004f2d1e" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListBaseSnapshotsV2(context.Background()).BaseVmId(baseVmId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListBaseSnapshotsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBaseSnapshotsV2`: []BaseSnapshotInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListBaseSnapshotsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListBaseSnapshotsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **baseVmId** | **string** | VM ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]BaseSnapshotInfoV2**](BaseSnapshotInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBaseVMs

> []BaseVMInfo ListBaseVMs(ctx).VcenterId(vcenterId).DatacenterId(datacenterId).FilterIncompatibleVms(filterIncompatibleVms).Execute()

Lists all the VMs from a vCenter or a datacenter in that vCenter which may be suitable as snapshots for instant clone desktop pool or farm creation.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID
	datacenterId := "datacenterId_example" // string | Datacenter ID (optional)
	filterIncompatibleVms := false // bool | Whether to filter out incompatible VMs (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListBaseVMs(context.Background()).VcenterId(vcenterId).DatacenterId(datacenterId).FilterIncompatibleVms(filterIncompatibleVms).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListBaseVMs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBaseVMs`: []BaseVMInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListBaseVMs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListBaseVMsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 
 **datacenterId** | **string** | Datacenter ID | 
 **filterIncompatibleVms** | **bool** | Whether to filter out incompatible VMs | [default to false]

### Return type

[**[]BaseVMInfo**](BaseVMInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBaseVMsV2

> []BaseVMInfoV2 ListBaseVMsV2(ctx).VcenterId(vcenterId).DatacenterId(datacenterId).FilterIncompatibleVms(filterIncompatibleVms).Execute()

Lists all the VMs from a vCenter or a datacenter in that vCenter which may be suitable as snapshots for instant clone desktop pool or farm creation.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID
	datacenterId := "datacenterId_example" // string | Datacenter ID (optional)
	filterIncompatibleVms := false // bool | Whether to filter out incompatible VMs (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListBaseVMsV2(context.Background()).VcenterId(vcenterId).DatacenterId(datacenterId).FilterIncompatibleVms(filterIncompatibleVms).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListBaseVMsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBaseVMsV2`: []BaseVMInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListBaseVMsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListBaseVMsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 
 **datacenterId** | **string** | Datacenter ID | 
 **filterIncompatibleVms** | **bool** | Whether to filter out incompatible VMs | [default to false]

### Return type

[**[]BaseVMInfoV2**](BaseVMInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCustomizationSpecs

> []CustomizationSpecInfo ListCustomizationSpecs(ctx).VcenterId(vcenterId).Execute()

Lists all the customization specifications from the vCenter.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListCustomizationSpecs(context.Background()).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListCustomizationSpecs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCustomizationSpecs`: []CustomizationSpecInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListCustomizationSpecs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCustomizationSpecsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]CustomizationSpecInfo**](CustomizationSpecInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDatacenters

> []DatacenterInfo ListDatacenters(ctx).VcenterId(vcenterId).Execute()

Lists all the datacenters of a vCenter.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListDatacenters(context.Background()).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListDatacenters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDatacenters`: []DatacenterInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListDatacenters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDatacentersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]DatacenterInfo**](DatacenterInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDatastoreClusters

> []DatastoreClusterInfo ListDatastoreClusters(ctx).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).Execute()

Lists all the datastore clusters from the vCenter for the given host or cluster.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListDatastoreClusters(context.Background()).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListDatastoreClusters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDatastoreClusters`: []DatastoreClusterInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListDatastoreClusters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDatastoreClustersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hostOrClusterId** | **string** | Host or Cluster ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]DatastoreClusterInfo**](DatastoreClusterInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDatastorePaths

> []DatastorePathInfo ListDatastorePaths(ctx).DatastoreId(datastoreId).VcenterId(vcenterId).Execute()

Lists all the folder paths within a Datastore from vCenter.



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
	datastoreId := "datastore-29" // string | Datastore ID
	vcenterId := "d0325b13-2bf1-4fa4-b027-e780004f2d1e" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListDatastorePaths(context.Background()).DatastoreId(datastoreId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListDatastorePaths``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDatastorePaths`: []DatastorePathInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListDatastorePaths`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDatastorePathsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **datastoreId** | **string** | Datastore ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]DatastorePathInfo**](DatastorePathInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDomains

> map[string]string ListDomains(ctx).Execute()

Returns a map of domain NETBIOS name and dns name for domains which are configured on connection server.

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
	resp, r, err := apiClient.ExternalAPI.ListDomains(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDomains`: map[string]string
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListDomains`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListDomainsRequest struct via the builder pattern


### Return type

**map[string]string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListHeldUsersOrGroups

> []HeldUserOrGroupInfo ListHeldUsersOrGroups(ctx).Execute()

List information related to Held Users.



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
	resp, r, err := apiClient.ExternalAPI.ListHeldUsersOrGroups(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListHeldUsersOrGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListHeldUsersOrGroups`: []HeldUserOrGroupInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListHeldUsersOrGroups`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListHeldUsersOrGroupsRequest struct via the builder pattern


### Return type

[**[]HeldUserOrGroupInfo**](HeldUserOrGroupInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListHostsOrClusters

> []HostOrClusterInfo ListHostsOrClusters(ctx).DatacenterId(datacenterId).VcenterId(vcenterId).Execute()

Lists all the hosts or clusters of the datacenter.



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
	datacenterId := "datacenterId_example" // string | Datacenter ID
	vcenterId := "vcenterId_example" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListHostsOrClusters(context.Background()).DatacenterId(datacenterId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListHostsOrClusters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListHostsOrClusters`: []HostOrClusterInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListHostsOrClusters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListHostsOrClustersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **datacenterId** | **string** | Datacenter ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]HostOrClusterInfo**](HostOrClusterInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListNetworkInterfaceCards

> []NetworkInterfaceCardInfo ListNetworkInterfaceCards(ctx).VcenterId(vcenterId).BaseSnapshotId(baseSnapshotId).BaseVmId(baseVmId).VmTemplateId(vmTemplateId).Execute()

Returns a list of network interface cards (NICs) suitable for configuration on a desktop pool/farm.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID
	baseSnapshotId := "baseSnapshotId_example" // string | Base Snapshot ID (optional)
	baseVmId := "baseVmId_example" // string | Base VM ID (optional)
	vmTemplateId := "vmTemplateId_example" // string | VM Template ID (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListNetworkInterfaceCards(context.Background()).VcenterId(vcenterId).BaseSnapshotId(baseSnapshotId).BaseVmId(baseVmId).VmTemplateId(vmTemplateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListNetworkInterfaceCards``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListNetworkInterfaceCards`: []NetworkInterfaceCardInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListNetworkInterfaceCards`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListNetworkInterfaceCardsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 
 **baseSnapshotId** | **string** | Base Snapshot ID | 
 **baseVmId** | **string** | Base VM ID | 
 **vmTemplateId** | **string** | VM Template ID | 

### Return type

[**[]NetworkInterfaceCardInfo**](NetworkInterfaceCardInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListNetworkInterfaceCardsV2

> []NetworkInterfaceCardInfoV2 ListNetworkInterfaceCardsV2(ctx).VcenterId(vcenterId).BaseSnapshotId(baseSnapshotId).BaseVmId(baseVmId).VmTemplateId(vmTemplateId).Execute()

Returns a list of network interface cards (NICs) suitable for configuration on a desktop pool/farm.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID
	baseSnapshotId := "baseSnapshotId_example" // string | Base Snapshot ID (optional)
	baseVmId := "baseVmId_example" // string | Base VM ID (optional)
	vmTemplateId := "vmTemplateId_example" // string | VM Template ID (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListNetworkInterfaceCardsV2(context.Background()).VcenterId(vcenterId).BaseSnapshotId(baseSnapshotId).BaseVmId(baseVmId).VmTemplateId(vmTemplateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListNetworkInterfaceCardsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListNetworkInterfaceCardsV2`: []NetworkInterfaceCardInfoV2
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListNetworkInterfaceCardsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListNetworkInterfaceCardsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 
 **baseSnapshotId** | **string** | Base Snapshot ID | 
 **baseVmId** | **string** | Base VM ID | 
 **vmTemplateId** | **string** | VM Template ID | 

### Return type

[**[]NetworkInterfaceCardInfoV2**](NetworkInterfaceCardInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListNetworkLabels

> []NetworkLabelInfo ListNetworkLabels(ctx).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).NetworkType(networkType).Execute()

Retrieves all network labels on the given host or cluster



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID
	networkType := "networkType_example" // string | Network Type * NETWORK: Standard network. * OPAQUE_NETWORK: Opaque network. * DISTRUBUTED_VIRTUAL_PORT_GROUP: DVS Port group. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListNetworkLabels(context.Background()).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).NetworkType(networkType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListNetworkLabels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListNetworkLabels`: []NetworkLabelInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListNetworkLabels`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListNetworkLabelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hostOrClusterId** | **string** | Host or Cluster ID | 
 **vcenterId** | **string** | Virtual Center ID | 
 **networkType** | **string** | Network Type * NETWORK: Standard network. * OPAQUE_NETWORK: Opaque network. * DISTRUBUTED_VIRTUAL_PORT_GROUP: DVS Port group. | 

### Return type

[**[]NetworkLabelInfo**](NetworkLabelInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListResourcePools

> []ResourcePoolInfo ListResourcePools(ctx).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).Execute()

Lists all the resource pools from the vCenter for the given host or cluster.



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
	hostOrClusterId := "domain-c85" // string | Host or Cluster ID
	vcenterId := "d0325b13-2bf1-4fa4-b027-e780004f2d1e" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListResourcePools(context.Background()).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListResourcePools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListResourcePools`: []ResourcePoolInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListResourcePools`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListResourcePoolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hostOrClusterId** | **string** | Host or Cluster ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]ResourcePoolInfo**](ResourcePoolInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVMFolders

> []VMFolderInfo ListVMFolders(ctx).DatacenterId(datacenterId).VcenterId(vcenterId).Execute()

Lists all the VM folders from the vCenter for the given datacenter.



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
	datacenterId := "datacenter-1" // string | Datacenter ID
	vcenterId := "d0325b13-2bf1-4fa4-b027-e780004f2d1e" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListVMFolders(context.Background()).DatacenterId(datacenterId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListVMFolders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVMFolders`: []VMFolderInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListVMFolders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListVMFoldersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **datacenterId** | **string** | Datacenter ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]VMFolderInfo**](VMFolderInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVMTemplates

> []VMTemplateInfo ListVMTemplates(ctx).VcenterId(vcenterId).DatacenterId(datacenterId).Execute()

Lists all the VM templates from a vCenter or a datacenter for the given vCenter which may be suitable for full clone desktop pool creation.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID
	datacenterId := "datacenterId_example" // string | Datacenter ID (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListVMTemplates(context.Background()).VcenterId(vcenterId).DatacenterId(datacenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListVMTemplates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVMTemplates`: []VMTemplateInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListVMTemplates`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListVMTemplatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 
 **datacenterId** | **string** | Datacenter ID | 

### Return type

[**[]VMTemplateInfo**](VMTemplateInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVirtualMachines

> []VirtualMachineInfo ListVirtualMachines(ctx).VcenterId(vcenterId).Execute()

Lists all the VMs from a vCenter.



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
	vcenterId := "vcenterId_example" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ListVirtualMachines(context.Background()).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ListVirtualMachines``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVirtualMachines`: []VirtualMachineInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ListVirtualMachines`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListVirtualMachinesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]VirtualMachineInfo**](VirtualMachineInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Listdatastores

> []DatastoreInfo Listdatastores(ctx).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).Execute()

Lists all the datastores from the vCenter for the given host or cluster.



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
	hostOrClusterId := "domain-c85" // string | Host or Cluster ID
	vcenterId := "d0325b13-2bf1-4fa4-b027-e780004f2d1e" // string | Virtual Center ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.Listdatastores(context.Background()).HostOrClusterId(hostOrClusterId).VcenterId(vcenterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.Listdatastores``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Listdatastores`: []DatastoreInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.Listdatastores`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListdatastoresRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hostOrClusterId** | **string** | Host or Cluster ID | 
 **vcenterId** | **string** | Virtual Center ID | 

### Return type

[**[]DatastoreInfo**](DatastoreInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Unbind

> Unbind(ctx, id).Execute()

Unbind untrusted domain from the connection server.



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
	r, err := apiClient.ExternalAPI.Unbind(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.Unbind``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUnbindRequest struct via the builder pattern


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


## Update

> Update(ctx, id).Body(body).Execute()

Updates untrusted domain.



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
	body := *openapiclient.NewADDomainUpdateSpec(*openapiclient.NewADDomainAdvancedSettings("dc=abc,dc=com", int32(389)), *openapiclient.NewADDomainServiceAccountSpec([]string{"Password_example"}, "Administrator")) // ADDomainUpdateSpec | Untrusted domain object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ExternalAPI.Update(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.Update``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**ADDomainUpdateSpec**](ADDomainUpdateSpec.md) | Untrusted domain object to be updated. | 

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


## UpdateAuxiliaryAccounts

> []BulkItemResponseInfo UpdateAuxiliaryAccounts(ctx).Body(body).Execute()

Update auxiliary accounts of the untrusted domain



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
	body := *openapiclient.NewADDomainAuxiliaryAccountUpdateSpec([]openapiclient.AuxiliaryAccountUpdateData{*openapiclient.NewAuxiliaryAccountUpdateData("1f95a15c-a7a5-4584-963f-2c3f5355b49f", []string{"Password_example"})}) // ADDomainAuxiliaryAccountUpdateSpec | Specification to update auxiliary accounts.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.UpdateAuxiliaryAccounts(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.UpdateAuxiliaryAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAuxiliaryAccounts`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.UpdateAuxiliaryAccounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAuxiliaryAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ADDomainAuxiliaryAccountUpdateSpec**](ADDomainAuxiliaryAccountUpdateSpec.md) | Specification to update auxiliary accounts. | 

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


## ValidateADUserEncryptedCredentials

> ADUserInfo ValidateADUserEncryptedCredentials(ctx).Body(body).Execute()

Validates the encrypted credentials of AD User



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
	body := *openapiclient.NewADUserEncryptedCredentialSpec("9QYxpdXrcrOGPSSz1/K/pJu8QlYT7pDkaKg/rb3hlw4=", "ut0yGq7CbhtBUGfW3ngjkvjQ2cc=", "Qvvjglg5iZinyuldroueo/hQFyqydMMDJPmfYGgIebqxbU9chJ9I8iM9SCBRHSkSW9y+RM", "testuser or testuser@example.com") // ADUserEncryptedCredentialSpec | AD user encrypted credentials object to be validated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ExternalAPI.ValidateADUserEncryptedCredentials(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ExternalAPI.ValidateADUserEncryptedCredentials``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidateADUserEncryptedCredentials`: ADUserInfo
	fmt.Fprintf(os.Stdout, "Response from `ExternalAPI.ValidateADUserEncryptedCredentials`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiValidateADUserEncryptedCredentialsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ADUserEncryptedCredentialSpec**](ADUserEncryptedCredentialSpec.md) | AD user encrypted credentials object to be validated. | 

### Return type

[**ADUserInfo**](ADUserInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

