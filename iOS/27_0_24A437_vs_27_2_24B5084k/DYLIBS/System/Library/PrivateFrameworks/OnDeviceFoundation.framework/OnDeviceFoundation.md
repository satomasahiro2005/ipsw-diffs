## OnDeviceFoundation

> `/System/Library/PrivateFrameworks/OnDeviceFoundation.framework/OnDeviceFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe298` | `0xbed8` | **`-0x23c0`** |
| `__DATA.__bss` | `0x800` | `0x100` | **`-0x700`** |
| `__TEXT.__const` | `0x98e` | `0x45e` | **`-0x530`** |
| `__AUTH_CONST.__const` | `0x838` | `0x3c0` | **`-0x478`** |
| `__TEXT.__swift5_typeref` | `0x3f0` | `0x21e` | **`-0x1d2`** |
| `__TEXT.__unwind_info` | `0x498` | `0x340` | **`-0x158`** |
| `__DATA_DIRTY.__data` | `0x3c8` | `0x280` | **`-0x148`** |
| `__TEXT.__eh_frame` | `0x8d8` | `0x7b0` | **`-0x128`** |
| `__TEXT.__swift5_reflstr` | `0x1d5` | `0xb0` | **`-0x125`** |
| `__DATA_DIRTY.__bss` | `0x180` | `0x80` | **`-0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x2f0` | `0x1f4` | **`-0xfc`** |
| `__TEXT.__swift5_assocty` | `0xc0` | `—` | **`-0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x140` | `0x88` | **`-0xb8`** |
| `__TEXT.__constg_swiftt` | `0x34c` | `0x2d0` | **`-0x7c`** |
| `__DATA.__data` | `0xc0` | `0x68` | **`-0x58`** |
| `__AUTH_CONST.__auth_got` | `0x640` | `0x5f0` | **`-0x50`** |
| `__TEXT.__swift5_proto` | `0x54` | `0x10` | **`-0x44`** |
| `__TEXT.__cstring` | `0x1e1` | `0x1a1` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x64` | `0x24` | **`-0x40`** |
| `__TEXT.__swift5_types` | `0x40` | `0x24` | **`-0x1c`** |
| `__DATA.__common` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x68` | `0x60` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `—` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x20` | `0x18` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x10` | `0x14` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x30` | `0x2c` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x30` | `0x2c` | **`-0x4`** |
| `__TEXT.__objc_classname` | `0x0` | `—` | **`-0x0`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-3.0.59.0.0
+3.1.10.0.0

-  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 351
-  Symbols:   253
-  CStrings:  18
+  Functions: 205
+  Symbols:   191
+  CStrings:  16
Symbols:
+ __os_log_impl
+ _objc_release_x23
+ _objc_release_x25
+ _objc_release_x26
+ _swift_getAssociatedConformanceWitness
+ _swift_getAssociatedTypeWitness
+ _swift_release_x28
+ _swift_retain_x28
+ _swift_stdlib_random
+ _symbolic $s18OnDeviceFoundation15ActivityTrackerV16CategoryProtocolP
+ _symbolic $s18OnDeviceFoundation15ActivityTrackerV17SubsystemProtocolP
+ _symbolic 8Category_____Qz 18OnDeviceFoundation15ActivityTrackerV17SubsystemProtocolP
+ _symbolic 8RawValueSYQz
+ _symbolic 9Subsystem_____Qz 18OnDeviceFoundation15ActivityTrackerV16CategoryProtocolP
+ _symbolic _____ 18OnDeviceFoundation15ActivityTrackerV0D0V7Failure33_DB9CC92C16032436E6D3B9BFF28B4C37LLV
+ _symbolic _____ 18OnDeviceFoundation15ActivityTrackerV7ContextV
+ _symbolic _____ 2os6LoggerV
+ _symbolic _____ So13os_log_type_ta
+ _symbolic _____ s5UInt8V
+ _symbolic _____y_____G s9TaskLocalC 18OnDeviceFoundation15ActivityTrackerV7ContextV
+ _type_layout_string 18OnDeviceFoundation15ActivityTrackerV0D0V7Failure33_DB9CC92C16032436E6D3B9BFF28B4C37LLV
+ _type_layout_string 18OnDeviceFoundation15ActivityTrackerV7ContextV
+ _type_layout_string So13os_log_type_ta
- _OBJC_CLASS_$_OS_os_log
- _OBJC_CLASS_$__TtCs12_SwiftObject
- __DATA__TtC18OnDeviceFoundationP33_7337EF6CBCABAFEA11039AF2E172D6DB13OSLogRegistry
- __IVARS__TtC18OnDeviceFoundationP33_7337EF6CBCABAFEA11039AF2E172D6DB13OSLogRegistry
- __METACLASS_DATA__TtC18OnDeviceFoundationP33_7337EF6CBCABAFEA11039AF2E172D6DB13OSLogRegistry
- ___swift_allocate_boxed_opaque_existential_1
- ___swift_destroy_boxed_opaque_existential_0Tm
- ___swift_memcpy1_1
- ___swift_memcpy33_8
- ___swift_memcpy4_4
- ___swift_memcpy8_8
- ___swift_project_boxed_opaque_existential_0Tm
- __swiftEmptyDictionarySingleton
- __swift_FORCE_LOAD_$_swiftOSLog
- __swift_FORCE_LOAD_$_swiftOSLog_$_OnDeviceFoundation
- _associated conformance 18OnDeviceFoundation10LogMessageV14ValueTreatmentOSHAASQ
- _associated conformance 18OnDeviceFoundation10LogMessageV19StringInterpolationVs0fG8ProtocolAA0F11LiteralTypesAFP_s021_ExpressibleByBuiltinfI0
- _associated conformance 18OnDeviceFoundation10LogMessageVs26ExpressibleByStringLiteralAA0hI4TypesADP_s01_fg7BuiltinhI0
- _associated conformance 18OnDeviceFoundation10LogMessageVs26ExpressibleByStringLiteralAAs0fg23ExtendedGraphemeClusterI0
- _associated conformance 18OnDeviceFoundation10LogMessageVs32ExpressibleByStringInterpolationAA0hI0sADP_s0hI8Protocol
- _associated conformance 18OnDeviceFoundation10LogMessageVs32ExpressibleByStringInterpolationAAs0fgH7Literal
- _associated conformance 18OnDeviceFoundation10LogMessageVs33ExpressibleByUnicodeScalarLiteralAA0hiJ4TypesADP_s01_fg7BuiltinhiJ0
- _associated conformance 18OnDeviceFoundation10LogMessageVs43ExpressibleByExtendedGraphemeClusterLiteralAA0hijK4TypesADP_s01_fg7BuiltinhijK0
- _associated conformance 18OnDeviceFoundation10LogMessageVs43ExpressibleByExtendedGraphemeClusterLiteralAAs0fg13UnicodeScalarK0
- _associated conformance 18OnDeviceFoundation13OSLogRegistry33_7337EF6CBCABAFEA11039AF2E172D6DBLLC3KeyVSHAASQ
- _associated conformance 18OnDeviceFoundation15LogMessageLevelOSHAASQ
- _associated conformance 18OnDeviceFoundation15LogMessageLevelOSLAASQ
- _associated conformance 18OnDeviceFoundation15LogMessageLevelOs12CaseIterableAA8AllCasessADP_Sl
- _associated conformance 18OnDeviceFoundation8OSLoggerV9SubsystemVSHAASQ
- _get_enum_tag_for_layout_string ypSg
- _objc_release_x1
- _objc_release_x27
- _objc_retain
- _objc_retain_x20
- _objc_retain_x27
- _objc_retain_x8
- _os_unfair_lock_lock
- _os_unfair_lock_unlock
- _swift_allocBox
- _swift_deallocClassInstance
- _swift_deletedMethodError
- _swift_getExistentialTypeMetadata
- _swift_release_x20
- _symbolic $s18OnDeviceFoundation6LoggerP
- _symbolic $sSY
- _symbolic $ss12CaseIterableP
- _symbolic $ss26ExpressibleByStringLiteralP
- _symbolic $ss27StringInterpolationProtocolP
- _symbolic $ss32ExpressibleByStringInterpolationP
- _symbolic $ss33ExpressibleByUnicodeScalarLiteralP
- _symbolic $ss43ExpressibleByExtendedGraphemeClusterLiteralP
- _symbolic Say_____G 18OnDeviceFoundation10LogMessageV
- _symbolic Say_____G 18OnDeviceFoundation10LogMessageV9Component33_7D3978BAE33564E98F3C9E2BEE3C4DF4LLV
- _symbolic Say_____G 18OnDeviceFoundation15LogMessageLevelO
- _symbolic Sb
- _symbolic Si
- _symbolic So9OS_os_logC
- _symbolic _____ 18OnDeviceFoundation10LogMessageV
- _symbolic _____ 18OnDeviceFoundation10LogMessageV14ValueTreatmentO
- _symbolic _____ 18OnDeviceFoundation10LogMessageV19StringInterpolationV
- _symbolic _____ 18OnDeviceFoundation10LogMessageV9Component33_7D3978BAE33564E98F3C9E2BEE3C4DF4LLV
- _symbolic _____ 18OnDeviceFoundation13OSLogRegistry33_7337EF6CBCABAFEA11039AF2E172D6DBLLC
- _symbolic _____ 18OnDeviceFoundation13OSLogRegistry33_7337EF6CBCABAFEA11039AF2E172D6DBLLC3KeyV
- _symbolic _____ 18OnDeviceFoundation15LogMessageLevelO
- _symbolic _____ 18OnDeviceFoundation8OSLoggerV
- _symbolic _____ 18OnDeviceFoundation8OSLoggerV9SubsystemV
- _symbolic _____ So16os_unfair_lock_sV
- _symbolic _____ s6UInt32V
- _symbolic ______p 18OnDeviceFoundation6LoggerP
- _symbolic _____ySDy_____So9OS_os_logCGG 2os21OSAllocatedUnfairLockV 18OnDeviceFoundation13OSLogRegistry33_7337EF6CBCABAFEA11039AF2E172D6DBLLC3KeyV
- _symbolic _____ySDy_____So9OS_os_logCG_____G s13ManagedBufferCsRi__rlE 18OnDeviceFoundation13OSLogRegistry33_7337EF6CBCABAFEA11039AF2E172D6DBLLC3KeyV So16os_unfair_lock_sV
- _symbolic _____ySSSgG s9TaskLocalC
- _symbolic _____ySay_____GSSG s15LazyMapSequenceV 18OnDeviceFoundation10LogMessageV
- _symbolic _____ySay_____GSSG s15LazyMapSequenceV 18OnDeviceFoundation10LogMessageV9Component33_7D3978BAE33564E98F3C9E2BEE3C4DF4LLV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18OnDeviceFoundation10LogMessageV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18OnDeviceFoundation10LogMessageV9Component33_7D3978BAE33564E98F3C9E2BEE3C4DF4LLV
- _symbolic _____y_____So9OS_os_logCG s18_DictionaryStorageC 18OnDeviceFoundation13OSLogRegistry33_7337EF6CBCABAFEA11039AF2E172D6DBLLC3KeyV
- _symbolic _____yypG s23_ContiguousArrayStorageC
- _symbolic ypSg
- _type_layout_string 18OnDeviceFoundation10LogMessageV
- _type_layout_string 18OnDeviceFoundation10LogMessageV9Component33_7D3978BAE33564E98F3C9E2BEE3C4DF4LLV
- _type_layout_string 18OnDeviceFoundation13OSLogRegistry33_7337EF6CBCABAFEA11039AF2E172D6DBLLC3KeyV
- _type_layout_string 18OnDeviceFoundation8OSLoggerV
- _type_layout_string 18OnDeviceFoundation8OSLoggerV9SubsystemV
- _type_layout_string So16os_unfair_lock_sV
CStrings:
+ "%{public}s"
- "%{public}@"
- "Fatal error"
- "OnDeviceFoundation/LogMessage.swift"
```
