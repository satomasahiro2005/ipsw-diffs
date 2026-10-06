## HealthPlatformFoundation

> `/System/Library/PrivateFrameworks/HealthPlatformFoundation.framework/HealthPlatformFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3322c` | `0x42c88` | **`+0xfa5c`** |
| `__TEXT.__eh_frame` | `0xeb0` | `0x1b9c` | **`+0xcec`** |
| `__DATA.__bss` | `0x2980` | `0x3080` | **`+0x700`** |
| `__TEXT.__const` | `0x1ff0` | `0x2690` | **`+0x6a0`** |
| `__TEXT.__unwind_info` | `0xd68` | `0x1198` | **`+0x430`** |
| `__AUTH_CONST.__const` | `0x1288` | `0x1648` | **`+0x3c0`** |
| `__AUTH.__data` | `0x800` | `0xb10` | **`+0x310`** |
| `__TEXT.__oslogstring` | `0x518` | `0x828` | **`+0x310`** |
| `__AUTH_CONST.__objc_const` | `0x700` | `0x940` | **`+0x240`** |
| `__AUTH_CONST.__auth_got` | `0x870` | `0xa70` | **`+0x200`** |
| `__TEXT.__constg_swiftt` | `0xb2c` | `0xd28` | **`+0x1fc`** |
| `__TEXT.__swift5_typeref` | `0x907` | `0xadb` | **`+0x1d4`** |
| `__TEXT.__cstring` | `0x392` | `0x563` | **`+0x1d1`** |
| `__TEXT.__swift5_fieldmd` | `0x99c` | `0xb6c` | **`+0x1d0`** |
| `__DATA.__data` | `0x910` | `0xac8` | **`+0x1b8`** |
| `__TEXT.__swift5_reflstr` | `0x650` | `0x790` | **`+0x140`** |
| `__DATA_CONST.__got` | `0x298` | `0x358` | **`+0xc0`** |
| `__TEXT.__swift_as_cont` | `0x6c` | `0xe4` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x54` | `0xbc` | **`+0x68`** |
| `__TEXT.__swift_as_ret` | `0x30` | `0x94` | **`+0x64`** |
| `__AUTH.__objc_data` | `0x130` | `0x180` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x88` | `0xd8` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0x38` | `0x88` | **`+0x50`** |
| `__TEXT.__swift5_proto` | `0x188` | `0x1cc` | **`+0x44`** |
| `__DATA.__common` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x78` | `0xa0` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0xc8` | `0xe8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x4a8` | `0x4b8` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x40` | `0x4c` | **`+0xc`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /System/Library/Frameworks/CoreLocation.framework/CoreLocation

+  - /System/Library/Frameworks/_LocationEssentials.framework/_LocationEssentials

+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 1170
-  Symbols:   415
-  CStrings:  57
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 1445
+  Symbols:   506
+  CStrings:  82
Symbols:
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_CLLocation
+ _OBJC_CLASS_$_CLLocationManager
+ _OBJC_CLASS_$_HKKeyValueDomain
+ _OBJC_CLASS_$_NSUserDefaults
+ _OBJC_CLASS_$__CLPlaceInference
+ __Block_copy
+ __Block_release
+ __DATA__TtC24HealthPlatformFoundation18LocationPrefetcher
+ __DATA__TtC24HealthPlatformFoundation19LiveLocationFetcher
+ __DATA__TtC24HealthPlatformFoundation26ArbiterCollectionAssertion
+ __IVARS__TtC24HealthPlatformFoundation18LocationPrefetcher
+ __IVARS__TtC24HealthPlatformFoundation19LiveLocationFetcher
+ __IVARS__TtC24HealthPlatformFoundation26ArbiterCollectionAssertion
+ __METACLASS_DATA__TtC24HealthPlatformFoundation18LocationPrefetcher
+ __METACLASS_DATA__TtC24HealthPlatformFoundation19LiveLocationFetcher
+ __METACLASS_DATA__TtC24HealthPlatformFoundation26ArbiterCollectionAssertion
+ __NSConcreteStackBlock
+ ___swift__destructor
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ ___swift_memcpy17_8
+ ___swift_memcpy40_8
+ ___swift_project_boxed_opaque_existential_1Tm
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_HealthPlatformFoundation
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_HealthPlatformFoundation
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_HealthPlatformFoundation
+ __swift_stdlib_bridgeErrorToNSError
+ _associated conformance 24HealthPlatformFoundation14PlaceInferenceV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLOSHAASQ
+ _associated conformance 24HealthPlatformFoundation14PlaceInferenceV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 24HealthPlatformFoundation14PlaceInferenceV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 24HealthPlatformFoundation15CurrentLocationV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLOSHAASQ
+ _associated conformance 24HealthPlatformFoundation15CurrentLocationV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 24HealthPlatformFoundation15CurrentLocationV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLOs0F3KeyAAs28CustomDebugStringConvertible
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _get_enum_tag_for_layout_string 24HealthPlatformFoundation18LocationFetchErrorO
+ _get_type_metadata 15Synchronization5MutexVyyyYbcSgG noncopyable
+ _objc_release_x28
+ _objc_retain_x24
+ _objc_retain_x25
+ _objc_retain_x27
+ _os_variant_has_internal_diagnostics
+ _swift_bridgeObjectRelease_n
+ _swift_cvw_enumFn_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_getFunctionTypeMetadata0
+ _swift_release_n
+ _swift_release_x26
+ _swift_retain_n
+ _swift_retain_x2
+ _swift_retain_x27
+ _swift_runtimeSupportsNoncopyableTypes
+ _swift_storeEnumTagMultiPayload
+ _swift_task_create
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s24HealthPlatformFoundation15LocationCachingP
+ _symbolic $s24HealthPlatformFoundation16LocationFetchingP
+ _symbolic $s24HealthPlatformFoundation23PrefetchedLocationCacheV6DomainP
+ _symbolic Iegh_
+ _symbolic SDy_____SSG 10Foundation4UUIDV
+ _symbolic ScA_pSg
+ _symbolic ScCy_____y__________G_____G s6ResultOsRi_zRi0_zrlE 24HealthPlatformFoundation14PlaceInferenceV AC18LocationFetchErrorO s5NeverO
+ _symbolic So17CLLocationManagerCSg
+ _symbolic _____ 24HealthPlatformFoundation14PlaceInferenceV
+ _symbolic _____ 24HealthPlatformFoundation14PlaceInferenceV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLO
+ _symbolic _____ 24HealthPlatformFoundation15CurrentLocationV
+ _symbolic _____ 24HealthPlatformFoundation15CurrentLocationV10CodingKeys33_87A14ED305622850EA6B211BC3E6DC6ALLO
+ _symbolic _____ 24HealthPlatformFoundation18LocationFetchErrorO
+ _symbolic _____ 24HealthPlatformFoundation18LocationPrefetcherC
+ _symbolic _____ 24HealthPlatformFoundation19LiveLocationFetcherC
+ _symbolic _____ 24HealthPlatformFoundation23PrefetchedLocationCacheV
+ _symbolic _____ 24HealthPlatformFoundation26ArbiterCollectionAssertionC
+ _symbolic _____ s5Int32V
+ _symbolic _____Sg 24HealthPlatformFoundation14PlaceInferenceV
+ _symbolic _____SgIeAgHr_ 24HealthPlatformFoundation15CurrentLocationV
+ _symbolic _____SgXw 24HealthPlatformFoundation7ArbiterC
+ _symbolic _____SgXwz_Xx 24HealthPlatformFoundation7ArbiterC
+ _symbolic ______p 24HealthPlatformFoundation15LocationCachingP
+ _symbolic ______p 24HealthPlatformFoundation16LocationFetchingP
+ _symbolic ______p 24HealthPlatformFoundation23PrefetchedLocationCacheV6DomainP
+ _symbolic _____ySo10CLLocationCGSg 9HealthKit10CodableBoxV
+ _symbolic _____ySo17_CLPlaceInferenceCG 9HealthKit10CodableBoxV
+ _type_layout_string 24HealthPlatformFoundation18LocationFetchErrorO
+ _type_layout_string 24HealthPlatformFoundation23PrefetchedLocationCacheV
- ___swift_destroy_boxed_opaque_existential_1Tm
- _associated conformance 24HealthPlatformFoundation7ArbiterC15ArbitrationMode33_59979E65C723FFDBC5095B9FF47CA8A3LLOSHAASQ
- _symbolic _____ 24HealthPlatformFoundation7ArbiterC15ArbitrationMode33_59979E65C723FFDBC5095B9FF47CA8A3LLO
CStrings:
+ "ArbiterCollectionAssertion("
+ "Failed to read cached location: %@"
+ "Failed to save denied status: %@"
+ "Failed to save prefetched location: %@"
+ "HKArbiterDebugSnapshotEnabled"
+ "HealthPlatformFoundation/LocationFetching.swift"
+ "Held collection assertions: "
+ "Location not authorized (status=%{public}d)"
+ "LocationPrefetcher"
+ "Only reduced-accuracy location is available"
+ "Place inference unavailable: %{public}@, falling back to liveUpdates"
+ "PrefetchedLocation"
+ "Saved prefetched location (liveUpdates fallback)"
+ "Saved prefetched location (place inference)"
+ "[%s] Collection assertion held: removing items without triggering processing"
+ "[%s] Collection assertion held: storing items without processing"
+ "[%s] Collection assertion released: %{public}s (%{public}s)"
+ "[%s] Collection assertion taken: %{public}s (%{public}s)"
+ "[%s] Failed to write debug snapshot: %@"
+ "[%s] No collection assertions held; triggering arbitration of buffered items"
+ "[ArbiterCollectionAssertion] Assertion for \"%{public}s\" (%{public}s) deallocated without being invalidated; releasing implicitly"
+ "_createCheckedThrowingContinuation(_:)"
+ "arbiter-snapshot.txt"
+ "com.apple.private.health.location"
+ "fallbackLocationStorage"
+ "fetchPlaceInference()"
+ "liveUpdates failed: %{public}@"
+ "placeInferenceStorage"
+ "rawAuthorizationStatus"
- "[%s] Collection mode: removing items without triggering processing"
- "[%s] Collection mode: storing items without processing"
- "[%s] Switching to active mode"
- "[%s] Triggering initial arbitration of collected items"
```
