# \ReplaysAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ReplaysCancelCreate**](ReplaysAPI.md#ReplaysCancelCreate) | **Post** /api/v1/replays/{replay_id}/cancel/ | Cancel replay job
[**ReplaysCreate**](ReplaysAPI.md#ReplaysCreate) | **Post** /api/v1/replays/ | Create replay job
[**ReplaysList**](ReplaysAPI.md#ReplaysList) | **Get** /api/v1/replays/ | List replay jobs
[**ReplaysPauseCreate**](ReplaysAPI.md#ReplaysPauseCreate) | **Post** /api/v1/replays/{replay_id}/pause/ | Pause replay job
[**ReplaysResumeCreate**](ReplaysAPI.md#ReplaysResumeCreate) | **Post** /api/v1/replays/{replay_id}/resume/ | Resume replay job
[**ReplaysRetrieve**](ReplaysAPI.md#ReplaysRetrieve) | **Get** /api/v1/replays/{replay_id}/ | Retrieve replay job
[**ReplaysRetryCreate**](ReplaysAPI.md#ReplaysRetryCreate) | **Post** /api/v1/replays/{replay_id}/retry/ | Retry failed replay job



## ReplaysCancelCreate

> ReplayDetail ReplaysCancelCreate(ctx, replayId).Execute()

Cancel replay job

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
	resp, r, err := apiClient.ReplaysAPI.ReplaysCancelCreate(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplaysAPI.ReplaysCancelCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaysCancelCreate`: ReplayDetail
	fmt.Fprintf(os.Stdout, "Response from `ReplaysAPI.ReplaysCancelCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReplaysCancelCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReplayDetail**](ReplayDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaysCreate

> ReplayDetail ReplaysCreate(ctx).ReplayCreateRequest(replayCreateRequest).Execute()

Create replay job



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
	replayCreateRequest := *openapiclient.NewReplayCreateRequest("TargetConsumerId_example") // ReplayCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReplaysAPI.ReplaysCreate(context.Background()).ReplayCreateRequest(replayCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplaysAPI.ReplaysCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaysCreate`: ReplayDetail
	fmt.Fprintf(os.Stdout, "Response from `ReplaysAPI.ReplaysCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReplaysCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **replayCreateRequest** | [**ReplayCreateRequest**](ReplayCreateRequest.md) |  | 

### Return type

[**ReplayDetail**](ReplayDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaysList

> []ReplayDetail ReplaysList(ctx).Status(status).TargetConsumer(targetConsumer).Execute()

List replay jobs



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
	status := "status_example" // string | Filter replay jobs by status. (optional)
	targetConsumer := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by target consumer UUID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReplaysAPI.ReplaysList(context.Background()).Status(status).TargetConsumer(targetConsumer).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplaysAPI.ReplaysList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaysList`: []ReplayDetail
	fmt.Fprintf(os.Stdout, "Response from `ReplaysAPI.ReplaysList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReplaysListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** | Filter replay jobs by status. | 
 **targetConsumer** | **string** | Filter by target consumer UUID. | 

### Return type

[**[]ReplayDetail**](ReplayDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaysPauseCreate

> ReplayDetail ReplaysPauseCreate(ctx, replayId).Execute()

Pause replay job

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
	resp, r, err := apiClient.ReplaysAPI.ReplaysPauseCreate(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplaysAPI.ReplaysPauseCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaysPauseCreate`: ReplayDetail
	fmt.Fprintf(os.Stdout, "Response from `ReplaysAPI.ReplaysPauseCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReplaysPauseCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReplayDetail**](ReplayDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaysResumeCreate

> ReplayDetail ReplaysResumeCreate(ctx, replayId).Execute()

Resume replay job

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
	resp, r, err := apiClient.ReplaysAPI.ReplaysResumeCreate(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplaysAPI.ReplaysResumeCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaysResumeCreate`: ReplayDetail
	fmt.Fprintf(os.Stdout, "Response from `ReplaysAPI.ReplaysResumeCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReplaysResumeCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReplayDetail**](ReplayDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaysRetrieve

> ReplayDetail ReplaysRetrieve(ctx, replayId).Execute()

Retrieve replay job



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
	resp, r, err := apiClient.ReplaysAPI.ReplaysRetrieve(context.Background(), replayId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplaysAPI.ReplaysRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaysRetrieve`: ReplayDetail
	fmt.Fprintf(os.Stdout, "Response from `ReplaysAPI.ReplaysRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReplaysRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReplayDetail**](ReplayDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaysRetryCreate

> ReplayDetail ReplaysRetryCreate(ctx, replayId).ReplayRetryRequest(replayRetryRequest).Execute()

Retry failed replay job

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
	resp, r, err := apiClient.ReplaysAPI.ReplaysRetryCreate(context.Background(), replayId).ReplayRetryRequest(replayRetryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReplaysAPI.ReplaysRetryCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaysRetryCreate`: ReplayDetail
	fmt.Fprintf(os.Stdout, "Response from `ReplaysAPI.ReplaysRetryCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**replayId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReplaysRetryCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **replayRetryRequest** | [**ReplayRetryRequest**](ReplayRetryRequest.md) |  | 

### Return type

[**ReplayDetail**](ReplayDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

