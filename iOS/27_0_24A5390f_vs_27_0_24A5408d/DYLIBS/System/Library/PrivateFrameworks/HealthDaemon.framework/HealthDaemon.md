## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/HealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x968db0` | `0x96c524` | **`+0x3774`** |
| `__TEXT.__cstring` | `0x85073` | `0x85417` | **`+0x3a4`** |
| `__TEXT.__oslogstring` | `0x499df` | `0x49c80` | **`+0x2a1`** |
| `__AUTH_CONST.__cfstring` | `0x40700` | `0x40860` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x83920` | `0x83a28` | **`+0x108`** |
| `__TEXT.__gcc_except_tab` | `0x398c8` | `0x399b4` | **`+0xec`** |
| `__AUTH.__data` | `0x1ea8` | `0x1f50` | **`+0xa8`** |
| `__DATA_CONST.__objc_arraydata` | `0x89a0` | `0x89e8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x21738` | `0x21780` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x448c` | `0x44d0` | **`+0x44`** |
| `__TEXT.__swift5_reflstr` | `0x32f8` | `0x3338` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x341c` | `0x3450` | **`+0x34`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2148` | `0x2178` | **`+0x30`** |
| `__TEXT.__const` | `0x26bd0` | `0x26c00` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x6fe8` | `0x7018` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x46694` | `0x466c4` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1dfd8` | `0x1e000` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b488` | `0x1b4a8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3dd8` | `0x3de8` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x18248` | `0x18250` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x458c` | `0x4594` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x5cf0` | `0x5cf8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2c20` | `0x2c28` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x4adb` | `0x4ae1` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x3bc` | `0x3c0` | **`+0x4`** |

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 41494
-  Symbols:   60162
-  CStrings:  14337
+  Functions: 41522
+  Symbols:   60189
+  CStrings:  14361
Symbols:
+ +[HDFitnessFriendActivitySnapshotEntity shouldInsertObject:sourceID:profile:transaction:objectToReplace:objectID:error:]
+ -[HDLocationDataCollector flushBufferedLocationsThroughDate:completion:]
+ -[HDLocationDataCollector shouldFlushBufferedLocationTail]
+ -[HDLocationManager flushBufferedLocationsThroughDate:timeout:completion:]
+ _HDLocationDataCollectorStateToString
+ _OBJC_IVAR_$_HDLocationDataCollector._usesBufferedSensorBehavior
+ _OBJC_IVAR_$_HDLocationManager._observerDeliveryQueue
+ __DATA__TtCC12HealthDaemon16HDDataCacheStoreP33_947F840B8844D71EAB3AFA884CB8010626AnchorAfterDatabaseScanBox
+ __HDCreateNMTable
+ __HDDeleteOrphanedFitnessFriendActivitySnapshots
+ __HDDropRedundantTrainingLoadCachePlainIndexes
+ __HKDaemonPreferencesTCCReportUseThrottleDayOverrideKey
+ __HKWorkoutExtendedModeTypeForPowerMode
+ __IVARS__TtCC12HealthDaemon16HDDataCacheStoreP33_947F840B8844D71EAB3AFA884CB8010626AnchorAfterDatabaseScanBox
+ __METACLASS_DATA__TtCC12HealthDaemon16HDDataCacheStoreP33_947F840B8844D71EAB3AFA884CB8010626AnchorAfterDatabaseScanBox
+ ___120+[HDFitnessFriendActivitySnapshotEntity shouldInsertObject:sourceID:profile:transaction:objectToReplace:objectID:error:]_block_invoke
+ ___72-[HDLocationDataCollector flushBufferedLocationsThroughDate:completion:]_block_invoke
+ ___72-[HDLocationDataCollector flushBufferedLocationsThroughDate:completion:]_block_invoke_2
+ ___74-[HDLocationManager flushBufferedLocationsThroughDate:timeout:completion:]_block_invoke
+ ___74-[HDLocationManager flushBufferedLocationsThroughDate:timeout:completion:]_block_invoke_2
+ ___78-[HDWorkoutRouteDataSource workoutDataDestination:didChangeFromState:toState:]_block_invoke
+ ___87-[HDWorkoutRouteDataSource workoutDataDestination:requestsFinalDataFrom:to:completion:]_block_invoke_4
+ ___87-[HDWorkoutRouteDataSource workoutDataDestination:requestsFinalDataFrom:to:completion:]_block_invoke_5
+ ___87-[HDWorkoutRouteDataSource workoutDataDestination:requestsFinalDataFrom:to:completion:]_block_invoke_6
+ ___87-[HDWorkoutRouteDataSource workoutDataDestination:requestsFinalDataFrom:to:completion:]_block_invoke_7
+ ___block_descriptor_48_e8_32s40bs_e31_v32?0q8"NSDate"16"NSError"24ls32l8s40l8
+ ___block_descriptor_65_e8_32s40s48r_e35_B24?0"HDDatabaseTransaction"8^16ls32l8r48l8s40l8
+ ___swift_memcpy120_8
+ ___swift_memcpy168_8
+ _symbolic _____ 12HealthDaemon16HDDataCacheStoreC26AnchorAfterDatabaseScanBox33_947F840B8844D71EAB3AFA884CB80106LLC
- ___block_descriptor_56_e8_32s40r48r_e35_B24?0"HDDatabaseTransaction"8^16lr40l8s32l8r48l8
- ___swift_memcpy112_8
- ___swift_memcpy160_8
CStrings:
+ "CREATE TEMPORARY TABLE temp_orphaned_ffas_ids AS             SELECT data_id FROM samples              WHERE data_type = 77                AND data_id NOT IN (SELECT data_id FROM fitness_friend_activity_snapshots)"
+ "DELETE FROM objects WHERE data_id IN (SELECT data_id FROM temp_orphaned_ffas_ids)"
+ "DELETE FROM samples WHERE data_id IN (SELECT data_id FROM temp_orphaned_ffas_ids)"
+ "DROP INDEX IF EXISTS training_load_statistics_cache_training_load_stats_idx"
+ "DROP INDEX IF EXISTS training_load_statistics_cache_training_load_stats_type_idx"
+ "DROP TABLE IF EXISTS temp_orphaned_ffas_ids"
+ "DROP TABLE temp_orphaned_ffas_ids"
+ "Invalidated abandoned CLLocationSmoother to release locationd smoother slot"
+ "MANUALLY_ENTERED_TYPES_COUNT"
+ "No active transaction for %{public}@; forwarding presentation failure to fail the pending request"
+ "SELECT ROWID AS device_id FROM source_devices WHERE name IS NOT ?"
+ "SELECT p.source_id AS source_id,\n       p.device_id AS device_id,\n       COUNT(*) AS cnt\nFROM samples AS s\nINNER JOIN objects AS o ON o.data_id = s.data_id\nINNER JOIN data_provenances AS p ON o.provenance = p.ROWID\nWHERE s.data_type = ?\nGROUP BY p.source_id, p.device_id"
+ "Saving cached manually-entered types count"
+ "Unauthorized access to feature availability requirement evaluation"
+ "Using QA TCC report-use throttle override day %ld for %{public}@"
+ "[Recovery] No accumulator snapshot for activity %s; creating fresh zone accumulators"
+ "[routes] %{public}@ Buffered-location flush finished: outcome=%ld lastDelivered=%@ error=%{public}@"
+ "[routes] %{public}@ Buffered-location flush skipped; no active location session."
+ "[routes] %{public}@ Deferring GPS teardown to final-data request to flush buffered route tail."
+ "[routes] %{public}@ Flushing buffered locations through %@ (timeout %.1lfs)."
+ "[routes] %{public}@ Flushing buffered route tail through %@."
+ "[routes] %{public}@ Skipping buffered-location flush; collector is %{public}@."
+ "com.appleinternal."
+ "countFirstPartyInternalBundleIdentifier"
+ "health-location-manager-delivery"
+ "skipping prompt for drained request group %@; finishing it"
+ "sourceID deviceID count "
+ "v32@?0q8@\"NSDate\"16@\"NSError\"24"
- "%{public}@: Failed to read associated builder configuration while finishing session: %{public}@"
- "%{public}@: Not finishing associated builder %{public}@: client is present and builder is actively saving (isEnding=YES)."
- "SELECT p.source_id AS source_id,\n       p.origin_product_type AS origin_product_type,\n       COUNT(*) AS cnt\nFROM samples AS s\nINNER JOIN objects AS o ON o.data_id = s.data_id\nINNER JOIN data_provenances AS p ON o.provenance = p.ROWID\nWHERE s.data_type = ?\nGROUP BY p.source_id, p.origin_product_type"
- "sourceID productType count "
```
