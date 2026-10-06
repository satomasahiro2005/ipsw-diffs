## Metal

> `/System/Library/Frameworks/Metal.framework/Metal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e8758` | `0x1e87cc` | **`+0x74`** |
| `__TEXT.__cstring` | `0x2378c` | `0x237a7` | **`+0x1b`** |
| `__DATA.__bss` | `0x37c` | `0x38c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xc3bc` | `0xc3c8` | **`+0xc`** |

### Other Changes

```diff

-382.5.3.0.0
+382.5.4.0.0

-  Symbols:   22582
-  CStrings:  4606
+  Symbols:   22584
+  CStrings:  4607
Symbols:
+ __ZGVZN18MTLCompilerFSCache8openSyncEvE20sShaderCacheReadOnly
+ __ZZN18MTLCompilerFSCache8openSyncEvE20sShaderCacheReadOnly
Functions:
~ __ZN18MTLCompilerFSCache8openSyncEv : 916 -> 1032
CStrings:
+ "01:16:28"
+ "MTL_SHADER_CACHE_READ_ONLY"
+ "Sep  1 2026"
+ "Sep  1 2026 01:16:28"
- "22:27:50"
- "Aug 10 2026"
- "Aug 10 2026 22:27:50"
```
