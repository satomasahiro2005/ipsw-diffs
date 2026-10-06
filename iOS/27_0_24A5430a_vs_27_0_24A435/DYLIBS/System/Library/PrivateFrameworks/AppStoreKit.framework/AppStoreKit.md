## AppStoreKit

> `/System/Library/PrivateFrameworks/AppStoreKit.framework/AppStoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8522d0` | `0x8527c0` | **`+0x4f0`** |
| `__AUTH_CONST.__objc_const` | `0x474b8` | `0x47598` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x6140` | `0x6178` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b20` | `0x4b30` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1c5a8` | `0x1c5b8` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 45577
-  Symbols:   12850
+  Functions: 45579
+  Symbols:   12852
Symbols:
+ +[ASKMobileGestalt isCobaltSupported]
+ -[ASKClient isCobaltSupported]
```
