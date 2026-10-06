## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3010` | `0x1b0` | **`-0x2e60`** |
| `__DATA_DIRTY.__objc_data` | `0xadc0` | `0xdc20` | **`+0x2e60`** |
| `__TEXT.__text` | `0x4c65a8` | `0x4c5d80` | **`-0x828`** |
| `__DATA_CONST.__got` | `0x2048` | `0x2528` | **`+0x4e0`** |
| `__AUTH_CONST.__cfstring` | `0x1dd80` | `0x1df20` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x2bf73` | `0x2c083` | **`+0x110`** |
| `__DATA_DIRTY.__data` | `0x1c0` | `0x2c0` | **`+0x100`** |
| `__AUTH.__data` | `0x200` | `0x118` | **`-0xe8`** |
| `__DATA_DIRTY.__bss` | `0x8d0` | `0x958` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x7540` | `0x75a8` | **`+0x68`** |
| `__DATA.__bss` | `0x3509` | `0x34b9` | **`-0x50`** |
| `__TEXT.__const` | `0x16578` | `0x165c8` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x323bb` | `0x3240b` | **`+0x50`** |
| `__DATA.__common` | `0x3f1` | `0x3c1` | **`-0x30`** |
| `__DATA_DIRTY.__common` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x13e88` | `0x13e58` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x41768` | `0x41790` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x7918` | `0x7938` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xeff8` | `0xefd8` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x67420` | `0x67440` | **`+0x20`** |
| `__DATA.__data` | `0x200c` | `0x1ff4` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x22a88` | `0x22a70` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x3680` | `0x3684` | **`+0x4`** |

### Other Changes

```diff

-435.65.2.0.0
+435.69.2.0.0

-  Symbols:   28380
-  CStrings:  8832
+  Symbols:   28402
+  CStrings:  8846
Symbols:
+ -[MADEmbeddingSearchOptions setUseCache:]
+ -[MADEmbeddingSearchOptions useCache]
+ -[MADNodeData dealloc]
+ _OBJC_IVAR_$_MADEmbeddingSearchOptions._useCache
+ _VCPAnalyticsEvent17246MADHKSVGenerativeProcessing
+ _VCPAnalyticsField17246HKSVProcessingDurationEndToEnd
+ _VCPAnalyticsField17246HKSVProcessingDurationReceiveResultsFromAgent
+ _VCPAnalyticsField17246HKSVProcessingDurationRunRequest
+ _VCPAnalyticsField17246HKSVProcessingDurationSendRequestToAgent
+ _VCPAnalyticsField17246HKSVProcessingDurationVideoCaption
+ _VCPAnalyticsField17246HKSVProcessingDurationVideoDecode
+ _VCPAnalyticsField17246HKSVProcessingDurationVideoEmbedding
+ _VCPAnalyticsField17246HKSVProcessingDurationVideoGate
+ _VCPAnalyticsField17246HKSVProcessingFragmentCount
+ _VCPAnalyticsField17246HKSVProcessingPayloadSizeRequest
+ _VCPAnalyticsField17246HKSVProcessingPayloadSizeResult
+ _VCPAnalyticsField17246HKSVProcessingStatus
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEED0Ev
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEED1Ev
+ __ZTINSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEEE
+ __ZTSNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEEE
+ __ZTVNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEEE
+ __ZZ43+[VCPMADCoreAnalyticsManager sharedManager]E4once
+ __ZZ43+[VCPMADCoreAnalyticsManager sharedManager]E8instance
+ __ZZ52+[VCPMADCoreAnalyticsManager sharedAuxiliaryManager]E4once
+ __ZZ52+[VCPMADCoreAnalyticsManager sharedAuxiliaryManager]E8instance
+ ___43-[VCPMABaseTask initWithCompletionHandler:]_block_invoke
+ ___block_descriptor_56_ea8_32bs40c40_ZTSNSt3__110shared_ptrINS_6atomicIbEEEE_e34_v24?0"NSDictionary"8"NSError"16l
+ ___copy_helper_block_ea8_40c40_ZTSNSt3__110shared_ptrINS_6atomicIbEEEE
+ ___destroy_helper_block_ea8_40c40_ZTSNSt3__110shared_ptrINS_6atomicIbEEEE
- -[MADNodeData setNextSample:]
- -[VCPHomeKitAnalysisSession processVideoFragmentAssetData:withOptions:andCompletionHandler:]
- -[VCPHomeKitAnalysisSession processVideoFragmentAssetData:withOptions:andErrorHandler:]
- -[VCPVideoAnalysisPipelineFrameResource setFrameSampleBuffer:]
- ___87-[VCPHomeKitAnalysisSession processVideoFragmentAssetData:withOptions:andErrorHandler:]_block_invoke
- ___87-[VCPHomeKitAnalysisSession processVideoFragmentAssetData:withOptions:andErrorHandler:]_block_invoke_2
- ___92-[VCPHomeKitAnalysisSession processVideoFragmentAssetData:withOptions:andCompletionHandler:]_block_invoke
- ___92-[VCPHomeKitAnalysisSession processVideoFragmentAssetData:withOptions:andCompletionHandler:]_block_invoke_2
- ___block_descriptor_32_e33_"VCPMADCoreAnalyticsManager"8?0l
- ___block_descriptor_64_ea8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
CStrings:
+ "%@ Existing session log payload is %@, expected NSDictionary; skip merging - %@"
+ "%@ run: returned NO without setting error"
+ "DurationEndToEnd"
+ "DurationReceiveResultsFromAgent"
+ "DurationRunRequest"
+ "DurationSendRequestToAgent"
+ "DurationVideoCaption"
+ "DurationVideoDecode"
+ "DurationVideoEmbedding"
+ "DurationVideoGate"
+ "FragmentCount"
+ "OSStatus"
+ "PayloadSizeRequest"
+ "PayloadSizeResult"
+ "UseCache"
+ "com.apple.mediaanalysisd.MADHKSVGenerativeProcessing"
+ "homekit.captions.camera"
- "@\"VCPMADCoreAnalyticsManager\"8@?0"
- "VCPMADCoreAnalyticsAuxillaryManager"
- "VCPMADCoreAnalyticsManager"
```
