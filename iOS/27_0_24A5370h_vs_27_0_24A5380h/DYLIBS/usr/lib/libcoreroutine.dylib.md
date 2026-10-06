## libcoreroutine.dylib

> `/usr/lib/libcoreroutine.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b003c` | `0x6b5624` | **`+0x55e8`** |
| `__TEXT.__oslogstring` | `0x88b9d` | `0x8992d` | **`+0xd90`** |
| `__DATA_DIRTY.__objc_data` | `0xbf90` | `0xc7b0` | **`+0x820`** |
| `__AUTH.__objc_data` | `0x2250` | `0x1ad0` | **`-0x780`** |
| `__AUTH_CONST.__objc_const` | `0x561c0` | `0x56850` | **`+0x690`** |
| `__TEXT.__cstring` | `0x4a0f0` | `0x4a64a` | **`+0x55a`** |
| `__AUTH_CONST.__cfstring` | `0x2b460` | `0x2b820` | **`+0x3c0`** |
| `__TEXT.__objc_methlist` | `0x34940` | `0x34c60` | **`+0x320`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b210` | `0x1b3d8` | **`+0x1c8`** |
| `__DATA_CONST.__const` | `0x10508` | `0x105f0` | **`+0xe8`** |
| `__TEXT.__gcc_except_tab` | `0x2e9a8` | `0x2ea88` | **`+0xe0`** |
| `__DATA_DIRTY.__data` | `0x730` | `0x7d8` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0xf118` | `0xf1c0` | **`+0xa8`** |
| `__DATA.__data` | `0x2e68` | `0x2dc8` | **`-0xa0`** |
| `__DATA.__objc_ivar` | `0x286c` | `0x28dc` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x34d0` | `0x3510` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x36b8` | `0x36d8` | **`+0x20`** |
| `__AUTH_CONST.__objc_doubleobj` | `0xbc0` | `0xbe0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x1678` | `0x1688` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1268` | `0x1278` | **`+0x10`** |
| `__TEXT.__const` | `0x4be8` | `0x4bd8` | **`-0x10`** |
| `__DATA.__bss` | `0x88` | `0x80` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x230` | `0x238` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1270` | `0x1278` | **`+0x8`** |

### Other Changes

```diff

-1114.0.0.0.0
+1117.0.0.0.0

-  Functions: 21891
-  Symbols:   33776
-  CStrings:  16224
+  Functions: 21965
+  Symbols:   33894
+  CStrings:  16306
Symbols:
+ +[RTFloorTransitionExtractor extractFloorTransitionFeatures:startIndex:labeledSimplifiedData:clusterResult:visitUUID:analyticsMetrics:]
+ +[RTFloorTransitionExtractor extractTransitionsFromElevationData:]
+ -[RTAltimeterFloorMapDataManager createFloorMapForLOI:learnedLocationStore:visitManager:reply:]
+ -[RTAltimeterFloorMapDataManager createFloorMapForVisit:rawAltimeterDataManager:locationManager:learnedLocationStore:reply:]
+ -[RTAltimeterFloorMapDataManager createLOIFloorMapFromVisits:learnedLocationStore:visitManager:reply:]
+ -[RTAltimeterFloorMapDataManager initWithAltimeterFloorMapDataStore:defaultsManager:learnedLocationStore:visitStore:]
+ -[RTAltimeterFloorMapDataManager setVisitStore:]
+ -[RTAltimeterFloorMapDataManager visitStore]
+ -[RTClientListenerInternal altimeterFloorMapDataManager]
+ -[RTClientListenerInternal initWithAccountManager:assetManager:authorizationManager:bluePOITileManager:buildingPolygonManager:dataIntegrityManager:deviceLocationPredictor:diagnostics:eventAgentManager:eventModelProvider:authorizedLocationManager:fingerprintManager:hintManager:intermittentGNSSManager:learnedLocationManager:learnedLocationStore:locationManager:locationStore:mapServiceManager:motionActivityManager:peopleDiscoveryProvider:persistenceManager:placeInferenceQueryStore:platform:pointOfInterestSampler:predictedContextManager:purgeManager:safetyCacheStore:scenarioTriggerManager:userCurationManager:vehicleLocationProvider:visitManager:tripSegmentManager:workoutRouteManager:workoutScheduler:rawAltimeterDataManager:altimeterFloorMapDataManager:]
+ -[RTClientListenerInternal setAltimeterFloorMapDataManager:]
+ -[RTClusterLearnedRouteMetrics localCloudReconciliationMetrics]
+ -[RTClusterLearnedRouteMetrics prepareLocalCloudReconciliationMetrics]
+ -[RTClusterLearnedRouteMetrics setLocalCloudReconciliationMetrics:]
+ -[RTDaemonClientInternal altimeterFloorMapDataManager]
+ -[RTDaemonClientInternal createFloorMapForLOI:reply:]
+ -[RTDaemonClientInternal createFloorMapForVisit:reply:]
+ -[RTDaemonClientInternal fetchTransactionDiagnosticsSampledWithReply:]
+ -[RTDaemonClientInternal initWithQueue:accountManager:assetManager:authorizationManager:bluePOITileManager:buildingPolygonManager:dataIntegrityManager:deviceLocationPredictor:diagnostics:eventModelProvider:authorizedLocationManager:fingerprintManager:hintManager:intermittentGNSSManager:learnedLocationManager:learnedLocationStore:locationManager:locationStore:mapServiceManager:motionActivityManager:peopleDiscoveryProvider:persistenceManager:placeInferenceQueryStore:pointOfInterestSampler:predictedContextManager:purgeManager:safetyCacheStore:scenarioTriggerManager:userCurationManager:vehicleLocationProvider:visitManager:tripSegmentManager:workoutRouteManager:workoutScheduler:rawAltimeterDataManager:altimeterFloorMapDataManager:]
+ -[RTDaemonClientInternal setAltimeterFloorMapDataManager:]
+ -[RTDaemonClientInternal setTransactionDiagnosticsSampled:reply:]
+ -[RTDiagnostics fetchTransactionDiagnosticsSampled]
+ -[RTDiagnostics setTransactionDiagnosticsSampled:]
+ -[RTFloorTransitionExtractor _advanceBufferWithSample:]
+ -[RTFloorTransitionExtractor _calculateAndStoreLevelWindowIfReady:]
+ -[RTFloorTransitionExtractor _computeBufferStatistics:elevationVariance:stepAverage:weightedTime:]
+ -[RTFloorTransitionExtractor _endTransitionWithBufferMean:elevationVariance:stepAverage:weightedTime:]
+ -[RTFloorTransitionExtractor _extractFloorTransitionFeatures:startIndex:labeledSimplifiedData:clusterResult:visitUUID:analyticsMetrics:]
+ -[RTFloorTransitionExtractor _extractTransitionsFromElevationDataWithStartIndex:startIndex:]
+ -[RTFloorTransitionExtractor _initializeBufferWithSample:]
+ -[RTFloorTransitionExtractor _processNewSample:]
+ -[RTFloorTransitionExtractor _seedLevelWindowAnchorFromCurrentBuffer]
+ -[RTFloorTransitionExtractor levelWindowAnchorTime]
+ -[RTFloorTransitionExtractor setLevelWindowAnchorTime:]
+ -[RTFloorTransitionExtractor setSettleCandidateTime:]
+ -[RTFloorTransitionExtractor setTransitionEndElevationVariance:]
+ -[RTFloorTransitionExtractor setTransitionStartElevationVariance:]
+ -[RTFloorTransitionExtractor settleCandidateTime]
+ -[RTFloorTransitionExtractor transitionEndElevationVariance]
+ -[RTFloorTransitionExtractor transitionStartElevationVariance]
+ -[RTInferredMapItemFuser fusedInferredMapItemsUsingCandidates:referenceLocation:snapToBestKnownPlace:snapToBestAoi:includeNonWinningCandidates:unfilteredBluePOICandidates:error:]
+ -[RTLearnedFloorMap createClusteredFloorMapDataFromVisits:withDataManager:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics .cxx_destruct]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics bootstrapFromCloudTriggered]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics clusterSyncCompletenessRatio]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics deviceOwnedClusterRatio]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics initForDefaultMetric]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics init]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics numDeviceOwnedClustersNotInCloudAfterSync]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics numDeviceOwnedClusters]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics numTraversalCountMismatches]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics postLearningSyncDurationMs]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics preLearningSyncDurationMs]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setBootstrapFromCloudTriggered:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setClusterSyncCompletenessRatio:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setDeviceOwnedClusterRatio:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setNumDeviceOwnedClusters:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setNumDeviceOwnedClustersNotInCloudAfterSync:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setNumTraversalCountMismatches:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setPostLearningSyncDurationMs:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setPreLearningSyncDurationMs:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setSyncErrorCount:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setSyncSkippedDueToDeferral:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setToCloud:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics setToLocal:]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics syncErrorCount]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics syncSkippedDueToDeferral]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics toCloud]
+ -[RTLearnedRouteLocalCloudReconciliationMetrics toLocal]
+ -[RTLearnedRouteSyncDirectionMetrics initForDefaultMetric]
+ -[RTLearnedRouteSyncDirectionMetrics init]
+ -[RTLearnedRouteSyncDirectionMetrics numClustersStored]
+ -[RTLearnedRouteSyncDirectionMetrics numClustersUpdated]
+ -[RTLearnedRouteSyncDirectionMetrics numRecenciesStored]
+ -[RTLearnedRouteSyncDirectionMetrics numSchedulesStored]
+ -[RTLearnedRouteSyncDirectionMetrics numWaypointClustersStored]
+ -[RTLearnedRouteSyncDirectionMetrics setNumClustersStored:]
+ -[RTLearnedRouteSyncDirectionMetrics setNumClustersUpdated:]
+ -[RTLearnedRouteSyncDirectionMetrics setNumRecenciesStored:]
+ -[RTLearnedRouteSyncDirectionMetrics setNumSchedulesStored:]
+ -[RTLearnedRouteSyncDirectionMetrics setNumWaypointClustersStored:]
+ -[RTTripClusterDataStoresContainer computePostSyncMetrics]
+ -[RTTripClusterDataStoresContainer reconciliationMetrics]
+ -[RTTripClusterDataStoresContainer resetReconciliationMetrics]
+ -[RTTripClusterManager _submitReconciliationMetrics]
+ GCC_except_table116
+ _NSFileTypeDirectory
+ _OBJC_CLASS_$_RTLearnedRouteLocalCloudReconciliationMetrics
+ _OBJC_CLASS_$_RTLearnedRouteSyncDirectionMetrics
+ _OBJC_IVAR_$_RTClusterLearnedRouteMetrics._localCloudReconciliationMetrics
+ _OBJC_IVAR_$_RTDaemonClientInternal._altimeterFloorMapDataManager
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._buffer
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferCount
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferEndTime
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferTailIdx
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferTotalWeight
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferWeightedEleSum
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferWeightedEleVarSum
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferWeightedStepSum
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._bufferWeightedTimeSum
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._levelWindowAnchorTime
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._settleCandidateTime
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._transitionEndElevationVariance
+ _OBJC_IVAR_$_RTFloorTransitionExtractor._transitionStartElevationVariance
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._bootstrapFromCloudTriggered
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._clusterSyncCompletenessRatio
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._deviceOwnedClusterRatio
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._numDeviceOwnedClusters
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._numDeviceOwnedClustersNotInCloudAfterSync
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._numTraversalCountMismatches
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._postLearningSyncDurationMs
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._preLearningSyncDurationMs
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._syncErrorCount
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._syncSkippedDueToDeferral
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._toCloud
+ _OBJC_IVAR_$_RTLearnedRouteLocalCloudReconciliationMetrics._toLocal
+ _OBJC_IVAR_$_RTLearnedRouteSyncDirectionMetrics._numClustersStored
+ _OBJC_IVAR_$_RTLearnedRouteSyncDirectionMetrics._numClustersUpdated
+ _OBJC_IVAR_$_RTLearnedRouteSyncDirectionMetrics._numRecenciesStored
+ _OBJC_IVAR_$_RTLearnedRouteSyncDirectionMetrics._numSchedulesStored
+ _OBJC_IVAR_$_RTLearnedRouteSyncDirectionMetrics._numWaypointClustersStored
+ _OBJC_IVAR_$_RTTripClusterDataStoresContainer._reconciliationMetrics
+ _OBJC_METACLASS_$_RTLearnedRouteLocalCloudReconciliationMetrics
+ _OBJC_METACLASS_$_RTLearnedRouteSyncDirectionMetrics
+ _RTAnalyticsEventRTTripClusterLearnedRouteLocalCloudReconciliation
+ __OBJC_$_CLASS_METHODS_RTFloorTransitionExtractor
+ __OBJC_$_INSTANCE_METHODS_RTLearnedRouteLocalCloudReconciliationMetrics
+ __OBJC_$_INSTANCE_METHODS_RTLearnedRouteSyncDirectionMetrics
+ __OBJC_$_INSTANCE_VARIABLES_RTLearnedRouteLocalCloudReconciliationMetrics
+ __OBJC_$_INSTANCE_VARIABLES_RTLearnedRouteSyncDirectionMetrics
+ __OBJC_$_PROP_LIST_RTLearnedRouteLocalCloudReconciliationMetrics
+ __OBJC_$_PROP_LIST_RTLearnedRouteSyncDirectionMetrics
+ __OBJC_CLASS_RO_$_RTLearnedRouteLocalCloudReconciliationMetrics
+ __OBJC_CLASS_RO_$_RTLearnedRouteSyncDirectionMetrics
+ __OBJC_METACLASS_RO_$_RTLearnedRouteLocalCloudReconciliationMetrics
+ __OBJC_METACLASS_RO_$_RTLearnedRouteSyncDirectionMetrics
+ ___102-[RTAltimeterFloorMapDataManager createLOIFloorMapFromVisits:learnedLocationStore:visitManager:reply:]_block_invoke
+ ___124-[RTAltimeterFloorMapDataManager createFloorMapForVisit:rawAltimeterDataManager:locationManager:learnedLocationStore:reply:]_block_invoke
+ ___178-[RTInferredMapItemFuser fusedInferredMapItemsUsingCandidates:referenceLocation:snapToBestKnownPlace:snapToBestAoi:includeNonWinningCandidates:unfilteredBluePOICandidates:error:]_block_invoke
+ ___178-[RTInferredMapItemFuser fusedInferredMapItemsUsingCandidates:referenceLocation:snapToBestKnownPlace:snapToBestAoi:includeNonWinningCandidates:unfilteredBluePOICandidates:error:]_block_invoke_2
+ ___50-[RTDiagnostics setTransactionDiagnosticsSampled:]_block_invoke
+ ___51-[RTDiagnostics fetchTransactionDiagnosticsSampled]_block_invoke
+ ___65-[RTDaemonClientInternal setTransactionDiagnosticsSampled:reply:]_block_invoke
+ ___70-[RTDaemonClientInternal fetchTransactionDiagnosticsSampledWithReply:]_block_invoke
+ ___block_descriptor_33_e5_v8?0l
+ ___block_descriptor_49_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_56_e8_32s40r48r_e32_v28?0"NSArray"8B16"NSError"20ls32l8r40l8r48l8
+ ___block_descriptor_64_e8_32s40s48s56r_e17_v16?0"NSError"8ls32l8s40l8r56l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e36_v24?0"RTLearnedVisit"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s80l8s72l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e5_v8?0ls32l8s40l8s48l8s80l8s56l8s64l8s72l8
- -[RTAltimeterFloorMapDataManager initWithAltimeterFloorMapDataStore:defaultsManager:learnedLocationStore:]
- -[RTClientListenerInternal initWithAccountManager:assetManager:authorizationManager:bluePOITileManager:buildingPolygonManager:dataIntegrityManager:deviceLocationPredictor:diagnostics:eventAgentManager:eventModelProvider:authorizedLocationManager:fingerprintManager:hintManager:intermittentGNSSManager:learnedLocationManager:learnedLocationStore:locationManager:locationStore:mapServiceManager:motionActivityManager:peopleDiscoveryProvider:persistenceManager:placeInferenceQueryStore:platform:pointOfInterestSampler:predictedContextManager:purgeManager:safetyCacheStore:scenarioTriggerManager:userCurationManager:vehicleLocationProvider:visitManager:tripSegmentManager:workoutRouteManager:workoutScheduler:rawAltimeterDataManager:]
- -[RTDaemonClientInternal initWithQueue:accountManager:assetManager:authorizationManager:bluePOITileManager:buildingPolygonManager:dataIntegrityManager:deviceLocationPredictor:diagnostics:eventModelProvider:authorizedLocationManager:fingerprintManager:hintManager:intermittentGNSSManager:learnedLocationManager:learnedLocationStore:locationManager:locationStore:mapServiceManager:motionActivityManager:peopleDiscoveryProvider:persistenceManager:placeInferenceQueryStore:pointOfInterestSampler:predictedContextManager:purgeManager:safetyCacheStore:scenarioTriggerManager:userCurationManager:vehicleLocationProvider:visitManager:tripSegmentManager:workoutRouteManager:workoutScheduler:rawAltimeterDataManager:]
- -[RTFloorTransitionExtractor _accumulateLevelTime:]
- -[RTFloorTransitionExtractor _calculateAndStoreLevelWindow:]
- -[RTFloorTransitionExtractor _calculateEvent:atIndex:]
- -[RTFloorTransitionExtractor _endEdgeDetection:]
- -[RTFloorTransitionExtractor _endTransition:]
- -[RTFloorTransitionExtractor _updateTransition:]
- -[RTFloorTransitionExtractor elevationData]
- -[RTFloorTransitionExtractor extractFloorTransitionFeatures:startIndex:labeledSimplifiedData:clusterResult:visitUUID:analyticsMetrics:]
- -[RTFloorTransitionExtractor extractTransitionsFromElevationData:]
- -[RTFloorTransitionExtractor extractTransitionsFromElevationDataWithStartIndex:startIndex:]
- -[RTFloorTransitionExtractor processElevationChangeEvent:]
- -[RTFloorTransitionExtractor setElevationData:]
- -[RTFloorTransitionExtractor setStableElevationDuration:]
- -[RTFloorTransitionExtractor setTransitionEndUncertainty:]
- -[RTFloorTransitionExtractor setTransitionStartUncertainty:]
- -[RTFloorTransitionExtractor stableElevationDuration]
- -[RTFloorTransitionExtractor transitionEndUncertainty]
- -[RTFloorTransitionExtractor transitionStartUncertainty]
- -[RTInferredMapItemFuser fusedInferredMapItemsUsingCandidates:referenceLocation:snapToBestKnownPlace:snapToBestAoi:unfilteredBluePOICandidates:error:]
- -[RTLearnedFloorMap _createClusteredFloorMapDataFromVisits:withDataManager:]
- -[RTVisitPipelineModuleAltitudeEstimator rawAltimeterData]
- -[RTVisitPipelineModuleAltitudeEstimator setRawAltimeterData:]
- _OBJC_IVAR_$_RTFloorTransitionExtractor._elevationData
- _OBJC_IVAR_$_RTFloorTransitionExtractor._stableElevationDuration
- _OBJC_IVAR_$_RTFloorTransitionExtractor._transitionEndUncertainty
- _OBJC_IVAR_$_RTFloorTransitionExtractor._transitionStartUncertainty
- _OBJC_IVAR_$_RTVisitPipelineModuleAltitudeEstimator._rawAltimeterData
- ___150-[RTInferredMapItemFuser fusedInferredMapItemsUsingCandidates:referenceLocation:snapToBestKnownPlace:snapToBestAoi:unfilteredBluePOICandidates:error:]_block_invoke
- ___150-[RTInferredMapItemFuser fusedInferredMapItemsUsingCandidates:referenceLocation:snapToBestKnownPlace:snapToBestAoi:unfilteredBluePOICandidates:error:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48r_e32_v28?0"NSArray"8B16"NSError"20ls32l8r48l8s40l8
CStrings:
+ "#altimeter,_fetchRawAltimeterDataFromStartTime,isContinue,%d,altimeterData,%lu"
+ "#altimeter,_fetchRawAltimeterDataFromStartTime,timeout,%@"
+ "#altimeter,advanceBufferWithSample,buffer overflow,count,%lu,visitUUID,%{private}@"
+ "#altimeter,calculateAndStoreLevelWindow,startWeightedTime,%.3f,endWeightedTime,%.3f,deltaH,%.3f,visitUUID,%{private}@"
+ "#altimeter,calculateAndStoreLevelWindowIfReady,no post-incorporation buffer stats,visitUUID,%{private}@"
+ "#altimeter,calculateAndStoreTransitionFeatures,isLevelWindow,%d,startTime,%.3f,endTime,%.3f,altitudeChange,%.3f,uncertainty,%.3f,duration,%.1f,stepCountChange,%.2f,visitUUID,%{private}@"
+ "#altimeter,createFloorTransitionModelEntriesFromLabeledData,values exceed int16_t,startFloorIdx,%lu,endFloorIdx,%lu,occurrenceCount,%lu,visitUUID,%{private}@"
+ "#altimeter,createGroupedAltimeterData,no positive-duration samples in time range (invalid or missing timestamps),startTime,%{private}@,endTime,%{private}@,visitUUID,%{private}@"
+ "#altimeter,createGroupedAltimeterData,pointCount,%lu,mean,%.2f,uncertainty,%.2f,visitUUID,%{private}@"
+ "#altimeter,endTransition,t_candidate,%.3f,t_end,%.3f,sustained,%.1f,visitUUID,%{private}@"
+ "#altimeter,enumerate visit elevation profile,timestamp,%f,altitude,%f,uncertainty,%f,sampleDuration,%f,visitUUID,%{private}@"
+ "#altimeter,processEventInLevelState,unexpected missing buffer stats,bufferCount,%lu,visitUUID,%{private}@"
+ "#altimeter,processEventInTransitioningState,no post-incorporation buffer stats,visitUUID,%{private}@"
+ "#altimeter,processEventInTransitioningState,unexpected missing buffer stats,bufferCount,%lu,visitUUID,%{private}@"
+ "#altimeter,processNewSample,state,%lu,H_t,%.3f,H_bar_pre,%.3f,sampleEnd,%.3f,sampleDuration,%.3f,visitUUID,%{private}@"
+ "#altimeter,processNewSample,unexpected data gap,gapSize,%.1f,visitUUID,%{private}@"
+ "#altimeter,reset state machine"
+ "#altimeter,seedLevelWindowAnchor,no buffer stats from initialized buffer,visitUUID,%{private}@"
+ "#altimeter,settle candidate marked,t_candidate,%.3f,H_t,%.3f,H_bar_pre,%.3f,visitUUID,%{private}@"
+ "#altimeter,settle candidate reset,H_t,%.3f,H_bar_pre,%.3f,visitUUID,%{private}@"
+ "#altimeter,startEdgeDetection,t_i,%.3f,H_i,%.3f,startSteps,%.2f,visitUUID,%{private}@"
+ "#altimeter,startEdgeDetection,unexpected missing buffer stats,visitUUID,%{private}@"
+ "#altimeter,startTransition,H_t,%.3f,H_bar_pre,%.3f,sampleEnd,%.3f,visitUUID,%{private}@"
+ "%@, %@, Cache file count exceeded scan cap (%lu) at %@; stopping scan"
+ "%@, %@, Found unexpected files (sampled first %lu)"
+ "%@, %@, Skipping cache file-extension check (not internal install)"
+ "%@, fetched transaction diagnostics sampled: %@"
+ "%@, set transaction diagnostics sampled to %@"
+ "%@, skipping append of non-winning candidates"
+ "%@,computePostSyncMetrics: local store is empty, skipping per-cluster checks"
+ "%@,computePostSyncMetrics: ratio=%.2f deviceOwned=%d notInCloud=%d traversalCountMismatches=%d deviceOwnedRatio=%.2f"
+ "%@:%@,Local cloud reconciliation metrics collection"
+ "-[RTAltimeterFloorMapDataManager createFloorMapForLOI:learnedLocationStore:visitManager:reply:]"
+ "-[RTAltimeterFloorMapDataManager createFloorMapForVisit:rawAltimeterDataManager:locationManager:learnedLocationStore:reply:]"
+ "-[RTAltimeterFloorMapDataManager createLOIFloorMapFromVisits:learnedLocationStore:visitManager:reply:]"
+ "-[RTDaemonClientInternal createFloorMapForLOI:reply:]"
+ "-[RTDaemonClientInternal createFloorMapForVisit:reply:]"
+ "02:54:25"
+ "AltimeterFloorMapDataManager is nil"
+ "BootstrapFromCloudTriggered"
+ "ClusterSyncCompletenessRatio"
+ "DeviceOwnedClusterRatio"
+ "Failed to create LOI floor map data object"
+ "Failed to create altitude estimator"
+ "Failed to create clustered floor map"
+ "Floor map result missing floorMapArray"
+ "Invalid parameter not satisfying: altimeterFloorMapDataManager"
+ "Invalid parameter not satisfying: loiUUID (in %s:%d)"
+ "Invalid visit properties"
+ "Invalid visit time bounds"
+ "Jun 28 2026"
+ "No learned visits found in date interval"
+ "NumClustersStoredToCloud"
+ "NumClustersStoredToLocal"
+ "NumClustersUpdatedInCloud"
+ "NumClustersUpdatedInLocal"
+ "NumDeviceOwnedClusters"
+ "NumDeviceOwnedClustersNotInCloudAfterSync"
+ "NumRecenciesStoredToCloud"
+ "NumRecenciesStoredToLocal"
+ "NumSchedulesStoredToCloud"
+ "NumSchedulesStoredToLocal"
+ "NumTraversalCountMismatches"
+ "NumWaypointClustersStoredToCloud"
+ "NumWaypointClustersStoredToLocal"
+ "PostLearningSyncDurationMs"
+ "PreLearningSyncDurationMs"
+ "R"
+ "RTAltimeterFloorMapDataManager successfully initialized."
+ "RTTransactionManager shared instance not set, cannot fetch sampling state"
+ "RTTransactionManager shared instance not set, cannot override sampling"
+ "Skipping data integrity validation registration (not internal install)"
+ "Skipping routined IPS log check (RBC not allowed)"
+ "SyncErrorCount"
+ "SyncSkippedDueToDeferral"
+ "Transaction diagnostics sampling override set to %@"
+ "createFloorMapForLOI, loiUUID,%{public}@"
+ "createFloorMapForVisit, failed to create RTVisitPipelineModuleAltitudeEstimator"
+ "createFloorMapForVisit, invalid visit: entry,%{public}@, exit,%{public}@, identifier,%{public}@"
+ "createFloorMapForVisit, learnedLocationStore store failed: %{public}@"
+ "createFloorMapForVisit, rawAltimeterDataManager is nil"
+ "createFloorMapForVisit, reply, visit identifier,%{public}@, updated visit,%{public}@, latency,%.2f"
+ "createFloorMapForVisit, stored learned visit, identifier,%{public}@"
+ "createFloorMapForVisit, validation FAILED — no RTLearnedVisit found for identifier,%{public}@"
+ "createFloorMapForVisit, validation OK — RTLearnedVisit found: identifier,%{public}@, entry,%{public}@, exit,%{public}@"
+ "createFloorMapForVisit, validation fetch failed: %{public}@"
+ "createFloorMapForVisit, visit identifier,%{public}@, entry,%{public}@, exit,%{public}@"
+ "createLOIFloorMapFromVisits, RTVisitMO entries purged"
+ "createLOIFloorMapFromVisits, failed to create RTAltimeterFloorMapData for LOI: %{public}@"
+ "createLOIFloorMapFromVisits, failed to create clustered floor map for LOI: %{public}@"
+ "createLOIFloorMapFromVisits, failed to store LOI floor map: %{public}@, error: %{public}@"
+ "createLOIFloorMapFromVisits, fetch failed: %{public}@"
+ "createLOIFloorMapFromVisits, fetched %{public}lu learned visit(s) for clustering"
+ "createLOIFloorMapFromVisits, fetching learned visits in interval %{public}@ — %{public}@"
+ "createLOIFloorMapFromVisits, floor map result missing floorMapArray for LOI: %{public}@"
+ "createLOIFloorMapFromVisits, invalid visit time bounds for LOI: %{public}@"
+ "createLOIFloorMapFromVisits, loiUUID,%{public}@"
+ "createLOIFloorMapFromVisits, no learned visits found — ensure createFloorMapForVisit ran first"
+ "createLOIFloorMapFromVisits, success, loiUUID,%{public}@, latency,%.2f"
+ "createLOIFloorMapFromVisits, visit purge failed: %{public}@"
+ "createLOIFloorMapFromVisits,,%d,learned visit,%{public}@"
+ "currentLOIUUID"
+ "r"
+ "rawAltimeterDataManager is nil"
+ "routined.LearnedRoutesLocalCloudReconciliation"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x93"
- "#altimeter,_fetchRawAltimeterDataFromStartTime,isContinue,%d,_rawAltimeterData,%lu,altimeterData,%lu"
- "#altimeter,calculateAndStoreLevelWindow,missing window start data,visitUUID,%{private}@"
- "#altimeter,calculateAndStoreLevelWindow,stored level window,startTime,%.3f,endTime,%.3f,deltaH,%.3f,visitUUID,%{private}@"
- "#altimeter,calculateAndStoreTransitionFeatures,added transition,startTime,%.3f,endTime,%.3f,altitudeChange,%.3f,uncertainty,%.3f,duration,%.1f,stepCountChange,%d,visitUUID,%{private}@"
- "#altimeter,createFloorTransitionModelEntriesFromLabeledData,missing or mismatched cluster uncertainties,centers,%lu,uncertainties,%lu,visitUUID,%{private}@"
- "#altimeter,createGroupedAltimeterData,pointCount,%d,mean,%.2f,uncertainty,%.2f,visitUUID,%{private}@"
- "#altimeter,endEdgeDetection,fallback to event data,time,%.3f,altitude,%.3f,visitUUID,%{private}@"
- "#altimeter,endEdgeDetection,using stored transition end,time,%.3f,altitude,%.3f,visitUUID,%{private}@"
- "#altimeter,endTransition,stableDuration,%.1f,transitionStartTime,%.3f,eventTimestamp,%.3f,visitUUID,%{private}@"
- "#altimeter,enumerate visit elevation profile,timestamp,%f,altitude,%f,uncertainty,%f,visitUUID,%{private}@"
- "#altimeter,processElevationChangeEvent,state,%lu,deltaH,%.3f,deltaT,%.1f,altitude,%.3f,visitUUID,%{private}@"
- "#altimeter,reset state machine,visitUUID,%{private}@"
- "#altimeter,startEdgeDetection,transition start,time,%.3f,altitude,%.3f,visitUUID,%{private}@"
- "#altimeter,startTransition,deltaH,%.3f,altitude,%.3f,timestamp,%.3f,visitUUID,%{private}@"
- "#altimeter,startTransition,determined start,time,%.3f,altitude,%.3f,visitUUID,%{private}@"
- "#altimeter,updateTransition,resetting stable duration,deltaH,%.3f,altitude,%.3f,visitUUID,%{private}@"
- "$!"
- "%@, %@, Found %lu files with unexpected extensions"
- "05:27:32"
- "Invalid parameter not satisfying: address.mergedThoroughfare.length > 0"
- "Jun 12 2026"
- "Skipping IPS log check on customer install"
- "b"
- "\x94"
```
