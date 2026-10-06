## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cbd98` | `0x4d1bec` | **`+0x5e54`** |
| `__DATA_DIRTY.__data` | `0x2b8` | `0x1410` | **`+0x1158`** |
| `__DATA.__data` | `0x2010` | `0xfb0` | **`-0x1060`** |
| `__TEXT.__gcc_except_tab` | `0x67b94` | `0x686bc` | **`+0xb28`** |
| `__TEXT.__oslogstring` | `0x329bb` | `0x3312b` | **`+0x770`** |
| `__DATA_DIRTY.__objc_data` | `0xdc28` | `0xdf18` | **`+0x2f0`** |
| `__AUTH.__objc_data` | `0x2f0` | `0x50` | **`-0x2a0`** |
| `__TEXT.__cstring` | `0x2cac1` | `0x2cd21` | **`+0x260`** |
| `__AUTH_CONST.__objc_const` | `0x41ba0` | `0x41de8` | **`+0x248`** |
| `__AUTH_CONST.__cfstring` | `0x1ea20` | `0x1eb80` | **`+0x160`** |
| `__AUTH.__data` | `0x118` | `—` | **`-0x118`** |
| `__TEXT.__objc_methlist` | `0x22c98` | `0x22d60` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x14060` | `0x14100` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0xf128` | `0xf198` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x7c80` | `0x7c18` | **`-0x68`** |
| `__AUTH_CONST.__objc_intobj` | `0x38d0` | `0x3930` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x36ac` | `0x36e0` | **`+0x34`** |
| `__DATA_CONST.__got` | `0x2550` | `0x2578` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x75c8` | `0x75e8` | **`+0x20`** |
| `__DATA.__bss` | `0x34f9` | `0x34d9` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x938` | `0x958` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2580` | `0x2590` | **`+0x10`** |
| `__AUTH_CONST.__objc_floatobj` | `0x2f0` | `0x300` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x15b8` | `0x15c0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xfa0` | `0xfa8` | **`+0x8`** |

### Other Changes

```diff

-460.7.1.0.0
+460.8.2.0.0

-  Functions: 20149
-  Symbols:   28572
-  CStrings:  8970
+  Functions: 20216
+  Symbols:   28613
+  CStrings:  9018
Symbols:
+ +[PHPhotoLibrary(MediaAnalysis) mad_isInitialAnalysisPass]
+ +[VCPMovieAssetWriter assetWriterWithURL:andTrack:andBitrate:withOutputSize:enableAudio:enableStyle:hasStyleApplied:enableTextureStyle:]
+ -[MADTextureStyleMetaAnalyzer .cxx_destruct]
+ -[MADTextureStyleMetaAnalyzer initWithRequestAnalyses:formatDescription:]
+ -[MADTextureStyleMetaAnalyzer privateResults]
+ -[MADTextureStyleMetaAnalyzer processMetadataGroup:flags:]
+ -[VCPMovieAssetWriter addSkinPixelBuffer:withTime:withAttachment:]
+ -[VCPMovieAssetWriter addTextureStyleInfoData:timerange:]
+ -[VCPMovieAssetWriter initWithURL:andTrack:andBitrate:withOutputSize:enableAudio:enableStyle:hasStyleApplied:enableTextureStyle:]
+ -[VCPMovieAssetWriter popSkinSample]
+ -[VCPMovieAssetWriter pushSkinSample:]
+ -[VCPMovieAssetWriter setupSkinTrack]
+ -[VCPVideoInterpolator createMetadataItem:identifier:timerange:]
+ -[VCPVideoInterpolator createSkinTrackDecoder:timerange:]
+ -[VCPVideoInterpolator createTextureStyleInfoMetadata:timerange:]
+ -[VCPVideoInterpolator deserializeMetadata:faceROIs:]
+ -[VCPVideoInterpolator enableTextureStyle]
+ -[VCPVideoInterpolator faceROIRect:fromDictionary:]
+ -[VCPVideoInterpolator findIntraFrameList:into:]
+ -[VCPVideoInterpolator hasIntraFrameAtEndBoundary]
+ -[VCPVideoInterpolator interpolateSkinMap]
+ _CMFormatDescriptionGetExtension
+ _MediaAnalysisMetaTSInfoResultsKey
+ _MediaAnalysisMetaTSResultsKey
+ _NSClassFromString
+ _OBJC_CLASS_$_MADTextureStyleMetaAnalyzer
+ _OBJC_IVAR_$_MADTextureStyleMetaAnalyzer._results
+ _OBJC_IVAR_$_VCPMovieAssetWriter._enableTextureStyle
+ _OBJC_IVAR_$_VCPMovieAssetWriter._skinDequeueSemaphore
+ _OBJC_IVAR_$_VCPMovieAssetWriter._skinEnqueueSemaphore
+ _OBJC_IVAR_$_VCPMovieAssetWriter._skinInput
+ _OBJC_IVAR_$_VCPMovieAssetWriter._skinQueue
+ _OBJC_IVAR_$_VCPMovieAssetWriter._skinsampleQueue
+ _OBJC_IVAR_$_VCPMovieAssetWriter._textureStyleInfoAdaptor
+ _OBJC_IVAR_$_VCPVideoInterpolator._enableTextureStyle
+ _OBJC_IVAR_$_VCPVideoInterpolator._previousTextureStyleMetadata
+ _OBJC_IVAR_$_VCPVideoInterpolator._stylesMetadataInterpolator
+ _OBJC_IVAR_$_VCPVideoInterpolator._textureStyleMetadata
+ _OBJC_IVAR_$_VCPVideoInterpolator._videoOutputTimeline
+ _OBJC_METACLASS_$_MADTextureStyleMetaAnalyzer
+ __OBJC_$_INSTANCE_METHODS_MADTextureStyleMetaAnalyzer
+ __OBJC_$_INSTANCE_VARIABLES_MADTextureStyleMetaAnalyzer
+ __OBJC_CLASS_RO_$_MADTextureStyleMetaAnalyzer
+ __OBJC_METACLASS_RO_$_MADTextureStyleMetaAnalyzer
+ __ZZ58+[PHPhotoLibrary(MediaAnalysis) mad_isInitialAnalysisPass]E21isInitialAnalysisPass
+ __ZZ58+[PHPhotoLibrary(MediaAnalysis) mad_isInitialAnalysisPass]E4once
+ ___58+[PHPhotoLibrary(MediaAnalysis) mad_isInitialAnalysisPass]_block_invoke
+ _kCMITextureStylesPersonInputDataKey_faceID
+ _kCMITextureStylesPersonInputDataKey_faceROI
+ _kVTCompressionPropertyKey_MaximumRealTimeFrameRate
+ _kVTProfileLevel_HEVC_Monochrome_AutoLevel
- +[PHAssetResourceManager(MediaAnalysis) vcp_inMemoryDownload:withTaskID:toData:cancel:]
- +[VCPMovieAssetWriter assetWriterWithURL:andTrack:andBitrate:withOutputSize:enableAudio:enableStyle:hasStyleApplied:]
- -[VCPMovieAssetWriter initWithURL:andTrack:andBitrate:withOutputSize:enableAudio:enableStyle:hasStyleApplied:]
- -[VCPVideoInterpolator deserializeMetadata:]
- -[VCPVideoInterpolator findIntraFrameList:]
- __ZZ44+[VCPVideoInterpolator processTextureStyles]E13textureStyles
- ___87+[PHAssetResourceManager(MediaAnalysis) vcp_inMemoryDownload:withTaskID:toData:cancel:]_block_invoke
- ___block_descriptor_40_e8_32s_e16_v16?0"NSData"8ls32l8
- ___block_descriptor_40_e8_32s_e8_v16?0d8ls32l8
- ___block_descriptor_64_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/MediaAnalysis/TextureStyleMetaAnalyzer.mm"
+ "CMIStylesMetadataInterpolator"
+ "Failed to append texturestyle-info at %.6f"
+ "Failed to create skin map decoder"
+ "Failed to create skin map writer input"
+ "Failed to splice the skin map segment (%@)"
+ "Failed to start FRC session for the skin map at usage %ld"
+ "Interpolated facebox %u has no usable faceROI, keys %@"
+ "MADInterpolatedFaceROIs"
+ "MetaTSInfoResults"
+ "MetaTSResults"
+ "Missing texture style metadata"
+ "No recorded video output timeline to follow"
+ "No skin map track on a texture styled asset"
+ "No skin map track to interpolate on a texture styled asset"
+ "No skin map writer input to append to"
+ "No texturestyle-info track to append to"
+ "Number of frames inconsistent with texture style metadata"
+ "Skin interpolation returned %lu frames for %lu expected between anchors %lu and %lu (%@)"
+ "Skin map %.0fx%.0f has no FRC usage"
+ "Skin map frame count does not match the video track timeline"
+ "Skin map ran out of samples at timeline entry %lu of %lu"
+ "Skin map sample %lu carries no image buffer"
+ "Skin map segment 1 is %.4f but video is %.4f"
+ "Skin map through the processed segment is %.4f but video is %.4f"
+ "Skin map track has %lu format descriptions"
+ "Styles metadata interpolation returned %lu results for %lu inserted frames over the gap at %.6f, payloads %@"
+ "Styles metadata interpolation returned no SmartStyle coefficients"
+ "Texture style enabled but the skin map is missing (processed %d, composition %d, original %d)"
+ "Texture style enabled but the texturestyle-info track is missing (processed %d, composition %d, original %d)"
+ "Video output timeline has %lu entries for %lu insertion points"
+ "[FRC] Failed to end the skin map FRC session"
+ "[FRC] Failed to read the sync samples of track %d"
+ "[FRC] Skin inserted frame %lu of pair %lu at %.6f, video track used %.6f"
+ "[FRC] Skin map encoding aborted"
+ "[FRC] Skin map encoding failed"
+ "[FRC] Skin map encoding finished"
+ "[FRC] Skipping asset: CMIStylesMetadataInterpolator %s"
+ "[FRC] Skipping asset: texturestyle-info without a style or a skin map"
+ "[MediaAnalysis] [MADTextureStyleMetaAnalyzer] Read %lu texture style info samples"
+ "[MediaAnalysis] [MADTextureStyleMetaAnalyzer] Texture style item carries no value"
+ "anchor"
+ "class not found"
+ "com.apple.mediaanalysisd.movieassetwriter.mediaDataRequest.skinEncoding"
+ "faceROIs"
+ "has no initialiser"
+ "has no interpolation method"
+ "inserted"
+ "interpolateStylesMetadataFromStartFrameMetadataDict:startFrameTime:endFrameMetadataDict:endFrameTime:frameTimesToInterpolate:"
+ "mdta/com.apple.quicktime.texturestyle-info"
+ "smartStyleMetadata"
+ "textureStyleMetadata"
- "Attempt to download resource: %@"
- "Cancelling download (ID:%d)"
- "Download resource timed-out (ID:%d)"
- "[%@] Download progress: %.2f"
```
