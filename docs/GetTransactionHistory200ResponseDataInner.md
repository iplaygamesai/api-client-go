# GetTransactionHistory200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**PlayerId** | Pointer to **string** |  | [optional] 
**Game** | Pointer to [**GetSessionStatus200ResponseDataGame**](GetSessionStatus200ResponseDataGame.md) |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **float32** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**BalanceAfter** | Pointer to **float32** |  | [optional] 
**RoundId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 

## Methods

### NewGetTransactionHistory200ResponseDataInner

`func NewGetTransactionHistory200ResponseDataInner() *GetTransactionHistory200ResponseDataInner`

NewGetTransactionHistory200ResponseDataInner instantiates a new GetTransactionHistory200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetTransactionHistory200ResponseDataInnerWithDefaults

`func NewGetTransactionHistory200ResponseDataInnerWithDefaults() *GetTransactionHistory200ResponseDataInner`

NewGetTransactionHistory200ResponseDataInnerWithDefaults instantiates a new GetTransactionHistory200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetTransactionHistory200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetTransactionHistory200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetTransactionHistory200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GetTransactionHistory200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPlayerId

`func (o *GetTransactionHistory200ResponseDataInner) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *GetTransactionHistory200ResponseDataInner) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *GetTransactionHistory200ResponseDataInner) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.

### HasPlayerId

`func (o *GetTransactionHistory200ResponseDataInner) HasPlayerId() bool`

HasPlayerId returns a boolean if a field has been set.

### GetGame

`func (o *GetTransactionHistory200ResponseDataInner) GetGame() GetSessionStatus200ResponseDataGame`

GetGame returns the Game field if non-nil, zero value otherwise.

### GetGameOk

`func (o *GetTransactionHistory200ResponseDataInner) GetGameOk() (*GetSessionStatus200ResponseDataGame, bool)`

GetGameOk returns a tuple with the Game field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGame

`func (o *GetTransactionHistory200ResponseDataInner) SetGame(v GetSessionStatus200ResponseDataGame)`

SetGame sets Game field to given value.

### HasGame

`func (o *GetTransactionHistory200ResponseDataInner) HasGame() bool`

HasGame returns a boolean if a field has been set.

### GetType

`func (o *GetTransactionHistory200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetTransactionHistory200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetTransactionHistory200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *GetTransactionHistory200ResponseDataInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetAmount

`func (o *GetTransactionHistory200ResponseDataInner) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *GetTransactionHistory200ResponseDataInner) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *GetTransactionHistory200ResponseDataInner) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *GetTransactionHistory200ResponseDataInner) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *GetTransactionHistory200ResponseDataInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GetTransactionHistory200ResponseDataInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GetTransactionHistory200ResponseDataInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *GetTransactionHistory200ResponseDataInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetBalanceAfter

`func (o *GetTransactionHistory200ResponseDataInner) GetBalanceAfter() float32`

GetBalanceAfter returns the BalanceAfter field if non-nil, zero value otherwise.

### GetBalanceAfterOk

`func (o *GetTransactionHistory200ResponseDataInner) GetBalanceAfterOk() (*float32, bool)`

GetBalanceAfterOk returns a tuple with the BalanceAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanceAfter

`func (o *GetTransactionHistory200ResponseDataInner) SetBalanceAfter(v float32)`

SetBalanceAfter sets BalanceAfter field to given value.

### HasBalanceAfter

`func (o *GetTransactionHistory200ResponseDataInner) HasBalanceAfter() bool`

HasBalanceAfter returns a boolean if a field has been set.

### GetRoundId

`func (o *GetTransactionHistory200ResponseDataInner) GetRoundId() string`

GetRoundId returns the RoundId field if non-nil, zero value otherwise.

### GetRoundIdOk

`func (o *GetTransactionHistory200ResponseDataInner) GetRoundIdOk() (*string, bool)`

GetRoundIdOk returns a tuple with the RoundId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoundId

`func (o *GetTransactionHistory200ResponseDataInner) SetRoundId(v string)`

SetRoundId sets RoundId field to given value.

### HasRoundId

`func (o *GetTransactionHistory200ResponseDataInner) HasRoundId() bool`

HasRoundId returns a boolean if a field has been set.

### GetStatus

`func (o *GetTransactionHistory200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetTransactionHistory200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetTransactionHistory200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GetTransactionHistory200ResponseDataInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetTransactionHistory200ResponseDataInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetTransactionHistory200ResponseDataInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetTransactionHistory200ResponseDataInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetTransactionHistory200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


