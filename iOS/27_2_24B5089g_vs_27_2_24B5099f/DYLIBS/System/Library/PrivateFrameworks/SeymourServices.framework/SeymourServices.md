## SeymourServices

> `/System/Library/PrivateFrameworks/SeymourServices.framework/SeymourServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b0400` | `0x9bad4c` | **`+0xa94c`** |
| `__TEXT.__eh_frame` | `0x78c04` | `0x79380` | **`+0x77c`** |
| `__TEXT.__oslogstring` | `0x14482` | `0x148c2` | **`+0x440`** |
| `__AUTH_CONST.__const` | `0x3a4b0` | `0x3a6e8` | **`+0x238`** |
| `__TEXT.__unwind_info` | `0x234d8` | `0x23608` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x16d38` | `0x16e54` | **`+0x11c`** |
| `__TEXT.__swift5_typeref` | `0x14a8a` | `0x14b86` | **`+0xfc`** |
| `__TEXT.__swift5_reflstr` | `0xc004` | `0xc0c4` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x126d8` | `0x12778` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xf945` | `0xf9d5` | **`+0x90`** |
| `__DATA.__data` | `0x5c58` | `0x5cd8` | **`+0x80`** |
| `__TEXT.__const` | `0x293f0` | `0x29470` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x81f4` | `0x81a4` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x94d8` | `0x9520` | **`+0x48`** |
| `__TEXT.__swift_as_ret` | `0x279c` | `0x27e0` | **`+0x44`** |
| `__DATA_DIRTY.__data` | `0xfde8` | `0xfdb8` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x6678` | `0x6658` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0x1d0c` | `0x1d28` | **`+0x1c`** |
| `__DATA.__common` | `0x190` | `0x198` | **`+0x8`** |

### Other Changes

```diff

-2027.1.54.0.0
+2027.1.63.0.0

-  Functions: 34794
-  Symbols:   7609
-  CStrings:  2938
+  Functions: 34881
+  Symbols:   7617
+  CStrings:  2956
Symbols:
+ ___swift_closure_destructor.626Tm
+ ___swift_closure_destructor.654Tm
+ ___swift_closure_destructor.672Tm
+ ___swift_closure_destructor.74Tm
+ _symbolic SDy_____y_____GyyYaYbKcG s14PartialKeyPathC 11SeymourCore33RemoteBrowsingEnvironmentProtobufV
+ _symbolic ScSySo13HKQueryAnchorCG
+ _symbolic Shy_____y_____GG s14PartialKeyPathC 11SeymourCore33RemoteBrowsingEnvironmentProtobufV
+ _symbolic So21NSPersistentContainerCXDXMT
+ _symbolic _____Say_____G______pIeggrzo_ 15SeymourServices18PersistenceContextV 0A14CoreFoundation18KeyValueStringPairV s5ErrorP
+ _symbolic _____Sg 13SeymourClient20WorkoutSessionStatusO
+ _symbolic ______pIeghHzo_ s5ErrorP
+ _symbolic ______pSgz_Xx s5ErrorP
+ _symbolic _____x______pIeggrzo_ 15SeymourServices18PersistenceContextV s5ErrorP
+ _symbolic _____ySDy_____SiG_____G s13ManagedBufferCsRi__rlE 10Foundation3URLV So16os_unfair_lock_sV
+ _symbolic _____ySo13HKQueryAnchorC_G ScS8IteratorV
+ _symbolic _____y_____SiG s18_DictionaryStorageC 10Foundation3URLV
+ _symbolic _____y______pSgG 2os21OSAllocatedUnfairLockV So14AMSBagProtocolP
+ _symbolic _____y______pSg_____G s13ManagedBufferCsRi__rlE So14AMSBagProtocolP So16os_unfair_lock_sV
+ _symbolic _____y_____y_____GG s11_SetStorageC s14PartialKeyPathC 11SeymourCore33RemoteBrowsingEnvironmentProtobufV
+ _symbolic _____y_____y_____GyyYaYbKcG s18_DictionaryStorageC s14PartialKeyPathC 11SeymourCore33RemoteBrowsingEnvironmentProtobufV
+ _symbolic _____yt______pIeggrzo_ 15SeymourServices18PersistenceContextV s5ErrorP
- ___swift_closure_destructor.624Tm
- ___swift_closure_destructor.652Tm
- ___swift_closure_destructor.669Tm
- ___swift_closure_destructor.72Tm
- ___swift_closure_destructor.83Tm
- _symbolic Say_____G______pIegrzo_ 21SeymourCoreFoundation18KeyValueStringPairV s5ErrorP
- _symbolic ScSy_____G 13SeymourClient21AnchoredSamplesResultV
- _symbolic _____Sg 13SeymourClient21AnchoredSamplesResultV
- _symbolic ______pSg So14AMSBagProtocolP
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18SeymourMetricsCore22MetricTopicIdentifiersV
- _symbolic _____y______G ScS8IteratorV 13SeymourClient21AnchoredSamplesResultV
- _symbolic x______pIegrzo_ s5ErrorP
- _symbolic yt______pIegrzo_ s5ErrorP
CStrings:
+ "Coalesced refresh for %{mask.hash}s failed: %s"
+ "Failed to execute maintenance: %s"
+ "Failed to publish metric identifiers: %{public}s"
+ "Failed to refresh personalization HealthKit workouts: %s"
+ "MetricComponent.publishMetricIdentifiers"
+ "Personalization was opted out while this HealthKit refresh was in flight, purging instead of publishing it"
+ "Purging the personalization HealthKit workouts"
+ "Refresh already in flight for %{mask.hash}s, coalescing this one into it"
+ "Refresh already in flight for %{mask.hash}s, it covers this one"
+ "StorefrontObserver country code fetch failed: %{public}s"
+ "StorefrontObserver failed to fetch country code: %{public}s"
+ "StorefrontObserver only found fallback country code: %{public}@"
+ "Updating Schema from %{public}s to %{public}s"
+ "Workout session is %{public}s, deferring personalization HealthKit maintenance"
+ "Workout session is %{public}s, deferring the personalization HealthKit refresh for this opt-in"
+ "[CatalogSyncCoordinator] Catalog synced in %{public}s, storefront is %{public}s; bootstrapping"
+ "[CatalogSyncEvaluator] Catalog language differs from the storefront, sync required"
+ "[attach-audit] %{public}s is attached to %{public}ld coordinators at once (reason=%{public}s). A second connection is what makes the write context's merge policy unable to converge an optimistic-locking conflict — rdar://186462994."
+ "[detach] %{public}s reason=%{public}s store=%{public}s db=%ld wal=%ld shm=%ld"
+ "fetchStorefrontCountryCode()"
+ "link-load"
+ "migration-complete"
+ "migration-load"
+ "migration-schema-step"
+ "publishMetricIdentifiers"
+ "publishMetricIdentifiers()"
+ "refreshCountryCode()"
- "Failed to process workout change notification: %s"
- "Failed to serialize metric identifiers: %{public}s"
- "Failed to update healthkit workouts on initial query: %s"
- "HealthKit workout callback carried no changes, skipping personalization refresh"
- "MetricComponent.serializeMetricIdentifiers"
- "Updating Schema from %s to %s"
- "[unlink] %{public}s store=%{public}s db=%ld wal=%ld shm=%ld"
- "serializeMetricIdentifiers"
- "serializeMetricIdentifiers()"
```
