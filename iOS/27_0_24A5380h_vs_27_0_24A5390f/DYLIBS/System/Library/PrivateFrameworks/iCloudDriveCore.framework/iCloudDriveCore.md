## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/iCloudDriveCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x306a2c` | `0x3070a8` | **`+0x67c`** |
| `__AUTH.__objc_data` | `0x2738` | `0x2558` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x43a8` | `0x4588` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x3db8d` | `0x3dc85` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x825b9` | `0x82516` | **`-0xa3`** |
| `__AUTH_CONST.__objc_const` | `0x419f0` | `0x41a20` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x17698` | `0x176c8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2cc8` | `0x2ca8` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1be28` | `0x1be40` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xa3f0` | `0xa400` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2028` | `0x202c` | **`+0x4`** |

### Other Changes

```diff

-5140.0.0.0.2
+5168.0.5.0.2

-  Functions: 14204
-  Symbols:   18237
-  CStrings:  12123
+  Functions: 14206
+  Symbols:   18241
+  CStrings:  12125
Symbols:
+ +[AppTelemetryTimeSeriesEvent(BRCAdditions) newIPCMethodAccessEventForMethod:bundleID:isSandboxed:]
+ -[BRCAccountSession(IPCTelemetry) postIPCMethodTelemetry:bundleID:isSandboxed:]
+ -[BRCQueryItemInfo isInDataScope]
+ -[BRCXPCRegularIPCsClient(FPFSAdditions) _resolveSyncUpZoneName:zoneOwner:itemIDString:forLocalItem:]
+ GCC_except_table104
+ GCC_except_table106
+ GCC_except_table113
+ GCC_except_table120
+ GCC_except_table133
+ GCC_except_table166
+ GCC_except_table176
+ GCC_except_table179
+ GCC_except_table183
+ GCC_except_table187
+ GCC_except_table189
+ GCC_except_table193
+ GCC_except_table199
+ GCC_except_table205
+ GCC_except_table212
+ GCC_except_table239
+ GCC_except_table264
+ GCC_except_table279
+ GCC_except_table294
+ GCC_except_table311
+ GCC_except_table345
+ GCC_except_table353
+ GCC_except_table79
+ _OBJC_IVAR_$_BRCQueryItemInfo._isInDataScope
+ ___block_descriptor_80_e8_32s40s48s56s64r72r_e5_B8?0ls32l8s40l8s48l8r64l8r72l8s56l8
- +[AppTelemetryTimeSeriesEvent(BRCAdditions) newMissingShareAliasEventWithZoneMangledID:enhancedDrivePrivacyEnabled:itemIDString:]
- -[BRCAccountSession _submitReimportDomainFailedTelemetryEventIfNeeded]
- GCC_except_table114
- GCC_except_table132
- GCC_except_table139
- GCC_except_table141
- GCC_except_table145
- GCC_except_table152
- GCC_except_table165
- GCC_except_table168
- GCC_except_table171
- GCC_except_table175
- GCC_except_table190
- GCC_except_table195
- GCC_except_table204
- GCC_except_table214
- GCC_except_table248
- GCC_except_table260
- GCC_except_table261
- GCC_except_table281
- GCC_except_table300
- GCC_except_table333
- GCC_except_table337
- ___70-[BRCAccountSession _submitReimportDomainFailedTelemetryEventIfNeeded]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56s_e5_B8?0ls32l8s40l8s48l8s56l8
CStrings:
+ "IPC_METHOD_ACCESS"
+ "[CRIT] Assertion failed: (bits & BRCSyncStateNeedsSyncUp) == 0%@"
+ "[CRIT] Assertion failed: (self.syncState & BRCSyncStateNeedsSyncUp) == 0%@"
+ "[CRIT] UNREACHABLE: Dead item already holds learn-target id %@ for %@%@"
+ "[CRIT] UNREACHABLE: Failed to save item during learn for %@%@"
+ "[ERROR] Connection %@ auto rollback handler...%@"
+ "[WARNING] Documents folder is on disk - possibly a delete retry%@"
+ "unreachable: Dead item already holds learn-target id %@ for %@"
+ "unreachable: Failed to save item during learn for %@"
- "-[BRCAccountSession _submitReimportDomainFailedTelemetryEventIfNeeded]"
- "-[BRCAccountSession _submitReimportDomainFailedTelemetryEventIfNeeded]_block_invoke"
- "Reimport domain on startup failed"
- "Reimport domain on startup failed, need to verify that things got recovered correctly"
- "[CRIT] UNREACHABLE: That's weird but Documents is still on disk.%@"
- "[DEBUG] Checking if there is a need to submit reimport failed telemetry%@"
- "it reset the database"
```
