## CommonUtilities

> `/System/Library/PrivateFrameworks/CommonUtilities.framework/CommonUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfa5c` | `0x26998` | **`+0x16f3c`** |
| `__DATA.__bss` | `0x150` | `0x2ac0` | **`+0x2970`** |
| `__TEXT.__const` | `0x110` | `0x1600` | **`+0x14f0`** |
| `__AUTH_CONST.__auth_got` | `0x0` | `0xc88` | **`+0xc88`** |
| `__AUTH_CONST.__const` | `0x340` | `0xda1` | **`+0xa61`** |
| `__TEXT.__eh_frame` | `—` | `0x728` | **`+0x728`** |
| `__AUTH_CONST.__objc_const` | `0x2178` | `0x2790` | **`+0x618`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0xbe8` | **`+0x608`** |
| `__TEXT.__swift5_typeref` | `—` | `0x498` | **`+0x498`** |
| `__TEXT.__constg_swiftt` | `—` | `0x480` | **`+0x480`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x468` | **`+0x468`** |
| `__AUTH.__objc_data` | `0x410` | `0x870` | **`+0x460`** |
| `__TEXT.__cstring` | `0xbf8` | `0xf8c` | **`+0x394`** |
| `__AUTH.__data` | `—` | `0x2e8` | **`+0x2e8`** |
| `__DATA.__data` | `—` | `0x280` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0xd16` | `0xf89` | **`+0x273`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x1dd` | **`+0x1dd`** |
| `__TEXT.__swift5_proto` | `—` | `0x148` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0x10f4` | `0x1214` | **`+0x120`** |
| `__DATA_CONST.__got` | `0x228` | `0x338` | **`+0x110`** |
| `__DATA_CONST.__objc_selrefs` | `0xb38` | `0xbf8` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x5b8` | `0x658` | **`+0xa0`** |
| `__DATA.__common` | `0x8` | `0x70` | **`+0x68`** |
| `__TEXT.__swift5_types` | `—` | `0x5c` | **`+0x5c`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xf8` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xaa0` | `0xac0` | **`+0x20`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_imageinfo`

### Other Changes

```diff

-300.100.1.0.0
+301.100.1.0.0

-  - /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony

-  Functions: 547
-  Symbols:   381
-  CStrings:  208
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftSynchronization.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 1088
+  Symbols:   471
+  CStrings:  255
Symbols:
+ _OBJC_CLASS_$_CUTEventTracingOperation
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSFileHandle
+ _OBJC_CLASS_$__TtC15CommonUtilities24CUTLogOperationPublisher
+ _OBJC_CLASS_$__TtC15CommonUtilities25CUTFileOperationPublisher
+ _OBJC_CLASS_$__TtC15CommonUtilities25CUTJSONOperationPublisher
+ _OBJC_CLASS_$__TtCE15CommonUtilitiesCSo24CUTEventTracingOperation5Field
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$_CUTEventTracingOperation
+ _OBJC_METACLASS_$__TtC15CommonUtilities24CUTLogOperationPublisher
+ _OBJC_METACLASS_$__TtC15CommonUtilities25CUTFileOperationPublisher
+ _OBJC_METACLASS_$__TtC15CommonUtilities25CUTJSONOperationPublisher
+ _OBJC_METACLASS_$__TtCE15CommonUtilitiesCSo24CUTEventTracingOperation5Field
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ ___chkstk_darwin
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_stdlib_bridgeErrorToNSError
+ __swift_stdlib_reportUnimplementedInitializer
+ _kIOMainPortDefault
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _swift_allocBox
+ _swift_allocError
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_coroFrameAlloc
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_deallocClassInstance
+ _swift_deallocPartialClassInstance
+ _swift_deletedMethodError
+ _swift_dynamicCast
+ _swift_dynamicCastClass
+ _swift_endAccess
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getEnumCaseMultiPayload
+ _swift_getErrorValue
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_isaMask
+ _swift_lookUpClassMethod
+ _swift_once
+ _swift_release
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x8
+ _swift_retain_x19
+ _swift_retain_x21
+ _swift_retain_x26
+ _swift_runtimeSupportsNoncopyableTypes
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_storeEnumTagMultiPayload
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_updateClassMetadata2
+ _swift_willThrow
- __CTServerConnectionCreateWithIdentifier
- __CTServerConnectionDormancySuspendAssertionCreate
- _kIOMasterPortDefault
CStrings:
+ " Duration: %.4fs"
+ " Status: IN PROGRESS"
+ " Status: SUCCESS"
+ "%s"
+ "CommonUtilities.CUTEventTracingOperation"
+ "CommonUtilities.CUTFileOperationPublisher"
+ "CommonUtilities.CUTLogOperationPublisher"
+ "CommonUtilities.Field"
+ "CommonUtilities/CUTEventTracing.swift"
+ "CoreTelephony"
+ "EventTracingOperation._start is not a Date!"
+ "EventTracingOperation._stopTime is not a Date!"
+ "Failed to create directory %s: %s"
+ "Failed to decode operation at file URL: %s, error: %@"
+ "Failed to drop oldest file: %@"
+ "Failed to encode operation as JSON"
+ "Failed to encode operation as a %s"
+ "Failed to load existing files, error: %@"
+ "Failed to publish operation as file, error: %@"
+ "Failed to write operation to streaming file: %@"
+ "Fatal error"
+ "Found %ld existing operations"
+ "IDSRegistrationEventTracing"
+ "Invalid number of keys found, expected one."
+ "Start operation %s %s"
+ "Stop operation %s %s"
+ "_CTServerConnectionCreateWithIdentifier"
+ "_CTServerConnectionDormancySuspendAssertionCreate"
+ "__CTServerConnectionCreateWithIdentifier failed to load!"
+ "__CTServerConnectionDormancySuspendAssertionCreate failed to load!"
+ "com.apple.CommonUtiliites"
+ "error"
+ "errorDescription"
+ "eventTracing-oversized"
+ "fields"
+ "init()"
+ "json"
+ "name"
+ "remotelyReportable"
+ "start"
+ "stopTime"
+ "stopped"
+ "subOperations"
+ "txt"
+ "underlyingErrors"
+ "uniqueIdentifier"
+ "yyyy-MM-dd HH:mm:ss.SSSSSS"
```
