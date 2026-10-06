## DataMigration

> `/System/Library/PrivateFrameworks/DataMigration.framework/DataMigration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75e0` | `0x7824` | **`+0x244`** |
| `__TEXT.__cstring` | `0x1769` | `0x17f9` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x1060` | `0x10a0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x120` | `0x160` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x180` | **`-0x28`** |
| `__DATA.__bss` | `0x58` | `0x68` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x960` | `0x970` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x168` | `0x170` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x690` | `0x698` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d0` | `0x2d8` | **`+0x8`** |

### Other Changes

```diff

-2858.0.0.0.0
+2858.1.3.0.0

-  Functions: 244
-  Symbols:   584
-  CStrings:  171
+  Functions: 247
+  Symbols:   588
+  CStrings:  173
Symbols:
+ +[DMConnection _migrationPluginResultsAllowedClasses]
+ +[DMConnection _migrationPluginResultsFromArchivedData:error:]
+ GCC_except_table14
+ GCC_except_table21
+ _NSDebugDescriptionErrorKey
+ ___53+[DMConnection _migrationPluginResultsAllowedClasses]_block_invoke
+ __migrationPluginResultsAllowedClasses.allowedClasses
+ __migrationPluginResultsAllowedClasses.onceToken
+ _objc_autorelease
- -[DMMigrationDeferredExitManager _exitClean]
- GCC_except_table15
- GCC_except_table18
- ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
- _xpc_transaction_exit_clean
CStrings:
+ "Data migrator -migrationPluginResults: did unarchive a %@ instead of a dictionary; discarding it"
+ "cancelDeferredExitWithConnection: will end transaction"
+ "deferred exit did timeout. will end transaction"
+ "migration plugin results archive root was a %@, not a dictionary"
- "cancelDeferredExitWithConnection: will end transaction and exit"
- "deferred exit did timeout. will end transaction and exit"
```
