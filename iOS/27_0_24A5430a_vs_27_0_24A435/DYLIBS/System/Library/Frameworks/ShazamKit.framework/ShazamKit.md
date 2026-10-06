## ShazamKit

> `/System/Library/Frameworks/ShazamKit.framework/ShazamKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa172c` | `0xa68cc` | **`+0x51a0`** |
| `__DATA.__bss` | `0x2018` | `0x2c28` | **`+0xc10`** |
| `__TEXT.__const` | `0x222b7` | `0x22a97` | **`+0x7e0`** |
| `__TEXT.__eh_frame` | `0x24c0` | `0x2b68` | **`+0x6a8`** |
| `__AUTH_CONST.__const` | `0x2160` | `0x27a8` | **`+0x648`** |
| `__AUTH_CONST.__objc_const` | `0x9f08` | `0xa398` | **`+0x490`** |
| `__TEXT.__constg_swiftt` | `0x7bc` | `0xa6c` | **`+0x2b0`** |
| `__DATA_DIRTY.__data` | `0x7e8` | `0xa78` | **`+0x290`** |
| `__TEXT.__swift5_fieldmd` | `0x66c` | `0x89c` | **`+0x230`** |
| `__TEXT.__unwind_info` | `0x34e8` | `0x36c8` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x3a9b` | `0x3c4d` | **`+0x1b2`** |
| `__TEXT.__swift5_reflstr` | `0x4c2` | `0x5ee` | **`+0x12c`** |
| `__AUTH_CONST.__auth_got` | `0x1330` | `0x1418` | **`+0xe8`** |
| `__TEXT.__swift5_typeref` | `0xfd4` | `0x10ac` | **`+0xd8`** |
| `__DATA.__data` | `0x1b2480` | `0x1b2530` | **`+0xb0`** |
| `__AUTH.__data` | `0x298` | `0x338` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x5170` | `0x5200` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x27a0` | `0x2820` | **`+0x80`** |
| `__TEXT.__swift5_proto` | `0x184` | `0x1e4` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x868` | `0x8b0` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0x94` | `0xd8` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x2518` | `0x2558` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1431` | `0x1471` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x370` | `0x3a0` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xdc` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x164` | `0x184` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x230` | `0x248` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x900` | `0x910` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xc8` | `0xd4` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x4e4` | `0x4ec` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x150` | `0x158` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xbc` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x38a0` | `0x38a4` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/Tightbeam.framework/Tightbeam

-  Functions: 3651
-  Symbols:   5136
-  CStrings:  575
+  Functions: 3816
+  Symbols:   5217
+  CStrings:  587
Symbols:
+ +[SHAmbientSession activateSessionWithContext:completionHandler:]
+ +[SHAmbientSession deactivateSessionWithContext:completionHandler:]
+ +[SHAmbientSession serverConnection]
+ +[SHAmbientSession setMusicDetectedState:completionHandler:]
+ -[SHCatalogConfiguration enableInstant]
+ -[SHCatalogConfiguration setEnableInstant:]
+ -[SHRecordRequest enableInstant]
+ -[SHRecordRequest initWithRequestID:notifications:deadline:storeSignatureOnNoMatch:enableLiveActivity:enableInstant:invocationSource:preferredInputAudioRoute:]
+ -[SHShazamKitServiceConnection setAmbientSessionActiveState:forContext:completionHandler:]
+ -[SHShazamKitServiceConnection setMusicDetected:completionHandler:]
+ _OBJC_CLASS_$_SHAmbientSession
+ _OBJC_IVAR_$_SHCatalogConfiguration._enableInstant
+ _OBJC_IVAR_$_SHRecordRequest._enableInstant
+ _OBJC_METACLASS_$_SHAmbientSession
+ _SHAmbientSessionContextLiveActivity
+ _SHAmbientSessionContextSmartStack
+ __DATA__TtC9ShazamKit16SHAmbientSession
+ __DATA__TtC9ShazamKit16SHExclaveService
+ __DATA__TtC9ShazamKit22ShazamSignatureService
+ __DATA__TtCC9ShazamKit22ShazamSignatureService6Server
+ __DATA__TtCC9ShazamKit22ShazamSignatureService7Service
+ __IVARS__TtC9ShazamKit16SHAmbientSession
+ __IVARS__TtC9ShazamKit16SHExclaveService
+ __IVARS__TtCC9ShazamKit22ShazamSignatureService6Server
+ __IVARS__TtCC9ShazamKit22ShazamSignatureService7Service
+ __METACLASS_DATA__TtC9ShazamKit16SHAmbientSession
+ __METACLASS_DATA__TtC9ShazamKit16SHExclaveService
+ __METACLASS_DATA__TtC9ShazamKit22ShazamSignatureService
+ __METACLASS_DATA__TtCC9ShazamKit22ShazamSignatureService6Server
+ __METACLASS_DATA__TtCC9ShazamKit22ShazamSignatureService7Service
+ __OBJC_$_CLASS_METHODS_SHAmbientSession
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SHAmbientSessionService
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SHAmbientSessionService
+ __OBJC_$_PROTOCOL_REFS_SHAmbientSessionService
+ __OBJC_CLASS_RO_$_SHAmbientSession
+ __OBJC_LABEL_PROTOCOL_$_SHAmbientSessionService
+ __OBJC_METACLASS_RO_$_SHAmbientSession
+ __OBJC_PROTOCOL_$_SHAmbientSessionService
+ ___36+[SHAmbientSession serverConnection]_block_invoke
+ ___67-[SHShazamKitServiceConnection setMusicDetected:completionHandler:]_block_invoke
+ ___90-[SHShazamKitServiceConnection setAmbientSessionActiveState:forContext:completionHandler:]_block_invoke
+ ___swift_memcpy0_1
+ ___swift_memcpy25_8
+ _associated conformance 9ShazamKit10SampleRateOSHAASQ
+ _associated conformance 9ShazamKit16SHAmbientSessionC7ContextOSHAASQ
+ _associated conformance 9ShazamKit16SHExclaveServiceC16InvocationSourceOSHAASQ
+ _associated conformance 9ShazamKit24SignatureGenerationErrorOSHAASQ
+ _associated conformance 9ShazamKit25SignatureInvocationSourceOSHAASQ
+ _get_enum_tag_for_layout_string 9ShazamKit16SignaturePayloadO
+ _mach_continuous_time
+ _swift_deallocPartialClassInstance
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _symbolic $s9ShazamKit0A23SignatureServiceHandlerP
+ _symbolic BD
+ _symbolic Say_____G s5UInt8V
+ _symbolic _____ 9ShazamKit0A16SignatureServiceC
+ _symbolic _____ 9ShazamKit0A16SignatureServiceC0D0C
+ _symbolic _____ 9ShazamKit0A16SignatureServiceC6ServerC
+ _symbolic _____ 9ShazamKit10SampleRateO
+ _symbolic _____ 9ShazamKit16SHAmbientSessionC
+ _symbolic _____ 9ShazamKit16SHAmbientSessionC7ContextO
+ _symbolic _____ 9ShazamKit16SHExclaveServiceC
+ _symbolic _____ 9ShazamKit16SHExclaveServiceC16InvocationSourceO
+ _symbolic _____ 9ShazamKit16SignaturePayloadO
+ _symbolic _____ 9ShazamKit16SignatureRequestV
+ _symbolic _____ 9ShazamKit24SignatureGenerationErrorO
+ _symbolic _____ 9ShazamKit25SignatureInvocationSourceO
+ _symbolic _____ 9ShazamKit7SecondsV
+ _symbolic _____ 9ShazamKit9AudioDataV
+ _symbolic _____ 9ShazamKit9AudioTimeV
+ _symbolic _____ 9ShazamKit9SignatureV
+ _symbolic _____ 9Tightbeam16ClientConnectionC
+ _symbolic _____ 9Tightbeam17ServiceConnectionC
+ _symbolic _____ So10tb_error_ta
+ _symbolic _____ s6UInt64V
+ _type_layout_string 9ShazamKit16SignaturePayloadO
+ _type_layout_string 9ShazamKit16SignatureRequestV
+ _type_layout_string 9ShazamKit7SecondsV
+ _type_layout_string 9ShazamKit9AudioDataV
+ _type_layout_string 9ShazamKit9AudioTimeV
+ _type_layout_string 9ShazamKit9SignatureV
- -[SHRecordRequest initWithRequestID:notifications:deadline:storeSignatureOnNoMatch:enableLiveActivity:invocationSource:preferredInputAudioRoute:]
CStrings:
+ "Encrypted data is not currently supported"
+ "Invalid key value while decoding result type for signature"
+ "Received exclave signature byte array with count %ld"
+ "SHAmbientSessionContextLiveActivity"
+ "SHAmbientSessionContextSmartStack"
+ "SHCatalogConfigurationEnableInstantKey"
+ "ShazamKit/SHExclaveService.swift"
+ "ShazamKit/ShazamKit_swift.swift"
+ "com.apple.shazamd.service"
+ "enableInstant"
+ "illegal variant selector: "
+ "invalid rawValue for SignatureGenerationError: "
```
