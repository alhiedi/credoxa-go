# \OperatorConsoleAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorArchivesCancel**](OperatorConsoleAPI.md#OperatorArchivesCancel) | **Post** /api/operators/v1/archives/{job_id}/cancel/ | Cancel an archive job
[**OperatorArchivesRetrieve**](OperatorConsoleAPI.md#OperatorArchivesRetrieve) | **Get** /api/operators/v1/archives/{job_id}/ | Get an archive job
[**OperatorArchivesRetry**](OperatorConsoleAPI.md#OperatorArchivesRetry) | **Post** /api/operators/v1/archives/{job_id}/retry/ | Retry an archive job
[**OperatorArchivesSearch**](OperatorConsoleAPI.md#OperatorArchivesSearch) | **Get** /api/operators/v1/archives/ | Search archive jobs across organizations
[**OperatorConsumersRetrieve**](OperatorConsoleAPI.md#OperatorConsumersRetrieve) | **Get** /api/operators/v1/consumers/{consumer_id}/ | Get a consumer registration
[**OperatorConsumersSearch**](OperatorConsoleAPI.md#OperatorConsumersSearch) | **Get** /api/operators/v1/consumers/ | Search consumers across organizations
[**OperatorConsumersSummaryRetrieve**](OperatorConsoleAPI.md#OperatorConsumersSummaryRetrieve) | **Get** /api/operators/v1/consumers/summary/ | Get consumer platform summary
[**OperatorPlatformSummaryRetrieve**](OperatorConsoleAPI.md#OperatorPlatformSummaryRetrieve) | **Get** /api/operators/v1/summary/ | Get operator platform summary
[**OperatorReplaysCancel**](OperatorConsoleAPI.md#OperatorReplaysCancel) | **Post** /api/operators/v1/replays/{replay_id}/cancel/ | Cancel a replay job
[**OperatorReplaysPause**](OperatorConsoleAPI.md#OperatorReplaysPause) | **Post** /api/operators/v1/replays/{replay_id}/pause/ | Pause a replay job
[**OperatorReplaysResume**](OperatorConsoleAPI.md#OperatorReplaysResume) | **Post** /api/operators/v1/replays/{replay_id}/resume/ | Resume a replay job
[**OperatorReplaysRetrieve**](OperatorConsoleAPI.md#OperatorReplaysRetrieve) | **Get** /api/operators/v1/replays/{replay_id}/ | Get a replay job
[**OperatorReplaysRetry**](OperatorConsoleAPI.md#OperatorReplaysRetry) | **Post** /api/operators/v1/replays/{replay_id}/retry/ | Retry a failed replay job
[**OperatorReplaysSearch**](OperatorConsoleAPI.md#OperatorReplaysSearch) | **Get** /api/operators/v1/replays/ | Search replay jobs across organizations



## OperatorArchivesCancel

> OperatorArchiveJob OperatorArchivesCancel(ctx, jobId).OperatorArchiveActionRequest(operatorArchiveActionRequest).Execute()

Cancel an archive job



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
	jobId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorArchiveActionRequest := *openapiclient.NewOperatorArchiveActionRequest() // OperatorArchiveActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorArchivesCancel(context.Background(), jobId).OperatorArchiveActionRequest(operatorArchiveActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorArchivesCancel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorArchivesCancel`: OperatorArchiveJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorArchivesCancel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorArchivesCancelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operatorArchiveActionRequest** | [**OperatorArchiveActionRequest**](OperatorArchiveActionRequest.md) |  | 

### Return type

[**OperatorArchiveJob**](OperatorArchiveJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorArchivesRetrieve

> OperatorArchiveJob OperatorArchivesRetrieve(ctx, jobId).Execute()

Get an archive job



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
	jobId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorArchivesRetrieve(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorArchivesRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorArchivesRetrieve`: OperatorArchiveJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorArchivesRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorArchivesRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorArchiveJob**](OperatorArchiveJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorArchivesRetry

> OperatorArchiveJob OperatorArchivesRetry(ctx, jobId).OperatorArchiveActionRequest(operatorArchiveActionRequest).Execute()

Retry an archive job



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
	jobId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	operatorArchiveActionRequest := *openapiclient.NewOperatorArchiveActionRequest() // OperatorArchiveActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorArchivesRetry(context.Background(), jobId).OperatorArchiveActionRequest(operatorArchiveActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorArchivesRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorArchivesRetry`: OperatorArchiveJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorArchivesRetry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorArchivesRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **operatorArchiveActionRequest** | [**OperatorArchiveActionRequest**](OperatorArchiveActionRequest.md) |  | 

### Return type

[**OperatorArchiveJob**](OperatorArchiveJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorArchivesSearch

> PaginatedOperatorArchiveJobList OperatorArchivesSearch(ctx).CompletedAfter(completedAfter).CompletedBefore(completedBefore).CreatedAfter(createdAfter).CreatedBefore(createdBefore).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).Retryable(retryable).Source(source).StartedAfter(startedAfter).StartedBefore(startedBefore).Status(status).Execute()

Search archive jobs across organizations



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
	completedAfter := "completedAfter_example" // string |  (optional)
	completedBefore := "completedBefore_example" // string |  (optional)
	createdAfter := "createdAfter_example" // string |  (optional)
	createdBefore := "createdBefore_example" // string |  (optional)
	ordering := "ordering_example" // string |  (optional)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	retryable := true // bool |  (optional)
	source := "source_example" // string |  (optional)
	startedAfter := "startedAfter_example" // string |  (optional)
	startedBefore := "startedBefore_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorArchivesSearch(context.Background()).CompletedAfter(completedAfter).CompletedBefore(completedBefore).CreatedAfter(createdAfter).CreatedBefore(createdBefore).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).Retryable(retryable).Source(source).StartedAfter(startedAfter).StartedBefore(startedBefore).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorArchivesSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorArchivesSearch`: PaginatedOperatorArchiveJobList
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorArchivesSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorArchivesSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **completedAfter** | **string** |  | 
 **completedBefore** | **string** |  | 
 **createdAfter** | **string** |  | 
 **createdBefore** | **string** |  | 
 **ordering** | **string** |  | 
 **organizationId** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **retryable** | **bool** |  | 
 **source** | **string** |  | 
 **startedAfter** | **string** |  | 
 **startedBefore** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**PaginatedOperatorArchiveJobList**](PaginatedOperatorArchiveJobList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorConsumersRetrieve

> OperatorConsumerDetail OperatorConsumersRetrieve(ctx, consumerId).Execute()

Get a consumer registration



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
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorConsumersRetrieve(context.Background(), consumerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorConsumersRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorConsumersRetrieve`: OperatorConsumerDetail
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorConsumersRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**consumerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorConsumersRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorConsumerDetail**](OperatorConsumerDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorConsumersSearch

> PaginatedOperatorConsumerRegistrationList OperatorConsumersSearch(ctx).Code(code).CreatedAfter(createdAfter).CreatedBefore(createdBefore).DeadLetterQueue(deadLetterQueue).Name(name).Ordering(ordering).OrganizationId(organizationId).OwnerService(ownerService).Page(page).PageSize(pageSize).QueueName(queueName).Status(status).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).Execute()

Search consumers across organizations



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
	code := "code_example" // string |  (optional)
	createdAfter := "createdAfter_example" // string |  (optional)
	createdBefore := "createdBefore_example" // string |  (optional)
	deadLetterQueue := "deadLetterQueue_example" // string |  (optional)
	name := "name_example" // string |  (optional)
	ordering := "ordering_example" // string |  (optional)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	ownerService := "ownerService_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	queueName := "queueName_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	updatedAfter := "updatedAfter_example" // string |  (optional)
	updatedBefore := "updatedBefore_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorConsumersSearch(context.Background()).Code(code).CreatedAfter(createdAfter).CreatedBefore(createdBefore).DeadLetterQueue(deadLetterQueue).Name(name).Ordering(ordering).OrganizationId(organizationId).OwnerService(ownerService).Page(page).PageSize(pageSize).QueueName(queueName).Status(status).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorConsumersSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorConsumersSearch`: PaginatedOperatorConsumerRegistrationList
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorConsumersSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorConsumersSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **code** | **string** |  | 
 **createdAfter** | **string** |  | 
 **createdBefore** | **string** |  | 
 **deadLetterQueue** | **string** |  | 
 **name** | **string** |  | 
 **ordering** | **string** |  | 
 **organizationId** | **string** |  | 
 **ownerService** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **queueName** | **string** |  | 
 **status** | **string** |  | 
 **updatedAfter** | **string** |  | 
 **updatedBefore** | **string** |  | 

### Return type

[**PaginatedOperatorConsumerRegistrationList**](PaginatedOperatorConsumerRegistrationList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorConsumersSummaryRetrieve

> OperatorConsumerSummary OperatorConsumersSummaryRetrieve(ctx).Execute()

Get consumer platform summary



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
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorConsumersSummaryRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorConsumersSummaryRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorConsumersSummaryRetrieve`: OperatorConsumerSummary
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorConsumersSummaryRetrieve`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorConsumersSummaryRetrieveRequest struct via the builder pattern


### Return type

[**OperatorConsumerSummary**](OperatorConsumerSummary.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorPlatformSummaryRetrieve

> OperatorPlatformSummary OperatorPlatformSummaryRetrieve(ctx).Execute()

Get operator platform summary



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
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorPlatformSummaryRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorPlatformSummaryRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorPlatformSummaryRetrieve`: OperatorPlatformSummary
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorPlatformSummaryRetrieve`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorPlatformSummaryRetrieveRequest struct via the builder pattern


### Return type

[**OperatorPlatformSummary**](OperatorPlatformSummary.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorReplaysCancel

> OperatorReplayJob OperatorReplaysCancel(ctx, replayId).Execute()

Cancel a replay job



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
	replayId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorReplaysCancel(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorReplaysCancel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorReplaysCancel`: OperatorReplayJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorReplaysCancel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorReplaysCancelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorReplayJob**](OperatorReplayJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorReplaysPause

> OperatorReplayJob OperatorReplaysPause(ctx, replayId).Execute()

Pause a replay job



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
	replayId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorReplaysPause(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorReplaysPause``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorReplaysPause`: OperatorReplayJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorReplaysPause`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorReplaysPauseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorReplayJob**](OperatorReplayJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorReplaysResume

> OperatorReplayJob OperatorReplaysResume(ctx, replayId).Execute()

Resume a replay job



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
	replayId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorReplaysResume(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorReplaysResume``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorReplaysResume`: OperatorReplayJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorReplaysResume`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorReplaysResumeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorReplayJob**](OperatorReplayJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorReplaysRetrieve

> OperatorReplayJob OperatorReplaysRetrieve(ctx, replayId).Execute()

Get a replay job



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
	replayId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorReplaysRetrieve(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorReplaysRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorReplaysRetrieve`: OperatorReplayJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorReplaysRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorReplaysRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperatorReplayJob**](OperatorReplayJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorReplaysRetry

> OperatorReplayJob OperatorReplaysRetry(ctx, replayId).ReplayRetryRequest(replayRetryRequest).Execute()

Retry a failed replay job



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
	replayId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	replayRetryRequest := *openapiclient.NewReplayRetryRequest() // ReplayRetryRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorReplaysRetry(context.Background(), replayId).ReplayRetryRequest(replayRetryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorReplaysRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorReplaysRetry`: OperatorReplayJob
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorReplaysRetry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorReplaysRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **replayRetryRequest** | [**ReplayRetryRequest**](ReplayRetryRequest.md) |  | 

### Return type

[**OperatorReplayJob**](OperatorReplayJob.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorReplaysSearch

> PaginatedOperatorReplayJobList OperatorReplaysSearch(ctx).CompletedAfter(completedAfter).CompletedBefore(completedBefore).CreatedAfter(createdAfter).CreatedBefore(createdBefore).FailedAfter(failedAfter).FailedBefore(failedBefore).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).RequestedBy(requestedBy).StartedAfter(startedAfter).StartedBefore(startedBefore).Status(status).TargetConsumerId(targetConsumerId).Execute()

Search replay jobs across organizations



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
	completedAfter := "completedAfter_example" // string |  (optional)
	completedBefore := "completedBefore_example" // string |  (optional)
	createdAfter := "createdAfter_example" // string |  (optional)
	createdBefore := "createdBefore_example" // string |  (optional)
	failedAfter := "failedAfter_example" // string |  (optional)
	failedBefore := "failedBefore_example" // string |  (optional)
	ordering := "ordering_example" // string |  (optional)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	requestedBy := "requestedBy_example" // string |  (optional)
	startedAfter := "startedAfter_example" // string |  (optional)
	startedBefore := "startedBefore_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	targetConsumerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorConsoleAPI.OperatorReplaysSearch(context.Background()).CompletedAfter(completedAfter).CompletedBefore(completedBefore).CreatedAfter(createdAfter).CreatedBefore(createdBefore).FailedAfter(failedAfter).FailedBefore(failedBefore).Ordering(ordering).OrganizationId(organizationId).Page(page).PageSize(pageSize).RequestedBy(requestedBy).StartedAfter(startedAfter).StartedBefore(startedBefore).Status(status).TargetConsumerId(targetConsumerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorConsoleAPI.OperatorReplaysSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorReplaysSearch`: PaginatedOperatorReplayJobList
	fmt.Fprintf(os.Stdout, "Response from `OperatorConsoleAPI.OperatorReplaysSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorReplaysSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **completedAfter** | **string** |  | 
 **completedBefore** | **string** |  | 
 **createdAfter** | **string** |  | 
 **createdBefore** | **string** |  | 
 **failedAfter** | **string** |  | 
 **failedBefore** | **string** |  | 
 **ordering** | **string** |  | 
 **organizationId** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **requestedBy** | **string** |  | 
 **startedAfter** | **string** |  | 
 **startedBefore** | **string** |  | 
 **status** | **string** |  | 
 **targetConsumerId** | **string** |  | 

### Return type

[**PaginatedOperatorReplayJobList**](PaginatedOperatorReplayJobList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

