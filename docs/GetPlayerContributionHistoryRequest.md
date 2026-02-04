# GetPlayerContributionHistoryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlayerId** | **string** | Must not be greater than 100 characters. | 
**Currency** | Pointer to **string** | Must be 3 characters. | [optional] 
**Limit** | Pointer to **int32** | Must be at least 1. Must not be greater than 100. | [optional] 
**Offset** | Pointer to **int32** | Must be at least 0. | [optional] 

## Methods

### NewGetPlayerContributionHistoryRequest

`func NewGetPlayerContributionHistoryRequest(playerId string, ) *GetPlayerContributionHistoryRequest`

NewGetPlayerContributionHistoryRequest instantiates a new GetPlayerContributionHistoryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPlayerContributionHistoryRequestWithDefaults

`func NewGetPlayerContributionHistoryRequestWithDefaults() *GetPlayerContributionHistoryRequest`

NewGetPlayerContributionHistoryRequestWithDefaults instantiates a new GetPlayerContributionHistoryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlayerId

`func (o *GetPlayerContributionHistoryRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *GetPlayerContributionHistoryRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *GetPlayerContributionHistoryRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetCurrency

`func (o *GetPlayerContributionHistoryRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GetPlayerContributionHistoryRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GetPlayerContributionHistoryRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *GetPlayerContributionHistoryRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetLimit

`func (o *GetPlayerContributionHistoryRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *GetPlayerContributionHistoryRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *GetPlayerContributionHistoryRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *GetPlayerContributionHistoryRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *GetPlayerContributionHistoryRequest) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *GetPlayerContributionHistoryRequest) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *GetPlayerContributionHistoryRequest) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *GetPlayerContributionHistoryRequest) HasOffset() bool`

HasOffset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


