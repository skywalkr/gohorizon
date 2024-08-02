# \FederationAPI

All URIs are relative to *http://localhost/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateHomeSites**](FederationAPI.md#CreateHomeSites) | **Post** /federation/v1/home-sites | Creates the given home sites in the pod federation.
[**CreateSite**](FederationAPI.md#CreateSite) | **Post** /federation/v1/sites | Creates a site.
[**DeleteHomeSites**](FederationAPI.md#DeleteHomeSites) | **Delete** /federation/v1/home-sites | Deletes the given home sites from the pod federation.
[**DeleteSite**](FederationAPI.md#DeleteSite) | **Delete** /federation/v1/sites/{id} | Deletes a site.
[**EjectPod**](FederationAPI.md#EjectPod) | **Post** /federation/v1/cpa/action/eject | Removes a pod from Cloud Pod Federation.
[**GetHomeSite**](FederationAPI.md#GetHomeSite) | **Get** /federation/v1/home-sites/{id} | Retrieves a given home site in the pod federation.
[**GetPod**](FederationAPI.md#GetPod) | **Get** /federation/v1/pods/{id} | Retrieves a given pod from the pod federation.
[**GetPodAssignment**](FederationAPI.md#GetPodAssignment) | **Get** /federation/v1/pod-assignments/{id} | Retrieves a given pod assignment from the pod federation.
[**GetPodEndpoint**](FederationAPI.md#GetPodEndpoint) | **Get** /federation/v1/pods/{id}/endpoints/{endpointId} | Retrieves pod endpoint details for the given pod endpoint id in the given pod.
[**GetPodFederation**](FederationAPI.md#GetPodFederation) | **Get** /federation/v1/cpa | Retrieves the pod federation details.
[**GetSite**](FederationAPI.md#GetSite) | **Get** /federation/v1/sites/{id} | Retrives a given site.
[**GetTask**](FederationAPI.md#GetTask) | **Get** /federation/v1/cpa/tasks/{id} | Retrieves the information for a given task.
[**InitializeCPA**](FederationAPI.md#InitializeCPA) | **Post** /federation/v1/cpa/action/initialize | Initialize Cloud Pod Federation.
[**JoinCPA**](FederationAPI.md#JoinCPA) | **Post** /federation/v1/cpa/action/join | Join Cloud Pod Federation.
[**ListHomeSites**](FederationAPI.md#ListHomeSites) | **Get** /federation/v1/home-sites | Lists all the home sites in the pod federation.
[**ListPodAssignments**](FederationAPI.md#ListPodAssignments) | **Get** /federation/v1/pod-assignments | Lists all the pod assignments in the pod federation.
[**ListPodEndpoint**](FederationAPI.md#ListPodEndpoint) | **Get** /federation/v1/pods/{id}/endpoints | Lists all the pod endpoints for the given pod.
[**ListPods**](FederationAPI.md#ListPods) | **Get** /federation/v1/pods | Lists all the pods in the pod federation.
[**ListSites**](FederationAPI.md#ListSites) | **Get** /federation/v1/sites | Lists all the sites in the pod federation.
[**ListTasks**](FederationAPI.md#ListTasks) | **Get** /federation/v1/cpa/tasks | Lists all the CPA tasks in the pod federation.
[**ResolveHomeSites**](FederationAPI.md#ResolveHomeSites) | **Post** /federation/v1/home-sites/action/resolve | Resolves home sites for a user in the pod federation.
[**UninitializeCPA**](FederationAPI.md#UninitializeCPA) | **Post** /federation/v1/cpa/action/uninitialize | Uninitialize Cloud Pod Federation.
[**UnjoinCPA**](FederationAPI.md#UnjoinCPA) | **Post** /federation/v1/cpa/action/unjoin | Unjoin from Cloud Pod Federation.
[**UpdatePod**](FederationAPI.md#UpdatePod) | **Put** /federation/v1/pods/{id} | Updates the given pod in the pod federation.
[**UpdatePodFederation**](FederationAPI.md#UpdatePodFederation) | **Put** /federation/v1/cpa | Updates a Pod Federation.
[**UpdateSite**](FederationAPI.md#UpdateSite) | **Put** /federation/v1/sites/{id} | Updates a site.



## CreateHomeSites

> []BulkItemResponseInfo CreateHomeSites(ctx).Body(body).Execute()

Creates the given home sites in the pod federation.



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
	body := []openapiclient.HomeSiteCreateSpec{*openapiclient.NewHomeSiteCreateSpec("S-1-5-32-551", "32a5ea06-cd09-4609-b3e5-df8379e99c13")} // []HomeSiteCreateSpec | List of home site objects to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FederationAPI.CreateHomeSites(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.CreateHomeSites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateHomeSites`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.CreateHomeSites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateHomeSitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**[]HomeSiteCreateSpec**](HomeSiteCreateSpec.md) | List of home site objects to be created. | 

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


## CreateSite

> CreateSite(ctx).Body(body).Execute()

Creates a site.



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
	body := *openapiclient.NewSiteCreateSpec("US Site") // SiteCreateSpec | Site object to be created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FederationAPI.CreateSite(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.CreateSite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSiteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**SiteCreateSpec**](SiteCreateSpec.md) | Site object to be created. | 

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


## DeleteHomeSites

> []BulkItemResponseInfo DeleteHomeSites(ctx).Body(body).Execute()

Deletes the given home sites from the pod federation.



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
	body := []string{"Property_example"} // []string | List of home site IDs to be deleted.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FederationAPI.DeleteHomeSites(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.DeleteHomeSites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteHomeSites`: []BulkItemResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.DeleteHomeSites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteHomeSitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **[]string** | List of home site IDs to be deleted. | 

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


## DeleteSite

> DeleteSite(ctx, id).Execute()

Deletes a site.



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
	r, err := apiClient.FederationAPI.DeleteSite(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.DeleteSite``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteSiteRequest struct via the builder pattern


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


## EjectPod

> EjectPod(ctx).Body(body).Execute()

Removes a pod from Cloud Pod Federation.



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
	body := *openapiclient.NewCPAEjectSpec("9e94a90d-e7c2-40b6-a702-bd781512408d") // CPAEjectSpec | The specification for removing a pod from pod federation.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FederationAPI.EjectPod(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.EjectPod``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEjectPodRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CPAEjectSpec**](CPAEjectSpec.md) | The specification for removing a pod from pod federation. | 

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


## GetHomeSite

> HomeSiteInfo GetHomeSite(ctx, id).Execute()

Retrieves a given home site in the pod federation.



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
	resp, r, err := apiClient.FederationAPI.GetHomeSite(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.GetHomeSite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHomeSite`: HomeSiteInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.GetHomeSite`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetHomeSiteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**HomeSiteInfo**](HomeSiteInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPod

> PodInfo GetPod(ctx, id).Execute()

Retrieves a given pod from the pod federation.



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
	id := "id_example" // string | ID of the Pod.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FederationAPI.GetPod(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.GetPod``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPod`: PodInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.GetPod`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the Pod. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPodRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PodInfo**](PodInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPodAssignment

> PodAssignmentInfo GetPodAssignment(ctx, id).Execute()

Retrieves a given pod assignment from the pod federation.



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
	resp, r, err := apiClient.FederationAPI.GetPodAssignment(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.GetPodAssignment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPodAssignment`: PodAssignmentInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.GetPodAssignment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPodAssignmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PodAssignmentInfo**](PodAssignmentInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPodEndpoint

> PodEndpointInfo GetPodEndpoint(ctx, endpointId, id).Execute()

Retrieves pod endpoint details for the given pod endpoint id in the given pod.



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
	endpointId := "endpointId_example" // string | Pod endpoint ID
	id := "id_example" // string | Pod ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FederationAPI.GetPodEndpoint(context.Background(), endpointId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.GetPodEndpoint``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPodEndpoint`: PodEndpointInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.GetPodEndpoint`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**endpointId** | **string** | Pod endpoint ID | 
**id** | **string** | Pod ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPodEndpointRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PodEndpointInfo**](PodEndpointInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPodFederation

> PodFederationInfo GetPodFederation(ctx).Execute()

Retrieves the pod federation details.



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
	resp, r, err := apiClient.FederationAPI.GetPodFederation(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.GetPodFederation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPodFederation`: PodFederationInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.GetPodFederation`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetPodFederationRequest struct via the builder pattern


### Return type

[**PodFederationInfo**](PodFederationInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSite

> SiteInfo GetSite(ctx, id).Execute()

Retrives a given site.



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
	resp, r, err := apiClient.FederationAPI.GetSite(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.GetSite``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSite`: SiteInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.GetSite`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSiteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SiteInfo**](SiteInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTask

> TaskInfo GetTask(ctx, id).Execute()

Retrieves the information for a given task.



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
	resp, r, err := apiClient.FederationAPI.GetTask(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.GetTask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTask`: TaskInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.GetTask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TaskInfo**](TaskInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitializeCPA

> CPATaskResponseInfo InitializeCPA(ctx).Execute()

Initialize Cloud Pod Federation.



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
	resp, r, err := apiClient.FederationAPI.InitializeCPA(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.InitializeCPA``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitializeCPA`: CPATaskResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.InitializeCPA`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiInitializeCPARequest struct via the builder pattern


### Return type

[**CPATaskResponseInfo**](CPATaskResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JoinCPA

> CPATaskResponseInfo JoinCPA(ctx).Body(body).Execute()

Join Cloud Pod Federation.



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
	body := *openapiclient.NewCPAJoinSpec([]string{"Password_example"}, "cs1.example.com", "AD-TEST-DOMAIN\Administrator") // CPAJoinSpec | The specification for joining the pod federation.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FederationAPI.JoinCPA(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.JoinCPA``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JoinCPA`: CPATaskResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.JoinCPA`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiJoinCPARequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CPAJoinSpec**](CPAJoinSpec.md) | The specification for joining the pod federation. | 

### Return type

[**CPATaskResponseInfo**](CPATaskResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListHomeSites

> []HomeSiteInfo ListHomeSites(ctx).Filter(filter).Page(page).Size(size).Execute()

Lists all the home sites in the pod federation.



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
	resp, r, err := apiClient.FederationAPI.ListHomeSites(context.Background()).Filter(filter).Page(page).Size(size).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.ListHomeSites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListHomeSites`: []HomeSiteInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.ListHomeSites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListHomeSitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** | filter expression built using fields with &lt;b&gt;&#39;supported filters&#39;&lt;/b&gt; as described in output &lt;b&gt;model&lt;/b&gt; schema of this API. | 
 **page** | **int32** | page, if passed should be &gt; 0. | 
 **size** | **int32** | size, if passed should be &gt; 0. | 

### Return type

[**[]HomeSiteInfo**](HomeSiteInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPodAssignments

> []PodAssignmentInfo ListPodAssignments(ctx).Filter(filter).Page(page).Size(size).Execute()

Lists all the pod assignments in the pod federation.



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
	resp, r, err := apiClient.FederationAPI.ListPodAssignments(context.Background()).Filter(filter).Page(page).Size(size).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.ListPodAssignments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPodAssignments`: []PodAssignmentInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.ListPodAssignments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPodAssignmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** | filter expression built using fields with &lt;b&gt;&#39;supported filters&#39;&lt;/b&gt; as described in output &lt;b&gt;model&lt;/b&gt; schema of this API. | 
 **page** | **int32** | page, if passed should be &gt; 0. | 
 **size** | **int32** | size, if passed should be &gt; 0. | 

### Return type

[**[]PodAssignmentInfo**](PodAssignmentInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPodEndpoint

> []PodEndpointInfo ListPodEndpoint(ctx, id).Execute()

Lists all the pod endpoints for the given pod.



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
	id := "id_example" // string | Pod ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FederationAPI.ListPodEndpoint(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.ListPodEndpoint``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPodEndpoint`: []PodEndpointInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.ListPodEndpoint`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Pod ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPodEndpointRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]PodEndpointInfo**](PodEndpointInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPods

> []PodInfo ListPods(ctx).Execute()

Lists all the pods in the pod federation.



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
	resp, r, err := apiClient.FederationAPI.ListPods(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.ListPods``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPods`: []PodInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.ListPods`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPodsRequest struct via the builder pattern


### Return type

[**[]PodInfo**](PodInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSites

> []SiteInfo ListSites(ctx).Execute()

Lists all the sites in the pod federation.



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
	resp, r, err := apiClient.FederationAPI.ListSites(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.ListSites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSites`: []SiteInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.ListSites`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListSitesRequest struct via the builder pattern


### Return type

[**[]SiteInfo**](SiteInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTasks

> []TaskInfo ListTasks(ctx).Execute()

Lists all the CPA tasks in the pod federation.



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
	resp, r, err := apiClient.FederationAPI.ListTasks(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.ListTasks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTasks`: []TaskInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.ListTasks`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListTasksRequest struct via the builder pattern


### Return type

[**[]TaskInfo**](TaskInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolveHomeSites

> []HomeSiteResolutionInfo ResolveHomeSites(ctx).Body(body).Execute()

Resolves home sites for a user in the pod federation.



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
	body := *openapiclient.NewHomeSiteResolutionSpec("S-1-5-21-3623811015-3361044348") // HomeSiteResolutionSpec | Home site specification to be resolved.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FederationAPI.ResolveHomeSites(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.ResolveHomeSites``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolveHomeSites`: []HomeSiteResolutionInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.ResolveHomeSites`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiResolveHomeSitesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**HomeSiteResolutionSpec**](HomeSiteResolutionSpec.md) | Home site specification to be resolved. | 

### Return type

[**[]HomeSiteResolutionInfo**](HomeSiteResolutionInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UninitializeCPA

> CPATaskResponseInfo UninitializeCPA(ctx).Execute()

Uninitialize Cloud Pod Federation.



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
	resp, r, err := apiClient.FederationAPI.UninitializeCPA(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.UninitializeCPA``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UninitializeCPA`: CPATaskResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.UninitializeCPA`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUninitializeCPARequest struct via the builder pattern


### Return type

[**CPATaskResponseInfo**](CPATaskResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnjoinCPA

> CPATaskResponseInfo UnjoinCPA(ctx).Execute()

Unjoin from Cloud Pod Federation.



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
	resp, r, err := apiClient.FederationAPI.UnjoinCPA(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.UnjoinCPA``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnjoinCPA`: CPATaskResponseInfo
	fmt.Fprintf(os.Stdout, "Response from `FederationAPI.UnjoinCPA`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUnjoinCPARequest struct via the builder pattern


### Return type

[**CPATaskResponseInfo**](CPATaskResponseInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePod

> UpdatePod(ctx, id).PodUpdateSpec(podUpdateSpec).Execute()

Updates the given pod in the pod federation.



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
	id := "id_example" // string | ID of the Pod.
	podUpdateSpec := *openapiclient.NewPodUpdateSpec("Cluster-CS-1", "9a892821-8c3d-4e61-9d65-69dfec7b70dc") // PodUpdateSpec | Pod object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FederationAPI.UpdatePod(context.Background(), id).PodUpdateSpec(podUpdateSpec).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.UpdatePod``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the Pod. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePodRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **podUpdateSpec** | [**PodUpdateSpec**](PodUpdateSpec.md) | Pod object to be updated. | 

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


## UpdatePodFederation

> UpdatePodFederation(ctx).Body(body).Execute()

Updates a Pod Federation.



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
	body := *openapiclient.NewCPAUpdateSpec("Horizon Cloud Pod Federation") // CPAUpdateSpec | Pod Federation object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FederationAPI.UpdatePodFederation(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.UpdatePodFederation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePodFederationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**CPAUpdateSpec**](CPAUpdateSpec.md) | Pod Federation object to be updated. | 

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


## UpdateSite

> UpdateSite(ctx, id).Body(body).Execute()

Updates a site.



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
	body := *openapiclient.NewSiteUpdateSpec("US Site") // SiteUpdateSpec | Site object to be updated.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FederationAPI.UpdateSite(context.Background(), id).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FederationAPI.UpdateSite``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateSiteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | [**SiteUpdateSpec**](SiteUpdateSpec.md) | Site object to be updated. | 

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

