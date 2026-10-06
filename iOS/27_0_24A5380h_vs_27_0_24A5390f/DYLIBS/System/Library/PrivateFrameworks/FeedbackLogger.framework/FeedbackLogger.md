## FeedbackLogger

> `/System/Library/PrivateFrameworks/FeedbackLogger.framework/FeedbackLogger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c200` | `0x1d25c` | **`+0x105c`** |
| `__TEXT.__oslogstring` | `0x1b54` | `0x1cfe` | **`+0x1aa`** |
| `__DATA_CONST.__const` | `0x360` | `0x428` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x19d0` | `0x1a60` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x117c` | `0x11fc` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x1e4` | `0x260` | **`+0x7c`** |
| `__TEXT.__cstring` | `0x2026` | `0x2081` | **`+0x5b`** |
| `__DATA_CONST.__objc_selrefs` | `0xc30` | `0xc88` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x9e0` | `0xa30` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x78` | `0xc0` | **`+0x48`** |
| `__DATA_CONST.__objc_arraydata` | `0x18` | `0x58` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__const` | `0x1490` | `0x14a0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x120` | `0x12c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x878` | `0x880` | **`+0x8`** |

### Other Changes

```diff

-3600.56.16.0.0
+3600.56.21.0.0

-  Functions: 909
-  Symbols:   1011
-  CStrings:  332
+  Functions: 926
+  Symbols:   1040
+  CStrings:  340
Symbols:
+ -[FLLogger _dispatchCleanupWithWatchdog]
+ -[FLLogger _dispatchPersistWithWatchdogForStoreID:category:payloadSize:writeTransaction:persistor:completion:]
+ -[FLLogger _persistentStoreKeyForStoreId:category:]
+ -[FLLogger cleanupWatchdogTimeout]
+ -[FLLogger persistWatchdogTimeout]
+ -[FLLogger reportCACleanupTimeout]
+ -[FLLogger reportCAPersistTimeoutFromBundleID:category:size:]
+ -[FLLogger setCleanupWatchdogTimeout:]
+ -[FLLogger setPersistWatchdogTimeout:]
+ -[FLLogger setWatchdogQueue:]
+ -[FLLogger watchdogQueue]
+ GCC_except_table102
+ GCC_except_table119
+ GCC_except_table180
+ GCC_except_table249
+ GCC_except_table274
+ GCC_except_table348
+ GCC_except_table47
+ GCC_except_table66
+ GCC_except_table68
+ GCC_except_table70
+ GCC_except_table72
+ GCC_except_table78
+ GCC_except_table83
+ GCC_except_table85
+ GCC_except_table89
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_IVAR_$_FLLogger._cleanupWatchdogTimeout
+ _OBJC_IVAR_$_FLLogger._persistWatchdogTimeout
+ _OBJC_IVAR_$_FLLogger._watchdogQueue
+ ___110-[FLLogger _dispatchPersistWithWatchdogForStoreID:category:payloadSize:writeTransaction:persistor:completion:]_block_invoke
+ ___40-[FLLogger _dispatchCleanupWithWatchdog]_block_invoke
+ ___52-[FLLogger write:category:toStoreWithID:completion:]_block_invoke_2
+ ___75-[FLLogger reportDataPlatformBatchedEvent:forBundleID:ofSchema:completion:]_block_invoke_2
+ ___block_descriptor_104_e8_32s40s48s56s64s72bs80bs88r96r_e5_v8?0lr88l8s32l8s40l8s48l8s56l8r96l8s72l8s64l8s80l8
+ ___block_descriptor_40_e8_32r_e17_v16?0"NSError"8lr32l8
+ ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8lr40l8s32l8
+ ___block_descriptor_48_e8_32r40w_e5_v8?0lw40l8r32l8
+ ___block_descriptor_48_e8_32s40s_e38_"NSError"16?0"FLSQLitePersistence"8ls32l8s40l8
+ ___block_descriptor_80_e8_32s40s48bs56r64w_e5_v8?0lr56l8w64l8s32l8s40l8s48l8
+ _sqlite3_interrupt
- GCC_except_table163
- GCC_except_table232
- GCC_except_table257
- GCC_except_table331
- GCC_except_table41
- GCC_except_table59
- GCC_except_table63
- GCC_except_table65
- GCC_except_table71
- GCC_except_table88
- GCC_except_table90
- ___block_descriptor_80_e8_32s40s48s56s64s72bs_e5_v8?0ls32l8s40l8s48l8s56l8s72l8s64l8
CStrings:
+ "@\"NSError\"16@?0@\"FLSQLitePersistence\"8"
+ "Cleanup completed via watchdog interrupt path"
+ "Cleanup watchdog fired — interrupting cached SQLite connections to break TTL-cleanup deadlock"
+ "Persist for store (%{public}@, %{public}@) skipped — watchdog fired before FBF block could run"
+ "Persist for store (%{public}@, %{public}@) was interrupted by watchdog; inner err=%@"
+ "Persist watchdog fired for store (%{public}@, %{public}@) — interrupting in-flight SQLite operation"
+ "com.apple.feedbacklogger.watchdog"
+ "v16@?0@\"NSError\"8"
```
