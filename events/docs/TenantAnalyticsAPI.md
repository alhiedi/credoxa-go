# \TenantAnalyticsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TenantAnalyticsProjectionDetail**](TenantAnalyticsAPI.md#TenantAnalyticsProjectionDetail) | **Get** /api/v1/operator/saas/analytics/projections/{projection_id}/ | Retrieve a tenant analytics projection
[**TenantAnalyticsProjectionList**](TenantAnalyticsAPI.md#TenantAnalyticsProjectionList) | **Get** /api/v1/operator/saas/analytics/projections/ | List tenant analytics projections
[**TenantAnalyticsProjectionReadiness**](TenantAnalyticsAPI.md#TenantAnalyticsProjectionReadiness) | **Get** /api/v1/operator/saas/analytics/projections/{projection_id}/readiness/ | Inspect tenant projection readiness
[**TenantAnalyticsQuery**](TenantAnalyticsAPI.md#TenantAnalyticsQuery) | **Post** /api/v1/operator/saas/analytics/query/ | Execute a tenant-scoped analytics query



## TenantAnalyticsProjectionDetail

> AnalyticsQueryAPIResponse TenantAnalyticsProjectionDetail(ctx, projectionId).Execute()

Retrieve a tenant analytics projection

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
	projectionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantAnalyticsAPI.TenantAnalyticsProjectionDetail(context.Background(), projectionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAnalyticsAPI.TenantAnalyticsProjectionDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TenantAnalyticsProjectionDetail`: AnalyticsQueryAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `TenantAnalyticsAPI.TenantAnalyticsProjectionDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTenantAnalyticsProjectionDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AnalyticsQueryAPIResponse**](AnalyticsQueryAPIResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TenantAnalyticsProjectionList

> AnalyticsQueryAPIResponse TenantAnalyticsProjectionList(ctx).Limit(limit).Name(name).Status(status).Execute()

List tenant analytics projections

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
	limit := int32(56) // int32 |  (optional)
	name := "name_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantAnalyticsAPI.TenantAnalyticsProjectionList(context.Background()).Limit(limit).Name(name).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAnalyticsAPI.TenantAnalyticsProjectionList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TenantAnalyticsProjectionList`: AnalyticsQueryAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `TenantAnalyticsAPI.TenantAnalyticsProjectionList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTenantAnalyticsProjectionListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | 
 **name** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**AnalyticsQueryAPIResponse**](AnalyticsQueryAPIResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TenantAnalyticsProjectionReadiness

> AnalyticsQueryAPIResponse TenantAnalyticsProjectionReadiness(ctx, projectionId).MaximumStalenessSeconds(maximumStalenessSeconds).Execute()

Inspect tenant projection readiness

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
	projectionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	maximumStalenessSeconds := int32(56) // int32 | Maximum accepted age of the latest projection refresh. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantAnalyticsAPI.TenantAnalyticsProjectionReadiness(context.Background(), projectionId).MaximumStalenessSeconds(maximumStalenessSeconds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAnalyticsAPI.TenantAnalyticsProjectionReadiness``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TenantAnalyticsProjectionReadiness`: AnalyticsQueryAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `TenantAnalyticsAPI.TenantAnalyticsProjectionReadiness`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTenantAnalyticsProjectionReadinessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **maximumStalenessSeconds** | **int32** | Maximum accepted age of the latest projection refresh. | 

### Return type

[**AnalyticsQueryAPIResponse**](AnalyticsQueryAPIResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TenantAnalyticsQuery

> AnalyticsQueryAPIResponse TenantAnalyticsQuery(ctx).AnalyticsQueryRequestRequest(analyticsQueryRequestRequest).Execute()

Execute a tenant-scoped analytics query



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
	analyticsQueryRequestRequest := *openapiclient.NewAnalyticsQueryRequestRequest(*openapiclient.NewAnalyticsProjectionSelectorRequest(), time.Now(), time.Now()) // AnalyticsQueryRequestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantAnalyticsAPI.TenantAnalyticsQuery(context.Background()).AnalyticsQueryRequestRequest(analyticsQueryRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAnalyticsAPI.TenantAnalyticsQuery``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TenantAnalyticsQuery`: AnalyticsQueryAPIResponse
	fmt.Fprintf(os.Stdout, "Response from `TenantAnalyticsAPI.TenantAnalyticsQuery`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTenantAnalyticsQueryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **analyticsQueryRequestRequest** | [**AnalyticsQueryRequestRequest**](AnalyticsQueryRequestRequest.md) |  | 

### Return type

[**AnalyticsQueryAPIResponse**](AnalyticsQueryAPIResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

