## MOVStreamIO

> `/System/Library/PrivateFrameworks/MOVStreamIO.framework/MOVStreamIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8df3c` | `0x97be8` | **`+0x9cac`** |
| `__TEXT.__const` | `0x3c12` | `0x4524` | **`+0x912`** |
| `__AUTH_CONST.__const` | `0x1130` | `0x1850` | **`+0x720`** |
| `__TEXT.__eh_frame` | `0xb8` | `0x6f0` | **`+0x638`** |
| `__TEXT.__cstring` | `0x8d4d` | `0x92a3` | **`+0x556`** |
| `__DATA.__bss` | `0x7b8` | `0xc90` | **`+0x4d8`** |
| `__AUTH_CONST.__auth_got` | `0xbd8` | `0xf48` | **`+0x370`** |
| `__AUTH_CONST.__objc_const` | `0xf430` | `0xf760` | **`+0x330`** |
| `__TEXT.__constg_swiftt` | `0xd0` | `0x3fc` | **`+0x32c`** |
| `__AUTH.__data` | `—` | `0x318` | **`+0x318`** |
| `__TEXT.__swift5_reflstr` | `0x124` | `0x40c` | **`+0x2e8`** |
| `__TEXT.__swift5_fieldmd` | `0x1d8` | `0x464` | **`+0x28c`** |
| `__TEXT.__unwind_info` | `0x32d0` | `0x3540` | **`+0x270`** |
| `__TEXT.__swift5_typeref` | `0x127` | `0x38e` | **`+0x267`** |
| `__DATA.__data` | `0xb6c` | `0xc9c` | **`+0x130`** |
| `__DATA_CONST.__got` | `0x8a8` | `0x9b0` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0x6c08` | `0x6c88` | **`+0x80`** |
| `__TEXT.__swift5_builtin` | `—` | `0x64` | **`+0x64`** |
| `__DATA_CONST.__objc_selrefs` | `0x33d0` | `0x3430` | **`+0x60`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x70` | **`+0x54`** |
| `__AUTH.__objc_data` | `0x90` | `0xe0` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x78` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x6220` | `0x6260` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xe850` | `0xe890` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3cc0` | `0x3cf6` | **`+0x36`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x54` | **`+0x24`** |
| `__DATA_CONST.__const` | `0xb90` | `0xbb0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x3a8` | `0x3c0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__common` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x674` | `0x678` | **`+0x4`** |

### Other Changes

```diff

-3.39.5.0.0
+3.40.1.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 2555
-  Symbols:   4751
-  CStrings:  1286
+  Functions: 2769
+  Symbols:   4900
+  CStrings:  1319
Symbols:
+ +[MOVStreamIOUtility isSlimTrack:withCompressionFormat:]
+ +[MOVStreamIOUtility isSlimYZipEncodedTrack:]
+ +[MOVStreamIOUtility slimYZipEncoderConfig]
+ +[MOVStreamOutputSettings slimCompressionFormatForConfiguration:]
+ -[MIOWriter finishWarning]
+ -[MIOWriter finishWithCompletionHandler:finishWarningHandler:]
+ -[MIOWriter finishWithTimeout:endTime:completionHandler:finishWarningHandler:]
+ -[MIOWriter setFinishWarning:]
+ -[MOVStreamReader grabNextMetadataForStream:timeRange:error:]
+ -[MOVStreamReader lastAVError]
+ _CMBlockBufferCopyDataBytes
+ _CMBlockBufferGetDataLength
+ _CMSampleBufferCreateReady
+ _CMSampleBufferGetSampleTimingInfo
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_IVAR_$_MIOWriter._finishWarning
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ _VTCompressionSessionEncodeFrameWithOutputHandler
+ _VTDecompressionSessionCreate
+ _VTDecompressionSessionDecodeFrameWithOutputHandler
+ _VTDecompressionSessionInvalidate
+ _VTDecompressionSessionWaitForAsynchronousFrames
+ _VTSessionSetProperties
+ __Block_copy
+ __Block_release
+ __DATA__TtC11MOVStreamIO18PixelBufferEncoder
+ __DATA__TtC11MOVStreamIO19SampleBufferDecoder
+ __DATA__TtC11MOVStreamIOP33_8135F46ADAFE8C6E6DC02D482E2F304215DecodeResultBox
+ __IVARS__TtC11MOVStreamIO18PixelBufferEncoder
+ __IVARS__TtC11MOVStreamIO19SampleBufferDecoder
+ __IVARS__TtC11MOVStreamIOP33_8135F46ADAFE8C6E6DC02D482E2F304215DecodeResultBox
+ __METACLASS_DATA__TtC11MOVStreamIO18PixelBufferEncoder
+ __METACLASS_DATA__TtC11MOVStreamIO19SampleBufferDecoder
+ __METACLASS_DATA__TtC11MOVStreamIOP33_8135F46ADAFE8C6E6DC02D482E2F304215DecodeResultBox
+ ___78-[MIOWriter finishWithTimeout:endTime:completionHandler:finishWarningHandler:]_block_invoke
+ ___block_descriptor_56_e8_32s40bs48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_88_e8_32bs40bs48w_e5_v8?0lw48l8s32l8s40l8
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_closure_destructor
+ ___swift_memcpy16_8
+ ___swift_memcpy24_4
+ ___swift_memcpy24_8
+ ___swift_memcpy25_8
+ ___swift_memcpy33_8
+ ___swift_memcpy4_4
+ ___swift_memcpy56_8
+ ___swift_memcpy8_8
+ __swift_dead_method_stub
+ __swift_implicitisolationactor_to_executor_cast
+ _associated conformance 11MOVStreamIO14VTSessionErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance s6UInt32Vs26ExpressibleByStringLiteral11MOVStreamIO0dE4TypesACP_s01_bc7BuiltindE0
+ _associated conformance s6UInt32Vs26ExpressibleByStringLiteral11MOVStreamIOs0bc23ExtendedGraphemeClusterE0
+ _associated conformance s6UInt32Vs33ExpressibleByUnicodeScalarLiteral11MOVStreamIO0deF4TypesACP_s01_bc7BuiltindeF0
+ _associated conformance s6UInt32Vs43ExpressibleByExtendedGraphemeClusterLiteral11MOVStreamIO0defG4TypesACP_s01_bc7BuiltindefG0
+ _associated conformance s6UInt32Vs43ExpressibleByExtendedGraphemeClusterLiteral11MOVStreamIOs0bc13UnicodeScalarG0
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _get_enum_tag_for_layout_string 10Foundation4DataV15_RepresentationO
+ _get_enum_tag_for_layout_string 11MOVStreamIO14VTSessionErrorO
+ _get_enum_tag_for_layout_string 11MOVStreamIO30SampleBufferSerializationErrorO
+ _kMIOUseSlimYZipCompression
+ _kSlim_kVTCompressionPropertyKey_Format
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_allocError
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_cvw_enumFn_getEnumTag
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_deallocObject
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _swift_defaultActor_initialize
+ _swift_deletedMethodError
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getErrorValue
+ _swift_getForeignTypeMetadata
+ _swift_getSingletonMetadata
+ _swift_lookUpClassMethod
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x27
+ _swift_release_x28
+ _swift_release_x8
+ _swift_retain
+ _swift_retain_x2
+ _swift_retain_x27
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_task_addCancellationHandler
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_removeCancellationHandler
+ _swift_task_switch
+ _swift_updateClassMetadata2
+ _swift_willThrow
+ _symbolic $ss26ExpressibleByStringLiteralP
+ _symbolic $ss33ExpressibleByUnicodeScalarLiteralP
+ _symbolic $ss43ExpressibleByExtendedGraphemeClusterLiteralP
+ _symbolic BD
+ _symbolic SDySSypG
+ _symbolic SS3key_yp5valuet
+ _symbolic SS_ypt
+ _symbolic Say_____G s5UInt8V
+ _symbolic ScCy___________pG 11MOVStreamIO19SampleBufferDecoderC12DecodedFrameV s5ErrorP
+ _symbolic ScCy___________pGSg 11MOVStreamIO19SampleBufferDecoderC12DecodedFrameV s5ErrorP
+ _symbolic Scsy___________pG So17CMSampleBufferRefa s5ErrorP
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ 11MOVStreamIO12BinaryReaderV
+ _symbolic _____ 11MOVStreamIO12BinaryWriterV
+ _symbolic _____ 11MOVStreamIO14VTSessionErrorO
+ _symbolic _____ 11MOVStreamIO15DecodeResultBox33_8135F46ADAFE8C6E6DC02D482E2F3042LLC
+ _symbolic _____ 11MOVStreamIO15DecodeResultBox33_8135F46ADAFE8C6E6DC02D482E2F3042LLC5StateO
+ _symbolic _____ 11MOVStreamIO18PixelBufferEncoderC
+ _symbolic _____ 11MOVStreamIO19SampleBufferDecoderC
+ _symbolic _____ 11MOVStreamIO19SampleBufferDecoderC12DecodedFrameV
+ _symbolic _____ 11MOVStreamIO19SampleBufferDecoderC12EncodedFrameV
+ _symbolic _____ 11MOVStreamIO30SampleBufferSerializationErrorO
+ _symbolic _____ So11CMTimeFlagsV
+ _symbolic _____ So11CVBufferRefa
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ So17CMSampleBufferRefa
+ _symbolic _____ So23VTCompressionSessionRefa
+ _symbolic _____ So25VTDecompressionSessionRefa
+ _symbolic _____ So6CMTimea
+ _symbolic _____ s5Int32V
+ _symbolic _____ s5Int64V
+ _symbolic _____Sg So6CMTimea
+ _symbolic _____XDXMT 11MOVStreamIO18PixelBufferEncoderC
+ _symbolic ______SS7contextt s5Int32V
+ _symbolic ______p s5ErrorP
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 11MOVStreamIO15DecodeResultBox33_8135F46ADAFE8C6E6DC02D482E2F3042LLC5StateO
+ _symbolic _____y_____SgG 2os21OSAllocatedUnfairLockV 11MOVStreamIO14VTSessionErrorO
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 11MOVStreamIO14VTSessionErrorO So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 11MOVStreamIO15DecodeResultBox33_8135F46ADAFE8C6E6DC02D482E2F3042LLC5StateO So16os_unfair_lock_sV
+ _symbolic _____y___________pG s6ResultOsRi_zRi0_zrlE 11MOVStreamIO19SampleBufferDecoderC12DecodedFrameV s5ErrorP
+ _symbolic _____y___________p_G Scs12ContinuationV So17CMSampleBufferRefa s5ErrorP
+ _symbolic _____y___________p__G Scs12ContinuationV11YieldResultO So17CMSampleBufferRefa s5ErrorP
+ _symbolic _____y___________p__G Scs12ContinuationV15BufferingPolicyO So17CMSampleBufferRefa s5ErrorP
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _symbolic yp
+ _type_layout_string 11MOVStreamIO12BinaryReaderV
+ _type_layout_string 11MOVStreamIO12BinaryWriterV
+ _type_layout_string 11MOVStreamIO14VTSessionErrorO
+ _type_layout_string 11MOVStreamIO19SampleBufferDecoderC12DecodedFrameV
+ _type_layout_string 11MOVStreamIO19SampleBufferDecoderC12EncodedFrameV
+ _type_layout_string 11MOVStreamIO30SampleBufferSerializationErrorO
+ _type_layout_string So11CMTimeFlagsV
+ _type_layout_string So6CMTimea
- GCC_except_table85
- ___57-[MIOWriter finishWithTimeout:endTime:completionHandler:]_block_invoke
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
- ___block_descriptor_88_e8_32s40bs48w_e5_v8?0lw48l8s40l8s32l8
- ___swift_memcpy32_8
- _kSlim_kVTCompressionPropertyKey_SlimXFormat
- _symbolic SaySJG
- _symbolic _____ySJG s23_ContiguousArrayStorageC
CStrings:
+ " failed with OSStatus "
+ " must be greater than the previous pts "
+ "3.40.1"
+ "CMBlockBufferCopyDataBytes"
+ "CMBlockBufferCreateWithMemoryBlock"
+ "CMBlockBufferReplaceDataBytes"
+ "CMSampleBufferCreateReady"
+ "CMSampleBufferGetSampleTimingInfo"
+ "CMVideoFormatDescriptionCreate"
+ "End of metadata stream."
+ "Plain 'slim' encoding is deprecated. Use slimX (kMIOUseSlimXCompression) or another encoder instead."
+ "UseSlimYZipCompression"
+ "VTCompressionSessionCompleteFrames"
+ "VTCompressionSessionCreate"
+ "VTCompressionSessionEncodeFrame"
+ "VTDecompressionSessionCreate"
+ "VTDecompressionSessionDecodeFrame"
+ "VTSessionError: "
+ "VTSessionError: frame was dropped"
+ "VTSessionError: invalid input - "
+ "VTSessionError: output callback fired with no buffer despite a successful status"
+ "VTSessionError: session has already been invalidated by finish()"
+ "VTSessionSetProperties"
+ "decode output callback"
+ "decoded plist was not a dictionary"
+ "encode output callback"
+ "expected exactly 1 sample, got "
+ "failed to decode plist dictionary: "
+ "failed to encode plist dictionary: "
+ "missing data buffer"
+ "missing video format description"
+ "payload too large to length-prefix: "
+ "sample data length overflows Int: "
+ "truncated record: expected "
+ "unsupported format version "
- "3.39.5"
- "Error on saving session start time: %{public}@"
```
