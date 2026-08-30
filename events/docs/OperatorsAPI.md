# \OperatorsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorConsumerRuntimeDashboardRetrieve**](OperatorsAPI.md#OperatorConsumerRuntimeDashboardRetrieve) | **Get** /api/operators/v1/consumers/runtime-dashboard/ | Get consumer runtime dashboard
[**OperatorConsumerRuntimeHealthRetrieve**](OperatorsAPI.md#OperatorConsumerRuntimeHealthRetrieve) | **Get** /api/operators/v1/consumers/{consumer_id}/runtime-health/ | Get consumer runtime health
[**OperatorConsumerRuntimeMetricsRetrieve**](OperatorsAPI.md#OperatorConsumerRuntimeMetricsRetrieve) | **Get** /api/operators/v1/consumers/runtime-metrics/ | Get consumer runtime metrics
[**OperatorConsumerRuntimeSnapshotRetrieve**](OperatorsAPI.md#OperatorConsumerRuntimeSnapshotRetrieve) | **Get** /api/operators/v1/consumers/{consumer_id}/runtime-snapshot/ | Get consumer runtime snapshot
[**OperatorRuntimeIncidentAcknowledge**](OperatorsAPI.md#OperatorRuntimeIncidentAcknowledge) | **Post** /api/operators/v1/runtime-incidents/{incident_id}/acknowledge/ | Acknowledge runtime incident
[**OperatorRuntimeIncidentNotificationReplay**](OperatorsAPI.md#OperatorRuntimeIncidentNotificationReplay) | **Post** /api/operators/v1/runtime-incident-notifications/{outbox_id}/replay/ | Replay dead-letter runtime incident notification
[**OperatorRuntimeIncidentNotificationRetrieve**](OperatorsAPI.md#OperatorRuntimeIncidentNotificationRetrieve) | **Get** /api/operators/v1/runtime-incident-notifications/{outbox_id}/ | Retrieve runtime incident notification delivery
[**OperatorRuntimeIncidentNotificationRetry**](OperatorsAPI.md#OperatorRuntimeIncidentNotificationRetry) | **Post** /api/operators/v1/runtime-incident-notifications/{outbox_id}/retry/ | Retry failed runtime incident notification
[**OperatorRuntimeIncidentNotificationSearch**](OperatorsAPI.md#OperatorRuntimeIncidentNotificationSearch) | **Get** /api/operators/v1/runtime-incident-notifications/ | Search runtime incident notification deliveries
[**OperatorRuntimeIncidentNotificationSummary**](OperatorsAPI.md#OperatorRuntimeIncidentNotificationSummary) | **Get** /api/operators/v1/runtime-incident-notifications/summary/ | Retrieve notification delivery backlog summary
[**OperatorRuntimeIncidentOccurrenceList**](OperatorsAPI.md#OperatorRuntimeIncidentOccurrenceList) | **Get** /api/operators/v1/runtime-incidents/{incident_id}/occurrences/ | List runtime incident occurrences
[**OperatorRuntimeIncidentReopen**](OperatorsAPI.md#OperatorRuntimeIncidentReopen) | **Post** /api/operators/v1/runtime-incidents/{incident_id}/reopen/ | Reopen runtime incident
[**OperatorRuntimeIncidentResolve**](OperatorsAPI.md#OperatorRuntimeIncidentResolve) | **Post** /api/operators/v1/runtime-incidents/{incident_id}/resolve/ | Resolve runtime incident
[**OperatorRuntimeIncidentRetrieve**](OperatorsAPI.md#OperatorRuntimeIncidentRetrieve) | **Get** /api/operators/v1/runtime-incidents/{incident_id}/ | Retrieve runtime incident
[**OperatorRuntimeIncidentSearch**](OperatorsAPI.md#OperatorRuntimeIncidentSearch) | **Get** /api/operators/v1/runtime-incidents/ | Search runtime incidents



## OperatorConsumerRuntimeDashboardRetrieve

> OperatorRuntimeDashboardResponse OperatorConsumerRuntimeDashboardRetrieve(ctx).OrganizationId(organizationId).TopLimit(topLimit).Execute()

Get consumer runtime dashboard



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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Optional organization scope. Omit this value to build a platform-wide dashboard. (optional)
	topLimit := int32(56) // int32 | Maximum number of consumers requiring attention to include in the ranked result. (optional) (default to 10)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorConsumerRuntimeDashboardRetrieve(context.Background()).OrganizationId(organizationId).TopLimit(topLimit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorConsumerRuntimeDashboardRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorConsumerRuntimeDashboardRetrieve`: OperatorRuntimeDashboardResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorConsumerRuntimeDashboardRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorConsumerRuntimeDashboardRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationId** | **string** | Optional organization scope. Omit this value to build a platform-wide dashboard. | 
 **topLimit** | **int32** | Maximum number of consumers requiring attention to include in the ranked result. | [default to 10]

### Return type

[**OperatorRuntimeDashboardResponse**](OperatorRuntimeDashboardResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorConsumerRuntimeHealthRetrieve

> OperatorConsumerRuntimeHealth OperatorConsumerRuntimeHealthRetrieve(ctx, consumerId).Execute()

Get consumer runtime health



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
	consumerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorConsumerRuntimeHealthRetrieve(context.Background(), consumerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorConsumerRuntimeHealthRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorConsumerRuntimeHealthRetrieve`: OperatorConsumerRuntimeHealth
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorConsumerRuntimeHealthRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**consumerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorConsumerRuntimeHealthRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorConsumerRuntimeHealth**](OperatorConsumerRuntimeHealth.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorConsumerRuntimeMetricsRetrieve

> OperatorRuntimeMetricsResponse OperatorConsumerRuntimeMetricsRetrieve(ctx).IncludePoints(includePoints).OrganizationId(organizationId).Execute()

Get consumer runtime metrics



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
	includePoints := true // bool | Include normalized per-consumer runtime metric points in the response. (optional) (default to false)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Optional organization filter. Omit this value to collect platform-wide runtime metrics. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorConsumerRuntimeMetricsRetrieve(context.Background()).IncludePoints(includePoints).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorConsumerRuntimeMetricsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorConsumerRuntimeMetricsRetrieve`: OperatorRuntimeMetricsResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorConsumerRuntimeMetricsRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorConsumerRuntimeMetricsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includePoints** | **bool** | Include normalized per-consumer runtime metric points in the response. | [default to false]
 **organizationId** | **string** | Optional organization filter. Omit this value to collect platform-wide runtime metrics. | 

### Return type

[**OperatorRuntimeMetricsResponse**](OperatorRuntimeMetricsResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorConsumerRuntimeSnapshotRetrieve

> OperatorConsumerRuntimeSnapshot OperatorConsumerRuntimeSnapshotRetrieve(ctx, consumerId).Execute()

Get consumer runtime snapshot



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
	consumerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorConsumerRuntimeSnapshotRetrieve(context.Background(), consumerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorConsumerRuntimeSnapshotRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorConsumerRuntimeSnapshotRetrieve`: OperatorConsumerRuntimeSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorConsumerRuntimeSnapshotRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**consumerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorConsumerRuntimeSnapshotRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorConsumerRuntimeSnapshot**](OperatorConsumerRuntimeSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentAcknowledge

> OperatorRuntimeIncidentActionResponse OperatorRuntimeIncidentAcknowledge(ctx, incidentId).OperatorRuntimeIncidentActionRequestRequest(operatorRuntimeIncidentActionRequestRequest).Execute()

Acknowledge runtime incident

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
	incidentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorRuntimeIncidentActionRequestRequest := *openapiclient.NewOperatorRuntimeIncidentActionRequestRequest() // OperatorRuntimeIncidentActionRequestRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentAcknowledge(context.Background(), incidentId).OperatorRuntimeIncidentActionRequestRequest(operatorRuntimeIncidentActionRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentAcknowledge``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentAcknowledge`: OperatorRuntimeIncidentActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentAcknowledge`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**incidentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentAcknowledgeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operatorRuntimeIncidentActionRequestRequest** | [**OperatorRuntimeIncidentActionRequestRequest**](OperatorRuntimeIncidentActionRequestRequest.md) |  | 

### Return type

[**OperatorRuntimeIncidentActionResponse**](OperatorRuntimeIncidentActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentNotificationReplay

> OperatorRuntimeIncidentNotificationActionResponse OperatorRuntimeIncidentNotificationReplay(ctx, outboxId).OperatorRuntimeIncidentNotificationActionRequestRequest(operatorRuntimeIncidentNotificationActionRequestRequest).Execute()

Replay dead-letter runtime incident notification

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
	outboxId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorRuntimeIncidentNotificationActionRequestRequest := *openapiclient.NewOperatorRuntimeIncidentNotificationActionRequestRequest() // OperatorRuntimeIncidentNotificationActionRequestRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentNotificationReplay(context.Background(), outboxId).OperatorRuntimeIncidentNotificationActionRequestRequest(operatorRuntimeIncidentNotificationActionRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentNotificationReplay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentNotificationReplay`: OperatorRuntimeIncidentNotificationActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentNotificationReplay`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**outboxId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentNotificationReplayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operatorRuntimeIncidentNotificationActionRequestRequest** | [**OperatorRuntimeIncidentNotificationActionRequestRequest**](OperatorRuntimeIncidentNotificationActionRequestRequest.md) |  | 

### Return type

[**OperatorRuntimeIncidentNotificationActionResponse**](OperatorRuntimeIncidentNotificationActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentNotificationRetrieve

> OperatorRuntimeIncidentNotificationDetail OperatorRuntimeIncidentNotificationRetrieve(ctx, outboxId).Execute()

Retrieve runtime incident notification delivery

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
	outboxId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentNotificationRetrieve(context.Background(), outboxId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentNotificationRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentNotificationRetrieve`: OperatorRuntimeIncidentNotificationDetail
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentNotificationRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**outboxId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentNotificationRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorRuntimeIncidentNotificationDetail**](OperatorRuntimeIncidentNotificationDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentNotificationRetry

> OperatorRuntimeIncidentNotificationActionResponse OperatorRuntimeIncidentNotificationRetry(ctx, outboxId).OperatorRuntimeIncidentNotificationActionRequestRequest(operatorRuntimeIncidentNotificationActionRequestRequest).Execute()

Retry failed runtime incident notification

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
	outboxId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorRuntimeIncidentNotificationActionRequestRequest := *openapiclient.NewOperatorRuntimeIncidentNotificationActionRequestRequest() // OperatorRuntimeIncidentNotificationActionRequestRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentNotificationRetry(context.Background(), outboxId).OperatorRuntimeIncidentNotificationActionRequestRequest(operatorRuntimeIncidentNotificationActionRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentNotificationRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentNotificationRetry`: OperatorRuntimeIncidentNotificationActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentNotificationRetry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**outboxId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentNotificationRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operatorRuntimeIncidentNotificationActionRequestRequest** | [**OperatorRuntimeIncidentNotificationActionRequestRequest**](OperatorRuntimeIncidentNotificationActionRequestRequest.md) |  | 

### Return type

[**OperatorRuntimeIncidentNotificationActionResponse**](OperatorRuntimeIncidentNotificationActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentNotificationSearch

> PaginatedOperatorRuntimeIncidentNotificationListList OperatorRuntimeIncidentNotificationSearch(ctx).ConsumerCode(consumerCode).ConsumerId(consumerId).CreatedFrom(createdFrom).CreatedTo(createdTo).EventId(eventId).EventType(eventType).IncidentId(incidentId).LeaseExpired(leaseExpired).Leased(leased).NextAttemptFrom(nextAttemptFrom).NextAttemptTo(nextAttemptTo).OccurrenceId(occurrenceId).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).Ready(ready).Severity(severity).Status(status).TenantKey(tenantKey).Execute()

Search runtime incident notification deliveries

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
	consumerCode := "consumerCode_example" // string |  (optional)
	consumerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	createdFrom := time.Now() // time.Time |  (optional)
	createdTo := time.Now() // time.Time |  (optional)
	eventId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	eventType := "eventType_example" // string |  (optional)
	incidentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	leaseExpired := true // bool |  (optional)
	leased := true // bool |  (optional)
	nextAttemptFrom := time.Now() // time.Time |  (optional)
	nextAttemptTo := time.Now() // time.Time |  (optional)
	occurrenceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	ordering := "ordering_example" // string | * `next_attempt_at` - next_attempt_at * `-next_attempt_at` - -next_attempt_at * `created_at` - created_at * `-created_at` - -created_at * `attempt_count` - attempt_count * `-attempt_count` - -attempt_count * `event_type` - event_type * `-event_type` - -event_type * `status` - status * `-status` - -status (optional) (default to "next_attempt_at")
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	page := int32(56) // int32 | A page number within the paginated result set. (optional)
	pageSize := int32(56) // int32 | Number of results to return per page. (optional)
	ready := true // bool |  (optional)
	severity := "severity_example" // string |  (optional)
	status := "status_example" // string | * `pending` - Pending * `publishing` - Publishing * `published` - Published * `failed` - Failed * `dead_letter` - Dead letter (optional)
	tenantKey := "tenantKey_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentNotificationSearch(context.Background()).ConsumerCode(consumerCode).ConsumerId(consumerId).CreatedFrom(createdFrom).CreatedTo(createdTo).EventId(eventId).EventType(eventType).IncidentId(incidentId).LeaseExpired(leaseExpired).Leased(leased).NextAttemptFrom(nextAttemptFrom).NextAttemptTo(nextAttemptTo).OccurrenceId(occurrenceId).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).Ready(ready).Severity(severity).Status(status).TenantKey(tenantKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentNotificationSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentNotificationSearch`: PaginatedOperatorRuntimeIncidentNotificationListList
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentNotificationSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentNotificationSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **consumerCode** | **string** |  | 
 **consumerId** | **string** |  | 
 **createdFrom** | **time.Time** |  | 
 **createdTo** | **time.Time** |  | 
 **eventId** | **string** |  | 
 **eventType** | **string** |  | 
 **incidentId** | **string** |  | 
 **leaseExpired** | **bool** |  | 
 **leased** | **bool** |  | 
 **nextAttemptFrom** | **time.Time** |  | 
 **nextAttemptTo** | **time.Time** |  | 
 **occurrenceId** | **string** |  | 
 **ordering** | **string** | * &#x60;next_attempt_at&#x60; - next_attempt_at * &#x60;-next_attempt_at&#x60; - -next_attempt_at * &#x60;created_at&#x60; - created_at * &#x60;-created_at&#x60; - -created_at * &#x60;attempt_count&#x60; - attempt_count * &#x60;-attempt_count&#x60; - -attempt_count * &#x60;event_type&#x60; - event_type * &#x60;-event_type&#x60; - -event_type * &#x60;status&#x60; - status * &#x60;-status&#x60; - -status | [default to &quot;next_attempt_at&quot;]
 **organizationId** | **string** |  | 
 **page** | **int32** | A page number within the paginated result set. | 
 **pageSize** | **int32** | Number of results to return per page. | 
 **ready** | **bool** |  | 
 **severity** | **string** |  | 
 **status** | **string** | * &#x60;pending&#x60; - Pending * &#x60;publishing&#x60; - Publishing * &#x60;published&#x60; - Published * &#x60;failed&#x60; - Failed * &#x60;dead_letter&#x60; - Dead letter | 
 **tenantKey** | **string** |  | 

### Return type

[**PaginatedOperatorRuntimeIncidentNotificationListList**](PaginatedOperatorRuntimeIncidentNotificationListList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentNotificationSummary

> OperatorRuntimeIncidentNotificationSummary OperatorRuntimeIncidentNotificationSummary(ctx).Execute()

Retrieve notification delivery backlog summary

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
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentNotificationSummary(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentNotificationSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentNotificationSummary`: OperatorRuntimeIncidentNotificationSummary
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentNotificationSummary`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentNotificationSummaryRequest struct via the builder pattern


### Return type

[**OperatorRuntimeIncidentNotificationSummary**](OperatorRuntimeIncidentNotificationSummary.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentOccurrenceList

> PaginatedOperatorRuntimeIncidentOccurrenceList OperatorRuntimeIncidentOccurrenceList(ctx, incidentId).Page(page).PageSize(pageSize).Execute()

List runtime incident occurrences

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
	incidentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	page := int32(56) // int32 | A page number within the paginated result set. (optional)
	pageSize := int32(56) // int32 | Number of results to return per page. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentOccurrenceList(context.Background(), incidentId).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentOccurrenceList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentOccurrenceList`: PaginatedOperatorRuntimeIncidentOccurrenceList
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentOccurrenceList`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**incidentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentOccurrenceListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | A page number within the paginated result set. | 
 **pageSize** | **int32** | Number of results to return per page. | 

### Return type

[**PaginatedOperatorRuntimeIncidentOccurrenceList**](PaginatedOperatorRuntimeIncidentOccurrenceList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentReopen

> OperatorRuntimeIncidentActionResponse OperatorRuntimeIncidentReopen(ctx, incidentId).OperatorRuntimeIncidentActionRequestRequest(operatorRuntimeIncidentActionRequestRequest).Execute()

Reopen runtime incident

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
	incidentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorRuntimeIncidentActionRequestRequest := *openapiclient.NewOperatorRuntimeIncidentActionRequestRequest() // OperatorRuntimeIncidentActionRequestRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentReopen(context.Background(), incidentId).OperatorRuntimeIncidentActionRequestRequest(operatorRuntimeIncidentActionRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentReopen``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentReopen`: OperatorRuntimeIncidentActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentReopen`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**incidentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentReopenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operatorRuntimeIncidentActionRequestRequest** | [**OperatorRuntimeIncidentActionRequestRequest**](OperatorRuntimeIncidentActionRequestRequest.md) |  | 

### Return type

[**OperatorRuntimeIncidentActionResponse**](OperatorRuntimeIncidentActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentResolve

> OperatorRuntimeIncidentActionResponse OperatorRuntimeIncidentResolve(ctx, incidentId).OperatorRuntimeIncidentActionRequestRequest(operatorRuntimeIncidentActionRequestRequest).Execute()

Resolve runtime incident

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
	incidentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorRuntimeIncidentActionRequestRequest := *openapiclient.NewOperatorRuntimeIncidentActionRequestRequest() // OperatorRuntimeIncidentActionRequestRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentResolve(context.Background(), incidentId).OperatorRuntimeIncidentActionRequestRequest(operatorRuntimeIncidentActionRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentResolve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentResolve`: OperatorRuntimeIncidentActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentResolve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**incidentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentResolveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operatorRuntimeIncidentActionRequestRequest** | [**OperatorRuntimeIncidentActionRequestRequest**](OperatorRuntimeIncidentActionRequestRequest.md) |  | 

### Return type

[**OperatorRuntimeIncidentActionResponse**](OperatorRuntimeIncidentActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentRetrieve

> OperatorRuntimeIncidentDetail OperatorRuntimeIncidentRetrieve(ctx, incidentId).Execute()

Retrieve runtime incident

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
	incidentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentRetrieve(context.Background(), incidentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentRetrieve`: OperatorRuntimeIncidentDetail
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**incidentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorRuntimeIncidentDetail**](OperatorRuntimeIncidentDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorRuntimeIncidentSearch

> PaginatedOperatorRuntimeIncidentListList OperatorRuntimeIncidentSearch(ctx).Acknowledged(acknowledged).Active(active).ConsumerCode(consumerCode).ConsumerId(consumerId).FirstDetectedFrom(firstDetectedFrom).FirstDetectedTo(firstDetectedTo).LastDetectedFrom(lastDetectedFrom).LastDetectedTo(lastDetectedTo).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).RuleCode(ruleCode).Scope(scope).Severity(severity).Status(status).Execute()

Search runtime incidents



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
	acknowledged := true // bool |  (optional)
	active := true // bool |  (optional)
	consumerCode := "consumerCode_example" // string |  (optional)
	consumerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	firstDetectedFrom := time.Now() // time.Time |  (optional)
	firstDetectedTo := time.Now() // time.Time |  (optional)
	lastDetectedFrom := time.Now() // time.Time |  (optional)
	lastDetectedTo := time.Now() // time.Time |  (optional)
	ordering := "ordering_example" // string | * `-last_detected_at` - -last_detected_at * `last_detected_at` - last_detected_at * `-first_detected_at` - -first_detected_at * `first_detected_at` - first_detected_at * `-severity` - -severity * `severity` - severity * `-occurrence_count` - -occurrence_count * `occurrence_count` - occurrence_count * `consumer_code` - consumer_code * `-consumer_code` - -consumer_code (optional) (default to "-last_detected_at")
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	page := int32(56) // int32 | A page number within the paginated result set. (optional)
	pageSize := int32(56) // int32 | Number of results to return per page. (optional)
	ruleCode := "ruleCode_example" // string |  (optional)
	scope := "scope_example" // string | * `platform` - Platform * `organization` - Organization * `consumer` - Consumer (optional)
	severity := "severity_example" // string | * `warning` - Warning * `critical` - Critical (optional)
	status := "status_example" // string | * `open` - Open * `acknowledged` - Acknowledged * `resolved` - Resolved (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorsAPI.OperatorRuntimeIncidentSearch(context.Background()).Acknowledged(acknowledged).Active(active).ConsumerCode(consumerCode).ConsumerId(consumerId).FirstDetectedFrom(firstDetectedFrom).FirstDetectedTo(firstDetectedTo).LastDetectedFrom(lastDetectedFrom).LastDetectedTo(lastDetectedTo).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).RuleCode(ruleCode).Scope(scope).Severity(severity).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorsAPI.OperatorRuntimeIncidentSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorRuntimeIncidentSearch`: PaginatedOperatorRuntimeIncidentListList
	fmt.Fprintf(os.Stdout, "Response from `OperatorsAPI.OperatorRuntimeIncidentSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorRuntimeIncidentSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acknowledged** | **bool** |  | 
 **active** | **bool** |  | 
 **consumerCode** | **string** |  | 
 **consumerId** | **string** |  | 
 **firstDetectedFrom** | **time.Time** |  | 
 **firstDetectedTo** | **time.Time** |  | 
 **lastDetectedFrom** | **time.Time** |  | 
 **lastDetectedTo** | **time.Time** |  | 
 **ordering** | **string** | * &#x60;-last_detected_at&#x60; - -last_detected_at * &#x60;last_detected_at&#x60; - last_detected_at * &#x60;-first_detected_at&#x60; - -first_detected_at * &#x60;first_detected_at&#x60; - first_detected_at * &#x60;-severity&#x60; - -severity * &#x60;severity&#x60; - severity * &#x60;-occurrence_count&#x60; - -occurrence_count * &#x60;occurrence_count&#x60; - occurrence_count * &#x60;consumer_code&#x60; - consumer_code * &#x60;-consumer_code&#x60; - -consumer_code | [default to &quot;-last_detected_at&quot;]
 **organizationId** | **string** |  | 
 **page** | **int32** | A page number within the paginated result set. | 
 **pageSize** | **int32** | Number of results to return per page. | 
 **ruleCode** | **string** |  | 
 **scope** | **string** | * &#x60;platform&#x60; - Platform * &#x60;organization&#x60; - Organization * &#x60;consumer&#x60; - Consumer | 
 **severity** | **string** | * &#x60;warning&#x60; - Warning * &#x60;critical&#x60; - Critical | 
 **status** | **string** | * &#x60;open&#x60; - Open * &#x60;acknowledged&#x60; - Acknowledged * &#x60;resolved&#x60; - Resolved | 

### Return type

[**PaginatedOperatorRuntimeIncidentListList**](PaginatedOperatorRuntimeIncidentListList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

