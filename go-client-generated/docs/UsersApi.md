# {{classname}}

All URIs are relative to *https://example.com:{port}/{version}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UsersUserIdReviewsGet**](UsersApi.md#UsersUserIdReviewsGet) | **Get** /users/{userId}/reviews | Get specified user reviews
[**UsersUserIdReviewsPost**](UsersApi.md#UsersUserIdReviewsPost) | **Post** /users/{userId}/reviews | Send new review

# **UsersUserIdReviewsGet**
> []Review UsersUserIdReviewsGet(ctx, userId)
Get specified user reviews

Get specified user reviews

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | **string**| User identifier | 

### Return type

[**[]Review**](Review.md)

### Authorization

[apikeyAuth](../README.md#apikeyAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **UsersUserIdReviewsPost**
> UsersUserIdReviewsPost(ctx, body, userId, optional)
Send new review

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**Review**](Review.md)| Contents of review | 
  **userId** | **string**| User identifier | 
 **optional** | ***UsersApiUsersUserIdReviewsPostOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiUsersUserIdReviewsPostOpts struct
Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xApiKey** | **optional.**| Request API key | 
 **token** | **optional.**| one time token | 

### Return type

 (empty response body)

### Authorization

[apikeyAuth](../README.md#apikeyAuth)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

