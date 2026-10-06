## Seeding

> `/System/Library/PrivateFrameworks/Seeding.framework/Seeding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d3b8` | `0x1d62c` | **`+0x274`** |
| `__TEXT.__gcc_except_tab` | `0x540` | `0x620` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x31e2` | `0x3262` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x2c30` | `0x2c60` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x850` | `0x878` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x16a4` | `0x16c4` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1170` | `0x1180` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc0` | `0xc4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-129.0.0.0.0
+130.0.0.0.0

-  Functions: 699
-  Symbols:   1147
-  CStrings:  600
+  Functions: 703
+  Symbols:   1152
+  CStrings:  601
Symbols:
+ -[SDBetaManager cacheLockToken]
+ -[SDBetaManager init]
+ -[SDBetaManager setCacheLockToken:]
+ GCC_except_table21
+ GCC_except_table28
+ GCC_except_table33
+ GCC_except_table79
+ GCC_except_table82
+ GCC_except_table97
+ _OBJC_IVAR_$_SDBetaManager._cacheLockToken
- GCC_except_table20
- GCC_except_table27
- GCC_except_table78
- GCC_except_table81
- GCC_except_table96
Functions:
+ -[SDBetaManager init]
~ -[SDBetaManager invalidateCache] : 160 -> 212
~ -[SDBetaManager isCacheValidForPlatforms:withMDMConfigurationDate:] : 604 -> 704
~ -[SDBetaManager _queryProgramsForSystemAccountsWithPlatforms:disableBuildPrefixMatching:language:completion:] : 2376 -> 2520
~ -[SDBetaManager cachePrograms:forPlatforms:] : 216 -> 272
~ -[SDBetaManager availableBetaProgramsForPlatforms:] : 412 -> 484
+ -[SDBetaManager cacheLockToken]
+ -[SDBetaManager postMigrationTasks]
~ -[SDBetaManager .cxx_destruct] : 80 -> 92
+ -[SDBetaManager _queryProgramsForSystemAccountsWithPlatforms:disableBuildPrefixMatching:language:completion:].cold.4
CStrings:
+ "Program cache was valid at check but empty at read for platforms [%ld]; a concurrent invalidate/reset raced the validity check."
```
