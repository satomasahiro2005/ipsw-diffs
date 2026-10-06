## Cinematic

> `/System/Library/Frameworks/Cinematic.framework/Cinematic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13e4c` | `0x14238` | **`+0x3ec`** |
| `__AUTH_CONST.__objc_const` | `0x1df0` | `0x1ee0` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x84d` | `0x927` | **`+0xda`** |
| `__TEXT.__gcc_except_tab` | `0x200` | `0x290` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x5a0` | `0x5f0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x708` | `0x6e0` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0xe8c` | `0xeb4` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1a0` | `0x180` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb88` | `0xb78` | **`-0x10`** |
| `__TEXT.__cstring` | `0x379` | `0x369` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x838` | `0x848` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xd8` | `0xe0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x94` | `0x98` | **`+0x4`** |

### Other Changes

```diff

-556.0.0.0.1
+558.0.0.0.0

-  Functions: 747
-  Symbols:   967
-  CStrings:  79
+  Functions: 753
+  Symbols:   977
+  CStrings:  83
Symbols:
+ +[CNAssetInfo loadFromCinematicVideoTracks:requireDisparity:error:]
+ -[CNAssetInfo initWithTracks:]
+ -[CNAssetInfoTracks .cxx_destruct]
+ -[CNAssetInfoTracks cinematicDisparityTrack]
+ -[CNAssetInfoTracks cinematicMetadataTrack]
+ -[CNAssetInfoTracks cinematicVideoTrack]
+ -[CNAssetInfoTracks initWithVideoTrack:disparityTrack:metadataTrack:]
+ GCC_except_table15
+ GCC_except_table33
+ _OBJC_CLASS_$_CNAssetInfoTracks
+ _OBJC_IVAR_$_CNAssetInfo._assetInfoTracks
+ _OBJC_IVAR_$_CNAssetInfoTracks._cinematicDisparityTrack
+ _OBJC_IVAR_$_CNAssetInfoTracks._cinematicMetadataTrack
+ _OBJC_IVAR_$_CNAssetInfoTracks._cinematicVideoTrack
+ _OBJC_METACLASS_$_CNAssetInfoTracks
+ __OBJC_$_INSTANCE_METHODS_CNAssetInfoTracks
+ __OBJC_$_INSTANCE_VARIABLES_CNAssetInfoTracks
+ __OBJC_$_PROP_LIST_CNAssetInfoTracks
+ __OBJC_CLASS_RO_$_CNAssetInfoTracks
+ __OBJC_METACLASS_RO_$_CNAssetInfoTracks
+ ___67+[CNAssetInfo loadFromCinematicVideoTracks:requireDisparity:error:]_block_invoke
+ ___block_descriptor_57_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_65_e8_32s40s48r56r_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8r48l8s40l8r56l8
+ ___block_descriptor_73_e8_32s40s48s56r64r_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8r56l8s40l8s48l8r64l8
+ _kPTCinematographyIdentifier
+ _objc_retain_x26
- +[CNAssetInfo loadFromCinematicVideoTrack:requireDisparity:completionHandler:]
- -[CNAssetInfo _initWithVideoTrack:disparityTrack:metadataTrack:]
- -[CNAssetInfo setCinematicDisparityTrack:]
- -[CNAssetInfo setCinematicMetadataTrack:]
- -[CNAssetInfo setCinematicVideoTrack:]
- GCC_except_table32
- _OBJC_IVAR_$_CNAssetInfo._cinematicDisparityTrack
- _OBJC_IVAR_$_CNAssetInfo._cinematicMetadataTrack
- _OBJC_IVAR_$_CNAssetInfo._cinematicVideoTrack
- ___65+[CNAssetInfo _loadFromAsset:requireDisparity:completionHandler:]_block_invoke_2
- ___78+[CNAssetInfo loadFromCinematicVideoTrack:requireDisparity:completionHandler:]_block_invoke
- ___block_descriptor_57_e8_32s40bs_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8s40l8
- ___block_descriptor_57_e8_32s40r48r_e33_v24?0"CNAssetInfo"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_65_e8_32s40s48bs_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8s48l8s40l8
- ___block_descriptor_73_e8_32s40bs48r56r_e5_v8?0ls32l8r48l8r56l8s40l8
- _objc_retain_x27
CStrings:
+ "Error ptr is nil"
+ "Error: Cannot find video track"
+ "Error: Unexpected number of video tracks. Found %lu expected 1."
+ "Ignoring multiple video tracks in asset"
+ "Unsupported asset. requireDisparity %i. Disparity %i. Metadata %i"
- "mdta/"
```
