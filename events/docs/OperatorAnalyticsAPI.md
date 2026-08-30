# \OperatorAnalyticsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorAnalyticsProjectionAction**](OperatorAnalyticsAPI.md#OperatorAnalyticsProjectionAction) | **Post** /api/v1/operator/saas/analytics/operator/projections/{projection_id}/{action}/ | Refresh, rebuild, or invalidate an analytics projection
[**OperatorAnalyticsProjectionDetail**](OperatorAnalyticsAPI.md#OperatorAnalyticsProjectionDetail) | **Get** /api/v1/operator/saas/analytics/operator/projections/{projection_id}/ | Inspect an analytics projection
[**OperatorAnalyticsProjectionList**](OperatorAnalyticsAPI.md#OperatorAnalyticsProjectionList) | **Get** /api/v1/operator/saas/analytics/operator/projections/ | List analytics projections for operators
[**OperatorAnalyticsProjectionRuntime**](OperatorAnalyticsAPI.md#OperatorAnalyticsProjectionRuntime) | **Get** /api/v1/operator/saas/analytics/operator/projections/{projection_id}/runtime/ | Inspect projection runtime state
[**OperatorAnalyticsRuntimeCollection**](OperatorAnalyticsAPI.md#OperatorAnalyticsRuntimeCollection) | **Get** /api/v1/operator/saas/analytics/operator/runtime/{kind}/ | List analytics runtime records



## OperatorAnalyticsProjectionAction

> OperatorAnalyticsProjectionAction(ctx, action, projectionId).OperatorActionRequest(operatorActionRequest).Execute()

Refresh, rebuild, or invalidate an analytics projection

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
	action := "action_example" // string | 
	projectionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorActionRequest := *openapiclient.NewOperatorActionRequest("IdempotencyKey_example", "Reason_example") // OperatorActionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsAPI.OperatorAnalyticsProjectionAction(context.Background(), action, projectionId).OperatorActionRequest(operatorActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsAPI.OperatorAnalyticsProjectionAction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**action** | **string** |  | 
**projectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsProjectionActionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **operatorActionRequest** | [**OperatorActionRequest**](OperatorActionRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorAnalyticsProjectionDetail

> OperatorAnalyticsProjectionDetail(ctx, projectionId).OrganizationId(organizationId).Execute()

Inspect an analytics projection

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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsAPI.OperatorAnalyticsProjectionDetail(context.Background(), projectionId).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsAPI.OperatorAnalyticsProjectionDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsProjectionDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organizationId** | **string** |  | 

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


## OperatorAnalyticsProjectionList

> OperatorAnalyticsProjectionList(ctx).Limit(limit).Name(name).OrganizationId(organizationId).Readiness(readiness).Status(status).Execute()

List analytics projections for operators

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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	readiness := "readiness_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsAPI.OperatorAnalyticsProjectionList(context.Background()).Limit(limit).Name(name).OrganizationId(organizationId).Readiness(readiness).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsAPI.OperatorAnalyticsProjectionList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsProjectionListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | 
 **name** | **string** |  | 
 **organizationId** | **string** |  | 
 **readiness** | **string** |  | 
 **status** | **string** |  | 

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


## OperatorAnalyticsProjectionRuntime

> OperatorAnalyticsProjectionRuntime(ctx, projectionId).OrganizationId(organizationId).Execute()

Inspect projection runtime state

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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsAPI.OperatorAnalyticsProjectionRuntime(context.Background(), projectionId).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsAPI.OperatorAnalyticsProjectionRuntime``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsProjectionRuntimeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organizationId** | **string** |  | 

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


## OperatorAnalyticsRuntimeCollection

> OperatorAnalyticsRuntimeCollection(ctx, kind).Limit(limit).OrganizationId(organizationId).ProjectionId(projectionId).Status(status).Execute()

List analytics runtime records

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
	kind := "kind_example" // string | 
	limit := int32(56) // int32 |  (optional)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	projectionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsAPI.OperatorAnalyticsRuntimeCollection(context.Background(), kind).Limit(limit).OrganizationId(organizationId).ProjectionId(projectionId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsAPI.OperatorAnalyticsRuntimeCollection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**kind** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsRuntimeCollectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** |  | 
 **organizationId** | **string** |  | 
 **projectionId** | **string** |  | 
 **status** | **string** |  | 

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

