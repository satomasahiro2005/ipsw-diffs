## Email

> `/System/Library/PrivateFrameworks/Email.framework/Email`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6ea0` | `0xd72c4` | **`+0x424`** |
| `__TEXT.__gcc_except_tab` | `0x1ae48` | `0x1aef4` | **`+0xac`** |
| `__AUTH_CONST.__cfstring` | `0xa420` | `0xa480` | **`+0x60`** |
| `__TEXT.__cstring` | `0xc1df` | `0xc21f` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x1e40` | `0x1e60` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8140` | `0x8160` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xd02c` | `0xd044` | **`+0x18`** |
| `__DATA.__bss` | `0x23c0` | `0x23d0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x45a8` | `0x45b8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6270` | `0x6280` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x16e08` | `0x16e10` | **`+0x8`** |

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  Functions: 5136
-  Symbols:   8936
-  CStrings:  2147
+  Functions: 5140
+  Symbols:   8943
+  CStrings:  2150
Symbols:
+ +[EMQuery _sortDescriptorsByNormalizingLegacyKeyPaths:]
+ -[EMDiagnosticInfoGatherer databaseStatisticsForcingRefresh:completionHandler:]
+ _EMPersistenceStatisticsKeyCalculatedAt
+ _EMUserDefaultNeverCollectIndexingDiagnostics
+ ___55+[EMQuery _sortDescriptorsByNormalizingLegacyKeyPaths:]_block_invoke
+ __sortDescriptorsByNormalizingLegacyKeyPaths:.onceToken
+ __sortDescriptorsByNormalizingLegacyKeyPaths:.sLegacyKeyPathAliases
CStrings:
+ "NeverCollectIndexingDiagnostics"
+ "calculatedAt"
+ "searchRelevanceRank"
```
