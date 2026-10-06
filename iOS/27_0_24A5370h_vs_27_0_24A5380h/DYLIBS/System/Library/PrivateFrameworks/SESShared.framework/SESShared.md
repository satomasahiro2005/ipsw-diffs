## SESShared

> `/System/Library/PrivateFrameworks/SESShared.framework/SESShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf254` | `0x13268` | **`+0x4014`** |
| `__TEXT.__const` | `0xc20` | `0x1380` | **`+0x760`** |
| `__DATA.__bss` | `0x10` | `0x680` | **`+0x670`** |
| `__AUTH_CONST.__const` | `0x230` | `0x7d0` | **`+0x5a0`** |
| `__TEXT.__cstring` | `0x1c5a` | `0x1f13` | **`+0x2b9`** |
| `__TEXT.__swift5_fieldmd` | `0x48` | `0x224` | **`+0x1dc`** |
| `__TEXT.__eh_frame` | `0xb0` | `0x230` | **`+0x180`** |
| `__TEXT.__constg_swiftt` | `0x64` | `0x1b8` | **`+0x154`** |
| `__TEXT.__swift5_reflstr` | `0xf` | `0x121` | **`+0x112`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x4d8` | **`+0xf8`** |
| `__TEXT.__swift5_typeref` | `0x40` | `0x12e` | **`+0xee`** |
| `__AUTH_CONST.__auth_got` | `0x4d0` | `0x5b8` | **`+0xe8`** |
| `__DATA_CONST.__const` | `0xbc0` | `0xb48` | **`-0x78`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1f0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x3c0` | `0x410` | **`+0x50`** |
| `__DATA.__data` | `0x28` | `0x70` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0x8` | `0x48` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x8` | `0x2c` | **`+0x24`** |
| `__AUTH.__data` | `—` | `0x20` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x2a40` | `0x2a60` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA_DIRTY.__bss` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0xc` | **`+0x8`** |

### Other Changes

```diff

-70.34.0.0.0
+70.35.1.0.0

-  Functions: 333
-  Symbols:   1013
-  CStrings:  416
+  Functions: 450
+  Symbols:   1052
+  CStrings:  438
Symbols:
+ _CA_DSKAnalyticsBrand
+ _CA_DSKAnalyticsKeyRole
+ _CA_DSKAnalyticsManufacturer
+ _CA_DSKAnalyticsStateChanges
+ _CA_DSKAnalyticsStateChangesOther
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_memcpy16_8
+ ___swift_memcpy17_8
+ ___swift_memcpy1_1
+ ___swift_memcpy24_8
+ ___swift_memcpy29_8
+ ___swift_memcpy40_8
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_stdlib_malloc_size
+ _associated conformance 9SESShared4APDUO6FormatOSHAASQ
+ _get_enum_tag_for_layout_string 9SESShared4APDUO5ErrorO
+ _get_enum_tag_for_layout_string 9SESShared4APDUO7CommandV6SelectO
+ _malloc_size
+ _swift_allocError
+ _swift_arrayInitWithCopy
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_cvw_enumFn_getEnumTag
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_release_x19
+ _swift_release_x28
+ _swift_unexpectedError
+ _swift_willThrow
+ _swift_willThrowTypedImpl
+ _symbolic $s9SESShared4APDUO7CodableP
+ _symbolic $s9SESShared4APDUO7RequestP
+ _symbolic $sSY
+ _symbolic SS
+ _symbolic SaySSG
+ _symbolic Si_S2it
+ _symbolic SnySiG
+ _symbolic _____ 9SESShared0A16DataParsingErrorO
+ _symbolic _____ 9SESShared4APDUO
+ _symbolic _____ 9SESShared4APDUO5ErrorO
+ _symbolic _____ 9SESShared4APDUO6FormatO
+ _symbolic _____ 9SESShared4APDUO7CommandV
+ _symbolic _____ 9SESShared4APDUO7CommandV6SelectO
+ _symbolic _____ 9SESShared4APDUO7CommandV6SelectO5ErrorO
+ _symbolic _____ 9SESShared4APDUO8ResponseV
+ _symbolic _____ 9SESShared4APDUO8ResponseV5ErrorO
+ _symbolic _____ s5UInt8V
+ _symbolic _____ s6UInt16V
+ _symbolic _____8response_SS9operationt 9SESShared4APDUO8ResponseV
+ _symbolic _____Sg s6UInt16V
+ _symbolic ______Sit 9SESShared4APDUO6FormatO
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _type_layout_string 9SESShared4APDUO5ErrorO
+ _type_layout_string 9SESShared4APDUO7CommandV
+ _type_layout_string 9SESShared4APDUO7CommandV6SelectO
+ _type_layout_string 9SESShared4APDUO7CommandV6SelectO5ErrorO
+ _type_layout_string 9SESShared4APDUO8ResponseV
+ _type_layout_string 9SESShared4APDUO8ResponseV5ErrorO
- _CA_DSKAnalyticsBtOutOfOrderMessageCount
- _CA_DSKAnalyticsBtTimeExtensionInitiatedByDeviceCount
- _CA_DSKAnalyticsBtTimeExtensionInitiatedByLockCount
- _CA_DSKAnalyticsInfoBrand
- _CA_DSKAnalyticsInfoFWVersion
- _CA_DSKAnalyticsInfoManufacturer
- _CA_DSKAnalyticsInfoProductID
- _CA_DSKAnalyticsInfoVendorID
- _CA_DSKAnalyticsIntentFallbackTriggered
- _CA_DSKAnalyticsKeyType
- _CA_DSKAnalyticsLockCapability
- _CA_DSKAnalyticsLockSharingCapability
- _CA_DSKAnalyticsLockStatus
- _CA_DSKAnalyticsLockStatusAtConnection
- _CA_DSKAnalyticsRangingExceptionBitmap
- _CA_DSKAnalyticsStepUpDuration
- _CA_DSKAnalyticsTransactionMode
- _CA_DSKAnalyticsUnlockCount
- _CA_DSKAnalyticsUnlockFromOtherSourceCount
- _CA_DSKAnalyticsUnlockSource
CStrings:
+ " does not fit observed byte count "
+ "A000000151435253"
+ "A000000396545400000001400101"
+ "A000000704E000000000"
+ "A000000809434343444B417631"
+ "A000000809434343444B467631"
+ "Declared format "
+ "Illegal read size "
+ "Invalid le bytes for extended format"
+ "Lc starts with 0x00 but is not extended format"
+ "Malformed APDU: "
+ "Missing header bytes"
+ "Payload length does not match lc"
+ "Response data too short"
+ "Response payload size exceeded request's le"
+ "SESShared/CommandAPDU.swift"
+ "Undefined status word"
+ "Unexpected response: "
+ "empty"
+ "extended"
+ "keyRole"
+ "pairingState"
+ "standard"
+ "stateChanges"
+ "stateChangesOther"
- "infoBrand"
- "infoManufacturer"
- "pendingState"
```
