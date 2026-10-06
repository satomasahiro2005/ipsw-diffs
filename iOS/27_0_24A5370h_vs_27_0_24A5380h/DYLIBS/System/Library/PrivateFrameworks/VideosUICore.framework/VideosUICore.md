## VideosUICore

> `/System/Library/PrivateFrameworks/VideosUICore.framework/VideosUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35218` | `0x35308` | **`+0xf0`** |
| `__DATA.__bss` | `0x121` | `0xd1` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0x230` | `0x280` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x854` | `0x884` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x6240` | `0x6260` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3421` | `0x3435` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x640` | `0x650` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c60` | `0x3c70` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1150` | `0x1160` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x5604` | `0x560c` | **`+0x8`** |

### Other Changes

```diff

-1143.0.0.0.2
+1145.0.2.0.1

-  Functions: 1872
-  Symbols:   3676
-  CStrings:  951
+  Functions: 1873
+  Symbols:   3678
+  CStrings:  952
Symbols:
+ +[VUICoreUtilities vui_runCatching:]
+ GCC_except_table46
Functions:
+ +[VUICoreUtilities vui_runCatching:]
CStrings:
+ "unknown NSException"
```
