# \LifecycleDashboardAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorSaasLifecycleDashboardBacklogRetrieve**](LifecycleDashboardAPI.md#OperatorSaasLifecycleDashboardBacklogRetrieve) | **Get** /api/v1/operator/saas/lifecycle/dashboard/backlog/ | 
[**OperatorSaasLifecycleDashboardComplianceRetrieve**](LifecycleDashboardAPI.md#OperatorSaasLifecycleDashboardComplianceRetrieve) | **Get** /api/v1/operator/saas/lifecycle/dashboard/compliance/ | 
[**OperatorSaasLifecycleDashboardExecutionsRetrieve**](LifecycleDashboardAPI.md#OperatorSaasLifecycleDashboardExecutionsRetrieve) | **Get** /api/v1/operator/saas/lifecycle/dashboard/executions/ | 
[**OperatorSaasLifecycleDashboardLegalHoldsRetrieve**](LifecycleDashboardAPI.md#OperatorSaasLifecycleDashboardLegalHoldsRetrieve) | **Get** /api/v1/operator/saas/lifecycle/dashboard/legal-holds/ | 
[**OperatorSaasLifecycleDashboardRetrieve**](LifecycleDashboardAPI.md#OperatorSaasLifecycleDashboardRetrieve) | **Get** /api/v1/operator/saas/lifecycle/dashboard/ | 



## OperatorSaasLifecycleDashboardBacklogRetrieve

> LifecycleBacklogView OperatorSaasLifecycleDashboardBacklogRetrieve(ctx).Execute()



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
	resp, r, err := apiClient.LifecycleDashboardAPI.OperatorSaasLifecycleDashboardBacklogRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardBacklogRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleDashboardBacklogRetrieve`: LifecycleBacklogView
	fmt.Fprintf(os.Stdout, "Response from `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardBacklogRetrieve`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleDashboardBacklogRetrieveRequest struct via the builder pattern


### Return type

[**LifecycleBacklogView**](LifecycleBacklogView.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleDashboardComplianceRetrieve

> LifecycleComplianceView OperatorSaasLifecycleDashboardComplianceRetrieve(ctx).Execute()



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
	resp, r, err := apiClient.LifecycleDashboardAPI.OperatorSaasLifecycleDashboardComplianceRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardComplianceRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleDashboardComplianceRetrieve`: LifecycleComplianceView
	fmt.Fprintf(os.Stdout, "Response from `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardComplianceRetrieve`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleDashboardComplianceRetrieveRequest struct via the builder pattern


### Return type

[**LifecycleComplianceView**](LifecycleComplianceView.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleDashboardExecutionsRetrieve

> OperatorSaasLifecycleDashboardExecutionsRetrieve(ctx).Execute()



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
	r, err := apiClient.LifecycleDashboardAPI.OperatorSaasLifecycleDashboardExecutionsRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardExecutionsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleDashboardExecutionsRetrieveRequest struct via the builder pattern


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


## OperatorSaasLifecycleDashboardLegalHoldsRetrieve

> OperatorSaasLifecycleDashboardLegalHoldsRetrieve(ctx).Execute()



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
	r, err := apiClient.LifecycleDashboardAPI.OperatorSaasLifecycleDashboardLegalHoldsRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardLegalHoldsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleDashboardLegalHoldsRetrieveRequest struct via the builder pattern


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


## OperatorSaasLifecycleDashboardRetrieve

> LifecycleDashboard OperatorSaasLifecycleDashboardRetrieve(ctx).Execute()



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
	resp, r, err := apiClient.LifecycleDashboardAPI.OperatorSaasLifecycleDashboardRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleDashboardRetrieve`: LifecycleDashboard
	fmt.Fprintf(os.Stdout, "Response from `LifecycleDashboardAPI.OperatorSaasLifecycleDashboardRetrieve`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleDashboardRetrieveRequest struct via the builder pattern


### Return type

[**LifecycleDashboard**](LifecycleDashboard.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

