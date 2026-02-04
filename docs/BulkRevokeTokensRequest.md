# BulkRevokeTokensRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TokenIds** | **[]string** | Array of token IDs to revoke. | 

## Methods

### NewBulkRevokeTokensRequest

`func NewBulkRevokeTokensRequest(tokenIds []string, ) *BulkRevokeTokensRequest`

NewBulkRevokeTokensRequest instantiates a new BulkRevokeTokensRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkRevokeTokensRequestWithDefaults

`func NewBulkRevokeTokensRequestWithDefaults() *BulkRevokeTokensRequest`

NewBulkRevokeTokensRequestWithDefaults instantiates a new BulkRevokeTokensRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTokenIds

`func (o *BulkRevokeTokensRequest) GetTokenIds() []string`

GetTokenIds returns the TokenIds field if non-nil, zero value otherwise.

### GetTokenIdsOk

`func (o *BulkRevokeTokensRequest) GetTokenIdsOk() (*[]string, bool)`

GetTokenIdsOk returns a tuple with the TokenIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenIds

`func (o *BulkRevokeTokensRequest) SetTokenIds(v []string)`

SetTokenIds sets TokenIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


