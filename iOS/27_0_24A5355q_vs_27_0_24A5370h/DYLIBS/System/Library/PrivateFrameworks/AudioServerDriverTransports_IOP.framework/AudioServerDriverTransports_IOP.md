## AudioServerDriverTransports_IOP

> `/System/Library/PrivateFrameworks/AudioServerDriverTransports_IOP.framework/AudioServerDriverTransports_IOP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19558` | `0x1cec0` | **`+0x3968`** |
| `__TEXT.__oslogstring` | `0x140d` | `0x18e5` | **`+0x4d8`** |
| `__TEXT.__gcc_except_tab` | `0x1c48` | `0x1fec` | **`+0x3a4`** |
| `__TEXT.__unwind_info` | `0xd80` | `0xf50` | **`+0x1d0`** |
| `__AUTH_CONST.__const` | `0x870` | `0x908` | **`+0x98`** |
| `__TEXT.__cstring` | `0x188f` | `0x1910` | **`+0x81`** |
| `__TEXT.__const` | `0x280` | `0x2f0` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xfcc` | `0xfb4` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x950` | `0x948` | **`-0x8`** |
| `__DATA_CONST.__weak_got` | `0x8` | `0x10` | **`+0x8`** |

### Other Changes

```diff

-400.29.0.0.0
+400.34.0.0.0

-  Functions: 771
-  Symbols:   1183
-  CStrings:  334
+  Functions: 881
+  Symbols:   1288
+  CStrings:  375
Symbols:
+ GCC_except_table23
+ GCC_except_table24
+ GCC_except_table28
+ GCC_except_table42
+ GCC_except_table44
+ GCC_except_table48
+ GCC_except_table50
+ _CFStringGetBytes
+ _CFStringGetCStringPtr
+ _CFStringGetLength
+ _CFStringGetTypeID
+ _IOIteratorNext
+ _IOObjectRelease
+ _IORegistryEntryGetName
+ _IOServiceGetMatchingServices
+ _IOServiceMatching
+ _OUTLINED_FUNCTION_5
+ __ZN10applesauce2CF10convert_toINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEELi0EEET_PK10__CFString
+ __ZN10applesauce2CF13convert_errorEv
+ __ZN10applesauce2CF20MutableDictionaryRef11from_createEP14__CFDictionary
+ __ZN10applesauce2CF20MutableDictionaryRefD1Ev
+ __ZN10applesauce2CF7details18CFString_get_valueILb1EEENSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEPK10__CFString
+ __ZN10applesauce2CF9StringRefD2Ev
+ __ZN4ASDT8IOPAudio11AlgInjector10SetUseCaseEN19RTKitAudioFramework8IOPAudio9Tightbeam7UseCaseE
+ __ZN4ASDT8IOPAudio11AlgInjector10_GetBufferEmRKN19RTKitAudioFramework8IOPAudio8Provider21DataStreamDescriptionERNSt3__13mapImNS8_6vectorIhNS8_9allocatorIhEEEENS8_4lessImEENSB_INS8_4pairIKmSD_EEEEEE
+ __ZN4ASDT8IOPAudio11AlgInjector10_WriteDataEmPKvm
+ __ZN4ASDT8IOPAudio11AlgInjector13ReadAudioDataEmPvRm
+ __ZN4ASDT8IOPAudio11AlgInjector13ReadEventDataEmPvRm
+ __ZN4ASDT8IOPAudio11AlgInjector14GetInputBufferEm
+ __ZN4ASDT8IOPAudio11AlgInjector14GetInputsCountEv
+ __ZN4ASDT8IOPAudio11AlgInjector14SetPayloadSizeEj
+ __ZN4ASDT8IOPAudio11AlgInjector14WriteAudioDataEmRKN19RTKitAudioFramework12ElementArrayIhEE
+ __ZN4ASDT8IOPAudio11AlgInjector14WriteEventDataEmRKN19RTKitAudioFramework12ElementArrayIhEE
+ __ZN4ASDT8IOPAudio11AlgInjector15GetOutputBufferEm
+ __ZN4ASDT8IOPAudio11AlgInjector15GetOutputsCountEv
+ __ZN4ASDT8IOPAudio11AlgInjector15_GetInputsCountEv
+ __ZN4ASDT8IOPAudio11AlgInjector16_GetOutputsCountEv
+ __ZN4ASDT8IOPAudio11AlgInjector18GetInputStreamInfoEm
+ __ZN4ASDT8IOPAudio11AlgInjector19GetOutputStreamInfoEm
+ __ZN4ASDT8IOPAudio11AlgInjector20SetProviderServiceIDEj
+ __ZN4ASDT8IOPAudio11AlgInjector29GetInputDataStreamDescriptionEm
+ __ZN4ASDT8IOPAudio11AlgInjector30GetOutputDataStreamDescriptionEm
+ __ZN4ASDT8IOPAudio11AlgInjector30_GetInputDataStreamDescriptionEm
+ __ZN4ASDT8IOPAudio11AlgInjector31_GetOutputDataStreamDescriptionEm
+ __ZN4ASDT8IOPAudio11AlgInjector5SetupEN19RTKitAudioFramework8IOPAudio9Tightbeam7UseCaseEj
+ __ZN4ASDT8IOPAudio11AlgInjector7CleanupEv
+ __ZN4ASDT8IOPAudio11AlgInjector7ProcessEv
+ __ZN4ASDT8IOPAudio11AlgInjector9_ReadDataEmPvRm
+ __ZN4ASDT8IOPAudio11AlgInjectorC1Ej
+ __ZN4ASDT8IOPAudio11AlgInjectorC2Ej
+ __ZN4ASDT8IOPAudio11AlgInjectorD0Ev
+ __ZN4ASDT8IOPAudio11AlgInjectorD1Ev
+ __ZN4ASDT8IOPAudio11AlgInjectorD2Ev
+ __ZN4ASDT8IOPAudio14AlgInjectorMap3endEv
+ __ZN4ASDT8IOPAudio14AlgInjectorMap4findERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE
+ __ZN4ASDT8IOPAudio14AlgInjectorMap5beginEv
+ __ZN4ASDT8IOPAudio14AlgInjectorMapC1Ev
+ __ZN4ASDT8IOPAudio14AlgInjectorMapC2Ev
+ __ZN4ASDT8IOPAudio14AlgInjectorMapD0Ev
+ __ZN4ASDT8IOPAudio14AlgInjectorMapD1Ev
+ __ZNK4ASDT8IOPAudio14AlgInjectorMap3endEv
+ __ZNK4ASDT8IOPAudio14AlgInjectorMap4findERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE
+ __ZNK4ASDT8IOPAudio14AlgInjectorMap4sizeEv
+ __ZNK4ASDT8IOPAudio14AlgInjectorMap5beginEv
+ __ZNK4ASDT8IOPAudio14AlgInjectorMap5emptyEv
+ __ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE4findB9fqe220106EPKcm
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeD1Ev
+ __ZNSt3__110unique_ptrINS_11__tree_nodeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS0_IN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISB_EEEEEEPvEENS_22__tree_node_destructorINS6_ISH_EEEEED1B9fqe220106Ev
+ __ZNSt3__111shared_lockINS_12shared_mutexEED2B9fqe220106Ev
+ __ZNSt3__111unique_lockINS_12shared_mutexEED2B9fqe220106Ev
+ __ZNSt3__112__destroy_atB9fqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISC_EEEEEEEEvPT_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_out_of_rangeB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220106EOS5_mmRKS4_
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeImNS_6vectorIhNS1_IhEEEEEEPvEEEEEclB9fqe220106EPS9_
+ __ZNSt3__127__tree_balance_after_insertB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__130__default_three_way_comparatorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES6_vEclB9fqe220106ERKS6_S9_
+ __ZNSt3__13mapINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISA_EEEENS_4lessIS6_EENS4_INS_4pairIKS6_SD_EEEEE7emplaceB9fqe220106IJRS6_SD_EEENSG_INS_14__map_iteratorINS_15__tree_iteratorINS_12__value_typeIS6_SD_EEPNS_11__tree_nodeISQ_PvEElEEEEbEEDpOT_
+ __ZNSt3__13mapImN19RTKitAudioFramework8IOPAudio8Provider21DataStreamDescriptionENS_4lessImEENS_9allocatorINS_4pairIKmS4_EEEEE6insertB9fqe220106EOSA_
+ __ZNSt3__13mapImNS_6vectorIhNS_9allocatorIhEEEENS_4lessImEENS2_INS_4pairIKmS4_EEEEE7emplaceB9fqe220106IJRmSD_EEENS7_INS_14__map_iteratorINS_15__tree_iteratorINS_12__value_typeImS4_EEPNS_11__tree_nodeISH_PvEElEEEEbEEDpOT_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISB_EEEEEENS_19__map_value_compareIS7_NS_4pairIKS7_SE_EENS_4lessIS7_EEEENS5_ISJ_EEE12__find_equalB9fqe220106IS7_EENSH_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSU_EERKT_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISB_EEEEEENS_19__map_value_compareIS7_NS_4pairIKS7_SE_EENS_4lessIS7_EEEENS5_ISJ_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeISF_PvEE
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISB_EEEEEENS_19__map_value_compareIS7_NS_4pairIKS7_SE_EENS_4lessIS7_EEEENS5_ISJ_EEE16__construct_nodeIJRS7_SE_EEENS8_INS_11__tree_nodeISF_PvEENS_22__tree_node_destructorINS5_IST_EEEEEEDpOT_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISB_EEEEEENS_19__map_value_compareIS7_NS_4pairIKS7_SE_EENS_4lessIS7_EEEENS5_ISJ_EEE16__insert_node_atEPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERST_ST_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4ASDT8IOPAudio11AlgInjectorENS_14default_deleteISB_EEEEEENS_19__map_value_compareIS7_NS_4pairIKS7_SE_EENS_4lessIS7_EEEENS5_ISJ_EEE7destroyEPNS_11__tree_nodeISF_PvEE
+ __ZNSt3__16__treeINS_12__value_typeImN19RTKitAudioFramework8IOPAudio8Provider21DataStreamDescriptionEEENS_19__map_value_compareImNS_4pairIKmS5_EENS_4lessImEEEENS_9allocatorISA_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS6_PvEE
+ __ZNSt3__16__treeINS_12__value_typeImN19RTKitAudioFramework8IOPAudio8Provider21DataStreamDescriptionEEENS_19__map_value_compareImNS_4pairIKmS5_EENS_4lessImEEEENS_9allocatorISA_EEE16__insert_node_atEPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSL_SL_
+ __ZNSt3__16__treeINS_12__value_typeImN19RTKitAudioFramework8IOPAudio8Provider21DataStreamDescriptionEEENS_19__map_value_compareImNS_4pairIKmS5_EENS_4lessImEEEENS_9allocatorISA_EEE7destroyEPNS_11__tree_nodeIS6_PvEE
+ __ZNSt3__16__treeINS_12__value_typeImNS_6vectorIhNS_9allocatorIhEEEEEENS_19__map_value_compareImNS_4pairIKmS5_EENS_4lessImEEEENS3_ISA_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS6_PvEE
+ __ZNSt3__16__treeINS_12__value_typeImNS_6vectorIhNS_9allocatorIhEEEEEENS_19__map_value_compareImNS_4pairIKmS5_EENS_4lessImEEEENS3_ISA_EEE16__construct_nodeIJRmSH_EEENS_10unique_ptrINS_11__tree_nodeIS6_PvEENS_22__tree_node_destructorINS3_ISL_EEEEEEDpOT_
+ __ZNSt3__16__treeINS_12__value_typeImNS_6vectorIhNS_9allocatorIhEEEEEENS_19__map_value_compareImNS_4pairIKmS5_EENS_4lessImEEEENS3_ISA_EEE16__insert_node_atEPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSK_SK_
+ __ZNSt3__16__treeINS_12__value_typeImNS_6vectorIhNS_9allocatorIhEEEEEENS_19__map_value_compareImNS_4pairIKmS5_EENS_4lessImEEEENS3_ISA_EEE7destroyEPNS_11__tree_nodeIS6_PvEE
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE6resizeEmRKh
+ __ZNSt3__16vectorIhNS_9allocatorIhEEEC2B9fqe220106Em
+ __ZTIN4ASDT8IOPAudio11AlgInjectorE
+ __ZTIN4ASDT8IOPAudio14AlgInjectorMapE
+ __ZTISt12out_of_range
+ __ZTSN4ASDT8IOPAudio11AlgInjectorE
+ __ZTSN4ASDT8IOPAudio14AlgInjectorMapE
+ __ZTVN4ASDT8IOPAudio11AlgInjectorE
+ __ZTVN4ASDT8IOPAudio14AlgInjectorMapE
+ __ZTVSt12out_of_range
+ _kIOMainPortDefault
+ _memchr
+ _memcmp
+ _printf
+ _strnlen
- -[NSDictionary(ASDTStreamCM) asdtStreamCMInfoForStream:]
- -[NSDictionary(ASDTStreamCM) asdtStreamCMInfoForStreamStr:]
- GCC_except_table37
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__111shared_lockINS_12shared_mutexEED2B9fqe220100Ev
- __ZNSt3__111unique_lockINS_12shared_mutexEED2B9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- _objc_retain_x28
CStrings:
+ "\nFailed to write kInputDataStreamBuffer %zu\n"
+ "\nPayload too large writing to stream %zu: %zu"
+ "%@:%@: Memory mapped for stream '%s'."
+ "%s: Bad argument."
+ "%s: IOServiceMatching failed"
+ "AlgInjectorMap"
+ "Bad Injector object.\n"
+ "Bad audio data size %zu frames (expecting %u)"
+ "Bad bytes to read: %zu, requested: %zu"
+ "Bad event data size %zu bytes (expecting %u)"
+ "Could not convert"
+ "Expected audio packet type for stream %zu, found '%s'."
+ "Expected event packet type for stream %zu, found '%s'."
+ "Failed opening connection to Injector.\n"
+ "Failed to allocate buffer for input stream %zu"
+ "Failed to allocate buffer for output stream %zu"
+ "Failed to enable AlgorithmInjector\n"
+ "Failed to get identifier for '%s'"
+ "Failed to get kInputDataStreamBufferInfo\n"
+ "Failed to get kInputDataStreamDescription\n"
+ "Failed to get kInputsCount\n"
+ "Failed to get kOutputDataStreamBufferInfo\n"
+ "Failed to get kOutputDataStreamDescription\n"
+ "Failed to get kOutputsCount\n"
+ "Failed to read kOutputDataStreamBuffer %zu"
+ "Failed to set kAlgorithmUseCase\n"
+ "Failed to trigger kDoProcess."
+ "Failed writing %zu frames of audio."
+ "Failed writing %zu frames of zeros."
+ "IORegistryEntryGetName: 0x%x"
+ "IOServiceGetMatchingServices: 0x%x"
+ "Identifier: %s\n"
+ "Insufficient memory for writing zeros."
+ "Payload size %u too small for audio format on stream %zu."
+ "Payload too large writing to stream %zu: %zu"
+ "ReadAudioData"
+ "ReadEventData"
+ "SetNodeProperty kServiceID '%s' failed."
+ "WriteAudioData"
+ "WriteEventData"
+ "algorithm-test"
+ "vector"
- "Stream array contains invalid or missing identifier: %@"
```
