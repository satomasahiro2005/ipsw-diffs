## SpaceAttribution

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/SpaceAttribution`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13810` | `0x139c0` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x1ec8` | `0x1ef8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x6d0` | `0x6f8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1420` | `0x1440` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x14b0` | `0x14d0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xe08` | `0xe20` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1367` | `0x1372` | **`+0xb`** |
| `__TEXT.__unwind_info` | `0x650` | `0x658` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x140` | `0x144` | **`+0x4`** |

### Other Changes

```diff

-499.40.3.0.0
+499.40.4.0.0

-  Functions: 598
-  Symbols:   966
-  CStrings:  328
+  Functions: 601
+  Symbols:   971
+  CStrings:  329
Symbols:
+ -[SAAppSizerResults addToVCCDetails:key:]
+ -[SAAppSizerResults setVccDetails:]
+ -[SAAppSizerResults vccDetails]
+ GCC_except_table102
+ GCC_except_table106
+ GCC_except_table113
+ _OBJC_IVAR_$_SAAppSizerResults._vccDetails
- GCC_except_table105
- GCC_except_table112
Functions:
~ -[SAAppSizerResults init] : 340 -> 360
+ -[SAAppSizerResults addToVCCDetails:key:]
~ -[SAAppSizerResults encodeWithCoder:] : 628 -> 648
~ -[SAAppSizerResults initWithCoder:] : 1940 -> 2044
+ -[SAAppSizerResults zeroSizeApps]
+ -[SAAppSizerResults setTotalPurgeableDataSize:]
~ -[SAAppSizerResults .cxx_destruct] : 248 -> 260
CStrings:
+ "vccDetails"
```
