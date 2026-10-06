## Cinematic

> `/System/Library/Frameworks/Cinematic.framework/Cinematic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13fdc` | `0x13df8` | **`-0x1e4`** |
| `__DATA_CONST.__const` | `0x730` | `0x6e0` | **`-0x50`** |
| `__AUTH_CONST.__objc_const` | `0x1df0` | `0x1e20` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xb78` | `0xb90` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x280` | `0x26c` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x848` | `0x838` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x94` | `0x98` | **`+0x4`** |

### Other Changes

```diff

-546.0.0.0.0
+551.0.0.0.0

-  Functions: 748
-  Symbols:   967
+  Functions: 747
+  Symbols:   965
Symbols:
+ +[CNAssetInfo _loadFromAsset:requireDisparity:completionHandler:]
+ +[CNAssetInfo loadFromCinematicVideoTrack:requireDisparity:completionHandler:]
+ -[CNRenderingSessionAttributes disparityPreview]
+ -[CNRenderingSessionAttributes setDisparityPreview:]
+ -[CNRenderingSessionFrameAttributes _initJustWithPTTimedRenderingMetadata:time:]
+ -[CNRenderingSessionFrameAttributes _initWithPTTimedRenderingMetadata:time:]
+ -[CNRenderingSessionFrameAttributes _initWithTimedData:sessionAttributes:time:]
+ GCC_except_table4
+ _CMAudioFormatDescriptionGetRichestDecodableFormatAndChannelLayout
+ _CMTimeMakeWithSeconds
+ _FigAudioChannelLayoutIsSupportedForCinematicAudio
+ _OBJC_IVAR_$_CNRenderingSessionAttributes._disparityPreview
+ __OBJC_$_INSTANCE_METHODS_CNScript
+ ___65+[CNAssetInfo _loadFromAsset:requireDisparity:completionHandler:]_block_invoke
+ ___78+[CNAssetInfo loadFromCinematicVideoTrack:requireDisparity:completionHandler:]_block_invoke
+ ___block_descriptor_57_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_57_e8_32s40bs_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8s40l8
+ ___block_descriptor_57_e8_32s40r48r_e33_v24?0"CNAssetInfo"8"NSError"16lr40l8r48l8s32l8
+ ___block_descriptor_65_e8_32s40s48bs_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8s48l8s40l8
- +[CNAssetInfo loadFromCinematicVideoTrack:completionHandler:]
- +[CNScriptFrame(Private) _copyInternalFromFrames:]
- -[CNRenderingSessionFrameAttributes _initJustWithPTTimedRenderingMetadata:]
- -[CNRenderingSessionFrameAttributes _initWithPTTimedRenderingMetadata:]
- -[CNRenderingSessionFrameAttributes _initWithTimedData:sessionAttributes:]
- -[CNScript(Private) _performWithInternalScript:]
- GCC_except_table114
- GCC_except_table3
- GCC_except_table30
- _CMAudioFormatDescriptionGetRichestDecodableFormat
- __OBJC_$_INSTANCE_METHODS_CNScript(Private)
- ___47+[CNAssetInfo loadFromAsset:completionHandler:]_block_invoke
- ___48-[CNScript(Private) _performWithInternalScript:]_block_invoke
- ___48-[CNScript(Private) _performWithInternalScript:]_block_invoke_2
- ___61+[CNAssetInfo loadFromCinematicVideoTrack:completionHandler:]_block_invoke
- ___block_descriptor_48_e8_32s40bs_e5_8?0ls40l8s32l8
- ___block_descriptor_56_e8_32s40bs48r_e5_v8?0lr48l8s40l8s32l8
- ___block_descriptor_56_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
- ___block_descriptor_56_e8_32s40bs_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8s40l8
- ___block_descriptor_56_e8_32s40r48r_e33_v24?0"CNAssetInfo"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_64_e8_32s40s48bs_e34_v24?0"AVAssetTrack"8"NSError"16ls32l8s48l8s40l8
```
