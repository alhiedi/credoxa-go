# \SaaSAnalyticsOperatorAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SaasAnalyticsRuntimeControl**](SaaSAnalyticsOperatorAPI.md#SaasAnalyticsRuntimeControl) | **Get** /api/v1/operator/saas/analytics/runtime-control/ | Get analytics runtime control snapshot



## SaasAnalyticsRuntimeControl

> SaasAnalyticsRuntimeControl(ctx).Execute()

Get analytics runtime control snapshot



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
	r, err := apiClient.SaaSAnalyticsOperatorAPI.SaasAnalyticsRuntimeControl(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SaaSAnalyticsOperatorAPI.SaasAnalyticsRuntimeControl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsRuntimeControlRequest struct via the builder pattern


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

