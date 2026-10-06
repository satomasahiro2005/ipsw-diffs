## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/CascadeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6462c` | `0x65860` | **`+0x1234`** |
| `__TEXT.__oslogstring` | `0x6b49` | `0x6cff` | **`+0x1b6`** |
| `__TEXT.__cstring` | `0x2b64` | `0x2a8f` | **`-0xd5`** |
| `__TEXT.__eh_frame` | `0x1748` | `0x17e0` | **`+0x98`** |
| `__TEXT.__swift5_typeref` | `0xdc6` | `0xe18` | **`+0x52`** |
| `__AUTH_CONST.__cfstring` | `0x1a20` | `0x19e0` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x1ef4` | `0x1f2c` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x5148` | `0x5168` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x508` | `0x4e8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1588` | `0x15a8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xee8` | `0xf00` | **`+0x18`** |
| `__DATA.__data` | `0xdf8` | `0xe10` | **`+0x18`** |
| `__AUTH.__data` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__const` | `0x1258` | `0x1250` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x2c4` | `0x2c8` | **`+0x4`** |

### Other Changes

```diff

-250.0.0.3.0
+255.0.2.0.0

-  Functions: 2280
-  Symbols:   2076
-  CStrings:  830
+  Functions: 2314
+  Symbols:   2086
+  CStrings:  833
Symbols:
+ +[CCSyncManager isCloudKitFeatureFlagEnabled]
+ +[CCSyncManager isCloudKitSyncEnabledByTrial]
+ -[CCRapportManager _isFileTransferSessionPossible:]
+ -[CCSyncManager sharedCloudKitSyncEngine]
+ GCC_except_table35
+ _OBJC_IVAR_$_CCSyncManager._cloudKitSyncEngineLock
+ _OUTLINED_FUNCTION_181
+ __OBJC_$_CLASS_METHODS_CCSyncManager
+ _objc_unsafeClaimAutoreleasedReturnValue
+ _symbolic So8NSObjectC3key______5valuet 13CascadeEngine10TimedCacheC5Entry33_900D586F8B467B403EE930617B3CC2C0LLC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _symbolic _____ySo8NSObjectC3key______5valuetG s23_ContiguousArrayStorageC 13CascadeEngine10TimedCacheC5Entry33_900D586F8B467B403EE930617B3CC2C0LLC
- +[CCSyncManager isCloudKitSyncEnabled]
- __OBJC_$_CLASS_METHODS_CCSyncManager(CascadeEngine)
CStrings:
+ "Cascade/CascadeCloudkitSync disabled; skipping CloudKit sync engine"
+ "CloudKit sync disabled by Trial"
+ "CloudKit sync disabled by Trial; skipping CloudKit sync engine"
+ "Evicting least-recently-accessed evictable entry to honor countLimit %s: %{public}@"
+ "Failed to evaluate CloudKit-enabled sets for eager init: %@, creating sync engine"
+ "No CloudKit-enabled sets for this platform; skipping CloudKit sync engine"
+ "TimedCache deinit: releasing %ld cached entry(s)"
+ "WALTruncator skipping %s — write in flight"
- "Client not initiating RPFileTransferSession because WiFi is off"
- "Evicting least-recently-accessed entry to honor countLimit %s: %{public}@"
- "Server not fullfilling RPFileTransferSession because WiFi is off"
- "TimedCache deinit: evicting all entries"
- "_cloudKitSyncEngine"
```
