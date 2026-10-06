## ANSTKit

> `/System/Library/PrivateFrameworks/ANSTKit.framework/ANSTKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd0d0c` | `0xd2464` | **`+0x1758`** |
| `__TEXT.__gcc_except_tab` | `0x52fc` | `0x4ba0` | **`-0x75c`** |
| `__TEXT.__const` | `0x3518` | `0x3798` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x3696` | `0x3841` | **`+0x1ab`** |
| `__AUTH_CONST.__cfstring` | `0x8000` | `0x81a0` | **`+0x1a0`** |
| `__AUTH.__objc_data` | `0x190` | `0x280` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x7084` | `0x6fbc` | **`-0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0x2a80` | `0x29e0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x1096f` | `0x109f9` | **`+0x8a`** |
| `__DATA_CONST.__objc_arraydata` | `0x198` | `0x120` | **`-0x78`** |
| `__DATA_CONST.__const` | `0x1188` | `0x1120` | **`-0x68`** |
| `__DATA_CONST.__got` | `0x5c0` | `0x628` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d88` | `0x1de0` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x168` | `0x1a0` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x150` | `0x120` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0xcf4` | `0xd24` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2380` | `0x2350` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x950` | `0x978` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x10170` | `0x10158` | **`-0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x330` | `0x348` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x468` | `0x470` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x428` | `0x430` | **`+0x8`** |

### Other Changes

```diff

-41.0.0.0.0
+43.2.0.0.0

+  - /System/Library/Frameworks/CoreImage.framework/CoreImage

-  Functions: 3197
-  Symbols:   1175
-  CStrings:  1848
+  Functions: 3217
+  Symbols:   1204
+  CStrings:  1855
Symbols:
+ _ANSTGetCurrentTimestampString
+ _ANSTShouldDumpViSam
+ _ANSTWriteBGRAPixelBufferToPNG
+ _ANSTWriteMaskPixelBufferToPNG
+ _ANSTWritePixelBufferToBin
+ _CGColorSpaceCreateWithName
+ _CGColorSpaceRelease
+ _CMTimeGetSeconds
+ _OBJC_CLASS_$_ANSTISPAlgorithmV5Dot4
+ _OBJC_CLASS_$_ANSTISPInferenceDescriptorV5Dot4
+ _OBJC_CLASS_$_ANSTISPInferencePostprocessorV5Dot4
+ _OBJC_CLASS_$_CIContext
+ _OBJC_CLASS_$_CIImage
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_METACLASS_$_ANSTISPAlgorithmV5Dot4
+ _OBJC_METACLASS_$_ANSTISPInferenceDescriptorV5Dot4
+ _OBJC_METACLASS_$_ANSTISPInferencePostprocessorV5Dot4
+ __Z21acDetNodeConfigEKUCv1v
+ __Z22acAssoNodeConfigEKUCV1v
+ __Z24acDetNodeConfigISPv5Dot4v
+ __Z25acAssoNodeConfigISPv5Dot4v
+ __ZNK9AcDetNode18getParamsForEKUCv1ER12AcANSTParams
+ ___kCFBooleanTrue
+ _kCGColorSpaceGenericGray
+ _kCGColorSpaceSRGB
+ _kCIFormatBGRA8
+ _kCIFormatL8
+ _kCVPixelBufferCGBitmapContextCompatibilityKey
+ _kCVPixelBufferCGImageCompatibilityKey
+ _objc_autoreleasePoolPop
+ _objc_autoreleasePoolPush
- _OBJC_CLASS_$_ANSTFsincAlgorithmV2Dot3
- _OBJC_CLASS_$_ANSTFsincInferenceDescriptorV2Dot3
- _OBJC_METACLASS_$_ANSTFsincAlgorithmV2Dot3
- _OBJC_METACLASS_$_ANSTFsincInferenceDescriptorV2Dot3
CStrings:
+ "    eyeOpenConf        %ld\n"
+ "    eyeOpenConfidence               %ld\n\n"
+ "    lookAtCameraConfidence          %ld\n\n"
+ "    vipPersonConfidence             %ld\n\n"
+ "  x: %.4f, y: %.4f, positive: %d\n"
+ "%@/%@_getBestMask_output_mask.bin"
+ "%@/%@_getBestMask_output_mask.png"
+ "%@/%@_getBestMask_prompt.txt"
+ "%@/%@_obj%ld_newObj_image.png"
+ "%@/%@_obj%ld_newObj_input_mask.bin"
+ "%@/%@_obj%ld_newObj_input_mask.png"
+ "%@/%@_obj%ld_newObj_output_box_conf.txt"
+ "%@/%@_obj%ld_newObj_output_mask.bin"
+ "%@/%@_obj%ld_newObj_output_mask.png"
+ "%@/%@_obj%ld_trackObject_image.png"
+ "%@/%@_obj%ld_trackObject_output_box_conf.txt"
+ "%@/%@_obj%ld_trackObject_output_mask.bin"
+ "%@/%@_obj%ld_trackObject_output_mask.png"
+ "%@/%@_setInferImage_image.png"
+ "%s: ANSTISPInferenceDescriptor does not conform to ANSTISPInferenceIOV5Dot4!"
+ "+[ANSTISPAlgorithmV5Dot4 networkDescriptorForConfig:]"
+ "-[ANSTISPAlgorithmV5Dot4 _prepareWithError:]"
+ "-[ANSTISPAlgorithmV5Dot4 initWithConfiguration:]"
+ "-[ANSTISPAlgorithmV5Dot4 resultForPixelBuffer:orientation:error:]"
+ "-[ANSTISPInferencePostprocessorV5Dot4 _processWithError:]"
+ "/AppleInternal/Library/Application Support/com.apple.ANSTKit/ANSTEK_v_1_50.mlmodelc/model.mil"
+ "/tmp/ViSam/Segmentation"
+ "/tmp/ViSam/Tracking"
+ "ANST Fatal Error: ANST v2 model has been removed and is no longer available. The framework has automatically fallen back to the ANSTv5 model. Please update your configuration to use ANSTISPAlgorithmVersion5Latest, and please ask QA to perform a thorough validation/test of this fallback behavior."
+ "ANST4EK UC v1"
+ "ANSTFsincAlgorithmV2(v2.6) initialized with config %{public}@."
+ "ANSTISPAlgorithm v5.4 initialized with config %{public}@."
+ "ANSTISPAlgorithmV5Dot4_prepareWithError"
+ "ANSTISPAlgorithmV5Dot4_resultForPixelBuffer"
+ "ANSTOnEK[Info]-> model loaded successfully for version: %{public}@"
+ "AcANSTPostProcessNetOutputs(_det, &_detControl, &_detParams, _bmBuffer_outputs, (uint32_t)_netOutputMax, &_detState, &acResult)"
+ "Box: x: %.4f, y: %.4f, w: %.4f, h: %.4f\n"
+ "CMTimeValue: %lld, CMTimeScale: %d, Seconds: %.4f\n"
+ "Confidence: %.4f\n"
+ "FSINC inference v2.3 has been removed. Please use v2.4 instead."
+ "Points:\n"
+ "Unsupported configuration combo. ANSTKit currently only ships [v1.9/v1.9.1/v1.9.1.1/v1.9.2-832x832, v1.9.4-448x448 and UCv1-512x512] ANST4EK models."
+ "Version5.4"
+ "anst4ek_uc_v1_1x.bundle"
+ "anst_v5d4"
+ "anst_v5dot4_%@"
+ "com.apple.ANSTKit.ViSamTracker.enable_viSam_dump"
+ "en_US_POSIX"
+ "eyeOpenConfidence"
+ "yyyyMMdd_HHmmss_SSS"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa1"
- "    lookAtCameraConfidence               %ld\n\n"
- "    vipPersonConfidence               %ld\n\n"
- "%{public}s: e5rt_tensor_desc_get_shape failed (code %u: %s)"
- "-[ANSTFsincAlgorithmV2Dot3 _allocateAndBindBuffers:]"
- "-[ANSTFsincAlgorithmV2Dot3 _executeInferenceWithError:]"
- "-[ANSTFsincAlgorithmV2Dot3 _loadE5ExecutionStreamOperation:]"
- "-[ANSTFsincAlgorithmV2Dot3 _releaseOutputBuffers]"
- "-[ANSTFsincAlgorithmV2Dot3 bindNetworkInputPixelBuffer:error:]"
- "-[ANSTFsincAlgorithmV2Dot3 dealloc]"
- "-[ANSTFsincAlgorithmV2Dot3 prepareWithError:]"
- "/AppleInternal/Library/Application Support/com.apple.ANSTKit/ANSTEK_v1_50.mlmodelc/model.mil"
- "ANSTFsincAlgorithmV2(v2.5) initialized with config %{public}@."
- "ANSTFsincAlgorithmV2Dot3 initialized with config %{public}@."
- "ANSTFsincAlgorithmV2Dot3_inference"
- "AcANSTPostProcessNetOutputs(_det, &_detControl, &_detParams, _bmBuffer_outputs, kAcANSTNetOutputEKv1Max, &_detState, &acResult)"
- "Failed to create cvpixelbuffer for output mask."
- "Not found"
- "Not found, %@"
- "Unsupported configuration combo. ANSTKit currently only ships [v1.9/v1.9.1/v1.9.1.1/v1.9.2-832x832 and v1.9.4-448x448] ANST4EK models."
- "e5rt_buffer_object_get_data_ptr(*buffer_t, &outputMasksDataPtr)"
- "e5rt_buffer_object_get_data_ptr(*buffer_t, &outputVisegDataPtr)"
- "e5rt_buffer_object_get_data_ptr(*maskScoreBuffer_t, &outputScoreDataPtr)"
- "e5rt_buffer_object_release(&_e5_outputs_arrays[i])"
- "e5rt_execution_stream_operation_get_num_outputs(_esop, &numOutputs)"
- "e5rt_execution_stream_operation_get_output_names(_esop, numOutputs, outputNames.data())"
- "fsinc_v2d3"
- "instance_%@_%lu"
- "instancescores_%@"
- "semantic_%@_%@"
- "semantic_%@_ears"
- "semantic_%@_eyebrow"
- "semantic_%@_face"
- "semantic_%@_glasses"
- "semantic_%@_hand"
- "semantic_%@_iris"
- "semantic_%@_lips"
- "semantic_%@_nose"
- "semantic_%@_otherskin"
- "semantic_%@_person"
- "semantic_%@_sclera"
- "semantic_%@_skin"
- "semantic_%@_tattoo"
- "semantic_%@_teeth"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0Q"
```
