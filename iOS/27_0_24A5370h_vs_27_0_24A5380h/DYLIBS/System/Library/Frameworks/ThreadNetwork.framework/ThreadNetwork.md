## ThreadNetwork

> `/System/Library/Frameworks/ThreadNetwork.framework/ThreadNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x140` | `0xa0` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x280` | `0x320` | **`+0xa0`** |
| `__TEXT.__text` | `0xe82c` | `0xe890` | **`+0x64`** |
| `__TEXT.__cstring` | `0x1689` | `0x16c2` | **`+0x39`** |
| `__DATA_CONST.__objc_selrefs` | `0x7a0` | `0x7a8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd50` | `0xd58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3a8` | `0x3b0` | **`+0x8`** |

### Other Changes

```diff

-434.0.1.0.0
+436.0.1.0.0

-  Functions: 358
-  Symbols:   678
-  CStrings:  211
+  Functions: 359
+  Symbols:   679
+  CStrings:  212
Symbols:
+ -[THClient initCommonForThreadradiodDataset]
+ GCC_except_table30
+ GCC_except_table38
+ GCC_except_table41
+ GCC_except_table44
+ GCC_except_table47
+ GCC_except_table55
+ GCC_except_table58
+ GCC_except_table64
+ GCC_except_table7
- GCC_except_table29
- GCC_except_table36
- GCC_except_table40
- GCC_except_table43
- GCC_except_table46
- GCC_except_table54
- GCC_except_table57
- GCC_except_table6
- GCC_except_table63
CStrings:
+ "CTCS XPC Client Thread Safe Property Queue (RCP Dataset)"
+ "thclient"
+ "thserver"
- "THClient"
- "THServer"
```
