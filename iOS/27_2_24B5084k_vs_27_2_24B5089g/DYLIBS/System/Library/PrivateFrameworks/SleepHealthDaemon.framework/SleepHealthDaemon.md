## SleepHealthDaemon

> `/System/Library/PrivateFrameworks/SleepHealthDaemon.framework/SleepHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2261c` | `0xc954` | **`-0x15cc8`** |
| `__AUTH_CONST.__auth_got` | `0xaf0` | `0x438` | **`-0x6b8`** |
| `__DATA.__bss` | `0x780` | `0x200` | **`-0x580`** |
| `__TEXT.__const` | `0x800` | `0x298` | **`-0x568`** |
| `__DATA.__data` | `0xc10` | `0x880` | **`-0x390`** |
| `__AUTH.__data` | `0x340` | `—` | **`-0x340`** |
| `__DATA_CONST.__got` | `0x6d0` | `0x3b8` | **`-0x318`** |
| `__TEXT.__unwind_info` | `0x5e8` | `0x2e8` | **`-0x300`** |
| `__TEXT.__eh_frame` | `0x320` | `0x48` | **`-0x2d8`** |
| `__TEXT.__swift5_typeref` | `0x2a2` | `0x51` | **`-0x251`** |
| `__TEXT.__swift5_reflstr` | `0x1bb` | `0x23` | **`-0x198`** |
| `__AUTH_CONST.__const` | `0x210` | `0x88` | **`-0x188`** |
| `__TEXT.__swift5_fieldmd` | `0x180` | `0x1c` | **`-0x164`** |
| `__TEXT.__constg_swiftt` | `0x174` | `0x2c` | **`-0x148`** |
| `__TEXT.__swift5_assocty` | `0x100` | `0x30` | **`-0xd0`** |
| `__TEXT.__oslogstring` | `0x1caa` | `0x1bef` | **`-0xbb`** |
| `__AUTH_CONST.__objc_const` | `0x16a8` | `0x15f0` | **`-0xb8`** |
| `__DATA_DIRTY.__bss` | `0x180` | `0x100` | **`-0x80`** |
| `__TEXT.__cstring` | `0x6b3` | `0x633` | **`-0x80`** |
| `__DATA_DIRTY.__data` | `0x68` | `0xa8` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x30` | `—` | **`-0x30`** |
| `__TEXT.__swift5_proto` | `0x48` | `0x18` | **`-0x30`** |
| `__DATA.__common` | `0x28` | `—` | **`-0x28`** |
| `__TEXT.__swift5_types` | `0x24` | `0x4` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb60` | `0xb48` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x280` | `0x278` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x58` | **`-0x8`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  - /System/Library/PrivateFrameworks/HealthDomains.framework/HealthDomains
-  - /System/Library/PrivateFrameworks/HealthDomainsDaemon.framework/HealthDomainsDaemon

-  - /System/Library/PrivateFrameworks/HealthReport.framework/HealthReport
-  - /System/Library/PrivateFrameworks/HealthTopicsCore.framework/HealthTopicsCore

-  - /usr/lib/swift/libswiftCoreImage.dylib

-  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 479
-  Symbols:   811
-  CStrings:  169
+  Functions: 197
+  Symbols:   697
+  CStrings:  163
Symbols:
- _OBJC_CLASS_$_HDDatabase
- _OBJC_CLASS_$_HDDatabaseTransactionContext
- _OBJC_CLASS_$_HDProfile
- _OBJC_CLASS_$_HKCalendarCache
- _OBJC_CLASS_$_HKUnit
- _OBJC_CLASS_$__TtCs12_SwiftObject
- _OBJC_METACLASS_$__TtCs12_SwiftObject
- __DATA__TtC17SleepHealthDaemon25InMemorySleepSummaryCache
- __IVARS__TtC17SleepHealthDaemon25InMemorySleepSummaryCache
- __METACLASS_DATA__TtC17SleepHealthDaemon25InMemorySleepSummaryCache
- ___chkstk_darwin
- ___swift_allocate_boxed_opaque_existential_1
- ___swift_allocate_value_buffer
- ___swift_closure_destructor
- ___swift_destroy_boxed_opaque_existential_0
- ___swift_memcpy0_1
- ___swift_noop_void_return
- ___swift_project_value_buffer
- __swiftEmptySetSingleton
- __swiftImmortalRefCount
- __swift_FORCE_LOAD_$_swiftCoreImage
- __swift_FORCE_LOAD_$_swiftCoreImage_$_SleepHealthDaemon
- __swift_stdlib_malloc_size
- _associated conformance 17SleepHealthDaemon0A15ScoreClassifierV0B6Report0bfE0AA5ModelAdEP_0B7Domains14Classification
- _associated conformance 17SleepHealthDaemon0A15ScoreClassifierV0B7Domains011MeasurementE0AA6PolicyAdEP_AD014ClassificationH0
- _associated conformance 17SleepHealthDaemon0A15ScoreClassifierV0B7Domains011MeasurementE0AaD0E0
- _associated conformance 17SleepHealthDaemon0A15ScoreClassifierV0B7Domains0E0AA5ModelAdEP_AD14Classification
- _associated conformance 17SleepHealthDaemon0A18DurationClassifierV0E5ErrorOSHAASQ
- _associated conformance 17SleepHealthDaemon0A23ScoreClassificationRuleV0B7Domains011AggregationF0AA0H0AdEP_AD10Aggregator
- _associated conformance 17SleepHealthDaemon0A23ScoreClassificationRuleV0B7Domains011AggregationF0AaD0eF0
- _associated conformance 17SleepHealthDaemon0A23ScoreClassificationRuleV0B7Domains0eF0AA0E0AdEP_AdF
- _associated conformance 17SleepHealthDaemon0A23ScoreClassificationRuleV0B7Domains0eF0AA11MeasurementAdEP_AD15TimeSeriesValue
- _associated conformance 17SleepHealthDaemon0A25ScoreClassificationPolicyV0B7Domains0eF0AA0E0AdEP_AdF
- _associated conformance 17SleepHealthDaemon0A25ScoreClassificationPolicyV0B7Domains0eF0AA11MeasurementAdEP_AD15TimeSeriesValue
- _associated conformance 17SleepHealthDaemon0A26ScoreMeasurementEnumeratorV0B7Domains0eF0AA0E0AdEP_AD15TimeSeriesValue
- _bzero
- _malloc_size
- _memcpy
- _memmove
- _swift_allocBox
- _swift_allocError
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_bridgeObjectRetain_n
- _swift_cvw_assignWithCopy
- _swift_cvw_assignWithTake
- _swift_cvw_destroy
- _swift_cvw_initStructMetadataWithLayoutString
- _swift_cvw_initWithCopy
- _swift_cvw_initWithTake
- _swift_cvw_initializeBufferWithCopyOfBuffer
- _swift_deallocClassInstance
- _swift_deallocObject
- _swift_errorRelease
- _swift_errorRetain
- _swift_getEnumCaseMultiPayload
- _swift_getEnumTagSinglePayloadGeneric
- _swift_getObjectType
- _swift_getOpaqueTypeConformance2
- _swift_getOpaqueTypeMetadata2
- _swift_getSingletonMetadata
- _swift_isUniquelyReferenced_nonNull_native
- _swift_lookUpClassMethod
- _swift_once
- _swift_release
- _swift_release_x21
- _swift_release_x22
- _swift_release_x24
- _swift_release_x25
- _swift_release_x8
- _swift_retain_x19
- _swift_retain_x24
- _swift_retain_x25
- _swift_retain_x28
- _swift_slowAlloc
- _swift_slowDealloc
- _swift_storeEnumTagMultiPayload
- _swift_storeEnumTagSinglePayloadGeneric
- _swift_unknownObjectWeakAssign
- _swift_unknownObjectWeakInit
- _swift_unknownObjectWeakLoadStrong
- _swift_willThrowTypedImpl
- _symbolic $s12HealthReport0aB10ClassifierP
- _symbolic $s13HealthDomains10ClassifierP
- _symbolic $s13HealthDomains15AggregationRuleP
- _symbolic $s13HealthDomains18ClassificationRuleP
- _symbolic $s13HealthDomains20ClassificationPolicyP
- _symbolic $s13HealthDomains21MeasurementClassifierP
- _symbolic $s13HealthDomains21MeasurementEnumeratorP
- _symbolic SNy_____G 9HealthKit8SleepDayV
- _symbolic So9HDProfileC
- _symbolic So9HDProfileCSgXw
- _symbolic _____ 10Foundation4DateV
- _symbolic _____ 10Foundation8CalendarV
- _symbolic _____ 11SleepHealth0A21ScoreAlgorithmVersionO
- _symbolic _____ 13HealthDomains17RawQuantitySampleV
- _symbolic _____ 13HealthDomains20MeasurementSortOrderO
- _symbolic _____ 13HealthDomains24SleepScoreClassificationV
- _symbolic _____ 17SleepHealthDaemon08InMemoryA12SummaryCacheC
- _symbolic _____ 17SleepHealthDaemon0A15ScoreClassifierV
- _symbolic _____ 17SleepHealthDaemon0A18DurationClassifierV
- _symbolic _____ 17SleepHealthDaemon0A18DurationClassifierV0E5ErrorO
- _symbolic _____ 17SleepHealthDaemon0A23ScoreClassificationRuleV
- _symbolic _____ 17SleepHealthDaemon0A25ScoreClassificationPolicyV
- _symbolic _____ 17SleepHealthDaemon0A25ScoreClassificationPolicyV16AccumulatedStateV
- _symbolic _____ 17SleepHealthDaemon0A26ScoreMeasurementEnumeratorV
- _symbolic _____Sg 13HealthDomains23ClassificationFactorSetV
- _symbolic _____Sg 13HealthDomains24SleepScoreClassificationV
- _symbolic _____Sg 17SleepHealthDaemon08InMemoryA12SummaryCacheC
- _symbolic _____Sg 17SleepHealthDaemon0A23ScoreClassificationRuleV
- _symbolic _____ySDySNy_____GSay_____GGG 15Synchronization5MutexVAARi_zrlE 9HealthKit8SleepDayV 0eC00e5ScoreF7SummaryV
- _symbolic _____y_____G 13HealthDomains19RollingMeanQuantityV AA03RawE6SampleV
- _symbolic _____y___________pGIeghn_ s6ResultOsRi_zRi0_zrlE 13HealthDomains28MeasuredSleepClassificationsV s5ErrorP
- _type_layout_string 17SleepHealthDaemon0A15ScoreClassifierV
CStrings:
- "Fatal error"
- "SleepHealthDaemon/SleepScoreMeasurementEnumerator.swift"
- "SleepScoreMeasurementEnumerator_"
- "[%{public}s] Averaged measured sleep duration over %{public}ld summaries with no measured night to date it"
- "[%{public}s] No profile — cannot vend measured sleep classifications"
- "lower upper "
```
