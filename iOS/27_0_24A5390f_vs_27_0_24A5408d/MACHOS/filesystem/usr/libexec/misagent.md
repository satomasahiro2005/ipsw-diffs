## misagent

> `/usr/libexec/misagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19318` | `0x1b420` | **`+0x2108`** |
| `__TEXT.__cstring` | `0x347e` | `0x3949` | **`+0x4cb`** |
| `__TEXT.__objc_methname` | `0x14e5` | `0x1894` | **`+0x3af`** |
| `__DATA_CONST.__const` | `0xe78` | `0x1080` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x1f47` | `0x20fd` | **`+0x1b6`** |
| `__DATA.__objc_data` | `0x4a0` | `0x630` | **`+0x190`** |
| `__DATA.__objc_const` | `0xd90` | `0xed8` | **`+0x148`** |
| `__TEXT.__objc_stubs` | `0x1200` | `0x1300` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x83c` | `0x90c` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x870` | `0x930` | **`+0xc0`** |
| `__DATA.__data` | `0x2d8` | `0x360` | **`+0x88`** |
| `__TEXT.__const` | `0x452` | `0x4d8` | **`+0x86`** |
| `__TEXT.__objc_methtype` | `0x3ac` | `0x42f` | **`+0x83`** |
| `__DATA_CONST.__cfstring` | `0x14e0` | `0x1560` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x1ac` | `0x22c` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x748` | `0x7c0` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x5b8` | `0x610` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0x141` | `0x199` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x266` | `0x2b9` | **`+0x53`** |
| `__TEXT.__swift5_reflstr` | `0x80` | `0xc9` | **`+0x49`** |
| `__TEXT.__swift5_fieldmd` | `0xe8` | `0x12c` | **`+0x44`** |
| `__TEXT.__gcc_except_tab` | `0x534` | `0x574` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x14b0` | `0x14e0` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x504` | `0x52c` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0xa68` | `0xa80` | **`+0x18`** |
| `__DATA.__bss` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x78` | **`+0x10`** |
| `__DATA.__common` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xb0` | `0xa8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x24` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-487.0.0.0.0
+487.0.2.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 665
-  Symbols:   367
-  CStrings:  725
+  Functions: 729
+  Symbols:   370
+  CStrings:  772
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_OnlineAuthMetrics
+ _OBJC_METACLASS_$_OnlineAuthMetrics
CStrings:
+ ""
+ "11"
+ "?"
+ "@\"NSDictionary\"8@?0"
+ "B36@0:8q16i24^@28"
+ "BuildVersion"
+ "CREATE TABLE IF NOT EXISTS online_auth_migration_state (  id INTEGER NOT NULL PRIMARY KEY CHECK (id = 1),  last_migration_monotonic_time INTEGER NOT NULL,  last_migration_sources_bitmask INTEGER NOT NULL,  last_seen_os_build TEXT NOT NULL )"
+ "Couldn't create the online auth migration state table: %s"
+ "Error getting online auth migration state: %{public}@"
+ "Error setting last seen OS build: %{public}@"
+ "Error setting online auth migration state: %{public}@"
+ "INSERT INTO online_auth_migration_state (\n    id, last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\n)\nVALUES (1, -1, 0, ?1)\nON CONFLICT(id) DO UPDATE SET last_seen_os_build = ?1"
+ "INSERT INTO online_auth_migration_state (\n    id, last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\n)\nVALUES (1, ?1, ?2, \"\")\nON CONFLICT(id) DO UPDATE SET\n    last_migration_monotonic_time = ?1,\n    last_migration_sources_bitmask = ?2"
+ "MISOnlineAuthMigrationState"
+ "MISQL: performing database migration 10 -> 11"
+ "Migration: indeterminate entry for profile %{public}@ has no cdHash, skipping"
+ "Migration: rejection entry for profile %{public}@ has no cdHash, skipping"
+ "OnlineAuthMetrics"
+ "SELECT last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\nFROM online_auth_migration_state\nWHERE id = 1"
+ "T@\"NSString\",N,R"
+ "T@\"OnlineAuthMetrics\",N,R"
+ "Ti,N,R,VlastMigrationSourcesBitmask"
+ "Tq,N,R,VlastMigrationMonotonicTime"
+ "com.apple.mis.onlineauth.indeterminate_detected"
+ "com.apple.mis.onlineauth.migration_completed"
+ "droppedProfileUninstalled"
+ "getOnlineAuthMigrationStateNoThrow"
+ "hoursSinceLastMigration"
+ "hoursSinceLastSuccess"
+ "lastMigrationMonotonicTime"
+ "lastMigrationSource"
+ "lastMigrationSourcesBitmask"
+ "lastSeenOSBuild"
+ "minutesSinceBoot"
+ "misagent.MISOnlineAuthMigrationState"
+ "misagent2"
+ "profileCountOnDevice"
+ "reportIndeterminateDetectedWithReason:gracePeriodDays:hoursSinceLastSuccess:profileCountOnDevice:minutesSinceBoot:hoursSinceLastMigration:lastMigrationSource:profileType:"
+ "reportMigrationCompletedWithSourcesBitmask:droppedNoCDHash:droppedProfileUninstalled:droppedOther:fromOsBuild:"
+ "setLastSeenOSBuild:error:"
+ "setLastSeenOSBuildNoThrow:"
+ "setOnlineAuthMigrationStateNoThrowWithLastMigrationMonotonicTime:lastMigrationSourcesBitmask:"
+ "setOnlineAuthMigrationStateWithLastMigrationMonotonicTime:lastMigrationSourcesBitmask:error:"
+ "shared"
+ "v28@0:8q16i24"
+ "v56@0:8q16q24q32q40@48"
+ "v80@0:8q16q24q32q40q48q56q64q72"
```
