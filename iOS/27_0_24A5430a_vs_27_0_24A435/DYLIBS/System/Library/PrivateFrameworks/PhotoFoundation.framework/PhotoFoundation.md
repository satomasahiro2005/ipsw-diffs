## PhotoFoundation

> `/System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f788` | `0x23fec` | **`+0x4864`** |
| `__DATA.__bss` | `0x15c0` | `0x1fc0` | **`+0xa00`** |
| `__TEXT.__const` | `0x1ac8` | `0x22f8` | **`+0x830`** |
| `__TEXT.__eh_frame` | `0x908` | `0xc48` | **`+0x340`** |
| `__AUTH_CONST.__auth_got` | `0xc20` | `0xe38` | **`+0x218`** |
| `__TEXT.__swift5_reflstr` | `0x7f9` | `0x9f9` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0xbc8` | `0xdc0` | **`+0x1f8`** |
| `__AUTH_CONST.__const` | `0x1560` | `0x1700` | **`+0x1a0`** |
| `__TEXT.__swift5_fieldmd` | `0x6e4` | `0x854` | **`+0x170`** |
| `__AUTH.__data` | `0x2d8` | `0x420` | **`+0x148`** |
| `__DATA.__data` | `0xa48` | `0xb68` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x764` | `0x87a` | **`+0x116`** |
| `__TEXT.__cstring` | `0x114f` | `0x125f` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x26f8` | `0x2800` | **`+0x108`** |
| `__TEXT.__constg_swiftt` | `0x7e8` | `0x894` | **`+0xac`** |
| `__DATA_CONST.__got` | `0x370` | `0x418` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0xc7c` | `0xd04` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x848` | `0x8c8` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x48` | `0xb8` | **`+0x70`** |
| `__TEXT.__swift5_proto` | `0xec` | `0x13c` | **`+0x50`** |
| `__DATA.__common` | `0x28` | `0x58` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x7c` | `0x90` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xf0` | `0xf8` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

+  - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

+  - /System/Library/PrivateFrameworks/InternalSwiftProtobuf.framework/InternalSwiftProtobuf
+  - /System/Library/PrivateFrameworks/MessageSecurity.framework/MessageSecurity
+  - /System/Library/PrivateFrameworks/SwiftASN1Internal.framework/SwiftASN1Internal

-  Functions: 1290
-  Symbols:   1285
-  CStrings:  250
+  Functions: 1494
+  Symbols:   1342
+  CStrings:  259
Symbols:
+ _MSDigestAlgorithmSHA256
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_MSAlgorithmIdentifier
+ _OBJC_CLASS_$_MSMessageImprint
+ _OBJC_CLASS_$_MSOID
+ _OBJC_CLASS_$_MSTimestampResponse
+ _OBJC_CLASS_$_PFAPNSRFC3161Timestamp
+ _OBJC_METACLASS_$_PFAPNSRFC3161Timestamp
+ _OUTLINED_FUNCTION_23
+ _OUTLINED_FUNCTION_24
+ __CLASS_METHODS_PFAPNSRFC3161Timestamp
+ __DATA_PFAPNSRFC3161Timestamp
+ __INSTANCE_METHODS_PFAPNSRFC3161Timestamp
+ __IVARS_PFAPNSRFC3161Timestamp
+ __METACLASS_DATA_PFAPNSRFC3161Timestamp
+ __PROPERTIES_PFAPNSRFC3161Timestamp
+ ___swift_allocate_boxed_opaque_existential_0
+ __swift_stdlib_reportUnimplementedInitializer
+ _associated conformance 15PhotoFoundation21ProvoloneFeatureFlagsOSHAASQ
+ _associated conformance 15PhotoFoundation25APNSRFC3161TimestampErrorO0B013CustomNSErrorAAs0E0
+ _associated conformance 15PhotoFoundation26LowerBoundTimestampWrapper33_CC6B8F7218AA87CCDCF178E40BDC0A20LLV17SwiftASN1Internal21DERImplicitlyTaggableAaE12DERParseable
+ _associated conformance 15PhotoFoundation26LowerBoundTimestampWrapper33_CC6B8F7218AA87CCDCF178E40BDC0A20LLV17SwiftASN1Internal21DERImplicitlyTaggableAaE15DERSerializable
+ _associated conformance 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageV013InternalSwiftE001_F18ImplementationBaseAASH
+ _associated conformance 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageV013InternalSwiftE001_F18ImplementationBaseAaD0F0
+ _associated conformance 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageV013InternalSwiftE00F0AAs28CustomDebugStringConvertible
+ _associated conformance 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageVSHAASQ
+ _associated conformance 15PhotoFoundation36APNSRFC3161TimestampProtobufMessagesV013InternalSwiftE026_MessageImplementationBaseAASH
+ _associated conformance 15PhotoFoundation36APNSRFC3161TimestampProtobufMessagesV013InternalSwiftE026_MessageImplementationBaseAaD0I0
+ _associated conformance 15PhotoFoundation36APNSRFC3161TimestampProtobufMessagesV013InternalSwiftE07MessageAAs28CustomDebugStringConvertible
+ _associated conformance 15PhotoFoundation36APNSRFC3161TimestampProtobufMessagesVSHAASQ
+ _get_enum_tag_for_layout_string 10Foundation4DataV15_RepresentationO
+ _get_enum_tag_for_layout_string 15PhotoFoundation25APNSRFC3161TimestampErrorO
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_deallocPartialClassInstance
+ _swift_errorRelease
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getErrorValue
+ _swift_getObjCClassFromMetadata
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic SDy__________G s6UInt32V 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageV
+ _symbolic SS6reason_t
+ _symbolic SS9oidString_t
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ 15PhotoFoundation21ProvoloneFeatureFlagsO
+ _symbolic _____ 15PhotoFoundation25APNSRFC3161TimestampErrorO
+ _symbolic _____ 15PhotoFoundation26LowerBoundTimestampWrapper33_CC6B8F7218AA87CCDCF178E40BDC0A20LLV
+ _symbolic _____ 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageV
+ _symbolic _____ 15PhotoFoundation36APNSRFC3161TimestampProtobufMessagesV
+ _symbolic _____ 21InternalSwiftProtobuf14UnknownStorageV
+ _symbolic _____3key______5valuet s6UInt32V 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageV
+ _symbolic _____6digest_t 10Foundation4DataV
+ _symbolic _____Sg 10Foundation4DateV
+ _symbolic _____Sg 15PhotoFoundation35APNSRFC3161TimestampProtobufMessageV
+ _symbolic ______pSg10underlying_t s5ErrorP
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _type_layout_string 15PhotoFoundation25APNSRFC3161TimestampErrorO
+ _type_layout_string 15PhotoFoundation26LowerBoundTimestampWrapper33_CC6B8F7218AA87CCDCF178E40BDC0A20LLV
CStrings:
+ "CinematicEverywhere"
+ "Decoding not implemented"
+ "PhotoFoundation.PFAPNSRFC3161Timestamp"
+ "PhotoFoundation/PFAPNSRFC3161Timestamp.swift"
+ "PhotoFoundationErrorDomain"
+ "Provenance"
+ "Provolone"
+ "Unable to get message for config ID "
+ "init()"
```
