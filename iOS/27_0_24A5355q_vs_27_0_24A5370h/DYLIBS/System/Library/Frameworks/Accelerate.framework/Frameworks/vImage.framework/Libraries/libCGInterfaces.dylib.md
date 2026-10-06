## libCGInterfaces.dylib

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/Libraries/libCGInterfaces.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x280` | `0x278` | **`-0x8`** |
| `__TEXT.__text` | `0x14380` | `0x14384` | **`+0x4`** |

### Other Changes

```text
Functions:
~ ___GetColorspaceTransformsWithTransformWithCGColorConversionInfo_block_invoke_2 : 680 -> 672
~ __vImageCGImageFormat_IsEqual : 456 -> 472
~ __vImageBuffer_InitWithCGImage : 3676 -> 3672
~ _DestroyTRCStep : 104 -> 120
~ __vImageCreateCGImageFromBuffer : 3316 -> 3304
~ _GetColorspaceTransformsWithTransform : 7968 -> 8076
~ _vImageCopyImageBlockSet : 2644 -> 2620
~ ___GetColorspaceTransformsWithTransformWithCGColorConversionInfo_block_invoke_4 : 832 -> 828
~ _InitICCTextDescription : 396 -> 404
~ _vImageMaskAlpha_Chunky8 : 216 -> 212
~ _vImageMaskAlpha_Chunky16U : 224 -> 220
~ _vImageMaskAlpha_Chunky16Q12 : 212 -> 208
~ _vImageMaskAlpha_ChunkyF : 204 -> 200
~ _GetImageWithBitmapContext : 2492 -> 2484
~ _MatrixInverse_3x3 : 540 -> 536
~ _DoConvert_MatrixStep : 752 -> 784
~ _DoConvert_Parameter : 236 -> 248
~ _DoConvert_TRCs : 136 -> 132
~ _DoTRC4 : 640 -> 632
~ _DoTRCTable : 536 -> 528
~ _DoTRC_PQ_OETF : 332 -> 328
~ _DoTRC_HLG_EOTF : 436 -> 432
~ _DoTRC_HLG_OETF : 396 -> 400
~ _DoTRCParametricInv709_1886_EOTF : 460 -> 468
~ _Print_Parameter : 472 -> 460
~ _PrintTRCStep : 1360 -> 1380
~ _DoConvert_LUT : 308 -> 296
~ _lerp : 404 -> 380
~ _Print_LUTStep : 400 -> 396
~ _DoConvert_LUT1D : 268 -> 260
~ _Print_LUT1D : 344 -> 340
~ _DoConvert_LuminanceScaling : 560 -> 540
~ _DoConvert_HLGSceneReferredMapping : 548 -> 520
~ _DoConvert_PQToneMapping : 712 -> 684
~ _DoConvert_LUTStep : 1192 -> 1204
~ _vImageCVImageFormat_Equal : 764 -> 772
~ _CVImageFormat_CopyChannelDescription : 184 -> 192
```
