# \LifecycleReportsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorSaasLifecycleReportsActionCreate**](LifecycleReportsAPI.md#OperatorSaasLifecycleReportsActionCreate) | **Post** /api/v1/operator/saas/lifecycle/reports/{report_id}/action/ | 
[**OperatorSaasLifecycleReportsActionRetrieve**](LifecycleReportsAPI.md#OperatorSaasLifecycleReportsActionRetrieve) | **Get** /api/v1/operator/saas/lifecycle/reports/{report_id}/action/ | 
[**OperatorSaasLifecycleReportsCreate**](LifecycleReportsAPI.md#OperatorSaasLifecycleReportsCreate) | **Post** /api/v1/operator/saas/lifecycle/reports/ | 
[**OperatorSaasLifecycleReportsDownloadRetrieve**](LifecycleReportsAPI.md#OperatorSaasLifecycleReportsDownloadRetrieve) | **Get** /api/v1/operator/saas/lifecycle/reports/{report_id}/download/ | 
[**OperatorSaasLifecycleReportsList**](LifecycleReportsAPI.md#OperatorSaasLifecycleReportsList) | **Get** /api/v1/operator/saas/lifecycle/reports/ | 
[**OperatorSaasLifecycleReportsRetrieve**](LifecycleReportsAPI.md#OperatorSaasLifecycleReportsRetrieve) | **Get** /api/v1/operator/saas/lifecycle/reports/{report_id}/ | 



## OperatorSaasLifecycleReportsActionCreate

> LifecycleReport OperatorSaasLifecycleReportsActionCreate(ctx, reportId).LifecycleReportActionRequest(lifecycleReportActionRequest).Execute()



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
	reportId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	lifecycleReportActionRequest := *openapiclient.NewLifecycleReportActionRequest(openapiclient.LifecycleReportActionActionEnum("regenerate")) // LifecycleReportActionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleReportsAPI.OperatorSaasLifecycleReportsActionCreate(context.Background(), reportId).LifecycleReportActionRequest(lifecycleReportActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleReportsAPI.OperatorSaasLifecycleReportsActionCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleReportsActionCreate`: LifecycleReport
	fmt.Fprintf(os.Stdout, "Response from `LifecycleReportsAPI.OperatorSaasLifecycleReportsActionCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleReportsActionCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **lifecycleReportActionRequest** | [**LifecycleReportActionRequest**](LifecycleReportActionRequest.md) |  | 

### Return type

[**LifecycleReport**](LifecycleReport.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleReportsActionRetrieve

> LifecycleReport OperatorSaasLifecycleReportsActionRetrieve(ctx, reportId).Execute()



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
	reportId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleReportsAPI.OperatorSaasLifecycleReportsActionRetrieve(context.Background(), reportId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleReportsAPI.OperatorSaasLifecycleReportsActionRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleReportsActionRetrieve`: LifecycleReport
	fmt.Fprintf(os.Stdout, "Response from `LifecycleReportsAPI.OperatorSaasLifecycleReportsActionRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleReportsActionRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LifecycleReport**](LifecycleReport.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleReportsCreate

> LifecycleReport OperatorSaasLifecycleReportsCreate(ctx).LifecycleReportRequestRequest(lifecycleReportRequestRequest).Execute()



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
	lifecycleReportRequestRequest := *openapiclient.NewLifecycleReportRequestRequest(openapiclient.LifecycleReportRequestReportTypeEnum("compliance"), "IdempotencyKey_example") // LifecycleReportRequestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleReportsAPI.OperatorSaasLifecycleReportsCreate(context.Background()).LifecycleReportRequestRequest(lifecycleReportRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleReportsAPI.OperatorSaasLifecycleReportsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleReportsCreate`: LifecycleReport
	fmt.Fprintf(os.Stdout, "Response from `LifecycleReportsAPI.OperatorSaasLifecycleReportsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleReportsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **lifecycleReportRequestRequest** | [**LifecycleReportRequestRequest**](LifecycleReportRequestRequest.md) |  | 

### Return type

[**LifecycleReport**](LifecycleReport.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleReportsDownloadRetrieve

> OperatorSaasLifecycleReportsDownloadRetrieve(ctx, reportId).Execute()



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
	reportId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.LifecycleReportsAPI.OperatorSaasLifecycleReportsDownloadRetrieve(context.Background(), reportId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleReportsAPI.OperatorSaasLifecycleReportsDownloadRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleReportsDownloadRetrieveRequest struct via the builder pattern


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


## OperatorSaasLifecycleReportsList

> []LifecycleReport OperatorSaasLifecycleReportsList(ctx).ReportType(reportType).Status(status).Execute()



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
	reportType := "reportType_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleReportsAPI.OperatorSaasLifecycleReportsList(context.Background()).ReportType(reportType).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleReportsAPI.OperatorSaasLifecycleReportsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleReportsList`: []LifecycleReport
	fmt.Fprintf(os.Stdout, "Response from `LifecycleReportsAPI.OperatorSaasLifecycleReportsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleReportsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reportType** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**[]LifecycleReport**](LifecycleReport.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleReportsRetrieve

> LifecycleReport OperatorSaasLifecycleReportsRetrieve(ctx, reportId).Execute()



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
	reportId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleReportsAPI.OperatorSaasLifecycleReportsRetrieve(context.Background(), reportId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleReportsAPI.OperatorSaasLifecycleReportsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleReportsRetrieve`: LifecycleReport
	fmt.Fprintf(os.Stdout, "Response from `LifecycleReportsAPI.OperatorSaasLifecycleReportsRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleReportsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LifecycleReport**](LifecycleReport.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

