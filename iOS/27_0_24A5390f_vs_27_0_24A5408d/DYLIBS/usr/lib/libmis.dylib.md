## libmis.dylib

> `/usr/lib/libmis.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xccd8` | `0x11438` | **`+0x4760`** |
| `__TEXT.__text` | `0x3c6fc` | `0x3f5f4` | **`+0x2ef8`** |
| `__TEXT.__cstring` | `0x5351` | `0x5812` | **`+0x4c1`** |
| `__DATA_CONST.__const` | `0x4710` | `0x4b70` | **`+0x460`** |
| `__AUTH.__objc_data` | `0x1b0` | `0x340` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x30f0` | `0x3259` | **`+0x169`** |
| `__AUTH_CONST.__const` | `0x14b8` | `0x1618` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x1528` | `0x1670` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0xd3c` | `0xe0c` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x108c` | `0x1154` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x944` | `0xa04` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x4c8` | `0x564` | **`+0x9c`** |
| `__TEXT.__unwind_info` | `0xe70` | `0xf08` | **`+0x98`** |
| `__TEXT.__swift5_typeref` | `0x474` | `0x4e5` | **`+0x71`** |
| `__DATA_CONST.__objc_selrefs` | `0x888` | `0x8f0` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x250` | `0x2a9` | **`+0x59`** |
| `__TEXT.__swift5_fieldmd` | `0x368` | `0x3bc` | **`+0x54`** |
| `__AUTH.__data` | `0x80` | `0xd0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xf10` | `0xf50` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x1d20` | `0x1d60` | **`+0x40`** |
| `__DATA.__data` | `0x2b8` | `0x2f8` | **`+0x40`** |
| `__DATA.__bss` | `0xc00` | `0xc20` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x300` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x78` | **`+0xc`** |
| `__DATA.__common` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-487.0.0.0.0
+487.0.2.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 1217
-  Symbols:   1021
-  CStrings:  693
+  Functions: 1270
+  Symbols:   1028
+  CStrings:  711
Symbols:
+ _AnalyticsSendEventLazy
+ _ApplePlatformBootstrapRootCAG1
+ _ApplePlatformBootstrapRootCAG1PublicKey
+ _ApplePlatformBootstrapRootCAG1SKID
+ _ApplePlatformBootstrapRootCAG1SPKI
+ _ApplePlatformDeveloperRootCAG1
+ _ApplePlatformDeveloperRootCAG1PublicKey
+ _ApplePlatformDeveloperRootCAG1SKID
+ _ApplePlatformDeveloperRootCAG1SPKI
+ _ApplePlatformMultipurposeRootCAG1
+ _ApplePlatformMultipurposeRootCAG1PublicKey
+ _ApplePlatformMultipurposeRootCAG1SKID
+ _ApplePlatformMultipurposeRootCAG1SPKI
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_OnlineAuthMetrics
+ _OBJC_METACLASS_$_OnlineAuthMetrics
+ __swiftEmptySetSingleton
+ _gettimeofday
+ _swift_retain_x23
+ _sysctl
- ___sandbox_ms
- _amfi_developer_mode_resolved
- _amfi_interface_authorize_local_signing
- _amfi_interface_authorize_local_signing_with_length
- _amfi_interface_cdhash_in_trustcache
- _amfi_interface_get_local_signing_private_key
- _amfi_interface_query_bootarg_state
- _amfi_interface_set_local_signing_public_key
- _amfi_launch_constraint_matches_process
- _amfi_launch_constraint_set_spawnattr
- _amfi_restricted_execution_mode_enable
- _amfi_restricted_execution_mode_status
- _posix_spawnattr_setmacpolicyinfo_np
CStrings:
+ "11"
+ "2f319679-66b9-44cf-9cf0-723471de0db9"
+ "?2 > last_success_monotonic_time + (grace_period"
+ "CREATE TABLE IF NOT EXISTS online_auth_migration_state (  id INTEGER NOT NULL PRIMARY KEY CHECK (id = 1),  last_migration_monotonic_time INTEGER NOT NULL,  last_migration_sources_bitmask INTEGER NOT NULL,  last_seen_os_build TEXT NOT NULL )"
+ "Couldn't create the online auth migration state table: %s"
+ "Error getting online auth migration state: %{public}@"
+ "Error setting last seen OS build: %{public}@"
+ "Error setting online auth migration state: %{public}@"
+ "INSERT INTO online_auth_migration_state (\n    id, last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\n)\nVALUES (1, -1, 0, ?1)\nON CONFLICT(id) DO UPDATE SET last_seen_os_build = ?1"
+ "INSERT INTO online_auth_migration_state (\n    id, last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\n)\nVALUES (1, ?1, ?2, \"\")\nON CONFLICT(id) DO UPDATE SET\n    last_migration_monotonic_time = ?1,\n    last_migration_sources_bitmask = ?2"
+ "IndeterminateTelemetry: error fetching indeterminates: %{public}@"
+ "MISQL: performing database migration 10 -> 11"
+ "SELECT\n    uuid,\n    cdhash,\n    grace_period,\n    last_success_monotonic_time,\n    last_success_reset_count,\n    is_rejected,\n    is_rejected_by_whole_profile\nFROM online_auth\nWHERE "
+ "SELECT 1 FROM online_auth WHERE "
+ "SELECT COUNT(*) FROM profiles"
+ "SELECT last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\nFROM online_auth_migration_state\nWHERE id = 1"
+ "adaea588-c074-4b87-b8ea-26cb685b3443"
+ "com.apple.mis.onlineauth.indeterminate_detected"
+ "com.apple.mis.onlineauth.migration_completed"
+ "droppedProfileUninstalled"
+ "hoursSinceLastMigration"
+ "hoursSinceLastSuccess"
+ "lastMigrationSource"
+ "last_migration_monotonic_time"
+ "last_migration_sources_bitmask"
+ "last_seen_os_build"
+ "minutesSinceBoot"
+ "mis.MISOnlineAuthMigrationState"
+ "profileCountOnDevice"
- ") AND is_rejected = 0 AND cdhash = ?3"
- ") AND is_rejected = 0 AND uuid = ?3"
- ") AND is_rejected = 0 AND uuid = ?3 AND cdhash = ?4"
- "?1 != last_success_reset_count OR ?2 > last_success_monotonic_time + grace_period * 24 * 60 * 60"
- "?2 > last_success_monotonic_time + (grace_period - "
- "AMFI"
- "Constraint too large"
- "No Constraint provided"
- "SELECT 1\nFROM online_auth\nWHERE ("
- "security.mac.amfi.developer_mode_resolved"
- "security.mac.amfi.developer_mode_status"
```
