## ReplayKit

> `/System/Library/Frameworks/ReplayKit.framework/ReplayKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x3630` | `0x3648` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2130` | `0x2138` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbd0` | `0xbd8` | **`+0x8`** |
| `__TEXT.__text` | `0x36460` | `0x36464` | **`+0x4`** |

### Other Changes

```diff

-740.53.1.0.0
+740.57.1.0.0

-  Functions: 1409
-  Symbols:   2226
+  Functions: 1410
+  Symbols:   2228
Symbols:
+ +[RPPipViewController deviceOrientationForInterfaceOrientation:fallback:]
+ __OBJC_$_CLASS_METHODS_RPPipViewController
Functions:
~ ___48-[RPControlCenterClient setUpFrontBoardServices]_block_invoke.85 : 120 -> 108
+ +[RPPipViewController deviceOrientationForInterfaceOrientation:fallback:]
```
