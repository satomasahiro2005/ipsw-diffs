## BiomeFoundation

> `/System/Library/PrivateFrameworks/BiomeFoundation.framework/BiomeFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3485c` | `0x34bbc` | **`+0x360`** |
| `__AUTH_CONST.__cfstring` | `0x58c0` | `0x58e0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x33a2` | `0x33c2` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x6c88` | `0x6c98` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x18c0` | `0x18d0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x50cd` | `0x50dd` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2a64` | `0x2a74` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xef0` | `0xef8` | **`+0x8`** |

### Other Changes

```diff

-250.0.0.3.0
+255.0.2.0.0

-  Functions: 1229
-  Symbols:   2200
-  CStrings:  1060
+  Functions: 1232
+  Symbols:   2203
+  CStrings:  1062
Symbols:
+ -[BMFileHandle isUnlinked]
+ -[BMFileManager removeFilesAtPaths:error:]
+ GCC_except_table22
+ GCC_except_table27
- GCC_except_table15
Functions:
~ -[BMFileManager removeFileAtPath:error:] : 880 -> 912
+ -[BMFileHandle isUnlinked]
+ -[BMFileManager removeFilesAtPaths:error:]
+ -[BMFileManager removeFilesAtPaths:error:].cold.1
CStrings:
+ "Unable to remove %{public}@: %@"
+ "paths"
```
