## ImageCaptureCore

> `/System/Library/Frameworks/ImageCaptureCore.framework/ImageCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cb9c` | `0x2cb38` | **`-0x64`** |
| `__TEXT.__objc_methlist` | `0x29ec` | `0x29dc` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d20` | `0x1d18` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xa10` | **`-0x8`** |

### Other Changes

```diff

-2116.0.0.0.0
+2118.0.0.0.0

-  Functions: 1027
-  Symbols:   1689
+  Functions: 1026
+  Symbols:   1688
Symbols:
+ GCC_except_table115
- -[ICCameraDevice deliveredObjectCount]
- GCC_except_table116
Functions:
- -[ICCameraDevice deliveredObjectCount]
~ -[ICCameraDevice updateContentCatalogPercentCompleted] : 288 -> 324
~ -[ICCameraDevice filesOfType:] : 336 -> 344
~ -[ICCameraDevice containsRestrictedStorage] : 332 -> 340
~ -[ICCameraDevice addMediaFiles:] : 392 -> 368
~ -[ICCameraDevice removeItems:] : 672 -> 748
~ ___60-[ICCameraDevice requestCloseSessionWithOptions:completion:]_block_invoke_2 : 480 -> 464
~ -[ICCameraDevice removeFolder:] : 156 -> 136
```
