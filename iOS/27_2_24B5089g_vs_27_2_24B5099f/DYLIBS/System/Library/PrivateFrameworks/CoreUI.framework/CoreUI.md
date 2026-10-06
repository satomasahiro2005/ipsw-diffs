## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/CoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe6420` | `0xe6554` | **`+0x134`** |
| `__TEXT.__cstring` | `0x25f71` | `0x26071` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x22e0` | `0x2290` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xff0` | `0x1040` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x2c7c` | `0x2cac` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x17b8` | `0x17e0` | **`+0x28`** |
| `__DATA.__bss` | `0x7c8` | `0x7d8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x43d8` | `0x43e0` | **`+0x8`** |

### Other Changes

```diff

-1011.2.0.0.0
+1011.4.0.0.0

-  Symbols:   9211
-  CStrings:  5513
+  Symbols:   9218
+  CStrings:  5518
Symbols:
+ __ZGVZL15__CSIBVGCLocalevE7localeC
+ __ZZL15__CSIBVGCLocalevE7localeC
+ ___cxa_guard_abort
+ ___cxa_guard_acquire
+ ___cxa_guard_release
+ _newlocale
+ _snprintf_l
Functions:
~ _CUIUncompressDeepmap2ImageData : 1040 -> 1140
~ ___CUIUncompressDeepmap2ImageData_block_invoke : 276 -> 272
~ __ZN24CSIBVGNumericListDecoder11appendValueEd : 172 -> 284
~ _CUIUncompressDeepmapImageData : 1024 -> 1124
~ ___CUIUncompressDeepmapImageData_block_invoke : 220 -> 216
~ sub_1bc8de674 -> sub_1bb8c57a4 : 3340 -> 3344
~ sub_1bc8e1ba0 -> sub_1bb8c8cd4 : 244 -> 384
~ sub_1bc8e1c94 -> sub_1bb8c8e54 : 384 -> 244
CStrings:
+ "C"
+ "CoreUI: Deepmap 2.0 block length %zu is smaller than its header"
+ "CoreUI: Deepmap 2.0 compressedBytes %llu exceeds block length %zu"
+ "CoreUI: Deepmap block length %zu is smaller than its header"
+ "CoreUI: Deepmap compressedBytes %llu exceeds block length %zu"
```
