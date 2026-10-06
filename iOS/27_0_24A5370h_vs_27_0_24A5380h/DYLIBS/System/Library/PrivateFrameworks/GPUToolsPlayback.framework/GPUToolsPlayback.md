## GPUToolsPlayback

> `/System/Library/PrivateFrameworks/GPUToolsPlayback.framework/GPUToolsPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63a4c` | `0x638d4` | **`-0x178`** |
| `__TEXT.__objc_methlist` | `0x30ec` | `0x30fc` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x5480` | `0x5488` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a60` | `0x2a68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x21f0` | `0x21e8` | **`-0x8`** |

### Other Changes

```text
Functions:
~ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220106EPKvm : 532 -> 520
~ -[DYMTLIndirectCommandBufferManager updateReplayerTranslationBuffer] : 1284 -> 1252
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN8GPUTools3MTL5Utils21DYMTLBufferGPUAddressEEEvT1_SA_T0_ : 180 -> 176
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN8GPUTools3MTL5Utils21DYMTLBufferGPUAddressEEEbT1_SA_T0_ : 1136 -> 1124
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEP10OffsetPairEEvT1_S7_T0_ : 212 -> 188
~ __ZNSt3__126__insertion_sort_unguardedB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEP10OffsetPairEEvT1_S7_T0_ : 224 -> 220
~ __ZNSt3__132__partition_with_equals_on_rightB9fqe220106INS_17_ClassicAlgPolicyEP10OffsetPairRNS_6__lessIvvEEEENS_4pairIT0_bEES8_S8_T1_ : 468 -> 464
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEP10OffsetPairEEbT1_S7_T0_ : 1208 -> 1184
~ __ZNSt3__119__partial_sort_implB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEP10OffsetPairS6_EET1_S7_S7_T2_OT0_ : 372 -> 352
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEP15PatchingRequestEEvT1_S7_T0_ : 292 -> 272
~ __ZNSt3__126__insertion_sort_unguardedB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEP15PatchingRequestEEvT1_S7_T0_ : 336 -> 348
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEP15PatchingRequestEEbT1_S7_T0_ : 836 -> 832
~ -[DYMTLIndirectArgumentBufferManager processResourceMapsData:] : 724 -> 720
~ -[DYMTLIndirectArgumentBufferManager notifyReplayerTargetIndirectArgumentBuffers:] : 444 -> 440
~ -[DYMTLIndirectArgumentBufferManager decodeReplayerIAB:offset:function:argument:] : 2260 -> 2264
~ __ZN8GPUTools3MTL27MakeMTLRenderPassDescriptorEPKvRNSt3__113unordered_mapIyU8__strongP11objc_objectNS3_4hashIyEENS3_8equal_toIyEENS3_9allocatorINS3_4pairIKyS7_EEEEEE : 1724 -> 1728
~ __ZN8GPUTools3MTL31MakeMTLRenderPipelineDescriptorEPKvRNSt3__113unordered_mapIyU8__strongP11objc_objectNS3_4hashIyEENS3_8equal_toIyEENS3_9allocatorINS3_4pairIKyS7_EEEEEE : 2292 -> 2320
~ __ZN8GPUTools3MTL35MakeMTLTileRenderPipelineDescriptorEPKvRNSt3__113unordered_mapIyU8__strongP11objc_objectNS3_4hashIyEENS3_8equal_toIyEENS3_9allocatorINS3_4pairIKyS7_EEEEEE : 612 -> 628
~ __ZN8GPUTools3MTL32MakeMTLComputePipelineDescriptorEPKvRNSt3__113unordered_mapIyU8__strongP11objc_objectNS3_4hashIyEENS3_8equal_toIyEENS3_9allocatorINS3_4pairIKyS7_EEEEEE : 884 -> 856
~ __ZN8GPUTools3MTL30MakeMTLImageFilterFunctionInfoEPKv : 256 -> 248
~ -[DYMTLDebugPlaybackEngineCounterSupport _profileSplitEncodersForProfileInfo:] : 5292 -> 5284
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_5tupleIJyyyyyyEEEEEvT1_S8_T0_ : 328 -> 312
~ __ZNSt3__126__insertion_sort_unguardedB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_5tupleIJyyyyyyEEEEEvT1_S8_T0_ : 424 -> 412
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_5tupleIJyyyyyyEEEEEbT1_S8_T0_ : 644 -> 620
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_5tupleIJyyyyyyyEEEEEvT1_S8_T0_ : 432 -> 400
~ __ZNSt3__126__insertion_sort_unguardedB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_5tupleIJyyyyyyyEEEEEvT1_S8_T0_ : 452 -> 428
~ __ZNSt3__132__partition_with_equals_on_rightB9fqe220106INS_17_ClassicAlgPolicyEPNS_5tupleIJyyyyyyyEEERNS_6__lessIvvEEEENS_4pairIT0_bEES9_S9_T1_ : 596 -> 604
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPNS_5tupleIJyyyyyyyEEEEEbT1_S8_T0_ : 700 -> 644
~ ___63-[DYMTLCommonDebugFunctionPlayer setupProfilingForCounterLists]_block_invoke_2 : 1736 -> 1720
~ __ZN14ShaderDebugger8Metadata12MDSerializer17serializeToBufferERNSt3__16vectorIhNS2_9allocatorIhEEEE : 1280 -> 1260
~ __ZN14ShaderDebugger8Metadata12MDSerializer22serializeCompositeTypeEyRKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEyyyytyRKNS2_6vectorINS2_4pairINS0_6MDBase12MetadataTypeEyEENS6_ISF_EEEE : 1100 -> 1088
~ __ZN14ShaderDebugger8Metadata12MDSerializer23serializeSubroutineTypeEyRKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEyyyytRKNS2_6vectorINS2_4pairINS0_6MDBase12MetadataTypeEyEENS6_ISF_EEEE : 984 -> 972
~ __ZNSt3__15dequeIU8__strongU13block_pointerFvvENS_9allocatorIS3_EEE19__add_back_capacityEv : 484 -> 472
```
