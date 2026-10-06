## online-auth-agent

> `/usr/libexec/online-auth-agent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ca2c` | `0x3d9d4` | **`+0xfa8`** |
| `__TEXT.__cstring` | `0x3c4b` | `0x4045` | **`+0x3fa`** |
| `__TEXT.__objc_methname` | `0x1d25` | `0x1f55` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x2ddb` | `0x2ee5` | **`+0x10a`** |
| `__DATA.__objc_const` | `0x1420` | `0x1508` | **`+0xe8`** |
| `__DATA.__objc_data` | `0x4c0` | `0x590` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x2488` | `0x2510` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x7ac` | `0x82c` | **`+0x80`** |
| `__TEXT.__const` | `0x23fc` | `0x2458` | **`+0x5c`** |
| `__DATA.__objc_selrefs` | `0x8c0` | `0x900` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x14a0` | `0x14e0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1c40` | `0x1c80` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x795` | `0x7d4` | **`+0x3f`** |
| `__TEXT.__constg_swiftt` | `0xbfc` | `0xc38` | **`+0x3c`** |
| `__TEXT.__swift5_fieldmd` | `0x9e8` | `0xa1c` | **`+0x34`** |
| `__DATA.__data` | `0x16b8` | `0x16e0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x1290` | `0x12b8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xec0` | `0xee8` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x358` | `0x378` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x534` | `0x554` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x468` | `0x480` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x670` | `0x688` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x949` | `0x958` | **`+0xf`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xf0` | `0xf4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-487.0.0.0.0
+487.0.2.0.0

-  - /System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset

-  Functions: 1265
+  Functions: 1292

-  CStrings:  1017
+  CStrings:  1045
CStrings:
+ "11"
+ "2f319679-66b9-44cf-9cf0-723471de0db9"
+ "?"
+ "B36@0:8q16i24^@28"
+ "CREATE TABLE IF NOT EXISTS online_auth_migration_state (  id INTEGER NOT NULL PRIMARY KEY CHECK (id = 1),  last_migration_monotonic_time INTEGER NOT NULL,  last_migration_sources_bitmask INTEGER NOT NULL,  last_seen_os_build TEXT NOT NULL )"
+ "Couldn't create the online auth migration state table: %s"
+ "Error getting online auth migration state: %{public}@"
+ "Error setting last seen OS build: %{public}@"
+ "Error setting online auth migration state: %{public}@"
+ "INSERT INTO online_auth_migration_state (\n    id, last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\n)\nVALUES (1, -1, 0, ?1)\nON CONFLICT(id) DO UPDATE SET last_seen_os_build = ?1"
+ "INSERT INTO online_auth_migration_state (\n    id, last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\n)\nVALUES (1, ?1, ?2, \"\")\nON CONFLICT(id) DO UPDATE SET\n    last_migration_monotonic_time = ?1,\n    last_migration_sources_bitmask = ?2"
+ "MISOnlineAuthMigrationState"
+ "MISQL: performing database migration 10 -> 11"
+ "SELECT last_migration_monotonic_time, last_migration_sources_bitmask, last_seen_os_build\nFROM online_auth_migration_state\nWHERE id = 1"
+ "T@\"NSString\",N,R"
+ "Ti,N,R,VlastMigrationSourcesBitmask"
+ "Tq,N,R,VlastMigrationMonotonicTime"
+ "adaea588-c074-4b87-b8ea-26cb685b3443"
+ "getOnlineAuthMigrationStateNoThrow"
+ "lastMigrationMonotonicTime"
+ "lastMigrationSourcesBitmask"
+ "lastSeenOSBuild"
+ "online_auth_agent.MISOnlineAuthMigrationState"
+ "setLastSeenOSBuild:error:"
+ "setLastSeenOSBuildNoThrow:"
+ "setOnlineAuthMigrationStateNoThrowWithLastMigrationMonotonicTime:lastMigrationSourcesBitmask:"
+ "setOnlineAuthMigrationStateWithLastMigrationMonotonicTime:lastMigrationSourcesBitmask:error:"
+ "v28@0:8q16i24"
```
