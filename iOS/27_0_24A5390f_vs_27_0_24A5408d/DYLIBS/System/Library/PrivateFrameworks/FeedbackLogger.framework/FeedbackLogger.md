## FeedbackLogger

> `/System/Library/PrivateFrameworks/FeedbackLogger.framework/FeedbackLogger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d25c` | `0x1d750` | **`+0x4f4`** |
| `__TEXT.__oslogstring` | `0x1cfe` | `0x1dd7` | **`+0xd9`** |
| `__TEXT.__unwind_info` | `0xa30` | `0xa80` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x260` | `0x2a4` | **`+0x44`** |
| `__AUTH_CONST.__auth_got` | `0x880` | `0x8a8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x428` | `0x450` | **`+0x28`** |
| `__TEXT.__const` | `0x14a0` | `0x14c0` | **`+0x20`** |

### Other Changes

```diff

-3600.56.21.0.0
+3600.56.26.0.0

-  Functions: 926
-  Symbols:   1040
-  CStrings:  340
+  Functions: 929
+  Symbols:   1047
+  CStrings:  344
Symbols:
+ GCC_except_table105
+ GCC_except_table107
+ GCC_except_table122
+ GCC_except_table183
+ GCC_except_table252
+ GCC_except_table277
+ GCC_except_table351
+ GCC_except_table92
+ ___block_descriptor_112_e8_32s40s48s56s64s72bs80bs88r96r_e5_v8?0lr88l8s32l8s40l8s48l8s56l8r96l8s72l8s64l8s80l8
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_88_e8_32s40s48bs56r64w_e5_v8?0lr56l8w64l8s32l8s40l8s48l8
+ __os_log_debug_impl
+ _clock_gettime_nsec_np
+ _dispatch_queue_get_label
+ _objc_moveWeak
+ _objc_storeWeak
- GCC_except_table102
- GCC_except_table104
- GCC_except_table119
- GCC_except_table180
- GCC_except_table249
- GCC_except_table274
- GCC_except_table348
- ___block_descriptor_104_e8_32s40s48s56s64s72bs80bs88r96r_e5_v8?0lr88l8s32l8s40l8s48l8s56l8r96l8s72l8s64l8s80l8
- ___block_descriptor_80_e8_32s40s48bs56r64w_e5_v8?0lr56l8w64l8s32l8s40l8s48l8
CStrings:
+ "Persist for store (%{public}@, %{public}@) ran in %.1fms err=%{public}@"
+ "PersistFlush"
+ "SQLite close connection failed: %d (queue=%{public}s, %.1fms, store=%{public}@)"
+ "SQLite connection closed on queue=%{public}s in %.1fms (store=%{public}@)"
+ "WatchdogFire"
- "SQLite close connection failed: %d"
```
