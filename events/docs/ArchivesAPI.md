# \ArchivesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ArchivesHealthRetrieve**](ArchivesAPI.md#ArchivesHealthRetrieve) | **Get** /api/v1/archives/health/ | Get archive worker health
[**ArchivesJobsCancel**](ArchivesAPI.md#ArchivesJobsCancel) | **Post** /api/v1/archives/jobs/{job_id}/cancel/ | Cancel a pending archive job
[**ArchivesJobsCreate**](ArchivesAPI.md#ArchivesJobsCreate) | **Post** /api/v1/archives/jobs/ | Create an archive job
[**ArchivesJobsDownload**](ArchivesAPI.md#ArchivesJobsDownload) | **Get** /api/v1/archives/jobs/{job_id}/download/ | Download an archived event file
[**ArchivesJobsList**](ArchivesAPI.md#ArchivesJobsList) | **Get** /api/v1/archives/jobs/ | List archive jobs
[**ArchivesJobsManifestRetrieve**](ArchivesAPI.md#ArchivesJobsManifestRetrieve) | **Get** /api/v1/archives/jobs/{job_id}/manifest/ | Get an archive manifest
[**ArchivesJobsRetrieve**](ArchivesAPI.md#ArchivesJobsRetrieve) | **Get** /api/v1/archives/jobs/{job_id}/ | Get an archive job
[**ArchivesJobsRetry**](ArchivesAPI.md#ArchivesJobsRetry) | **Post** /api/v1/archives/jobs/{job_id}/retry/ | Retry a failed archive job



## ArchivesHealthRetrieve

> ArchivesHealthRetrieve(ctx).Execute()

Get archive worker health

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
	r, err := apiClient.ArchivesAPI.ArchivesHealthRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesHealthRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiArchivesHealthRetrieveRequest struct via the builder pattern


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


## ArchivesJobsCancel

> ArchivesJobsCancel(ctx, jobId).ArchiveActionRequest(archiveActionRequest).Execute()

Cancel a pending archive job

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
	archiveActionRequest := *openapiclient.NewArchiveActionRequest() // ArchiveActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ArchivesAPI.ArchivesJobsCancel(context.Background(), jobId).ArchiveActionRequest(archiveActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesJobsCancel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchivesJobsCancelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **archiveActionRequest** | [**ArchiveActionRequest**](ArchiveActionRequest.md) |  | 

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


## ArchivesJobsCreate

> ArchivesJobsCreate(ctx).ArchiveJobCreateRequest(archiveJobCreateRequest).Execute()

Create an archive job

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
	archiveJobCreateRequest := *openapiclient.NewArchiveJobCreateRequest("Source_example", "IdempotencyKey_example", time.Now(), time.Now()) // ArchiveJobCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ArchivesAPI.ArchivesJobsCreate(context.Background()).ArchiveJobCreateRequest(archiveJobCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesJobsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiArchivesJobsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **archiveJobCreateRequest** | [**ArchiveJobCreateRequest**](ArchiveJobCreateRequest.md) |  | 

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


## ArchivesJobsDownload

> ArchivesJobsDownload(ctx, jobId).Execute()

Download an archived event file

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
	r, err := apiClient.ArchivesAPI.ArchivesJobsDownload(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesJobsDownload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchivesJobsDownloadRequest struct via the builder pattern


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


## ArchivesJobsList

> ArchivesJobsList(ctx).CreatedAfter(createdAfter).CreatedBefore(createdBefore).Ordering(ordering).Page(page).PageSize(pageSize).Source(source).Status(status).Execute()

List archive jobs

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
	createdAfter := "createdAfter_example" // string |  (optional)
	createdBefore := "createdBefore_example" // string |  (optional)
	ordering := "ordering_example" // string |  (optional)
	page := int32(56) // int32 |  (optional)
	pageSize := int32(56) // int32 |  (optional)
	source := "source_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ArchivesAPI.ArchivesJobsList(context.Background()).CreatedAfter(createdAfter).CreatedBefore(createdBefore).Ordering(ordering).Page(page).PageSize(pageSize).Source(source).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesJobsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiArchivesJobsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createdAfter** | **string** |  | 
 **createdBefore** | **string** |  | 
 **ordering** | **string** |  | 
 **page** | **int32** |  | 
 **pageSize** | **int32** |  | 
 **source** | **string** |  | 
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


## ArchivesJobsManifestRetrieve

> ArchivesJobsManifestRetrieve(ctx, jobId).Execute()

Get an archive manifest

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
	r, err := apiClient.ArchivesAPI.ArchivesJobsManifestRetrieve(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesJobsManifestRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchivesJobsManifestRetrieveRequest struct via the builder pattern


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


## ArchivesJobsRetrieve

> ArchivesJobsRetrieve(ctx, jobId).Execute()

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
	r, err := apiClient.ArchivesAPI.ArchivesJobsRetrieve(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesJobsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchivesJobsRetrieveRequest struct via the builder pattern


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


## ArchivesJobsRetry

> ArchivesJobsRetry(ctx, jobId).ArchiveActionRequest(archiveActionRequest).Execute()

Retry a failed archive job

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
	archiveActionRequest := *openapiclient.NewArchiveActionRequest() // ArchiveActionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ArchivesAPI.ArchivesJobsRetry(context.Background(), jobId).ArchiveActionRequest(archiveActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ArchivesAPI.ArchivesJobsRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchivesJobsRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **archiveActionRequest** | [**ArchiveActionRequest**](ArchiveActionRequest.md) |  | 

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

