# \GamesAPI

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetApiV1GamesId**](GamesAPI.md#GetApiV1GamesId) | **Get** /api/v1/games/{id} | 
[**ListGames**](GamesAPI.md#ListGames) | **Get** /api/v1/games | List games



## GetApiV1GamesId

> GetApiV1GamesId(ctx, id).Execute()





### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "architecto" // string | The ID of the game.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GamesAPI.GetApiV1GamesId(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GamesAPI.GetApiV1GamesId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the game. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetApiV1GamesIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGames

> ListGames200Response ListGames(ctx).Search(search).ProducerId(producerId).Provider(provider).Type_(type_).PerPage(perPage).ListGamesRequest(listGamesRequest).Execute()

List games



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	search := "sweet bonanza" // string | Search games by name. (optional)
	producerId := int32(1) // int32 | Filter by producer ID. (optional)
	provider := "nuxgaming" // string | Filter by provider slug. (optional)
	type_ := "slot" // string | Filter by game type. (optional)
	perPage := "20" // string | Number of results per page or \"all\" for all results. (optional)
	listGamesRequest := *openapiclient.NewListGamesRequest() // ListGamesRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GamesAPI.ListGames(context.Background()).Search(search).ProducerId(producerId).Provider(provider).Type_(type_).PerPage(perPage).ListGamesRequest(listGamesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GamesAPI.ListGames``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGames`: ListGames200Response
	fmt.Fprintf(os.Stdout, "Response from `GamesAPI.ListGames`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGamesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **search** | **string** | Search games by name. | 
 **producerId** | **int32** | Filter by producer ID. | 
 **provider** | **string** | Filter by provider slug. | 
 **type_** | **string** | Filter by game type. | 
 **perPage** | **string** | Number of results per page or \&quot;all\&quot; for all results. | 
 **listGamesRequest** | [**ListGamesRequest**](ListGamesRequest.md) |  | 

### Return type

[**ListGames200Response**](ListGames200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

