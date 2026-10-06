## HeartHealthDaemon

> `/System/Library/PrivateFrameworks/HeartHealthDaemon.framework/HeartHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67ecc` | `0x66c28` | **`-0x12a4`** |
| `__TEXT.__oslogstring` | `0xca8f` | `0xc53e` | **`-0x551`** |
| `__DATA.__bss` | `0x1c0` | `0x4c0` | **`+0x300`** |
| `__TEXT.__objc_methlist` | `0x5104` | `0x4ee4` | **`-0x220`** |
| `__TEXT.__const` | `0x3ca` | `0x5e4` | **`+0x21a`** |
| `__AUTH_CONST.__objc_const` | `0x9c10` | `0x9a28` | **`-0x1e8`** |
| `__AUTH_CONST.__cfstring` | `0x4820` | `0x4680` | **`-0x1a0`** |
| `__DATA.__data` | `0x1d60` | `0x1eb0` | **`+0x150`** |
| `__TEXT.__cstring` | `0x59e2` | `0x5892` | **`-0x150`** |
| `__DATA_CONST.__objc_selrefs` | `0x3610` | `0x3538` | **`-0xd8`** |
| `__AUTH_CONST.__auth_got` | `0x8a0` | `0x960` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x19e0` | `0x1970` | **`-0x70`** |
| `__TEXT.__gcc_except_tab` | `0xb4c` | `0xae4` | **`-0x68`** |
| `__TEXT.__swift5_typeref` | `0x47` | `0x99` | **`+0x52`** |
| `__TEXT.__eh_frame` | `0x78` | `0xc0` | **`+0x48`** |
| `__DATA_CONST.__objc_protolist` | `0x270` | `0x2a8` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x64c` | `0x618` | **`-0x34`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x9c` | `0xc8` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x620` | `0x648` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x17` | `0x3a` | **`+0x23`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x60` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1748` | `0x1728` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x38` | `0x54` | **`+0x1c`** |
| `__AUTH_CONST.__objc_intobj` | `0xdc8` | `0xdb0` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x24` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xee8` | `0xef0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x290` | `0x288` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 2153
-  Symbols:   4123
-  CStrings:  1365
+  Functions: 2145
+  Symbols:   4067
+  CStrings:  1332
Symbols:
+ -[HDHRHypertensionMeasurementAnalyzer sendAnalyticsEventWithDateInterval:additionalPayload:]
+ -[HDHRHypertensionNotificationManager _sendAnalyticsEventWithType:algorithmVersion:]
+ -[HDHRHypertensionNotificationsRescindedAlertManager _sendAnalyticsEventWithType:]
+ -[HDHRIrregularRhythmNotificationsV1FeatureAvailabilityManager _onboardedCountryCodeSupportedStateWithError:]
+ -[HDHeartbeatSeriesFeatureStatusManager initWithDatabase:aFibBurdenFeatureStatusManager:irregularRhythmNotificationsFeatureStatusManager:]
+ GCC_except_table21
+ _HKBloodPressureClassificationCategoryAHASevereHypertension
+ _OBJC_CLASS_$_HDHRHypertensionNotificationsAnalyticsUtilities
+ _OBJC_IVAR_$_HDHeartbeatSeriesFeatureStatusManager._database
+ _OBJC_METACLASS_$_HDHRHypertensionNotificationsAnalyticsUtilities
+ __CATEGORY_HKFeatureAvailabilityRequirementSet_$_HeartHealthDaemon
+ __HDIsUnitTesting
+ __OBJC_$_CLASS_METHODS_HKFeatureAvailabilityRequirementSet(HeartHealthDaemon|HeartHealthDaemon1|HeartHealthDaemon2)
+ __OBJC_$_CLASS_PROP_LIST_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROP_LIST_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_CLASS_METHODS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
+ __OBJC_$_PROTOCOL_REFS_HKFeatureAvailabilityRequirement
+ __OBJC_CLASS_RO_$_HDHRHypertensionNotificationsAnalyticsUtilities
+ __OBJC_LABEL_PROTOCOL_$_HKFeatureAvailabilityRequirement
+ __OBJC_LABEL_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_LABEL_PROTOCOL_$_NSCopying
+ __OBJC_METACLASS_RO_$_HDHRHypertensionNotificationsAnalyticsUtilities
+ __OBJC_PROTOCOL_$_HKFeatureAvailabilityRequirement
+ __OBJC_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_PROTOCOL_$_NSCopying
+ ___104-[HDHRHypertensionNotificationsRescindedAlertManager _unitTesting_callNotificationNotPostedHandlerIfSet]_block_invoke
+ __swiftEmptyArrayStorage
+ _associated conformance So28HKFeatureAvailabilityContextaSHSCSQ
+ _associated conformance So28HKFeatureAvailabilityContextas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So28HKFeatureAvailabilityContextas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _objc_retain_x9
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_bridgeObjectRelease_n
+ _swift_dynamicCastMetatype
+ _swift_dynamicCastObjCProtocolConditional
+ _swift_getExistentialTypeMetadata
+ _swift_getForeignTypeMetadata
+ _swift_getTupleTypeMetadata2
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_release_x19
+ _swift_setDeallocating
+ _symbolic $sSY
+ _symbolic $ss21_ObjectiveCBridgeableP
+ _symbolic SS
+ _symbolic So8NSStringC
+ _symbolic _____ So28HKFeatureAvailabilityContexta
+ _type_layout_string So28HKFeatureAvailabilityContexta
- +[HKFeatureAvailabilityRequirementSet(BPJ) bloodPressureJournalFeatureAvailabilityRequirementSet]
- -[HDHRElectrocardiogramRecordingCommonFeatureAvailabilityManager earliestDateLowestOnboardingVersionCompletedWithError:]
- -[HDHRElectrocardiogramRecordingCommonFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]
- -[HDHRElectrocardiogramRecordingCommonFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]
- -[HDHRElectrocardiogramRecordingCommonFeatureAvailabilityManager onboardedCountryCodeSupportedStateWithError:]
- -[HDHRElectrocardiogramRecordingFeatureAvailabilityManager earliestDateLowestOnboardingVersionCompletedWithError:]
- -[HDHRElectrocardiogramRecordingFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]
- -[HDHRElectrocardiogramRecordingFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]
- -[HDHRElectrocardiogramRecordingFeatureAvailabilityManager onboardedCountryCodeSupportedStateWithError:]
- -[HDHRHealthLiteDataCollector .cxx_destruct]
- -[HDHRHealthLiteDataCollector _queue_createHealthLiteManager]
- -[HDHRHealthLiteDataCollector _queue_handleBradycardiaEventWithDateInterval:threshold:heartRateUUIDs:]
- -[HDHRHealthLiteDataCollector _queue_handleTachycardiaEventWithDateInterval:threshold:heartRateUUIDs:]
- -[HDHRHealthLiteDataCollector _queue_privacyPreferencesDidChange]
- -[HDHRHealthLiteDataCollector _queue_updateAllCollectionTypes]
- -[HDHRHealthLiteDataCollector _queue_updateBradycardiaCollectionType]
- -[HDHRHealthLiteDataCollector _queue_updateTachycardiaCollectionType]
- -[HDHRHealthLiteDataCollector _registerPowerLogEvent:]
- -[HDHRHealthLiteDataCollector beginCollectionForDataAggregator:lastPersistedSensorDatum:]
- -[HDHRHealthLiteDataCollector daemonReady:]
- -[HDHRHealthLiteDataCollector dataAggregator:wantsCollectionWithConfiguration:]
- -[HDHRHealthLiteDataCollector dealloc]
- -[HDHRHealthLiteDataCollector deviceForDataAggregator:]
- -[HDHRHealthLiteDataCollector diagnosticDescription]
- -[HDHRHealthLiteDataCollector identifierForDataAggregator:]
- -[HDHRHealthLiteDataCollector initWithProfile:]
- -[HDHRHealthLiteDataCollector sourceForDataAggregator:]
- -[HDHRHeartRateNotificationsFeatureAvailabilityManager earliestDateLowestOnboardingVersionCompletedWithError:]
- -[HDHRHeartRateNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]
- -[HDHRHeartRateNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]
- -[HDHRHeartRateNotificationsFeatureAvailabilityManager onboardedCountryCodeSupportedStateWithError:]
- -[HDHRHypertensionNotificationsFeatureAvailabilityManager earliestDateLowestOnboardingVersionCompletedWithError:]
- -[HDHRHypertensionNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]
- -[HDHRHypertensionNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]
- -[HDHRHypertensionNotificationsFeatureAvailabilityManager onboardedCountryCodeSupportedStateWithError:]
- -[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager earliestDateLowestOnboardingVersionCompletedWithError:]
- -[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]
- -[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]
- -[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager onboardedCountryCodeSupportedStateWithError:]
- -[HDHRIrregularRhythmNotificationsV1FeatureAvailabilityManager earliestDateLowestOnboardingVersionCompletedWithError:]
- -[HDHRIrregularRhythmNotificationsV1FeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]
- -[HDHRIrregularRhythmNotificationsV1FeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]
- -[HDHRIrregularRhythmNotificationsV1FeatureAvailabilityManager onboardedCountryCodeSupportedStateWithError:]
- -[HDHeartProfileExtension healthLiteDataCollector]
- -[HDHeartProfileExtension setHealthLiteDataCollector:]
- -[HDHeartbeatSeriesFeatureStatusManager initWithProfile:aFibBurdenFeatureStatusManager:irregularRhythmNotificationsFeatureStatusManager:heartNotificationsUserDefaults:]
- GCC_except_table18
- GCC_except_table22
- GCC_except_table26
- GCC_except_table29
- GCC_except_table30
- GCC_except_table34
- _HKBloodPressureClassificationCategoryAHAHypertensiveCrisis
- _HKDataCollectionTypeToString
- _HKIsHeartRateEnabled
- _OBJC_CLASS_$_HDHRHealthLiteDataCollector
- _OBJC_CLASS_$_HDHeartEventSensorDatum
- _OBJC_CLASS_$_HKDataCollectorState
- _OBJC_CLASS_$_HKSource
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._bradycardiaAggregator
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._bradycardiaCollectionConfiguration
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._bradycardiaCollectionState
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._heartRateEnabledInPrivacy
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._localDeviceEntity
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._privacyPreferencesNotificationToken
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._profile
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._queue
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._tachycardiaAggregator
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._tachycardiaCollectionConfiguration
- _OBJC_IVAR_$_HDHRHealthLiteDataCollector._tachycardiaCollectionState
- _OBJC_IVAR_$_HDHeartProfileExtension._healthLiteDataCollector
- _OBJC_IVAR_$_HDHeartbeatSeriesFeatureStatusManager._heartNotificationsUserDefaults
- _OBJC_IVAR_$_HDHeartbeatSeriesFeatureStatusManager._profile
- _OBJC_METACLASS_$_HDHRHealthLiteDataCollector
- _OUTLINED_FUNCTION_8
- __OBJC_$_CATEGORY_CLASS_METHODS_HKFeatureAvailabilityRequirementSet_$_BPJ
- __OBJC_$_CATEGORY_HKFeatureAvailabilityRequirementSet_$_BPJ
- __OBJC_$_INSTANCE_METHODS_HDHRHealthLiteDataCollector
- __OBJC_$_INSTANCE_VARIABLES_HDHRHealthLiteDataCollector
- __OBJC_$_PROP_LIST_HDHRHealthLiteDataCollector
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_HDDataCollector
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HDDataCollector
- __OBJC_$_PROTOCOL_METHOD_TYPES_HDDataCollector
- __OBJC_$_PROTOCOL_REFS_HDDataCollector
- __OBJC_CLASS_PROTOCOLS_$_HDHRHealthLiteDataCollector
- __OBJC_CLASS_RO_$_HDHRHealthLiteDataCollector
- __OBJC_LABEL_PROTOCOL_$_HDDataCollector
- __OBJC_METACLASS_RO_$_HDHRHealthLiteDataCollector
- __OBJC_PROTOCOL_$_HDDataCollector
- __OBJC_PROTOCOL_REFERENCE_$_HDHRHeartNotificationsUserDefaultsProviding
- ___110-[HDHRElectrocardiogramRecordingFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]_block_invoke
- ___110-[HDHRElectrocardiogramRecordingFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]_block_invoke_2
- ___110-[HDHRElectrocardiogramRecordingFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]_block_invoke_3
- ___112-[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]_block_invoke
- ___112-[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]_block_invoke_2
- ___112-[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]_block_invoke_3
- ___38-[HDHRHealthLiteDataCollector dealloc]_block_invoke
- ___43-[HDHRHealthLiteDataCollector daemonReady:]_block_invoke
- ___47-[HDHRHealthLiteDataCollector initWithProfile:]_block_invoke
- ___79-[HDHRHealthLiteDataCollector dataAggregator:wantsCollectionWithConfiguration:]_block_invoke
- ___block_descriptor_56_e8_32s40r48r_e30_v24?0"NSNumber"8"NSError"16lr40l8r48l8s32l8
- _kHKNanoLifestylePrivacyPreferencesChangedNotification
- _kHLPowerLogActionConnected
- _kHLPowerLogActionDisconnected
- _kHLPowerLogActionKey
- _kHLPowerLogActionStartActive
- _kHLPowerLogActionStartPassive
- _kHLPowerLogActionStopUpdates
- _kHLPowerLogBundleIdentifierKey
- _kHLPowerLogEvent
- _kHLPowerLogPIDKey
CStrings:
+ "Initial v2"
+ "Repeat v2"
- "\nHeart enabled in privacy: %@\nTachycardia Collection: %@\nBradycardia Collection: %@"
- "$"
- "%{public}@ persisting bradycardia event with date interval %{public}@"
- "%{public}@ persisting tachycardia event with date interval %{public}@"
- "Error checking onboarded country code supported state for IRN 1.0, returning supported state for 2.0: %{public}@"
- "Error checking onboarded country code supported state for IRN 2.0, returning supported state for 1.0: %{public}@"
- "HDHRHealthLiteDataCollector"
- "HDHRHealthLiteDataCollector.m"
- "Initial"
- "PowerLog %@: %@"
- "Profile extension that provides heart defaults must be installed"
- "Repeat"
- "[%{public}@] Database is inaccessible; can't read ECG onboarding completion"
- "[%{public}@] Error checking onboarded country code supported state for Hypertension Notifications 1.0, returning supported state for 2.0: %{public}@"
- "[%{public}@] Error checking onboarded country code supported state for Hypertension Notifications 2.0, returning supported state for 1.0: %{public}@"
- "[%{public}@] Error reading ECG onboarding completion: %{public}@"
- "[%{public}@] Failed to retrieve lowest onboarding version completed with the 1.0 extension: %{public}@"
- "[%{public}@] Failed to retrieve lowest onboarding version completed with the 2.0 extension: %{public}@"
- "[%{public}@] Predominant feature is IRN"
- "aggregator %{public}@ wants collection with configuration: %{public}@"
- "bradycardia collection transitioning from %{public}@ to %{public}@"
- "bundleid"
- "client_connected"
- "client_disconnected"
- "disabled"
- "enabled"
- "healthlite_event"
- "heart rate collection is disabled due to privacy"
- "heart rate privacy setting changed to %s"
- "pid"
- "profile != nil"
- "start_active"
- "start_passive"
- "stop_updates"
- "tachycardia collection transitioning from %{public}@ to %{public}@"
```
