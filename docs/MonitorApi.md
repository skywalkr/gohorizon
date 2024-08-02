# \MonitorAPI

All URIs are relative to *http://localhost/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAppVolumesManagerMonitorInfo**](MonitorAPI.md#GetAppVolumesManagerMonitorInfo) | **Get** /monitor/app-volumes-managers/{id} | Retrieves information about an app volumes manager.
[**GetConnectionServerMonitorInfoV2**](MonitorAPI.md#GetConnectionServerMonitorInfoV2) | **Get** /monitor/v1/connection-servers/{id} | Gets monitoring information related to Connection Server.
[**GetConnectionServerMonitorInfoV3**](MonitorAPI.md#GetConnectionServerMonitorInfoV3) | **Get** /monitor/v2/connection-servers/{id} | Gets monitoring information related to Connection Server.
[**GetEventDatabaseMonitor**](MonitorAPI.md#GetEventDatabaseMonitor) | **Get** /monitor/event-database | Returns monitoring information related to Event database of the environment.
[**GetFarmMonitorInfo**](MonitorAPI.md#GetFarmMonitorInfo) | **Get** /monitor/v1/farms/{id} | Gets monitoring information related to farm.
[**GetGatewayMonitorInfo**](MonitorAPI.md#GetGatewayMonitorInfo) | **Get** /monitor/v1/gateways/{id} | Gets monitoring information related to a Gateway.
[**GetGatewayMonitorInfoV2**](MonitorAPI.md#GetGatewayMonitorInfoV2) | **Get** /monitor/v2/gateways/{id} | Gets monitoring information related to a Gateway.
[**GetPodMonitorInfoV2**](MonitorAPI.md#GetPodMonitorInfoV2) | **Get** /monitor/v1/pods/{id} | Gets monitoring information related to the remote pod.
[**GetRDSServerMonitors**](MonitorAPI.md#GetRDSServerMonitors) | **Get** /monitor/v1/rds-servers/{id} | Gets monitoring information related to RDS Server.
[**GetSAMLAuthenticatorMonitorInfo**](MonitorAPI.md#GetSAMLAuthenticatorMonitorInfo) | **Get** /monitor/v1/saml-authenticators/{id} | Gets Monitoring Information related to a SAML Authenticator
[**GetTrueSSOMonitorInfo**](MonitorAPI.md#GetTrueSSOMonitorInfo) | **Get** /monitor/v1/true-sso/{id} | Gets monitoring information related to a True SSO connector.
[**GetViewComposerByVCId**](MonitorAPI.md#GetViewComposerByVCId) | **Get** /monitor/v1/view-composers/{vcId} | View Composer is no longer supported from Horizon version 2012 onwards.
[**GetVirtualCenterMonitorInfo**](MonitorAPI.md#GetVirtualCenterMonitorInfo) | **Get** /monitor/v1/virtual-centers/{id} | Gets monitoring information related to Virtual Center.
[**ListADDomainMonitorInfosV2**](MonitorAPI.md#ListADDomainMonitorInfosV2) | **Get** /monitor/v2/ad-domains | Lists monitoring information related to AD Domains of the environment.
[**ListADDomainMonitorInfosV3**](MonitorAPI.md#ListADDomainMonitorInfosV3) | **Get** /monitor/v3/ad-domains | Lists monitoring information related to AD Domains of the environment.
[**ListADDomainMonitors**](MonitorAPI.md#ListADDomainMonitors) | **Get** /monitor/ad-domains | Lists monitoring information related to AD Domains of the environment.
[**ListAppVolumesManagerMonitorInfoV1**](MonitorAPI.md#ListAppVolumesManagerMonitorInfoV1) | **Get** /monitor/app-volumes-managers | Lists monitoring information related to App volumes managers registered in the environment.
[**ListConnectionServerMonitors**](MonitorAPI.md#ListConnectionServerMonitors) | **Get** /monitor/connection-servers | Lists monitoring information related to Connection Servers of the environment.
[**ListConnectionServerMonitorsV2**](MonitorAPI.md#ListConnectionServerMonitorsV2) | **Get** /monitor/v2/connection-servers | Lists monitoring information related to Connection Servers of the environment.
[**ListConnectionServerMonitorsV3**](MonitorAPI.md#ListConnectionServerMonitorsV3) | **Get** /monitor/v3/connection-servers | Lists monitoring information related to Connection Servers of the environment.
[**ListDesktopPoolMetrics**](MonitorAPI.md#ListDesktopPoolMetrics) | **Get** /monitor/v1/desktop-pools/metrics | Lists metrics of desktop pools (except RDS desktop pools).
[**ListFarmMonitors**](MonitorAPI.md#ListFarmMonitors) | **Get** /monitor/farms | Lists monitoring information related to Farms of the environment.
[**ListGatewayMonitorInfoV1**](MonitorAPI.md#ListGatewayMonitorInfoV1) | **Get** /monitor/gateways | Lists monitoring information related to Gateways registered in the environment.
[**ListGatewayMonitorInfoV2**](MonitorAPI.md#ListGatewayMonitorInfoV2) | **Get** /monitor/v2/gateways | Lists monitoring information related to Gateways registered in the environment.
[**ListGatewayMonitorInfoV3**](MonitorAPI.md#ListGatewayMonitorInfoV3) | **Get** /monitor/v3/gateways | Lists monitoring information related to Gateways registered in the environment.
[**ListPodMonitorInfosV1**](MonitorAPI.md#ListPodMonitorInfosV1) | **Get** /monitor/v1/pods | Lists monitoring information related to the remote pods.
[**ListPodMonitorInfosV2**](MonitorAPI.md#ListPodMonitorInfosV2) | **Get** /monitor/v2/pods | Lists monitoring information related to the remote pods.
[**ListRDSServerMonitors**](MonitorAPI.md#ListRDSServerMonitors) | **Get** /monitor/rds-servers | Lists monitoring information related to RDS Servers of the environment.
[**ListSAMLAuthenticatorMonitorsV1**](MonitorAPI.md#ListSAMLAuthenticatorMonitorsV1) | **Get** /monitor/saml-authenticators | Lists monitoring information related to SAML Authenticators of the environment.
[**ListSAMLAuthenticatorMonitorsV2**](MonitorAPI.md#ListSAMLAuthenticatorMonitorsV2) | **Get** /monitor/v2/saml-authenticators | Lists monitoring information related to SAML Authenticators of the environment.
[**ListTrueSSOMonitorInfos**](MonitorAPI.md#ListTrueSSOMonitorInfos) | **Get** /monitor/v1/true-sso | Lists monitoring information related to True SSO connectors.
[**ListViewComposerMonitorsV1**](MonitorAPI.md#ListViewComposerMonitorsV1) | **Get** /monitor/view-composers | View Composer is no longer supported from Horizon version 2012 onwards.
[**ListViewComposerMonitorsV2**](MonitorAPI.md#ListViewComposerMonitorsV2) | **Get** /monitor/v2/view-composers | View Composer is no longer supported from Horizon version 2012 onwards.
[**ListVirtualCenterMonitors**](MonitorAPI.md#ListVirtualCenterMonitors) | **Get** /monitor/virtual-centers | Lists monitoring information related to Virtual Centers of the environment.
[**ListVirtualCenterMonitorsV2**](MonitorAPI.md#ListVirtualCenterMonitorsV2) | **Get** /monitor/v2/virtual-centers | Lists monitoring information related to Virtual Centers of the environment.



## GetAppVolumesManagerMonitorInfo

> AppVolumesManagerMonitorInfo GetAppVolumesManagerMonitorInfo(ctx, id).Execute()

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
	resp, r, err := apiClient.MonitorAPI.GetAppVolumesManagerMonitorInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetAppVolumesManagerMonitorInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppVolumesManagerMonitorInfo`: AppVolumesManagerMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetAppVolumesManagerMonitorInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppVolumesManagerMonitorInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppVolumesManagerMonitorInfo**](AppVolumesManagerMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConnectionServerMonitorInfoV2

> ConnectionServerMonitorInfoV2 GetConnectionServerMonitorInfoV2(ctx, id).Execute()

Gets monitoring information related to Connection Server.

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
	resp, r, err := apiClient.MonitorAPI.GetConnectionServerMonitorInfoV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetConnectionServerMonitorInfoV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnectionServerMonitorInfoV2`: ConnectionServerMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetConnectionServerMonitorInfoV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionServerMonitorInfoV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConnectionServerMonitorInfoV2**](ConnectionServerMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConnectionServerMonitorInfoV3

> ConnectionServerMonitorInfoV3 GetConnectionServerMonitorInfoV3(ctx, id).Execute()

Gets monitoring information related to Connection Server.

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
	resp, r, err := apiClient.MonitorAPI.GetConnectionServerMonitorInfoV3(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetConnectionServerMonitorInfoV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnectionServerMonitorInfoV3`: ConnectionServerMonitorInfoV3
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetConnectionServerMonitorInfoV3`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionServerMonitorInfoV3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConnectionServerMonitorInfoV3**](ConnectionServerMonitorInfoV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEventDatabaseMonitor

> EventDatabaseMonitorInfo GetEventDatabaseMonitor(ctx).Execute()

Returns monitoring information related to Event database of the environment.

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
	resp, r, err := apiClient.MonitorAPI.GetEventDatabaseMonitor(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetEventDatabaseMonitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEventDatabaseMonitor`: EventDatabaseMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetEventDatabaseMonitor`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetEventDatabaseMonitorRequest struct via the builder pattern


### Return type

[**EventDatabaseMonitorInfo**](EventDatabaseMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFarmMonitorInfo

> FarmMonitorInfo GetFarmMonitorInfo(ctx, id).Execute()

Gets monitoring information related to farm.

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
	resp, r, err := apiClient.MonitorAPI.GetFarmMonitorInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetFarmMonitorInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFarmMonitorInfo`: FarmMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetFarmMonitorInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetFarmMonitorInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FarmMonitorInfo**](FarmMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGatewayMonitorInfo

> GatewayMonitorInfoV2 GetGatewayMonitorInfo(ctx, id).Execute()

Gets monitoring information related to a Gateway.

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
	resp, r, err := apiClient.MonitorAPI.GetGatewayMonitorInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetGatewayMonitorInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGatewayMonitorInfo`: GatewayMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetGatewayMonitorInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGatewayMonitorInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GatewayMonitorInfoV2**](GatewayMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGatewayMonitorInfoV2

> GatewayMonitorInfoV3 GetGatewayMonitorInfoV2(ctx, id).Execute()

Gets monitoring information related to a Gateway.

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
	resp, r, err := apiClient.MonitorAPI.GetGatewayMonitorInfoV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetGatewayMonitorInfoV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGatewayMonitorInfoV2`: GatewayMonitorInfoV3
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetGatewayMonitorInfoV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGatewayMonitorInfoV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GatewayMonitorInfoV3**](GatewayMonitorInfoV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPodMonitorInfoV2

> PodMonitorInfoV2 GetPodMonitorInfoV2(ctx, id).Execute()

Gets monitoring information related to the remote pod.



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
	resp, r, err := apiClient.MonitorAPI.GetPodMonitorInfoV2(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetPodMonitorInfoV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPodMonitorInfoV2`: PodMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetPodMonitorInfoV2`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPodMonitorInfoV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PodMonitorInfoV2**](PodMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRDSServerMonitors

> RDSServerMonitorInfo GetRDSServerMonitors(ctx, id).Execute()

Gets monitoring information related to RDS Server.

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
	resp, r, err := apiClient.MonitorAPI.GetRDSServerMonitors(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetRDSServerMonitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRDSServerMonitors`: RDSServerMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetRDSServerMonitors`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRDSServerMonitorsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RDSServerMonitorInfo**](RDSServerMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSAMLAuthenticatorMonitorInfo

> SAMLAuthenticatorMonitorInfoV2 GetSAMLAuthenticatorMonitorInfo(ctx, id).Execute()

Gets Monitoring Information related to a SAML Authenticator

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
	resp, r, err := apiClient.MonitorAPI.GetSAMLAuthenticatorMonitorInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetSAMLAuthenticatorMonitorInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSAMLAuthenticatorMonitorInfo`: SAMLAuthenticatorMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetSAMLAuthenticatorMonitorInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSAMLAuthenticatorMonitorInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SAMLAuthenticatorMonitorInfoV2**](SAMLAuthenticatorMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrueSSOMonitorInfo

> TrueSSOMonitorInfo GetTrueSSOMonitorInfo(ctx, id).Execute()

Gets monitoring information related to a True SSO connector.

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
	resp, r, err := apiClient.MonitorAPI.GetTrueSSOMonitorInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetTrueSSOMonitorInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrueSSOMonitorInfo`: TrueSSOMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetTrueSSOMonitorInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTrueSSOMonitorInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TrueSSOMonitorInfo**](TrueSSOMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetViewComposerByVCId

> ViewComposerMonitorInfoV2 GetViewComposerByVCId(ctx, vcId).Execute()

View Composer is no longer supported from Horizon version 2012 onwards.

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
	vcId := "vcId_example" // string | vcId

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MonitorAPI.GetViewComposerByVCId(context.Background(), vcId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetViewComposerByVCId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetViewComposerByVCId`: ViewComposerMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetViewComposerByVCId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**vcId** | **string** | vcId | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetViewComposerByVCIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ViewComposerMonitorInfoV2**](ViewComposerMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVirtualCenterMonitorInfo

> VirtualCenterMonitorInfoV2 GetVirtualCenterMonitorInfo(ctx, id).Execute()

Gets monitoring information related to Virtual Center.

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
	resp, r, err := apiClient.MonitorAPI.GetVirtualCenterMonitorInfo(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.GetVirtualCenterMonitorInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVirtualCenterMonitorInfo`: VirtualCenterMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.GetVirtualCenterMonitorInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVirtualCenterMonitorInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**VirtualCenterMonitorInfoV2**](VirtualCenterMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADDomainMonitorInfosV2

> []ADDomainMonitorInfoV2 ListADDomainMonitorInfosV2(ctx).Execute()

Lists monitoring information related to AD Domains of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListADDomainMonitorInfosV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListADDomainMonitorInfosV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADDomainMonitorInfosV2`: []ADDomainMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListADDomainMonitorInfosV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListADDomainMonitorInfosV2Request struct via the builder pattern


### Return type

[**[]ADDomainMonitorInfoV2**](ADDomainMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADDomainMonitorInfosV3

> []ADDomainMonitorInfoV3 ListADDomainMonitorInfosV3(ctx).Execute()

Lists monitoring information related to AD Domains of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListADDomainMonitorInfosV3(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListADDomainMonitorInfosV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADDomainMonitorInfosV3`: []ADDomainMonitorInfoV3
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListADDomainMonitorInfosV3`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListADDomainMonitorInfosV3Request struct via the builder pattern


### Return type

[**[]ADDomainMonitorInfoV3**](ADDomainMonitorInfoV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListADDomainMonitors

> []ADDomainMonitorInfo ListADDomainMonitors(ctx).Execute()

Lists monitoring information related to AD Domains of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListADDomainMonitors(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListADDomainMonitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListADDomainMonitors`: []ADDomainMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListADDomainMonitors`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListADDomainMonitorsRequest struct via the builder pattern


### Return type

[**[]ADDomainMonitorInfo**](ADDomainMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAppVolumesManagerMonitorInfoV1

> []AppVolumesManagerMonitorInfo ListAppVolumesManagerMonitorInfoV1(ctx).Execute()

Lists monitoring information related to App volumes managers registered in the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListAppVolumesManagerMonitorInfoV1(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListAppVolumesManagerMonitorInfoV1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAppVolumesManagerMonitorInfoV1`: []AppVolumesManagerMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListAppVolumesManagerMonitorInfoV1`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListAppVolumesManagerMonitorInfoV1Request struct via the builder pattern


### Return type

[**[]AppVolumesManagerMonitorInfo**](AppVolumesManagerMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListConnectionServerMonitors

> []ConnectionServerMonitorInfo ListConnectionServerMonitors(ctx).Execute()

Lists monitoring information related to Connection Servers of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListConnectionServerMonitors(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListConnectionServerMonitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListConnectionServerMonitors`: []ConnectionServerMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListConnectionServerMonitors`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListConnectionServerMonitorsRequest struct via the builder pattern


### Return type

[**[]ConnectionServerMonitorInfo**](ConnectionServerMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListConnectionServerMonitorsV2

> []ConnectionServerMonitorInfoV2 ListConnectionServerMonitorsV2(ctx).Execute()

Lists monitoring information related to Connection Servers of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListConnectionServerMonitorsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListConnectionServerMonitorsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListConnectionServerMonitorsV2`: []ConnectionServerMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListConnectionServerMonitorsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListConnectionServerMonitorsV2Request struct via the builder pattern


### Return type

[**[]ConnectionServerMonitorInfoV2**](ConnectionServerMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListConnectionServerMonitorsV3

> []ConnectionServerMonitorInfoV3 ListConnectionServerMonitorsV3(ctx).Execute()

Lists monitoring information related to Connection Servers of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListConnectionServerMonitorsV3(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListConnectionServerMonitorsV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListConnectionServerMonitorsV3`: []ConnectionServerMonitorInfoV3
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListConnectionServerMonitorsV3`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListConnectionServerMonitorsV3Request struct via the builder pattern


### Return type

[**[]ConnectionServerMonitorInfoV3**](ConnectionServerMonitorInfoV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDesktopPoolMetrics

> []DesktopPoolMetricsInfo ListDesktopPoolMetrics(ctx).Ids(ids).Execute()

Lists metrics of desktop pools (except RDS desktop pools).



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
	ids := []string{"Inner_example"} // []string | Desktop pool IDs

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MonitorAPI.ListDesktopPoolMetrics(context.Background()).Ids(ids).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListDesktopPoolMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDesktopPoolMetrics`: []DesktopPoolMetricsInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListDesktopPoolMetrics`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDesktopPoolMetricsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ids** | **[]string** | Desktop pool IDs | 

### Return type

[**[]DesktopPoolMetricsInfo**](DesktopPoolMetricsInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListFarmMonitors

> []FarmMonitorInfo ListFarmMonitors(ctx).Execute()

Lists monitoring information related to Farms of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListFarmMonitors(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListFarmMonitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListFarmMonitors`: []FarmMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListFarmMonitors`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListFarmMonitorsRequest struct via the builder pattern


### Return type

[**[]FarmMonitorInfo**](FarmMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGatewayMonitorInfoV1

> []GatewayMonitorInfo ListGatewayMonitorInfoV1(ctx).Execute()

Lists monitoring information related to Gateways registered in the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListGatewayMonitorInfoV1(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListGatewayMonitorInfoV1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGatewayMonitorInfoV1`: []GatewayMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListGatewayMonitorInfoV1`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListGatewayMonitorInfoV1Request struct via the builder pattern


### Return type

[**[]GatewayMonitorInfo**](GatewayMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGatewayMonitorInfoV2

> []GatewayMonitorInfoV2 ListGatewayMonitorInfoV2(ctx).Execute()

Lists monitoring information related to Gateways registered in the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListGatewayMonitorInfoV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListGatewayMonitorInfoV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGatewayMonitorInfoV2`: []GatewayMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListGatewayMonitorInfoV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListGatewayMonitorInfoV2Request struct via the builder pattern


### Return type

[**[]GatewayMonitorInfoV2**](GatewayMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGatewayMonitorInfoV3

> []GatewayMonitorInfoV3 ListGatewayMonitorInfoV3(ctx).Execute()

Lists monitoring information related to Gateways registered in the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListGatewayMonitorInfoV3(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListGatewayMonitorInfoV3``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGatewayMonitorInfoV3`: []GatewayMonitorInfoV3
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListGatewayMonitorInfoV3`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListGatewayMonitorInfoV3Request struct via the builder pattern


### Return type

[**[]GatewayMonitorInfoV3**](GatewayMonitorInfoV3.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPodMonitorInfosV1

> []PodMonitorInfo ListPodMonitorInfosV1(ctx).Execute()

Lists monitoring information related to the remote pods.



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
	resp, r, err := apiClient.MonitorAPI.ListPodMonitorInfosV1(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListPodMonitorInfosV1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPodMonitorInfosV1`: []PodMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListPodMonitorInfosV1`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPodMonitorInfosV1Request struct via the builder pattern


### Return type

[**[]PodMonitorInfo**](PodMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPodMonitorInfosV2

> []PodMonitorInfoV2 ListPodMonitorInfosV2(ctx).Execute()

Lists monitoring information related to the remote pods.



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
	resp, r, err := apiClient.MonitorAPI.ListPodMonitorInfosV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListPodMonitorInfosV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPodMonitorInfosV2`: []PodMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListPodMonitorInfosV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPodMonitorInfosV2Request struct via the builder pattern


### Return type

[**[]PodMonitorInfoV2**](PodMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRDSServerMonitors

> []RDSServerMonitorInfo ListRDSServerMonitors(ctx).Execute()

Lists monitoring information related to RDS Servers of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListRDSServerMonitors(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListRDSServerMonitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRDSServerMonitors`: []RDSServerMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListRDSServerMonitors`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListRDSServerMonitorsRequest struct via the builder pattern


### Return type

[**[]RDSServerMonitorInfo**](RDSServerMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSAMLAuthenticatorMonitorsV1

> []SAMLAuthenticatorMonitorInfo ListSAMLAuthenticatorMonitorsV1(ctx).Execute()

Lists monitoring information related to SAML Authenticators of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListSAMLAuthenticatorMonitorsV1(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListSAMLAuthenticatorMonitorsV1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSAMLAuthenticatorMonitorsV1`: []SAMLAuthenticatorMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListSAMLAuthenticatorMonitorsV1`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListSAMLAuthenticatorMonitorsV1Request struct via the builder pattern


### Return type

[**[]SAMLAuthenticatorMonitorInfo**](SAMLAuthenticatorMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSAMLAuthenticatorMonitorsV2

> []SAMLAuthenticatorMonitorInfoV2 ListSAMLAuthenticatorMonitorsV2(ctx).Execute()

Lists monitoring information related to SAML Authenticators of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListSAMLAuthenticatorMonitorsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListSAMLAuthenticatorMonitorsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSAMLAuthenticatorMonitorsV2`: []SAMLAuthenticatorMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListSAMLAuthenticatorMonitorsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListSAMLAuthenticatorMonitorsV2Request struct via the builder pattern


### Return type

[**[]SAMLAuthenticatorMonitorInfoV2**](SAMLAuthenticatorMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTrueSSOMonitorInfos

> []TrueSSOMonitorInfo ListTrueSSOMonitorInfos(ctx).Execute()

Lists monitoring information related to True SSO connectors.

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
	resp, r, err := apiClient.MonitorAPI.ListTrueSSOMonitorInfos(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListTrueSSOMonitorInfos``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTrueSSOMonitorInfos`: []TrueSSOMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListTrueSSOMonitorInfos`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListTrueSSOMonitorInfosRequest struct via the builder pattern


### Return type

[**[]TrueSSOMonitorInfo**](TrueSSOMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListViewComposerMonitorsV1

> []ViewComposerMonitorInfo ListViewComposerMonitorsV1(ctx).Execute()

View Composer is no longer supported from Horizon version 2012 onwards.

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
	resp, r, err := apiClient.MonitorAPI.ListViewComposerMonitorsV1(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListViewComposerMonitorsV1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListViewComposerMonitorsV1`: []ViewComposerMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListViewComposerMonitorsV1`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListViewComposerMonitorsV1Request struct via the builder pattern


### Return type

[**[]ViewComposerMonitorInfo**](ViewComposerMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListViewComposerMonitorsV2

> []ViewComposerMonitorInfoV2 ListViewComposerMonitorsV2(ctx).Execute()

View Composer is no longer supported from Horizon version 2012 onwards.

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
	resp, r, err := apiClient.MonitorAPI.ListViewComposerMonitorsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListViewComposerMonitorsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListViewComposerMonitorsV2`: []ViewComposerMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListViewComposerMonitorsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListViewComposerMonitorsV2Request struct via the builder pattern


### Return type

[**[]ViewComposerMonitorInfoV2**](ViewComposerMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVirtualCenterMonitors

> []VirtualCenterMonitorInfo ListVirtualCenterMonitors(ctx).Execute()

Lists monitoring information related to Virtual Centers of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListVirtualCenterMonitors(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListVirtualCenterMonitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVirtualCenterMonitors`: []VirtualCenterMonitorInfo
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListVirtualCenterMonitors`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListVirtualCenterMonitorsRequest struct via the builder pattern


### Return type

[**[]VirtualCenterMonitorInfo**](VirtualCenterMonitorInfo.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVirtualCenterMonitorsV2

> []VirtualCenterMonitorInfoV2 ListVirtualCenterMonitorsV2(ctx).Execute()

Lists monitoring information related to Virtual Centers of the environment.

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
	resp, r, err := apiClient.MonitorAPI.ListVirtualCenterMonitorsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MonitorAPI.ListVirtualCenterMonitorsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVirtualCenterMonitorsV2`: []VirtualCenterMonitorInfoV2
	fmt.Fprintf(os.Stdout, "Response from `MonitorAPI.ListVirtualCenterMonitorsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListVirtualCenterMonitorsV2Request struct via the builder pattern


### Return type

[**[]VirtualCenterMonitorInfoV2**](VirtualCenterMonitorInfoV2.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

