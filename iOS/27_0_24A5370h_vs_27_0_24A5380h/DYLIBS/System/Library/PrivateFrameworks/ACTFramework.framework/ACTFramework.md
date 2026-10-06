## ACTFramework

> `/System/Library/PrivateFrameworks/ACTFramework.framework/ACTFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34e3c` | `0x34da0` | **`-0x9c`** |

### Other Changes

```diff

-558.0.0.0.0
+560.0.0.0.0
Symbols:
+ _MFGetSliceTranslation
- _MFGetMotionFilterIncrementalTranslation
Functions:
~ _ACTPostRegisterSlices : 668 -> 660
~ _Blending_addImage : 1444 -> 1476
~ _Blending_addImage_v2 : 1436 -> 1468
~ _FastFilter_HorBoxFilterAndSubsampling : 264 -> 244
~ _FlareDetector_avgFlareProbability : 144 -> 140
~ _Contrast_globalEnhance : 652 -> 636
~ _MFGetMotionFilterIncrementalTranslation -> _MFGetSliceTranslation : 144 -> 192
~ _MFRegRegisterSlices : 324 -> 328
~ _PixelShuffler_imageFlipHorizontally : 112 -> 108
~ _PixelShuffler_cropRoi : 104 -> 116
~ _PixelShuffler_cropRoi_uint16 : 112 -> 108
~ _PixelShuffler_imageTransposeRoi : 660 -> 700
~ _PixelShuffler_imageTransposeRoi_uint16 : 700 -> 664
~ _PixelShuffler_imageTranspose : 636 -> 644
~ _PixelShuffler_imageTranspose_uint16 : 648 -> 616
~ _PixelShuffler_yuv420TransposeAndFlipHorizontally : 296 -> 292
~ _PixelShuffler_yuv420ExposureMap : 4208 -> 4220
~ _Stitcher_Alpha_pasteImageToReference : 580 -> 576
~ _Stitcher_SceneCut_findVerticalSeam_orig : 616 -> 564
~ _minInRange : 60 -> 68
~ _Stitcher_SceneCut_findVerticalSeam_NEON : 388 -> 384
~ _Stitcher_SceneCut_setStraightVerticalSeam : 144 -> 152
~ _Stitcher_SceneCut_calculateFlarePerRow : 228 -> 208
~ _Stitcher_SceneCut_blendToReferencePoisson_NoExposureDifference : 1356 -> 1360
~ _Stitcher_SceneCut_blendToReferencePoisson : 1684 -> 1660
~ _Stitcher_SceneCut_blendToReference : 728 -> 700
~ _Stitcher_SceneCut_alphaBlendToReference : 568 -> 548
~ _Stitcher_SceneCut_findVerticalSeam_orig_v2 : 616 -> 564
~ _Stitcher_SceneCut_findVerticalSeam_v2_NEON : 388 -> 384
~ _Stitcher_SceneCut_setStraightVerticalSeam_v2 : 144 -> 152
~ _Stitcher_SceneCut_calculateFlarePerRow_v2 : 228 -> 208
~ _Stitcher_SceneCut_blendToReferencePoisson_NoExposureDifference_v2 : 1456 -> 1468
~ _Stitcher_SceneCut_blendToReferencePoisson_v2 : 1872 -> 1892
~ _Stitcher_SceneCut_blendToReference_v2 : 728 -> 700
~ _Stitcher_SceneCut_alphaBlendToReference_v2 : 568 -> 548
```
