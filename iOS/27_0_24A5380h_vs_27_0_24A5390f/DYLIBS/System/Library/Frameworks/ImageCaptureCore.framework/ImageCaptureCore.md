## ImageCaptureCore

> `/System/Library/Frameworks/ImageCaptureCore.framework/ImageCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x3460` | `0x3580` | **`+0x120`** |
| `__TEXT.__text` | `0x2cb38` | `0x2cb9c` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x29c4` | `0x29ec` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d10` | `0x1d20` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa10` | `0xa18` | **`+0x8`** |

### Other Changes

```diff

-2114.0.0.0.0
+2116.0.0.0.0

-  Functions: 1026
-  Symbols:   1686
+  Functions: 1027
+  Symbols:   1689
Symbols:
+ -[ICCameraDevice deliveredObjectCount]
+ GCC_except_table116
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_ICMediaItemProtocol
+ __OBJC_$_PROTOCOL_REFS_ICMediaItemProtocol
- GCC_except_table115
Functions:
+ -[ICCameraDevice deliveredObjectCount]
~ -[ICCameraDevice updateContentCatalogPercentCompleted] : 324 -> 288
~ -[ICCameraDevice filesOfType:] : 344 -> 336
~ -[ICCameraDevice containsRestrictedStorage] : 340 -> 332
~ -[ICCameraDevice addMediaFiles:] : 368 -> 392
~ -[ICCameraDevice removeItems:] : 748 -> 672
~ ___60-[ICCameraDevice requestCloseSessionWithOptions:completion:]_block_invoke_2 : 464 -> 480
~ -[ICCameraDevice removeFolder:] : 136 -> 156
```
