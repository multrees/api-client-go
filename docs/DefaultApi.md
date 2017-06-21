# \DefaultApi

All URIs are relative to *https://api.multrees.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountsAccountGet**](DefaultApi.md#AccountsAccountGet) | **Get** /accounts/{account} | 
[**AccountsGet**](DefaultApi.md#AccountsGet) | **Get** /accounts | 
[**BeneficiariesBeneficiaryGet**](DefaultApi.md#BeneficiariesBeneficiaryGet) | **Get** /beneficiaries/{beneficiary} | 
[**BeneficiariesGet**](DefaultApi.md#BeneficiariesGet) | **Get** /beneficiaries | 
[**ClientsClientGet**](DefaultApi.md#ClientsClientGet) | **Get** /clients/{client} | 
[**ClientsGet**](DefaultApi.md#ClientsGet) | **Get** /clients | 
[**HoldingsGet**](DefaultApi.md#HoldingsGet) | **Get** /holdings | 
[**HoldingsHoldingAccountsAccountGet**](DefaultApi.md#HoldingsHoldingAccountsAccountGet) | **Get** /holdings/{holding}/accounts/{account} | 
[**HoldingsHoldingClassificationsClassificationGet**](DefaultApi.md#HoldingsHoldingClassificationsClassificationGet) | **Get** /holdings/{holding}/classifications/{classification} | 
[**HoldingsHoldingGet**](DefaultApi.md#HoldingsHoldingGet) | **Get** /holdings/{holding} | 
[**PaymentsGet**](DefaultApi.md#PaymentsGet) | **Get** /payments | 
[**PaymentsPaymentGet**](DefaultApi.md#PaymentsPaymentGet) | **Get** /payments/{payment} | 
[**TradesGet**](DefaultApi.md#TradesGet) | **Get** /trades | 
[**TradesTradeGet**](DefaultApi.md#TradesTradeGet) | **Get** /trades/{trade} | 
[**UsersGet**](DefaultApi.md#UsersGet) | **Get** /users | 
[**UsersUserGet**](DefaultApi.md#UsersUserGet) | **Get** /users/{user} | 


# **AccountsAccountGet**
> Account AccountsAccountGet($account)



Retrieve an account.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account** | **string**|  | 

### Return type

[**Account**](Account.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **AccountsGet**
> Accounts AccountsGet()



Retrieve all accounts.


### Parameters
This endpoint does not need any parameter.

### Return type

[**Accounts**](Accounts.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **BeneficiariesBeneficiaryGet**
> Beneficiary BeneficiariesBeneficiaryGet($beneficiary)



Retrieve a beneficiary.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **beneficiary** | **string**|  | 

### Return type

[**Beneficiary**](Beneficiary.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **BeneficiariesGet**
> Beneficiaries BeneficiariesGet()



Retrieve all beneficiaries.


### Parameters
This endpoint does not need any parameter.

### Return type

[**Beneficiaries**](Beneficiaries.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ClientsClientGet**
> Client ClientsClientGet($client)



Retrieve a client.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **client** | **string**|  | 

### Return type

[**Client**](Client.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ClientsGet**
> Clients ClientsGet()



Retrieve all clients.


### Parameters
This endpoint does not need any parameter.

### Return type

[**Clients**](Clients.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **HoldingsGet**
> Holdings HoldingsGet($extractDate)



Retrieve all holdings.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **extractDate** | **time.Time**| TODO | [optional] 

### Return type

[**Holdings**](Holdings.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **HoldingsHoldingAccountsAccountGet**
> Holdings HoldingsHoldingAccountsAccountGet($holding, $account)




### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **holding** | **string**|  | 
 **account** | **string**|  | 

### Return type

[**Holdings**](Holdings.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **HoldingsHoldingClassificationsClassificationGet**
> Holdings HoldingsHoldingClassificationsClassificationGet($holding, $classification)




### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **holding** | **string**|  | 
 **classification** | **string**|  | 

### Return type

[**Holdings**](Holdings.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **HoldingsHoldingGet**
> Holding HoldingsHoldingGet($holding)




### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **holding** | **string**|  | 

### Return type

[**Holding**](Holding.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PaymentsGet**
> Payments PaymentsGet()



Retrieve all payments.


### Parameters
This endpoint does not need any parameter.

### Return type

[**Payments**](Payments.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **PaymentsPaymentGet**
> Payment PaymentsPaymentGet($payment)



Retrieve a payment.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **payment** | **string**|  | 

### Return type

[**Payment**](Payment.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **TradesGet**
> Trades TradesGet()



Retrieve all trades.


### Parameters
This endpoint does not need any parameter.

### Return type

[**Trades**](Trades.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **TradesTradeGet**
> Trade TradesTradeGet($trade)



Retrieve a single trade.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **trade** | **string**|  | 

### Return type

[**Trade**](Trade.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UsersGet**
> UsersGet()



Retrieve all users.


### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UsersUserGet**
> UsersUserGet($user)



Retieve a user.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user** | **string**|  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

