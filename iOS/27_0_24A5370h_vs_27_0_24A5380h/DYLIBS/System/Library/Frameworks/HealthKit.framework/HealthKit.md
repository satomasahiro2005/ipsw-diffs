## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x152b9c` | `0x158b3c` | **`+0x5fa0`** |
| `__TEXT.__text` | `0x3f31f0` | `0x3f61dc` | **`+0x2fec`** |
| `__DATA.__bss` | `0x31530` | `0x32370` | **`+0xe40`** |
| `__TEXT.__oslogstring` | `0xdcb3` | `0xd683` | **`-0x630`** |
| `__AUTH_CONST.__objc_const` | `0x530e0` | `0x53468` | **`+0x388`** |
| `__TEXT.__objc_methlist` | `0x31534` | `0x31744` | **`+0x210`** |
| `__TEXT.__unwind_info` | `0x13200` | `0x133b8` | **`+0x1b8`** |
| `__AUTH_CONST.__const` | `0x13bd1` | `0x13d81` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x78e8` | `0x7a30` | **`+0x148`** |
| `__DATA_CONST.__got` | `0x1d08` | `0x1e18` | **`+0x110`** |
| `__DATA.__data` | `0xfcb0` | `0xfda0` | **`+0xf0`** |
| `__DATA_DIRTY.__data` | `0x1e8` | `0x2d8` | **`+0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x2648` | `0x2738` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x5240` | `0x5314` | **`+0xd4`** |
| `__AUTH_CONST.__cfstring` | `0x33480` | `0x33540` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x5600` | `0x569c` | **`+0x9c`** |
| `__DATA_CONST.__objc_selrefs` | `0x11f98` | `0x12020` | **`+0x88`** |
| `__TEXT.__swift5_proto` | `0x18d0` | `0x1954` | **`+0x84`** |
| `__AUTH.__objc_data` | `0xf258` | `0xf2c8` | **`+0x70`** |
| `__DATA_DIRTY.__bss` | `0xcd8` | `0xd30` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x5223` | `0x5275` | **`+0x52`** |
| `__TEXT.__cstring` | `0x37ad2` | `0x37b12` | **`+0x40`** |
| `__AUTH.__data` | `0x34b8` | `0x34e8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x10448` | `0x10468` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x369b` | `0x36bb` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2f60` | `0x2f7c` | **`+0x1c`** |
| `__TEXT.__swift5_capture` | `0xef0` | `0xed4` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x2040` | `0x2028` | **`-0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x46b0` | `0x4698` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x1bb8` | `0x1bd0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x720` | `0x738` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x1798` | `0x17a8` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1c4` | `0x1b4` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x33c` | `0x348` | **`+0xc`** |
| `__TEXT.__gcc_except_tab` | `0x3f28` | `0x3f24` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0xc8` | `0xc4` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x1b0` | `0x1ac` | **`-0x4`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 29449
-  Symbols:   35699
-  CStrings:  9173
+  Functions: 29622
+  Symbols:   35787
+  CStrings:  9160
Symbols:
+ +[HKAppleIntelligenceUtilities shared]
+ +[HKHeartRateVariabilityUtilities _isHRVType:]
+ +[HKHeartRateVariabilityUtilities deleteHRVSamplesOfType:fromStartDate:endDate:predicate:options:healthStore:completion:]
+ +[HKTrailingDailyAverageConfiguration supportsSecureCoding]
+ -[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfos:forBundleIdentifier:options:completion:]
+ -[HKHealthStore cyclingPowerWorkoutZoneConfigurationWrapperWithCompletion:]
+ -[HKHealthStore setCyclingPowerWorkoutZoneConfigurationWrapper:withCompletion:]
+ -[HKHealthStoreImplementation cyclingPowerWorkoutZoneConfigurationWrapperWithCompletion:]
+ -[HKHealthStoreImplementation setCyclingPowerWorkoutZoneConfigurationWrapper:withCompletion:]
+ -[HKMCMenopauseModel sampleForDayIndex:]
+ -[HKStatistics _setTrailingDailyAverageQuantity:]
+ -[HKStatistics daysWithDataCount]
+ -[HKStatistics setDaysWithDataCount:]
+ -[HKStatisticsCollectionQuery setTrailingDailyAverageConfiguration:]
+ -[HKStatisticsCollectionQuery trailingDailyAverageConfiguration]
+ -[HKTrailingDailyAverageConfiguration .cxx_destruct]
+ -[HKTrailingDailyAverageConfiguration copyWithZone:]
+ -[HKTrailingDailyAverageConfiguration encodeWithCoder:]
+ -[HKTrailingDailyAverageConfiguration hash]
+ -[HKTrailingDailyAverageConfiguration initWithCoder:]
+ -[HKTrailingDailyAverageConfiguration initWithWindowLength:minimumDaysWithData:]
+ -[HKTrailingDailyAverageConfiguration isEqual:]
+ -[HKTrailingDailyAverageConfiguration minimumDaysWithData]
+ -[HKTrailingDailyAverageConfiguration windowLength]
+ -[_HKStatisticsCollectionQueryServerConfiguration setTrailingDailyAverageConfiguration:]
+ -[_HKStatisticsCollectionQueryServerConfiguration trailingDailyAverageConfiguration]
+ -[_HKWorkoutRouteLoadingContext .cxx_destruct]
+ -[_HKWorkoutRouteLoadingContext completion]
+ -[_HKWorkoutRouteLoadingContext init]
+ -[_HKWorkoutRouteLoadingContext locationsByUUID]
+ -[_HKWorkoutRouteLoadingContext orderedLocations]
+ -[_HKWorkoutRouteLoadingContext orderedSamples]
+ -[_HKWorkoutRouteLoadingContext remainingCount]
+ -[_HKWorkoutRouteLoadingContext setCompletion:]
+ -[_HKWorkoutRouteLoadingContext setLocationsByUUID:]
+ -[_HKWorkoutRouteLoadingContext setOrderedSamples:]
+ -[_HKWorkoutRouteLoadingContext setRemainingCount:]
+ -[_HKWorkoutRouteStore _fetchAllLocationsFromSeriesSample:context:]
+ -[_HKWorkoutRouteStore _queue_setLocations:forUUID:context:]
+ _OBJC_CLASS_$_HKAppleIntelligenceUtilities
+ _OBJC_CLASS_$_HKCyclingPowerZonesConfigurationWrapper
+ _OBJC_CLASS_$_HKTrailingDailyAverageConfiguration
+ _OBJC_CLASS_$__HKWorkoutRouteLoadingContext
+ _OBJC_IVAR_$_HKStatistics._daysWithDataCount
+ _OBJC_IVAR_$_HKStatisticsCollectionQuery._trailingDailyAverageConfiguration
+ _OBJC_IVAR_$_HKTrailingDailyAverageConfiguration._minimumDaysWithData
+ _OBJC_IVAR_$_HKTrailingDailyAverageConfiguration._windowLength
+ _OBJC_IVAR_$__HKStatisticsCollectionQueryServerConfiguration._trailingDailyAverageConfiguration
+ _OBJC_IVAR_$__HKWorkoutRouteLoadingContext._completion
+ _OBJC_IVAR_$__HKWorkoutRouteLoadingContext._locationsByUUID
+ _OBJC_IVAR_$__HKWorkoutRouteLoadingContext._orderedSamples
+ _OBJC_IVAR_$__HKWorkoutRouteLoadingContext._remainingCount
+ _OBJC_IVAR_$__HKWorkoutRouteStore._currentLoadingContext
+ _OBJC_METACLASS_$_HKAppleIntelligenceUtilities
+ _OBJC_METACLASS_$_HKCyclingPowerZonesConfigurationWrapper
+ _OBJC_METACLASS_$_HKTrailingDailyAverageConfiguration
+ _OBJC_METACLASS_$__HKWorkoutRouteLoadingContext
+ __CLASS_METHODS_HKCyclingPowerZonesConfigurationWrapper
+ __CLASS_PROPERTIES_HKCyclingPowerZonesConfigurationWrapper
+ __DATA_HKCyclingPowerZonesConfigurationWrapper
+ __HKStatisticsOptionTrailingDailyAverage
+ __INSTANCE_METHODS_HKCyclingPowerZonesConfigurationWrapper
+ __IVARS_HKCyclingPowerZonesConfigurationWrapper
+ __METACLASS_DATA_HKCyclingPowerZonesConfigurationWrapper
+ __OBJC_$_CLASS_METHODS_HKAppleIntelligenceUtilities
+ __OBJC_$_CLASS_METHODS_HKTrailingDailyAverageConfiguration
+ __OBJC_$_CLASS_PROP_LIST_HKTrailingDailyAverageConfiguration
+ __OBJC_$_INSTANCE_METHODS_HKTrailingDailyAverageConfiguration
+ __OBJC_$_INSTANCE_METHODS__HKWorkoutRouteLoadingContext
+ __OBJC_$_INSTANCE_VARIABLES_HKTrailingDailyAverageConfiguration
+ __OBJC_$_INSTANCE_VARIABLES__HKWorkoutRouteLoadingContext
+ __OBJC_$_PROP_LIST_HKTrailingDailyAverageConfiguration
+ __OBJC_$_PROP_LIST__HKWorkoutRouteLoadingContext
+ __OBJC_CLASS_PROTOCOLS_$_HKTrailingDailyAverageConfiguration
+ __OBJC_CLASS_RO_$_HKAppleIntelligenceUtilities
+ __OBJC_CLASS_RO_$_HKTrailingDailyAverageConfiguration
+ __OBJC_CLASS_RO_$__HKWorkoutRouteLoadingContext
+ __OBJC_METACLASS_RO_$_HKAppleIntelligenceUtilities
+ __OBJC_METACLASS_RO_$_HKTrailingDailyAverageConfiguration
+ __OBJC_METACLASS_RO_$__HKWorkoutRouteLoadingContext
+ __PROTOCOLS_HKCyclingPowerZonesConfigurationWrapper
+ ___117-[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfos:forBundleIdentifier:options:completion:]_block_invoke
+ ___117-[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfos:forBundleIdentifier:options:completion:]_block_invoke_2
+ ___117-[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfos:forBundleIdentifier:options:completion:]_block_invoke_3
+ ___121+[HKHeartRateVariabilityUtilities deleteHRVSamplesOfType:fromStartDate:endDate:predicate:options:healthStore:completion:]_block_invoke
+ ___56-[_HKWorkoutRouteStore fetchAllLocationsWithCompletion:]_block_invoke
+ ___56-[_HKWorkoutRouteStore fetchAllLocationsWithCompletion:]_block_invoke_2
+ ___67-[_HKWorkoutRouteStore _fetchAllLocationsFromSeriesSample:context:]_block_invoke
+ ___68-[HKStatisticsCollectionQuery setTrailingDailyAverageConfiguration:]_block_invoke
+ ___89-[HKHealthStoreImplementation cyclingPowerWorkoutZoneConfigurationWrapperWithCompletion:]_block_invoke
+ ___89-[HKHealthStoreImplementation cyclingPowerWorkoutZoneConfigurationWrapperWithCompletion:]_block_invoke_2
+ ___89-[HKHealthStoreImplementation cyclingPowerWorkoutZoneConfigurationWrapperWithCompletion:]_block_invoke_3
+ ___93-[HKHealthStoreImplementation setCyclingPowerWorkoutZoneConfigurationWrapper:withCompletion:]_block_invoke
+ ___93-[HKHealthStoreImplementation setCyclingPowerWorkoutZoneConfigurationWrapper:withCompletion:]_block_invoke_2
+ ___93-[HKHealthStoreImplementation setCyclingPowerWorkoutZoneConfigurationWrapper:withCompletion:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e61_v24?0"HKCyclingPowerZonesConfigurationWrapper"8"NSError"16ls32l8
+ ___block_descriptor_64_e8_32s40s48s56s_e56_v36?0"HKWorkoutRouteQuery"8"NSArray"16B24"NSError"28ls32l8s40l8s48l8s56l8
+ ___block_descriptor_88_e8_32s40s48s56s64bs_e23_v28?0B8Q12"NSError"20ls64l8s32l8s40l8s48l8s56l8
+ ___swift_closure_destructor.11Tm
+ _associated conformance 9HealthKit27ClassificationConfigurationV10CodingKeys33_C671526B9F61015261EE413755C6C835LLOSHAASQ
+ _associated conformance 9HealthKit27ClassificationConfigurationV10CodingKeys33_C671526B9F61015261EE413755C6C835LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 9HealthKit27ClassificationConfigurationV10CodingKeys33_C671526B9F61015261EE413755C6C835LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9HealthKit38ClassificationObservationConfigurationV10CodingKeys33_79116D2FDA55F68C452D789F58F3BB3DLLOSHAASQ
+ _associated conformance 9HealthKit38ClassificationObservationConfigurationV10CodingKeys33_79116D2FDA55F68C452D789F58F3BB3DLLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 9HealthKit38ClassificationObservationConfigurationV10CodingKeys33_79116D2FDA55F68C452D789F58F3BB3DLLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9HealthKit9QueryTypeO10CodingKeys33_C671526B9F61015261EE413755C6C835LLOSHAASQ
+ _associated conformance 9HealthKit9QueryTypeO10CodingKeys33_C671526B9F61015261EE413755C6C835LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 9HealthKit9QueryTypeO10CodingKeys33_C671526B9F61015261EE413755C6C835LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9HealthKit9QueryTypeO13AllCodingKeys33_C671526B9F61015261EE413755C6C835LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 9HealthKit9QueryTypeO13AllCodingKeys33_C671526B9F61015261EE413755C6C835LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9HealthKit9QueryTypeO16LatestCodingKeys33_C671526B9F61015261EE413755C6C835LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 9HealthKit9QueryTypeO16LatestCodingKeys33_C671526B9F61015261EE413755C6C835LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9HealthKit9QueryTypeOSHAASQ
+ _symbolic $s9HealthKit13ConfigurationO12WithCalendarP
+ _symbolic $s9HealthKit13ConfigurationO13WithQueryTypeP
+ _symbolic SNy_____GSg 10Foundation4DateV
+ _symbolic _____ 9HealthKit27ClassificationConfigurationV
+ _symbolic _____ 9HealthKit27ClassificationConfigurationV10CodingKeys33_C671526B9F61015261EE413755C6C835LLO
+ _symbolic _____ 9HealthKit38ClassificationObservationConfigurationV
+ _symbolic _____ 9HealthKit38ClassificationObservationConfigurationV10CodingKeys33_79116D2FDA55F68C452D789F58F3BB3DLLO
+ _symbolic _____ 9HealthKit9QueryTypeO
+ _symbolic _____ 9HealthKit9QueryTypeO10CodingKeys33_C671526B9F61015261EE413755C6C835LLO
+ _symbolic _____ 9HealthKit9QueryTypeO13AllCodingKeys33_C671526B9F61015261EE413755C6C835LLO
+ _symbolic _____ 9HealthKit9QueryTypeO16LatestCodingKeys33_C671526B9F61015261EE413755C6C835LLO
+ _symbolic _____y9ModelKind_____QzSg______pGIeghg_ s6ResultOsRi_zRi0_zrlE 9HealthKit0B4TypeP s5ErrorP
+ _symbolic _____y9ModelKind_____QzSg______pGIeghn_ s6ResultOsRi_zRi0_zrlE 9HealthKit0B4TypeP s5ErrorP
+ _symbolic _____ySayxGG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 9HealthKit24ClientEvaluationExecutorC5State33_110D0FF4273B356E1EE076D7C880D620LLV
- +[HKHeartRateVariabilityUtilities _hrvType]
- +[HKHeartRateVariabilityUtilities deleteHRVSamplesFromStartDate:endDate:predicate:options:healthStore:completion:]
- -[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfo:forBundleIdentifier:options:completion:]
- -[_HKWorkoutRouteStore _fetchAllLocationsFromSeriesSample:]
- -[_HKWorkoutRouteStore _queue_checkAndReturnIfLocationsLoaded]
- -[_HKWorkoutRouteStore _queue_locations]
- -[_HKWorkoutRouteStore _setLocations:forUUID:]
- _OBJC_IVAR_$__HKWorkoutRouteStore._loadingCompletionBlock
- _OBJC_IVAR_$__HKWorkoutRouteStore._loadingCount
- _OBJC_IVAR_$__HKWorkoutRouteStore._locations
- __DATA__TtC9HealthKit31HKFunctionalThresholdPowerStore
- __IVARS__TtC9HealthKit31HKFunctionalThresholdPowerStore
- __METACLASS_DATA__TtC9HealthKit31HKFunctionalThresholdPowerStore
- ___114+[HKHeartRateVariabilityUtilities deleteHRVSamplesFromStartDate:endDate:predicate:options:healthStore:completion:]_block_invoke
- ___116-[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfo:forBundleIdentifier:options:completion:]_block_invoke
- ___116-[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfo:forBundleIdentifier:options:completion:]_block_invoke_2
- ___116-[HKAuthorizationStore setAuthorizationStatuses:authorizationModes:modeInfo:forBundleIdentifier:options:completion:]_block_invoke_3
- ___40-[_HKWorkoutRouteStore _queue_locations]_block_invoke
- ___46-[_HKWorkoutRouteStore _setLocations:forUUID:]_block_invoke
- ___59-[_HKWorkoutRouteStore _fetchAllLocationsFromSeriesSample:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e56_v36?0"HKWorkoutRouteQuery"8"NSArray"16B24"NSError"28ls32l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56bs_e23_v28?0B8Q12"NSError"20ls56l8s32l8s40l8s48l8
- ___swift_closure_destructor.13Tm
- _get_type_metadata 15Synchronization5MutexVy9HealthKit24ClientEvaluationExecutorC5State33_110D0FF4273B356E1EE076D7C880D620LLVG noncopyable
- _get_type_metadata s8SendableRzl15Synchronization5MutexVySayxGG noncopyable
- _swift_retain_x9
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic $s9HealthKit39HKFunctionalThresholdPowerStoreProtocolP
- _symbolic $s9HealthKit45HKPreferredWorkoutZoneKeyValueStorageProtocolP
- _symbolic $s9HealthKit45HKPreferredWorkoutZoneNanoSyncControlProtocolP
- _symbolic ScCy__________G 9HealthKit32HKCyclingPowerZonesConfigurationV s5NeverO
- _symbolic _____ 9HealthKit27HKPreferredWorkoutZoneStoreV
- _symbolic _____ 9HealthKit31HKFunctionalThresholdPowerStoreC
- _symbolic _____Ieghn_ 9HealthKit32HKCyclingPowerZonesConfigurationV
- _symbolic _____SgIeghn_ 9HealthKit33HKCyclingPowerFunctionalThresholdV
- _symbolic _____XDXMT 9HealthKit31HKFunctionalThresholdPowerStoreC
- _symbolic ______p 9HealthKit39HKFunctionalThresholdPowerStoreProtocolP
- _symbolic ______p 9HealthKit45HKPreferredWorkoutZoneKeyValueStorageProtocolP
- _symbolic ______p 9HealthKit45HKPreferredWorkoutZoneNanoSyncControlProtocolP
- _type_layout_string 9HealthKit27HKPreferredWorkoutZoneStoreV
CStrings:
+ "Classifications"
+ "Cycling power zones configuration unexpectedly nil"
+ "Should only delete HRV sample types"
+ "daysWithDataCount"
+ "lower upper "
+ "minimumDaysWithData"
+ "modeInfos != nil"
+ "trailingDailyAverageConfiguration"
+ "v24@?0@\"HKCyclingPowerZonesConfigurationWrapper\"8@\"NSError\"16"
+ "windowLength"
- "%s Cannot decode CyclingPowerZonesConfiguration, creating automatic configuration, error: %@"
- "%s Cannot fetch most recent Apple FTP quantity sample, error: %@"
- "%s Cannot save CyclingPowerZonesConfiguration to valueStore, error: %@"
- "%s Current automatic FTP is available and less then %ld days old (fetchDate: %s, now: %s, daysBack: %ld, defaultsOverride: %{bool}d), skip fetching most recent Apple FTP, current: %s"
- "%s Cycling power zone configuration has been nano synced."
- "%s Failed to nano sync the cycling power zone configuration."
- "%s Failed to nano sync the cycling power zone configuration: %@"
- "%s Fetched CyclingPowerZonesConfiguration from valueStore, no data found, creating automatic configuration"
- "%s Fetched most recent Apple FTP: %s"
- "%s Fetching most recent Apple FTP, current automatic FTP is available: %{bool}d, (fetchDate: %s, now: %s, daysBack: %ld, defaultsOverride: %{bool}d)"
- "%s Fetching most recent Apple FTP, executed healthStore query, thread: %@"
- "%s Fetching most recent Apple FTP, executing healthStore query, thread: %@"
- "%s Most recent Apple FTP is available, updated with appleFTP: %s, configuration: %s"
- "%s Most recent Apple FTP is not available, updated with emptyFTP: %s, configuration: %s"
- "%s Most recent Apple FTP quantity sample is not available"
- "%s Saved CyclingPowerZonesConfiguration to valueStore, data: %ld bytes"
- "%s Saving CyclingPowerZonesConfiguration to valueStore"
- "CyclingPowerZonesConfiguration"
- "CyclingPowerZonesDoNotFetchAutomaticFTPDaysBack"
- "HKPreferredWorkoutZoneStore"
- "HealthKit/Locale+HealthKit.swift"
- "[CyclingPowerZones] Fetching most recent Apple FTP"
- "createCyclingPowerZonesConfigurationFromAppleFTP(configuration:)"
```
