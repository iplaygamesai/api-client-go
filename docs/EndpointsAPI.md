# \EndpointsAPI

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddAContributionToAJackpotPool**](EndpointsAPI.md#AddAContributionToAJackpotPool) | **Post** /api/v1/jackpot/contribute | Add a contribution to a jackpot pool
[**AddGamesToAJackpotPoolType**](EndpointsAPI.md#AddGamesToAJackpotPoolType) | **Post** /api/v1/jackpot/games | Add games to a jackpot pool type
[**BulkCreateExternalGamesFromJSONArray**](EndpointsAPI.md#BulkCreateExternalGamesFromJSONArray) | **Post** /api/v1/external-games/bulk | Bulk create external games from JSON array
[**BulkDeleteExternalGamesByIDs**](EndpointsAPI.md#BulkDeleteExternalGamesByIDs) | **Delete** /api/v1/external-games/bulk | Bulk delete external games by IDs
[**ConfigureJackpotSettingsForTheOperator**](EndpointsAPI.md#ConfigureJackpotSettingsForTheOperator) | **Post** /api/v1/jackpot/configure | Configure jackpot settings for the operator
[**ConfigureLiveModeSettingsForAPool**](EndpointsAPI.md#ConfigureLiveModeSettingsForAPool) | **Put** /api/v1/jackpot/pools/{poolId}/live-mode | Configure live mode settings for a pool
[**CreateANewPromotion**](EndpointsAPI.md#CreateANewPromotion) | **Post** /api/v1/promotions | Create a new promotion
[**CreateASingleExternalGame**](EndpointsAPI.md#CreateASingleExternalGame) | **Post** /api/v1/external-games | Create a single external game
[**CreateATargetedPlayerConfiguration**](EndpointsAPI.md#CreateATargetedPlayerConfiguration) | **Post** /api/v1/jackpot/targeted-players | Create a targeted player configuration
[**DeactivateATargetedPlayerConfiguration**](EndpointsAPI.md#DeactivateATargetedPlayerConfiguration) | **Delete** /api/v1/jackpot/targeted-players/{targetedPlayerId} | Deactivate a targeted player configuration
[**DeleteAPromotion**](EndpointsAPI.md#DeleteAPromotion) | **Delete** /api/v1/promotions/{id} | Delete a promotion
[**DeleteAnExternalGame**](EndpointsAPI.md#DeleteAnExternalGame) | **Delete** /api/v1/external-games/{id} | Delete an external game
[**GetASingleExternalGame**](EndpointsAPI.md#GetASingleExternalGame) | **Get** /api/v1/external-games/{id} | Get a single external game
[**GetASpecificPromotion**](EndpointsAPI.md#GetASpecificPromotion) | **Get** /api/v1/promotions/{id} | Get a specific promotion
[**GetApiV1Producers**](EndpointsAPI.md#GetApiV1Producers) | **Get** /api/v1/producers | 
[**GetApiV1ProducersId**](EndpointsAPI.md#GetApiV1ProducersId) | **Get** /api/v1/producers/{id} | 
[**GetApiV1TransactionExportsExportIdDownload**](EndpointsAPI.md#GetApiV1TransactionExportsExportIdDownload) | **Get** /api/v1/transaction-exports/{export_id}/download | 
[**GetCurrentConfigurationWithGames**](EndpointsAPI.md#GetCurrentConfigurationWithGames) | **Get** /api/v1/jackpot/configuration | Get current configuration with games
[**GetGamesForAPoolTypeOrAllPoolTypes**](EndpointsAPI.md#GetGamesForAPoolTypeOrAllPoolTypes) | **Get** /api/v1/jackpot/games | Get games for a pool type or all pool types
[**GetLeaderboardForAPromotion**](EndpointsAPI.md#GetLeaderboardForAPromotion) | **Get** /api/v1/promotions/{id}/leaderboard | Get leaderboard for a promotion
[**GetPlayerContributionHistory**](EndpointsAPI.md#GetPlayerContributionHistory) | **Get** /api/v1/jackpot/contributions | Get player contribution history
[**GetPoolDetails**](EndpointsAPI.md#GetPoolDetails) | **Get** /api/v1/jackpot/pools/{poolId} | Get pool details
[**GetPoolWinners**](EndpointsAPI.md#GetPoolWinners) | **Get** /api/v1/jackpot/pools/{poolId}/winners | Get pool winners
[**GetTargetedPlayerDetails**](EndpointsAPI.md#GetTargetedPlayerDetails) | **Get** /api/v1/jackpot/targeted-players/{targetedPlayerId} | Get targeted player details
[**GetUniqueProducerNamesForFiltering**](EndpointsAPI.md#GetUniqueProducerNamesForFiltering) | **Get** /api/v1/external-games/producers | Get unique producer names for filtering
[**GetWinnersForAPromotion**](EndpointsAPI.md#GetWinnersForAPromotion) | **Get** /api/v1/promotions/{id}/winners | Get winners for a promotion
[**ImportExternalGamesFromCSVFile**](EndpointsAPI.md#ImportExternalGamesFromCSVFile) | **Post** /api/v1/external-games/import/csv | Import external games from CSV file
[**ImportExternalGamesFromJSONPaste**](EndpointsAPI.md#ImportExternalGamesFromJSONPaste) | **Post** /api/v1/external-games/import/json | Import external games from JSON paste
[**ListExternalGamesForOperator**](EndpointsAPI.md#ListExternalGamesForOperator) | **Get** /api/v1/external-games | List external games for operator
[**ListOperatorsJackpotPools**](EndpointsAPI.md#ListOperatorsJackpotPools) | **Get** /api/v1/jackpot/pools | List operator&#39;s jackpot pools
[**ListPromotionsForTheOperator**](EndpointsAPI.md#ListPromotionsForTheOperator) | **Get** /api/v1/promotions | List promotions for the operator
[**ListTargetedPlayersForOperator**](EndpointsAPI.md#ListTargetedPlayersForOperator) | **Get** /api/v1/jackpot/targeted-players | List targeted players for operator
[**ManageGamesForAPromotion**](EndpointsAPI.md#ManageGamesForAPromotion) | **Post** /api/v1/promotions/{id}/games | Manage games for a promotion
[**ManuallyDistributePrizesForAPeriod**](EndpointsAPI.md#ManuallyDistributePrizesForAPeriod) | **Post** /api/v1/promotions/{id}/periods/{periodId}/distribute | Manually distribute prizes for a period
[**ManuallyTriggerPoolRelease**](EndpointsAPI.md#ManuallyTriggerPoolRelease) | **Post** /api/v1/jackpot/pools/{poolId}/release | Manually trigger pool release
[**OptInOperatorToAPlatformnetworkPromotion**](EndpointsAPI.md#OptInOperatorToAPlatformnetworkPromotion) | **Post** /api/v1/promotions/{id}/opt-in | Opt-in operator to a platform/network promotion
[**OptOutOperatorFromAPlatformnetworkPromotion**](EndpointsAPI.md#OptOutOperatorFromAPlatformnetworkPromotion) | **Post** /api/v1/promotions/{id}/opt-out | Opt-out operator from a platform/network promotion
[**PostApiV1GameTransactionsExport**](EndpointsAPI.md#PostApiV1GameTransactionsExport) | **Post** /api/v1/game-transactions/export | 
[**RemoveGamesFromAJackpotPoolType**](EndpointsAPI.md#RemoveGamesFromAJackpotPoolType) | **Delete** /api/v1/jackpot/games | Remove games from a jackpot pool type
[**SetGrandPrizeExpirationDate**](EndpointsAPI.md#SetGrandPrizeExpirationDate) | **Put** /api/v1/jackpot/pools/{poolId}/expiration | Set grand prize expiration date
[**UpdateAPromotion**](EndpointsAPI.md#UpdateAPromotion) | **Put** /api/v1/promotions/{id} | Update a promotion
[**UpdateAnExternalGame**](EndpointsAPI.md#UpdateAnExternalGame) | **Put** /api/v1/external-games/{id} | Update an external game



## AddAContributionToAJackpotPool

> AddAContributionToAJackpotPool(ctx).AddAContributionToAJackpotPoolRequest(addAContributionToAJackpotPoolRequest).Execute()

Add a contribution to a jackpot pool



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
	addAContributionToAJackpotPoolRequest := *openapiclient.NewAddAContributionToAJackpotPoolRequest("b", "ngz", float32(17), "weekly", "i") // AddAContributionToAJackpotPoolRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.AddAContributionToAJackpotPool(context.Background()).AddAContributionToAJackpotPoolRequest(addAContributionToAJackpotPoolRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.AddAContributionToAJackpotPool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddAContributionToAJackpotPoolRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addAContributionToAJackpotPoolRequest** | [**AddAContributionToAJackpotPoolRequest**](AddAContributionToAJackpotPoolRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddGamesToAJackpotPoolType

> AddGamesToAJackpotPoolType(ctx).AddGamesToAJackpotPoolTypeRequest(addGamesToAJackpotPoolTypeRequest).Execute()

Add games to a jackpot pool type



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
	addGamesToAJackpotPoolTypeRequest := *openapiclient.NewAddGamesToAJackpotPoolTypeRequest("grand_prize") // AddGamesToAJackpotPoolTypeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.AddGamesToAJackpotPoolType(context.Background()).AddGamesToAJackpotPoolTypeRequest(addGamesToAJackpotPoolTypeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.AddGamesToAJackpotPoolType``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddGamesToAJackpotPoolTypeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addGamesToAJackpotPoolTypeRequest** | [**AddGamesToAJackpotPoolTypeRequest**](AddGamesToAJackpotPoolTypeRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BulkCreateExternalGamesFromJSONArray

> BulkCreateExternalGamesFromJSONArray(ctx).BulkCreateExternalGamesFromJSONArrayRequest(bulkCreateExternalGamesFromJSONArrayRequest).Execute()

Bulk create external games from JSON array



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
	bulkCreateExternalGamesFromJSONArrayRequest := *openapiclient.NewBulkCreateExternalGamesFromJSONArrayRequest([]openapiclient.CreateASingleExternalGameRequest{*openapiclient.NewCreateASingleExternalGameRequest("b", "n")}) // BulkCreateExternalGamesFromJSONArrayRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.BulkCreateExternalGamesFromJSONArray(context.Background()).BulkCreateExternalGamesFromJSONArrayRequest(bulkCreateExternalGamesFromJSONArrayRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.BulkCreateExternalGamesFromJSONArray``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkCreateExternalGamesFromJSONArrayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkCreateExternalGamesFromJSONArrayRequest** | [**BulkCreateExternalGamesFromJSONArrayRequest**](BulkCreateExternalGamesFromJSONArrayRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BulkDeleteExternalGamesByIDs

> BulkDeleteExternalGamesByIDs(ctx).BulkDeleteExternalGamesByIDsRequest(bulkDeleteExternalGamesByIDsRequest).Execute()

Bulk delete external games by IDs



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
	bulkDeleteExternalGamesByIDsRequest := *openapiclient.NewBulkDeleteExternalGamesByIDsRequest() // BulkDeleteExternalGamesByIDsRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.BulkDeleteExternalGamesByIDs(context.Background()).BulkDeleteExternalGamesByIDsRequest(bulkDeleteExternalGamesByIDsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.BulkDeleteExternalGamesByIDs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkDeleteExternalGamesByIDsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkDeleteExternalGamesByIDsRequest** | [**BulkDeleteExternalGamesByIDsRequest**](BulkDeleteExternalGamesByIDsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureJackpotSettingsForTheOperator

> ConfigureJackpotSettingsForTheOperator(ctx).ConfigureJackpotSettingsForTheOperatorRequest(configureJackpotSettingsForTheOperatorRequest).Execute()

Configure jackpot settings for the operator



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
	configureJackpotSettingsForTheOperatorRequest := *openapiclient.NewConfigureJackpotSettingsForTheOperatorRequest() // ConfigureJackpotSettingsForTheOperatorRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ConfigureJackpotSettingsForTheOperator(context.Background()).ConfigureJackpotSettingsForTheOperatorRequest(configureJackpotSettingsForTheOperatorRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ConfigureJackpotSettingsForTheOperator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiConfigureJackpotSettingsForTheOperatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **configureJackpotSettingsForTheOperatorRequest** | [**ConfigureJackpotSettingsForTheOperatorRequest**](ConfigureJackpotSettingsForTheOperatorRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfigureLiveModeSettingsForAPool

> ConfigureLiveModeSettingsForAPool(ctx, poolId).ConfigureLiveModeSettingsForAPoolRequest(configureLiveModeSettingsForAPoolRequest).Execute()

Configure live mode settings for a pool



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
	poolId := "architecto" // string | 
	configureLiveModeSettingsForAPoolRequest := *openapiclient.NewConfigureLiveModeSettingsForAPoolRequest(false) // ConfigureLiveModeSettingsForAPoolRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ConfigureLiveModeSettingsForAPool(context.Background(), poolId).ConfigureLiveModeSettingsForAPoolRequest(configureLiveModeSettingsForAPoolRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ConfigureLiveModeSettingsForAPool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfigureLiveModeSettingsForAPoolRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **configureLiveModeSettingsForAPoolRequest** | [**ConfigureLiveModeSettingsForAPoolRequest**](ConfigureLiveModeSettingsForAPoolRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateANewPromotion

> CreateANewPromotion(ctx).CreateANewPromotionRequest(createANewPromotionRequest).Execute()

Create a new promotion



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
	createANewPromotionRequest := *openapiclient.NewCreateANewPromotionRequest("b", "architecto", "architecto") // CreateANewPromotionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.CreateANewPromotion(context.Background()).CreateANewPromotionRequest(createANewPromotionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.CreateANewPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateANewPromotionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createANewPromotionRequest** | [**CreateANewPromotionRequest**](CreateANewPromotionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateASingleExternalGame

> CreateASingleExternalGame(ctx).CreateASingleExternalGameRequest(createASingleExternalGameRequest).Execute()

Create a single external game



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
	createASingleExternalGameRequest := *openapiclient.NewCreateASingleExternalGameRequest("b", "n") // CreateASingleExternalGameRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.CreateASingleExternalGame(context.Background()).CreateASingleExternalGameRequest(createASingleExternalGameRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.CreateASingleExternalGame``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateASingleExternalGameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createASingleExternalGameRequest** | [**CreateASingleExternalGameRequest**](CreateASingleExternalGameRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateATargetedPlayerConfiguration

> CreateATargetedPlayerConfiguration(ctx).CreateATargetedPlayerConfigurationRequest(createATargetedPlayerConfigurationRequest).Execute()

Create a targeted player configuration



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
	createATargetedPlayerConfigurationRequest := *openapiclient.NewCreateATargetedPlayerConfigurationRequest("b", "mini", "ngz", float32(27)) // CreateATargetedPlayerConfigurationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.CreateATargetedPlayerConfiguration(context.Background()).CreateATargetedPlayerConfigurationRequest(createATargetedPlayerConfigurationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.CreateATargetedPlayerConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateATargetedPlayerConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createATargetedPlayerConfigurationRequest** | [**CreateATargetedPlayerConfigurationRequest**](CreateATargetedPlayerConfigurationRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeactivateATargetedPlayerConfiguration

> DeactivateATargetedPlayerConfiguration(ctx, targetedPlayerId).Execute()

Deactivate a targeted player configuration



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
	targetedPlayerId := "architecto" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.DeactivateATargetedPlayerConfiguration(context.Background(), targetedPlayerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.DeactivateATargetedPlayerConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**targetedPlayerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeactivateATargetedPlayerConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAPromotion

> DeleteAPromotion(ctx, id).Execute()

Delete a promotion



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
	id := "architecto" // string | The ID of the promotion.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.DeleteAPromotion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.DeleteAPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAPromotionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAnExternalGame

> DeleteAnExternalGame(ctx, id).Execute()

Delete an external game



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
	id := "architecto" // string | The ID of the external game.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.DeleteAnExternalGame(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.DeleteAnExternalGame``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the external game. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAnExternalGameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetASingleExternalGame

> GetASingleExternalGame(ctx, id).Execute()

Get a single external game



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
	id := "architecto" // string | The ID of the external game.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetASingleExternalGame(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetASingleExternalGame``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the external game. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetASingleExternalGameRequest struct via the builder pattern


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


## GetASpecificPromotion

> GetASpecificPromotion(ctx, id).Execute()

Get a specific promotion



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
	id := "architecto" // string | The ID of the promotion.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetASpecificPromotion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetASpecificPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetASpecificPromotionRequest struct via the builder pattern


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


## GetApiV1Producers

> GetApiV1Producers(ctx).Execute()





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
	r, err := apiClient.EndpointsAPI.GetApiV1Producers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetApiV1Producers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetApiV1ProducersRequest struct via the builder pattern


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


## GetApiV1ProducersId

> GetApiV1ProducersId(ctx, id).Execute()





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
	id := "architecto" // string | The ID of the producer.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetApiV1ProducersId(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetApiV1ProducersId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the producer. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetApiV1ProducersIdRequest struct via the builder pattern


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


## GetApiV1TransactionExportsExportIdDownload

> GetApiV1TransactionExportsExportIdDownload(ctx, exportId).Execute()





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
	exportId := int32(16) // int32 | The ID of the export.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetApiV1TransactionExportsExportIdDownload(context.Background(), exportId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetApiV1TransactionExportsExportIdDownload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**exportId** | **int32** | The ID of the export. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetApiV1TransactionExportsExportIdDownloadRequest struct via the builder pattern


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


## GetCurrentConfigurationWithGames

> GetCurrentConfigurationWithGames(ctx).Execute()

Get current configuration with games



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
	r, err := apiClient.EndpointsAPI.GetCurrentConfigurationWithGames(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetCurrentConfigurationWithGames``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentConfigurationWithGamesRequest struct via the builder pattern


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


## GetGamesForAPoolTypeOrAllPoolTypes

> GetGamesForAPoolTypeOrAllPoolTypes(ctx).GetGamesForAPoolTypeOrAllPoolTypesRequest(getGamesForAPoolTypeOrAllPoolTypesRequest).Execute()

Get games for a pool type or all pool types



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
	getGamesForAPoolTypeOrAllPoolTypesRequest := *openapiclient.NewGetGamesForAPoolTypeOrAllPoolTypesRequest() // GetGamesForAPoolTypeOrAllPoolTypesRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetGamesForAPoolTypeOrAllPoolTypes(context.Background()).GetGamesForAPoolTypeOrAllPoolTypesRequest(getGamesForAPoolTypeOrAllPoolTypesRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetGamesForAPoolTypeOrAllPoolTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetGamesForAPoolTypeOrAllPoolTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getGamesForAPoolTypeOrAllPoolTypesRequest** | [**GetGamesForAPoolTypeOrAllPoolTypesRequest**](GetGamesForAPoolTypeOrAllPoolTypesRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLeaderboardForAPromotion

> GetLeaderboardForAPromotion(ctx, id).Execute()

Get leaderboard for a promotion



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
	id := "architecto" // string | The ID of the promotion.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetLeaderboardForAPromotion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetLeaderboardForAPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLeaderboardForAPromotionRequest struct via the builder pattern


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


## GetPlayerContributionHistory

> GetPlayerContributionHistory(ctx).GetPlayerContributionHistoryRequest(getPlayerContributionHistoryRequest).Execute()

Get player contribution history



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
	getPlayerContributionHistoryRequest := *openapiclient.NewGetPlayerContributionHistoryRequest("b") // GetPlayerContributionHistoryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetPlayerContributionHistory(context.Background()).GetPlayerContributionHistoryRequest(getPlayerContributionHistoryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetPlayerContributionHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPlayerContributionHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getPlayerContributionHistoryRequest** | [**GetPlayerContributionHistoryRequest**](GetPlayerContributionHistoryRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPoolDetails

> GetPoolDetails(ctx, poolId).Execute()

Get pool details



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
	poolId := "architecto" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetPoolDetails(context.Background(), poolId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetPoolDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPoolDetailsRequest struct via the builder pattern


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


## GetPoolWinners

> GetPoolWinners(ctx, poolId).Execute()

Get pool winners



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
	poolId := "architecto" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetPoolWinners(context.Background(), poolId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetPoolWinners``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPoolWinnersRequest struct via the builder pattern


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


## GetTargetedPlayerDetails

> GetTargetedPlayerDetails(ctx, targetedPlayerId).Execute()

Get targeted player details



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
	targetedPlayerId := "architecto" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetTargetedPlayerDetails(context.Background(), targetedPlayerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetTargetedPlayerDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**targetedPlayerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTargetedPlayerDetailsRequest struct via the builder pattern


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


## GetUniqueProducerNamesForFiltering

> GetUniqueProducerNamesForFiltering(ctx).Execute()

Get unique producer names for filtering



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
	r, err := apiClient.EndpointsAPI.GetUniqueProducerNamesForFiltering(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetUniqueProducerNamesForFiltering``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUniqueProducerNamesForFilteringRequest struct via the builder pattern


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


## GetWinnersForAPromotion

> GetWinnersForAPromotion(ctx, id).Execute()

Get winners for a promotion



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
	id := "architecto" // string | The ID of the promotion.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.GetWinnersForAPromotion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.GetWinnersForAPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetWinnersForAPromotionRequest struct via the builder pattern


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


## ImportExternalGamesFromCSVFile

> ImportExternalGamesFromCSVFile(ctx).File(file).Execute()

Import external games from CSV file



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
	file := os.NewFile(1234, "some_file") // *os.File | Must be a file. Must not be greater than 10240 kilobytes.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ImportExternalGamesFromCSVFile(context.Background()).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ImportExternalGamesFromCSVFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiImportExternalGamesFromCSVFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | Must be a file. Must not be greater than 10240 kilobytes. | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportExternalGamesFromJSONPaste

> ImportExternalGamesFromJSONPaste(ctx).ImportExternalGamesFromJSONPasteRequest(importExternalGamesFromJSONPasteRequest).Execute()

Import external games from JSON paste



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
	importExternalGamesFromJSONPasteRequest := *openapiclient.NewImportExternalGamesFromJSONPasteRequest([]openapiclient.ImportExternalGamesFromJSONPasteRequestGamesInner{*openapiclient.NewImportExternalGamesFromJSONPasteRequestGamesInner("b", "n")}) // ImportExternalGamesFromJSONPasteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ImportExternalGamesFromJSONPaste(context.Background()).ImportExternalGamesFromJSONPasteRequest(importExternalGamesFromJSONPasteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ImportExternalGamesFromJSONPaste``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiImportExternalGamesFromJSONPasteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **importExternalGamesFromJSONPasteRequest** | [**ImportExternalGamesFromJSONPasteRequest**](ImportExternalGamesFromJSONPasteRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListExternalGamesForOperator

> ListExternalGamesForOperator(ctx).ListExternalGamesForOperatorRequest(listExternalGamesForOperatorRequest).Execute()

List external games for operator



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
	listExternalGamesForOperatorRequest := *openapiclient.NewListExternalGamesForOperatorRequest() // ListExternalGamesForOperatorRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ListExternalGamesForOperator(context.Background()).ListExternalGamesForOperatorRequest(listExternalGamesForOperatorRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ListExternalGamesForOperator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListExternalGamesForOperatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **listExternalGamesForOperatorRequest** | [**ListExternalGamesForOperatorRequest**](ListExternalGamesForOperatorRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOperatorsJackpotPools

> ListOperatorsJackpotPools(ctx).ListOperatorsJackpotPoolsRequest(listOperatorsJackpotPoolsRequest).Execute()

List operator's jackpot pools



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
	listOperatorsJackpotPoolsRequest := *openapiclient.NewListOperatorsJackpotPoolsRequest() // ListOperatorsJackpotPoolsRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ListOperatorsJackpotPools(context.Background()).ListOperatorsJackpotPoolsRequest(listOperatorsJackpotPoolsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ListOperatorsJackpotPools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOperatorsJackpotPoolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **listOperatorsJackpotPoolsRequest** | [**ListOperatorsJackpotPoolsRequest**](ListOperatorsJackpotPoolsRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPromotionsForTheOperator

> ListPromotionsForTheOperator(ctx).Execute()

List promotions for the operator



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
	r, err := apiClient.EndpointsAPI.ListPromotionsForTheOperator(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ListPromotionsForTheOperator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListPromotionsForTheOperatorRequest struct via the builder pattern


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


## ListTargetedPlayersForOperator

> ListTargetedPlayersForOperator(ctx).ListTargetedPlayersForOperatorRequest(listTargetedPlayersForOperatorRequest).Execute()

List targeted players for operator



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
	listTargetedPlayersForOperatorRequest := *openapiclient.NewListTargetedPlayersForOperatorRequest() // ListTargetedPlayersForOperatorRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ListTargetedPlayersForOperator(context.Background()).ListTargetedPlayersForOperatorRequest(listTargetedPlayersForOperatorRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ListTargetedPlayersForOperator``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTargetedPlayersForOperatorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **listTargetedPlayersForOperatorRequest** | [**ListTargetedPlayersForOperatorRequest**](ListTargetedPlayersForOperatorRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManageGamesForAPromotion

> ManageGamesForAPromotion(ctx, id).ManageGamesForAPromotionRequest(manageGamesForAPromotionRequest).Execute()

Manage games for a promotion



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
	id := "architecto" // string | The ID of the promotion.
	manageGamesForAPromotionRequest := *openapiclient.NewManageGamesForAPromotionRequest() // ManageGamesForAPromotionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ManageGamesForAPromotion(context.Background(), id).ManageGamesForAPromotionRequest(manageGamesForAPromotionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ManageGamesForAPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiManageGamesForAPromotionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **manageGamesForAPromotionRequest** | [**ManageGamesForAPromotionRequest**](ManageGamesForAPromotionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManuallyDistributePrizesForAPeriod

> ManuallyDistributePrizesForAPeriod(ctx, id, periodId).Execute()

Manually distribute prizes for a period



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
	id := "architecto" // string | The ID of the promotion.
	periodId := "architecto" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ManuallyDistributePrizesForAPeriod(context.Background(), id, periodId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ManuallyDistributePrizesForAPeriod``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 
**periodId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiManuallyDistributePrizesForAPeriodRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManuallyTriggerPoolRelease

> ManuallyTriggerPoolRelease(ctx, poolId).Execute()

Manually trigger pool release



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
	poolId := "architecto" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.ManuallyTriggerPoolRelease(context.Background(), poolId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.ManuallyTriggerPoolRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiManuallyTriggerPoolReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OptInOperatorToAPlatformnetworkPromotion

> OptInOperatorToAPlatformnetworkPromotion(ctx, id).Execute()

Opt-in operator to a platform/network promotion



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
	id := "architecto" // string | The ID of the promotion.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.OptInOperatorToAPlatformnetworkPromotion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.OptInOperatorToAPlatformnetworkPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOptInOperatorToAPlatformnetworkPromotionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OptOutOperatorFromAPlatformnetworkPromotion

> OptOutOperatorFromAPlatformnetworkPromotion(ctx, id).Execute()

Opt-out operator from a platform/network promotion



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
	id := "architecto" // string | The ID of the promotion.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.OptOutOperatorFromAPlatformnetworkPromotion(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.OptOutOperatorFromAPlatformnetworkPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOptOutOperatorFromAPlatformnetworkPromotionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostApiV1GameTransactionsExport

> PostApiV1GameTransactionsExport(ctx).PostApiV1GameTransactionsExportRequest(postApiV1GameTransactionsExportRequest).Execute()





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
	postApiV1GameTransactionsExportRequest := *openapiclient.NewPostApiV1GameTransactionsExportRequest("pdf", "2026-02-04T11:49:09", "2052-02-28") // PostApiV1GameTransactionsExportRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.PostApiV1GameTransactionsExport(context.Background()).PostApiV1GameTransactionsExportRequest(postApiV1GameTransactionsExportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.PostApiV1GameTransactionsExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostApiV1GameTransactionsExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postApiV1GameTransactionsExportRequest** | [**PostApiV1GameTransactionsExportRequest**](PostApiV1GameTransactionsExportRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveGamesFromAJackpotPoolType

> RemoveGamesFromAJackpotPoolType(ctx).RemoveGamesFromAJackpotPoolTypeRequest(removeGamesFromAJackpotPoolTypeRequest).Execute()

Remove games from a jackpot pool type



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
	removeGamesFromAJackpotPoolTypeRequest := *openapiclient.NewRemoveGamesFromAJackpotPoolTypeRequest("daily") // RemoveGamesFromAJackpotPoolTypeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.RemoveGamesFromAJackpotPoolType(context.Background()).RemoveGamesFromAJackpotPoolTypeRequest(removeGamesFromAJackpotPoolTypeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.RemoveGamesFromAJackpotPoolType``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRemoveGamesFromAJackpotPoolTypeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **removeGamesFromAJackpotPoolTypeRequest** | [**RemoveGamesFromAJackpotPoolTypeRequest**](RemoveGamesFromAJackpotPoolTypeRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetGrandPrizeExpirationDate

> SetGrandPrizeExpirationDate(ctx, poolId).SetGrandPrizeExpirationDateRequest(setGrandPrizeExpirationDateRequest).Execute()

Set grand prize expiration date



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
	poolId := "architecto" // string | 
	setGrandPrizeExpirationDateRequest := *openapiclient.NewSetGrandPrizeExpirationDateRequest("2052-02-28") // SetGrandPrizeExpirationDateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.SetGrandPrizeExpirationDate(context.Background(), poolId).SetGrandPrizeExpirationDateRequest(setGrandPrizeExpirationDateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.SetGrandPrizeExpirationDate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**poolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetGrandPrizeExpirationDateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setGrandPrizeExpirationDateRequest** | [**SetGrandPrizeExpirationDateRequest**](SetGrandPrizeExpirationDateRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAPromotion

> UpdateAPromotion(ctx, id).UpdateAPromotionRequest(updateAPromotionRequest).Execute()

Update a promotion



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
	id := "architecto" // string | The ID of the promotion.
	updateAPromotionRequest := *openapiclient.NewUpdateAPromotionRequest() // UpdateAPromotionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.UpdateAPromotion(context.Background(), id).UpdateAPromotionRequest(updateAPromotionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.UpdateAPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the promotion. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAPromotionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAPromotionRequest** | [**UpdateAPromotionRequest**](UpdateAPromotionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAnExternalGame

> UpdateAnExternalGame(ctx, id).UpdateAnExternalGameRequest(updateAnExternalGameRequest).Execute()

Update an external game



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
	id := "architecto" // string | The ID of the external game.
	updateAnExternalGameRequest := *openapiclient.NewUpdateAnExternalGameRequest() // UpdateAnExternalGameRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EndpointsAPI.UpdateAnExternalGame(context.Background(), id).UpdateAnExternalGameRequest(updateAnExternalGameRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EndpointsAPI.UpdateAnExternalGame``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the external game. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAnExternalGameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAnExternalGameRequest** | [**UpdateAnExternalGameRequest**](UpdateAnExternalGameRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

