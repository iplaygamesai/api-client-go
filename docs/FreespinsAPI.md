# \FreespinsAPI

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelAStandaloneFreespin**](FreespinsAPI.md#CancelAStandaloneFreespin) | **Post** /api/v1/freespins/{freespin_id}/cancel | Cancel a standalone freespin
[**CreateAStandaloneFreespin**](FreespinsAPI.md#CreateAStandaloneFreespin) | **Post** /api/v1/freespins | Create a standalone freespin



## CancelAStandaloneFreespin

> CancelAStandaloneFreespin200Response CancelAStandaloneFreespin(ctx, freespinId).CancelAStandaloneFreespinRequest(cancelAStandaloneFreespinRequest).Execute()

Cancel a standalone freespin



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	freespinId := "campaign_abc" // string | The freespin campaign ID.
	cancelAStandaloneFreespinRequest := *openapiclient.NewCancelAStandaloneFreespinRequest() // CancelAStandaloneFreespinRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreespinsAPI.CancelAStandaloneFreespin(context.Background(), freespinId).CancelAStandaloneFreespinRequest(cancelAStandaloneFreespinRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreespinsAPI.CancelAStandaloneFreespin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelAStandaloneFreespin`: CancelAStandaloneFreespin200Response
	fmt.Fprintf(os.Stdout, "Response from `FreespinsAPI.CancelAStandaloneFreespin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**freespinId** | **string** | The freespin campaign ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelAStandaloneFreespinRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cancelAStandaloneFreespinRequest** | [**CancelAStandaloneFreespinRequest**](CancelAStandaloneFreespinRequest.md) |  | 

### Return type

[**CancelAStandaloneFreespin200Response**](CancelAStandaloneFreespin200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAStandaloneFreespin

> CreateAStandaloneFreespin201Response CreateAStandaloneFreespin(ctx).CreateAStandaloneFreespinRequest(createAStandaloneFreespinRequest).Execute()

Create a standalone freespin



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	createAStandaloneFreespinRequest := *openapiclient.NewCreateAStandaloneFreespinRequest(int32(123), "player_456", "USD", "campaign_abc", int32(10)) // CreateAStandaloneFreespinRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreespinsAPI.CreateAStandaloneFreespin(context.Background()).CreateAStandaloneFreespinRequest(createAStandaloneFreespinRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreespinsAPI.CreateAStandaloneFreespin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAStandaloneFreespin`: CreateAStandaloneFreespin201Response
	fmt.Fprintf(os.Stdout, "Response from `FreespinsAPI.CreateAStandaloneFreespin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAStandaloneFreespinRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAStandaloneFreespinRequest** | [**CreateAStandaloneFreespinRequest**](CreateAStandaloneFreespinRequest.md) |  | 

### Return type

[**CreateAStandaloneFreespin201Response**](CreateAStandaloneFreespin201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

