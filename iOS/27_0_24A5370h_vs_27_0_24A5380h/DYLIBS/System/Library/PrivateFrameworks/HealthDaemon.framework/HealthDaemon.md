## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/HealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x956790` | `0x95b22c` | **`+0x4a9c`** |
| `__DATA_DIRTY.__objc_data` | `0x129d0` | `0x14438` | **`+0x1a68`** |
| `__AUTH.__objc_data` | `0xa9d8` | `0x9188` | **`-0x1850`** |
| `__TEXT.__cstring` | `0x83dcc` | `0x84b8d` | **`+0xdc1`** |
| `__DATA_DIRTY.__data` | `0x36b0` | `0x4090` | **`+0x9e0`** |
| `__TEXT.__oslogstring` | `0x488a1` | `0x49110` | **`+0x86f`** |
| `__AUTH_CONST.__cfstring` | `0x3fbe0` | `0x40440` | **`+0x860`** |
| `__AUTH.__data` | `0x2560` | `0x1dc8` | **`-0x798`** |
| `__TEXT.__eh_frame` | `0x76a0` | `0x6fb8` | **`-0x6e8`** |
| `__DATA_DIRTY.__bss` | `0x1b38` | `0x21d8` | **`+0x6a0`** |
| `__DATA.__bss` | `0x8fb8` | `0x8a10` | **`-0x5a8`** |
| `__AUTH_CONST.__const` | `0x17cf0` | `0x18270` | **`+0x580`** |
| `__AUTH_CONST.__objc_const` | `0x83238` | `0x83708` | **`+0x4d0`** |
| `__TEXT.__objc_methlist` | `0x461ec` | `0x46584` | **`+0x398`** |
| `__DATA.__data` | `0x9f38` | `0x9bb8` | **`-0x380`** |
| `__TEXT.__swift5_typeref` | `0x471d` | `0x4a71` | **`+0x354`** |
| `__TEXT.__gcc_except_tab` | `0x395f4` | `0x397f0` | **`+0x1fc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b1f8` | `0x1b3f0` | **`+0x1f8`** |
| `__TEXT.__swift5_fieldmd` | `0x31cc` | `0x338c` | **`+0x1c0`** |
| `__DATA_CONST.__got` | `0x5ba0` | `0x5cf0` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x3108` | `0x3248` | **`+0x140`** |
| `__TEXT.__const` | `0x267d0` | `0x268f0` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x1de60` | `0x1df58` | **`+0xf8`** |
| `__TEXT.__constg_swiftt` | `0x4324` | `0x4410` | **`+0xec`** |
| `__TEXT.__swift5_capture` | `0x2568` | `0x2638` | **`+0xd0`** |
| `__TEXT.__swift_as_cont` | `0x170` | `0xa0` | **`-0xd0`** |
| `__AUTH_CONST.__auth_got` | `0x3ce0` | `0x3d90` | **`+0xb0`** |
| `__TEXT.__swift_as_ret` | `0xdc` | `0x70` | **`-0x6c`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2088` | `0x20e8` | **`+0x60`** |
| `__AUTH_CONST.__objc_intobj` | `0x3f18` | `0x3f78` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x88f0` | `0x8948` | **`+0x58`** |
| `__DATA_DIRTY.__common` | `0x120` | `0x168` | **`+0x48`** |
| `__TEXT.__swift_as_entry` | `0xd0` | `0x88` | **`-0x48`** |
| `__DATA.__common` | `0x2e0` | `0x2a8` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x21678` | `0x21648` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x455c` | `0x4584` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x394` | `0x3b0` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x2c08` | `0x2c18` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d68` | `0x1d70` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0xe4c` | `0xe54` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x5dc` | `0x5e4` | **`+0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 41309
-  Symbols:   59956
-  CStrings:  14196
+  Functions: 41396
+  Symbols:   60105
+  CStrings:  14291
Symbols:
+ +[HDAuthorizationDailyAnalytics _eventDictionaryForSource:records:profileType:timeBoundedAuthEnabled:]
+ +[HDAuthorizationDailyAnalytics _grantRateNumerator:denominator:]
+ +[HDAuthorizationEntity setAuthorizationStatuses:authorizationRequests:authorizationModes:sourceEntity:options:modeInfos:sourceManager:syncIdentityManager:healthDatabase:error:]
+ +[HDKeyValueEntity setTypedValuesWithDictionary:domain:category:profile:error:]
+ +[HDRCacheManagementEntity inputWatermarkForQueryIdentifier:anchorData:rowExists:healthDatabase:error:]
+ +[HDRCacheManagementEntity insertOrUpdateManagementFor:creationDate:updatedDate:inputWatermark:healthDatabase:error:]
+ +[HDRCacheManagementEntity insertOrUpdateManagementForQueryIdentifier:anchorData:creationDate:updatedDate:inputWatermark:healthDatabase:error:]
+ +[HDWorkoutActivityEntity _zoneGroupsForWorkoutActivityWithPersistentId:activityUUID:activityType:database:error:]
+ +[HDWorkoutTrainingLoadQueryHelper workoutEffortAssociationWatermarkBetween:and:database:]
+ +[HDWorkoutUtilities submitRouteSmoothingWorkoutPerformanceAnalyticsWithCoordinator:event:sessionIdentifier:activityType:duration:activityCount:extendedMode:totalLocations:routeSmoothingRetryCount:activityID:failure:isIndoor:]
+ +[HDWorkoutUtilities submitWorkoutPerformanceAnalyticsWithCoordinator:event:sessionIdentifier:activityType:duration:activityCount:failure:isIndoor:]
+ -[HDAnalyticsSubmissionCoordinator(Workout) workout_reportEvent:timestamp:sessionID:activityType:sessionDuration:activityCount:extendedMode:totalLocations:routeSmoothingRetryCount:activityID:failure:isIndoor:]
+ -[HDAuthorizationDailyAnalytics .cxx_destruct]
+ -[HDAuthorizationDailyAnalytics initWithProfile:]
+ -[HDAuthorizationDailyAnalytics reportDailyAnalyticsWithCoordinator:completion:]
+ -[HDAuthorizationManager setAuthorizationStatuses:authorizationModes:forBundleIdentifier:options:modeInfos:completion:]
+ -[HDAuthorizationStoreWriteServer remote_setAuthorizationStatuses:authorizationModes:modeInfos:forBundleIdentifier:options:completion:]
+ -[HDCodableWorkoutSetMetric duration]
+ -[HDCodableWorkoutSetMetric hasDuration]
+ -[HDCodableWorkoutSetMetric hasRepetitionType]
+ -[HDCodableWorkoutSetMetric repetitionType]
+ -[HDCodableWorkoutSetMetric setDuration:]
+ -[HDCodableWorkoutSetMetric setHasDuration:]
+ -[HDCodableWorkoutSetMetric setHasRepetitionType:]
+ -[HDCodableWorkoutSetMetric setRepetitionType:]
+ -[HDCoreAnalyticsSubmissionManager .cxx_destruct]
+ -[HDCoreAnalyticsSubmissionManager _actions]
+ -[HDCoreAnalyticsSubmissionManager _activitySummaryForActivityCacheIndex:error:]
+ -[HDCoreAnalyticsSubmissionManager _countOfObjectsWithSQLQuery:database:error:bindingHandler:]
+ -[HDCoreAnalyticsSubmissionManager _int64ForKeyPrefix:profile:date:error:]
+ -[HDCoreAnalyticsSubmissionManager _manuallyEnteredTypesCountWithTransaction:error:]
+ -[HDCoreAnalyticsSubmissionManager _nonAppleSourcesWithDataSince:transaction:error:]
+ -[HDCoreAnalyticsSubmissionManager _setInt64:keyPrefix:profile:date:error:]
+ -[HDCoreAnalyticsSubmissionManager _updateDeltaToInt64:forKey:profile:currentDate:timeInterval:error:]
+ -[HDCoreAnalyticsSubmissionManager aggregateDatabaseSizeStats:]
+ -[HDCoreAnalyticsSubmissionManager dealloc]
+ -[HDCoreAnalyticsSubmissionManager diagnosticDescription]
+ -[HDCoreAnalyticsSubmissionManager initWithProfile:]
+ -[HDCoreAnalyticsSubmissionManager profileDidBecomeReady:]
+ -[HDCoreAnalyticsSubmissionManager profile]
+ -[HDCoreAnalyticsSubmissionManager reportDailyAnalyticsWithCoordinator:completion:]
+ -[HDCoreAnalyticsSubmissionManager resetTask:]
+ -[HDCoreAnalyticsSubmissionManager runTask:error:]
+ -[HDCoreAnalyticsSubmissionManager setTestHandler:]
+ -[HDCoreAnalyticsSubmissionManager testHandler]
+ -[HDDatabase setUnitTest_databaseCheckoutOptionsHandler:]
+ -[HDDatabase setUnitTest_walCheckpointGuardHandler:]
+ -[HDDatabase setUnitTest_willAcquireWriteLockHandler:]
+ -[HDDatabase unitTest_databaseCheckoutOptionsHandler]
+ -[HDDatabase unitTest_flushConnectionsAndWait]
+ -[HDDatabase unitTest_walCheckpointGuardHandler]
+ -[HDDatabase unitTest_willAcquireWriteLockHandler]
+ -[HDDefaultAuthorizationSchemaProvider setAuthorizationStatuses:authorizationModes:bundleIdentifier:options:modeInfos:profile:completion:]
+ -[HDHealthStoreServer remote_cyclingPowerWorkoutZoneConfigurationWrapperWithCompletion:]
+ -[HDHealthStoreServer remote_setCyclingPowerWorkoutZoneConfigurationWrapper:withCompletion:]
+ -[HDKeyValueDomain setTypedValuesWithDictionary:error:]
+ -[HDPrimaryProfile _newCoreAnalyticsSubmissionManager]
+ -[HDPrimaryProfile coreAnalyticsSubmissionManager]
+ -[HDProfile _newCoreAnalyticsSubmissionManager]
+ -[HDProfile closeObserverTransaction]
+ -[HDProfile coreAnalyticsSubmissionManager]
+ -[HDProfile openObserverTransaction]
+ -[HDQuantitySampleSeriesDataEnumerator initWithTransaction:persistentID:startTime:endTime:sourceID:HFDKey:]
+ -[HDQueryServer _analyticsCacheEntryHits]
+ -[HDQueryServer _analyticsCacheEntryMisses]
+ -[HDQueryUsageDailyAnalytics _eventDictionaryForStats:databaseSizeMB:dataCacheSizeMB:databaseShape:isIHAEnabled:]
+ -[HDQueryUsageDailyAnalytics invalidate]
+ -[HDQueryUsageStatistics cachePersistenceDictionary]
+ -[HDQueryUsageStatistics mergePersistedCacheDictionary:]
+ -[HDQueryUsageStatistics recordQueryWithDuration:boundaryType:dataTypeID:cacheEntryHits:cacheEntryMisses:]
+ -[HDQueryUsageTracker _clearPersistedCacheStatistics]
+ -[HDQueryUsageTracker _flushCacheStatistics]
+ -[HDQueryUsageTracker _loadPersistedCacheStatistics]
+ -[HDQueryUsageTracker _persistenceDomainForProfile:]
+ -[HDQueryUsageTracker _resetForTesting]
+ -[HDQueryUsageTracker _statisticsForQueryTypeForTesting:]
+ -[HDQueryUsageTracker _synchronouslyFlushForTesting]
+ -[HDQueryUsageTracker _waitForPendingPersistenceForTesting]
+ -[HDQueryUsageTracker detachFromProfile:]
+ -[HDQueryUsageTracker recordQueryCompletionForServer:duration:cacheEntryHits:cacheEntryMisses:]
+ -[HDQueryUsageTracker setPersistenceProfile:]
+ -[HDSeriesBuilderServer connectionConfigured]
+ -[HDStatisticsCollectionQueryServer _analyticsCacheEntryHits]
+ -[HDStatisticsCollectionQueryServer _analyticsCacheEntryMisses]
+ -[HDWorkoutBuilderServer isEnding]
+ -[HDWorkoutEffortRelationshipQueryServer _buildRelationshipsForWorkouts:effortDataTypes:options:error:]
+ -[HDWorkoutEffortRelationshipQueryServer _fetchSamplesFromGroupDataIDs:effortDataTypes:limit:error:]
+ -[HDWorkoutManager setUnitTest_beforeRecoveryWorkBlock:]
+ -[HDWorkoutManager unitTest_beforeRecoveryWorkBlock]
+ -[HDWorkoutSessionServer _queue_deleteSessionAndFinishAssociatedBuilderAtDate:]
+ -[HDWorkoutSessionServer unitTest_deleteSessionAndFinishAssociatedBuilderAtDate:]
+ -[HDWorkoutTrainingLoadQueryHelper _populateAndStampCacheForRequestedRange]
+ -[_HDCoreAnalyticsPeriodicAction .cxx_destruct]
+ -[_HDCoreAnalyticsPeriodicAction _queue_setIntervalCounter:]
+ -[_HDCoreAnalyticsPeriodicAction _queue_setLastProcessedDate:]
+ -[_HDCoreAnalyticsPeriodicAction _queue_setLastSubmissionAttemptDate:]
+ -[_HDCoreAnalyticsPeriodicAction _queue_setWaitingToRun:]
+ -[_HDCoreAnalyticsPeriodicAction dealloc]
+ -[_HDCoreAnalyticsPeriodicAction lastProcessedDate]
+ -[_HDCoreAnalyticsPeriodicAction performPeriodicActivity:completion:]
+ -[_HDCoreAnalyticsPeriodicAction periodicActivity:configureXPCActivityCriteria:]
+ -[_HDStatisticsCollectionQueryPendingSeries initWithSeries:anchor:]
+ OBJC_IVAR_$_HDCodableWorkoutSetMetric._duration
+ OBJC_IVAR_$_HDCodableWorkoutSetMetric._repetitionType
+ _HDEnforceFutureMigrationCarryDevicePolicy
+ _HDFutureMigrationCarryDeviceGuardShouldFireTapToRadar
+ _HDFutureMigrationCarryDeviceRemediationCommand
+ _HDTCCShouldRemoveHealthAccessReminderForBundleIdentifier
+ _HDTrailingDailyAverageComponentsAreWholeDays
+ _IDSSendMessageOptionFireAndForgetKey
+ _OBJC_CLASS_$_HDAuthorizationDailyAnalytics
+ _OBJC_CLASS_$_HDCoreAnalyticsSubmissionManager
+ _OBJC_CLASS_$_HDTrailingDailyAverageWindowCalculator
+ _OBJC_CLASS_$_HDTrailingDailyAverageWindowResult
+ _OBJC_CLASS_$_HKCyclingPowerZonesConfigurationWrapper
+ _OBJC_CLASS_$__HDCoreAnalyticsPeriodicAction
+ _OBJC_IVAR_$_HDAuthorizationDailyAnalytics._profile
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._actions
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._fitnessDailyAction
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._fitnessDailyCollectionEnabledNotifyToken
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._profile
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._queue
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._serverConnectionsByComponentId
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._started
+ _OBJC_IVAR_$_HDCoreAnalyticsSubmissionManager._testHandler
+ _OBJC_IVAR_$_HDDatabase._pendingWriteTransactionCount
+ _OBJC_IVAR_$_HDDatabase._unitTest_databaseCheckoutOptionsHandler
+ _OBJC_IVAR_$_HDDatabase._unitTest_walCheckpointGuardHandler
+ _OBJC_IVAR_$_HDDatabase._unitTest_willAcquireWriteLockHandler
+ _OBJC_IVAR_$_HDProfile._authorizationDailyAnalytics
+ _OBJC_IVAR_$_HDProfile._coreAnalyticsSubmissionManager
+ _OBJC_IVAR_$_HDQueryUsageTracker._flushScheduled
+ _OBJC_IVAR_$_HDQueryUsageTracker._persistenceProfile
+ _OBJC_IVAR_$_HDQueryUsageTracker._persistenceQueue
+ _OBJC_IVAR_$_HDWorkoutManager._unitTest_beforeRecoveryWorkBlock
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._block
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._graceInterval
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._intervalCounter
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._intervalCounterKey
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._intervalMultiple
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._lastProcessedDate
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._lastProcessedDateKey
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._lastSubmissionAttemptDate
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._lastSubmissionAttemptKey
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._maximumAttemptCount
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._minimumDelayBetweenAttempts
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._periodicActivity
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._preparedDatabaseAccessibilityAssertion
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._profile
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._queue
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._repeatInterval
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._requiresClassB
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._taskName
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._waitingToRun
+ _OBJC_IVAR_$__HDCoreAnalyticsPeriodicAction._waitingToRunKey
+ _OBJC_METACLASS_$_HDAuthorizationDailyAnalytics
+ _OBJC_METACLASS_$_HDCoreAnalyticsSubmissionManager
+ _OBJC_METACLASS_$_HDTrailingDailyAverageWindowCalculator
+ _OBJC_METACLASS_$_HDTrailingDailyAverageWindowResult
+ _OBJC_METACLASS_$__HDCoreAnalyticsPeriodicAction
+ _RPOptionStatusFlags
+ __AnchorDataForDayIndex
+ __DATA_HDTrailingDailyAverageWindowCalculator
+ __DATA_HDTrailingDailyAverageWindowResult
+ __HDAddMetricDurationAndRepetitionTypeColumnProtected
+ __HDAddMetricDurationAndRepetitionTypeColumnUnprotected
+ __HDAddTrainingLoadCacheInputWatermark
+ __HDDeduplicateTrainingLoadCacheAndAddUniqueIndexes
+ __HDRemoveActiveHeartRateContextMetadata
+ __HDRunCoreAnalyticsFitnessDailyTask
+ __HKStatisticsOptionTrailingDailyAverage
+ __INSTANCE_METHODS_HDTrailingDailyAverageWindowCalculator
+ __INSTANCE_METHODS_HDTrailingDailyAverageWindowResult
+ __IVARS_HDTrailingDailyAverageWindowCalculator
+ __IVARS_HDTrailingDailyAverageWindowResult
+ __METACLASS_DATA_HDTrailingDailyAverageWindowCalculator
+ __METACLASS_DATA_HDTrailingDailyAverageWindowResult
+ __OBJC_$_CLASS_METHODS_HDAuthorizationDailyAnalytics
+ __OBJC_$_CLASS_METHODS_HDWorkoutTrainingLoadQueryHelper
+ __OBJC_$_CLASS_METHODS__TtC12HealthDaemon27HDPreferredWorkoutZoneStore(HealthDaemon|HealthDaemon1)
+ __OBJC_$_INSTANCE_METHODS_HDAuthorizationDailyAnalytics
+ __OBJC_$_INSTANCE_METHODS_HDCoreAnalyticsSubmissionManager
+ __OBJC_$_INSTANCE_METHODS__HDCoreAnalyticsPeriodicAction
+ __OBJC_$_INSTANCE_VARIABLES_HDAuthorizationDailyAnalytics
+ __OBJC_$_INSTANCE_VARIABLES_HDCoreAnalyticsSubmissionManager
+ __OBJC_$_INSTANCE_VARIABLES__HDCoreAnalyticsPeriodicAction
+ __OBJC_$_PROP_LIST_HDAuthorizationDailyAnalytics
+ __OBJC_$_PROP_LIST_HDCoreAnalyticsSubmissionManager
+ __OBJC_$_PROP_LIST__HDCoreAnalyticsPeriodicAction
+ __OBJC_CLASS_PROTOCOLS_$_HDAuthorizationDailyAnalytics
+ __OBJC_CLASS_PROTOCOLS_$_HDCoreAnalyticsSubmissionManager
+ __OBJC_CLASS_PROTOCOLS_$__HDCoreAnalyticsPeriodicAction
+ __OBJC_CLASS_RO_$_HDAuthorizationDailyAnalytics
+ __OBJC_CLASS_RO_$_HDCoreAnalyticsSubmissionManager
+ __OBJC_CLASS_RO_$__HDCoreAnalyticsPeriodicAction
+ __OBJC_METACLASS_RO_$_HDAuthorizationDailyAnalytics
+ __OBJC_METACLASS_RO_$_HDCoreAnalyticsSubmissionManager
+ __OBJC_METACLASS_RO_$__HDCoreAnalyticsPeriodicAction
+ __PROPERTIES_HDTrailingDailyAverageWindowResult
+ __PROPERTIES__TtC12HealthDaemon18HDDataCacheSession
+ ___103+[HDRCacheManagementEntity inputWatermarkForQueryIdentifier:anchorData:rowExists:healthDatabase:error:]_block_invoke
+ ___103+[HDRCacheManagementEntity inputWatermarkForQueryIdentifier:anchorData:rowExists:healthDatabase:error:]_block_invoke_2
+ ___103+[HDRCacheManagementEntity inputWatermarkForQueryIdentifier:anchorData:rowExists:healthDatabase:error:]_block_invoke_3
+ ___103-[HDWorkoutEffortRelationshipQueryServer _buildRelationshipsForWorkouts:effortDataTypes:options:error:]_block_invoke
+ ___117+[HDRCacheManagementEntity insertOrUpdateManagementFor:creationDate:updatedDate:inputWatermark:healthDatabase:error:]_block_invoke
+ ___117+[HDRCacheManagementEntity insertOrUpdateManagementFor:creationDate:updatedDate:inputWatermark:healthDatabase:error:]_block_invoke_2
+ ___119-[HDAuthorizationManager setAuthorizationStatuses:authorizationModes:forBundleIdentifier:options:modeInfos:completion:]_block_invoke
+ ___126-[HDAuthorizationManager _queue_setAuthorizationStatuses:authorizationModes:forBundleIdentifier:options:modeInfos:completion:]_block_invoke
+ ___138-[HDDefaultAuthorizationSchemaProvider setAuthorizationStatuses:authorizationModes:bundleIdentifier:options:modeInfos:profile:completion:]_block_invoke
+ ___138-[HDDefaultAuthorizationSchemaProvider setAuthorizationStatuses:authorizationModes:bundleIdentifier:options:modeInfos:profile:completion:]_block_invoke_2
+ ___143+[HDRCacheManagementEntity insertOrUpdateManagementForQueryIdentifier:anchorData:creationDate:updatedDate:inputWatermark:healthDatabase:error:]_block_invoke
+ ___143+[HDRCacheManagementEntity insertOrUpdateManagementForQueryIdentifier:anchorData:creationDate:updatedDate:inputWatermark:healthDatabase:error:]_block_invoke_2
+ ___177+[HDAuthorizationEntity setAuthorizationStatuses:authorizationRequests:authorizationModes:sourceEntity:options:modeInfos:sourceManager:syncIdentityManager:healthDatabase:error:]_block_invoke
+ ___209-[HDAnalyticsSubmissionCoordinator(Workout) workout_reportEvent:timestamp:sessionID:activityType:sessionDuration:activityCount:extendedMode:totalLocations:routeSmoothingRetryCount:activityID:failure:isIndoor:]_block_invoke
+ ___38-[HDQueryUsageTracker drainStatistics]_block_invoke
+ ___39-[HDQueryUsageTracker _resetForTesting]_block_invoke
+ ___39-[_HDCoreAnalyticsPeriodicAction reset]_block_invoke
+ ___39-[_HDCoreAnalyticsPeriodicAction start]_block_invoke
+ ___41-[HDQueryUsageTracker detachFromProfile:]_block_invoke
+ ___44-[HDCoreAnalyticsSubmissionManager _actions]_block_invoke
+ ___45-[HDQueryUsageTracker setPersistenceProfile:]_block_invoke
+ ___45-[HDSeriesBuilderServer connectionConfigured]_block_invoke
+ ___49-[_HDCoreAnalyticsPeriodicAction intervalCounter]_block_invoke
+ ___51-[_HDCoreAnalyticsPeriodicAction lastProcessedDate]_block_invoke
+ ___52-[HDCoreAnalyticsSubmissionManager initWithProfile:]_block_invoke
+ ___52-[HDQueryUsageTracker _synchronouslyFlushForTesting]_block_invoke
+ ___52-[_HDCoreAnalyticsPeriodicAction _beginWaitingToRun]_block_invoke
+ ___55-[_HDCoreAnalyticsPeriodicAction setLastProcessedDate:]_block_invoke
+ ___56-[_HDCoreAnalyticsPeriodicAction _doIfWaitingWithError:]_block_invoke
+ ___56-[_HDCoreAnalyticsPeriodicAction _doIfWaitingWithError:]_block_invoke_2
+ ___59-[HDQueryUsageTracker _waitForPendingPersistenceForTesting]_block_invoke
+ ___59-[_HDCoreAnalyticsPeriodicAction lastSubmissionAttemptDate]_block_invoke
+ ___60-[HDWorkoutManager _recoverCurrentWorkoutSessionAfterLaunch]_block_invoke_3
+ ___69-[HDWorkoutBuilderServer initWithUUID:configuration:client:delegate:]_block_invoke
+ ___69-[_HDCoreAnalyticsPeriodicAction performPeriodicActivity:completion:]_block_invoke
+ ___75-[HDWorkoutTrainingLoadQueryHelper _populateAndStampCacheForRequestedRange]_block_invoke
+ ___75-[HDWorkoutTrainingLoadQueryHelper _populateAndStampCacheForRequestedRange]_block_invoke_2
+ ___76-[_HDCoreAnalyticsPeriodicAction _runBlockWithAccessibilityAssertion:error:]_block_invoke
+ ___79+[HDKeyValueEntity setTypedValuesWithDictionary:domain:category:profile:error:]_block_invoke
+ ___80-[HDAuthorizationDailyAnalytics reportDailyAnalyticsWithCoordinator:completion:]_block_invoke
+ ___80-[HDCoreAnalyticsSubmissionManager _activitySummaryForActivityCacheIndex:error:]_block_invoke
+ ___81-[HDWorkoutSessionServer unitTest_deleteSessionAndFinishAssociatedBuilderAtDate:]_block_invoke
+ ___83-[HDCoreAnalyticsSubmissionManager reportDailyAnalyticsWithCoordinator:completion:]_block_invoke
+ ___84-[HDAuthorizationManager _queue_resetAuthorizationRecordsForBundleIdentifier:error:]_block_invoke
+ ___84-[HDAuthorizationManager _queue_resetAuthorizationRecordsForBundleIdentifier:error:]_block_invoke_2
+ ___84-[HDAuthorizationManager _queue_resetAuthorizationRecordsForBundleIdentifier:error:]_block_invoke_3
+ ___84-[HDCoreAnalyticsSubmissionManager _manuallyEnteredTypesCountWithTransaction:error:]_block_invoke
+ ___84-[HDCoreAnalyticsSubmissionManager _nonAppleSourcesWithDataSince:transaction:error:]_block_invoke
+ ___85+[HDTrainingLoadStatisticsCacheEntity pruneTrainingLoadForDate:healthDatabase:error:]_block_invoke
+ ___85+[HDTrainingLoadStatisticsCacheEntity pruneTrainingLoadForDate:healthDatabase:error:]_block_invoke_2
+ ___90+[HDWorkoutTrainingLoadQueryHelper workoutEffortAssociationWatermarkBetween:and:database:]_block_invoke
+ ___90+[HDWorkoutTrainingLoadQueryHelper workoutEffortAssociationWatermarkBetween:and:database:]_block_invoke_2
+ ___90+[HDWorkoutTrainingLoadQueryHelper workoutEffortAssociationWatermarkBetween:and:database:]_block_invoke_3
+ ___94-[HDCoreAnalyticsSubmissionManager _countOfObjectsWithSQLQuery:database:error:bindingHandler:]_block_invoke
+ ___95-[HDQueryUsageTracker recordQueryCompletionForServer:duration:cacheEntryHits:cacheEntryMisses:]_block_invoke
+ ___96-[_HDCoreAnalyticsPeriodicAction _doIfWaitingOnMaintenanceQueueWithPeriodicActivity:completion:]_block_invoke
+ ___HDFireFutureMigrationCarryDeviceTapToRadar_block_invoke
+ ___block_descriptor_107_e8_32s40s48s56s_e19_"NSDictionary"8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_128_e8_32s40s48s56s64s72s80s88bs96r104r_e35_B24?0"HDDatabaseTransaction"8^16ls32l8s40l8s48l8s56l8s64l8s72l8s80l8r96l8s88l8r104l8
+ ___block_descriptor_40_e8_32w_e43_B20?0"_HDCoreAnalyticsPeriodicAction"8B16lw32l8
+ ___block_descriptor_48_e8_32s40s_e65_v24?0"HKWorkoutTrainingLoadCollectionQueryResults"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_ea8_32s_e20_v20?0B8"NSError"12ls32l8
+ ___block_descriptor_56_e8_32s40r48r_e35_B24?0"HDDatabaseTransaction"8^16lr40l8s32l8r48l8
+ ___block_descriptor_56_e8_32s40s48w_e35_B24?0"HDDatabaseTransaction"8^16ls32l8s40l8w48l8
+ ___block_descriptor_56_e8_32s_e25_v32?0"NSString"816^B24ls32l8
+ ___block_descriptor_57_ea8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56r_e5_v8?0ls32l8r56l8s40l8s48l8
+ ___block_descriptor_73_e8_32s40s48s_e19_"NSDictionary"8?0ls32l8s40l8s48l8
+ ___swift_closure_destructor.15Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_memcpy112_8
+ _associated conformance 12HealthDaemon31TrailingDailyAverageAggregationOSHAASQ
+ _kHKDatabasePreferencesDomain
+ _kHKDatabasePreferencesKeyEnableFutureMigrations
+ _kHKDatabasePreferencesKeyEnableOntologyFutureMigrations
+ _symbolic $s12HealthDaemon34HDFunctionalThresholdPowerFetchingP
+ _symbolic Say_____G 12HealthDaemon25TrailingDailyAverageDatumV
+ _symbolic Say_____G6basics_Si16totalSampleCounttSg 12HealthDaemon29HDDatabaseDetailDataCollectorC9TypeBasic33_BBE2356FAC7BECE7957402C2CA67DB70LLV
+ _symbolic Say______pG So20HKDataCacheProvidingP
+ _symbolic ShySSG
+ _symbolic So17OS_dispatch_groupC
+ _symbolic So19NSMutableDictionaryCSg___________pSgIeggyg_ So24HDPeriodicActivityResultV s5ErrorP
+ _symbolic So21HDDatabaseTransactionCSay_____G6basics_Si16totalSampleCountt______pIggrzo_ 12HealthDaemon29HDDatabaseDetailDataCollectorC9TypeBasic33_BBE2356FAC7BECE7957402C2CA67DB70LLV s5ErrorP
+ _symbolic So21HDDatabaseTransactionC___________pIggrzo_ 12HealthDaemon29HDDatabaseDetailDataCollectorC15OriginBreakdown33_BBE2356FAC7BECE7957402C2CA67DB70LLV s5ErrorP
+ _symbolic So25_HKDateIntervalCollectionC
+ _symbolic So39HKCyclingPowerZonesConfigurationWrapperCSgSo7NSErrorCSgIeyByy_
+ _symbolic So8NSNumberCSg
+ _symbolic So9HDProfileCSo14HKQuantityTypeCSo17HDSQLitePredicateCSgShySo14HDSourceEntityCGSgSo9_HKFilterCSgSi______pSgIeggggggyo_ So43HDStatisticsCollectionQueryServerDataSourceP
+ _symbolic So9HDProfileCSo14HKQuantityTypeCSo17HDSQLitePredicateCSgShySo14HDSourceEntityCGSgSo9_HKFilterCSgSi______pSgIegnnnnnnr_ So43HDStatisticsCollectionQueryServerDataSourceP
+ _symbolic _____ 12HealthDaemon25TrailingDailyAverageDatumV
+ _symbolic _____ 12HealthDaemon29HDDatabaseDetailDataCollectorC15OriginBreakdown33_BBE2356FAC7BECE7957402C2CA67DB70LLV
+ _symbolic _____ 12HealthDaemon29HDDatabaseDetailDataCollectorC19CollectionCancelledV
+ _symbolic _____ 12HealthDaemon29HDDatabaseDetailDataCollectorC9TypeBasic33_BBE2356FAC7BECE7957402C2CA67DB70LLV
+ _symbolic _____ 12HealthDaemon31TrailingDailyAverageAggregationO
+ _symbolic _____ 12HealthDaemon32TrailingDailyAverageWindowResultV
+ _symbolic _____ 12HealthDaemon36TrailingDailyAverageWindowResultObjCC
+ _symbolic _____ 12HealthDaemon40TrailingDailyAverageWindowCalculatorObjCC
+ _symbolic _____ 8Dispatch0A4TimeV
+ _symbolic _____Sg 12HealthDaemon29HDDatabaseDetailDataCollectorC15OriginBreakdown33_BBE2356FAC7BECE7957402C2CA67DB70LLV
+ _symbolic _____XDXMT 12HealthDaemon32HDDatabaseDetailAnalyticsManagerC
+ _symbolic ______p 12HealthDaemon34HDFunctionalThresholdPowerFetchingP
+ _symbolic ______pSgSo9HDProfileC_So14HKQuantityTypeCSo17HDSQLitePredicateCSgShySo14HDSourceEntityCGSgSo9_HKFilterCSgSitc So43HDStatisticsCollectionQueryServerDataSourceP
+ _symbolic _____ySDyS2SGG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____ySDySSSo11HDAssertionCGG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____ySDySS_____GG 15Synchronization5MutexVAARi_zrlE 12HealthDaemon23HDCommandLineDispatcherC13CommandStruct33_27B5656387D514842E96111DF441E27ELLV
+ _symbolic _____ySDy__________GG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV 12HealthDaemon0F12TypeExecutorC15EvaluationState33_B45338753DA9E0A74AC7F8A078D6F806LLV
+ _symbolic _____ySo63STBackgroundActivitiesStatusDomainBackgroundActivityAttributionCSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon0D19ObservationExecutorC5State33_88CD6C4B3A9A3A40E86CB578E266153FLLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon12StateStorageV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon15DeferralManagerC5State33_AA15BBBF63258AF8D7D53CA14395A031LLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon20RequestedWorkManagerC5State33_F5537C39F29E26CB0CFD6F876447B632LLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon21HDWorkoutZonesBuilderC5StateV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon24HDWorkoutZoneAccumulatorC5StateV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon29SampleObservationStateStorageV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12HealthDaemon30DerivedObservationStateStorageV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 31HealthKitOrchestrationAdditions32ObjectTypeAnchorQueryInputSignalC0C6DaemonE0J8ObserverC5State33_83F6E6B9872C34CA9CD28AFB1F18E2C5LLV
+ _type_layout_string 12HealthDaemon25TrailingDailyAverageDatumV
+ _type_layout_string 12HealthDaemon29HDDatabaseDetailDataCollectorC15OriginBreakdown33_BBE2356FAC7BECE7957402C2CA67DB70LLV
+ _type_layout_string 12HealthDaemon29HDDatabaseDetailDataCollectorC9TypeBasic33_BBE2356FAC7BECE7957402C2CA67DB70LLV
+ _type_layout_string 12HealthDaemon32TrailingDailyAverageWindowResultV
- +[HDAuthorizationEntity setAuthorizationStatuses:authorizationRequests:authorizationModes:sourceEntity:options:modeInfo:sourceManager:syncIdentityManager:healthDatabase:error:]
- +[HDRCacheManagementEntity insertOrUpdateManagementFor:creationDate:updatedDate:healthDatabase:error:]
- +[HDRCacheManagementEntity insertOrUpdateManagementForQueryIdentifier:anchorData:creationDate:updatedDate:healthDatabase:error:]
- +[HDWorkoutActivityEntity _zoneGroupsForWorkoutActivityWithPersistentId:activityUUID:database:error:]
- +[HDWorkoutUtilities submitRouteSmoothingWorkoutPerformanceAnalyticsWithCoordinator:event:sessionIdentifier:activityType:duration:activityCount:extendedMode:totalLocations:routeSmoothingRetryCount:activityID:failure:]
- +[HDWorkoutUtilities submitWorkoutPerformanceAnalyticsWithCoordinator:event:sessionIdentifier:activityType:duration:activityCount:failure:]
- -[HDAWDSubmissionManager .cxx_destruct]
- -[HDAWDSubmissionManager _actions]
- -[HDAWDSubmissionManager _activitySummaryForActivityCacheIndex:error:]
- -[HDAWDSubmissionManager _countOfObjectsWithSQLQuery:database:error:bindingHandler:]
- -[HDAWDSubmissionManager _int64ForKeyPrefix:profile:date:error:]
- -[HDAWDSubmissionManager _manuallyEnteredTypesCountWithTransaction:error:]
- -[HDAWDSubmissionManager _nonAppleSourcesWithDataSince:transaction:error:]
- -[HDAWDSubmissionManager _setInt64:keyPrefix:profile:date:error:]
- -[HDAWDSubmissionManager _updateDeltaToInt64:forKey:profile:currentDate:timeInterval:error:]
- -[HDAWDSubmissionManager aggregateDatabaseSizeStats:]
- -[HDAWDSubmissionManager dealloc]
- -[HDAWDSubmissionManager diagnosticDescription]
- -[HDAWDSubmissionManager initWithProfile:]
- -[HDAWDSubmissionManager profileDidBecomeReady:]
- -[HDAWDSubmissionManager profile]
- -[HDAWDSubmissionManager reportDailyAnalyticsWithCoordinator:completion:]
- -[HDAWDSubmissionManager resetTask:]
- -[HDAWDSubmissionManager runTask:error:]
- -[HDAWDSubmissionManager setTestHandler:]
- -[HDAWDSubmissionManager testHandler]
- -[HDAnalyticsSubmissionCoordinator(Workout) workout_reportEvent:timestamp:sessionID:activityType:sessionDuration:activityCount:extendedMode:totalLocations:routeSmoothingRetryCount:activityID:failure:]
- -[HDAuthorizationManager setAuthorizationStatuses:authorizationModes:forBundleIdentifier:options:modeInfo:completion:]
- -[HDAuthorizationStoreWriteServer remote_setAuthorizationStatuses:authorizationModes:modeInfo:forBundleIdentifier:options:completion:]
- -[HDDefaultAuthorizationSchemaProvider setAuthorizationStatuses:authorizationModes:bundleIdentifier:options:modeInfo:profile:error:]
- -[HDPrimaryProfile _newAWDSubmissionManager]
- -[HDPrimaryProfile awdSubmissionManager]
- -[HDProfile _newAWDSubmissionManager]
- -[HDProfile awdSubmissionManager]
- -[HDQuantitySampleSeriesDataEnumerator initWithTransaction:persistentID:startTime:endTime:HFDKey:]
- -[HDQueryUsageDailyAnalytics _eventDictionaryForStats:databaseSizeMB:databaseShape:isIHAEnabled:]
- -[HDQueryUsageStatistics cacheSizeObservationCount]
- -[HDQueryUsageStatistics recordQueryWithDuration:boundaryType:dataTypeID:cacheEntryHits:cacheEntryMisses:cacheSizeMB:]
- -[HDQueryUsageStatistics totalCacheSizeMB]
- -[HDQueryUsageTracker recordQueryCompletionForServer:duration:cacheEntryHits:cacheEntryMisses:cacheSizeMB:]
- -[HDWorkoutBuilderServer _cancelStatisticsRequeryTimer]
- -[_HDAWDPeriodicAction .cxx_destruct]
- -[_HDAWDPeriodicAction _queue_setIntervalCounter:]
- -[_HDAWDPeriodicAction _queue_setLastProcessedDate:]
- -[_HDAWDPeriodicAction _queue_setLastSubmissionAttemptDate:]
- -[_HDAWDPeriodicAction _queue_setWaitingToRun:]
- -[_HDAWDPeriodicAction dealloc]
- -[_HDAWDPeriodicAction lastProcessedDate]
- -[_HDAWDPeriodicAction performPeriodicActivity:completion:]
- -[_HDAWDPeriodicAction periodicActivity:configureXPCActivityCriteria:]
- GCC_except_table159
- GCC_except_table191
- GCC_except_table238
- _HDAbortIfFutureMigrationsEnabledOnCarryDevice
- _OBJC_CLASS_$_HDAWDSubmissionManager
- _OBJC_CLASS_$__HDAWDPeriodicAction
- _OBJC_IVAR_$_HDAWDSubmissionManager._actions
- _OBJC_IVAR_$_HDAWDSubmissionManager._fitnessDailyAction
- _OBJC_IVAR_$_HDAWDSubmissionManager._fitnessDailyCollectionEnabledNotifyToken
- _OBJC_IVAR_$_HDAWDSubmissionManager._profile
- _OBJC_IVAR_$_HDAWDSubmissionManager._queue
- _OBJC_IVAR_$_HDAWDSubmissionManager._serverConnectionsByComponentId
- _OBJC_IVAR_$_HDAWDSubmissionManager._started
- _OBJC_IVAR_$_HDAWDSubmissionManager._testHandler
- _OBJC_IVAR_$_HDProfile._awdSubmissionManager
- _OBJC_IVAR_$_HDQueryUsageStatistics._cacheSizeObservationCount
- _OBJC_IVAR_$_HDQueryUsageStatistics._totalCacheSizeMB
- _OBJC_IVAR_$__HDAWDPeriodicAction._block
- _OBJC_IVAR_$__HDAWDPeriodicAction._graceInterval
- _OBJC_IVAR_$__HDAWDPeriodicAction._intervalCounter
- _OBJC_IVAR_$__HDAWDPeriodicAction._intervalCounterKey
- _OBJC_IVAR_$__HDAWDPeriodicAction._intervalMultiple
- _OBJC_IVAR_$__HDAWDPeriodicAction._lastProcessedDate
- _OBJC_IVAR_$__HDAWDPeriodicAction._lastProcessedDateKey
- _OBJC_IVAR_$__HDAWDPeriodicAction._lastSubmissionAttemptDate
- _OBJC_IVAR_$__HDAWDPeriodicAction._lastSubmissionAttemptKey
- _OBJC_IVAR_$__HDAWDPeriodicAction._maximumAttemptCount
- _OBJC_IVAR_$__HDAWDPeriodicAction._minimumDelayBetweenAttempts
- _OBJC_IVAR_$__HDAWDPeriodicAction._periodicActivity
- _OBJC_IVAR_$__HDAWDPeriodicAction._preparedDatabaseAccessibilityAssertion
- _OBJC_IVAR_$__HDAWDPeriodicAction._profile
- _OBJC_IVAR_$__HDAWDPeriodicAction._queue
- _OBJC_IVAR_$__HDAWDPeriodicAction._repeatInterval
- _OBJC_IVAR_$__HDAWDPeriodicAction._requiresClassB
- _OBJC_IVAR_$__HDAWDPeriodicAction._taskName
- _OBJC_IVAR_$__HDAWDPeriodicAction._waitingToRun
- _OBJC_IVAR_$__HDAWDPeriodicAction._waitingToRunKey
- _OBJC_METACLASS_$_HDAWDSubmissionManager
- _OBJC_METACLASS_$__HDAWDPeriodicAction
- __DATA__TtC12HealthDaemonP33_E20C92A6CA7FCD1E06F5DCFA3D8FB2CC19NoOpNanoSyncControl
- __HDRunAWDFitnessDailyTask
- __METACLASS_DATA__TtC12HealthDaemonP33_E20C92A6CA7FCD1E06F5DCFA3D8FB2CC19NoOpNanoSyncControl
- __OBJC_$_CLASS_METHODS__TtC12HealthDaemon27HDPreferredWorkoutZoneStore(HealthDaemon)
- __OBJC_$_INSTANCE_METHODS_HDAWDSubmissionManager
- __OBJC_$_INSTANCE_METHODS__HDAWDPeriodicAction
- __OBJC_$_INSTANCE_VARIABLES_HDAWDSubmissionManager
- __OBJC_$_INSTANCE_VARIABLES__HDAWDPeriodicAction
- __OBJC_$_PROP_LIST_HDAWDSubmissionManager
- __OBJC_$_PROP_LIST__HDAWDPeriodicAction
- __OBJC_CLASS_PROTOCOLS_$_HDAWDSubmissionManager
- __OBJC_CLASS_PROTOCOLS_$__HDAWDPeriodicAction
- __OBJC_CLASS_RO_$_HDAWDSubmissionManager
- __OBJC_CLASS_RO_$__HDAWDPeriodicAction
- __OBJC_METACLASS_RO_$_HDAWDSubmissionManager
- __OBJC_METACLASS_RO_$__HDAWDPeriodicAction
- ___102+[HDRCacheManagementEntity insertOrUpdateManagementFor:creationDate:updatedDate:healthDatabase:error:]_block_invoke
- ___102+[HDRCacheManagementEntity insertOrUpdateManagementFor:creationDate:updatedDate:healthDatabase:error:]_block_invoke_2
- ___109-[HDWorkoutEffortRelationshipQueryServer _queue_fetchUpdatedEffortRelationshipsWithAnchor:newAnchor:handler:]_block_invoke
- ___118-[HDAuthorizationManager setAuthorizationStatuses:authorizationModes:forBundleIdentifier:options:modeInfo:completion:]_block_invoke
- ___128+[HDRCacheManagementEntity insertOrUpdateManagementForQueryIdentifier:anchorData:creationDate:updatedDate:healthDatabase:error:]_block_invoke
- ___128+[HDRCacheManagementEntity insertOrUpdateManagementForQueryIdentifier:anchorData:creationDate:updatedDate:healthDatabase:error:]_block_invoke_2
- ___132-[HDDefaultAuthorizationSchemaProvider setAuthorizationStatuses:authorizationModes:bundleIdentifier:options:modeInfo:profile:error:]_block_invoke
- ___132-[HDDefaultAuthorizationSchemaProvider setAuthorizationStatuses:authorizationModes:bundleIdentifier:options:modeInfo:profile:error:]_block_invoke_2
- ___176+[HDAuthorizationEntity setAuthorizationStatuses:authorizationRequests:authorizationModes:sourceEntity:options:modeInfo:sourceManager:syncIdentityManager:healthDatabase:error:]_block_invoke
- ___200-[HDAnalyticsSubmissionCoordinator(Workout) workout_reportEvent:timestamp:sessionID:activityType:sessionDuration:activityCount:extendedMode:totalLocations:routeSmoothingRetryCount:activityID:failure:]_block_invoke
- ___29-[_HDAWDPeriodicAction reset]_block_invoke
- ___29-[_HDAWDPeriodicAction start]_block_invoke
- ___34-[HDAWDSubmissionManager _actions]_block_invoke
- ___39-[_HDAWDPeriodicAction intervalCounter]_block_invoke
- ___41-[_HDAWDPeriodicAction lastProcessedDate]_block_invoke
- ___42-[HDAWDSubmissionManager initWithProfile:]_block_invoke
- ___42-[_HDAWDPeriodicAction _beginWaitingToRun]_block_invoke
- ___45-[_HDAWDPeriodicAction setLastProcessedDate:]_block_invoke
- ___46-[_HDAWDPeriodicAction _doIfWaitingWithError:]_block_invoke
- ___46-[_HDAWDPeriodicAction _doIfWaitingWithError:]_block_invoke_2
- ___49-[_HDAWDPeriodicAction lastSubmissionAttemptDate]_block_invoke
- ___59-[_HDAWDPeriodicAction performPeriodicActivity:completion:]_block_invoke
- ___60-[HDWorkoutBuilderServer _scheduleStatisticsRequeryIfNeeded]_block_invoke
- ___66-[_HDAWDPeriodicAction _runBlockWithAccessibilityAssertion:error:]_block_invoke
- ___68-[HDSeriesBuilderServer initWithUUID:configuration:client:delegate:]_block_invoke
- ___70-[HDAWDSubmissionManager _activitySummaryForActivityCacheIndex:error:]_block_invoke
- ___73-[HDAWDSubmissionManager reportDailyAnalyticsWithCoordinator:completion:]_block_invoke
- ___74-[HDAWDSubmissionManager _manuallyEnteredTypesCountWithTransaction:error:]_block_invoke
- ___74-[HDAWDSubmissionManager _nonAppleSourcesWithDataSince:transaction:error:]_block_invoke
- ___84-[HDAWDSubmissionManager _countOfObjectsWithSQLQuery:database:error:bindingHandler:]_block_invoke
- ___86-[_HDAWDPeriodicAction _doIfWaitingOnMaintenanceQueueWithPeriodicActivity:completion:]_block_invoke
- ___98-[HDWorkoutEffortRelationshipQueryServer _queue_fetchAllEffortRelationshipsWithNewAnchor:handler:]_block_invoke
- ___block_descriptor_106_e8_32s40s48s56s_e19_"NSDictionary"8?0ls32l8s40l8s48l8s56l8
- ___block_descriptor_40_e8_32s_e63_v24?0"_TtC12HealthDaemon21HDWorkoutZonesBuilder"8"NSError"16ls32l8
- ___block_descriptor_40_e8_32w_e33_B20?0"_HDAWDPeriodicAction"8B16lw32l8
- ___block_descriptor_49_ea8_32s40s_e20_v20?0B8"NSError"12ls32l8s40l8
- ___block_descriptor_49_ea8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_65_e8_32s40s48s_e19_"NSDictionary"8?0ls32l8s40l8s48l8
- ___block_descriptor_65_e8_32s40s48s_e35_B24?0"HDDatabaseTransaction"8^16ls32l8s40l8s48l8
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.36Tm
- _abort
- _get_type_metadata 15Synchronization5MutexVy12HealthDaemon0D19ObservationExecutorC5State33_88CD6C4B3A9A3A40E86CB578E266153FLLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy12HealthDaemon15DeferralManagerC5State33_AA15BBBF63258AF8D7D53CA14395A031LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy12HealthDaemon20RequestedWorkManagerC5State33_F5537C39F29E26CB0CFD6F876447B632LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy12HealthDaemon21HDWorkoutZonesBuilderC5StateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy12HealthDaemon24HDWorkoutZoneAccumulatorC5StateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy12HealthDaemon29SampleObservationStateStorageVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy12HealthDaemon30DerivedObservationStateStorageVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy31HealthKitOrchestrationAdditions32ObjectTypeAnchorQueryInputSignalC0C6DaemonE0J8ObserverC5State33_83F6E6B9872C34CA9CD28AFB1F18E2C5LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDV12HealthDaemon0F12TypeExecutorC15EvaluationState33_B45338753DA9E0A74AC7F8A078D6F806LLVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDyS2SGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySS12HealthDaemon23HDCommandLineDispatcherC13CommandStruct33_27B5656387D514842E96111DF441E27ELLVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSo11HDAssertionCGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo63STBackgroundActivitiesStatusDomainBackgroundActivityAttributionCSgG noncopyable
- _get_type_metadata SeRzSERz9HealthKit13ConfigurationO10SampleBaseRz19PredicatedModelKindAC13WithPredicatePQzRs_r0_l15Synchronization5MutexVy0A6Daemon12StateStorageVG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic $s12HealthDaemon39HDCyclingPowerZoneConfigurationProviderP
- _symbolic SaySay______pG_SiSgtG So20HKDataCacheProvidingP
- _symbolic SaySay______pG_SiSgtGz_Xx So20HKDataCacheProvidingP
- _symbolic Say_____GSg 12HealthDaemon25HDDatabaseDetailTypeStatsV
- _symbolic So12NSDictionaryCSg
- _symbolic So21HDDatabaseTransactionCSay_____G______pIggrzo_ 12HealthDaemon25HDDatabaseDetailTypeStatsV s5ErrorP
- _symbolic _____ 12HealthDaemon19NoOpNanoSyncControl33_E20C92A6CA7FCD1E06F5DCFA3D8FB2CCLLC
- _symbolic _____SgSo7NSErrorCSgIeyByy_ 12HealthDaemon21HDWorkoutZonesBuilderC
- _symbolic ______p 12HealthDaemon39HDCyclingPowerZoneConfigurationProviderP
CStrings:
+ " && "
+ "%@: Failed to write zone builder recovery state: %@"
+ "%{public}@: Failed to get PID for workout %{public}@: %{public}@"
+ "%{public}@: Failed to read associated builder configuration while finishing session: %{public}@"
+ "%{public}@: Not finishing associated builder %{public}@: client is present and builder is actively saving (isEnding=YES)."
+ "A trailing daily average configuration is required when using the trailing daily average option."
+ "ALTER TABLE r_cache_management ADD COLUMN input_watermark INTEGER"
+ "ALTER TABLE workout_builder_set_me ADD COLUMN duration REAL"
+ "ALTER TABLE workout_builder_set_me ADD COLUMN rep_type INTEGER NOT NULL DEFAULT 2"
+ "ALTER TABLE workout_set_me ADD COLUMN duration REAL"
+ "ALTER TABLE workout_set_me ADD COLUMN rep_type INTEGER NOT NULL DEFAULT 2"
+ "Authorization reset transaction rolled back for %{private}@: %{public}@"
+ "Authorization schema provider missing required selector"
+ "B20@?0@\"_HDCoreAnalyticsPeriodicAction\"8B16"
+ "CREATE UNIQUE INDEX training_load_stats_total_unique_idx ON training_load_statistics_cache (start_date, end_date) WHERE activity_type IS NULL"
+ "CREATE UNIQUE INDEX training_load_stats_type_unique_idx ON training_load_statistics_cache (start_date, end_date, activity_type) WHERE activity_type IS NOT NULL"
+ "Could not open carry-device Future Migrations Tap-to-Radar URL: %{public}@"
+ "Cycling power zones configuration unexpectedly nil"
+ "CyclingPowerZonesConfiguration"
+ "DELETE FROM %@ WHERE %@ < ?"
+ "DELETE FROM metadata_values WHERE key_id = (SELECT rowid FROM metadata_keys WHERE key = '_HKPrivateHeartRateContext') AND value_type = 1 AND numerical_value = 12"
+ "DELETE FROM r_cache_management WHERE query_identifier = 'trainingLoadCacheBackfill'"
+ "DELETE FROM training_load_statistics_cache WHERE ROWID NOT IN (SELECT MAX(ROWID) FROM training_load_statistics_cache GROUP BY start_date, end_date, IFNULL(activity_type, -1))"
+ "DROP INDEX IF EXISTS training_load_stats_idx"
+ "DROP INDEX IF EXISTS training_load_stats_type_idx"
+ "Failed to read post-write authorization records for %{private}@: %{public}@"
+ "Future Migrations enabled on a carry device (flags=0x%lx); refusing to honor them. To re-allow normal startup run: %{public}@ (or disable the Livability Carry toggle)."
+ "HDAuthorizationDailyAnalytics.m"
+ "HDCoreAnalyticsSubmissionManager.m"
+ "HDFutureMigrationCarryDeviceGuardTapToRadarCount"
+ "HDFutureMigrationCarryDeviceGuardTapToRadarDay"
+ "HDQueryUsageTracker.m"
+ "HealthDaemon.TrailingDailyAverageWindowCalculatorObjC"
+ "HealthDaemon.TrailingDailyAverageWindowResultObjC"
+ "INSERT OR REPLACE INTO %@ (%@, %@, %@, %@, %@) VALUES (?, ?, ?, ?, ?)"
+ "No smoothed route series for this workout; nothing to smooth, completing as a no-op"
+ "Refreshed automatic FTP"
+ "SELECT %@ FROM %@ WHERE %@ = ? AND %@ = ? LIMIT 1"
+ "SELECT %@, %@, %@, %@                            FROM %@                           WHERE %@ >= ? AND %@ < ? AND %@ IS NULL ORDER BY %@ ASC"
+ "SELECT %@, %@, %@, %@, %@                            FROM %@                           WHERE %@ >= ? AND %@ < ? AND %@ IS NOT NULL ORDER BY %@ ASC"
+ "SELECT MAX(a.ROWID) FROM %@ a INNER JOIN %@ wo ON a.%@ = wo.data_id INNER JOIN %@ s ON s.data_id = wo.data_id WHERE s.%@ >= ? AND s.%@ < ? AND a.%@ = ? AND a.%@ = 0"
+ "SELECT SUM(CASE WHEN p.origin_product_type LIKE 'iPhone%' THEN 1 ELSE 0 END) AS iphone_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'iPad%' THEN 1 ELSE 0 END) AS ipad_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'Watch%' THEN 1 ELSE 0 END) AS watch_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'AirPods%'\n                  OR p.origin_product_type LIKE 'AudioAccessory%'\n                  OR p.origin_product_type LIKE 'iProd%' THEN 1 ELSE 0 END) AS airpods_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'RealityDevice%' THEN 1 ELSE 0 END) AS vision_count,\n       COUNT(*) AS total\nFROM samples AS s\nINNER JOIN objects AS o ON o.data_id = s.data_id\nINNER JOIN data_provenances AS p ON o.provenance = p.ROWID\nWHERE s.data_type = ?"
+ "SELECT p.source_id AS source_id,\n       p.origin_product_type AS origin_product_type,\n       COUNT(*) AS cnt\nFROM samples AS s\nINNER JOIN objects AS o ON o.data_id = s.data_id\nINNER JOIN data_provenances AS p ON o.provenance = p.ROWID\nWHERE s.data_type = ?\nGROUP BY p.source_id, p.origin_product_type"
+ "SELECT src.ROWID AS source_id, ls.bundle_id AS bundle_id\nFROM sources AS src\nINNER JOIN logical_sources AS ls ON src.logical_source_id = ls.ROWID"
+ "Skipping post-merge availability notification: success=%{BOOL}d, error=%{public}@"
+ "The trailing daily average option currently requires daily (1 day) interval components."
+ "The trailing daily average option does not support separating statistics by source."
+ "The trailing daily average option requires HKStatisticsCollectionQuery."
+ "The trailing daily average option supports only discrete-arithmetic and cumulative quantity types."
+ "The trailing daily average window length must be a positive whole number of days."
+ "Updated cycling power zones configuration"
+ "[%s] Failed to save batch of %ld caches at anchor: %s with err: %@."
+ "[%s] Unsupported configurationType: %{public}s"
+ "[%{public}s] Collection exceeded %{public}fs budget; skipping this cycle"
+ "[CyclingPowerZones] Apple FTP fetch returned a sample but also reported error: %{public}s"
+ "[CyclingPowerZones] Apple FTP unchanged since last fetch, skipping write-back"
+ "[CyclingPowerZones] Cannot decode stored configuration, will create automatic empty: %{public}s"
+ "[CyclingPowerZones] Failed to fetch most recent Apple FTP: %{public}s"
+ "[CyclingPowerZones] Failed to persist refreshed automatic FTP: %{public}s"
+ "[CyclingPowerZones] Fetched most recent Apple FTP — creationDate: %{public}s"
+ "[CyclingPowerZones] No Apple-Watch FTP sample available"
+ "[CyclingPowerZones] No stored configuration and no Apple-Watch FTP yet, returning automatic-empty without persisting"
+ "[CyclingPowerZones] No stored configuration found"
+ "[CyclingPowerZones] Saved configuration to KVD: %{public}ld bytes — reason: %{public}s"
+ "[CyclingPowerZones] Stored configuration's automatic FTP is fresh, returning as-is"
+ "[CyclingPowerZones] XPC: cyclingPowerWorkoutZoneConfigurationWrapper requested"
+ "[CyclingPowerZones] XPC: setCyclingPowerWorkoutZoneConfiguration received nil configuration in wrapper"
+ "[CyclingPowerZones] XPC: setCyclingPowerWorkoutZoneConfiguration requested"
+ "[HDQueryUsageTracker] Failed to clear persisted cache stats: %{public}@"
+ "[HDQueryUsageTracker] Failed to load persisted cache stats: %{public}@"
+ "[HDQueryUsageTracker] Failed to persist cache stats: %{public}@"
+ "[HDTrainingLoadChangeManager] Failed to prune training load cache: %{public}s"
+ "activity_type IS NOT NULL"
+ "activity_type IS NULL"
+ "authorizedReadTypeCount"
+ "authorizedWriteTypeCount"
+ "cacheHitQueryCount"
+ "cacheMissQueryCount"
+ "characteristicReadTypeCount"
+ "com.apple.healthd.authorization"
+ "com.apple.healthd.cache-session.save"
+ "com.apple.healthd.query.usage.cache"
+ "com.apple.healthd.query.usage.persistence"
+ "defaults delete %@ %@"
+ "fullReadTypeCount"
+ "healthd detected Future Migrations enabled on a Livability Carry Device (flags=0x%lx) and refused to honor them to keep the database openable. This device should not have Future Migrations enabled. To clear only the offending defaults, run:\n\n    %@\n\nAlternatively, turn off the Livability Carry toggle."
+ "healthd: Future Migrations enabled on a carry device"
+ "hrContextSwitchCountPer5MinWindow0"
+ "hrContextSwitchCountPer5MinWindow1"
+ "hrContextSwitchCountPer5MinWindow10Plus"
+ "hrContextSwitchCountPer5MinWindow2"
+ "hrContextSwitchCountPer5MinWindow3"
+ "hrContextSwitchCountPer5MinWindow4"
+ "hrContextSwitchCountPer5MinWindow5"
+ "hrContextSwitchCountPer5MinWindow6"
+ "hrContextSwitchCountPer5MinWindow7"
+ "hrContextSwitchCountPer5MinWindow8"
+ "hrContextSwitchCountPer5MinWindow9"
+ "hrContextSwitchCountPer5MinWindowNone"
+ "input_watermark"
+ "isAuthorizedToRead"
+ "isAuthorizedToReadAll"
+ "isAuthorizedToWrite"
+ "isAuthorizedToWriteAll"
+ "isCharacteristicTypesOnly"
+ "isFirstPartyApp"
+ "isIndoor"
+ "isRequestingRead"
+ "isRequestingWrite"
+ "isThirdPartyApp"
+ "limitedReadRate"
+ "limitedReadTypeCount"
+ "modeInfos != nil"
+ "readGrantRate"
+ "repetitionType"
+ "requestedReadTypeCount"
+ "requestedWriteTypeCount"
+ "setTypedValuesWithDictionary: unsupported value class %@ for key %@"
+ "sourceID productType count "
+ "stats"
+ "totalCacheEntryHits"
+ "totalCacheEntryMisses"
+ "totalCacheHitQueryDuration"
+ "totalCacheMissQueryDuration"
+ "training_load_stats_total_unique_idx"
+ "training_load_stats_type_unique_idx"
+ "writeGrantRate"
+ "\xf01"
+ "\xf0\xb1"
- "%{public}@: Failed to get persisted id for workout: %{public}@, %{public}@"
- ")\nGROUP BY s.data_type"
- ")\nGROUP BY s.data_type, ls.bundle_id, p.origin_product_type"
- "B20@?0@\"_HDAWDPeriodicAction\"8B16"
- "Cannot complete smoothing without smoothed route series identifier"
- "FATAL: Cannot enable Future Migrations on a carry device (flags=0x%lx). Clear com.apple.healthd defaults or disable the Livability Carry toggle."
- "Failed to get records for %{private}@ setting authorizations %{public}@"
- "HDAWDSubmissionManager.m"
- "HDWorkoutBatchLocationSmoother"
- "No smoothed route series identifier"
- "SELECT %@, %@, %@, %@                            FROM %@                           WHERE %@ = ? AND %@ = ? AND %@ IS NULL"
- "SELECT %@, %@, %@, %@, %@                            FROM %@                           WHERE %@ = ? AND %@= ? AND %@ IS NOT NULL"
- "SELECT s.data_type AS data_type,\n       ls.bundle_id AS bundle_id,\n       p.origin_product_type AS origin_product_type,\n       COUNT(*) AS cnt\nFROM samples AS s\nINNER JOIN objects AS o ON o.data_id = s.data_id\nINNER JOIN data_provenances AS p ON o.provenance = p.ROWID\nINNER JOIN sources AS src ON p.source_id = src.ROWID\nINNER JOIN logical_sources AS ls ON src.logical_source_id = ls.ROWID\nWHERE s.data_type IN ("
- "SELECT s.data_type,\n       SUM(CASE WHEN p.origin_product_type LIKE 'iPhone%' THEN 1 ELSE 0 END) AS iphone_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'iPad%' THEN 1 ELSE 0 END) AS ipad_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'Watch%' THEN 1 ELSE 0 END) AS watch_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'AirPods%'\n                  OR p.origin_product_type LIKE 'AudioAccessory%'\n                  OR p.origin_product_type LIKE 'iProd%' THEN 1 ELSE 0 END) AS airpods_count,\n       SUM(CASE WHEN p.origin_product_type LIKE 'RealityDevice%' THEN 1 ELSE 0 END) AS vision_count,\n       COUNT(*) AS total\nFROM samples AS s\nINNER JOIN objects AS o ON o.data_id = s.data_id\nINNER JOIN data_provenances AS p ON o.provenance = p.ROWID\nWHERE s.data_type IN ("
- "[%s] Failed to save %ld cache data at anchor: %s with err: %@."
- "[%s] Unsupported configurationType: %s"
- "firstParty thirdParty "
- "hr_context_switch_count_per_5min_window_0"
- "hr_context_switch_count_per_5min_window_1"
- "hr_context_switch_count_per_5min_window_10_plus"
- "hr_context_switch_count_per_5min_window_2"
- "hr_context_switch_count_per_5min_window_3"
- "hr_context_switch_count_per_5min_window_4"
- "hr_context_switch_count_per_5min_window_5"
- "hr_context_switch_count_per_5min_window_6"
- "hr_context_switch_count_per_5min_window_7"
- "hr_context_switch_count_per_5min_window_8"
- "hr_context_switch_count_per_5min_window_9"
- "hr_context_switch_count_per_5min_window_none"
- "training_load_stats_idx"
- "training_load_stats_type_idx"
- "v24@?0@\"_TtC12HealthDaemon21HDWorkoutZonesBuilder\"8@\"NSError\"16"
- "\xf0\xa1"
- "\xf0\xf0\xb1"
```
