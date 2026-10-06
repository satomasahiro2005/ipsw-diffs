## SensorKit

> `/System/Library/Frameworks/SensorKit.framework/SensorKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44cc8` | `0x45bd4` | **`+0xf0c`** |
| `__AUTH_CONST.__const` | `0x13d8` | `0x15e0` | **`+0x208`** |
| `__AUTH_CONST.__objc_const` | `0xa828` | `0xa688` | **`-0x1a0`** |
| `__TEXT.__objc_methlist` | `0x56cc` | `0x55d4` | **`-0xf8`** |
| `__TEXT.__swift5_capture` | `0xc0` | `0x158` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x2248` | `0x21b8` | **`-0x90`** |
| `__AUTH_CONST.__auth_got` | `0x748` | `0x7d0` | **`+0x88`** |
| `__TEXT.__cstring` | `0x5c36` | `0x5baf` | **`-0x87`** |
| `__DATA_CONST.__const` | `0x12f8` | `0x1280` | **`-0x78`** |
| `__AUTH_CONST.__cfstring` | `0x5d20` | `0x5cc0` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x1788` | `0x1738` | **`-0x50`** |
| `__TEXT.__const` | `0x1ae8` | `0x1a98` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x448` | `0x480` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x398` | `0x368` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0x8c8` | `0x898` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x8ca` | `0x8f8` | **`+0x2e`** |
| `__DATA_DIRTY.__bss` | `0x160` | `0x180` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x658` | `0x640` | **`-0x18`** |
| `__DATA.__bss` | `0x2d48` | `0x2d38` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x404` | `0x410` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0x14a` | `0x155` | **`+0xb`** |
| `__DATA.__data` | `0x11d8` | `0x11d0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2a8` | `0x2a0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x250` | `0x248` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1650` | `0x1658` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x20` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x4dd3` | `0x4dd4` | **`+0x1`** |

### Other Changes

```diff

-1027.0.0.0.0
+1036.0.0.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 2317
-  Symbols:   4031
-  CStrings:  1147
+  Functions: 2330
+  Symbols:   3997
+  CStrings:  1140
Symbols:
+ GCC_except_table32
+ ___conditionsForOpticalSample_block_invoke
+ ___conditionsForOpticalSample_block_invoke_2
+ ___conditionsForOpticalSample_block_invoke_3
+ ___swift_get_extra_inhabitant_indexTm
+ ___swift_store_extra_inhabitant_indexTm
+ _associated conformance 9SensorKit16SRYieldingStreamV13AsyncIteratorVyx_GScIAA7FailureScI_s5Error
+ _associated conformance 9SensorKit16SRYieldingStreamVyxGSciAA13AsyncIteratorSci_ScI
+ _get_witness_table 9SensorKit06SRDataA0RzlAA16SRYieldingStreamVy6SampleQzGSciHPyHC
+ _get_witness_table 9SensorKit06SRDataA0RzlAA16SRYieldingStreamVySo16SRDeletionRecordCGSciHPyHC
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_retain
+ _swift_retain_x8
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_unknownObjectRelease
+ _symbolic B1
+ _symbolic Scsy_____yxG______pG 9SensorKit15SRFetchResponseV s5ErrorP
+ _symbolic Si
+ _symbolic So13SRFetchResultC
+ _symbolic _____ 9SensorKit16SRYieldingStreamV
+ _symbolic _____ 9SensorKit16SRYieldingStreamV13AsyncIteratorV
+ _symbolic _____y6Sample_____QzG 9SensorKit16SRYieldingStreamV AA06SRDataA0P
+ _symbolic _____ySbG 15Synchronization6AtomicV
+ _symbolic _____ySbG_Xx 15Synchronization6AtomicV
+ _symbolic _____ySo16SRDeletionRecordCG 9SensorKit16SRYieldingStreamV
+ _symbolic _____y_____yqd__G______p_G Scs12ContinuationV 9SensorKit15SRFetchResponseV s5ErrorP
+ _symbolic _____y_____yxG______p_G Scs8IteratorV 9SensorKit15SRFetchResponseV s5ErrorP
+ _symbolic _____yx_G 9SensorKit16SRYieldingStreamV13AsyncIteratorV
- +[SRFetchResultBuffer initialize]
- -[SRFetchResultBuffer addSampleToBuffer:]
- -[SRFetchResultBuffer bufferSizeLimit]
- -[SRFetchResultBuffer buffer]
- -[SRFetchResultBuffer dealloc]
- -[SRFetchResultBuffer fetchRequest]
- -[SRFetchResultBuffer getSampleFromBuffer]
- -[SRFetchResultBuffer hasStoredSamples]
- -[SRFetchResultBuffer initWithReader:fetchRequest:]
- -[SRFetchResultBuffer initWithReader:fetchRequest:bufferSize:]
- -[SRFetchResultBuffer isReadyToEmitSamples]
- -[SRFetchResultBuffer nextResultWithCompletionHandler:]
- -[SRFetchResultBuffer reader]
- -[SRFetchResultBuffer setBuffer:]
- -[SRFetchResultBuffer setBufferSizeLimit:]
- -[SRFetchResultBuffer setFetchRequest:]
- -[SRFetchResultBuffer setReader:]
- -[SRFetchResultBuffer updateFetchRequestFromSample]
- -[SRSensorReader fetch:fetchResultHandler:fetchFailedWithErrorHandler:]
- GCC_except_table25
- GCC_except_table31
- GCC_except_table35
- GCC_except_table39
- _OBJC_CLASS_$_SRFetchResultBuffer
- _OBJC_IVAR_$_SRFetchResultBuffer._buffer
- _OBJC_IVAR_$_SRFetchResultBuffer._bufferSize
- _OBJC_IVAR_$_SRFetchResultBuffer._bufferSizeLimit
- _OBJC_IVAR_$_SRFetchResultBuffer._fetchComplete
- _OBJC_IVAR_$_SRFetchResultBuffer._fetchRequest
- _OBJC_IVAR_$_SRFetchResultBuffer._reader
- _OBJC_METACLASS_$_SRFetchResultBuffer
- _SRFetchResultBufferLog
- __OBJC_$_CLASS_METHODS_SRFetchResultBuffer
- __OBJC_$_INSTANCE_METHODS_SRFetchResultBuffer
- __OBJC_$_INSTANCE_VARIABLES_SRFetchResultBuffer
- __OBJC_$_PROP_LIST_SRFetchResultBuffer
- __OBJC_CLASS_RO_$_SRFetchResultBuffer
- __OBJC_METACLASS_RO_$_SRFetchResultBuffer
- ___55-[SRFetchResultBuffer nextResultWithCompletionHandler:]_block_invoke
- ___71-[SRSensorReader fetch:fetchResultHandler:fetchFailedWithErrorHandler:]_block_invoke
- ___71-[SRSensorReader fetch:fetchResultHandler:fetchFailedWithErrorHandler:]_block_invoke_2
- ___block_descriptor_48_e8_32b40r_e23_B16?0"SRFetchResult"8ls32l8r40l8
- ___block_descriptor_48_e8_32b40r_e5_v8?0lr40l8s32l8
- ___block_descriptor_48_e8_32b40w_e23_B16?0"SRFetchResult"8lw40l8s32l8
- ___sizeOfFetchResult_block_invoke
- ___swift_allocate_boxed_opaque_existential_0
- ___swift_project_boxed_opaque_existential_0
- ___unnamed_4
- ___unnamed_6
- _associated conformance 9SensorKit23SRFetchResponseSequenceV13AsyncIteratorVyx_GScIAA7FailureScI_s5Error
- _associated conformance 9SensorKit23SRFetchResponseSequenceVyxGSciAA13AsyncIteratorSci_ScI
- _class_getInstanceSize
- _get_witness_table 9SensorKit06SRDataA0RzlAA23SRFetchResponseSequenceVy6SampleQzGSciHPyHC
- _get_witness_table 9SensorKit06SRDataA0RzlAA23SRFetchResponseSequenceVySo16SRDeletionRecordCGSciHPyHC
- _sizeOfFetchResult
- _symbolic ScCySo13SRFetchResultCSg______pG s5ErrorP
- _symbolic So13SRFetchResultCSg
- _symbolic So19SRFetchResultBufferC
- _symbolic _____ 9SensorKit23SRFetchResponseSequenceV
- _symbolic _____ 9SensorKit23SRFetchResponseSequenceV13AsyncIteratorV
- _symbolic _____y6Sample_____QzG 9SensorKit23SRFetchResponseSequenceV AA06SRDataA0P
- _symbolic _____ySo16SRDeletionRecordCG 9SensorKit23SRFetchResponseSequenceV
- _symbolic _____yx_G 9SensorKit23SRFetchResponseSequenceV13AsyncIteratorV
- _type_layout_string l9SensorKit23SRFetchResponseSequenceVyxG
CStrings:
+ "Fetch operation failed for sensor %s: %@"
- "B16@?0@\"SRFetchResult\"8"
- "SRFetchResultBuffer"
- "SRFetchResultBuffer.m"
- "Sample fetch failed because of %@"
- "Self is nil."
- "_createCheckedThrowingContinuation(_:)"
- "fetchRequest"
- "reader"
```
