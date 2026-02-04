# GetDomainDetails200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Data** | Pointer to [**GetDomainDetails200ResponseData**](GetDomainDetails200ResponseData.md) |  | [optional] 

## Methods

### NewGetDomainDetails200Response

`func NewGetDomainDetails200Response() *GetDomainDetails200Response`

NewGetDomainDetails200Response instantiates a new GetDomainDetails200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDomainDetails200ResponseWithDefaults

`func NewGetDomainDetails200ResponseWithDefaults() *GetDomainDetails200Response`

NewGetDomainDetails200ResponseWithDefaults instantiates a new GetDomainDetails200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetDomainDetails200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetDomainDetails200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetDomainDetails200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetDomainDetails200Response) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetData

`func (o *GetDomainDetails200Response) GetData() GetDomainDetails200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetDomainDetails200Response) GetDataOk() (*GetDomainDetails200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetDomainDetails200Response) SetData(v GetDomainDetails200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *GetDomainDetails200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


