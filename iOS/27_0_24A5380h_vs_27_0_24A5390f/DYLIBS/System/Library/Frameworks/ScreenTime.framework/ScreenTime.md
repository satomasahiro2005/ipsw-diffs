## ScreenTime

> `/System/Library/Frameworks/ScreenTime.framework/ScreenTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54ac` | `0x5888` | **`+0x3dc`** |
| `__DATA_CONST.__const` | `0x348` | `0x3e8` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0xc0` | `0x120` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x7ac` | `0x7ec` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x630` | `0x668` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0xf40` | `0xf10` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x270` | `0x2a0` | **`+0x30`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__cstring` | `0x35d` | `0x366` | **`+0x9`** |
| `__DATA_CONST.__got` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__const` | `0x80` | `0x78` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x64` | `0x60` | **`-0x4`** |

### Other Changes

```diff

-645.1.100.0.0
+649.0.0.0.0

-  Functions: 185
-  Symbols:   413
-  CStrings:  52
+  Functions: 198
+  Symbols:   431
+  CStrings:  53
Symbols:
+ +[STWebHistory _legacyConnection]
+ -[STWebHistory _deleteAllHistoryWithHasMigrated:]
+ -[STWebHistory _deleteHistoryDuringInterval:hasMigrated:]
+ -[STWebHistory _deleteHistoryForURL:hasMigrated:]
+ -[STWebHistory _fetchAllHistoryWithHasMigrated:completionHandler:]
+ -[STWebHistory _fetchHistoryDuringInterval:hasMigrated:completionHandler:]
+ __OBJC_$_CLASS_METHODS_STWebHistory
+ ___33+[STWebHistory _legacyConnection]_block_invoke
+ ___49-[STWebHistory _deleteAllHistoryWithHasMigrated:]_block_invoke
+ ___49-[STWebHistory _deleteAllHistoryWithHasMigrated:]_block_invoke_2
+ ___49-[STWebHistory _deleteHistoryForURL:hasMigrated:]_block_invoke
+ ___49-[STWebHistory _deleteHistoryForURL:hasMigrated:]_block_invoke_2
+ ___57-[STWebHistory _deleteHistoryDuringInterval:hasMigrated:]_block_invoke
+ ___57-[STWebHistory _deleteHistoryDuringInterval:hasMigrated:]_block_invoke_2
+ ___66-[STWebHistory _fetchAllHistoryWithHasMigrated:completionHandler:]_block_invoke
+ ___66-[STWebHistory _fetchAllHistoryWithHasMigrated:completionHandler:]_block_invoke_2
+ ___66-[STWebHistory _fetchAllHistoryWithHasMigrated:completionHandler:]_block_invoke_3
+ ___74-[STWebHistory _fetchHistoryDuringInterval:hasMigrated:completionHandler:]_block_invoke
+ ___74-[STWebHistory _fetchHistoryDuringInterval:hasMigrated:completionHandler:]_block_invoke_2
+ ___74-[STWebHistory _fetchHistoryDuringInterval:hasMigrated:completionHandler:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e27_v24?0"NSSet"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32s_e8_v12?0B8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v12?0B8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e8_v12?0B8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8ls32l8s40l8s48l8
+ __legacyConnection.connection
+ __legacyConnection.onceToken
- -[STWebHistory dealloc]
- -[STWebHistory xpcConnection]
- _OBJC_IVAR_$_STWebHistory._xpcConnection
- ___32-[STWebHistory deleteAllHistory]_block_invoke_2
- ___36-[STWebHistory deleteHistoryForURL:]_block_invoke_2
- ___44-[STWebHistory deleteHistoryDuringInterval:]_block_invoke_2
- ___53-[STWebHistory fetchAllHistoryWithCompletionHandler:]_block_invoke_3
- ___61-[STWebHistory fetchHistoryDuringInterval:completionHandler:]_block_invoke_3
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
CStrings:
+ "v12@?0B8"
```
