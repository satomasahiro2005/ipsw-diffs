## MDM

> `/System/Library/PrivateFrameworks/MDM.framework/MDM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x580e0` | `0x58544` | **`+0x464`** |
| `__TEXT.__oslogstring` | `0x7596` | `0x76e4` | **`+0x14e`** |
| `__DATA_CONST.__const` | `0x1f40` | `0x1f68` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x437c` | `0x43a4` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x35a8` | `0x35c0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x7d8` | `0x7e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1300` | `0x1310` | **`+0x10`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

-  Functions: 1708
-  Symbols:   3437
-  CStrings:  1366
+  Functions: 1711
+  Symbols:   3443
+  CStrings:  1370
Symbols:
+ -[MDMDEPPushTokenManager _queue_scheduleAppTokenSyncWithLatestTokenHash:]
+ -[MDMMigrator _removeMigrationStateFiles]
+ -[MDMServerCore _uprootStopManagingAppWithBundleID:preservedAppIDs:error:]
+ -[MDMServerCore _uprootStopManagingApps]
+ GCC_except_table319
+ GCC_except_table330
+ GCC_except_table334
+ GCC_except_table345
+ GCC_except_table349
+ GCC_except_table365
+ _MDMCloudConfigurationPendingMigrationDetailsFilePath
+ _MDMMigrationConfigFilePath
+ ___block_descriptor_56_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- -[MDMDEPPushTokenManager _queue_scheduleAppTokenSync]
- GCC_except_table317
- GCC_except_table328
- GCC_except_table332
- GCC_except_table343
- GCC_except_table347
- GCC_except_table363
CStrings:
+ "Failed to remove stale migration state file at %{public}@: %{public}@"
+ "MDMDEPPushTokenManager: Received app token for topic: %{public}@, appToken: %{public}@, hash: %{public}@"
+ "MDMDEPPushTokenManager: _scheduleAppTokenSync app token changed since last sync, syncing immediately"
+ "MDMDEPPushTokenManager: _scheduleAppTokenSync schedule sync with random delay due to no previous sync"
+ "MDMServerCore retrying stop managing for %lu app(s) that failed during initial uproot pass"
+ "Removed stale migration state file at %{public}@"
- "MDMDEPPushTokenManager: Received app token for topic: %{public}@, appToken: %{public}@"
- "MDMDEPPushTokenManager: _scheduleAppTokenSync schedule sync with random delay due to no deadline"
```
