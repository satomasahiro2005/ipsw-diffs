## MetricMeasurement

> `/System/Library/PrivateFrameworks/MetricMeasurement.framework/MetricMeasurement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1da90` | `0x1f878` | **`+0x1de8`** |
| `__TEXT.__oslogstring` | `0xb07` | `0x101a` | **`+0x513`** |
| `__TEXT.__gcc_except_tab` | `0x648` | `0x85c` | **`+0x214`** |
| `__AUTH_CONST.__objc_const` | `0x5a08` | `0x5b08` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x28e4` | `0x29cc` | **`+0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x28a0` | `0x2980` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x2718` | `0x27da` | **`+0xc2`** |
| `__TEXT.__unwind_info` | `0x9a8` | `0xa58` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1578` | `0x1618` | **`+0xa0`** |
| `__DATA.__data` | `0x7e0` | `0x840` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xe60` | `0xeb0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x6a8` | `0x6f0` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x140` | `0x180` | **`+0x40`** |
| `__DATA.__bss` | `0x2b0` | `0x2d8` | **`+0x28`** |
| `__TEXT.__const` | `0x278` | `0x298` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x288` | `0x2a0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x174` | `0x17c` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x178` | `0x180` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x108` | `0x110` | **`+0x8`** |

### Other Changes

```diff

-358.0.0.0.0
+361.0.0.0.0

-  Functions: 874
-  Symbols:   1667
-  CStrings:  402
+  Functions: 894
+  Symbols:   1716
+  CStrings:  426
Symbols:
+ +[MXMOSSignpostProbe initialize]
+ +[MXMOSSignpostProbe invalidateIntervalCache]
+ +[MXMOSSignpostProbe registerSubsystem:category:]
+ +[MXMOSSignpostProbe registeredFilterEntries]
+ +[MXMOSSignpostProbe resetRegisteredFilterEntries]
+ -[MXMCompositeKeyDictionary .cxx_destruct]
+ -[MXMCompositeKeyDictionary count]
+ -[MXMCompositeKeyDictionary init]
+ -[MXMCompositeKeyDictionary objectForPrimaryKey:secondaryKey:]
+ -[MXMCompositeKeyDictionary removeAllObjects]
+ -[MXMCompositeKeyDictionary removeObjectForPrimaryKey:secondaryKey:]
+ -[MXMCompositeKeyDictionary setObject:forPrimaryKey:secondaryKey:]
+ -[MXMOSSignpostMetric prepareWithOptions:error:]
+ -[MXMOSSignpostProbe _cacheSignpostInterval:]
+ -[MXMOSSignpostProbe _isHitchSignpostMetric]
+ -[MXMOSSignpostProbe _replayIntervals:]
+ -[MXMProxyServiceManager _syncSignpostAllowlistConfig:response:]
+ GCC_except_table18
+ GCC_except_table31
+ GCC_except_table35
+ GCC_except_table36
+ GCC_except_table37
+ GCC_except_table38
+ GCC_except_table41
+ GCC_except_table47
+ GCC_except_table58
+ GCC_except_table60
+ GCC_except_table66
+ _OBJC_CLASS_$_MXMCompositeKeyDictionary
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_CLASS_$_SignpostSupportSubsystemCategoryAllowlist
+ _OBJC_IVAR_$_MXMCompositeKeyDictionary._count
+ _OBJC_IVAR_$_MXMCompositeKeyDictionary._storage
+ _OBJC_METACLASS_$_MXMCompositeKeyDictionary
+ __OBJC_$_INSTANCE_METHODS_MXMCompositeKeyDictionary
+ __OBJC_$_INSTANCE_VARIABLES_MXMCompositeKeyDictionary
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MXMSProxySignpostConfig_Internal
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MXMSProxySignpostConfig_Internal
+ __OBJC_$_PROTOCOL_REFS_MXMSProxySignpostConfig_Internal
+ __OBJC_CLASS_RO_$_MXMCompositeKeyDictionary
+ __OBJC_LABEL_PROTOCOL_$_MXMSProxySignpostConfig_Internal
+ __OBJC_METACLASS_RO_$_MXMCompositeKeyDictionary
+ __OBJC_PROTOCOL_$_MXMSProxySignpostConfig_Internal
+ ___48-[MXMOSSignpostMetric prepareWithOptions:error:]_block_invoke
+ ___51-[MXMOSSignpostProbe sampleWithTimeout:stopReason:]_block_invoke
+ ___51-[MXMOSSignpostProbe sampleWithTimeout:stopReason:]_block_invoke_2
+ ___64-[MXMProxyServiceManager _syncSignpostAllowlistConfig:response:]_block_invoke
+ ___block_descriptor_32_e47_q24?0"SignpostInterval"8"SignpostInterval"16l
+ ___block_descriptor_40_e8_32s_e43_B24?0"SignpostInterval"8"NSDictionary"16ls32l8
+ __intervalCache
+ __lastSeenIterationStartDate
+ __overflowedCacheKeys
+ __registeredFilterEntries
+ __totalIntervalsCached
- GCC_except_table50
- GCC_except_table52
- _OBJC_CLASS_$_SignpostSupportSubsystemCategoryWhitelist
- ___44-[MXMOSSignpostProbe _setupProcessingBlocks]_block_invoke_4
- ___44-[MXMOSSignpostProbe _setupProcessingBlocks]_block_invoke_5
CStrings:
+ "(subsystem='%@' category='%@')"
+ ", "
+ "B24@?0@\"SignpostInterval\"8@\"NSDictionary\"16"
+ "Intervals Found"
+ "MXM: Beginning to collect metric updates"
+ "MXM: Cache HIT — replayed %lu interval(s), produced %tu sample(s) for subsystem='%@' category='%@'"
+ "MXM: Cache MISS for subsystem='%@' category='%@'. Starting log archive scan."
+ "MXM: Cache lookup for subsystem='%@' category='%@' — %@"
+ "MXM: Cached signpost interval — subsystem='%@' category='%@' (total cached: %lu)"
+ "MXM: Helper iteration boundary detected (startDate=%@) — invalidating probe interval cache"
+ "MXM: Interval with subsystem=%@, category=%@ filtered by mach time, processed, and cached."
+ "MXM: Interval with subsystem=%@, category=%@ processed and cached. No mach time available for filtering."
+ "MXM: Probe interval cache invalidated"
+ "MXM: Probe registered filter: subsystem='%@' category='%@'"
+ "MXM: Processing complete. Cache now has %lu entries."
+ "MXM: Setting up processing filter with %lu entries: [%@]"
+ "MXM: Signpost allowlist not synced (%@); if SignpostSupport scans with an empty allowlist then ALL signposts may be extracted. Ensure that code is being on os 27 or higher."
+ "MXM: Signpost cache limit of %lu interval(s) reached; dropping subsystem='%@' category='%@' and all subsequent intervals for this iteration. Lookup for subsequent intervals will be done via SignpostSupport."
+ "MXM: Skipping cache — interval has nil subsystem or category"
+ "No Intervals Found"
+ "category"
+ "filterEntries"
+ "q24@?0@\"SignpostInterval\"8@\"SignpostInterval\"16"
+ "subsystem"
```
