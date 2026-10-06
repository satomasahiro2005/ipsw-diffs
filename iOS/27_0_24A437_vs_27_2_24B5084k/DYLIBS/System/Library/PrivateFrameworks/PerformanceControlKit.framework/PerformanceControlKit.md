## PerformanceControlKit

> `/System/Library/PrivateFrameworks/PerformanceControlKit.framework/PerformanceControlKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1304c` | `0x13174` | **`+0x128`** |
| `__TEXT.__gcc_except_tab` | `0x17d8` | `0x1800` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xc80` | `0xca0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xace` | `0xae6` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x684` | `0x69c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7b0` | `0x7c0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0xe40` | `0xe48` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x390` | `0x398` | **`+0x8`** |

### Other Changes

```diff

-1794.0.32.0.4
+1794.40.23.0.0

-  Functions: 316
-  Symbols:   815
-  CStrings:  128
+  Functions: 317
+  Symbols:   816
+  CStrings:  129
Symbols:
+ -[CLPCPolicyClient setCLPCTrialID:error:]
Functions:
+ -[CLPCPolicyClient setCLPCTrialID:error:]
CStrings:
+ "Failed to set trial ID."
```
