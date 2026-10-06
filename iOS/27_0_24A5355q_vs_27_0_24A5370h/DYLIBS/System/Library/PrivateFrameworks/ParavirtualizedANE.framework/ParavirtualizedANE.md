## ParavirtualizedANE

> `/System/Library/PrivateFrameworks/ParavirtualizedANE.framework/ParavirtualizedANE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f5e8` | `0x1f970` | **`+0x388`** |
| `__TEXT.__oslogstring` | `0x6332` | `0x6427` | **`+0xf5`** |
| `__TEXT.__gcc_except_tab` | `0x3ac0` | `0x3b0c` | **`+0x4c`** |
| `__TEXT.__unwind_info` | `0x6e8` | `0x6f0` | **`+0x8`** |

### Other Changes

```diff

-382.7.4.0.0
+382.9.0.0.0

-  Functions: 533
+  Functions: 537

-  CStrings:  553
+  CStrings:  557
Symbols:
+ __ZNSt3__115allocate_sharedB9fqe220106I17_IOSurfaceWrapperNS_9allocatorIS1_EEJRjRU8__strongPU19objcproto9OS_os_log8NSObjectELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
+ __ZNSt3__115allocate_sharedB9fqe220106I17_IOSurfaceWrapperNS_9allocatorIS1_EEJRjU8__strongPU19objcproto9OS_os_log8NSObjectELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
- __ZNSt3__115allocate_sharedB9fqe220100I17_IOSurfaceWrapperNS_9allocatorIS1_EEJRjRU8__strongPU19objcproto9OS_os_log8NSObjectELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
- __ZNSt3__115allocate_sharedB9fqe220100I17_IOSurfaceWrapperNS_9allocatorIS1_EEJRjU8__strongPU19objcproto9OS_os_log8NSObjectELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
Functions:
~ -[_ANEVirtualPlatformClient unmapAllMutableWeightsForVirtualModel:] : 724 -> 720
~ -[_ANEVirtualPlatformClient loadModelNewInstance:] : 5388 -> 5380
~ -[_ANEVirtualPlatformClient validateNetworkCreate:] : 6120 -> 6116
~ -[_ANEVirtualPlatformClient createModelFile:path:ioSID:length:] : 192 -> 336
~ -[_ANEVirtualPlatformClient printIOSurfaceDataInBytes:] : 504 -> 500
~ -[_ANEVirtualPlatformClient doCreateModelFile:aneModelKey:] : 5376 -> 5468
~ +[_ANEVirtualPlatformClient createAssetsOnDiskFromDataBuffer:withDataSize:atDestDirectory:] : 1964 -> 2120
~ -[_ANEVirtualPlatformClient createLLIRBundleOnDiskFromIOSurfaceWithID:destDirectory:llirDataSize:] : 1452 -> 1580
~ -[_ANEVirtualPlatformClient createANEModelInstanceParameters:modelUUID:] : 2692 -> 2688
~ -[_ANEVirtualPlatformClient requestWithVirtualANEModel:] : 1336 -> 1360
~ +[_ANEVirtualPlatformClient prepareValidationResultForSerialization:] : 608 -> 604
~ -[_ANEVirtualPlatformClient generateExpectedPathForFileName:withFileType:withInputDictionary:] : 152 -> 300
~ +[_ANEVirtualPlatformClient getPrecompiledModelPath:error:] : 712 -> 708
~ __ZN14aneserializers28anemodelnewinstanceparams_v149_ANEModelInstanceParametersSerializerDeserializerC2EPNS0_41_ANEModelInstanceParametersSerializedDataEPU19objcproto9OS_os_log8NSObject : 384 -> 376
~ __ZN14aneserializers28anemodelnewinstanceparams_v139_ANEProcedureDataSerializerDeserializerC2EPNS0_31_ANEProcedureDataSerializedDataEPU19objcproto9OS_os_log8NSObject : 456 -> 452
~ __ZN14aneserializers28anemodelnewinstanceparams_v149_ANEModelInstanceParametersSerializerDeserializerD2Ev : 140 -> 128
~ __ZN14aneserializers28anemodelnewinstanceparams_v139_ANEProcedureDataSerializerDeserializerD2Ev : 164 -> 160
+ -[_ANEVirtualPlatformClient createModelFile:path:ioSID:length:].cold.1
+ +[_ANEVirtualPlatformClient createAssetsOnDiskFromDataBuffer:withDataSize:atDestDirectory:].cold.4
~ -[_ANEVirtualPlatformClient createLLIRBundleOnDiskFromIOSurfaceWithID:destDirectory:llirDataSize:].cold.5 : 60 -> 68
~ -[_ANEVirtualPlatformClient createLLIRBundleOnDiskFromIOSurfaceWithID:destDirectory:llirDataSize:].cold.7 : 68 -> 60
+ -[_ANEVirtualPlatformClient createLLIRBundleOnDiskFromIOSurfaceWithID:destDirectory:llirDataSize:].cold.9
+ -[_ANEVirtualPlatformClient generateExpectedPathForFileName:withFileType:withInputDictionary:].cold.1
CStrings:
+ "%@: bundleName rejected (empty, traversal, or path separator): %@"
+ "%@: fileName rejected (empty, traversal, or absolute): %@"
+ "%@: fileRelativePath rejected (traversal or absolute): %@"
+ "%@: modelFileName rejected (empty, traversal, or absolute): %@"
```
