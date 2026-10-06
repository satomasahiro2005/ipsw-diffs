## ProxCardKit

> `/System/Library/PrivateFrameworks/ProxCardKit.framework/ProxCardKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1db38` | `0x1dcec` | **`+0x1b4`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3f8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2d90` | `0x2da8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x300` | `0x308` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fa8` | `0x1fb0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x808` | `0x810` | **`+0x8`** |

### Other Changes

```diff

-2122.10.2.2.1
+2124.10.2.2.2

-  Functions: 718
-  Symbols:   1737
+  Functions: 720
+  Symbols:   1742
Symbols:
+ -[PRXCardContentWrapperView dealloc]
+ -[PRXCardContentWrapperView observeValueForKeyPath:ofObject:change:context:]
+ _NSKeyValueChangeNewKey
+ _NSKeyValueChangeOldKey
+ _PRXCardContentWrapperViewScrollViewContentSizeContext
Functions:
~ -[PRXCardContentWrapperView initWithContentView:] : 4184 -> 4216
+ -[PRXCardContentWrapperView dealloc]
+ -[PRXCardContentWrapperView observeValueForKeyPath:ofObject:change:context:]
~ -[UITraitCollection(ProxCardKit) prx_cardContainerLayoutMargins] : 128 -> 124
~ _PRXCardContainerDefaultLayoutMargins : 60 -> 56
```
