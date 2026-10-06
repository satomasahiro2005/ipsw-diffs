## spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x422d0` | `0x3f8fc` | **`-0x29d4`** |
| `__TEXT.__objc_methname` | `0x8ea5` | `0x8a2a` | **`-0x47b`** |
| `__DATA_CONST.__cfstring` | `0x30e0` | `0x2d80` | **`-0x360`** |
| `__TEXT.__cstring` | `0x384e` | `0x359d` | **`-0x2b1`** |
| `__TEXT.__objc_stubs` | `0x7880` | `0x7660` | **`-0x220`** |
| `__DATA.__objc_const` | `0x4740` | `0x45b0` | **`-0x190`** |
| `__TEXT.__objc_methlist` | `0x30b8` | `0x2f50` | **`-0x168`** |
| `__TEXT.__gcc_except_tab` | `0x1948` | `0x1800` | **`-0x148`** |
| `__DATA_CONST.__const` | `0x1880` | `0x1790` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0x58aa` | `0x57cf` | **`-0xdb`** |
| `__DATA.__objc_selrefs` | `0x23d8` | `0x2320` | **`-0xb8`** |
| `__TEXT.__unwind_info` | `0xee8` | `0xe50` | **`-0x98`** |
| `__TEXT.__objc_methtype` | `0x1227` | `0x1192` | **`-0x95`** |
| `__DATA_CONST.__got` | `0x248` | `0x2b0` | **`+0x68`** |
| `__DATA.__objc_data` | `0xdc0` | `0xd70` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0xa00` | `0x9e0` | **`-0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x5a0` | `0x588` | **`-0x18`** |
| `__TEXT.__objc_classname` | `0x30a` | `0x2f4` | **`-0x16`** |
| `__DATA.__objc_ivar` | `0x384` | `0x370` | **`-0x14`** |
| `__DATA_CONST.__auth_got` | `0x510` | `0x500` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x160` | `0x158` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc8` | `0xc0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-490.0.0.0.0
+491.0.0.0.0

-  Functions: 1511
-  Symbols:   246
-  CStrings:  2847
+  Functions: 1468
+  Symbols:   244
+  CStrings:  2774
Symbols:
- _objc_retain_x27
- _traverse_directory
CStrings:
- "%s: can't decode data with %@"
- "%s: can't read from disk with %@"
- "%s: unknown sorting criteria"
- "-[SACacheUsageTelemetry getSortedBundleIDs:by:]_block_invoke"
- "-[SACacheUsageTelemetry loadFromDisk]"
- "@32@0:8@16q24"
- "B24@?0r*8^{?=BBqiIQQQ{timespec=qq}{timespec=qq}B}16"
- "B56@0:8@16@24@32@40@48"
- "Cache usage telemetry Deferred"
- "CacheUsage.db"
- "FAILED to log %@ cache usage telemetry using AnalyticsSendEventLazy\n"
- "Q32@0:8@16@24"
- "SACacheUsageTelemetry"
- "T@\"NSDate\",&,V_lastRunDate"
- "T@\"NSMutableDictionary\",&,V_cacheUsageTelemetry"
- "T@\"NSMutableDictionary\",&,V_movingAveragesInfo"
- "T@\"NSNumber\",&,V_databaseVersion"
- "UpdateCacheAndTmpTelemetryEntries:appPathList:pathList:BGTask:"
- "_cacheUsageTelemetry"
- "_databaseVersion"
- "_lastRunDate"
- "_movingAveragesInfo"
- "addValueToTelemetryEntry:value:bundleIDs:"
- "app_usage"
- "app_usage_30d"
- "buildCacheUsageTelemetry:telemetryManager:appPathList:pathList:BGTask:"
- "cacheUsageTelemetry"
- "cache_age_weighted_size"
- "cache_age_weighted_size_30d"
- "cache_file_count_30d"
- "cache_purgeable_count"
- "cache_purgeable_size"
- "cache_size_30d"
- "calculateMovingAverageForKey:currentValueKey:numOfSamples:windowLength:appAverageInfo:bundleIDs:"
- "can't archive data with %@"
- "com.apple.massStorage.spaceAttribution.cacheUsage"
- "createAppCacheUsageInfoForBundleIDs:"
- "data_file_count_30"
- "data_size"
- "data_size_30d"
- "databaseVersion"
- "databaseVersionNumber"
- "dateWithTimeIntervalSince1970:"
- "disk_used"
- "getSortedBundleIDs:by:"
- "getValueForTelemetryEntry:bundleIDs:"
- "lastRunDate"
- "movingAveragesInfo"
- "removeNonExistingAppsFromDiskData"
- "sendCacheUsageTelemetry:telemetryManager:appPathList:pathList:BGTask:"
- "setCacheUsageTelemetry:"
- "setDatabaseVersion:"
- "setLastRunDate:"
- "setMovingAveragesInfo:"
- "setValueToTelemetryEntry:value:bundleIDs:"
- "time_since_last_used"
- "tmp_age_weighted_size"
- "tmp_age_weighted_size_30d"
- "tmp_file_count"
- "tmp_file_count_30d"
- "tmp_file_size"
- "tmp_file_size_30d"
- "tmp_purgeable_count"
- "tmp_purgeable_size"
- "traversePath:BGTask:reply:"
- "updateAppsSizesAndUsageTimeInTelemetry:telemetryManager:"
- "updateMovingAveragesInTelemetry"
- "updateTelemetryForBundleIDs:folderType:size:fileCount:purgeableFileCount:purgeableFileSize:ageWeightedSize:"
- "v48@0:8@16@24@32@40"
- "v48@?0Q8Q16Q24Q32Q40"
- "v56@0:8@16@24@32@40@48"
- "v64@0:8@16@24Q32Q40@48@56"
- "v72@0:8@16q24Q32Q40Q48Q56Q64"
```
