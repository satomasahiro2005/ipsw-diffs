## BannerKit

> `/System/Library/PrivateFrameworks/BannerKit.framework/BannerKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d77c` | `0x2d8c8` | **`+0x14c`** |
| `__AUTH.__objc_data` | `0xfa0` | `0xf50` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f68` | `0x1f90` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3d2c` | `0x3d44` | **`+0x18`** |
| `__DATA.__bss` | `0x60` | `0x50` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xfb0` | `0xfb8` | **`+0x8`** |

### Other Changes

```diff

-167.0.0.0.0
+168.0.0.0.0

-  Functions: 1140
-  Symbols:   2362
+  Functions: 1142
+  Symbols:   2366
Symbols:
+ -[UIView(BannerKitAdditions) bn_frameIgnoringTransform]
+ -[UIView(BannerKitAdditions) bn_setFrameRespectingTransform:]
+ _CGRectGetMidX
+ _CGRectGetMidY
```
