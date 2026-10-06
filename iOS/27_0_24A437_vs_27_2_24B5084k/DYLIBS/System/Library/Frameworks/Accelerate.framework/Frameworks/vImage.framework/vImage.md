## vImage

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2aab10` | `0x293d50` | **`-0x16dc0`** |
| `__TEXT.__eh_frame` | `0x26b8` | `0x1f20` | **`-0x798`** |
| `__TEXT.__const` | `0x9a330` | `0x99ef0` | **`-0x440`** |
| `__TEXT.__cstring` | `0x6acb` | `0x6bc0` | **`+0xf5`** |
| `__TEXT.__unwind_info` | `0x2500` | `0x2428` | **`-0xd8`** |
| `__AUTH_CONST.__auth_got` | `0x330` | `0x328` | **`-0x8`** |

### Other Changes

```diff

-650.0.1.0.0
+650.40.4.0.0

-  Functions: 3446
-  Symbols:   4385
-  CStrings:  404
+  Functions: 3409
+  Symbols:   4342
+  CStrings:  406
Symbols:
- ___sme_memset
- _tbl_tile0
- _tbl_tile1
- _tbl_tile2
- _tbl_tile3
- _vHorizontal_Reflect_ARGB_8888_SME2
- _vHorizontal_Reflect_ARGB_8888_SME2_internal
- _vHorizontal_Reflect_Planar_UInt16_SME2
- _vHorizontal_Reflect_Planar_UInt16_SME2_internal
- _vHorizontal_Reflect_Planar_UInt8_SME2
- _vHorizontal_Reflect_Planar_UInt8_SME2_internal
- _vHorizontal_Scale_ARGB_8888_SME_64x16
- _vHorizontal_Scale_ARGB_8888_SME_64x16_internal
- _vHorizontal_Scale_CbCr8_SME_64x16
- _vHorizontal_Scale_CbCr8_SME_64x16_internal
- _vHorizontal_Scale_Planar_UInt8_SME_64x16
- _vHorizontal_Scale_Planar_UInt8_SME_64x16_internal
- _vRotateClockwise270Degree_ARGB8888_SME2_internal
- _vRotateClockwise270Degree_UInt16_SME2
- _vRotateClockwise270Degree_UInt16_SME2_internal
- _vRotateClockwise270Degree_UInt8_SME2
- _vRotateClockwise270Degree_UInt8_SME2_internal
- _vRotateClockwise90Degree_ARGB8888_SME2_internal
- _vRotateClockwise90Degree_UInt16_SME2
- _vRotateClockwise90Degree_UInt16_SME2_internal
- _vRotateClockwise90Degree_UInt8_SME2
- _vRotateClockwise90Degree_UInt8_SME2_internal
- _vRotate_90_ARGB_8888_270Degree_SME2
- _vRotate_90_ARGB_8888_90Degree_SME2
- _vSquareBoxPlanar8_SME2
- _vSquareBoxPlanar8ext_3x3_SME2_internal
- _vVertical_Reflect_ARGB_16S_SME2
- _vVertical_Reflect_ARGB_16U_SME2
- _vVertical_Reflect_ARGB_8888_SME2
- _vVertical_Reflect_ARGB_8888_SME2_internal
- _vVertical_Reflect_Planar_UInt8_SME2
- _vVertical_Reflect_Planar_UInt8_SME2_internal
- _vVertical_Scale_ARGB_8888_SME_64x16
- _vVertical_Scale_ARGB_8888_SME_64x16_internal
- _vVertical_Scale_CbCr8_SME_64x16
- _vVertical_Scale_CbCr8_SME_64x16_internal
- _vVertical_Scale_Planar_UInt8_SME_64x16
- _vVertical_Scale_Planar_UInt8_SME_64x16_internal
CStrings:
+ "650.40.4"
+ "kvImagePrintDiagnosticsToConsole: vImageConverter: indexed color table has more entries than srcFormat->bitsPerComponent can address."
+ "kvImagePrintDiagnosticsToConsole: vImageConverter: indexed destination color table has more than 256 entries."
- "650.0.1"
```
