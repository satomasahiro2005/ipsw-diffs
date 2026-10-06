## HearingCore

> `/System/Library/PrivateFrameworks/HearingCore.framework/HearingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f90` | `0x844c` | **`+0x4bc`** |
| `__TEXT.__oslogstring` | `0x707` | `0x7f0` | **`+0xe9`** |
| `__DATA_CONST.__const` | `0x398` | `0x3f8` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x5a` | **`+0x5a`** |
| `__TEXT.__cstring` | `0xb5b` | `0xb79` | **`+0x1e`** |
| `__TEXT.__gcc_except_tab` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x988` | `0x9a0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x308` | `0x320` | **`+0x18`** |
| `__DATA.__bss` | `0x149` | `0x160` | **`+0x17`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x838` | `0x848` | **`+0x10`** |

### Other Changes

```diff

-530.0.0.0.0
+534.0.0.0.0

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 247
-  Symbols:   641
-  CStrings:  168
+  Functions: 251
+  Symbols:   658
+  CStrings:  174
Symbols:
+ -[HCDatabaseManager excludeStoreFromCloudBackupIfNeeded:]
+ -[HCDatabaseManager shouldExcludeStoreFromCloudBackup]
+ GCC_except_table235
+ GCC_except_table249
+ _CFURLSetResourcePropertyForKey
+ _SetupAssistantLibraryCore.frameworkLibrary
+ ___SetupAssistantLibraryCore_block_invoke
+ ___block_descriptor_40_e5_v8?0l
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_48_e8_32s40s_e50_v24?0"NSPersistentStoreDescription"8"NSError"16ls32l8s40l8
+ ___getBYSetupAssistantNeedsToRunSymbolLoc_block_invoke
+ __kCFURLIsExcludedFromCloudBackupKey
+ __sl_dlopen
+ _abort_report_np
+ _audit_stringSetupAssistant
+ _dlerror
+ _dlsym
+ _getBYSetupAssistantNeedsToRunSymbolLoc.ptr
+ _kCFBooleanTrue
- GCC_except_table245
- ___block_descriptor_40_e8_32s_e50_v24?0"NSPersistentStoreDescription"8"NSError"16ls32l8
CStrings:
+ "%s"
+ "BYSetupAssistantNeedsToRun"
+ "Database Manager: Excluded store from iCloud Backup: %@"
+ "Database Manager: Failed to exclude store from iCloud Backup: %@ error: %@"
+ "Database Manager: Setup Assistant still needs to run, deferring iCloud Backup exclusion for store: %@"
+ "softlink:r:path:/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant"
```
