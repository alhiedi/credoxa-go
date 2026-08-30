# \EventPublishingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PublishEvent**](EventPublishingAPI.md#PublishEvent) | **Post** /api/v1/events/ | Publish an event



## PublishEvent

> PublishEventEnvelope PublishEvent(ctx).IdempotencyKey(idempotencyKey).PublishEventRequestRequest(publishEventRequestRequest).Execute()

Publish an event



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
	idempotencyKey := "idempotencyKey_example" // string | Unique publication key scoped to the tenant and event source.
	publishEventRequestRequest := *openapiclient.NewPublishEventRequestRequest("EventType_example", int32(123), "Source_example", interface{}(123)) // PublishEventRequestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EventPublishingAPI.PublishEvent(context.Background()).IdempotencyKey(idempotencyKey).PublishEventRequestRequest(publishEventRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EventPublishingAPI.PublishEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishEvent`: PublishEventEnvelope
	fmt.Fprintf(os.Stdout, "Response from `EventPublishingAPI.PublishEvent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPublishEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idempotencyKey** | **string** | Unique publication key scoped to the tenant and event source. | 
 **publishEventRequestRequest** | [**PublishEventRequestRequest**](PublishEventRequestRequest.md) |  | 

### Return type

[**PublishEventEnvelope**](PublishEventEnvelope.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

