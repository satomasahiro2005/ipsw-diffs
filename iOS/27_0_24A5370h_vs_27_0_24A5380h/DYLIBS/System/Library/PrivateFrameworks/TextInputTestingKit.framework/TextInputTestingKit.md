## TextInputTestingKit

> `/System/Library/PrivateFrameworks/TextInputTestingKit.framework/TextInputTestingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x544b8` | `0x54514` | **`+0x5c`** |
| `__DATA_CONST.__got` | `0x418` | `0x460` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0xb2b0` | `0xb2e0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x5e64` | `0x5e7c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3728` | `0x3738` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x16d8` | `0x16d0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x788` | `0x78c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3557.15.100.0.0
+3559.100.0.0.0

-  Functions: 1923
-  Symbols:   4153
+  Functions: 1925
+  Symbols:   4156
Symbols:
+ -[ACTKeyboardController deferCandidateGeneration]
+ -[ACTKeyboardController setDeferCandidateGeneration:]
+ GCC_except_table1777
+ GCC_except_table1781
+ GCC_except_table1798
+ GCC_except_table1821
+ GCC_except_table1834
+ GCC_except_table1837
+ GCC_except_table1851
+ GCC_except_table1882
+ _OBJC_IVAR_$_ACTKeyboardController._deferCandidateGeneration
- GCC_except_table1775
- GCC_except_table1779
- GCC_except_table1796
- GCC_except_table1819
- GCC_except_table1832
- GCC_except_table1835
- GCC_except_table1849
- GCC_except_table1878
CStrings:
+ "bad length in yy_scan_bytes()"
- "bad buffer in yy_scan_bytes()"
```
