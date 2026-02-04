# \MultiSessionsAPI

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EndMultiSession**](MultiSessionsAPI.md#EndMultiSession) | **Post** /api/v1/multi-sessions/{token}/end | End multi-session
[**GetMultiSessionStatus**](MultiSessionsAPI.md#GetMultiSessionStatus) | **Get** /api/v1/multi-sessions/{token}/status | Get multi-session status
[**StartAMultiSession**](MultiSessionsAPI.md#StartAMultiSession) | **Post** /api/v1/multi-sessions/start | Start a multi-session



## EndMultiSession

> EndMultiSession200Response EndMultiSession(ctx, token).Execute()

End multi-session



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	token := "550e8400-e29b-41d4-a716-446655440000" // string | The multi-session token.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MultiSessionsAPI.EndMultiSession(context.Background(), token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MultiSessionsAPI.EndMultiSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EndMultiSession`: EndMultiSession200Response
	fmt.Fprintf(os.Stdout, "Response from `MultiSessionsAPI.EndMultiSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**token** | **string** | The multi-session token. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEndMultiSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EndMultiSession200Response**](EndMultiSession200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMultiSessionStatus

> GetMultiSessionStatus200Response GetMultiSessionStatus(ctx, token).Execute()

Get multi-session status



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	token := "550e8400-e29b-41d4-a716-446655440000" // string | The multi-session token.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MultiSessionsAPI.GetMultiSessionStatus(context.Background(), token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MultiSessionsAPI.GetMultiSessionStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMultiSessionStatus`: GetMultiSessionStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `MultiSessionsAPI.GetMultiSessionStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**token** | **string** | The multi-session token. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMultiSessionStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetMultiSessionStatus200Response**](GetMultiSessionStatus200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartAMultiSession

> StartAMultiSession201Response StartAMultiSession(ctx).StartAMultiSessionRequest(startAMultiSessionRequest).Execute()

Start a multi-session



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	startAMultiSessionRequest := *openapiclient.NewStartAMultiSessionRequest("player_456", "USD", "US", "192.168.1.1") // StartAMultiSessionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MultiSessionsAPI.StartAMultiSession(context.Background()).StartAMultiSessionRequest(startAMultiSessionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MultiSessionsAPI.StartAMultiSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartAMultiSession`: StartAMultiSession201Response
	fmt.Fprintf(os.Stdout, "Response from `MultiSessionsAPI.StartAMultiSession`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStartAMultiSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startAMultiSessionRequest** | [**StartAMultiSessionRequest**](StartAMultiSessionRequest.md) |  | 

### Return type

[**StartAMultiSession201Response**](StartAMultiSession201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

