## ReplayKit

> `/System/Library/Frameworks/ReplayKit.framework/ReplayKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36464` | `0x36608` | **`+0x1a4`** |
| `__TEXT.__cstring` | `0x80eb` | `0x816a` | **`+0x7f`** |
| `__AUTH_CONST.__const` | `0xe18` | `0xe38` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3648` | `0x3658` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x66e8` | `0x66f0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2138` | `0x2140` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbd8` | `0xbe0` | **`+0x8`** |

### Other Changes

```diff

-740.57.1.0.0
+740.63.1.1.0

-  Functions: 1410
-  Symbols:   2228
-  CStrings:  1091
+  Functions: 1413
+  Symbols:   2230
+  CStrings:  1093
Symbols:
+ -[RPDaemonProxy pickerDidDismiss:forStream:isCancelled:]
+ ___56-[RPDaemonProxy pickerDidDismiss:forStream:isCancelled:]_block_invoke
CStrings:
+ "-[RPDaemonProxy pickerDidDismiss:forStream:isCancelled:]"
+ "-[RPDaemonProxy pickerDidDismiss:forStream:isCancelled:]_block_invoke"
```
