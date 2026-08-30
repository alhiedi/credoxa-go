# \LifecycleOperatorAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorSaasLifecycleBatchesList**](LifecycleOperatorAPI.md#OperatorSaasLifecycleBatchesList) | **Get** /api/v1/operator/saas/lifecycle/batches/ | 
[**OperatorSaasLifecycleDeadLettersActionCreate**](LifecycleOperatorAPI.md#OperatorSaasLifecycleDeadLettersActionCreate) | **Post** /api/v1/operator/saas/lifecycle/dead-letters/{batch_id}/{candidate_id}/action/ | 
[**OperatorSaasLifecycleDeadLettersRetrieve**](LifecycleOperatorAPI.md#OperatorSaasLifecycleDeadLettersRetrieve) | **Get** /api/v1/operator/saas/lifecycle/dead-letters/ | 
[**OperatorSaasLifecycleExecutionsControlCreate**](LifecycleOperatorAPI.md#OperatorSaasLifecycleExecutionsControlCreate) | **Post** /api/v1/operator/saas/lifecycle/executions/{execution_id}/control/ | 
[**OperatorSaasLifecycleExecutionsControlRetrieve**](LifecycleOperatorAPI.md#OperatorSaasLifecycleExecutionsControlRetrieve) | **Get** /api/v1/operator/saas/lifecycle/executions/{execution_id}/control/ | 
[**OperatorSaasLifecycleExecutionsList**](LifecycleOperatorAPI.md#OperatorSaasLifecycleExecutionsList) | **Get** /api/v1/operator/saas/lifecycle/executions/ | 
[**OperatorSaasLifecycleExecutionsRetrieve**](LifecycleOperatorAPI.md#OperatorSaasLifecycleExecutionsRetrieve) | **Get** /api/v1/operator/saas/lifecycle/executions/{execution_id}/ | 
[**OperatorSaasLifecycleLegalHoldsCreate**](LifecycleOperatorAPI.md#OperatorSaasLifecycleLegalHoldsCreate) | **Post** /api/v1/operator/saas/lifecycle/legal-holds/ | 
[**OperatorSaasLifecycleLegalHoldsList**](LifecycleOperatorAPI.md#OperatorSaasLifecycleLegalHoldsList) | **Get** /api/v1/operator/saas/lifecycle/legal-holds/ | 
[**OperatorSaasLifecycleLegalHoldsReleaseCreate**](LifecycleOperatorAPI.md#OperatorSaasLifecycleLegalHoldsReleaseCreate) | **Post** /api/v1/operator/saas/lifecycle/legal-holds/{hold_id}/release/ | 
[**OperatorSaasLifecycleLegalHoldsReleaseRetrieve**](LifecycleOperatorAPI.md#OperatorSaasLifecycleLegalHoldsReleaseRetrieve) | **Get** /api/v1/operator/saas/lifecycle/legal-holds/{hold_id}/release/ | 
[**OperatorSaasLifecycleLegalHoldsRetrieve**](LifecycleOperatorAPI.md#OperatorSaasLifecycleLegalHoldsRetrieve) | **Get** /api/v1/operator/saas/lifecycle/legal-holds/{hold_id}/ | 
[**OperatorSaasLifecyclePoliciesList**](LifecycleOperatorAPI.md#OperatorSaasLifecyclePoliciesList) | **Get** /api/v1/operator/saas/lifecycle/policies/ | 
[**OperatorSaasLifecyclePoliciesRetrieve**](LifecycleOperatorAPI.md#OperatorSaasLifecyclePoliciesRetrieve) | **Get** /api/v1/operator/saas/lifecycle/policies/{policy_id}/ | 
[**OperatorSaasLifecyclePolicyVersionsList**](LifecycleOperatorAPI.md#OperatorSaasLifecyclePolicyVersionsList) | **Get** /api/v1/operator/saas/lifecycle/policy-versions/ | 
[**OperatorSaasLifecycleTombstonesList**](LifecycleOperatorAPI.md#OperatorSaasLifecycleTombstonesList) | **Get** /api/v1/operator/saas/lifecycle/tombstones/ | 
[**OperatorSaasLifecycleTombstonesRetrieve**](LifecycleOperatorAPI.md#OperatorSaasLifecycleTombstonesRetrieve) | **Get** /api/v1/operator/saas/lifecycle/tombstones/{tombstone_id}/ | 



## OperatorSaasLifecycleBatchesList

> []LifecycleBatch OperatorSaasLifecycleBatchesList(ctx).ExecutionId(executionId).Kind(kind).Execute()



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
	executionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	kind := "kind_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleBatchesList(context.Background()).ExecutionId(executionId).Kind(kind).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleBatchesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleBatchesList`: []LifecycleBatch
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleBatchesList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleBatchesListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **executionId** | **string** |  | 
 **kind** | **string** |  | 

### Return type

[**[]LifecycleBatch**](LifecycleBatch.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleDeadLettersActionCreate

> OperatorSaasLifecycleDeadLettersActionCreate(ctx, batchId, candidateId).DeadLetterActionRequest(deadLetterActionRequest).Execute()



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
	batchId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	candidateId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	deadLetterActionRequest := *openapiclient.NewDeadLetterActionRequest(openapiclient.DeadLetterActionActionEnum("retry-approved")) // DeadLetterActionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleDeadLettersActionCreate(context.Background(), batchId, candidateId).DeadLetterActionRequest(deadLetterActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleDeadLettersActionCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**batchId** | **string** |  | 
**candidateId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleDeadLettersActionCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **deadLetterActionRequest** | [**DeadLetterActionRequest**](DeadLetterActionRequest.md) |  | 

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


## OperatorSaasLifecycleDeadLettersRetrieve

> OperatorSaasLifecycleDeadLettersRetrieve(ctx).Execute()



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
	r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleDeadLettersRetrieve(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleDeadLettersRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleDeadLettersRetrieveRequest struct via the builder pattern


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


## OperatorSaasLifecycleExecutionsControlCreate

> LifecycleExecution OperatorSaasLifecycleExecutionsControlCreate(ctx, executionId).LifecycleExecutionControlRequest(lifecycleExecutionControlRequest).Execute()



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
	executionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	lifecycleExecutionControlRequest := *openapiclient.NewLifecycleExecutionControlRequest(openapiclient.LifecycleExecutionControlActionEnum("pause")) // LifecycleExecutionControlRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsControlCreate(context.Background(), executionId).LifecycleExecutionControlRequest(lifecycleExecutionControlRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsControlCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleExecutionsControlCreate`: LifecycleExecution
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsControlCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleExecutionsControlCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **lifecycleExecutionControlRequest** | [**LifecycleExecutionControlRequest**](LifecycleExecutionControlRequest.md) |  | 

### Return type

[**LifecycleExecution**](LifecycleExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleExecutionsControlRetrieve

> LifecycleExecution OperatorSaasLifecycleExecutionsControlRetrieve(ctx, executionId).Execute()



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
	executionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsControlRetrieve(context.Background(), executionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsControlRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleExecutionsControlRetrieve`: LifecycleExecution
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsControlRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleExecutionsControlRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LifecycleExecution**](LifecycleExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleExecutionsList

> []LifecycleExecution OperatorSaasLifecycleExecutionsList(ctx).Kind(kind).Status(status).Execute()



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
	kind := "kind_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsList(context.Background()).Kind(kind).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleExecutionsList`: []LifecycleExecution
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleExecutionsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kind** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**[]LifecycleExecution**](LifecycleExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleExecutionsRetrieve

> LifecycleExecution OperatorSaasLifecycleExecutionsRetrieve(ctx, executionId).Execute()



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
	executionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsRetrieve(context.Background(), executionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleExecutionsRetrieve`: LifecycleExecution
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleExecutionsRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleExecutionsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LifecycleExecution**](LifecycleExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleLegalHoldsCreate

> LegalHold OperatorSaasLifecycleLegalHoldsCreate(ctx).LegalHoldCreateRequest(legalHoldCreateRequest).Execute()



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
	legalHoldCreateRequest := *openapiclient.NewLegalHoldCreateRequest("OrganizationId_example", openapiclient.ScopeKindEnum("tenant"), "Reason_example", "AuthorityReference_example", time.Now(), "CreatedBy_example", "Fingerprint_example") // LegalHoldCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsCreate(context.Background()).LegalHoldCreateRequest(legalHoldCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleLegalHoldsCreate`: LegalHold
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleLegalHoldsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **legalHoldCreateRequest** | [**LegalHoldCreateRequest**](LegalHoldCreateRequest.md) |  | 

### Return type

[**LegalHold**](LegalHold.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleLegalHoldsList

> []LegalHold OperatorSaasLifecycleLegalHoldsList(ctx).Execute()



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
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleLegalHoldsList`: []LegalHold
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleLegalHoldsListRequest struct via the builder pattern


### Return type

[**[]LegalHold**](LegalHold.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleLegalHoldsReleaseCreate

> LegalHold OperatorSaasLifecycleLegalHoldsReleaseCreate(ctx, holdId).LegalHoldReleaseRequest(legalHoldReleaseRequest).Execute()



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
	holdId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	legalHoldReleaseRequest := *openapiclient.NewLegalHoldReleaseRequest() // LegalHoldReleaseRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsReleaseCreate(context.Background(), holdId).LegalHoldReleaseRequest(legalHoldReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsReleaseCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleLegalHoldsReleaseCreate`: LegalHold
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsReleaseCreate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**holdId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleLegalHoldsReleaseCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **legalHoldReleaseRequest** | [**LegalHoldReleaseRequest**](LegalHoldReleaseRequest.md) |  | 

### Return type

[**LegalHold**](LegalHold.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleLegalHoldsReleaseRetrieve

> LegalHold OperatorSaasLifecycleLegalHoldsReleaseRetrieve(ctx, holdId).Execute()



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
	holdId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsReleaseRetrieve(context.Background(), holdId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsReleaseRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleLegalHoldsReleaseRetrieve`: LegalHold
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsReleaseRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**holdId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleLegalHoldsReleaseRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LegalHold**](LegalHold.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleLegalHoldsRetrieve

> LegalHold OperatorSaasLifecycleLegalHoldsRetrieve(ctx, holdId).Execute()



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
	holdId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsRetrieve(context.Background(), holdId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleLegalHoldsRetrieve`: LegalHold
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleLegalHoldsRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**holdId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleLegalHoldsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LegalHold**](LegalHold.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecyclePoliciesList

> []RetentionPolicy OperatorSaasLifecyclePoliciesList(ctx).Execute()



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
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecyclePoliciesList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecyclePoliciesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecyclePoliciesList`: []RetentionPolicy
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecyclePoliciesList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecyclePoliciesListRequest struct via the builder pattern


### Return type

[**[]RetentionPolicy**](RetentionPolicy.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecyclePoliciesRetrieve

> RetentionPolicy OperatorSaasLifecyclePoliciesRetrieve(ctx, policyId).Execute()



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
	policyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecyclePoliciesRetrieve(context.Background(), policyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecyclePoliciesRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecyclePoliciesRetrieve`: RetentionPolicy
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecyclePoliciesRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**policyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecyclePoliciesRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RetentionPolicy**](RetentionPolicy.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecyclePolicyVersionsList

> []RetentionPolicyVersion OperatorSaasLifecyclePolicyVersionsList(ctx).PolicyId(policyId).Execute()



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
	policyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecyclePolicyVersionsList(context.Background()).PolicyId(policyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecyclePolicyVersionsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecyclePolicyVersionsList`: []RetentionPolicyVersion
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecyclePolicyVersionsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecyclePolicyVersionsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **policyId** | **string** |  | 

### Return type

[**[]RetentionPolicyVersion**](RetentionPolicyVersion.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleTombstonesList

> []PurgeTombstone OperatorSaasLifecycleTombstonesList(ctx).CandidateId(candidateId).ManifestId(manifestId).Execute()



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
	candidateId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	manifestId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleTombstonesList(context.Background()).CandidateId(candidateId).ManifestId(manifestId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleTombstonesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleTombstonesList`: []PurgeTombstone
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleTombstonesList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleTombstonesListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **candidateId** | **string** |  | 
 **manifestId** | **string** |  | 

### Return type

[**[]PurgeTombstone**](PurgeTombstone.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasLifecycleTombstonesRetrieve

> PurgeTombstone OperatorSaasLifecycleTombstonesRetrieve(ctx, tombstoneId).Execute()



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
	tombstoneId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LifecycleOperatorAPI.OperatorSaasLifecycleTombstonesRetrieve(context.Background(), tombstoneId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LifecycleOperatorAPI.OperatorSaasLifecycleTombstonesRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasLifecycleTombstonesRetrieve`: PurgeTombstone
	fmt.Fprintf(os.Stdout, "Response from `LifecycleOperatorAPI.OperatorSaasLifecycleTombstonesRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tombstoneId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasLifecycleTombstonesRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PurgeTombstone**](PurgeTombstone.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

