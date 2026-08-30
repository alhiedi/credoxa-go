# \LifecycleAlertsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorSaasLifecycleAlertsActionCreate**](LifecycleAlertsAPI.md#OperatorSaasLifecycleAlertsActionCreate) | **Post** /api/v1/operator/saas/lifecycle/alerts/{alert_id}/action/ | 
[**OperatorSaasLifecycleAlertsActionRetrieve**](LifecycleAlertsAPI.md#OperatorSaasLifecycleAlertsActionRetrieve) | **Get** /api/v1/operator/saas/lifecycle/alerts/{alert_id}/action/ | 
[**OperatorSaasLifecycleAlertsList**](LifecycleAlertsAPI.md#OperatorSaasLifecycleAlertsList) | **Get** /api/v1/operator/saas/lifecycle/alerts/ | 
[**OperatorSaasLifecycleAlertsRetrieve**](LifecycleAlertsAPI.md#OperatorSaasLifecycleAlertsRetrieve) | **Get** /api/v1/operator/saas/lifecycle/alerts/{alert_id}/ | 



## OperatorSaasLifecycleAlertsActionCreate

> LifecycleAlert OperatorSaasLifecycleAlertsActionCreate(ctx, alertId).LifecycleAlertActionRequest(lifecycleAlertActionRequest).Execute()



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	lifecycleAlertActionRequest := *openapiclient.NewLifecycleAlertActionRequest(openapiclient.LifecycleAlertActionActionEnum("acknowledge")) // LifecycleAlertActionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleAlertsAPI.OperatorSaasLifecycleAlertsActionCreate(context.Background(), alertId).LifecycleAlertActionRequest(lifecycleAlertActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsActionCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleAlertsActionCreate`: LifecycleAlert
	fmt.Fprintf(os.Stdout, "Response from `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsActionCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleAlertsActionCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **lifecycleAlertActionRequest** | [**LifecycleAlertActionRequest**](LifecycleAlertActionRequest.md) |  | 

### Return type

[**LifecycleAlert**](LifecycleAlert.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleAlertsActionRetrieve

> LifecycleAlert OperatorSaasLifecycleAlertsActionRetrieve(ctx, alertId).Execute()



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleAlertsAPI.OperatorSaasLifecycleAlertsActionRetrieve(context.Background(), alertId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsActionRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleAlertsActionRetrieve`: LifecycleAlert
	fmt.Fprintf(os.Stdout, "Response from `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsActionRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleAlertsActionRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LifecycleAlert**](LifecycleAlert.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleAlertsList

> []LifecycleAlert OperatorSaasLifecycleAlertsList(ctx).AlertType(alertType).Severity(severity).Status(status).Execute()



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
	alertType := "alertType_example" // string |  (optional)
	severity := "severity_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleAlertsAPI.OperatorSaasLifecycleAlertsList(context.Background()).AlertType(alertType).Severity(severity).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleAlertsList`: []LifecycleAlert
	fmt.Fprintf(os.Stdout, "Response from `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleAlertsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **alertType** | **string** |  | 
 **severity** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**[]LifecycleAlert**](LifecycleAlert.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleAlertsRetrieve

> LifecycleAlert OperatorSaasLifecycleAlertsRetrieve(ctx, alertId).Execute()



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleAlertsAPI.OperatorSaasLifecycleAlertsRetrieve(context.Background(), alertId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleAlertsRetrieve`: LifecycleAlert
	fmt.Fprintf(os.Stdout, "Response from `LifecycleAlertsAPI.OperatorSaasLifecycleAlertsRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleAlertsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LifecycleAlert**](LifecycleAlert.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

