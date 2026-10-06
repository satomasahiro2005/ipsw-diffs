## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/CoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe6104` | `0xe6420` | **`+0x31c`** |
| `__TEXT.__cstring` | `0x25d27` | `0x25f71` | **`+0x24a`** |
| `__AUTH_CONST.__cfstring` | `0x12540` | `0x12580` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x3660` | `0x3680` | **`+0x20`** |
| `__DATA.__bss` | `0x7b8` | `0x7c8` | **`+0x10`** |

### Other Changes

```diff

-1010.0.0.0.0
+1011.2.0.0.0

-  Functions: 5828
-  Symbols:   9208
-  CStrings:  5504
+  Functions: 5830
+  Symbols:   9211
+  CStrings:  5513
Symbols:
+ _____preferredLocalization_block_invoke
+ ___preferredLocalization.__preferredLocalizationCache
+ ___preferredLocalization.__preferredLocalizationOnce
Functions:
~ __ReadFreeList : 472 -> 420
~ _OUTLINED_FUNCTION_1 : 24 -> 44
~ -[CUICatalog _setPreferredLocalization:] : 400 -> 600
~ -[_CUIThemePixelRendition _initWithCSIHeader:version:] : 3084 -> 3160
~ -[_CUIThemePixelRendition newImageFromCSIDataSlice:ofBitmap:usingColorspace:] : 1776 -> 1832
~ -[_CSIRenditionBlockData expandCSIBitmapData:fromSlice:makeReadOnly:] : 1708 -> 1716
~ _CUIUncompressDeepmap2ImageData : 1032 -> 1040
~ -[CUIVectorGlyphLayerDrawAttachmentStore initFromSVGString:attachmentData:] : 1316 -> 1308
~ -[CUIVectorGlyphLayerDrawAttachmentStore computeCapacity:numAttachments:withScanner:usingAttachmentDelimiter:fieldDelimiter:digits:] : 388 -> 392
~ _pk_decompressData : 248 -> 456
~ ___decompressRLE8 : 300 -> 352
~ ___decompressRLE16 : 296 -> 352
~ ___decompressRLE32 : 296 -> 360
+ _____preferredLocalization_block_invoke
+ -[CUICatalog _vibrantColorMatrixBrightnessSaturationForColor:saturation:brightness:].cold.1
CStrings:
+ "%@:%@"
+ "CoreUI: CSI bitmap data starts past the end of the rendition data"
+ "CoreUI: CSI image index %u (offset %u) is outside the rendition data: '%@'"
+ "CoreUI: Invalid chunk rows of %lu in image of height %lu (rows already decoded: %lu)"
+ "CoreUI: raw image slice needs %zu bytes at offset %zu but only %zu bytes of bitmap data are available (rowbytes %zu)"
+ "com.apple.coreui-preferred-localization-cache"
+ "decompressData: %zu byte block too small to hold the row index for rows %d..%d\n"
+ "decompressData: invalid region %d,%d %dx%d\n"
+ "decompressData: row %d offset %u lies outside the %zu byte block\n"
+ "decompressData: truncated scanline %d in the %zu byte block\n"
- "_ReadFreeList: tring to read count of freelist table."
```
