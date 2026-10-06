## ImageCaptureCore

> `/System/Library/Frameworks/ImageCaptureCore.framework/ImageCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cb14` | `0x2cb38` | **`+0x24`** |

### Other Changes

```diff

-2113.0.0.0.0
+2114.0.0.0.0
Symbols:
+ -[ICCameraFile requestOpenStreamDataAtOffset:]
+ ___46-[ICCameraFile requestOpenStreamDataAtOffset:]_block_invoke
- -[ICCameraFile requestOpenStreamData]
- ___37-[ICCameraFile requestOpenStreamData]_block_invoke
Functions:
~ ___54-[ICCameraFile requestDownloadWithOptions:completion:]_block_invoke : 3880 -> 3884
~ -[ICCameraFile requestOpenStreamData] -> -[ICCameraFile requestOpenStreamDataAtOffset:] : 344 -> 376
```
