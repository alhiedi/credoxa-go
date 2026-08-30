# \OperatorAnalyticsRecoveryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorAnalyticsEventDeadLetters**](OperatorAnalyticsRecoveryAPI.md#OperatorAnalyticsEventDeadLetters) | **Get** /api/v1/operator/saas/analytics/recovery/dead-letters/events/ | 
[**OperatorAnalyticsLateArrivalRepair**](OperatorAnalyticsRecoveryAPI.md#OperatorAnalyticsLateArrivalRepair) | **Post** /api/v1/operator/saas/analytics/recovery/late-arrivals/repair/ | Dispatch a guarded late-arrival repair
[**OperatorAnalyticsRebuildList**](OperatorAnalyticsRecoveryAPI.md#OperatorAnalyticsRebuildList) | **Get** /api/v1/operator/saas/analytics/recovery/rebuilds/ | 
[**OperatorAnalyticsRecoveryLeases**](OperatorAnalyticsRecoveryAPI.md#OperatorAnalyticsRecoveryLeases) | **Get** /api/v1/operator/saas/analytics/recovery/leases/ | 
[**OperatorAnalyticsRecoveryList**](OperatorAnalyticsRecoveryAPI.md#OperatorAnalyticsRecoveryList) | **Get** /api/v1/operator/saas/analytics/recovery/operations/ | List durable analytics recovery operations
[**OperatorAnalyticsRepairAction**](OperatorAnalyticsRecoveryAPI.md#OperatorAnalyticsRepairAction) | **Post** /api/v1/operator/saas/analytics/recovery/repairs/{repair_id}/{action}/ | Retry or requeue an analytics repair
[**OperatorAnalyticsRepairDeadLetters**](OperatorAnalyticsRecoveryAPI.md#OperatorAnalyticsRepairDeadLetters) | **Get** /api/v1/operator/saas/analytics/recovery/dead-letters/repairs/ | 



## OperatorAnalyticsEventDeadLetters

> OperatorAnalyticsEventDeadLetters(ctx).Execute()



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
	r, err := apiClient.OperatorAnalyticsRecoveryAPI.OperatorAnalyticsEventDeadLetters(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsRecoveryAPI.OperatorAnalyticsEventDeadLetters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsEventDeadLettersRequest struct via the builder pattern


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


## OperatorAnalyticsLateArrivalRepair

> OperatorAnalyticsLateArrivalRepair(ctx).AnalyticsLateArrivalRepairRequest(analyticsLateArrivalRepairRequest).Execute()

Dispatch a guarded late-arrival repair

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
	analyticsLateArrivalRepairRequest := *openapiclient.NewAnalyticsLateArrivalRepairRequest("ProjectionId_example", "IdempotencyKey_example", "Reason_example") // AnalyticsLateArrivalRepairRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsRecoveryAPI.OperatorAnalyticsLateArrivalRepair(context.Background()).AnalyticsLateArrivalRepairRequest(analyticsLateArrivalRepairRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsRecoveryAPI.OperatorAnalyticsLateArrivalRepair``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsLateArrivalRepairRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **analyticsLateArrivalRepairRequest** | [**AnalyticsLateArrivalRepairRequest**](AnalyticsLateArrivalRepairRequest.md) |  | 

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


## OperatorAnalyticsRebuildList

> OperatorAnalyticsRebuildList(ctx).OrganizationId(organizationId).ProjectionId(projectionId).Status(status).Execute()



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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	projectionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRebuildList(context.Background()).OrganizationId(organizationId).ProjectionId(projectionId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRebuildList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsRebuildListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
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


## OperatorAnalyticsRecoveryLeases

> OperatorAnalyticsRecoveryLeases(ctx).OrganizationId(organizationId).Status(status).Execute()



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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRecoveryLeases(context.Background()).OrganizationId(organizationId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRecoveryLeases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsRecoveryLeasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationId** | **string** |  | 
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


## OperatorAnalyticsRecoveryList

> OperatorAnalyticsRecoveryList(ctx).OrganizationId(organizationId).ProjectionId(projectionId).Status(status).Execute()

List durable analytics recovery operations

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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	projectionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRecoveryList(context.Background()).OrganizationId(organizationId).ProjectionId(projectionId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRecoveryList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsRecoveryListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
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


## OperatorAnalyticsRepairAction

> OperatorAnalyticsRepairAction(ctx, action, repairId).AnalyticsRecoveryActionRequest(analyticsRecoveryActionRequest).Execute()

Retry or requeue an analytics repair

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
	repairId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	analyticsRecoveryActionRequest := *openapiclient.NewAnalyticsRecoveryActionRequest("ProjectionId_example", "IdempotencyKey_example", "Reason_example") // AnalyticsRecoveryActionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRepairAction(context.Background(), action, repairId).AnalyticsRecoveryActionRequest(analyticsRecoveryActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRepairAction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**action** | **string** |  | 
**repairId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsRepairActionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **analyticsRecoveryActionRequest** | [**AnalyticsRecoveryActionRequest**](AnalyticsRecoveryActionRequest.md) |  | 

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


## OperatorAnalyticsRepairDeadLetters

> OperatorAnalyticsRepairDeadLetters(ctx).ErrorCode(errorCode).OrganizationId(organizationId).ProjectionId(projectionId).Reason(reason).Execute()



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
	errorCode := "errorCode_example" // string |  (optional)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	projectionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	reason := "reason_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRepairDeadLetters(context.Background()).ErrorCode(errorCode).OrganizationId(organizationId).ProjectionId(projectionId).Reason(reason).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsRecoveryAPI.OperatorAnalyticsRepairDeadLetters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsRepairDeadLettersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **errorCode** | **string** |  | 
 **organizationId** | **string** |  | 
 **projectionId** | **string** |  | 
 **reason** | **string** |  | 

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

