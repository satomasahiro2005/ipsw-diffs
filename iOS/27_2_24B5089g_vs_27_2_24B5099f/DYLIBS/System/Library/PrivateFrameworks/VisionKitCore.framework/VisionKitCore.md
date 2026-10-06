## VisionKitCore

> `/System/Library/PrivateFrameworks/VisionKitCore.framework/VisionKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x43c0` | `0x4190` | **`-0x230`** |
| `__DATA_DIRTY.__objc_data` | `0x1288` | `0x14b8` | **`+0x230`** |
| `__TEXT.__text` | `0xe76a4` | `0xe7718` | **`+0x74`** |
| `__AUTH.__data` | `0x11e0` | `0x1210` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x68c0` | `0x68e0` | **`+0x20`** |
| `__DATA.__bss` | `0x1490` | `0x1470` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x110` | `0x130` | **`+0x20`** |
| `__TEXT.__cstring` | `0x829d` | `0x82bd` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1065c` | `0x10674` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x31368` | `0x31378` | **`+0x10`** |
| `__DATA.__data` | `0x2130` | `0x2140` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x98c0` | `0x98d0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4398` | `0x43a0` | **`+0x8`** |

### Other Changes

```diff

-346.0.0.0.0
+347.1.1.0.0

-  Functions: 6782
-  Symbols:   10682
-  CStrings:  1625
+  Functions: 6785
+  Symbols:   10685
+  CStrings:  1626
Symbols:
+ +[VKCInternalSettings usesGestureInputHandlingSettingsValue]
+ +[VKCInternalSettings usesGestureInputHandling]
+ _vk_overridesRequireMouseDownFallbackForGestureInput
Functions:
+ _vk_overridesRequireMouseDownFallbackForGestureInput
+ +[VKCInternalSettings usesGestureInputHandling]
+ +[VKCInternalSettings localeFreeQRSupportSettingsValue]
CStrings:
+ "usesGestureInputHandling"
```
