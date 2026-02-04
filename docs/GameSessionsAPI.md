# \GameSessionsAPI

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EndAGameSession**](GameSessionsAPI.md#EndAGameSession) | **Post** /api/v1/game-sessions/{session_id}/end | End a game session
[**GetSessionStatus**](GameSessionsAPI.md#GetSessionStatus) | **Get** /api/v1/game-sessions/{session_id}/status | Get session status
[**StartAGameSession**](GameSessionsAPI.md#StartAGameSession) | **Post** /api/v1/game-sessions/start | Start a game session



## EndAGameSession

> EndAGameSession200Response EndAGameSession(ctx, sessionId).Execute()

End a game session



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	sessionId := "abc123" // string | The session ID to end.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GameSessionsAPI.EndAGameSession(context.Background(), sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GameSessionsAPI.EndAGameSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EndAGameSession`: EndAGameSession200Response
	fmt.Fprintf(os.Stdout, "Response from `GameSessionsAPI.EndAGameSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** | The session ID to end. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEndAGameSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EndAGameSession200Response**](EndAGameSession200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSessionStatus

> GetSessionStatus200Response GetSessionStatus(ctx, sessionId).Execute()

Get session status



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	sessionId := "abc123" // string | The session ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GameSessionsAPI.GetSessionStatus(context.Background(), sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GameSessionsAPI.GetSessionStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSessionStatus`: GetSessionStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `GameSessionsAPI.GetSessionStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** | The session ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSessionStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetSessionStatus200Response**](GetSessionStatus200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartAGameSession

> StartAGameSession201Response StartAGameSession(ctx).StartAGameSessionRequest(startAGameSessionRequest).Execute()

Start a game session



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	startAGameSessionRequest := *openapiclient.NewStartAGameSessionRequest(int32(123), "player_456", "USD", "192.168.1.1", "US") // StartAGameSessionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GameSessionsAPI.StartAGameSession(context.Background()).StartAGameSessionRequest(startAGameSessionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GameSessionsAPI.StartAGameSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartAGameSession`: StartAGameSession201Response
	fmt.Fprintf(os.Stdout, "Response from `GameSessionsAPI.StartAGameSession`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStartAGameSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startAGameSessionRequest** | [**StartAGameSessionRequest**](StartAGameSessionRequest.md) |  | 

### Return type

[**StartAGameSession201Response**](StartAGameSession201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

