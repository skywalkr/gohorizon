# \AuthAPI

All URIs are relative to *http://localhost/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AuthenticateSmartCard**](AuthAPI.md#AuthenticateSmartCard) | **Get** /login | Logs in a user with smart card. Returns access and refresh tokens.
[**KeyAgreement**](AuthAPI.md#KeyAgreement) | **Post** /key-agreement | Uses Diffie-Hellman algorithm to achieve encryption key agreement between client and server, which then can be used to encrypt and decrypt sensitive information.
[**LoginUser**](AuthAPI.md#LoginUser) | **Post** /login | Logs in a user. Returns access token and refresh token.
[**LogoutUser**](AuthAPI.md#LogoutUser) | **Post** /logout | Logs out a user.
[**RefreshAccessToken**](AuthAPI.md#RefreshAccessToken) | **Post** /refresh | Refreshes access token from refresh token.



## AuthenticateSmartCard

> SmartCardAuthTokens AuthenticateSmartCard(ctx).AcceptLanguage(acceptLanguage).ClientReferenceId(clientReferenceId).Execute()

Logs in a user with smart card. Returns access and refresh tokens.



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
	acceptLanguage := "acceptLanguage_example" // string | Accept-Language (optional)
	clientReferenceId := "clientReferenceId_example" // string | client_reference_id (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.AuthenticateSmartCard(context.Background()).AcceptLanguage(acceptLanguage).ClientReferenceId(clientReferenceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.AuthenticateSmartCard``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AuthenticateSmartCard`: SmartCardAuthTokens
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.AuthenticateSmartCard`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAuthenticateSmartCardRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLanguage** | **string** | Accept-Language | 
 **clientReferenceId** | **string** | client_reference_id | 

### Return type

[**SmartCardAuthTokens**](SmartCardAuthTokens.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeyAgreement

> ServerKeyDerivationInfo KeyAgreement(ctx).Body(body).Execute()

Uses Diffie-Hellman algorithm to achieve encryption key agreement between client and server, which then can be used to encrypt and decrypt sensitive information.

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
	body := *openapiclient.NewClientKeyDerivationSpec(string(V2luZG93c0xPQ0FUSU9OSUQ6NTIyNTI0NTM0NTM0NjM0MzQ2MzYzNDYzNjc1MzI0NjUyMzY3NDUyNzY1NDIzNjc1NDY3MjM1NDI0Mw==), string(DaY+kne1X2B6h8a4gLZu2w==), string(<public key>), []string{"SupportedSchemes_example"}) // ClientKeyDerivationSpec | Client key derivation spec.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.KeyAgreement(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.KeyAgreement``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeyAgreement`: ServerKeyDerivationInfo
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.KeyAgreement`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiKeyAgreementRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ClientKeyDerivationSpec**](ClientKeyDerivationSpec.md) | Client key derivation spec. | 

### Return type

[**ServerKeyDerivationInfo**](ServerKeyDerivationInfo.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LoginUser

> AuthTokens LoginUser(ctx).Body(body).AcceptLanguage(acceptLanguage).ClientReferenceId(clientReferenceId).Execute()

Logs in a user. Returns access token and refresh token.



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
	body := *openapiclient.NewAuthLogin("AD-TEST-DOMAIN", []string{"Password_example"}, "Administrator") // AuthLogin | Login credentials needed for Authentication
	acceptLanguage := "acceptLanguage_example" // string | Header to support localization. (optional) (default to "en")
	clientReferenceId := "clientReferenceId_example" // string | Client reference identifier present in the response of key-agreement api. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.LoginUser(context.Background()).Body(body).AcceptLanguage(acceptLanguage).ClientReferenceId(clientReferenceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.LoginUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LoginUser`: AuthTokens
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.LoginUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLoginUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthLogin**](AuthLogin.md) | Login credentials needed for Authentication | 
 **acceptLanguage** | **string** | Header to support localization. | [default to &quot;en&quot;]
 **clientReferenceId** | **string** | Client reference identifier present in the response of key-agreement api. | 

### Return type

[**AuthTokens**](AuthTokens.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LogoutUser

> LogoutUser(ctx).Body(body).Execute()

Logs out a user.

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
	body := *openapiclient.NewRefreshToken("<jwt.refresh.token>") // RefreshToken | Refresh token needed for Logout

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AuthAPI.LogoutUser(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.LogoutUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLogoutUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**RefreshToken**](RefreshToken.md) | Refresh token needed for Logout | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefreshAccessToken

> AccessToken RefreshAccessToken(ctx).Body(body).Execute()

Refreshes access token from refresh token.

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
	body := *openapiclient.NewRefreshToken("<jwt.refresh.token>") // RefreshToken | Refresh token needed to generate new Access Token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthAPI.RefreshAccessToken(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthAPI.RefreshAccessToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefreshAccessToken`: AccessToken
	fmt.Fprintf(os.Stdout, "Response from `AuthAPI.RefreshAccessToken`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRefreshAccessTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**RefreshToken**](RefreshToken.md) | Refresh token needed to generate new Access Token | 

### Return type

[**AccessToken**](AccessToken.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

