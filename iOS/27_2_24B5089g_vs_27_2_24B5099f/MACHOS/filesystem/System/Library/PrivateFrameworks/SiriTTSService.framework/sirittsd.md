## sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b468` | `0x5c820` | **`+0x13b8`** |
| `__TEXT.__auth_stubs` | `0x2e60` | `0x2f70` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x23fd` | `0x24cd` | **`+0xd0`** |
| `__DATA_CONST.__auth_got` | `0x1738` | `0x17c0` | **`+0x88`** |
| `__TEXT.__eh_frame` | `0x1cb8` | `0x1d40` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0xe60` | `0xe88` | **`+0x28`** |
| `__DATA.__data` | `0x1bb8` | `0x1bc8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8f0` | `0x900` | **`+0x10`** |
| `__TEXT.__const` | `0x1210` | `0x1220` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xb06` | `0xb0e` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.33.1.1.1
+3605.41.1.0.0

-  Functions: 1092
-  Symbols:   1132
-  CStrings:  586
+  Functions: 1100
+  Symbols:   1152
+  CStrings:  588
Symbols:
+ _$s10Foundation13__DataStorageC5bytes6length4copy11deallocator6offsetACSvSg_SiSbySv_SitcSgSitcfc
+ _$s10Foundation13__DataStorageC5bytes6lengthACSVSg_Sitcfc
+ _$s10Foundation13__DataStorageC6_bytesSvSgvg
+ _$s10Foundation13__DataStorageC6lengthACSi_tcfc
+ _$s10Foundation13__DataStorageC7_lengthSivg
+ _$s10Foundation13__DataStorageC7_offsetSivg
+ _$s10Foundation13__DataStorageCMa
+ _$s10Foundation15ContiguousBytesMp
+ _$s10Foundation15ContiguousBytesP010withUnsafeC0yqd__qd__SWKXEKlFTj
+ _$s10Foundation4DataV10LargeSliceV21ensureUniqueReferenceyyF
+ _$s10Foundation4DataV14RangeReferenceCMa
+ _$s10Foundation4DataV15_RepresentationO15replaceSubrange_4with5countySnySiG_SVSgSitF
+ _$s10Foundation4DataV15_RepresentationO6append10contentsOfySW_tF
+ _$s10Foundation4DataV15_RepresentationON
+ _$s14SiriTTSService20VoiceSelectionActionC06selectC5Asset_19synthesizingRequest09disableFmC09requestIdAA0cG0CAA09SynthesisC0C_AA012SynthesizingI8Protocol_AA04BaseI0CXcSgSbs6UInt64VtKFTj
+ _$s14SiriTTSService20VoiceSelectionActionC06selectC5Asset_19synthesizingRequest09disableFmC09requestIdAA0cG0CAA09SynthesisC0C_AA012SynthesizingI8Protocol_AA04BaseI0CXcSgSbs6UInt64VtKFfA1_
+ _$s14SiriTTSService20VoiceSelectionActionC06selectC5Asset_19synthesizingRequest09disableFmC09requestIdAA0cG0CAA09SynthesisC0C_AA012SynthesizingI8Protocol_AA04BaseI0CXcSgSbs6UInt64VtKFfA2_
+ _$s14SiriTTSService27SynthesizingRequestProtocolPAAE20disableFallbackVoiceSbvg
+ _$sSS8UTF8ViewV13_foreignIndex5afterSS0D0VAF_tF
+ _$sSS8UTF8ViewV13_foreignIndex_8offsetBySS0D0VAF_SitF
+ _$sSS8UTF8ViewV17_foreignSubscript8positions5UInt8VSS5IndexV_tF
+ _$sSS8UTF8ViewVN
+ _$sSS9UTF16ViewV5index_8offsetBySS5IndexVAF_SitF
+ _$ss11_StringGutsV8copyUTF84intoSiSgSrys5UInt8VG_tF
- _$s14SiriTTSService20VoiceSelectionActionC06selectC5Asset_22disableThermalFallback0h7CompactC09requestId19synthesizingRequest0h2FmC0AA0cG0CAA09SynthesisC0C_S2bs6UInt64VAA012SynthesizingO8Protocol_AA04BaseO0CXcSgSbtKFTj
- _$s14SiriTTSService20VoiceSelectionActionC06selectC5Asset_22disableThermalFallback0h7CompactC09requestId19synthesizingRequest0h2FmC0AA0cG0CAA09SynthesisC0C_S2bs6UInt64VAA012SynthesizingO8Protocol_AA04BaseO0CXcSgSbtKFfA4_
- _$s14SiriTTSService27SynthesizingRequestProtocolPAAE19disableCompactVoiceSbvg
- _$sSS10FoundationE4data5using20allowLossyConversionAA4DataVSgSSAAE8EncodingV_SbtF
CStrings:
+ "Defaults forceServerTTS %{bool}d, Request forceOspreyTTS %{bool}d"
+ "Disable Osprey since a local FM asset is available"
+ "PCC voice is not enabled due to found a local %{public}s asset already."
+ "Prefer Osprey since internal settings set forceServerTTS"
+ "Prefer PCC since internal settings set forceGMS."
- "Defaults set forceServerTTS"
- "PCC voice is not enabled due to found a local Natural asset already."
- "Request set forceOspreyTTS"
```
