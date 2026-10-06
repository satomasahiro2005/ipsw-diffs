## CoreSpeechUtils

> `/System/Library/PrivateFrameworks/CoreSpeechUtils.framework/CoreSpeechUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28c7c` | `0x39b08` | **`+0x10e8c`** |
| `__TEXT.__swift5_fieldmd` | `0xf8c` | `0x1b5c` | **`+0xbd0`** |
| `__TEXT.__const` | `0x1728` | `0x2288` | **`+0xb60`** |
| `__AUTH_CONST.__const` | `0x1758` | `0x2298` | **`+0xb40`** |
| `__DATA.__bss` | `0xa00` | `0x1080` | **`+0x680`** |
| `__TEXT.__swift5_reflstr` | `0x151c` | `0x19fc` | **`+0x4e0`** |
| `__TEXT.__constg_swiftt` | `0xb70` | `0xe94` | **`+0x324`** |
| `__AUTH_CONST.__objc_const` | `0x1f30` | `0x2248` | **`+0x318`** |
| `__TEXT.__unwind_info` | `0x8c0` | `0xb98` | **`+0x2d8`** |
| `__TEXT.__eh_frame` | `0x170` | `0x438` | **`+0x2c8`** |
| `__AUTH.__data` | `0x98` | `0x338` | **`+0x2a0`** |
| `__TEXT.__swift5_typeref` | `0x3d2` | `0x5b6` | **`+0x1e4`** |
| `__TEXT.__cstring` | `0x17a3` | `0x18c3` | **`+0x120`** |
| `__AUTH_CONST.__auth_got` | `0x6b0` | `0x778` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x103e` | `0x10ae` | **`+0x70`** |
| `__DATA.__data` | `0x490` | `0x4e8` | **`+0x58`** |
| `__TEXT.__swift5_proto` | `0x54` | `0xac` | **`+0x58`** |
| `__TEXT.__swift5_types` | `0xb8` | `0x104` | **`+0x4c`** |
| `__DATA_CONST.__const` | `0x108` | `0x150` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0xa8` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0xa8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x160` | `0x178` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x10` | **`+0xc`** |

### Other Changes

```diff

-3600.70.32.0.0
+3600.70.47.0.0

-  Functions: 1206
-  Symbols:   380
-  CStrings:  225
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 2069
+  Symbols:   461
+  CStrings:  234
Symbols:
+ __DATA__TtC15CoreSpeechUtils15Int16SamplePool
+ __DATA__TtC15CoreSpeechUtils22PolarisResourceEncoder
+ __DATA__TtC15CoreSpeechUtils24PolarisAudioBatchEncoder
+ __DATA__TtC15CoreSpeechUtils26PolarisGestureBatchEncoder
+ __IVARS__TtC15CoreSpeechUtils15Int16SamplePool
+ __IVARS__TtC15CoreSpeechUtils24PolarisAudioBatchEncoder
+ __IVARS__TtC15CoreSpeechUtils26PolarisGestureBatchEncoder
+ __METACLASS_DATA__TtC15CoreSpeechUtils15Int16SamplePool
+ __METACLASS_DATA__TtC15CoreSpeechUtils22PolarisResourceEncoder
+ __METACLASS_DATA__TtC15CoreSpeechUtils24PolarisAudioBatchEncoder
+ __METACLASS_DATA__TtC15CoreSpeechUtils26PolarisGestureBatchEncoder
+ ___swift_memcpy1040_16
+ ___swift_memcpy12_8
+ ___swift_memcpy16_4
+ ___swift_memcpy2064_16
+ ___swift_memcpy248_16
+ ___swift_memcpy4136_16
+ ___swift_memcpy48_8
+ ___swift_memcpy512_16
+ ___swift_memcpy8208_16
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_CoreSpeechUtils
+ _associated conformance 15CoreSpeechUtils19PolarisEncodingTypeOSHAASQ
+ _associated conformance 15CoreSpeechUtils19PolarisEncodingTypeOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 15CoreSpeechUtils20PolarisEncodingErrorOSHAASQ
+ _free
+ _swift_allocError
+ _swift_coroFrameAlloc
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _symbolic $s15CoreSpeechUtils16PolarisDecodableP
+ _symbolic $s15CoreSpeechUtils16PolarisEncodableP
+ _symbolic $s15CoreSpeechUtils19PolarisAudioCodableP
+ _symbolic SaySay_____GG s5Int16V
+ _symbolic Say_____G 15CoreSpeechUtils17PolarisAudioChunkV
+ _symbolic Say_____G 15CoreSpeechUtils19PolarisEncodingTypeO
+ _symbolic Say_____G 15CoreSpeechUtils19PolarisGestureChunkV
+ _symbolic Say_____G 15CoreSpeechUtils20PolarisGestureSampleV
+ _symbolic Si
+ _symbolic _____ 15CoreSpeechUtils15Int16SamplePoolC
+ _symbolic _____ 15CoreSpeechUtils16FlatBufferHeaderV
+ _symbolic _____ 15CoreSpeechUtils16SecureAudioChunkC04FlatdeF0V
+ _symbolic _____ 15CoreSpeechUtils17PolarisAudioChunkV
+ _symbolic _____ 15CoreSpeechUtils19PolarisEncodingTypeO
+ _symbolic _____ 15CoreSpeechUtils19PolarisGestureChunkV
+ _symbolic _____ 15CoreSpeechUtils20PolarisEncodingErrorO
+ _symbolic _____ 15CoreSpeechUtils20PolarisGestureSampleV
+ _symbolic _____ 15CoreSpeechUtils22FlatSecureGestureChunkV
+ _symbolic _____ 15CoreSpeechUtils22PolarisResourceEncoderC
+ _symbolic _____ 15CoreSpeechUtils23PolarisAudioChunkHeaderV
+ _symbolic _____ 15CoreSpeechUtils24PolarisAudioBatchEncoderC
+ _symbolic _____ 15CoreSpeechUtils24SecureGestureChunkHeaderV
+ _symbolic _____ 15CoreSpeechUtils25FlatSecureAudioChunkBatchV
+ _symbolic _____ 15CoreSpeechUtils26PolarisGestureBatchEncoderC
+ _symbolic _____ 15CoreSpeechUtils27FlatSecureGestureChunkBatchV
+ _symbolic _____ 15CoreSpeechUtils27PolarisGestureResourceBatchV
+ _symbolic _____ 15CoreSpeechUtils28PolarisSecureAudioChunkBatchV
+ _symbolic _____ 15CoreSpeechUtils30PolarisSecureGestureChunkBatchV
+ _symbolic _____ s5Int32V
+ _symbolic _____ySay_____GG s23_ContiguousArrayStorageC s5Int16V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4DataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15CoreSpeechUtils17PolarisAudioChunkV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15CoreSpeechUtils19PolarisGestureChunkV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15CoreSpeechUtils20PolarisGestureSampleV
+ _symbolic _____y_____G s5SIMD2V s6UInt64V
+ _symbolic _____y_____G s5SIMD8V s5Int32V
+ _symbolic _____y_____G s5SIMD8V s6UInt64V
+ _symbolic _____y_____G s6SIMD16V s5Int32V
+ _symbolic _____y_____G s6SIMD64V s5Int16V
+ _symbolic _____y_____G s6SIMD64V s5UInt8V
+ _symbolic x
+ _type_layout_string 15CoreSpeechUtils16FlatBufferHeaderV
+ _type_layout_string 15CoreSpeechUtils16SecureAudioChunkC04FlatdeF0V
+ _type_layout_string 15CoreSpeechUtils17PolarisAudioChunkV
+ _type_layout_string 15CoreSpeechUtils19PolarisGestureChunkV
+ _type_layout_string 15CoreSpeechUtils20PolarisGestureSampleV
+ _type_layout_string 15CoreSpeechUtils22FlatSecureGestureChunkV
+ _type_layout_string 15CoreSpeechUtils25FlatSecureAudioChunkBatchV
+ _type_layout_string 15CoreSpeechUtils27FlatSecureGestureChunkBatchV
+ _type_layout_string 15CoreSpeechUtils27PolarisGestureResourceBatchV
+ _type_layout_string 15CoreSpeechUtils28PolarisSecureAudioChunkBatchV
+ _type_layout_string 15CoreSpeechUtils30PolarisSecureGestureChunkBatchV
CStrings:
+ " samples, first_ts: "
+ " samples], first_ts: "
+ ", bufferHostTime: "
+ "CoreSpeechUtils/PolarisSecureAudioChunkBatch.swift"
+ "[%s] [%ld] PolarisSecureAudioChunkBatch has invalid encodingTypeRaw=%d; falling back to .secureaudiochunk"
+ "polaris_audio_batch["
+ "polaris_gesture_batch["
+ "secureaudiochunk"
+ "securegesturechunk"
```
