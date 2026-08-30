# \RetentionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RetentionPoliciesCreate**](RetentionAPI.md#RetentionPoliciesCreate) | **Post** /api/v1/retention/policies/ | 
[**RetentionPoliciesDestroy**](RetentionAPI.md#RetentionPoliciesDestroy) | **Delete** /api/v1/retention/policies/{policy_id}/ | 
[**RetentionPoliciesList**](RetentionAPI.md#RetentionPoliciesList) | **Get** /api/v1/retention/policies/ | 
[**RetentionPoliciesPartialUpdate**](RetentionAPI.md#RetentionPoliciesPartialUpdate) | **Patch** /api/v1/retention/policies/{policy_id}/ | 
[**RetentionPoliciesRetrieve**](RetentionAPI.md#RetentionPoliciesRetrieve) | **Get** /api/v1/retention/policies/{policy_id}/ | 
[**RetentionPoliciesUpdate**](RetentionAPI.md#RetentionPoliciesUpdate) | **Put** /api/v1/retention/policies/{policy_id}/ | 
[**RetentionPreviewCreate**](RetentionAPI.md#RetentionPreviewCreate) | **Post** /api/v1/retention/preview/ | 



## RetentionPoliciesCreate

> RetentionPolicyRead RetentionPoliciesCreate(ctx).RetentionPolicyWriteRequest(retentionPolicyWriteRequest).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/alhiedi/credoxa-go/events"
)

func main() {
	retentionPolicyWriteRequest := *openapiclient.NewRetentionPolicyWriteRequest("Name_example", openapiclient.RetentionPolicyWriteScopeEnum("organization")) // RetentionPolicyWriteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RetentionAPI.RetentionPoliciesCreate(context.Background()).RetentionPolicyWriteRequest(retentionPolicyWriteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RetentionAPI.RetentionPoliciesCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetentionPoliciesCreate`: RetentionPolicyRead
	fmt.Fprintf(os.Stdout, "Response from `RetentionAPI.RetentionPoliciesCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRetentionPoliciesCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **retentionPolicyWriteRequest** | [**RetentionPolicyWriteRequest**](RetentionPolicyWriteRequest.md) |  | 

### Return type

[**RetentionPolicyRead**](RetentionPolicyRead.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetentionPoliciesDestroy

> RetentionPoliciesDestroy(ctx, policyId).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/alhiedi/credoxa-go/events"
)

func main() {
	policyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.RetentionAPI.RetentionPoliciesDestroy(context.Background(), policyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RetentionAPI.RetentionPoliciesDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**policyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetentionPoliciesDestroyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetentionPoliciesList

> []RetentionPolicyRead RetentionPoliciesList(ctx).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/alhiedi/credoxa-go/events"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RetentionAPI.RetentionPoliciesList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RetentionAPI.RetentionPoliciesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetentionPoliciesList`: []RetentionPolicyRead
	fmt.Fprintf(os.Stdout, "Response from `RetentionAPI.RetentionPoliciesList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRetentionPoliciesListRequest struct via the builder pattern


### Return type

[**[]RetentionPolicyRead**](RetentionPolicyRead.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetentionPoliciesPartialUpdate

> RetentionPolicyRead RetentionPoliciesPartialUpdate(ctx, policyId).PatchedRetentionPolicyWriteRequest(patchedRetentionPolicyWriteRequest).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/alhiedi/credoxa-go/events"
)

func main() {
	policyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	patchedRetentionPolicyWriteRequest := *openapiclient.NewPatchedRetentionPolicyWriteRequest() // PatchedRetentionPolicyWriteRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RetentionAPI.RetentionPoliciesPartialUpdate(context.Background(), policyId).PatchedRetentionPolicyWriteRequest(patchedRetentionPolicyWriteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RetentionAPI.RetentionPoliciesPartialUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetentionPoliciesPartialUpdate`: RetentionPolicyRead
	fmt.Fprintf(os.Stdout, "Response from `RetentionAPI.RetentionPoliciesPartialUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**policyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetentionPoliciesPartialUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchedRetentionPolicyWriteRequest** | [**PatchedRetentionPolicyWriteRequest**](PatchedRetentionPolicyWriteRequest.md) |  | 

### Return type

[**RetentionPolicyRead**](RetentionPolicyRead.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetentionPoliciesRetrieve

> RetentionPolicyRead RetentionPoliciesRetrieve(ctx, policyId).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/alhiedi/credoxa-go/events"
)

func main() {
	policyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RetentionAPI.RetentionPoliciesRetrieve(context.Background(), policyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RetentionAPI.RetentionPoliciesRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetentionPoliciesRetrieve`: RetentionPolicyRead
	fmt.Fprintf(os.Stdout, "Response from `RetentionAPI.RetentionPoliciesRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**policyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetentionPoliciesRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RetentionPolicyRead**](RetentionPolicyRead.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetentionPoliciesUpdate

> RetentionPolicyRead RetentionPoliciesUpdate(ctx, policyId).RetentionPolicyWriteRequest(retentionPolicyWriteRequest).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/alhiedi/credoxa-go/events"
)

func main() {
	policyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	retentionPolicyWriteRequest := *openapiclient.NewRetentionPolicyWriteRequest("Name_example", openapiclient.RetentionPolicyWriteScopeEnum("organization")) // RetentionPolicyWriteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RetentionAPI.RetentionPoliciesUpdate(context.Background(), policyId).RetentionPolicyWriteRequest(retentionPolicyWriteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RetentionAPI.RetentionPoliciesUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetentionPoliciesUpdate`: RetentionPolicyRead
	fmt.Fprintf(os.Stdout, "Response from `RetentionAPI.RetentionPoliciesUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**policyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetentionPoliciesUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **retentionPolicyWriteRequest** | [**RetentionPolicyWriteRequest**](RetentionPolicyWriteRequest.md) |  | 

### Return type

[**RetentionPolicyRead**](RetentionPolicyRead.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetentionPreviewCreate

> RetentionExplanation RetentionPreviewCreate(ctx).RetentionPreviewInputRequest(retentionPreviewInputRequest).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/alhiedi/credoxa-go/events"
)

func main() {
	retentionPreviewInputRequest := *openapiclient.NewRetentionPreviewInputRequest("EventTypeId_example", "Source_example", time.Now()) // RetentionPreviewInputRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RetentionAPI.RetentionPreviewCreate(context.Background()).RetentionPreviewInputRequest(retentionPreviewInputRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RetentionAPI.RetentionPreviewCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetentionPreviewCreate`: RetentionExplanation
	fmt.Fprintf(os.Stdout, "Response from `RetentionAPI.RetentionPreviewCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRetentionPreviewCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **retentionPreviewInputRequest** | [**RetentionPreviewInputRequest**](RetentionPreviewInputRequest.md) |  | 

### Return type

[**RetentionExplanation**](RetentionExplanation.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

