## ImageCaptureDevices

> `/System/Library/PrivateFrameworks/ImageCaptureDevices.framework/ImageCaptureDevices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a380` | `0x1a4d4` | **`+0x154`** |
| `__AUTH_CONST.__objc_const` | `0x2970` | `0x29a0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1d3c` | `0x1d64` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1328` | `0x1348` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5d0` | `0x5d8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x268` | `0x26c` | **`+0x4`** |

### Other Changes

```diff

-2114.0.0.0.0
+2116.0.0.0.0

-  Functions: 667
-  Symbols:   1225
+  Functions: 670
+  Symbols:   1229
Symbols:
+ -[ICOrderedMediaSet mediaItemWithIdentifier:]
+ -[ICOrderedMediaSet mediaItemsByIdentifier]
+ -[ICOrderedMediaSet setMediaItemsByIdentifier:]
+ _OBJC_IVAR_$_ICOrderedMediaSet._mediaItemsByIdentifier
Functions:
~ -[ICOrderedMediaSet initWithTypes:] : 372 -> 392
~ -[ICOrderedMediaSet addMediaItemToIndex:] : 344 -> 404
~ -[ICOrderedMediaSet removeMediaItemFromIndex:] : 156 -> 212
~ -[ICOrderedMediaSet removeAllItems] : 288 -> 296
+ -[ICOrderedMediaSet mediaItemWithIdentifier:]
+ -[ICOrderedMediaSet mediaItemsByIdentifier]
+ -[ICOrderedMediaSet .cxx_destruct]
```
