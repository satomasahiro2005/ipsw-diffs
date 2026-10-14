## VoiceTriggerUI

> `/System/Library/PrivateFrameworks/VoiceTriggerUI.framework/VoiceTriggerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ca90` | `0x6cfe0` | **`+0x550`** |
| `__DATA.__data` | `0x16b8` | `0x1718` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xa40` | `0xa88` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x7798` | `0x77d8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x18f8` | `0x1920` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x4cfc` | `0x4d14` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3438` | `0x3448` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x608` | `0x610` | **`+0x8`** |

### Other Changes

```diff

-3605.7.1.0.0
+3605.8.2.0.0

-  Functions: 2413
-  Symbols:   3293
+  Functions: 2428
+  Symbols:   3297
Symbols:
+ -[VTUIPagedLabel _restingContentOffset]
+ -[VTUIPagedLabel layoutSubviews]
+ _OBJC_IVAR_$_VTUIPagedLabel._isSliding
+ _OBJC_IVAR_$_VTUIPagedLabel._slideGeneration
+ ___block_descriptor_64_e8_32s40s48bs_e8_v12?0B8ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48bs_e8_v12?0B8ls32l8s40l8s48l8
```
