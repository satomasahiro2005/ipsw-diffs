## PhotosRendering

> `/System/Library/PrivateFrameworks/PhotosRendering.framework/PhotosRendering`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xd00` | `0x880` | **`-0x480`** |
| `__AUTH_CONST.__const` | `0x1338` | `0x14c8` | **`+0x190`** |
| `__TEXT.__constg_swiftt` | `0x950` | `0xa68` | **`+0x118`** |
| `__TEXT.__text` | `0x19d34` | `0x19c60` | **`-0xd4`** |
| `__DATA_DIRTY.__data` | `0x4b8` | `0x400` | **`-0xb8`** |
| `__TEXT.__swift5_typeref` | `0x762` | `0x814` | **`+0xb2`** |
| `__AUTH_CONST.__auth_got` | `0x7f0` | `0x760` | **`-0x90`** |
| `__DATA.__data` | `0x900` | `0x988` | **`+0x88`** |
| `__TEXT.__const` | `0x11c0` | `0x1140` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0x1118` | `0x1098` | **`-0x80`** |
| `__AUTH.__objc_data` | `0x90` | `0xe0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x140` | `0xf0` | **`-0x50`** |
| `__AUTH.__data` | `0x328` | `0x360` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x385` | `0x3a5` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x908` | `0x8e8` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0xd0` | `0xb4` | **`-0x1c`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xc8` | **`+0x14`** |
| `__TEXT.__cstring` | `0x62a` | `0x63a` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x834` | `0x844` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4e8` | `0x4e0` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x28` | `0x2c` | **`+0x4`** |

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

-  Functions: 953
-  Symbols:   667
-  CStrings:  52
+  Functions: 942
+  Symbols:   673
+  CStrings:  49
Symbols:
+ _OBJC_CLASS_$_NSString
+ __DATA__TtC15PhotosRendering13RenderSession
+ __IVARS__TtC15PhotosRendering13RenderContext
+ __IVARS__TtC15PhotosRendering13RenderSession
+ __METACLASS_DATA__TtC15PhotosRendering13RenderSession
+ ___swift_memcpy24_8
+ ___unnamed_14
+ ___unnamed_9
+ _associated conformance 15PhotosRendering14ComputeRequestVAA06RenderD0AA10ResultTypeAaDP_AA0eF0
+ _associated conformance 15PhotosRendering17BitmapDestinationVAA011ImageRenderD0AA6ResultAaDP_AA0fG0
+ _associated conformance 15PhotosRendering18ImageRenderRequestVyxGAA0dE0AA10ResultTypeAaEP_AA0dF0
+ _associated conformance 15PhotosRendering22PixelBufferDestinationVAA011ImageRenderE0AA6ResultAaDP_AA0gH0
+ _get_witness_table 15PhotosRendering13RenderRequestRzlScSyAA0C8ResponseVy10ResultTypeQzGGSciHPyHC
+ _swift_checkMetadataState
+ _swift_retain_x23
+ _symbolic $s15PhotosRendering12RenderResultP
+ _symbolic $s15PhotosRendering13RenderRequestP
+ _symbolic $s15PhotosRendering22ImageRenderDestinationP
+ _symbolic 10ResultType_____Qz 15PhotosRendering13RenderRequestP
+ _symbolic 6Result_____Qz 15PhotosRendering22ImageRenderDestinationP
+ _symbolic 7ElementSciQyd__
+ _symbolic 7FailureSciQyd__
+ _symbolic ScSy_____y10ResultType_____QzGG 15PhotosRendering14RenderResponseV AA0C7RequestP
+ _symbolic So12NUColorSpaceCSg
+ _symbolic _____ 15PhotosRendering12BitmapResultV
+ _symbolic _____ 15PhotosRendering13RenderContextC
+ _symbolic _____ 15PhotosRendering13RenderSessionC
+ _symbolic _____ 15PhotosRendering13RenderSessionC10AttributesV
+ _symbolic _____ 15PhotosRendering13RenderSessionC12MemoryBudgetO
+ _symbolic _____ 15PhotosRendering14RenderResponseV
+ _symbolic _____ 15PhotosRendering16RenderStatisticsV
+ _symbolic _____ 15PhotosRendering17BitmapDestinationV
+ _symbolic _____ 15PhotosRendering17PixelBufferResultV
+ _symbolic _____ 15PhotosRendering18ImageRenderRequestV
+ _symbolic _____ 15PhotosRendering22PixelBufferDestinationV
+ _symbolic _____ 15PhotosRendering23RenderContextAttributesV
+ _symbolic _____ 15PhotosRendering23RenderContextAttributesV14SchedulingModeO
+ _symbolic _____ 15PhotosRendering23RenderContextAttributesV15RateControlModeO
+ _symbolic _____ 15PhotosRendering23RenderContextAttributesV17CoalescingOptionsV
+ _symbolic _____ 15PhotosRendering23RenderContextAttributesV18RateControlOptionsV
+ _symbolic _____ 15PhotosRendering23RenderContextAttributesV8PriorityV
+ _symbolic _____ So10CGImageRefa
+ _symbolic _____ s5NeverO
+ _symbolic _____Sg 9CoreVideo17CVPixelFormatTypeV
+ _symbolic _____Sg So15CGColorSpaceRefa
+ _symbolic _____y10ResultType_____QzG 15PhotosRendering14RenderResponseV AA0C7RequestP
+ _symbolic _____y_____G 15PhotosRendering18ImageRenderRequestV AA22PixelBufferDestinationV
+ _symbolic _____y_____y10ResultType_____QzG_G ScS12ContinuationV 15PhotosRendering14RenderResponseV AC0D7RequestP
+ _symbolic _____yxGSgXw 15PhotosRendering13RenderContextC
+ _symbolic _____yxGSgXwz_x______RzlXX 15PhotosRendering13RenderContextC AA0C7RequestP
+ _symbolic qd__
+ _type_layout_string 15PhotosRendering12BitmapResultV
+ _type_layout_string 15PhotosRendering12RenderResultRzlAA0C8ResponseVyxG
+ _type_layout_string 15PhotosRendering13RenderSessionC10AttributesV
+ _type_layout_string 15PhotosRendering16RenderStatisticsV
+ _type_layout_string 15PhotosRendering17BitmapDestinationV
+ _type_layout_string 15PhotosRendering17PixelBufferResultV
+ _type_layout_string 15PhotosRendering23RenderContextAttributesV18RateControlOptionsV
- _OUTLINED_FUNCTION_150
- _OUTLINED_FUNCTION_151
- _OUTLINED_FUNCTION_152
- _OUTLINED_FUNCTION_153
- _OUTLINED_FUNCTION_154
- __DATA__TtC15PhotosRendering7Session
- __IVARS__TtC15PhotosRendering7Context
- __IVARS__TtC15PhotosRendering7Session
- __METACLASS_DATA__TtC15PhotosRendering7Session
- ___unnamed_11
- ___unnamed_7
- _associated conformance 15PhotosRendering10RenderTimeO10CodingKeys33_7CBA3D948920DCE683699E619EA8C973LLOSHAASQ
- _associated conformance 15PhotosRendering10RenderTimeO10CodingKeys33_7CBA3D948920DCE683699E619EA8C973LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 15PhotosRendering10RenderTimeO10CodingKeys33_7CBA3D948920DCE683699E619EA8C973LLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 15PhotosRendering13RenderRequestVAA0D0AA10ResultTypeAaDP_AA0E0
- _associated conformance 15PhotosRendering14ComputeRequestVAA0D0AA10ResultTypeAaDP_AA0E0
- _associated conformance 15PhotosRendering17ContextAttributesV14CoalescingModeOSHAASQ
- _get_enum_tag_for_layout_string 15PhotosRendering10ColorSpaceO
- _swift_allocError
- _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
- _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
- _swift_cvw_singlePayloadEnumGeneric_getEnumTag
- _swift_retain_x24
- _symbolic $s15PhotosRendering6ResultP
- _symbolic $s15PhotosRendering7RequestP
- _symbolic 10ResultType_____Qz 15PhotosRendering7RequestP
- _symbolic ScSy_____y10ResultType_____QzGG 15PhotosRendering8ResponseV AA7RequestP
- _symbolic _____ 15PhotosRendering10ColorSpaceO
- _symbolic _____ 15PhotosRendering10RenderTimeO10CodingKeys33_7CBA3D948920DCE683699E619EA8C973LLO
- _symbolic _____ 15PhotosRendering11PixelFormatO
- _symbolic _____ 15PhotosRendering12RenderResultV
- _symbolic _____ 15PhotosRendering13RenderRequestV
- _symbolic _____ 15PhotosRendering17ContextAttributesV
- _symbolic _____ 15PhotosRendering17ContextAttributesV14CoalescingModeO
- _symbolic _____ 15PhotosRendering17ContextAttributesV15RateControlModeO
- _symbolic _____ 15PhotosRendering17ContextAttributesV8PriorityV
- _symbolic _____ 15PhotosRendering7ContextC
- _symbolic _____ 15PhotosRendering7SessionC
- _symbolic _____ 15PhotosRendering7SessionC10AttributesV
- _symbolic _____ 15PhotosRendering7SessionC12MemoryBudgetO
- _symbolic _____ 15PhotosRendering8ResponseV
- _symbolic _____ 9CoreVideo17CVPixelFormatTypeV
- _symbolic _____ So15CGColorSpaceRefa
- _symbolic _____y_____G s22KeyedDecodingContainerV 15PhotosRendering10RenderTimeO10CodingKeys33_7CBA3D948920DCE683699E619EA8C973LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 15PhotosRendering10RenderTimeO10CodingKeys33_7CBA3D948920DCE683699E619EA8C973LLO
- _symbolic _____y_____y10ResultType_____QzG_G ScS12ContinuationV 15PhotosRendering8ResponseV AC7RequestP
- _symbolic _____yxGSgXw 15PhotosRendering7ContextC
- _symbolic _____yxGSgXwz_x______RzlXX 15PhotosRendering7ContextC AA7RequestP
- _type_layout_string 15PhotosRendering10ColorSpaceO
- _type_layout_string 15PhotosRendering12RenderResultV
- _type_layout_string 15PhotosRendering6ResultRzlAA8ResponseVyxG
- _type_layout_string 15PhotosRendering7SessionC10AttributesV
CStrings:
+ "Failed to create CGImage from rendered result"
+ "PhotosRendering/RenderContext.swift"
+ "PhotosRendering/RenderRequest.swift"
- "PhotosRendering/Context.swift"
- "PhotosRendering/Request.swift"
- "Unknown RenderTime type: "
- "timescale"
- "type"
- "value"
```
