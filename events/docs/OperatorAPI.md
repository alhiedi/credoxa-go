# \OperatorAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OperatorSaasAnalyticsDashboardCheckpointsRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardCheckpointsRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/checkpoints/ | 
[**OperatorSaasAnalyticsDashboardLeasesRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardLeasesRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/leases/ | 
[**OperatorSaasAnalyticsDashboardPlatformRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardPlatformRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/platform/ | 
[**OperatorSaasAnalyticsDashboardProjectionsRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardProjectionsRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/projections/ | 
[**OperatorSaasAnalyticsDashboardRebuildsRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardRebuildsRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/rebuilds/ | 
[**OperatorSaasAnalyticsDashboardRepairsRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardRepairsRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/repairs/ | 
[**OperatorSaasAnalyticsDashboardRuntimeRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardRuntimeRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/runtime/ | 
[**OperatorSaasAnalyticsDashboardSlosRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardSlosRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/slos/ | 
[**OperatorSaasAnalyticsDashboardTenantsRetrieve**](OperatorAPI.md#OperatorSaasAnalyticsDashboardTenantsRetrieve) | **Get** /api/v1/operator/saas/analytics/dashboard/tenants/ | 
[**OperatorSelfHealingEscalationsList**](OperatorAPI.md#OperatorSelfHealingEscalationsList) | **Get** /api/v1/operator/self-healing/escalations/ | 
[**OperatorSelfHealingEscalationsRetrieve**](OperatorAPI.md#OperatorSelfHealingEscalationsRetrieve) | **Get** /api/v1/operator/self-healing/escalations/{escalation_id}/ | 
[**OperatorSelfHealingQuarantinesList**](OperatorAPI.md#OperatorSelfHealingQuarantinesList) | **Get** /api/v1/operator/self-healing/quarantines/ | 
[**OperatorSelfHealingQuarantinesRetrieve**](OperatorAPI.md#OperatorSelfHealingQuarantinesRetrieve) | **Get** /api/v1/operator/self-healing/quarantines/{quarantine_id}/ | 
[**OperatorSelfHealingRecoveriesList**](OperatorAPI.md#OperatorSelfHealingRecoveriesList) | **Get** /api/v1/operator/self-healing/recoveries/ | 
[**OperatorSelfHealingRecoveriesRetrieve**](OperatorAPI.md#OperatorSelfHealingRecoveriesRetrieve) | **Get** /api/v1/operator/self-healing/recoveries/{execution_id}/ | 
[**RegionalControlPlaneAuthorityProposalCreate**](OperatorAPI.md#RegionalControlPlaneAuthorityProposalCreate) | **Post** /api/v1/operator/regional-resilience/control-plane/proposals/ | 
[**RegionalControlPlaneAuthorityProposalDetail**](OperatorAPI.md#RegionalControlPlaneAuthorityProposalDetail) | **Get** /api/v1/operator/regional-resilience/control-plane/proposals/{proposal_id}/ | 
[**RegionalControlPlaneAuthorityProposalList**](OperatorAPI.md#RegionalControlPlaneAuthorityProposalList) | **Get** /api/v1/operator/regional-resilience/control-plane/proposals/ | 
[**RegionalControlPlaneAuthorityVote**](OperatorAPI.md#RegionalControlPlaneAuthorityVote) | **Post** /api/v1/operator/regional-resilience/control-plane/proposals/{proposal_id}/votes/ | 
[**RegionalControlPlaneConvergenceEvaluate**](OperatorAPI.md#RegionalControlPlaneConvergenceEvaluate) | **Post** /api/v1/operator/regional-resilience/control-plane/convergence/evaluate/ | 
[**RegionalControlPlaneConvergenceLatest**](OperatorAPI.md#RegionalControlPlaneConvergenceLatest) | **Get** /api/v1/operator/regional-resilience/control-plane/convergence/{topology_id}/latest/ | 
[**RegionalControlPlaneDivergenceResolve**](OperatorAPI.md#RegionalControlPlaneDivergenceResolve) | **Post** /api/v1/operator/regional-resilience/control-plane/divergences/{divergence_id}/resolve/ | 
[**RegionalControlPlaneElection**](OperatorAPI.md#RegionalControlPlaneElection) | **Post** /api/v1/operator/regional-resilience/control-plane/elections/ | 
[**RegionalControlPlaneHeartbeat**](OperatorAPI.md#RegionalControlPlaneHeartbeat) | **Post** /api/v1/operator/regional-resilience/control-plane/heartbeat/ | 
[**RegionalControlPlaneLeadershipList**](OperatorAPI.md#RegionalControlPlaneLeadershipList) | **Get** /api/v1/operator/regional-resilience/control-plane/leadership/ | 
[**RegionalControlPlaneMemberCreate**](OperatorAPI.md#RegionalControlPlaneMemberCreate) | **Post** /api/v1/operator/regional-resilience/control-plane/members/ | 
[**RegionalControlPlaneMemberList**](OperatorAPI.md#RegionalControlPlaneMemberList) | **Get** /api/v1/operator/regional-resilience/control-plane/members/ | 
[**RegionalControlPlaneTopologyList**](OperatorAPI.md#RegionalControlPlaneTopologyList) | **Get** /api/v1/operator/regional-resilience/control-plane/topologies/ | 
[**RegionalDrComplianceDetail**](OperatorAPI.md#RegionalDrComplianceDetail) | **Get** /api/v1/operator/regional-resilience/disaster-recovery/compliance/{report_id}/ | 
[**RegionalDrComplianceList**](OperatorAPI.md#RegionalDrComplianceList) | **Get** /api/v1/operator/regional-resilience/disaster-recovery/compliance/ | 
[**RegionalDrDrillCancel**](OperatorAPI.md#RegionalDrDrillCancel) | **Post** /api/v1/operator/regional-resilience/disaster-recovery/drills/{drill_id}/cancel/ | 
[**RegionalDrDrillCreate**](OperatorAPI.md#RegionalDrDrillCreate) | **Post** /api/v1/operator/regional-resilience/disaster-recovery/drills/ | 
[**RegionalDrDrillDetail**](OperatorAPI.md#RegionalDrDrillDetail) | **Get** /api/v1/operator/regional-resilience/disaster-recovery/drills/{drill_id}/ | 
[**RegionalDrDrillDispatch**](OperatorAPI.md#RegionalDrDrillDispatch) | **Post** /api/v1/operator/regional-resilience/disaster-recovery/drills/{drill_id}/dispatch/ | 
[**RegionalDrDrillList**](OperatorAPI.md#RegionalDrDrillList) | **Get** /api/v1/operator/regional-resilience/disaster-recovery/drills/ | 
[**RegionalDrObjectiveCreate**](OperatorAPI.md#RegionalDrObjectiveCreate) | **Post** /api/v1/operator/regional-resilience/disaster-recovery/objectives/ | 
[**RegionalDrObjectiveDetail**](OperatorAPI.md#RegionalDrObjectiveDetail) | **Get** /api/v1/operator/regional-resilience/disaster-recovery/objectives/{objective_id}/ | 
[**RegionalDrObjectiveList**](OperatorAPI.md#RegionalDrObjectiveList) | **Get** /api/v1/operator/regional-resilience/disaster-recovery/objectives/ | 
[**RegionalFailoverExecutionCreate**](OperatorAPI.md#RegionalFailoverExecutionCreate) | **Post** /api/v1/operator/regional-resilience/failover-executions/ | 
[**RegionalFailoverExecutionDetail**](OperatorAPI.md#RegionalFailoverExecutionDetail) | **Get** /api/v1/operator/regional-resilience/failover-executions/{execution_id}/ | 
[**RegionalFailoverExecutionDispatch**](OperatorAPI.md#RegionalFailoverExecutionDispatch) | **Post** /api/v1/operator/regional-resilience/failover-executions/{execution_id}/dispatch/ | 
[**RegionalFailoverExecutionList**](OperatorAPI.md#RegionalFailoverExecutionList) | **Get** /api/v1/operator/regional-resilience/failover-executions/ | 
[**RegionalFailoverExecutionRetry**](OperatorAPI.md#RegionalFailoverExecutionRetry) | **Post** /api/v1/operator/regional-resilience/failover-executions/{execution_id}/retry/ | 
[**RegionalFailoverExecutionVerify**](OperatorAPI.md#RegionalFailoverExecutionVerify) | **Post** /api/v1/operator/regional-resilience/failover-executions/{execution_id}/verify/ | 
[**RegionalFailoverReconciliationApprove**](OperatorAPI.md#RegionalFailoverReconciliationApprove) | **Post** /api/v1/operator/regional-resilience/failover-reconciliations/{plan_id}/approve/ | 
[**RegionalFailoverReconciliationExecute**](OperatorAPI.md#RegionalFailoverReconciliationExecute) | **Post** /api/v1/operator/regional-resilience/failover-reconciliations/{plan_id}/execute/ | 
[**RegionalFailoverReconciliationPlanDetail**](OperatorAPI.md#RegionalFailoverReconciliationPlanDetail) | **Get** /api/v1/operator/regional-resilience/failover-reconciliations/{plan_id}/ | 
[**RegionalFailoverReconciliationPlanList**](OperatorAPI.md#RegionalFailoverReconciliationPlanList) | **Get** /api/v1/operator/regional-resilience/failover-reconciliations/ | 
[**RegionalFailoverSafetyDecisionApprove**](OperatorAPI.md#RegionalFailoverSafetyDecisionApprove) | **Post** /api/v1/operator/regional-resilience/safety-decisions/{decision_id}/approve/ | 
[**RegionalFailoverSafetyDecisionCancel**](OperatorAPI.md#RegionalFailoverSafetyDecisionCancel) | **Post** /api/v1/operator/regional-resilience/safety-decisions/{decision_id}/cancel/ | 
[**RegionalFailoverSafetyDecisionDetail**](OperatorAPI.md#RegionalFailoverSafetyDecisionDetail) | **Get** /api/v1/operator/regional-resilience/safety-decisions/{decision_id}/ | 
[**RegionalFailoverSafetyDecisionList**](OperatorAPI.md#RegionalFailoverSafetyDecisionList) | **Get** /api/v1/operator/regional-resilience/safety-decisions/ | 
[**RegionalFailoverSafetyDecisionReject**](OperatorAPI.md#RegionalFailoverSafetyDecisionReject) | **Post** /api/v1/operator/regional-resilience/safety-decisions/{decision_id}/reject/ | 
[**RegionalFailoverVerificationDetail**](OperatorAPI.md#RegionalFailoverVerificationDetail) | **Get** /api/v1/operator/regional-resilience/failover-verifications/{verification_id}/ | 
[**RegionalFailoverVerificationList**](OperatorAPI.md#RegionalFailoverVerificationList) | **Get** /api/v1/operator/regional-resilience/failover-verifications/ | 
[**RegionalHealthSignalCreate**](OperatorAPI.md#RegionalHealthSignalCreate) | **Post** /api/v1/operator/regional-resilience/signals/ | 
[**RegionalObservationHistory**](OperatorAPI.md#RegionalObservationHistory) | **Get** /api/v1/operator/regional-resilience/regions/{region_id}/observations/ | 
[**RegionalOperatorDrComplianceDetail**](OperatorAPI.md#RegionalOperatorDrComplianceDetail) | **Get** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/compliance/{report_id}/ | 
[**RegionalOperatorDrComplianceList**](OperatorAPI.md#RegionalOperatorDrComplianceList) | **Get** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/compliance/ | 
[**RegionalOperatorDrDrillCancel**](OperatorAPI.md#RegionalOperatorDrDrillCancel) | **Post** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/drills/{drill_id}/cancel/ | 
[**RegionalOperatorDrDrillCreate**](OperatorAPI.md#RegionalOperatorDrDrillCreate) | **Post** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/drills/ | 
[**RegionalOperatorDrDrillDetail**](OperatorAPI.md#RegionalOperatorDrDrillDetail) | **Get** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/drills/{drill_id}/ | 
[**RegionalOperatorDrDrillDispatch**](OperatorAPI.md#RegionalOperatorDrDrillDispatch) | **Post** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/drills/{drill_id}/dispatch/ | 
[**RegionalOperatorDrDrillList**](OperatorAPI.md#RegionalOperatorDrDrillList) | **Get** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/drills/ | 
[**RegionalOperatorDrObjectiveCreate**](OperatorAPI.md#RegionalOperatorDrObjectiveCreate) | **Post** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/objectives/ | 
[**RegionalOperatorDrObjectiveDetail**](OperatorAPI.md#RegionalOperatorDrObjectiveDetail) | **Get** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/objectives/{objective_id}/ | 
[**RegionalOperatorDrObjectiveList**](OperatorAPI.md#RegionalOperatorDrObjectiveList) | **Get** /api/v1/operator/regional-resilience/control-plane/disaster-recovery/objectives/ | 
[**RegionalReadinessEvaluate**](OperatorAPI.md#RegionalReadinessEvaluate) | **Post** /api/v1/operator/regional-resilience/regions/evaluate/ | 
[**RegionalReadinessHistory**](OperatorAPI.md#RegionalReadinessHistory) | **Get** /api/v1/operator/regional-resilience/regions/{region_id}/history/ | 
[**RegionalReadinessLatest**](OperatorAPI.md#RegionalReadinessLatest) | **Get** /api/v1/operator/regional-resilience/regions/{region_id}/latest/ | 
[**RegionalResilienceMetrics**](OperatorAPI.md#RegionalResilienceMetrics) | **Get** /api/v1/operator/regional-resilience/metrics/ | 
[**RegionalTopologyReadinessEvaluate**](OperatorAPI.md#RegionalTopologyReadinessEvaluate) | **Post** /api/v1/operator/regional-resilience/topologies/evaluate/ | 
[**RegionalTopologyReadinessLatest**](OperatorAPI.md#RegionalTopologyReadinessLatest) | **Get** /api/v1/operator/regional-resilience/topologies/{topology_id}/latest/ | 
[**SaasAnalyticsCheckpointList**](OperatorAPI.md#SaasAnalyticsCheckpointList) | **Get** /api/v1/operator/saas/analytics/recovery/checkpoints/ | 
[**SaasAnalyticsCheckpointRecoveryAction**](OperatorAPI.md#SaasAnalyticsCheckpointRecoveryAction) | **Post** /api/v1/operator/saas/analytics/recovery/checkpoints/{checkpoint_id}/{action}/ | 
[**SaasAnalyticsEventDeadLetterPreview**](OperatorAPI.md#SaasAnalyticsEventDeadLetterPreview) | **Post** /api/v1/operator/saas/analytics/recovery/dead-letters/events/{analytics_event_id}/preview/ | 
[**SaasAnalyticsEventDeadLetterReplay**](OperatorAPI.md#SaasAnalyticsEventDeadLetterReplay) | **Post** /api/v1/operator/saas/analytics/recovery/dead-letters/events/{analytics_event_id}/replay/ | 
[**SaasAnalyticsLeaseRecoveryAction**](OperatorAPI.md#SaasAnalyticsLeaseRecoveryAction) | **Post** /api/v1/operator/saas/analytics/recovery/leases/{lease_id}/{action}/ | 
[**SaasAnalyticsRebuildAction**](OperatorAPI.md#SaasAnalyticsRebuildAction) | **Post** /api/v1/operator/saas/analytics/recovery/rebuilds/{job_id}/{action}/ | 
[**SaasAnalyticsRebuildPreview**](OperatorAPI.md#SaasAnalyticsRebuildPreview) | **Post** /api/v1/operator/saas/analytics/recovery/rebuilds/{job_id}/preview/{action}/ | 
[**SaasAnalyticsRebuildProgressRepair**](OperatorAPI.md#SaasAnalyticsRebuildProgressRepair) | **Post** /api/v1/operator/saas/analytics/recovery/rebuilds/{job_id}/repair-progress/ | 
[**SaasAnalyticsRepairDeadLetterBulkReplay**](OperatorAPI.md#SaasAnalyticsRepairDeadLetterBulkReplay) | **Post** /api/v1/operator/saas/analytics/recovery/dead-letters/repairs/bulk-replay/ | 
[**SaasAnalyticsRepairDeadLetterPreview**](OperatorAPI.md#SaasAnalyticsRepairDeadLetterPreview) | **Post** /api/v1/operator/saas/analytics/recovery/dead-letters/repairs/{repair_id}/preview/ | 
[**SaasAnalyticsRepairDeadLetterReplay**](OperatorAPI.md#SaasAnalyticsRepairDeadLetterReplay) | **Post** /api/v1/operator/saas/analytics/recovery/dead-letters/repairs/{repair_id}/replay/ | 
[**SaasDegradedModeEvaluate**](OperatorAPI.md#SaasDegradedModeEvaluate) | **Post** /api/v1/operator/saas/degraded-mode/evaluate/ | 
[**SaasDegradedModeOverrideCreate**](OperatorAPI.md#SaasDegradedModeOverrideCreate) | **Post** /api/v1/operator/saas/degraded-mode/overrides/ | 
[**SaasDegradedModeOverrideDetail**](OperatorAPI.md#SaasDegradedModeOverrideDetail) | **Get** /api/v1/operator/saas/degraded-mode/overrides/{override_id}/ | 
[**SaasDegradedModeOverrideList**](OperatorAPI.md#SaasDegradedModeOverrideList) | **Get** /api/v1/operator/saas/degraded-mode/overrides/ | 
[**SaasDegradedModeOverrideRevoke**](OperatorAPI.md#SaasDegradedModeOverrideRevoke) | **Post** /api/v1/operator/saas/degraded-mode/overrides/{override_id}/revoke/ | 
[**SaasOperatorMetrics**](OperatorAPI.md#SaasOperatorMetrics) | **Get** /api/v1/operator/saas/metrics/ | 
[**SaasOperatorOutbox**](OperatorAPI.md#SaasOperatorOutbox) | **Get** /api/v1/operator/saas/outbox/ | 
[**SaasOperatorReservations**](OperatorAPI.md#SaasOperatorReservations) | **Get** /api/v1/operator/saas/reservations/ | 
[**SaasOperatorSummary**](OperatorAPI.md#SaasOperatorSummary) | **Get** /api/v1/operator/saas/summary/ | 
[**SaasRuntimeGovernanceOverrideActive**](OperatorAPI.md#SaasRuntimeGovernanceOverrideActive) | **Get** /api/v1/operator/saas/analytics/runtime-governance/overrides/active/ | 
[**SaasRuntimeGovernanceOverrideCreate**](OperatorAPI.md#SaasRuntimeGovernanceOverrideCreate) | **Post** /api/v1/operator/saas/analytics/runtime-governance/overrides/ | 
[**SaasRuntimeGovernanceOverrideDetail**](OperatorAPI.md#SaasRuntimeGovernanceOverrideDetail) | **Get** /api/v1/operator/saas/analytics/runtime-governance/overrides/{override_id}/ | 
[**SaasRuntimeGovernanceOverrideList**](OperatorAPI.md#SaasRuntimeGovernanceOverrideList) | **Get** /api/v1/operator/saas/analytics/runtime-governance/overrides/ | 
[**SaasRuntimeGovernanceOverrideRevoke**](OperatorAPI.md#SaasRuntimeGovernanceOverrideRevoke) | **Post** /api/v1/operator/saas/analytics/runtime-governance/overrides/{override_id}/revoke/ | 
[**SelfHealingConsumerQuarantineCreate**](OperatorAPI.md#SelfHealingConsumerQuarantineCreate) | **Post** /api/v1/operator/self-healing/quarantines/activate/ | 
[**SelfHealingConsumerQuarantineRelease**](OperatorAPI.md#SelfHealingConsumerQuarantineRelease) | **Post** /api/v1/operator/self-healing/quarantines/{quarantine_id}/release/ | 
[**SelfHealingHealthLiveness**](OperatorAPI.md#SelfHealingHealthLiveness) | **Get** /api/v1/operator/self-healing/health/live/ | 
[**SelfHealingHealthReadiness**](OperatorAPI.md#SelfHealingHealthReadiness) | **Get** /api/v1/operator/self-healing/health/ready/ | 
[**SelfHealingMetrics**](OperatorAPI.md#SelfHealingMetrics) | **Get** /api/v1/operator/self-healing/metrics/ | 
[**SelfHealingRecoveryEscalationAcknowledge**](OperatorAPI.md#SelfHealingRecoveryEscalationAcknowledge) | **Post** /api/v1/operator/self-healing/escalations/{escalation_id}/acknowledge/ | 
[**SelfHealingRecoveryEscalationResolve**](OperatorAPI.md#SelfHealingRecoveryEscalationResolve) | **Post** /api/v1/operator/self-healing/escalations/{escalation_id}/resolve/ | 
[**SelfHealingRecoveryExecutionCancel**](OperatorAPI.md#SelfHealingRecoveryExecutionCancel) | **Post** /api/v1/operator/self-healing/recoveries/{execution_id}/cancel/ | 
[**SelfHealingRecoveryExecutionRetry**](OperatorAPI.md#SelfHealingRecoveryExecutionRetry) | **Post** /api/v1/operator/self-healing/recoveries/{execution_id}/retry/ | 



## OperatorSaasAnalyticsDashboardCheckpointsRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardCheckpointsRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardCheckpointsRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardCheckpointsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardCheckpointsRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardCheckpointsRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardCheckpointsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardLeasesRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardLeasesRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardLeasesRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardLeasesRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardLeasesRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardLeasesRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardLeasesRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardPlatformRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardPlatformRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardPlatformRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardPlatformRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardPlatformRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardPlatformRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardPlatformRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardProjectionsRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardProjectionsRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardProjectionsRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardProjectionsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardProjectionsRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardProjectionsRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardProjectionsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardRebuildsRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardRebuildsRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardRebuildsRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardRebuildsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardRebuildsRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardRebuildsRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardRebuildsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardRepairsRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardRepairsRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardRepairsRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardRepairsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardRepairsRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardRepairsRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardRepairsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardRuntimeRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardRuntimeRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardRuntimeRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardRuntimeRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardRuntimeRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardRuntimeRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardRuntimeRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardSlosRetrieve

> AnalyticsDashboardSLOSectionResponse OperatorSaasAnalyticsDashboardSlosRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardSlosRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardSlosRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardSlosRetrieve`: AnalyticsDashboardSLOSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardSlosRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardSlosRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardSLOSectionResponse**](AnalyticsDashboardSLOSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSaasAnalyticsDashboardTenantsRetrieve

> AnalyticsDashboardJSONSectionResponse OperatorSaasAnalyticsDashboardTenantsRetrieve(ctx).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()



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
	checkpointLagTargetSeconds := int32(56) // int32 |  (optional) (default to 300)
	freshnessTargetSeconds := int32(56) // int32 |  (optional) (default to 900)
	leaseHealthTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	rebuildSuccessTargetPercent := float64(1.2) // float64 |  (optional) (default to 99.0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSaasAnalyticsDashboardTenantsRetrieve(context.Background()).CheckpointLagTargetSeconds(checkpointLagTargetSeconds).FreshnessTargetSeconds(freshnessTargetSeconds).LeaseHealthTargetPercent(leaseHealthTargetPercent).OrganizationId(organizationId).RebuildSuccessTargetPercent(rebuildSuccessTargetPercent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSaasAnalyticsDashboardTenantsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSaasAnalyticsDashboardTenantsRetrieve`: AnalyticsDashboardJSONSectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSaasAnalyticsDashboardTenantsRetrieve`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSaasAnalyticsDashboardTenantsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **checkpointLagTargetSeconds** | **int32** |  | [default to 300]
 **freshnessTargetSeconds** | **int32** |  | [default to 900]
 **leaseHealthTargetPercent** | **float64** |  | [default to 99.0]
 **organizationId** | **string** |  | 
 **rebuildSuccessTargetPercent** | **float64** |  | [default to 99.0]

### Return type

[**AnalyticsDashboardJSONSectionResponse**](AnalyticsDashboardJSONSectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSelfHealingEscalationsList

> PaginatedRecoveryEscalationList OperatorSelfHealingEscalationsList(ctx).Ordering(ordering).Page(page).PageSize(pageSize).Search(search).Execute()



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
	ordering := "ordering_example" // string | Which field to use when ordering the results. (optional)
	page := int32(56) // int32 | A page number within the paginated result set. (optional)
	pageSize := int32(56) // int32 | Number of results to return per page. (optional)
	search := "search_example" // string | A search term. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSelfHealingEscalationsList(context.Background()).Ordering(ordering).Page(page).PageSize(pageSize).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSelfHealingEscalationsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSelfHealingEscalationsList`: PaginatedRecoveryEscalationList
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSelfHealingEscalationsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSelfHealingEscalationsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ordering** | **string** | Which field to use when ordering the results. | 
 **page** | **int32** | A page number within the paginated result set. | 
 **pageSize** | **int32** | Number of results to return per page. | 
 **search** | **string** | A search term. | 

### Return type

[**PaginatedRecoveryEscalationList**](PaginatedRecoveryEscalationList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSelfHealingEscalationsRetrieve

> RecoveryEscalation OperatorSelfHealingEscalationsRetrieve(ctx, escalationId).Execute()



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
	escalationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSelfHealingEscalationsRetrieve(context.Background(), escalationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSelfHealingEscalationsRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSelfHealingEscalationsRetrieve`: RecoveryEscalation
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSelfHealingEscalationsRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**escalationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSelfHealingEscalationsRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RecoveryEscalation**](RecoveryEscalation.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSelfHealingQuarantinesList

> PaginatedConsumerQuarantineList OperatorSelfHealingQuarantinesList(ctx).Ordering(ordering).Page(page).PageSize(pageSize).Search(search).Execute()



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
	ordering := "ordering_example" // string | Which field to use when ordering the results. (optional)
	page := int32(56) // int32 | A page number within the paginated result set. (optional)
	pageSize := int32(56) // int32 | Number of results to return per page. (optional)
	search := "search_example" // string | A search term. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSelfHealingQuarantinesList(context.Background()).Ordering(ordering).Page(page).PageSize(pageSize).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSelfHealingQuarantinesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSelfHealingQuarantinesList`: PaginatedConsumerQuarantineList
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSelfHealingQuarantinesList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSelfHealingQuarantinesListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ordering** | **string** | Which field to use when ordering the results. | 
 **page** | **int32** | A page number within the paginated result set. | 
 **pageSize** | **int32** | Number of results to return per page. | 
 **search** | **string** | A search term. | 

### Return type

[**PaginatedConsumerQuarantineList**](PaginatedConsumerQuarantineList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSelfHealingQuarantinesRetrieve

> ConsumerQuarantine OperatorSelfHealingQuarantinesRetrieve(ctx, quarantineId).Execute()



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
	quarantineId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSelfHealingQuarantinesRetrieve(context.Background(), quarantineId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSelfHealingQuarantinesRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSelfHealingQuarantinesRetrieve`: ConsumerQuarantine
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSelfHealingQuarantinesRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quarantineId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSelfHealingQuarantinesRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConsumerQuarantine**](ConsumerQuarantine.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSelfHealingRecoveriesList

> PaginatedRuntimeRecoveryExecutionListList OperatorSelfHealingRecoveriesList(ctx).Ordering(ordering).Page(page).PageSize(pageSize).Search(search).Execute()



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
	ordering := "ordering_example" // string | Which field to use when ordering the results. (optional)
	page := int32(56) // int32 | A page number within the paginated result set. (optional)
	pageSize := int32(56) // int32 | Number of results to return per page. (optional)
	search := "search_example" // string | A search term. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.OperatorSelfHealingRecoveriesList(context.Background()).Ordering(ordering).Page(page).PageSize(pageSize).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSelfHealingRecoveriesList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSelfHealingRecoveriesList`: PaginatedRuntimeRecoveryExecutionListList
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSelfHealingRecoveriesList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSelfHealingRecoveriesListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ordering** | **string** | Which field to use when ordering the results. | 
 **page** | **int32** | A page number within the paginated result set. | 
 **pageSize** | **int32** | Number of results to return per page. | 
 **search** | **string** | A search term. | 

### Return type

[**PaginatedRuntimeRecoveryExecutionListList**](PaginatedRuntimeRecoveryExecutionListList.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OperatorSelfHealingRecoveriesRetrieve

> RuntimeRecoveryExecutionDetail OperatorSelfHealingRecoveriesRetrieve(ctx, executionId).Execute()



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
	resp, r, err := apiClient.OperatorAPI.OperatorSelfHealingRecoveriesRetrieve(context.Background(), executionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.OperatorSelfHealingRecoveriesRetrieve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperatorSelfHealingRecoveriesRetrieve`: RuntimeRecoveryExecutionDetail
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.OperatorSelfHealingRecoveriesRetrieve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperatorSelfHealingRecoveriesRetrieveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RuntimeRecoveryExecutionDetail**](RuntimeRecoveryExecutionDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneAuthorityProposalCreate

> AuthorityProposal RegionalControlPlaneAuthorityProposalCreate(ctx).AuthorityProposalCreateRequest(authorityProposalCreateRequest).Execute()



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
	authorityProposalCreateRequest := *openapiclient.NewAuthorityProposalCreateRequest("TopologyId_example", "LeadershipTermId_example", "ProposedRegionId_example", "Reason_example") // AuthorityProposalCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneAuthorityProposalCreate(context.Background()).AuthorityProposalCreateRequest(authorityProposalCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneAuthorityProposalCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneAuthorityProposalCreate`: AuthorityProposal
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneAuthorityProposalCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneAuthorityProposalCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorityProposalCreateRequest** | [**AuthorityProposalCreateRequest**](AuthorityProposalCreateRequest.md) |  | 

### Return type

[**AuthorityProposal**](AuthorityProposal.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneAuthorityProposalDetail

> AuthorityProposalDetailResponse RegionalControlPlaneAuthorityProposalDetail(ctx, proposalId).Execute()



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
	proposalId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneAuthorityProposalDetail(context.Background(), proposalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneAuthorityProposalDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneAuthorityProposalDetail`: AuthorityProposalDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneAuthorityProposalDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**proposalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneAuthorityProposalDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AuthorityProposalDetailResponse**](AuthorityProposalDetailResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneAuthorityProposalList

> []AuthorityProposal RegionalControlPlaneAuthorityProposalList(ctx).Status(status).Execute()



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
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneAuthorityProposalList(context.Background()).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneAuthorityProposalList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneAuthorityProposalList`: []AuthorityProposal
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneAuthorityProposalList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneAuthorityProposalListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | 

### Return type

[**[]AuthorityProposal**](AuthorityProposal.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneAuthorityVote

> AuthorityVoteResponse RegionalControlPlaneAuthorityVote(ctx, proposalId).AuthorityVoteCreateRequest(authorityVoteCreateRequest).Execute()



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
	proposalId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	authorityVoteCreateRequest := *openapiclient.NewAuthorityVoteCreateRequest("ControllerId_example", openapiclient.DecisionEnum("accept")) // AuthorityVoteCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneAuthorityVote(context.Background(), proposalId).AuthorityVoteCreateRequest(authorityVoteCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneAuthorityVote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneAuthorityVote`: AuthorityVoteResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneAuthorityVote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**proposalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneAuthorityVoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **authorityVoteCreateRequest** | [**AuthorityVoteCreateRequest**](AuthorityVoteCreateRequest.md) |  | 

### Return type

[**AuthorityVoteResponse**](AuthorityVoteResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneConvergenceEvaluate

> ConvergenceSnapshot RegionalControlPlaneConvergenceEvaluate(ctx).ConvergenceEvaluateRequest(convergenceEvaluateRequest).Execute()



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
	convergenceEvaluateRequest := *openapiclient.NewConvergenceEvaluateRequest("TopologyId_example") // ConvergenceEvaluateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneConvergenceEvaluate(context.Background()).ConvergenceEvaluateRequest(convergenceEvaluateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneConvergenceEvaluate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneConvergenceEvaluate`: ConvergenceSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneConvergenceEvaluate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneConvergenceEvaluateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **convergenceEvaluateRequest** | [**ConvergenceEvaluateRequest**](ConvergenceEvaluateRequest.md) |  | 

### Return type

[**ConvergenceSnapshot**](ConvergenceSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneConvergenceLatest

> ConvergenceSnapshot RegionalControlPlaneConvergenceLatest(ctx, topologyId).Execute()



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
	topologyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneConvergenceLatest(context.Background(), topologyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneConvergenceLatest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneConvergenceLatest`: ConvergenceSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneConvergenceLatest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**topologyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneConvergenceLatestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ConvergenceSnapshot**](ConvergenceSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneDivergenceResolve

> Divergence RegionalControlPlaneDivergenceResolve(ctx, divergenceId).Execute()



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
	divergenceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneDivergenceResolve(context.Background(), divergenceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneDivergenceResolve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneDivergenceResolve`: Divergence
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneDivergenceResolve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**divergenceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneDivergenceResolveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Divergence**](Divergence.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneElection

> ControlPlaneElectionResponse RegionalControlPlaneElection(ctx).ControlPlaneElectionRequest(controlPlaneElectionRequest).Execute()



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
	controlPlaneElectionRequest := *openapiclient.NewControlPlaneElectionRequest("TopologyId_example") // ControlPlaneElectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneElection(context.Background()).ControlPlaneElectionRequest(controlPlaneElectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneElection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneElection`: ControlPlaneElectionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneElection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneElectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **controlPlaneElectionRequest** | [**ControlPlaneElectionRequest**](ControlPlaneElectionRequest.md) |  | 

### Return type

[**ControlPlaneElectionResponse**](ControlPlaneElectionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneHeartbeat

> ControlPlaneMember RegionalControlPlaneHeartbeat(ctx).ControlPlaneHeartbeatRequest(controlPlaneHeartbeatRequest).Execute()



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
	controlPlaneHeartbeatRequest := *openapiclient.NewControlPlaneHeartbeatRequest("ControllerId_example") // ControlPlaneHeartbeatRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneHeartbeat(context.Background()).ControlPlaneHeartbeatRequest(controlPlaneHeartbeatRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneHeartbeat``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneHeartbeat`: ControlPlaneMember
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneHeartbeat`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneHeartbeatRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **controlPlaneHeartbeatRequest** | [**ControlPlaneHeartbeatRequest**](ControlPlaneHeartbeatRequest.md) |  | 

### Return type

[**ControlPlaneMember**](ControlPlaneMember.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneLeadershipList

> []LeadershipTerm RegionalControlPlaneLeadershipList(ctx).TopologyId(topologyId).Execute()



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
	topologyId := "topologyId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneLeadershipList(context.Background()).TopologyId(topologyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneLeadershipList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneLeadershipList`: []LeadershipTerm
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneLeadershipList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneLeadershipListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **topologyId** | **string** |  | 

### Return type

[**[]LeadershipTerm**](LeadershipTerm.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneMemberCreate

> ControlPlaneMember RegionalControlPlaneMemberCreate(ctx).ControlPlaneMemberWriteRequest(controlPlaneMemberWriteRequest).Execute()



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
	controlPlaneMemberWriteRequest := *openapiclient.NewControlPlaneMemberWriteRequest("TopologyId_example", "RegionId_example", "ControllerId_example", openapiclient.RoleEnum("voter"), "FailureDomain_example") // ControlPlaneMemberWriteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneMemberCreate(context.Background()).ControlPlaneMemberWriteRequest(controlPlaneMemberWriteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneMemberCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneMemberCreate`: ControlPlaneMember
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneMemberCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneMemberCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **controlPlaneMemberWriteRequest** | [**ControlPlaneMemberWriteRequest**](ControlPlaneMemberWriteRequest.md) |  | 

### Return type

[**ControlPlaneMember**](ControlPlaneMember.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneMemberList

> []ControlPlaneMember RegionalControlPlaneMemberList(ctx).TopologyId(topologyId).Execute()



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
	topologyId := "topologyId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneMemberList(context.Background()).TopologyId(topologyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneMemberList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneMemberList`: []ControlPlaneMember
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneMemberList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneMemberListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **topologyId** | **string** |  | 

### Return type

[**[]ControlPlaneMember**](ControlPlaneMember.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalControlPlaneTopologyList

> []ControlPlaneTopologyItem RegionalControlPlaneTopologyList(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalControlPlaneTopologyList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalControlPlaneTopologyList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalControlPlaneTopologyList`: []ControlPlaneTopologyItem
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalControlPlaneTopologyList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalControlPlaneTopologyListRequest struct via the builder pattern


### Return type

[**[]ControlPlaneTopologyItem**](ControlPlaneTopologyItem.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrComplianceDetail

> DisasterRecoveryComplianceResponse RegionalDrComplianceDetail(ctx, reportId).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalDrComplianceDetail(context.Background(), reportId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrComplianceDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrComplianceDetail`: DisasterRecoveryComplianceResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrComplianceDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrComplianceDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryComplianceResponse**](DisasterRecoveryComplianceResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrComplianceList

> []DisasterRecoveryComplianceResponse RegionalDrComplianceList(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalDrComplianceList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrComplianceList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrComplianceList`: []DisasterRecoveryComplianceResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrComplianceList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrComplianceListRequest struct via the builder pattern


### Return type

[**[]DisasterRecoveryComplianceResponse**](DisasterRecoveryComplianceResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrDrillCancel

> DisasterRecoveryDrillResponse RegionalDrDrillCancel(ctx, drillId).DrillCancelRequest(drillCancelRequest).Execute()



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
	drillId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	drillCancelRequest := *openapiclient.NewDrillCancelRequest() // DrillCancelRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalDrDrillCancel(context.Background(), drillId).DrillCancelRequest(drillCancelRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrDrillCancel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrDrillCancel`: DisasterRecoveryDrillResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrDrillCancel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**drillId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrDrillCancelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **drillCancelRequest** | [**DrillCancelRequest**](DrillCancelRequest.md) |  | 

### Return type

[**DisasterRecoveryDrillResponse**](DisasterRecoveryDrillResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrDrillCreate

> DisasterRecoveryDrillResponse RegionalDrDrillCreate(ctx).DrillCreateRequest(drillCreateRequest).Execute()



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
	drillCreateRequest := *openapiclient.NewDrillCreateRequest("ObjectiveId_example", int32(123)) // DrillCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalDrDrillCreate(context.Background()).DrillCreateRequest(drillCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrDrillCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrDrillCreate`: DisasterRecoveryDrillResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrDrillCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrDrillCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **drillCreateRequest** | [**DrillCreateRequest**](DrillCreateRequest.md) |  | 

### Return type

[**DisasterRecoveryDrillResponse**](DisasterRecoveryDrillResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrDrillDetail

> DisasterRecoveryDrillDetailResponse RegionalDrDrillDetail(ctx, drillId).Execute()



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
	drillId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalDrDrillDetail(context.Background(), drillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrDrillDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrDrillDetail`: DisasterRecoveryDrillDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrDrillDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**drillId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrDrillDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryDrillDetailResponse**](DisasterRecoveryDrillDetailResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrDrillDispatch

> DisasterRecoveryDrillDispatchResponse RegionalDrDrillDispatch(ctx, drillId).Execute()



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
	drillId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalDrDrillDispatch(context.Background(), drillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrDrillDispatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrDrillDispatch`: DisasterRecoveryDrillDispatchResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrDrillDispatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**drillId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrDrillDispatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryDrillDispatchResponse**](DisasterRecoveryDrillDispatchResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrDrillList

> []DisasterRecoveryDrillResponse RegionalDrDrillList(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalDrDrillList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrDrillList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrDrillList`: []DisasterRecoveryDrillResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrDrillList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrDrillListRequest struct via the builder pattern


### Return type

[**[]DisasterRecoveryDrillResponse**](DisasterRecoveryDrillResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrObjectiveCreate

> DisasterRecoveryObjectiveResponse RegionalDrObjectiveCreate(ctx).ObjectiveCreateRequest(objectiveCreateRequest).Execute()



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
	objectiveCreateRequest := *openapiclient.NewObjectiveCreateRequest("TopologyId_example", "WorkloadName_example", openapiclient.CriticalityEnum("mission_critical"), int32(123), int32(123), int32(123)) // ObjectiveCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalDrObjectiveCreate(context.Background()).ObjectiveCreateRequest(objectiveCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrObjectiveCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrObjectiveCreate`: DisasterRecoveryObjectiveResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrObjectiveCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrObjectiveCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **objectiveCreateRequest** | [**ObjectiveCreateRequest**](ObjectiveCreateRequest.md) |  | 

### Return type

[**DisasterRecoveryObjectiveResponse**](DisasterRecoveryObjectiveResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrObjectiveDetail

> DisasterRecoveryObjectiveResponse RegionalDrObjectiveDetail(ctx, objectiveId).Execute()



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
	objectiveId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalDrObjectiveDetail(context.Background(), objectiveId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrObjectiveDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrObjectiveDetail`: DisasterRecoveryObjectiveResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrObjectiveDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**objectiveId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrObjectiveDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryObjectiveResponse**](DisasterRecoveryObjectiveResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalDrObjectiveList

> []DisasterRecoveryObjectiveResponse RegionalDrObjectiveList(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalDrObjectiveList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalDrObjectiveList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalDrObjectiveList`: []DisasterRecoveryObjectiveResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalDrObjectiveList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalDrObjectiveListRequest struct via the builder pattern


### Return type

[**[]DisasterRecoveryObjectiveResponse**](DisasterRecoveryObjectiveResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverExecutionCreate

> RegionalFailoverExecution RegionalFailoverExecutionCreate(ctx).RegionalFailoverExecutionCreateRequest(regionalFailoverExecutionCreateRequest).Execute()



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
	regionalFailoverExecutionCreateRequest := *openapiclient.NewRegionalFailoverExecutionCreateRequest("SafetyDecisionId_example", "Reason_example") // RegionalFailoverExecutionCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverExecutionCreate(context.Background()).RegionalFailoverExecutionCreateRequest(regionalFailoverExecutionCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverExecutionCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverExecutionCreate`: RegionalFailoverExecution
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverExecutionCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverExecutionCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **regionalFailoverExecutionCreateRequest** | [**RegionalFailoverExecutionCreateRequest**](RegionalFailoverExecutionCreateRequest.md) |  | 

### Return type

[**RegionalFailoverExecution**](RegionalFailoverExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverExecutionDetail

> RegionalFailoverExecution RegionalFailoverExecutionDetail(ctx, executionId).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverExecutionDetail(context.Background(), executionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverExecutionDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverExecutionDetail`: RegionalFailoverExecution
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverExecutionDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverExecutionDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RegionalFailoverExecution**](RegionalFailoverExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverExecutionDispatch

> RegionalFailoverExecutionDispatchResponse RegionalFailoverExecutionDispatch(ctx, executionId).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverExecutionDispatch(context.Background(), executionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverExecutionDispatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverExecutionDispatch`: RegionalFailoverExecutionDispatchResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverExecutionDispatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverExecutionDispatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RegionalFailoverExecutionDispatchResponse**](RegionalFailoverExecutionDispatchResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverExecutionList

> []RegionalFailoverExecution RegionalFailoverExecutionList(ctx).Status(status).TargetRegionId(targetRegionId).TopologyId(topologyId).Execute()



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
	status := "status_example" // string |  (optional)
	targetRegionId := "targetRegionId_example" // string |  (optional)
	topologyId := "topologyId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverExecutionList(context.Background()).Status(status).TargetRegionId(targetRegionId).TopologyId(topologyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverExecutionList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverExecutionList`: []RegionalFailoverExecution
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverExecutionList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverExecutionListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | 
 **targetRegionId** | **string** |  | 
 **topologyId** | **string** |  | 

### Return type

[**[]RegionalFailoverExecution**](RegionalFailoverExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverExecutionRetry

> RegionalFailoverExecution RegionalFailoverExecutionRetry(ctx, executionId).RegionalFailoverExecutionRetryRequest(regionalFailoverExecutionRetryRequest).Execute()



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
	regionalFailoverExecutionRetryRequest := *openapiclient.NewRegionalFailoverExecutionRetryRequest(int32(123), "Reason_example") // RegionalFailoverExecutionRetryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverExecutionRetry(context.Background(), executionId).RegionalFailoverExecutionRetryRequest(regionalFailoverExecutionRetryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverExecutionRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverExecutionRetry`: RegionalFailoverExecution
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverExecutionRetry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverExecutionRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **regionalFailoverExecutionRetryRequest** | [**RegionalFailoverExecutionRetryRequest**](RegionalFailoverExecutionRetryRequest.md) |  | 

### Return type

[**RegionalFailoverExecution**](RegionalFailoverExecution.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverExecutionVerify

> RegionalFailoverVerificationOutcome RegionalFailoverExecutionVerify(ctx, executionId).RegionalFailoverVerificationRequestRequest(regionalFailoverVerificationRequestRequest).Execute()



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
	regionalFailoverVerificationRequestRequest := *openapiclient.NewRegionalFailoverVerificationRequestRequest() // RegionalFailoverVerificationRequestRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverExecutionVerify(context.Background(), executionId).RegionalFailoverVerificationRequestRequest(regionalFailoverVerificationRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverExecutionVerify``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverExecutionVerify`: RegionalFailoverVerificationOutcome
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverExecutionVerify`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverExecutionVerifyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **regionalFailoverVerificationRequestRequest** | [**RegionalFailoverVerificationRequestRequest**](RegionalFailoverVerificationRequestRequest.md) |  | 

### Return type

[**RegionalFailoverVerificationOutcome**](RegionalFailoverVerificationOutcome.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverReconciliationApprove

> RegionalFailoverReconciliationPlan RegionalFailoverReconciliationApprove(ctx, planId).RegionalFailoverReconciliationApprovalRequest(regionalFailoverReconciliationApprovalRequest).Execute()



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
	planId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	regionalFailoverReconciliationApprovalRequest := *openapiclient.NewRegionalFailoverReconciliationApprovalRequest([]string{"ActionIds_example"}, "Reason_example") // RegionalFailoverReconciliationApprovalRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverReconciliationApprove(context.Background(), planId).RegionalFailoverReconciliationApprovalRequest(regionalFailoverReconciliationApprovalRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverReconciliationApprove``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverReconciliationApprove`: RegionalFailoverReconciliationPlan
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverReconciliationApprove`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**planId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverReconciliationApproveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **regionalFailoverReconciliationApprovalRequest** | [**RegionalFailoverReconciliationApprovalRequest**](RegionalFailoverReconciliationApprovalRequest.md) |  | 

### Return type

[**RegionalFailoverReconciliationPlan**](RegionalFailoverReconciliationPlan.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverReconciliationExecute

> RegionalFailoverReconciliationExecutionOutcome RegionalFailoverReconciliationExecute(ctx, planId).RegionalFailoverReconciliationExecuteRequest(regionalFailoverReconciliationExecuteRequest).Execute()



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
	planId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	regionalFailoverReconciliationExecuteRequest := *openapiclient.NewRegionalFailoverReconciliationExecuteRequest() // RegionalFailoverReconciliationExecuteRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverReconciliationExecute(context.Background(), planId).RegionalFailoverReconciliationExecuteRequest(regionalFailoverReconciliationExecuteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverReconciliationExecute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverReconciliationExecute`: RegionalFailoverReconciliationExecutionOutcome
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverReconciliationExecute`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**planId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverReconciliationExecuteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **regionalFailoverReconciliationExecuteRequest** | [**RegionalFailoverReconciliationExecuteRequest**](RegionalFailoverReconciliationExecuteRequest.md) |  | 

### Return type

[**RegionalFailoverReconciliationExecutionOutcome**](RegionalFailoverReconciliationExecutionOutcome.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverReconciliationPlanDetail

> RegionalFailoverReconciliationPlan RegionalFailoverReconciliationPlanDetail(ctx, planId).Execute()



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
	planId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverReconciliationPlanDetail(context.Background(), planId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverReconciliationPlanDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverReconciliationPlanDetail`: RegionalFailoverReconciliationPlan
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverReconciliationPlanDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**planId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverReconciliationPlanDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RegionalFailoverReconciliationPlan**](RegionalFailoverReconciliationPlan.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverReconciliationPlanList

> []RegionalFailoverReconciliationPlan RegionalFailoverReconciliationPlanList(ctx).ExecutionId(executionId).Status(status).Execute()



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
	executionId := "executionId_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverReconciliationPlanList(context.Background()).ExecutionId(executionId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverReconciliationPlanList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverReconciliationPlanList`: []RegionalFailoverReconciliationPlan
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverReconciliationPlanList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverReconciliationPlanListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **executionId** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**[]RegionalFailoverReconciliationPlan**](RegionalFailoverReconciliationPlan.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverSafetyDecisionApprove

> FailoverSafetyDecision RegionalFailoverSafetyDecisionApprove(ctx, decisionId).FailoverSafetyDecisionTransitionRequest(failoverSafetyDecisionTransitionRequest).Execute()



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
	decisionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	failoverSafetyDecisionTransitionRequest := *openapiclient.NewFailoverSafetyDecisionTransitionRequest(int32(123), "Reason_example") // FailoverSafetyDecisionTransitionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverSafetyDecisionApprove(context.Background(), decisionId).FailoverSafetyDecisionTransitionRequest(failoverSafetyDecisionTransitionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverSafetyDecisionApprove``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverSafetyDecisionApprove`: FailoverSafetyDecision
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverSafetyDecisionApprove`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**decisionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverSafetyDecisionApproveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **failoverSafetyDecisionTransitionRequest** | [**FailoverSafetyDecisionTransitionRequest**](FailoverSafetyDecisionTransitionRequest.md) |  | 

### Return type

[**FailoverSafetyDecision**](FailoverSafetyDecision.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverSafetyDecisionCancel

> FailoverSafetyDecision RegionalFailoverSafetyDecisionCancel(ctx, decisionId).FailoverSafetyDecisionTransitionRequest(failoverSafetyDecisionTransitionRequest).Execute()



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
	decisionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	failoverSafetyDecisionTransitionRequest := *openapiclient.NewFailoverSafetyDecisionTransitionRequest(int32(123), "Reason_example") // FailoverSafetyDecisionTransitionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverSafetyDecisionCancel(context.Background(), decisionId).FailoverSafetyDecisionTransitionRequest(failoverSafetyDecisionTransitionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverSafetyDecisionCancel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverSafetyDecisionCancel`: FailoverSafetyDecision
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverSafetyDecisionCancel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**decisionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverSafetyDecisionCancelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **failoverSafetyDecisionTransitionRequest** | [**FailoverSafetyDecisionTransitionRequest**](FailoverSafetyDecisionTransitionRequest.md) |  | 

### Return type

[**FailoverSafetyDecision**](FailoverSafetyDecision.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverSafetyDecisionDetail

> FailoverSafetyDecision RegionalFailoverSafetyDecisionDetail(ctx, decisionId).Execute()



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
	decisionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverSafetyDecisionDetail(context.Background(), decisionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverSafetyDecisionDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverSafetyDecisionDetail`: FailoverSafetyDecision
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverSafetyDecisionDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**decisionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverSafetyDecisionDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**FailoverSafetyDecision**](FailoverSafetyDecision.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverSafetyDecisionList

> []FailoverSafetyDecision RegionalFailoverSafetyDecisionList(ctx).ApprovalStatus(approvalStatus).Decision(decision).TopologyId(topologyId).Execute()



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
	approvalStatus := "approvalStatus_example" // string |  (optional)
	decision := "decision_example" // string |  (optional)
	topologyId := "topologyId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverSafetyDecisionList(context.Background()).ApprovalStatus(approvalStatus).Decision(decision).TopologyId(topologyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverSafetyDecisionList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverSafetyDecisionList`: []FailoverSafetyDecision
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverSafetyDecisionList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverSafetyDecisionListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **approvalStatus** | **string** |  | 
 **decision** | **string** |  | 
 **topologyId** | **string** |  | 

### Return type

[**[]FailoverSafetyDecision**](FailoverSafetyDecision.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverSafetyDecisionReject

> FailoverSafetyDecision RegionalFailoverSafetyDecisionReject(ctx, decisionId).FailoverSafetyDecisionTransitionRequest(failoverSafetyDecisionTransitionRequest).Execute()



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
	decisionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	failoverSafetyDecisionTransitionRequest := *openapiclient.NewFailoverSafetyDecisionTransitionRequest(int32(123), "Reason_example") // FailoverSafetyDecisionTransitionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverSafetyDecisionReject(context.Background(), decisionId).FailoverSafetyDecisionTransitionRequest(failoverSafetyDecisionTransitionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverSafetyDecisionReject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverSafetyDecisionReject`: FailoverSafetyDecision
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverSafetyDecisionReject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**decisionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverSafetyDecisionRejectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **failoverSafetyDecisionTransitionRequest** | [**FailoverSafetyDecisionTransitionRequest**](FailoverSafetyDecisionTransitionRequest.md) |  | 

### Return type

[**FailoverSafetyDecision**](FailoverSafetyDecision.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverVerificationDetail

> RegionalFailoverVerification RegionalFailoverVerificationDetail(ctx, verificationId).Execute()



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
	verificationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverVerificationDetail(context.Background(), verificationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverVerificationDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverVerificationDetail`: RegionalFailoverVerification
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverVerificationDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**verificationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverVerificationDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RegionalFailoverVerification**](RegionalFailoverVerification.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalFailoverVerificationList

> []RegionalFailoverVerification RegionalFailoverVerificationList(ctx).ExecutionId(executionId).Status(status).Execute()



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
	executionId := "executionId_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalFailoverVerificationList(context.Background()).ExecutionId(executionId).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalFailoverVerificationList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalFailoverVerificationList`: []RegionalFailoverVerification
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalFailoverVerificationList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalFailoverVerificationListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **executionId** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**[]RegionalFailoverVerification**](RegionalFailoverVerification.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalHealthSignalCreate

> RegionHealthObservation RegionalHealthSignalCreate(ctx).RegionHealthSignalRequest(regionHealthSignalRequest).Execute()



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
	regionHealthSignalRequest := *openapiclient.NewRegionHealthSignalRequest("RegionId_example", openapiclient.RequiredChecksEnum("heartbeat"), openapiclient.RegionHealthSignalStatusEnum("passing"), time.Now(), time.Now()) // RegionHealthSignalRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalHealthSignalCreate(context.Background()).RegionHealthSignalRequest(regionHealthSignalRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalHealthSignalCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalHealthSignalCreate`: RegionHealthObservation
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalHealthSignalCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalHealthSignalCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **regionHealthSignalRequest** | [**RegionHealthSignalRequest**](RegionHealthSignalRequest.md) |  | 

### Return type

[**RegionHealthObservation**](RegionHealthObservation.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalObservationHistory

> []RegionHealthObservation RegionalObservationHistory(ctx, regionId).CheckType(checkType).Execute()



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
	regionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	checkType := "checkType_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalObservationHistory(context.Background(), regionId).CheckType(checkType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalObservationHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalObservationHistory`: []RegionHealthObservation
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalObservationHistory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**regionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalObservationHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **checkType** | **string** |  | 

### Return type

[**[]RegionHealthObservation**](RegionHealthObservation.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrComplianceDetail

> DisasterRecoveryComplianceResponse RegionalOperatorDrComplianceDetail(ctx, reportId).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrComplianceDetail(context.Background(), reportId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrComplianceDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrComplianceDetail`: DisasterRecoveryComplianceResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrComplianceDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrComplianceDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryComplianceResponse**](DisasterRecoveryComplianceResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrComplianceList

> []DisasterRecoveryComplianceResponse RegionalOperatorDrComplianceList(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrComplianceList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrComplianceList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrComplianceList`: []DisasterRecoveryComplianceResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrComplianceList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrComplianceListRequest struct via the builder pattern


### Return type

[**[]DisasterRecoveryComplianceResponse**](DisasterRecoveryComplianceResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrDrillCancel

> DisasterRecoveryDrillResponse RegionalOperatorDrDrillCancel(ctx, drillId).DrillCancelRequest(drillCancelRequest).Execute()



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
	drillId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	drillCancelRequest := *openapiclient.NewDrillCancelRequest() // DrillCancelRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrDrillCancel(context.Background(), drillId).DrillCancelRequest(drillCancelRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrDrillCancel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrDrillCancel`: DisasterRecoveryDrillResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrDrillCancel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**drillId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrDrillCancelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **drillCancelRequest** | [**DrillCancelRequest**](DrillCancelRequest.md) |  | 

### Return type

[**DisasterRecoveryDrillResponse**](DisasterRecoveryDrillResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrDrillCreate

> DisasterRecoveryDrillResponse RegionalOperatorDrDrillCreate(ctx).DrillCreateRequest(drillCreateRequest).Execute()



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
	drillCreateRequest := *openapiclient.NewDrillCreateRequest("ObjectiveId_example", int32(123)) // DrillCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrDrillCreate(context.Background()).DrillCreateRequest(drillCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrDrillCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrDrillCreate`: DisasterRecoveryDrillResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrDrillCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrDrillCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **drillCreateRequest** | [**DrillCreateRequest**](DrillCreateRequest.md) |  | 

### Return type

[**DisasterRecoveryDrillResponse**](DisasterRecoveryDrillResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrDrillDetail

> DisasterRecoveryDrillDetailResponse RegionalOperatorDrDrillDetail(ctx, drillId).Execute()



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
	drillId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrDrillDetail(context.Background(), drillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrDrillDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrDrillDetail`: DisasterRecoveryDrillDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrDrillDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**drillId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrDrillDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryDrillDetailResponse**](DisasterRecoveryDrillDetailResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrDrillDispatch

> DisasterRecoveryDrillDispatchResponse RegionalOperatorDrDrillDispatch(ctx, drillId).Execute()



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
	drillId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrDrillDispatch(context.Background(), drillId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrDrillDispatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrDrillDispatch`: DisasterRecoveryDrillDispatchResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrDrillDispatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**drillId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrDrillDispatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryDrillDispatchResponse**](DisasterRecoveryDrillDispatchResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrDrillList

> []DisasterRecoveryDrillResponse RegionalOperatorDrDrillList(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrDrillList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrDrillList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrDrillList`: []DisasterRecoveryDrillResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrDrillList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrDrillListRequest struct via the builder pattern


### Return type

[**[]DisasterRecoveryDrillResponse**](DisasterRecoveryDrillResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrObjectiveCreate

> DisasterRecoveryObjectiveResponse RegionalOperatorDrObjectiveCreate(ctx).ObjectiveCreateRequest(objectiveCreateRequest).Execute()



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
	objectiveCreateRequest := *openapiclient.NewObjectiveCreateRequest("TopologyId_example", "WorkloadName_example", openapiclient.CriticalityEnum("mission_critical"), int32(123), int32(123), int32(123)) // ObjectiveCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrObjectiveCreate(context.Background()).ObjectiveCreateRequest(objectiveCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrObjectiveCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrObjectiveCreate`: DisasterRecoveryObjectiveResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrObjectiveCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrObjectiveCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **objectiveCreateRequest** | [**ObjectiveCreateRequest**](ObjectiveCreateRequest.md) |  | 

### Return type

[**DisasterRecoveryObjectiveResponse**](DisasterRecoveryObjectiveResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrObjectiveDetail

> DisasterRecoveryObjectiveResponse RegionalOperatorDrObjectiveDetail(ctx, objectiveId).Execute()



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
	objectiveId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrObjectiveDetail(context.Background(), objectiveId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrObjectiveDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrObjectiveDetail`: DisasterRecoveryObjectiveResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrObjectiveDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**objectiveId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrObjectiveDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DisasterRecoveryObjectiveResponse**](DisasterRecoveryObjectiveResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalOperatorDrObjectiveList

> []DisasterRecoveryObjectiveResponse RegionalOperatorDrObjectiveList(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalOperatorDrObjectiveList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalOperatorDrObjectiveList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalOperatorDrObjectiveList`: []DisasterRecoveryObjectiveResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalOperatorDrObjectiveList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalOperatorDrObjectiveListRequest struct via the builder pattern


### Return type

[**[]DisasterRecoveryObjectiveResponse**](DisasterRecoveryObjectiveResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalReadinessEvaluate

> RegionReadinessSnapshot RegionalReadinessEvaluate(ctx).RegionReadinessEvaluationRequest(regionReadinessEvaluationRequest).Execute()



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
	regionReadinessEvaluationRequest := *openapiclient.NewRegionReadinessEvaluationRequest("RegionId_example") // RegionReadinessEvaluationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalReadinessEvaluate(context.Background()).RegionReadinessEvaluationRequest(regionReadinessEvaluationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalReadinessEvaluate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalReadinessEvaluate`: RegionReadinessSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalReadinessEvaluate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalReadinessEvaluateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **regionReadinessEvaluationRequest** | [**RegionReadinessEvaluationRequest**](RegionReadinessEvaluationRequest.md) |  | 

### Return type

[**RegionReadinessSnapshot**](RegionReadinessSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalReadinessHistory

> []RegionReadinessSnapshot RegionalReadinessHistory(ctx, regionId).Execute()



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
	regionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalReadinessHistory(context.Background(), regionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalReadinessHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalReadinessHistory`: []RegionReadinessSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalReadinessHistory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**regionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalReadinessHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]RegionReadinessSnapshot**](RegionReadinessSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalReadinessLatest

> RegionReadinessSnapshot RegionalReadinessLatest(ctx, regionId).Execute()



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
	regionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalReadinessLatest(context.Background(), regionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalReadinessLatest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalReadinessLatest`: RegionReadinessSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalReadinessLatest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**regionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalReadinessLatestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RegionReadinessSnapshot**](RegionReadinessSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalResilienceMetrics

> string RegionalResilienceMetrics(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.RegionalResilienceMetrics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalResilienceMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalResilienceMetrics`: string
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalResilienceMetrics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalResilienceMetricsRequest struct via the builder pattern


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalTopologyReadinessEvaluate

> TopologyReadinessSnapshot RegionalTopologyReadinessEvaluate(ctx).TopologyReadinessEvaluationRequest(topologyReadinessEvaluationRequest).Execute()



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
	topologyReadinessEvaluationRequest := *openapiclient.NewTopologyReadinessEvaluationRequest("TopologyId_example") // TopologyReadinessEvaluationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalTopologyReadinessEvaluate(context.Background()).TopologyReadinessEvaluationRequest(topologyReadinessEvaluationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalTopologyReadinessEvaluate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalTopologyReadinessEvaluate`: TopologyReadinessSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalTopologyReadinessEvaluate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegionalTopologyReadinessEvaluateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **topologyReadinessEvaluationRequest** | [**TopologyReadinessEvaluationRequest**](TopologyReadinessEvaluationRequest.md) |  | 

### Return type

[**TopologyReadinessSnapshot**](TopologyReadinessSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegionalTopologyReadinessLatest

> TopologyReadinessSnapshot RegionalTopologyReadinessLatest(ctx, topologyId).Execute()



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
	topologyId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.RegionalTopologyReadinessLatest(context.Background(), topologyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.RegionalTopologyReadinessLatest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegionalTopologyReadinessLatest`: TopologyReadinessSnapshot
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.RegionalTopologyReadinessLatest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**topologyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegionalTopologyReadinessLatestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TopologyReadinessSnapshot**](TopologyReadinessSnapshot.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsCheckpointList

> AnalyticsCheckpointListResponse SaasAnalyticsCheckpointList(ctx).OrganizationId(organizationId).Execute()



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
	organizationId := "organizationId_example" // string | Tenant organization UUID. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsCheckpointList(context.Background()).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsCheckpointList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsCheckpointList`: AnalyticsCheckpointListResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsCheckpointList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsCheckpointListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationId** | **string** | Tenant organization UUID. | 

### Return type

[**AnalyticsCheckpointListResponse**](AnalyticsCheckpointListResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsCheckpointRecoveryAction

> AnalyticsLeaseCheckpointActionResponse SaasAnalyticsCheckpointRecoveryAction(ctx, action, checkpointId).CheckpointRecoveryRequest(checkpointRecoveryRequest).Execute()



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
	action := "action_example" // string | 
	checkpointId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	checkpointRecoveryRequest := *openapiclient.NewCheckpointRecoveryRequest("ProjectionId_example", "IdempotencyKey_example", "Reason_example", int32(123), int32(123)) // CheckpointRecoveryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsCheckpointRecoveryAction(context.Background(), action, checkpointId).CheckpointRecoveryRequest(checkpointRecoveryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsCheckpointRecoveryAction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsCheckpointRecoveryAction`: AnalyticsLeaseCheckpointActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsCheckpointRecoveryAction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**action** | **string** |  | 
**checkpointId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsCheckpointRecoveryActionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **checkpointRecoveryRequest** | [**CheckpointRecoveryRequest**](CheckpointRecoveryRequest.md) |  | 

### Return type

[**AnalyticsLeaseCheckpointActionResponse**](AnalyticsLeaseCheckpointActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsEventDeadLetterPreview

> AnalyticsDeadLetterPreviewResponse SaasAnalyticsEventDeadLetterPreview(ctx, analyticsEventId).AnalyticsEventDeadLetterPreviewRequestRequest(analyticsEventDeadLetterPreviewRequestRequest).Execute()



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
	analyticsEventId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	analyticsEventDeadLetterPreviewRequestRequest := *openapiclient.NewAnalyticsEventDeadLetterPreviewRequestRequest() // AnalyticsEventDeadLetterPreviewRequestRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsEventDeadLetterPreview(context.Background(), analyticsEventId).AnalyticsEventDeadLetterPreviewRequestRequest(analyticsEventDeadLetterPreviewRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsEventDeadLetterPreview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsEventDeadLetterPreview`: AnalyticsDeadLetterPreviewResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsEventDeadLetterPreview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**analyticsEventId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsEventDeadLetterPreviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **analyticsEventDeadLetterPreviewRequestRequest** | [**AnalyticsEventDeadLetterPreviewRequestRequest**](AnalyticsEventDeadLetterPreviewRequestRequest.md) |  | 

### Return type

[**AnalyticsDeadLetterPreviewResponse**](AnalyticsDeadLetterPreviewResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsEventDeadLetterReplay

> AnalyticsDeadLetterReplayResponse SaasAnalyticsEventDeadLetterReplay(ctx, analyticsEventId).EventReplayRequest(eventReplayRequest).Execute()



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
	analyticsEventId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	eventReplayRequest := *openapiclient.NewEventReplayRequest("IdempotencyKey_example", "Reason_example") // EventReplayRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsEventDeadLetterReplay(context.Background(), analyticsEventId).EventReplayRequest(eventReplayRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsEventDeadLetterReplay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsEventDeadLetterReplay`: AnalyticsDeadLetterReplayResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsEventDeadLetterReplay`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**analyticsEventId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsEventDeadLetterReplayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **eventReplayRequest** | [**EventReplayRequest**](EventReplayRequest.md) |  | 

### Return type

[**AnalyticsDeadLetterReplayResponse**](AnalyticsDeadLetterReplayResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsLeaseRecoveryAction

> AnalyticsLeaseCheckpointActionResponse SaasAnalyticsLeaseRecoveryAction(ctx, action, leaseId).LeaseRecoveryRequest(leaseRecoveryRequest).Execute()



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
	action := "action_example" // string | 
	leaseId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	leaseRecoveryRequest := *openapiclient.NewLeaseRecoveryRequest("ProjectionId_example", "IdempotencyKey_example", "Reason_example", "ExpectedLeaseToken_example", int32(123)) // LeaseRecoveryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsLeaseRecoveryAction(context.Background(), action, leaseId).LeaseRecoveryRequest(leaseRecoveryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsLeaseRecoveryAction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsLeaseRecoveryAction`: AnalyticsLeaseCheckpointActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsLeaseRecoveryAction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**action** | **string** |  | 
**leaseId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsLeaseRecoveryActionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **leaseRecoveryRequest** | [**LeaseRecoveryRequest**](LeaseRecoveryRequest.md) |  | 

### Return type

[**AnalyticsLeaseCheckpointActionResponse**](AnalyticsLeaseCheckpointActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsRebuildAction

> AnalyticsRebuildActionResponse SaasAnalyticsRebuildAction(ctx, action, jobId).RebuildActionRequest(rebuildActionRequest).Execute()



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
	action := "action_example" // string | 
	jobId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	rebuildActionRequest := *openapiclient.NewRebuildActionRequest("ProjectionId_example", "IdempotencyKey_example", "Reason_example", int32(123), int32(123), int32(123)) // RebuildActionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsRebuildAction(context.Background(), action, jobId).RebuildActionRequest(rebuildActionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsRebuildAction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsRebuildAction`: AnalyticsRebuildActionResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsRebuildAction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**action** | **string** |  | 
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsRebuildActionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **rebuildActionRequest** | [**RebuildActionRequest**](RebuildActionRequest.md) |  | 

### Return type

[**AnalyticsRebuildActionResponse**](AnalyticsRebuildActionResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsRebuildPreview

> AnalyticsRebuildPreviewResponse SaasAnalyticsRebuildPreview(ctx, action, jobId).RebuildPreviewRequest(rebuildPreviewRequest).Execute()



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
	action := "action_example" // string | 
	jobId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	rebuildPreviewRequest := *openapiclient.NewRebuildPreviewRequest("ProjectionId_example") // RebuildPreviewRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsRebuildPreview(context.Background(), action, jobId).RebuildPreviewRequest(rebuildPreviewRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsRebuildPreview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsRebuildPreview`: AnalyticsRebuildPreviewResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsRebuildPreview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**action** | **string** |  | 
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsRebuildPreviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **rebuildPreviewRequest** | [**RebuildPreviewRequest**](RebuildPreviewRequest.md) |  | 

### Return type

[**AnalyticsRebuildPreviewResponse**](AnalyticsRebuildPreviewResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsRebuildProgressRepair

> AnalyticsRebuildProgressRepairResponse SaasAnalyticsRebuildProgressRepair(ctx, jobId).RebuildProgressRequest(rebuildProgressRequest).Execute()



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
	rebuildProgressRequest := *openapiclient.NewRebuildProgressRequest("ProjectionId_example", "IdempotencyKey_example", "Reason_example", int32(123), int32(123), int32(123), int32(123), int32(123), int32(123), int32(123), int32(123)) // RebuildProgressRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsRebuildProgressRepair(context.Background(), jobId).RebuildProgressRequest(rebuildProgressRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsRebuildProgressRepair``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsRebuildProgressRepair`: AnalyticsRebuildProgressRepairResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsRebuildProgressRepair`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsRebuildProgressRepairRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rebuildProgressRequest** | [**RebuildProgressRequest**](RebuildProgressRequest.md) |  | 

### Return type

[**AnalyticsRebuildProgressRepairResponse**](AnalyticsRebuildProgressRepairResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsRepairDeadLetterBulkReplay

> AnalyticsDeadLetterBulkReplayResponse SaasAnalyticsRepairDeadLetterBulkReplay(ctx).BulkRepairReplayRequest(bulkRepairReplayRequest).Execute()



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
	bulkRepairReplayRequest := *openapiclient.NewBulkRepairReplayRequest("ProjectionId_example", []string{"RepairIds_example"}, "IdempotencyKey_example", "Reason_example", int32(123), int32(123)) // BulkRepairReplayRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsRepairDeadLetterBulkReplay(context.Background()).BulkRepairReplayRequest(bulkRepairReplayRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsRepairDeadLetterBulkReplay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsRepairDeadLetterBulkReplay`: AnalyticsDeadLetterBulkReplayResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsRepairDeadLetterBulkReplay`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsRepairDeadLetterBulkReplayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkRepairReplayRequest** | [**BulkRepairReplayRequest**](BulkRepairReplayRequest.md) |  | 

### Return type

[**AnalyticsDeadLetterBulkReplayResponse**](AnalyticsDeadLetterBulkReplayResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsRepairDeadLetterPreview

> AnalyticsDeadLetterPreviewResponse SaasAnalyticsRepairDeadLetterPreview(ctx, repairId).RepairPreviewRequest(repairPreviewRequest).Execute()



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
	repairId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	repairPreviewRequest := *openapiclient.NewRepairPreviewRequest("ProjectionId_example") // RepairPreviewRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsRepairDeadLetterPreview(context.Background(), repairId).RepairPreviewRequest(repairPreviewRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsRepairDeadLetterPreview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsRepairDeadLetterPreview`: AnalyticsDeadLetterPreviewResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsRepairDeadLetterPreview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**repairId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsRepairDeadLetterPreviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **repairPreviewRequest** | [**RepairPreviewRequest**](RepairPreviewRequest.md) |  | 

### Return type

[**AnalyticsDeadLetterPreviewResponse**](AnalyticsDeadLetterPreviewResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasAnalyticsRepairDeadLetterReplay

> AnalyticsDeadLetterReplayResponse SaasAnalyticsRepairDeadLetterReplay(ctx, repairId).RepairReplayRequest(repairReplayRequest).Execute()



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
	repairId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	repairReplayRequest := *openapiclient.NewRepairReplayRequest("ProjectionId_example", "IdempotencyKey_example", "Reason_example", int32(123), int32(123), int32(123)) // RepairReplayRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasAnalyticsRepairDeadLetterReplay(context.Background(), repairId).RepairReplayRequest(repairReplayRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasAnalyticsRepairDeadLetterReplay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasAnalyticsRepairDeadLetterReplay`: AnalyticsDeadLetterReplayResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasAnalyticsRepairDeadLetterReplay`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**repairId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasAnalyticsRepairDeadLetterReplayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **repairReplayRequest** | [**RepairReplayRequest**](RepairReplayRequest.md) |  | 

### Return type

[**AnalyticsDeadLetterReplayResponse**](AnalyticsDeadLetterReplayResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)




## SaasDegradedModeEvaluate

> DegradedModeEvaluationResponse SaasDegradedModeEvaluate(ctx).DegradedModeEvaluationRequestRequest(degradedModeEvaluationRequestRequest).Execute()



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
	degradedModeEvaluationRequestRequest := *openapiclient.NewDegradedModeEvaluationRequestRequest("Intent_example") // DegradedModeEvaluationRequestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasDegradedModeEvaluate(context.Background()).DegradedModeEvaluationRequestRequest(degradedModeEvaluationRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasDegradedModeEvaluate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasDegradedModeEvaluate`: DegradedModeEvaluationResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasDegradedModeEvaluate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasDegradedModeEvaluateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **degradedModeEvaluationRequestRequest** | [**DegradedModeEvaluationRequestRequest**](DegradedModeEvaluationRequestRequest.md) |  | 

### Return type

[**DegradedModeEvaluationResponse**](DegradedModeEvaluationResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasDegradedModeOverrideCreate

> DegradedModeOverride SaasDegradedModeOverrideCreate(ctx).DegradedModeOverrideCreateRequestRequest(degradedModeOverrideCreateRequestRequest).Execute()



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
	degradedModeOverrideCreateRequestRequest := *openapiclient.NewDegradedModeOverrideCreateRequestRequest("OrganizationId_example", []string{"AllowedIntents_example"}, []string{"Authorities_example"}, "Reason_example", "ApprovedBy_example", time.Now(), time.Now()) // DegradedModeOverrideCreateRequestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasDegradedModeOverrideCreate(context.Background()).DegradedModeOverrideCreateRequestRequest(degradedModeOverrideCreateRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasDegradedModeOverrideCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasDegradedModeOverrideCreate`: DegradedModeOverride
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasDegradedModeOverrideCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasDegradedModeOverrideCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **degradedModeOverrideCreateRequestRequest** | [**DegradedModeOverrideCreateRequestRequest**](DegradedModeOverrideCreateRequestRequest.md) |  | 

### Return type

[**DegradedModeOverride**](DegradedModeOverride.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasDegradedModeOverrideDetail

> DegradedModeOverride SaasDegradedModeOverrideDetail(ctx, overrideId).Execute()



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
	overrideId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasDegradedModeOverrideDetail(context.Background(), overrideId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasDegradedModeOverrideDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasDegradedModeOverrideDetail`: DegradedModeOverride
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasDegradedModeOverrideDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**overrideId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasDegradedModeOverrideDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DegradedModeOverride**](DegradedModeOverride.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasDegradedModeOverrideList

> DegradedModeOverrideListResponse SaasDegradedModeOverrideList(ctx).OrganizationId(organizationId).Execute()



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
	organizationId := "organizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasDegradedModeOverrideList(context.Background()).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasDegradedModeOverrideList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasDegradedModeOverrideList`: DegradedModeOverrideListResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasDegradedModeOverrideList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasDegradedModeOverrideListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationId** | **string** |  | 

### Return type

[**DegradedModeOverrideListResponse**](DegradedModeOverrideListResponse.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasDegradedModeOverrideRevoke

> DegradedModeOverride SaasDegradedModeOverrideRevoke(ctx, overrideId).DegradedModeOverrideRevokeRequestRequest(degradedModeOverrideRevokeRequestRequest).Execute()



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
	overrideId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	degradedModeOverrideRevokeRequestRequest := *openapiclient.NewDegradedModeOverrideRevokeRequestRequest("RevokedBy_example", "Reason_example") // DegradedModeOverrideRevokeRequestRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasDegradedModeOverrideRevoke(context.Background(), overrideId).DegradedModeOverrideRevokeRequestRequest(degradedModeOverrideRevokeRequestRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasDegradedModeOverrideRevoke``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasDegradedModeOverrideRevoke`: DegradedModeOverride
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasDegradedModeOverrideRevoke`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**overrideId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasDegradedModeOverrideRevokeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **degradedModeOverrideRevokeRequestRequest** | [**DegradedModeOverrideRevokeRequestRequest**](DegradedModeOverrideRevokeRequestRequest.md) |  | 

### Return type

[**DegradedModeOverride**](DegradedModeOverride.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasOperatorMetrics

> string SaasOperatorMetrics(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.SaasOperatorMetrics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasOperatorMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasOperatorMetrics`: string
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasOperatorMetrics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSaasOperatorMetricsRequest struct via the builder pattern


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasOperatorOutbox

> SaaSOperatorOutboxResponse SaasOperatorOutbox(ctx).Destination(destination).Limit(limit).Status(status).Execute()



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
	destination := "destination_example" // string |  (optional)
	limit := int32(56) // int32 | Maximum records; bounded to 1..500. (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasOperatorOutbox(context.Background()).Destination(destination).Limit(limit).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasOperatorOutbox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasOperatorOutbox`: SaaSOperatorOutboxResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasOperatorOutbox`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasOperatorOutboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **destination** | **string** |  | 
 **limit** | **int32** | Maximum records; bounded to 1..500. | 
 **status** | **string** |  | 

### Return type

[**SaaSOperatorOutboxResponse**](SaaSOperatorOutboxResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasOperatorReservations

> SaaSOperatorReservationResponse SaasOperatorReservations(ctx).Limit(limit).Status(status).Execute()



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
	limit := int32(56) // int32 | Maximum records; bounded to 1..500. (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasOperatorReservations(context.Background()).Limit(limit).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasOperatorReservations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasOperatorReservations`: SaaSOperatorReservationResponse
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasOperatorReservations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasOperatorReservationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Maximum records; bounded to 1..500. | 
 **status** | **string** |  | 

### Return type

[**SaaSOperatorReservationResponse**](SaaSOperatorReservationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasOperatorSummary

> SaaSOperatorSummary SaasOperatorSummary(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.SaasOperatorSummary(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasOperatorSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasOperatorSummary`: SaaSOperatorSummary
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasOperatorSummary`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSaasOperatorSummaryRequest struct via the builder pattern


### Return type

[**SaaSOperatorSummary**](SaaSOperatorSummary.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasRuntimeGovernanceOverrideActive

> map[string]interface{} SaasRuntimeGovernanceOverrideActive(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.SaasRuntimeGovernanceOverrideActive(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasRuntimeGovernanceOverrideActive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasRuntimeGovernanceOverrideActive`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasRuntimeGovernanceOverrideActive`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSaasRuntimeGovernanceOverrideActiveRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasRuntimeGovernanceOverrideCreate

> map[string]interface{} SaasRuntimeGovernanceOverrideCreate(ctx).RuntimeGovernanceOverrideCreateRequest(runtimeGovernanceOverrideCreateRequest).Execute()



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
	runtimeGovernanceOverrideCreateRequest := *openapiclient.NewRuntimeGovernanceOverrideCreateRequest(openapiclient.ModeEnum("force_allow"), "Reason_example", int32(123)) // RuntimeGovernanceOverrideCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasRuntimeGovernanceOverrideCreate(context.Background()).RuntimeGovernanceOverrideCreateRequest(runtimeGovernanceOverrideCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasRuntimeGovernanceOverrideCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasRuntimeGovernanceOverrideCreate`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasRuntimeGovernanceOverrideCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasRuntimeGovernanceOverrideCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **runtimeGovernanceOverrideCreateRequest** | [**RuntimeGovernanceOverrideCreateRequest**](RuntimeGovernanceOverrideCreateRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasRuntimeGovernanceOverrideDetail

> map[string]interface{} SaasRuntimeGovernanceOverrideDetail(ctx, overrideId).Execute()



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
	overrideId := "overrideId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasRuntimeGovernanceOverrideDetail(context.Background(), overrideId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasRuntimeGovernanceOverrideDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasRuntimeGovernanceOverrideDetail`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasRuntimeGovernanceOverrideDetail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**overrideId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasRuntimeGovernanceOverrideDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasRuntimeGovernanceOverrideList

> map[string]interface{} SaasRuntimeGovernanceOverrideList(ctx).Limit(limit).Execute()



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
	limit := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasRuntimeGovernanceOverrideList(context.Background()).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasRuntimeGovernanceOverrideList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasRuntimeGovernanceOverrideList`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasRuntimeGovernanceOverrideList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaasRuntimeGovernanceOverrideListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | 

### Return type

**map[string]interface{}**

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaasRuntimeGovernanceOverrideRevoke

> map[string]interface{} SaasRuntimeGovernanceOverrideRevoke(ctx, overrideId).RuntimeGovernanceOverrideRevokeRequest(runtimeGovernanceOverrideRevokeRequest).Execute()



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
	overrideId := "overrideId_example" // string | 
	runtimeGovernanceOverrideRevokeRequest := *openapiclient.NewRuntimeGovernanceOverrideRevokeRequest(int32(123), "Reason_example") // RuntimeGovernanceOverrideRevokeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SaasRuntimeGovernanceOverrideRevoke(context.Background(), overrideId).RuntimeGovernanceOverrideRevokeRequest(runtimeGovernanceOverrideRevokeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SaasRuntimeGovernanceOverrideRevoke``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaasRuntimeGovernanceOverrideRevoke`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SaasRuntimeGovernanceOverrideRevoke`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**overrideId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaasRuntimeGovernanceOverrideRevokeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **runtimeGovernanceOverrideRevokeRequest** | [**RuntimeGovernanceOverrideRevokeRequest**](RuntimeGovernanceOverrideRevokeRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingConsumerQuarantineCreate

> ConsumerQuarantine SelfHealingConsumerQuarantineCreate(ctx).ConsumerQuarantineCreateRequest(consumerQuarantineCreateRequest).Execute()



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
	consumerQuarantineCreateRequest := *openapiclient.NewConsumerQuarantineCreateRequest("ConsumerId_example", "ReasonCode_example", "Reason_example") // ConsumerQuarantineCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SelfHealingConsumerQuarantineCreate(context.Background()).ConsumerQuarantineCreateRequest(consumerQuarantineCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingConsumerQuarantineCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingConsumerQuarantineCreate`: ConsumerQuarantine
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingConsumerQuarantineCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingConsumerQuarantineCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **consumerQuarantineCreateRequest** | [**ConsumerQuarantineCreateRequest**](ConsumerQuarantineCreateRequest.md) |  | 

### Return type

[**ConsumerQuarantine**](ConsumerQuarantine.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingConsumerQuarantineRelease

> ConsumerQuarantine SelfHealingConsumerQuarantineRelease(ctx, quarantineId).ConsumerQuarantineReleaseRequest(consumerQuarantineReleaseRequest).Execute()



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
	quarantineId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	consumerQuarantineReleaseRequest := *openapiclient.NewConsumerQuarantineReleaseRequest(int32(123), "Reason_example") // ConsumerQuarantineReleaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SelfHealingConsumerQuarantineRelease(context.Background(), quarantineId).ConsumerQuarantineReleaseRequest(consumerQuarantineReleaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingConsumerQuarantineRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingConsumerQuarantineRelease`: ConsumerQuarantine
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingConsumerQuarantineRelease`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quarantineId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingConsumerQuarantineReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **consumerQuarantineReleaseRequest** | [**ConsumerQuarantineReleaseRequest**](ConsumerQuarantineReleaseRequest.md) |  | 

### Return type

[**ConsumerQuarantine**](ConsumerQuarantine.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingHealthLiveness

> map[string]interface{} SelfHealingHealthLiveness(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.SelfHealingHealthLiveness(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingHealthLiveness``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingHealthLiveness`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingHealthLiveness`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingHealthLivenessRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingHealthReadiness

> map[string]interface{} SelfHealingHealthReadiness(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.SelfHealingHealthReadiness(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingHealthReadiness``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingHealthReadiness`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingHealthReadiness`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingHealthReadinessRequest struct via the builder pattern


### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingMetrics

> string SelfHealingMetrics(ctx).Execute()



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
	resp, r, err := apiClient.OperatorAPI.SelfHealingMetrics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingMetrics`: string
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingMetrics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingMetricsRequest struct via the builder pattern


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingRecoveryEscalationAcknowledge

> RecoveryEscalation SelfHealingRecoveryEscalationAcknowledge(ctx, escalationId).EscalationAcknowledgeRequest(escalationAcknowledgeRequest).Execute()



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
	escalationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	escalationAcknowledgeRequest := *openapiclient.NewEscalationAcknowledgeRequest(int32(123)) // EscalationAcknowledgeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SelfHealingRecoveryEscalationAcknowledge(context.Background(), escalationId).EscalationAcknowledgeRequest(escalationAcknowledgeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingRecoveryEscalationAcknowledge``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingRecoveryEscalationAcknowledge`: RecoveryEscalation
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingRecoveryEscalationAcknowledge`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**escalationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingRecoveryEscalationAcknowledgeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **escalationAcknowledgeRequest** | [**EscalationAcknowledgeRequest**](EscalationAcknowledgeRequest.md) |  | 

### Return type

[**RecoveryEscalation**](RecoveryEscalation.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingRecoveryEscalationResolve

> RecoveryEscalation SelfHealingRecoveryEscalationResolve(ctx, escalationId).EscalationResolveRequest(escalationResolveRequest).Execute()



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
	escalationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	escalationResolveRequest := *openapiclient.NewEscalationResolveRequest(int32(123), "Resolution_example") // EscalationResolveRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SelfHealingRecoveryEscalationResolve(context.Background(), escalationId).EscalationResolveRequest(escalationResolveRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingRecoveryEscalationResolve``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingRecoveryEscalationResolve`: RecoveryEscalation
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingRecoveryEscalationResolve`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**escalationId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingRecoveryEscalationResolveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **escalationResolveRequest** | [**EscalationResolveRequest**](EscalationResolveRequest.md) |  | 

### Return type

[**RecoveryEscalation**](RecoveryEscalation.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingRecoveryExecutionCancel

> RuntimeRecoveryExecutionDetail SelfHealingRecoveryExecutionCancel(ctx, executionId).RecoveryCancelRequest(recoveryCancelRequest).Execute()



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
	recoveryCancelRequest := *openapiclient.NewRecoveryCancelRequest(int32(123), "Reason_example") // RecoveryCancelRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SelfHealingRecoveryExecutionCancel(context.Background(), executionId).RecoveryCancelRequest(recoveryCancelRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingRecoveryExecutionCancel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingRecoveryExecutionCancel`: RuntimeRecoveryExecutionDetail
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingRecoveryExecutionCancel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingRecoveryExecutionCancelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **recoveryCancelRequest** | [**RecoveryCancelRequest**](RecoveryCancelRequest.md) |  | 

### Return type

[**RuntimeRecoveryExecutionDetail**](RuntimeRecoveryExecutionDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfHealingRecoveryExecutionRetry

> RuntimeRecoveryExecutionDetail SelfHealingRecoveryExecutionRetry(ctx, executionId).RecoveryRetryRequest(recoveryRetryRequest).Execute()



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
	recoveryRetryRequest := *openapiclient.NewRecoveryRetryRequest(int32(123), "IdempotencyKey_example") // RecoveryRetryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperatorAPI.SelfHealingRecoveryExecutionRetry(context.Background(), executionId).RecoveryRetryRequest(recoveryRetryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperatorAPI.SelfHealingRecoveryExecutionRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfHealingRecoveryExecutionRetry`: RuntimeRecoveryExecutionDetail
	fmt.Fprintf(os.Stdout, "Response from `OperatorAPI.SelfHealingRecoveryExecutionRetry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**executionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSelfHealingRecoveryExecutionRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **recoveryRetryRequest** | [**RecoveryRetryRequest**](RecoveryRetryRequest.md) |  | 

### Return type

[**RuntimeRecoveryExecutionDetail**](RuntimeRecoveryExecutionDetail.md)

### Authorization

[cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

