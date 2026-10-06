## ColorSync

> `/System/Library/Frameworks/ColorSync.framework/ColorSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62c70` | `0x64538` | **`+0x18c8`** |
| `__AUTH_CONST.__const` | `0x6cd0` | `0x7358` | **`+0x688`** |
| `__TEXT.__const` | `0x1224f0` | `0x122880` | **`+0x390`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x2b5` | **`+0x2b5`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x270` | **`+0x270`** |
| `__TEXT.__constg_swiftt` | `—` | `0x1a4` | **`+0x1a4`** |
| `__TEXT.__eh_frame` | `—` | `0x130` | **`+0x130`** |
| `__TEXT.__swift5_typeref` | `—` | `0x114` | **`+0x114`** |
| `__TEXT.__unwind_info` | `0x10a8` | `0x1168` | **`+0xc0`** |
| `__DATA.__bss` | `0x1100` | `0x1180` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x5f8` | `0x660` | **`+0x68`** |
| `__TEXT.__cstring` | `0x70d8` | `0x7086` | **`-0x52`** |
| `__TEXT.__swift5_types` | `—` | `0x34` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x1cd0` | `0x1d00` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4de0` | `0x4dc0` | **`-0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA.__data` | `0x908` | `0x918` | **`+0x10`** |
| `__DATA_CONST.__objc_imageinfo` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xeac` | `0xeb0` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-3917.0.0.0.0
+3922.0.0.0.0

+  - /System/Library/Frameworks/Foundation.framework/Foundation

-  Functions: 1573
-  Symbols:   2948
-  CStrings:  902
+  - /usr/lib/libobjc.A.dylib
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  Functions: 1701
+  Symbols:   3019
+  CStrings:  901
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__16vectorI10CMMTagInfo10TAllocatorIS1_EE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorI10CMMTagInfo10TAllocatorIS1_EE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI10CMMTagInfo10TAllocatorIS1_EE20__throw_out_of_rangeB9fqe220106Ev
+ __ZNSt3__16vectorI14CMMProfileInfo10TAllocatorIS1_EE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorI14CMMProfileInfo10TAllocatorIS1_EE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI14CMMProfileInfo10TAllocatorIS1_EE20__throw_out_of_rangeB9fqe220106Ev
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy0_1
+ ___swift_memcpy17_8
+ ___swift_memcpy24_8
+ ___swift_memcpy25_4
+ ___swift_memcpy33_4
+ ___swift_memcpy48_8
+ ___swift_memcpy56_8
+ ___swift_memcpy64_8
+ ___swift_memcpy72_8
+ ___swift_memcpy8_8
+ ___swift_noop_void_return
+ ___swift_reflection_version
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_ColorSync
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_ColorSync
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_ColorSync
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_ColorSync
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_ColorSync
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_ColorSync
+ _get_enum_tag_for_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingVSg
+ _get_enum_tag_for_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformVSg
+ _kColorSyncControlPointSlopes
+ _kColorSyncLookupTableScale
+ _swift_allocError
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_getForeignTypeMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getWitnessTable
+ _swift_retain_x19
+ _swift_willThrow
+ _symbolic SaySfG
+ _symbolic Say_____G So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V
+ _symbolic Sf
+ _symbolic Sf3red_Sf5greenSf4blueSf6maxRGBSf03minE0Sf9componentt
+ _symbolic SfSg
+ _symbolic Si1x_Si1yt
+ _symbolic Si3got_Si8expectedt
+ _symbolic Si5count_Si5limitt
+ _symbolic _____ So19ColorSyncProfileRefa
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V12ComponentMixO
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V13ControlPointsV
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V13ControlPointsV6SlopesO
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO0fgH0V
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO14ChromaticitiesO
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV5ErrorO
+ _symbolic _____ So19ColorSyncProfileRefa0aB0E32HeadroomAdaptiveGainCurveOptionsV
+ _symbolic _____ s5UInt8V
+ _symbolic _____Sg So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV
+ _symbolic _____Sg So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV
+ _symbolic _____y$1_SfG3red_AB5greenAB4blueAB5whitet s11InlineArrayVsRi__rlE
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V13ControlPointsV
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO09AlternateH0V13ControlPointsV6SlopesO
+ _type_layout_string So19ColorSyncProfileRefa0aB0E25HeadroomAdaptiveGainCurveV0A15VolumeTransformV11ToneMappingV6MethodO0fgH0V
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9fqe220100EPKc
- __ZNSt3__16vectorI10CMMTagInfo10TAllocatorIS1_EE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorI10CMMTagInfo10TAllocatorIS1_EE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI10CMMTagInfo10TAllocatorIS1_EE20__throw_out_of_rangeB9fqe220100Ev
- __ZNSt3__16vectorI14CMMProfileInfo10TAllocatorIS1_EE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorI14CMMProfileInfo10TAllocatorIS1_EE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI14CMMProfileInfo10TAllocatorIS1_EE20__throw_out_of_rangeB9fqe220100Ev
- __ZZN8CMMTable20CreateHAGCurveLookupEfP21icHAGCurveDataDecodedfPK14__CFDictionarymP14icComponentMixP29icComponentMixCoefficientInfoPfR9CMMMemMgrE7pattern
- _kColorSynReferenceWhiteToneMapping
- _kColorSyncControlPointsSlope
- _kColorSyncLastControlPointX
CStrings:
+ "\tHeadroom Adaptive Gain Tone Mapping params:\n\t\tsource headroom = % 3.10f\n\t\ttarget headroom = % 3.10f\n\t\tlookup table scale = % 3.10f\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tHeadroom Adaptive Gain Table Count = %zu\n\t\tHeadroom Adaptive Gain Table = %p\n"
+ "com.apple.cmm.ControlPointSlopes"
+ "com.apple.cmm.LookupTableScale"
- "\tHeadroom Adaptive Gain Tone Mapping params:\n\t\tsource headroom = % 3.10f\n\t\ttarget headroom = % 3.10f\n\t\tlast control point X = % 3.10f\n\t\tcomponent mixing type = % d\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tcoefficients[%s] info {flag = %s, = % 3.10f}\n\t\tHeadroom Adaptive Gain Table Count = %zu\n\t\tHeadroom Adaptive Gain Table = %p\n"
- "com.apple.cmm.ControlPointsSlope"
- "com.apple.cmm.LastControlPointX"
- "com.apple.cmm.kColorSynReferenceWhiteToneMapping"
```
