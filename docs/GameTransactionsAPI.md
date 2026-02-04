# \GameTransactionsAPI

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetTransactionDetails**](GameTransactionsAPI.md#GetTransactionDetails) | **Get** /api/v1/game-transactions/{id} | Get transaction details
[**GetTransactionHistory**](GameTransactionsAPI.md#GetTransactionHistory) | **Get** /api/v1/game-transactions | Get transaction history



## GetTransactionDetails

> string GetTransactionDetails(ctx, id).Execute()

Get transaction details



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := int32(789) // int32 | The ID of the transaction.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GameTransactionsAPI.GetTransactionDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GameTransactionsAPI.GetTransactionDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTransactionDetails`: string
	fmt.Fprintf(os.Stdout, "Response from `GameTransactionsAPI.GetTransactionDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | The ID of the transaction. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTransactionDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTransactionHistory

> GetTransactionHistory200Response GetTransactionHistory(ctx).PlayerId(playerId).GameId(gameId).Type_(type_).FromDate(fromDate).ToDate(toDate).Limit(limit).Offset(offset).Execute()

Get transaction history



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	playerId := "player_456" // string | Filter by player ID. (optional)
	gameId := int32(123) // int32 | Filter by game ID. (optional)
	type_ := "bet" // string | Filter by transaction type (bet, win, rollback). (optional)
	fromDate := "2024-01-01T00:00:00Z" // string | Filter transactions from date (ISO 8601). (optional)
	toDate := "2024-01-31T23:59:59Z" // string | Filter transactions to date (ISO 8601). (optional)
	limit := int32(50) // int32 | Number of results per page. Default: 100. (optional)
	offset := int32(100) // int32 | Number of results to skip. Default: 0. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GameTransactionsAPI.GetTransactionHistory(context.Background()).PlayerId(playerId).GameId(gameId).Type_(type_).FromDate(fromDate).ToDate(toDate).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GameTransactionsAPI.GetTransactionHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTransactionHistory`: GetTransactionHistory200Response
	fmt.Fprintf(os.Stdout, "Response from `GameTransactionsAPI.GetTransactionHistory`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTransactionHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **playerId** | **string** | Filter by player ID. | 
 **gameId** | **int32** | Filter by game ID. | 
 **type_** | **string** | Filter by transaction type (bet, win, rollback). | 
 **fromDate** | **string** | Filter transactions from date (ISO 8601). | 
 **toDate** | **string** | Filter transactions to date (ISO 8601). | 
 **limit** | **int32** | Number of results per page. Default: 100. | 
 **offset** | **int32** | Number of results to skip. Default: 0. | 

### Return type

[**GetTransactionHistory200Response**](GetTransactionHistory200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

