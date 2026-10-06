## analyticsagent

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3c4` | `0x1c0c` | **`-0xc7b8`** |
| `__TEXT.__oslogstring` | `0xb12` | `0xa6` | **`-0xa6c`** |
| `__TEXT.__auth_stubs` | `0xcf0` | `0x480` | **`-0x870`** |
| `__TEXT.__objc_stubs` | `0x700` | `0x40` | **`-0x6c0`** |
| `__TEXT.__objc_methname` | `0x484` | `0x13` | **`-0x471`** |
| `__DATA_CONST.__const` | `0x4f0` | `0xa8` | **`-0x448`** |
| `__DATA_CONST.__auth_got` | `0x680` | `0x250` | **`-0x430`** |
| `__TEXT.__cstring` | `0x3f9` | `0x99` | **`-0x360`** |
| `__DATA.__data` | `0x3f8` | `0xc8` | **`-0x330`** |
| `__TEXT.__const` | `0x380` | `0x98` | **`-0x2e8`** |
| `__TEXT.__eh_frame` | `0xf0` | `0x378` | **`+0x288`** |
| `__DATA.__objc_data` | `0x248` | `—` | **`-0x248`** |
| `__TEXT.__swift5_typeref` | `0x26a` | `0x4d` | **`-0x21d`** |
| `__DATA.__objc_const` | `0x268` | `0x90` | **`-0x1d8`** |
| `__DATA.__objc_selrefs` | `0x1d8` | `0x10` | **`-0x1c8`** |
| `__DATA.__bss` | `0x1c0` | `—` | **`-0x1c0`** |
| `__TEXT.__constg_swiftt` | `0x22c` | `0x70` | **`-0x1bc`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x20` | **`-0x198`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x138` | **`-0x188`** |
| `__TEXT.__swift5_fieldmd` | `0x168` | `0x20` | **`-0x148`** |
| `__DATA_CONST.__auth_ptr` | `0x148` | `0x28` | **`-0x120`** |
| `__TEXT.__swift5_reflstr` | `0xf6` | `—` | **`-0xf6`** |
| `__TEXT.__objc_classname` | `0xf0` | `0x2b` | **`-0xc5`** |
| `__TEXT.__gcc_except_tab` | `—` | `0xb4` | **`+0xb4`** |
| `__TEXT.__objc_methtype` | `0xb2` | `—` | **`-0xb2`** |
| `__TEXT.__swift5_capture` | `0xb8` | `0x20` | **`-0x98`** |
| `__TEXT.__objc_methlist` | `0x64` | `—` | **`-0x64`** |
| `__DATA.__common` | `0x60` | `0x18` | **`-0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x8` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0x24` | `0x4` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `—` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x10` | `0x4` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-548.0.0.0.0
-  - /System/Library/Frameworks/Accounts.framework/Accounts
+559.0.0.502.1

+  - /System/Library/Frameworks/CoreLocation.framework/CoreLocation

-  - /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices
-  - /System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/BackgroundSystemTasks
-  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary
-  - /System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams
+  - /System/Library/PrivateFrameworks/AnalyticsAgentFramework.framework/AnalyticsAgentFramework

-  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels
+  - /System/Library/PrivateFrameworks/XPCDistributed.framework/XPCDistributed

-  - /usr/lib/swift/libswiftAccelerate.dylib

-  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswiftCoreLocation.dylib

-  - /usr/lib/swift/libswiftMetal.dylib

-  - /usr/lib/swift/libswiftQuartzCore.dylib
-  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

-  - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 199
-  Symbols:   322
-  CStrings:  155
+  Functions: 28
+  Symbols:   97
+  CStrings:  12
Symbols:
+ _$s23AnalyticsAgentFramework0A16XPCEventHandlersC5startyyF
+ _$s23AnalyticsAgentFramework0A16XPCEventHandlersC8xpcQueueSo17OS_dispatch_queueCvg
+ _$s23AnalyticsAgentFramework0A16XPCEventHandlersCACycfC
+ _$s23AnalyticsAgentFramework0A16XPCEventHandlersCMa
+ _$s23AnalyticsAgentFramework15BackgroundTasksV5start5queueySo012OS_dispatch_G0C_tF
+ _$s23AnalyticsAgentFramework15BackgroundTasksVACycfC
+ _$s23AnalyticsAgentFramework15BackgroundTasksVMa
+ _$sScM6sharedScMvgZ
+ _$sScMMa
+ _$sScMScAsWP
+ _$sScMs11GlobalActorsMc
+ __Unwind_Resume
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_exceptionPersonality
+ _exit
+ _swift_deletedAsyncMethodErrorTu
+ _swift_release_x24
- _$s10Foundation22_convertNSErrorToErrorys0E0_pSo0C0CSgF
- _$s10Foundation25NSFastEnumerationIteratorV4nextypSgyF
- _$s10Foundation25NSFastEnumerationIteratorVMa
- _$s10Foundation4DateV17timeIntervalSinceySdACF
- _$s10Foundation4DateV19_bridgeToObjectiveCSo6NSDateCyF
- _$s10Foundation4DateV21timeIntervalSince1970ACSd_tcfC
- _$s10Foundation4DateV21timeIntervalSince1970Sdvg
- _$s10Foundation4DateV36_unconditionallyBridgeFromObjectiveCyACSo6NSDateCSgFZ
- _$s10Foundation4DateVACycfC
- _$s10Foundation4DateVMa
- _$s10Foundation4DateVMn
- _$s10Foundation4DateVs23CustomStringConvertibleAAMc
- _$s10Foundation8TimeZoneV10identifierACSgSSh_tcfC
- _$s10Foundation8TimeZoneV19_bridgeToObjectiveCSo06NSTimeC0CyF
- _$s10Foundation8TimeZoneVMa
- _$s10Foundation8TimeZoneVMn
- _$s16GenerativeModels0aB12AvailabilityV0C0O10restrictedyA2E14RestrictedInfoVcAEmFWC
- _$s16GenerativeModels0aB12AvailabilityV0C0O11unavailableyA2E15UnavailableInfoVcAEmFWC
- _$s16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoV0D6ReasonO11descriptionSSvg
- _$s16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoV0D6ReasonOMa
- _$s16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoV0D6ReasonOSHAAMc
- _$s16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoV7reasonsShyAG0D6ReasonOGvg
- _$s16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoVMa
- _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV0D6ReasonO11descriptionSSvg
- _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV0D6ReasonOMa
- _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV0D6ReasonOSHAAMc
- _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV7reasonsShyAG0D6ReasonOGvg
- _$s16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoVMa
- _$s16GenerativeModels0aB12AvailabilityV0C0O9availableyA2EmFWC
- _$s16GenerativeModels0aB12AvailabilityV0C0OMa
- _$s16GenerativeModels0aB12AvailabilityV10ParametersV17useCaseIdentifier8languageAESS_AC14LanguageOptionOtcfC
- _$s16GenerativeModels0aB12AvailabilityV10ParametersVMa
- _$s16GenerativeModels0aB12AvailabilityV12availabilityAC0C0Ovg
- _$s16GenerativeModels0aB12AvailabilityV14LanguageOptionO3anyyA2EmFWC
- _$s16GenerativeModels0aB12AvailabilityV14LanguageOptionOMa
- _$s16GenerativeModels0aB12AvailabilityV7current10parametersA2C10ParametersV_tFZ
- _$s16GenerativeModels0aB12AvailabilityVMa
- _$s16GenerativeModels0aB12AvailabilityVMn
- _$s16GenerativeModels0aB12AvailabilityVN
- _$s18AppleMediaServices15AccountIdentityV03amsD2IDACSo010AMSAccountE0C_tcfC
- _$s18AppleMediaServices15AccountIdentityVMa
- _$s18AppleMediaServices18AsyncValueSequenceV04makeD8IteratorAC0H0Vyx_GyF
- _$s18AppleMediaServices18AsyncValueSequenceV8IteratorVMn
- _$s18AppleMediaServices18AsyncValueSequenceV8IteratorVyx_GScIAAMc
- _$s18AppleMediaServices18AsyncValueSequenceVMn
- _$s18AppleMediaServices23AccountCachedServerDataC0E5ValueV5valuexSgvg
- _$s18AppleMediaServices23AccountCachedServerDataC0E5ValueVMn
- _$s18AppleMediaServices23AccountCachedServerDataC14stringSequence6forKey9accountIDAA010AsyncValueI0Vys6ResultOyAC0eO0Vy_SSGAC5ErrorOGGAC06StringK0O_AA0D8IdentityVtF
- _$s18AppleMediaServices23AccountCachedServerDataC5ErrorOMa
- _$s18AppleMediaServices23AccountCachedServerDataC5ErrorOMn
- _$s18AppleMediaServices23AccountCachedServerDataC5ErrorOsAdAMc
- _$s18AppleMediaServices23AccountCachedServerDataC6sharedACvgZ
- _$s18AppleMediaServices23AccountCachedServerDataCMa
- _$s18AppleMediaServices23AccountCachedServerDataCMn
- _$s18AppleMediaServices23AccountCachedServerDataCMo
- _$s18AppleMediaServices23AccountCachedServerDataCN
- _$s3XPC0A15_EVENT_KEY_NAMESPys4Int8VGvg
- _$s8Dispatch0A13WorkItemFlagsVMa
- _$s8Dispatch0A13WorkItemFlagsVMn
- _$s8Dispatch0A13WorkItemFlagsVs10SetAlgebraAAMc
- _$s8Dispatch0A3QoSV11unspecifiedACvgZ
- _$s8Dispatch0A3QoSVMa
- _$s8RawValueSYTl
- _$sBOWV
- _$sBi32_WV
- _$sSD10FoundationE19_bridgeToObjectiveCSo12NSDictionaryCyF
- _$sSD10FoundationE36_unconditionallyBridgeFromObjectiveCySDyxq_GSo12NSDictionaryCSgFZ
- _$sSH13_rawHashValue4seedS2i_tFTq
- _$sSH4hash4intoys6HasherVz_tFTq
- _$sSH9hashValueSivgTq
- _$sSHMp
- _$sSHSQTb
- _$sSQ2eeoiySbx_xtFZTq
- _$sSQMp
- _$sSS10FoundationE19_bridgeToObjectiveCSo8NSStringCyF
- _$sSS10FoundationE36_unconditionallyBridgeFromObjectiveCySSSo8NSStringCSgFZ
- _$sSS4hash4intoys6HasherVz_tF
- _$sSS6appendyySSF
- _$sSS8UTF8ViewV13_foreignCountSiyF
- _$sSSN
- _$sSSSHsWP
- _$sSSSysMc
- _$sSY8rawValue03RawB0QzvgTq
- _$sSY8rawValuexSg03RawB0Qz_tcfCTq
- _$sSYMp
- _$sSayxGSTsMc
- _$sSbN
- _$sScI4next7ElementQzSgyYaKFTj
- _$sScI4next7ElementQzSgyYaKFTjTu
- _$sSh11descriptionSSvg
- _$sSo13os_log_type_ta0A0E4infoABvgZ
- _$sSo13os_log_type_ta0A0E7defaultABvgZ
- _$sSo17OS_dispatch_queueC8DispatchE10AttributesVMa
- _$sSo17OS_dispatch_queueC8DispatchE10AttributesVMn
- _$sSo17OS_dispatch_queueC8DispatchE10AttributesVs10SetAlgebraACMc
- _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyO7inherityA2EmFWC
- _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyOMa
- _$sSo17OS_dispatch_queueC8DispatchE5async5group3qos5flags7executeySo0a1_b1_F0CSg_AC0D3QoSVAC0D13WorkItemFlagsVyyXBtF
- _$sSo17OS_dispatch_queueC8DispatchE5label3qos10attributes20autoreleaseFrequency6targetABSS_AC0D3QoSVAbCE10AttributesVAbCE011AutoreleaseI0OABSgtcfC
- _$sSo7NSArrayC10FoundationE12arrayLiteralABypd_tcfC
- _$sSo7NSArrayC10FoundationE12makeIteratorAC017NSFastEnumerationD0VyF
- _$sSqMa
- _$sSy10FoundationE8containsySbqd__SyRd__lF
- _$ss10SetAlgebraPyxqd__ncSTRd__7ElementQyd__ACRtzlufCTj
- _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
- _$ss11_StringGutsV16_foreignCopyUTF84intoSiSgSrys5UInt8VG_tF
- _$ss11_StringGutsVN
- _$ss13_StringObjectV10sharedUTF8SRys5UInt8VGvg
- _$ss15_print_unlockedyyx_q_zts16TextOutputStreamR_r0_lF
- _$ss18_DictionaryStorageC4copy8originalAByxq_Gs05__RawaB0C_tFZ
- _$ss18_DictionaryStorageC6resize8original8capacity4moveAByxq_Gs05__RawaB0C_SiSbtFZ
- _$ss18_DictionaryStorageC8allocate8capacityAByxq_GSi_tFZ
- _$ss18_DictionaryStorageCMn
- _$ss20__StaticArrayStorageCN
- _$ss21_findStringSwitchCase5cases6stringSiSays06StaticB0VG_SStF
- _$ss23CustomStringConvertibleP11descriptionSSvgTj
- _$ss23_ContiguousArrayStorageCMn
- _$ss26DefaultStringInterpolationVN
- _$ss26DefaultStringInterpolationVs16TextOutputStreamsWP
- _$ss27_stringCompareWithSmolCheck__9expectingSbs11_StringGutsV_ADs01_G16ComparisonResultOtF
- _$ss53KEY_TYPE_OF_DICTIONARY_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
- _$ss5ErrorMp
- _$ss5ErrorP10FoundationE20localizedDescriptionSSvg
- _$ss5Int32VMn
- _$ss5Int32VN
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _$ss5UInt8VMn
- _$ss6HasherV5_seedABSi_tcfC
- _$ss6HasherV9_finalizeSiyF
- _$ss6ResultOMn
- _$ss6UInt32VMn
- _$ss6UInt32VN
- _$sypN
- _$sytWV
- _AnalyticsSendEventLazy
- _BiomeLibrary
- _CFAbsoluteTimeGetCurrent
- _NSLocalizedDescriptionKey
- _OBJC_CLASS_$_ACAccountStore
- _OBJC_CLASS_$_BGNonRepeatingSystemTaskRequest
- _OBJC_CLASS_$_BGSystemTaskScheduler
- _OBJC_CLASS_$_BMPublisherOptions
- _OBJC_CLASS_$_NSDateFormatter
- _OBJC_CLASS_$_NSError
- _OBJC_CLASS_$_NSMutableArray
- _OBJC_CLASS_$_NSNumber
- _OBJC_CLASS_$_NSObject
- _OBJC_CLASS_$_NSProcessInfo
- _OBJC_CLASS_$_NSUserDefaults
- _OBJC_CLASS_$_OS_dispatch_queue
- _OBJC_METACLASS_$_NSObject
- _XPC_ACTIVITY_CHECK_IN
- __Block_copy
- __Block_release
- __NSConcreteStackBlock
- __swiftEmptyArrayStorage
- __swiftEmptyDictionarySingleton
- __swiftImmortalRefCount
- __swift_FORCE_LOAD_$_swiftAccelerate
- __swift_FORCE_LOAD_$_swiftCoreAudio
- __swift_FORCE_LOAD_$_swiftMetal
- __swift_FORCE_LOAD_$_swiftQuartzCore
- __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
- __swift_FORCE_LOAD_$_swiftsimd
- _bzero
- _fmod
- _malloc_size
- _memcpy
- _memmove
- _objc_allocWithZone
- _objc_autoreleaseReturnValue
- _objc_msgSendSuper2
- _objc_release
- _objc_release_x1
- _objc_release_x21
- _objc_release_x22
- _objc_release_x23
- _objc_release_x24
- _objc_release_x27
- _objc_release_x28
- _objc_release_x8
- _objc_retain
- _objc_retain_x19
- _objc_retain_x20
- _objc_retain_x21
- _objc_retain_x23
- _objc_retain_x24
- _objc_retain_x26
- _report_locale_prefs_to_analyticsd
- _setObjectForKey
- _swift_allocError
- _swift_arrayDestroy
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_beginAccess
- _swift_bridgeObjectRelease_n
- _swift_bridgeObjectRetain
- _swift_bridgeObjectRetain_n
- _swift_cvw_assignWithCopy
- _swift_cvw_assignWithTake
- _swift_cvw_destroy
- _swift_cvw_initStructMetadataWithLayoutString
- _swift_cvw_initWithCopy
- _swift_cvw_initWithTake
- _swift_cvw_initializeBufferWithCopyOfBuffer
- _swift_dynamicCast
- _swift_endAccess
- _swift_getEnumCaseMultiPayload
- _swift_getEnumTagSinglePayloadGeneric
- _swift_getErrorValue
- _swift_getForeignTypeMetadata
- _swift_getObjCClassMetadata
- _swift_getSingletonMetadata
- _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_getWitnessTable
- _swift_isaMask
- _swift_release_n
- _swift_release_x21
- _swift_release_x23
- _swift_release_x25
- _swift_release_x27
- _swift_retain
- _swift_retain_n
- _swift_retain_x19
- _swift_retain_x2
- _swift_retain_x20
- _swift_retain_x21
- _swift_retain_x24
- _swift_retain_x26
- _swift_setDeallocating
- _swift_storeEnumTagSinglePayloadGeneric
- _swift_willThrow
- _swift_willThrowTypedImpl
- _xpc_activity_register
- _xpc_array_append_value
- _xpc_array_create_empty
- _xpc_dictionary_create_empty
- _xpc_dictionary_get_string
- _xpc_dictionary_set_value
- _xpc_set_event_stream_handler
- _xpc_string_create
CStrings:
+ "Failed to start Analytics Agent: %@"
- ".cxx_destruct"
- "@\"NSDictionary\"8@?0"
- "@16@0:8"
- "ACAccountStore is unavailable."
- "All stops matched and past reporting window, terminating early"
- "App"
- "AppUsageObserver"
- "AppUsageScheduler: BackgroundSystemTasks framework not available on this platform"
- "AppUsageScheduler: Failed to register task handler for %s"
- "AppUsageScheduler: Failed to schedule last-minute task: %s"
- "AppUsageScheduler: Failed to schedule midnight task: %s"
- "AppUsageScheduler: Midnight GMT task triggered - %s at epoch %.*f"
- "AppUsageScheduler: Midnight task completed in %.*f seconds"
- "AppUsageScheduler: Midnight task fired early, scheduling last-minute task for 23:59:00 GMT"
- "AppUsageScheduler: Registering background task handlers"
- "AppUsageScheduler: Scheduling last-minute task - eligible in %.*fs, deadline in %.*fs"
- "AppUsageScheduler: Scheduling midnight task - eligible in %.*fs, deadline in %.*fs"
- "AppUsageScheduler: Successfully registered task handler for %s"
- "AppUsageScheduler: Successfully scheduled last-minute task for 23:59:00 GMT"
- "AppUsageScheduler: Successfully scheduled midnight task"
- "AppUsageScheduler: Task completed in %.*f seconds"
- "AppUsageScheduler: Task triggered - %s"
- "AppUsageSyncTime"
- "AppUsageTelemetry"
- "B16@0:8"
- "Biome classes not available"
- "Capping duration for %{public}s from %.*f to %.*f seconds"
- "Collection completed in %.*f seconds"
- "Duplicate STOP event detected for %{public}s:%d at %{public}f. Previous STOP will be overwritten."
- "Event %{public}s not enabled, skipping %{public}s duration=%u collectedDate=%{public}s"
- "Failed to collect app usage sessions"
- "Failed to query Biome stream: %{public}s"
- "Failed to retrieved app store country: %@"
- "First run - initialized sync time to current time (matching appUsage behavior)"
- "GenerativeModels is available."
- "GenerativeModels is restricted. Reason: %s"
- "GenerativeModels is unavailable. Reason: %s"
- "GenerativeModels returned unknown availability case."
- "GreyMatterAvailable"
- "Handle AppUsage test trigger notification: %s"
- "Handle notification: %s"
- "InFocus"
- "MediaAccountStatus"
- "Orphaned stop: %{public}s at %{public}s"
- "Processed %ld app sessions"
- "RAW DURATION - bundleID=%{public}s raw=%.*fs floor=%u ceil=%u"
- "Reporting window: lastSync=%.*f now=%.*f queryStart=%.*f"
- "Reset sync time to current timestamp"
- "Sent telemetry for %{public}s duration=%u collectedDate=%{public}s"
- "Skipping app usage collection on simulator"
- "Skipping pair for %{public}s with negative duration %.*f"
- "Starting app usage collection"
- "Successfully collected %ld sessions, updated sync time"
- "Successfully queried Biome stream"
- "Successfully retrieved app store country: %s"
- "Unknown completion state"
- "_TtC14analyticsagent17AppUsageScheduler"
- "_TtC14analyticsagent20AnalyticsXPCServices"
- "_TtC14analyticsagent20MediaAccountServices"
- "_TtC14analyticsagent25GenerativeModelsAvailable"
- "absoluteTimestamp"
- "actualCollectedDate"
- "addObject:"
- "ams_accountID"
- "ams_activeiTunesAccount"
- "ams_sharedAccountStore"
- "appStoreCountry"
- "appUsageScheduler"
- "availability"
- "available"
- "bundleID"
- "cancelTaskRequestWithIdentifier:error:"
- "com.apple.Settings.AppleIntelligence"
- "com.apple.analyticsagent.appusage.tasks"
- "com.apple.analyticsagent.midnightlaunch"
- "com.apple.analyticsagent.xpc"
- "com.apple.coreanalytics.AppUsageCollectionTrigger"
- "com.apple.coreanalytics.analyticsagent"
- "com.apple.coreanalytics.appUsage2"
- "com.apple.coreanalytics.appusage.midnight"
- "com.apple.coreanalytics.appusage.sync"
- "com.apple.gms.availability.notification"
- "com.apple.notifyd.matching"
- "countryPolicy"
- "dealloc"
- "displayType"
- "doubleForKey:"
- "dyldPlatform"
- "environment"
- "error"
- "eventBody"
- "exactBundleVersion"
- "exactVersionString"
- "extensionHostID"
- "hasDyldPlatform"
- "hasIsNativeArchitecture"
- "hasStarting"
- "init"
- "initWithBool:"
- "initWithDomain:code:userInfo:"
- "initWithDouble:"
- "initWithIdentifier:"
- "initWithInt:"
- "initWithStartDate:endDate:maxEvents:lastN:reversed:"
- "initWithUnsignedInt:"
- "isNativeArchitecture"
- "lastPathComponent"
- "launchReason"
- "parentBundleID"
- "processInfo"
- "publisherWithUseCase:options:"
- "reasons"
- "registerForTaskWithIdentifier:usingQueue:launchHandler:"
- "restricted"
- "retrieveGenerativeModelsAvailable"
- "setDateFormat:"
- "setDouble:forKey:"
- "setPriority:"
- "setRequiresExternalPower:"
- "setRequiresNetworkConnectivity:"
- "setRequiresUserInactivity:"
- "setScheduleAfter:"
- "setTaskCompleted"
- "setTimeZone:"
- "setTrySchedulingBefore:"
- "sharedScheduler"
- "shortVersionString"
- "sinkWithBookmark:completion:receiveInput:"
- "standardUserDefaults"
- "starting"
- "state"
- "stringFromDate:"
- "submitTaskRequest:error:"
- "taskQueue"
- "type"
- "unavailable"
- "unknown"
- "v16@0:8"
- "v16@?0@\"<OS_xpc_object>\"8"
- "v16@?0@\"BGSystemTask\"8"
- "v16@?0@8"
- "v24@?0@\"BPSCompletion\"8@\"<BMBookmark>\"16"
- "v8@?0"
- "xpcQueue"
```
