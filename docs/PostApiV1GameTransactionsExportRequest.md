# PostApiV1GameTransactionsExportRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Format** | **string** |  | 
**FromDate** | **string** | Must be a valid date. | 
**ToDate** | **string** | Must be a valid date. Must be a date after or equal to &lt;code&gt;from_date&lt;/code&gt;. | 
**PlayerId** | Pointer to **NullableString** |  | [optional] 
**GameId** | Pointer to **NullableInt32** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the games table. | [optional] 
**Type** | Pointer to **NullableString** |  | [optional] 
**IncludeSummary** | Pointer to **bool** |  | [optional] 
**Async** | Pointer to **bool** |  | [optional] 

## Methods

### NewPostApiV1GameTransactionsExportRequest

`func NewPostApiV1GameTransactionsExportRequest(format string, fromDate string, toDate string, ) *PostApiV1GameTransactionsExportRequest`

NewPostApiV1GameTransactionsExportRequest instantiates a new PostApiV1GameTransactionsExportRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostApiV1GameTransactionsExportRequestWithDefaults

`func NewPostApiV1GameTransactionsExportRequestWithDefaults() *PostApiV1GameTransactionsExportRequest`

NewPostApiV1GameTransactionsExportRequestWithDefaults instantiates a new PostApiV1GameTransactionsExportRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFormat

`func (o *PostApiV1GameTransactionsExportRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *PostApiV1GameTransactionsExportRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *PostApiV1GameTransactionsExportRequest) SetFormat(v string)`

SetFormat sets Format field to given value.


### GetFromDate

`func (o *PostApiV1GameTransactionsExportRequest) GetFromDate() string`

GetFromDate returns the FromDate field if non-nil, zero value otherwise.

### GetFromDateOk

`func (o *PostApiV1GameTransactionsExportRequest) GetFromDateOk() (*string, bool)`

GetFromDateOk returns a tuple with the FromDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromDate

`func (o *PostApiV1GameTransactionsExportRequest) SetFromDate(v string)`

SetFromDate sets FromDate field to given value.


### GetToDate

`func (o *PostApiV1GameTransactionsExportRequest) GetToDate() string`

GetToDate returns the ToDate field if non-nil, zero value otherwise.

### GetToDateOk

`func (o *PostApiV1GameTransactionsExportRequest) GetToDateOk() (*string, bool)`

GetToDateOk returns a tuple with the ToDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToDate

`func (o *PostApiV1GameTransactionsExportRequest) SetToDate(v string)`

SetToDate sets ToDate field to given value.


### GetPlayerId

`func (o *PostApiV1GameTransactionsExportRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *PostApiV1GameTransactionsExportRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *PostApiV1GameTransactionsExportRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.

### HasPlayerId

`func (o *PostApiV1GameTransactionsExportRequest) HasPlayerId() bool`

HasPlayerId returns a boolean if a field has been set.

### SetPlayerIdNil

`func (o *PostApiV1GameTransactionsExportRequest) SetPlayerIdNil(b bool)`

 SetPlayerIdNil sets the value for PlayerId to be an explicit nil

### UnsetPlayerId
`func (o *PostApiV1GameTransactionsExportRequest) UnsetPlayerId()`

UnsetPlayerId ensures that no value is present for PlayerId, not even an explicit nil
### GetGameId

`func (o *PostApiV1GameTransactionsExportRequest) GetGameId() int32`

GetGameId returns the GameId field if non-nil, zero value otherwise.

### GetGameIdOk

`func (o *PostApiV1GameTransactionsExportRequest) GetGameIdOk() (*int32, bool)`

GetGameIdOk returns a tuple with the GameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameId

`func (o *PostApiV1GameTransactionsExportRequest) SetGameId(v int32)`

SetGameId sets GameId field to given value.

### HasGameId

`func (o *PostApiV1GameTransactionsExportRequest) HasGameId() bool`

HasGameId returns a boolean if a field has been set.

### SetGameIdNil

`func (o *PostApiV1GameTransactionsExportRequest) SetGameIdNil(b bool)`

 SetGameIdNil sets the value for GameId to be an explicit nil

### UnsetGameId
`func (o *PostApiV1GameTransactionsExportRequest) UnsetGameId()`

UnsetGameId ensures that no value is present for GameId, not even an explicit nil
### GetType

`func (o *PostApiV1GameTransactionsExportRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PostApiV1GameTransactionsExportRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PostApiV1GameTransactionsExportRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PostApiV1GameTransactionsExportRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *PostApiV1GameTransactionsExportRequest) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *PostApiV1GameTransactionsExportRequest) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetIncludeSummary

`func (o *PostApiV1GameTransactionsExportRequest) GetIncludeSummary() bool`

GetIncludeSummary returns the IncludeSummary field if non-nil, zero value otherwise.

### GetIncludeSummaryOk

`func (o *PostApiV1GameTransactionsExportRequest) GetIncludeSummaryOk() (*bool, bool)`

GetIncludeSummaryOk returns a tuple with the IncludeSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeSummary

`func (o *PostApiV1GameTransactionsExportRequest) SetIncludeSummary(v bool)`

SetIncludeSummary sets IncludeSummary field to given value.

### HasIncludeSummary

`func (o *PostApiV1GameTransactionsExportRequest) HasIncludeSummary() bool`

HasIncludeSummary returns a boolean if a field has been set.

### GetAsync

`func (o *PostApiV1GameTransactionsExportRequest) GetAsync() bool`

GetAsync returns the Async field if non-nil, zero value otherwise.

### GetAsyncOk

`func (o *PostApiV1GameTransactionsExportRequest) GetAsyncOk() (*bool, bool)`

GetAsyncOk returns a tuple with the Async field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsync

`func (o *PostApiV1GameTransactionsExportRequest) SetAsync(v bool)`

SetAsync sets Async field to given value.

### HasAsync

`func (o *PostApiV1GameTransactionsExportRequest) HasAsync() bool`

HasAsync returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


