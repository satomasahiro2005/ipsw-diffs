## DVTInstrumentsUtilities

> `/System/Library/PrivateFrameworks/DVTInstrumentsUtilities.framework/DVTInstrumentsUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2df80` | `0x31c50` | **`+0x3cd0`** |
| `__TEXT.__eh_frame` | `0x210` | `0x530` | **`+0x320`** |
| `__AUTH_CONST.__const` | `0xed0` | `0x1158` | **`+0x288`** |
| `__AUTH.__objc_data` | `0x1aa0` | `0x1cd8` | **`+0x238`** |
| `__TEXT.__constg_swiftt` | `0x12c` | `0x34c` | **`+0x220`** |
| `__DATA.__data` | `0x9d8` | `0xbd8` | **`+0x200`** |
| `__TEXT.__const` | `0x15ac` | `0x175c` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x6310` | `0x6478` | **`+0x168`** |
| `__AUTH_CONST.__auth_got` | `0xa10` | `0xb70` | **`+0x160`** |
| `__TEXT.__swift5_typeref` | `0x1bf` | `0x313` | **`+0x154`** |
| `__TEXT.__unwind_info` | `0x1320` | `0x1468` | **`+0x148`** |
| `__TEXT.__cstring` | `0x5c3a` | `0x5d4a` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x1a4` | `0x284` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x2f7c` | `0x2ffc` | **`+0x80`** |
| `__AUTH.__data` | `0x78` | `0xf0` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0x10d` | `0x15d` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x550` | `0x588` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `—` | `0x38` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x2368` | `0x2390` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `—` | `0x1c` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x24` | `0x3c` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0xa8` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x20` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x7c` | `0x80` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift5_types2` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-64578.141.1.0.0
+64578.145.1.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 1426
-  Symbols:   576
-  CStrings:  1280
+  Functions: 1523
+  Symbols:   615
+  CStrings:  1287
Symbols:
+ _OBJC_CLASS_$__TtC23DVTInstrumentsUtilities17TaskExecutionStop
+ _OBJC_CLASS_$__TtC23DVTInstrumentsUtilities22CancellableMobileAgent
+ _OBJC_METACLASS_$__TtC23DVTInstrumentsUtilities17TaskExecutionStop
+ _OBJC_METACLASS_$__TtC23DVTInstrumentsUtilities22CancellableMobileAgent
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ _swift_allocateGenericClassMetadata
+ _swift_beginAccess
+ _swift_checkMetadataState
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_deallocClassInstance
+ _swift_deallocObject
+ _swift_deletedMethodError
+ _swift_getEnumCaseMultiPayload
+ _swift_getExtendedFunctionTypeMetadata
+ _swift_getFunctionTypeMetadata0
+ _swift_getGenericMetadata
+ _swift_getObjectType
+ _swift_initClassMetadata2
+ _swift_initStructMetadata
+ _swift_isaMask
+ _swift_lookUpClassMethod
+ _swift_release_x21
+ _swift_release_x26
+ _swift_release_x8
+ _swift_retain_x19
+ _swift_storeEnumTagMultiPayload
+ _swift_task_addCancellationHandler
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_removeCancellationHandler
+ _swift_task_switch
+ _swift_willThrowTypedImpl
CStrings:
+ " was not of the expected type "
+ "CheckedContinuation<(), Never>"
+ "DVTInstrumentsUtilities/CancellableMobileAgent.swift"
+ "DVTInstrumentsUtilities/TaskExecutionStop.swift"
+ "Fatal error"
+ "Result is not available from a ticket in the "
+ "activateAndWait(_:)"
```
