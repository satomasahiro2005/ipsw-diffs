## TipKitCore

> `/System/Library/PrivateFrameworks/TipKitCore.framework/TipKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbbb28` | `0xbd1ac` | **`+0x1684`** |
| `__AUTH_CONST.__const` | `0x5270` | `0x5390` | **`+0x120`** |
| `__DATA.__data` | `0x10e8` | `0x11e0` | **`+0xf8`** |
| `__TEXT.__const` | `0xb0c8` | `0xb1a8` | **`+0xe0`** |
| `__AUTH.__data` | `0x288` | `0x1e8` | **`-0xa0`** |
| `__TEXT.__swift5_typeref` | `0x352c` | `0x35cc` | **`+0xa0`** |
| `__DATA.__bss` | `0x7fd0` | `0x7f50` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x6980` | `0x6a00` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0x2682` | `0x2700` | **`+0x7e`** |
| `__TEXT.__swift5_capture` | `0x5a8` | `0x61c` | **`+0x74`** |
| `__AUTH.__objc_data` | `0xd8` | `0x128` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3d28` | `0x3d70` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x1926` | `0x1966` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x22dc` | `0x2318` | **`+0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x1538` | `0x1570` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x1a68` | `0x1a9c` | **`+0x34`** |
| `__TEXT.__eh_frame` | `0x73c0` | `0x73d8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1500` | `0x1510` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x278` | `0x288` | **`+0x10`** |
| `__TEXT.__cstring` | `0x33e2` | `0x33f2` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x978` | `0x980` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x258` | `0x260` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x168` | `0x16c` | **`+0x4`** |

### Other Changes

```diff

-126.0.0.0.0
+127.0.0.0.0

-  Functions: 6254
-  Symbols:   1573
-  CStrings:  362
+  Functions: 6297
+  Symbols:   1589
+  CStrings:  363
Symbols:
+ _OBJC_CLASS_$_NSProcessInfo
+ ___swift_memcpy7_1
+ _swift_deletedAsyncMethodErrorTu
+ _swift_retain_x1
+ _swift_task_deinitOnExecutor
+ _swift_task_immediate
+ _swift_task_isCurrentExecutorWithFlags
+ _symbolic ScSyyyYaYbcG
+ _symbolic _____SgXw 10TipKitCore13DeviceProfileC
+ _symbolic _____SgXwz_Xx 10TipKitCore13DeviceProfileC
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10TipKitCore13DeviceProfileC0G7ContentV
+ _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE 10TipKitCore13DeviceProfileC0G7ContentV
+ _symbolic _____yyyYaYbc_G ScS12ContinuationV
+ _symbolic _____yyyYaYbc_G ScS8IteratorV
+ _symbolic _____yyyYaYbc__G ScS12ContinuationV11YieldResultO
+ _symbolic _____yyyYaYbc__G ScS12ContinuationV15BufferingPolicyO
+ _symbolic y_____YbcSg 10Foundation4DataV
+ _symbolic yyYaYbc
- ___swift_memcpy6_1
- _symbolic _____ 10Foundation4DataV
CStrings:
+ "DeviceProfile monitoring plist: "
+ "TipKitCore/DeviceProfile+FileHandler.swift"
+ "XCTestConfigurationFilePath"
- "DeviceProfile loaded and monitoring at: "
- "DeviceProfile.shared will update with tipsd content: "
```
