# \WidgetManagementAPI

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkRevokeTokens**](WidgetManagementAPI.md#BulkRevokeTokens) | **Post** /api/v1/widget/tokens/bulk-revoke | Bulk revoke tokens
[**GenerateAWidgetToken**](WidgetManagementAPI.md#GenerateAWidgetToken) | **Post** /api/v1/widget/tokens | Generate a widget token
[**GetDomainDetails**](WidgetManagementAPI.md#GetDomainDetails) | **Get** /api/v1/widget/domains/{id} | Get domain details
[**GetTokenDetails**](WidgetManagementAPI.md#GetTokenDetails) | **Get** /api/v1/widget/tokens/{id} | Get token details
[**ListRegisteredDomains**](WidgetManagementAPI.md#ListRegisteredDomains) | **Get** /api/v1/widget/domains | List registered domains
[**ListWidgetTokens**](WidgetManagementAPI.md#ListWidgetTokens) | **Get** /api/v1/widget/tokens | List widget tokens
[**RegenerateDomainToken**](WidgetManagementAPI.md#RegenerateDomainToken) | **Post** /api/v1/widget/domains/{id}/regenerate-token | Regenerate domain token
[**RegisterANewDomain**](WidgetManagementAPI.md#RegisterANewDomain) | **Post** /api/v1/widget/domains | Register a new domain
[**RemoveADomain**](WidgetManagementAPI.md#RemoveADomain) | **Delete** /api/v1/widget/domains/{id} | Remove a domain
[**RevokeAToken**](WidgetManagementAPI.md#RevokeAToken) | **Delete** /api/v1/widget/tokens/{id} | Revoke a token
[**UpdateDomainSettings**](WidgetManagementAPI.md#UpdateDomainSettings) | **Put** /api/v1/widget/domains/{id} | Update domain settings



## BulkRevokeTokens

> BulkRevokeTokens200Response BulkRevokeTokens(ctx).BulkRevokeTokensRequest(bulkRevokeTokensRequest).Execute()

Bulk revoke tokens



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
	bulkRevokeTokensRequest := *openapiclient.NewBulkRevokeTokensRequest([]string{"TokenIds_example"}) // BulkRevokeTokensRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.BulkRevokeTokens(context.Background()).BulkRevokeTokensRequest(bulkRevokeTokensRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.BulkRevokeTokens``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkRevokeTokens`: BulkRevokeTokens200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.BulkRevokeTokens`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkRevokeTokensRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkRevokeTokensRequest** | [**BulkRevokeTokensRequest**](BulkRevokeTokensRequest.md) |  | 

### Return type

[**BulkRevokeTokens200Response**](BulkRevokeTokens200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateAWidgetToken

> GenerateAWidgetToken201Response GenerateAWidgetToken(ctx).GenerateAWidgetTokenRequest(generateAWidgetTokenRequest).Execute()

Generate a widget token



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
	generateAWidgetTokenRequest := *openapiclient.NewGenerateAWidgetTokenRequest("abc123...") // GenerateAWidgetTokenRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.GenerateAWidgetToken(context.Background()).GenerateAWidgetTokenRequest(generateAWidgetTokenRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.GenerateAWidgetToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateAWidgetToken`: GenerateAWidgetToken201Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.GenerateAWidgetToken`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateAWidgetTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateAWidgetTokenRequest** | [**GenerateAWidgetTokenRequest**](GenerateAWidgetTokenRequest.md) |  | 

### Return type

[**GenerateAWidgetToken201Response**](GenerateAWidgetToken201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDomainDetails

> GetDomainDetails200Response GetDomainDetails(ctx, id).Execute()

Get domain details



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
	id := int32(1) // int32 | The domain ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.GetDomainDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.GetDomainDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDomainDetails`: GetDomainDetails200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.GetDomainDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The domain ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDomainDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetDomainDetails200Response**](GetDomainDetails200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTokenDetails

> GetTokenDetails200Response GetTokenDetails(ctx, id).Execute()

Get token details



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
	id := int32(1) // int32 | The token ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.GetTokenDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.GetTokenDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTokenDetails`: GetTokenDetails200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.GetTokenDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The token ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTokenDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetTokenDetails200Response**](GetTokenDetails200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRegisteredDomains

> ListRegisteredDomains200Response ListRegisteredDomains(ctx).Execute()

List registered domains



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
	resp, r, err := apiClient.WidgetManagementAPI.ListRegisteredDomains(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.ListRegisteredDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRegisteredDomains`: ListRegisteredDomains200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.ListRegisteredDomains`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListRegisteredDomainsRequest struct via the builder pattern


### Return type

[**ListRegisteredDomains200Response**](ListRegisteredDomains200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWidgetTokens

> ListWidgetTokens200Response ListWidgetTokens(ctx).DomainId(domainId).Active(active).Execute()

List widget tokens



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
	domainId := int32(1) // int32 | optional Filter by domain ID. (optional)
	active := true // bool | optional Filter by active status. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.ListWidgetTokens(context.Background()).DomainId(domainId).Active(active).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.ListWidgetTokens``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWidgetTokens`: ListWidgetTokens200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.ListWidgetTokens`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListWidgetTokensRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainId** | **int32** | optional Filter by domain ID. | 
 **active** | **bool** | optional Filter by active status. | 

### Return type

[**ListWidgetTokens200Response**](ListWidgetTokens200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegenerateDomainToken

> RegenerateDomainToken200Response RegenerateDomainToken(ctx, id).Execute()

Regenerate domain token



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
	id := int32(1) // int32 | The domain ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.RegenerateDomainToken(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.RegenerateDomainToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegenerateDomainToken`: RegenerateDomainToken200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.RegenerateDomainToken`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The domain ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegenerateDomainTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RegenerateDomainToken200Response**](RegenerateDomainToken200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegisterANewDomain

> RegisterANewDomain201Response RegisterANewDomain(ctx).RegisterANewDomainRequest(registerANewDomainRequest).Execute()

Register a new domain



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
	registerANewDomainRequest := *openapiclient.NewRegisterANewDomainRequest("casino.example.com") // RegisterANewDomainRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.RegisterANewDomain(context.Background()).RegisterANewDomainRequest(registerANewDomainRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.RegisterANewDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterANewDomain`: RegisterANewDomain201Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.RegisterANewDomain`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterANewDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **registerANewDomainRequest** | [**RegisterANewDomainRequest**](RegisterANewDomainRequest.md) |  | 

### Return type

[**RegisterANewDomain201Response**](RegisterANewDomain201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveADomain

> RemoveADomain200Response RemoveADomain(ctx, id).Execute()

Remove a domain



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
	id := int32(1) // int32 | The domain ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.RemoveADomain(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.RemoveADomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveADomain`: RemoveADomain200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.RemoveADomain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The domain ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveADomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RemoveADomain200Response**](RemoveADomain200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeAToken

> RevokeAToken200Response RevokeAToken(ctx, id).Execute()

Revoke a token



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
	id := int32(1) // int32 | The token ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.RevokeAToken(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.RevokeAToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeAToken`: RevokeAToken200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.RevokeAToken`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The token ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeATokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RevokeAToken200Response**](RevokeAToken200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDomainSettings

> UpdateDomainSettings200Response UpdateDomainSettings(ctx, id).UpdateDomainSettingsRequest(updateDomainSettingsRequest).Execute()

Update domain settings



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
	id := int32(1) // int32 | The domain ID.
	updateDomainSettingsRequest := *openapiclient.NewUpdateDomainSettingsRequest() // UpdateDomainSettingsRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetManagementAPI.UpdateDomainSettings(context.Background(), id).UpdateDomainSettingsRequest(updateDomainSettingsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetManagementAPI.UpdateDomainSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDomainSettings`: UpdateDomainSettings200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetManagementAPI.UpdateDomainSettings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The domain ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDomainSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDomainSettingsRequest** | [**UpdateDomainSettingsRequest**](UpdateDomainSettingsRequest.md) |  | 

### Return type

[**UpdateDomainSettings200Response**](UpdateDomainSettings200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

