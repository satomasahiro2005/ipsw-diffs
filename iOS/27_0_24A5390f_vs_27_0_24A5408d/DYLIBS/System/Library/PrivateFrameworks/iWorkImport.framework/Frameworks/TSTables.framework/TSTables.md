## TSTables

> `/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSTables.framework/TSTables`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69e488` | `0x69e8fc` | **`+0x474`** |
| `__TEXT.__gcc_except_tab` | `0x9b960` | `0x9ba20` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x45440` | `0x454d0` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x35a04` | `0x35a5c` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x2d990` | `0x2d9c8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x16250` | `0x16280` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xec60` | `0xec40` | **`-0x20`** |
| `__TEXT.__cstring` | `0x451bc` | `0x451d0` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x29ac` | `0x29bc` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1b50` | `0x1b48` | **`-0x8`** |

### Other Changes

```diff

-487.0.0.0.0
+488.0.0.0.0

+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSFundamentals.framework/TSFundamentals
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSGeometry.framework/TSGeometry

-  Functions: 36022
-  Symbols:   13345
+  Functions: 36033
+  Symbols:   13344
Symbols:
- _TSULogCat_IsCategoryEnabled
CStrings:
+ "%d is not a valid node tag, seen at offset: %lu"
- "TSTMergeOwnerDetailedLogCat"
```
