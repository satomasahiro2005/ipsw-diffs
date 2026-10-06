## ACTFramework

> `/System/Library/PrivateFrameworks/ACTFramework.framework/ACTFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3532c` | `0x34e3c` | **`-0x4f0`** |
| `__AUTH_CONST.__auth_got` | `0xa08` | `0x9f0` | **`-0x18`** |
| `__TEXT.__cstring` | `0x2883` | `0x287c` | **`-0x7`** |

### Other Changes

```diff

-557.0.0.0.0
+558.0.0.0.0

-  Symbols:   961
-  CStrings:  382
+  Symbols:   958
+  CStrings:  380
Symbols:
- _CFStringCreateWithCString
- _strstr
- _sysctl
Functions:
~ sub_247f2f42c -> sub_2494da42c : 272 -> 212
~ _ABRegRegisterSlicesRobust : 1512 -> 1480
~ sub_247f33d00 -> sub_2494deca4 : 284 -> 280
~ sub_247f3421c -> sub_2494df1bc : 1280 -> 1276
~ sub_247f34724 -> sub_2494df6c0 : 956 -> 968
~ sub_247f34d48 -> sub_2494dfcf0 : 832 -> 824
~ sub_247f35088 -> sub_2494e0028 : 1468 -> 1464
~ sub_247f35644 -> sub_2494e05e0 : 328 -> 324
~ _destroyBandPassNoiseReductionContext : 184 -> 176
~ _Blending_addImage : 1468 -> 1444
~ _Blending_addImage_v2 : 1460 -> 1436
~ _getPointersFromGeometry : 92 -> 100
~ _blockyfyGeometry : 384 -> 336
~ _FastFilter_destructor : 136 -> 132
~ _FIR1DFilter_constructor : 212 -> 220
~ _FIR1DFilter_Gaussian : 336 -> 340
~ _normalizeMinMax : 236 -> 232
~ _initMeanStdTable : 96 -> 112
~ _ACT_CopyDefaultConfigurationForPanorama : 676 -> 508
~ _GaussianScaler_downsample : 2792 -> 2400
~ _GaussianScaler_uint16_downsample : 2744 -> 2340
~ _histogramCalculation : 204 -> 200
~ _getBlackPointOfChannel : 300 -> 296
~ _FlareDetector_flareProbability : 64 -> 60
~ _FlareDetector_avgFlareProbability : 148 -> 144
~ _registrationThread : 1940 -> 1936
~ sub_247f43d84 -> sub_2494ee8f8 : 384 -> 396
~ sub_247f44598 -> sub_2494ef118 : 196 -> 192
~ sub_247f44a3c -> sub_2494ef5b8 : 628 -> 640
~ sub_247f45d28 -> sub_2494f08b0 : 436 -> 456
~ sub_247f45eec -> sub_2494f0a88 : 268 -> 264
~ sub_247f476e8 -> sub_2494f2280 : 72 -> 80
~ sub_247f47730 -> sub_2494f22d0 : 72 -> 80
~ _printHomography : 172 -> 168
~ _scaleHomography : 240 -> 232
~ _convertCoordMetalToLKT : 308 -> 300
~ _convertCoordLKTToMetal : 312 -> 304
~ _PixelShuffler_setOptions : 520 -> 512
~ _PixelShuffler_yuv420ExposureMap : 4320 -> 4208
~ _initProjectionContext : 668 -> 688
~ _computeIntegralImages : 396 -> 424
~ _projectionColsFromIntegralImage : 376 -> 392
~ _projectionRowsFromIntegralImage : 480 -> 496
~ _smoothSignature : 224 -> 200
~ sub_247f52b70 -> sub_2494fd6bc : 104 -> 100
~ _TUPrintTiming : 1116 -> 1120
~ _Stitcher_Alpha_constructor : 228 -> 216
~ _Stitcher_Alpha_pasteImageToReference : 588 -> 580
~ _Stitcher_SceneCut_findVerticalSeam_orig : 600 -> 616
~ _Stitcher_SceneCut_findVerticalSeam_NEON : 396 -> 388
~ _Stitcher_SceneCut_calculateCostImage_Yuv : 712 -> 676
~ _Stitcher_SceneCut_setStraightVerticalSeam : 152 -> 144
~ _Stitcher_SceneCut_calculateCostImage_Y : 360 -> 324
~ _Stitcher_SceneCut_blendToReferencePoisson_NoExposureDifference : 1364 -> 1356
~ _Stitcher_SceneCut_blendToReferencePoisson : 1552 -> 1684
~ _Stitcher_SceneCut_blendToReference : 716 -> 728
~ _Stitcher_SceneCut_constructor : 1692 -> 1660
~ _Stitcher_SceneCut_setDefaults : 1272 -> 1268
~ _Stitcher_SceneCut_minOverlapWidth : 144 -> 140
~ _Stitcher_SceneCut_findVerticalSeam_orig_v2 : 600 -> 616
~ _Stitcher_SceneCut_findVerticalSeam_v2_NEON : 396 -> 388
~ _Stitcher_SceneCut_calculateCostImage_Yuv_v2 : 712 -> 676
~ _Stitcher_SceneCut_setStraightVerticalSeam_v2 : 152 -> 144
~ _Stitcher_SceneCut_calculateCostImage_Y_v2 : 360 -> 324
~ _Stitcher_SceneCut_blendToReferencePoisson_NoExposureDifference_v2 : 1472 -> 1456
~ _Stitcher_SceneCut_blendToReferencePoisson_v2 : 1828 -> 1872
~ _Stitcher_SceneCut_blendToReference_v2 : 716 -> 728
~ _Stitcher_SceneCut_constructor_v2 : 1692 -> 1660
~ _Stitcher_SceneCut_setDefaults_v2 : 1272 -> 1268
~ _Stitcher_SceneCut_minOverlapWidth_v2 : 144 -> 140
~ sub_247f5b314 -> sub_249505e1c : 388 -> 400
~ sub_247f5bcb0 -> sub_2495067c4 : 1252 -> 1228
~ sub_247f5c8b0 -> sub_2495073ac : 404 -> 432
~ sub_247f5ca44 -> sub_24950755c : 664 -> 644
~ sub_247f5ec88 -> sub_24950978c : 868 -> 884
~ sub_247f5f2f0 -> sub_249509e04 : 732 -> 728
CStrings:
- "AP"
- "DEV"
```
