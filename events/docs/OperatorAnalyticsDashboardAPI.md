# \OperatorAnalyticsDashboardAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorAnalyticsDashboardSummary**](OperatorAnalyticsDashboardAPI.md#OperatorAnalyticsDashboardSummary) | **Get** /api/v1/operator/saas/analytics/dashboard/ | Retrieve the complete analytics operator dashboard



## OperatorAnalyticsDashboardSummary

> OperatorAnalyticsDashboardSummary(ctx).OrganizationId(organizationId).Execute()

Retrieve the complete analytics operator dashboard

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OperatorAnalyticsDashboardAPI.OperatorAnalyticsDashboardSummary(context.Background()).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAnalyticsDashboardAPI.OperatorAnalyticsDashboardSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorAnalyticsDashboardSummaryRequest struct via the builder pattern


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

