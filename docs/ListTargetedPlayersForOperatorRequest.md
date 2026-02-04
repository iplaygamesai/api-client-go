# ListTargetedPlayersForOperatorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PoolType** | Pointer to **string** |  | [optional] 
**Currency** | Pointer to **string** | Must be 3 characters. | [optional] 
**ActiveOnly** | Pointer to **bool** |  | [optional] 
**Limit** | Pointer to **int32** | Must be at least 1. Must not be greater than 100. | [optional] 
**Offset** | Pointer to **int32** | Must be at least 0. | [optional] 

## Methods

### NewListTargetedPlayersForOperatorRequest

`func NewListTargetedPlayersForOperatorRequest() *ListTargetedPlayersForOperatorRequest`

NewListTargetedPlayersForOperatorRequest instantiates a new ListTargetedPlayersForOperatorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListTargetedPlayersForOperatorRequestWithDefaults

`func NewListTargetedPlayersForOperatorRequestWithDefaults() *ListTargetedPlayersForOperatorRequest`

NewListTargetedPlayersForOperatorRequestWithDefaults instantiates a new ListTargetedPlayersForOperatorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPoolType

`func (o *ListTargetedPlayersForOperatorRequest) GetPoolType() string`

GetPoolType returns the PoolType field if non-nil, zero value otherwise.

### GetPoolTypeOk

`func (o *ListTargetedPlayersForOperatorRequest) GetPoolTypeOk() (*string, bool)`

GetPoolTypeOk returns a tuple with the PoolType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolType

`func (o *ListTargetedPlayersForOperatorRequest) SetPoolType(v string)`

SetPoolType sets PoolType field to given value.

### HasPoolType

`func (o *ListTargetedPlayersForOperatorRequest) HasPoolType() bool`

HasPoolType returns a boolean if a field has been set.

### GetCurrency

`func (o *ListTargetedPlayersForOperatorRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ListTargetedPlayersForOperatorRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ListTargetedPlayersForOperatorRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ListTargetedPlayersForOperatorRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetActiveOnly

`func (o *ListTargetedPlayersForOperatorRequest) GetActiveOnly() bool`

GetActiveOnly returns the ActiveOnly field if non-nil, zero value otherwise.

### GetActiveOnlyOk

`func (o *ListTargetedPlayersForOperatorRequest) GetActiveOnlyOk() (*bool, bool)`

GetActiveOnlyOk returns a tuple with the ActiveOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveOnly

`func (o *ListTargetedPlayersForOperatorRequest) SetActiveOnly(v bool)`

SetActiveOnly sets ActiveOnly field to given value.

### HasActiveOnly

`func (o *ListTargetedPlayersForOperatorRequest) HasActiveOnly() bool`

HasActiveOnly returns a boolean if a field has been set.

### GetLimit

`func (o *ListTargetedPlayersForOperatorRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ListTargetedPlayersForOperatorRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ListTargetedPlayersForOperatorRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *ListTargetedPlayersForOperatorRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *ListTargetedPlayersForOperatorRequest) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ListTargetedPlayersForOperatorRequest) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ListTargetedPlayersForOperatorRequest) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *ListTargetedPlayersForOperatorRequest) HasOffset() bool`

HasOffset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


