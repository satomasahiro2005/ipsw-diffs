## FeedbackLogger

> `/System/Library/PrivateFrameworks/FeedbackLogger.framework/FeedbackLogger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c198` | `0x1c27c` | **`+0xe4`** |
| `__TEXT.__cstring` | `0x1fb0` | `0x2026` | **`+0x76`** |
| `__AUTH_CONST.__cfstring` | `0x8e0` | `0x920` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x116c` | `0x117c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xc28` | `0xc30` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9c0` | `0x9c8` | **`+0x8`** |

### Other Changes

```diff

-3600.53.23.1.2
+3600.56.7.0.0

-  Functions: 912
-  Symbols:   1014
-  CStrings:  330
+  Functions: 913
+  Symbols:   1015
+  CStrings:  332
Symbols:
+ -[FLSQLitePersistence(BatchManager) doBatchesHousekeepingWithLimit:]
+ GCC_except_table163
+ GCC_except_table232
+ GCC_except_table257
+ GCC_except_table331
- GCC_except_table162
- GCC_except_table231
- GCC_except_table256
- GCC_except_table330
CStrings:
+ "%s ORDER BY rowid LIMIT %ld"
+ "DELETE FROM records WHERE batchId IN (%@); DELETE FROM batchStatus WHERE batchId IN (%@);"
```
