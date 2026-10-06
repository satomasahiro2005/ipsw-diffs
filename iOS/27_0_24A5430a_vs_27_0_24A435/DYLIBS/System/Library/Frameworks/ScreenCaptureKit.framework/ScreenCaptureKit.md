## ScreenCaptureKit

> `/System/Library/Frameworks/ScreenCaptureKit.framework/ScreenCaptureKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36c90` | `0x36fac` | **`+0x31c`** |
| `__AUTH_CONST.__const` | `0x278` | `0x298` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xd00` | `0xd20` | **`+0x20`** |
| `__DATA.__bss` | `0xa8` | `0xb8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6c8` | `0x6d0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x22f8` | `0x2300` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x3864` | `0x386c` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1451
-  Symbols:   2566
+  Functions: 1456
+  Symbols:   2572
Symbols:
+ -[SCContentFilter currentApplicationWindowScene]
+ _MGGetProductType
+ _RPCachedProductType
+ _RPCachedProductType.cachedType
+ _RPCachedProductType.onceToken
+ ___RPCachedProductType_block_invoke
```
