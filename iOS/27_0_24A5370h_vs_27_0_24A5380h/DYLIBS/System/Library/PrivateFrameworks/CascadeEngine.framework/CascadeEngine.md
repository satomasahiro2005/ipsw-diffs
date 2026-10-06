## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/CascadeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61a38` | `0x639f4` | **`+0x1fbc`** |
| `__TEXT.__oslogstring` | `0x6539` | `0x6a29` | **`+0x4f0`** |
| `__AUTH_CONST.__objc_const` | `0x4cf0` | `0x50d8` | **`+0x3e8`** |
| `__DATA_DIRTY.__objc_data` | `0x820` | `0xb00` | **`+0x2e0`** |
| `__AUTH.__objc_data` | `0x918` | `0x648` | **`-0x2d0`** |
| `__DATA_DIRTY.__data` | `0x2c8` | `0x508` | **`+0x240`** |
| `__TEXT.__cstring` | `0x2894` | `0x2a84` | **`+0x1f0`** |
| `__AUTH.__data` | `0x1c8` | `0x50` | **`-0x178`** |
| `__DATA_CONST.__const` | `0xde8` | `0xf00` | **`+0x118`** |
| `__TEXT.__objc_methlist` | `0x1ddc` | `0x1e8c` | **`+0xb0`** |
| `__TEXT.__gcc_except_tab` | `0x61c` | `0x6bc` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1958` | `0x19f0` | **`+0x98`** |
| `__AUTH_CONST.__const` | `0x26a0` | `0x2718` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x14e0` | `0x1558` | **`+0x78`** |
| `__DATA.__data` | `0xe38` | `0xdf8` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0xd9c` | `0xdd8` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x638` | `0x670` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x1960` | `0x1980` | **`+0x20`** |
| `__TEXT.__const` | `0x1228` | `0x1248` | **`+0x20`** |
| `__DATA.__bss` | `0xb50` | `0xb40` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x410` | `0x420` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2ac` | `0x2b8` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x368` | `0x374` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xed0` | `0xed8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xdbe` | `0xdc6` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x8c` | `0x94` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x317` | `0x31e` | **`+0x7`** |

### Other Changes

```diff

-239.0.2.0.0
+243.0.0.0.0

-  Functions: 2235
-  Symbols:   2020
-  CStrings:  801
+  Functions: 2263
+  Symbols:   2054
+  CStrings:  823
Symbols:
+ -[CCDifferentialSetUpdater _updateCacheContentForPredicate:cacheContentData:isEvict:outIsDuplicate:outDidEvictRow:error:]
+ -[CCDifferentialSetUpdater cacheEvictionResult]
+ -[CCDifferentialSetUpdater evictBatchOfKeyPrefixedIdentifiers:outRowsEvicted:error:]
+ -[CCDifferentialSetUpdater finalizeEvictionInPlaceWithError:]
+ -[CCDifferentialSetUpdater reclaimableFreelistBytes:]
+ -[CCDifferentialSetUpdater runEvictionSessionWithPercentage:candidateBatchProvider:error:]
+ -[CCDonationServiceConnection evictCacheContentWithStorageReductionPercentageTarget:reply:]
+ -[CCDonationServiceConnection(CacheEviction) _evictCacheContentWithStorageReductionPercentageTarget:candidateBatchProvider:reply:]
+ -[CCSetStoreUpdateServiceExported evictCacheContentWithStorageReductionPercentageTarget:reply:]
+ GCC_except_table24
+ GCC_except_table35
+ _OBJC_CLASS_$_CCSetDonationCacheEvictionResult
+ _OBJC_CLASS_$_CCSetDonationResult
+ _OBJC_IVAR_$_CCDifferentialSetUpdater._cacheEvictionResult
+ _OBJC_IVAR_$_CCDifferentialSetUpdater._evictionInitialFootprintBytes
+ _OBJC_IVAR_$_CCDifferentialSetUpdater._evictionSessionActive
+ _OUTLINED_FUNCTION_179
+ __OBJC_$_INSTANCE_METHODS_CCDonationServiceConnection(CacheEviction)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CCCacheEvictionCandidateProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CCDonationService
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CCCacheEvictionCandidateProvider
+ __OBJC_$_PROTOCOL_REFS_CCCacheEvictionCandidateProvider
+ __OBJC_LABEL_PROTOCOL_$_CCCacheEvictionCandidateProvider
+ __OBJC_PROTOCOL_$_CCCacheEvictionCandidateProvider
+ ___130-[CCDonationServiceConnection(CacheEviction) _evictCacheContentWithStorageReductionPercentageTarget:candidateBatchProvider:reply:]_block_invoke
+ ___55-[CCSetStoreAdminConnection _shouldDeferActivityBlock:]_block_invoke_3
+ ___55-[CCSetStoreAdminConnection _shouldDeferActivityBlock:]_block_invoke_4
+ ___77-[CCDonationServiceConnection endSetDonationWithOptions:revisionToken:reply:]_block_invoke_2
+ ___91-[CCDonationServiceConnection evictCacheContentWithStorageReductionPercentageTarget:reply:]_block_invoke
+ ___91-[CCDonationServiceConnection evictCacheContentWithStorageReductionPercentageTarget:reply:]_block_invoke_2
+ ___block_descriptor_40_e8_32r_e17_v16?0"NSArray"8lr32l8
+ ___block_descriptor_48_e8_32bs40r_e20_v20?0C8"NSError"12ls32l8r40l8
+ ___block_descriptor_48_e8_32bs_e38_B24?0"CCDifferentialSetUpdater"8^16ls32l8
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e18_"NSArray"16?0^8ls32l8r40l8
+ ___block_descriptor_50_e8_32s40r_e38_B24?0"CCDifferentialSetUpdater"8^16ls32l8r40l8
+ ___block_descriptor_64_e8_32r40r48r56r_e5_v8?0lr32l8r40l8r48l8r56l8
+ ___block_descriptor_80_e8_32r40r48r56r64r72r_e5_v8?0lr32l8r40l8r48l8r56l8r64l8r72l8
+ ___block_descriptor_88_e8_32s40s48s56r64r72r_e5_B8?0ls32l8r56l8r64l8r72l8s40l8s48l8
+ ___swift_closure_destructor.369Tm
+ _symbolic _____Sg 13CascadeEngine014CCCloudKitSyncB0C
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
- GCC_except_table11
- GCC_except_table25
- __OBJC_$_INSTANCE_METHODS_CCDonationServiceConnection
- ___block_descriptor_42_e8_32s_e38_B24?0"CCDifferentialSetUpdater"8^16ls32l8
- ___block_descriptor_56_e8_32s40s_e5_B8?0ls32l8s40l8
- _get_type_metadata 15Synchronization5MutexVy13CascadeEngine12WALTruncatorC13BudgetTrackerVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy13CascadeEngine12WALTruncatorC16TerminationStateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSSiGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%@: evictCacheContent percentage=%.3f"
+ "%@: eviction batch reverse-XPC error: %@"
+ "%@: eviction session bailing after %lu iterations without reaching target (target=%llu)"
+ "%@: eviction session done after %lu iteration(s); evictedRows=%llu of targetRows=%llu (avgRowFootprint=%llu, adjustedTarget=%llu, rawTarget=%llu, existingFreelist=%llu, initialFootprint=%llu)"
+ "%@: eviction session not starting: failed to sample existing freelist: %@"
+ "%@: eviction session not starting: failed to sample initial storage footprint: %@"
+ "%@: eviction session not starting: failed to sample live cache row count: %@"
+ "%@: eviction session starting: initialFootprint=%llu, percentage=%.3f, rawTarget=%llu, existingFreelist=%llu, adjustedTarget=%llu, liveRows=%llu, avgRowFootprint=%llu, targetRows=%llu"
+ "%@: eviction session stopping: batch eviction failed (iteration=%lu, evictedRows=%llu of targetRows=%llu)"
+ "%@: eviction session stopping: target already covered before eviction (rawTarget=%llu, existingFreelist=%llu, liveRows=%llu) — finish-time VACUUM will reclaim"
+ "%@: eviction session stopping: target met (evictedRows=%llu of targetRows=%llu) after %lu iteration(s)"
+ "%@: failed to sample final footprint (reporting 0): %@"
+ "%@: vacuumAndTruncateWAL skipped (proceeding with un-compacted final): %@"
+ "-[CCDifferentialSetUpdater evictBatchOfKeyPrefixedIdentifiers:outRowsEvicted:error:]"
+ "-[CCDifferentialSetUpdater finalizeEvictionInPlaceWithError:]"
+ "-[CCDifferentialSetUpdater runEvictionSessionWithPercentage:candidateBatchProvider:error:]"
+ "-[CCDonationServiceConnection(CacheEviction) _evictCacheContentWithStorageReductionPercentageTarget:candidateBatchProvider:reply:]"
+ "@\"NSArray\"16@?0^@8"
+ "Cancelling in-flight CKSyncEngine operations"
+ "Eviction batch provider unavailable"
+ "Reverse-XPC eviction batch call returned nil"
+ "com.apple.cascade.shouldDefer.state"
+ "v16@?0@\"NSArray\"8"
+ "v20@?0C8@\"NSError\"12"
- "%@: Item is already evicted for sourceItemIdentifier: %@"
- "%@: invalid sourceItemIdentifer: %@"
```
