## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/CoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe600c` | `0xe6104` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x25cf7` | `0x25d27` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xed00` | `0xed18` | **`+0x18`** |
| `__TEXT.__const` | `0x64c8` | `0x64d8` | **`+0x10`** |

### Other Changes

```diff

-  CStrings:  5502
+  CStrings:  5504
Functions:
~ -[CUINamedRenditionInfo attributePresent:withValue:] : 1544 -> 1564
~ -[CUIThemeRendition _initializeCompositingOptionsFromCSIData:version:] : 172 -> 176
~ _CUIRenditionKeyTokenCount : 44 -> 48
~ _CUIRenditionKeySetValueForAttribute : 308 -> 316
~ _CUIValidateIdiomSubtypes : 640 -> 644
~ -[_CUIRawDataRendition _initWithCSIHeader:version:] : 356 -> 360
~ -[_CUILayerStackRendition _initWithCSIHeader:version:] : 1396 -> 1400
~ -[_CUIThemeTextureImageRendition _initWithCSIHeader:version:] : 792 -> 796
~ -[CUINamedRenditionInfo decrementValue:forAttribute:] : 3080 -> 3120
~ -[CUIThemeRendition _initalizeMetadataFromCSIData:version:] : 212 -> 216
~ -[_CUIThemeVectorGlyphRendition _initWithCSIHeader:version:] : 292 -> 296
~ -[_CUIInternalLinkRendition _initWithCSIHeader:version:] : 1644 -> 1640
~ -[_CUIThemeVectorGlyphRendition _initalizeMetadataFromCSIData:version:] : 656 -> 660
~ __dense_addFreeRange : 252 -> 256
~ -[_CUIThemeNamedColorGradientRendition _initWithCSIHeader:version:] : 792 -> 796
~ -[CUINamedRenditionInfo setAttributePresent:withValue:] : 1540 -> 1560
~ __findRemove : 1784 -> 1788
~ -[_CUIThemeColorRendition _initWithCSIHeader:version:] : 320 -> 324
~ -[_CUIThemeMultisizeImageSetRendition _initWithCSIHeader:version:] : 476 -> 480
~ -[CUIVectorGlyphMutator clipStrokeKeyframesForPath:scalars:] : 1812 -> 1800
~ -[_CUIThemeTextureRendition _initWithCSIHeader:version:] : 680 -> 684
~ -[_CUIThemeSVGRendition _initWithCSIHeader:version:] : 256 -> 260
~ -[_CUIThemePDFRendition _initWithCSIHeader:version:] : 308 -> 312
~ __ZNSt3__16vectorIdNS_9allocatorIdEEE6resizeEm : 284 -> 288
~ __ZN2RB4Path10JoinStroke9closepathEv : 1592 -> 1596
~ _compress_line_16 : 268 -> 260
~ _compress_line_32 : 264 -> 256
~ -[_CUIThemeEffectRendition _initWithCSIHeader:version:] : 200 -> 204
~ -[_CUIThemeModelSubmeshRendition _initWithCSIHeader:version:] : 1188 -> 1192
~ -[CUINamedRenditionInfo clearAttributePresent:withValue:] : 1540 -> 1560
~ -[CUINamedRenditionInfo incrementIndex:inValues:forAttribute:] : 3152 -> 3192
~ +[CUINamedRenditionInfo subtypeToIndexWithPlatform:andInput:] : 1268 -> 1288
~ -[_CUIThemeTextStyleRendition _initWithCSIHeader:version:] : 156 -> 160
~ __ZNSt3__16vectorIP23CPSDActionBaseComponentNS_9allocatorIS2_EEE6resizeEm : 284 -> 288
~ __ZN19CPSDLayerSliceImageC2ER15CPSDLayerRecordR21CPSDLayerChannelGroupR7PSDRectjjjPh : 360 -> 364
~ __ZN2RB4Path10ClipStroke9Transform17subpath_keyframesENSt3__14spanIK24CGPathClipStrokeKeyframeLm18446744073709551615EEE : 1152 -> 1148
~ -[_CUIExternalLinkRendition _initWithCSIHeader:version:] : 372 -> 376
~ _DrawNinePartImageWithOperation : 3484 -> 3476
~ -[_CUIThemeModelMeshRendition _initWithCSIHeader:version:] : 1068 -> 1072
~ -[_CUIThemeModelAssetRendition _initWithCSIHeader:version:] : 416 -> 420
~ -[_CUIRawPixelRendition _initWithCSIHeader:version:] : 1988 -> 1992
~ -[_CUIRecognitionObjectRendition _initalizeMetadataFromCSIData:version:] : 376 -> 380
~ -[_CUINameContentRendition _initWithCSIHeader:version:] : 308 -> 312
~ __ExpandBlockTable : 228 -> 232
CStrings:
+ "APPLE11"
+ "kCoreThemeFeatureSetMetalGPUFamily11"
```
