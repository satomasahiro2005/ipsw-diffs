## CMPhoto

> `/System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e3ab0` | `0x1e4d68` | **`+0x12b8`** |
| `__TEXT.__const` | `0x13564` | `0x136a4` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0xc680` | `0xc740` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x1450` | `0x14ae` | **`+0x5e`** |
| `__AUTH_CONST.__cfstring` | `0x5f6e0` | `0x5f6a0` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x45c4` | `0x4604` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1e80` | `0x1eb4` | **`+0x34`** |
| `__TEXT.__cstring` | `0x4aaef` | `0x4ab1f` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0xa54` | `0xa84` | **`+0x30`** |
| `__DATA.__data` | `0xea8` | `0xec8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4728` | `0x4748` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x19a8` | `0x19c4` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xa0` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2570` | `0x2580` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x98af0` | `0x98ae0` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x848` | `0x858` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1575` | `0x1585` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x38f4` | `0x38ec` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x214` | `0x218` | **`+0x4`** |

### Other Changes

```diff

-483.0.0.0.0
+486.0.0.0.1

-  Functions: 7600
-  Symbols:   11854
-  CStrings:  13487
+  Functions: 7628
+  Symbols:   11869
+  CStrings:  13488
Symbols:
+ _CMPhotoInterleaveCFADataInto
+ _JxlDecoderSetCms
+ _JxlDecoderSetOutputColorProfile
+ _JxlGetDefaultCms
+ _OUTLINED_FUNCTION_160
+ _OUTLINED_FUNCTION_161
+ _OUTLINED_FUNCTION_162
+ _SlimVideoEncoder_WorstCaseRawPayloadSize
+ ___swift_closure_destructor.127Tm
+ ___swift_memcpy33_8
+ __findBestChromaHalfPixelShift
+ __findBestHalfPixelShift
+ __sadAtHalfShift
+ _get_enum_tag_for_layout_string 7CMPhoto15TIFFDataPayloadO
+ _kHalfPixelShiftCandidates
+ _symbolic SDy_____Say_____GG s6UInt16V 7CMPhoto15TIFFDataPayloadO
+ _symbolic Say___________tG 7CMPhoto16TIFFMemoryWriter33_F6096635BB59448AD24FA2064A4EAF27LLC14OffsetEntryKeyV AA15TIFFDataPayloadO
+ _symbolic _____ 7CMPhoto15TIFFDataPayloadO
+ _symbolic _____6source______14absoluteOffsetSi9byteCountt 7CMPhoto10ParserSpanC s6UInt32V
+ _symbolic _____Sg 7CMPhoto10ParserSpanC
+ _symbolic ___________t 7CMPhoto16TIFFMemoryWriter33_F6096635BB59448AD24FA2064A4EAF27LLC14OffsetEntryKeyV AA15TIFFDataPayloadO
+ _symbolic _____y_____5tagID_Si9listIndextG s23_ContiguousArrayStorageC s6UInt16V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 7CMPhoto15TIFFDataPayloadO
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC s6UInt16V 7CMPhoto15TIFFDataPayloadO
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC 7CMPhoto16TIFFMemoryWriter33_F6096635BB59448AD24FA2064A4EAF27LLC14OffsetEntryKeyV AC15TIFFDataPayloadO
+ _type_layout_string 7CMPhoto15TIFFDataPayloadO
- _CFStringCreateByCombiningStrings
- _CMPhotoAddMeteorPlusGainMapMetadata
- _CMPhotoAddValueToCGMutableImageMetadata
- ___swift_closure_destructor.116Tm
- _kCMPhotoHDRMeteorGainMapCGImageMetadataKey_HDRGainMapVersion
- _kCMPhotoHDRMeteorGainMapCGImageMetadataPrefix
- _symbolic SDy_____Say_____GG s6UInt16V 10Foundation4DataV
- _symbolic Say___________tG 7CMPhoto16TIFFMemoryWriter33_F6096635BB59448AD24FA2064A4EAF27LLC14OffsetEntryKeyV 10Foundation4DataV
- _symbolic ___________t 7CMPhoto16TIFFMemoryWriter33_F6096635BB59448AD24FA2064A4EAF27LLC14OffsetEntryKeyV 10Foundation4DataV
- _symbolic _____y_____Say_____GG s18_DictionaryStorageC s6UInt16V 10Foundation4DataV
- _symbolic _____y___________tG s23_ContiguousArrayStorageC 7CMPhoto16TIFFMemoryWriter33_F6096635BB59448AD24FA2064A4EAF27LLC14OffsetEntryKeyV 10Foundation4DataV
CStrings:
+ "<<<< CMPhotoDetectCorruption >>>>"
+ "Could not reference data payload at offset %u, size %u: %s"
+ "Payload at %u (+%ld) exceeds the %ld reachable bytes"
+ "deferred(validating:absoluteOffset:byteCount:)"
- "Could not read data payload at offset %u, size %u: %s"
- "HDRGainMap"
- "HDRGainMapVersion"
```
