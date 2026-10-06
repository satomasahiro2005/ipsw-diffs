## ODDFeatureDigestsExtension

> `/System/Library/ExtensionKit/Extensions/ODDFeatureDigestsExtension.appex/ODDFeatureDigestsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dac` | `0x3b58` | **`+0x1dac`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x550` | **`+0x200`** |
| `__DATA.__bss` | `0x280` | `0x400` | **`+0x180`** |
| `__DATA_CONST.__auth_ptr` | `0x278` | `0x130` | **`-0x148`** |
| `__DATA_CONST.__auth_got` | `0x1a8` | `0x2a8` | **`+0x100`** |
| `__DATA.__data` | `0x110` | `0x1e0` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0xd3` | `0x1c` | **`-0xb7`** |
| `__DATA_CONST.__const` | `0xf0` | `0x198` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x110` | `0x70` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `—` | `0x83` | **`+0x83`** |
| `__TEXT.__constg_swiftt` | `0x64` | `0xd8` | **`+0x74`** |
| `__TEXT.__cstring` | `0xb3` | `0x53` | **`-0x60`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x18` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x178` | `0x1c0` | **`+0x48`** |
| `__TEXT.__const` | `0x388` | `0x342` | **`-0x46`** |
| `__TEXT.__eh_frame` | `0x340` | `0x310` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2c` | `0x5c` | **`+0x30`** |
| `__DATA.__objc_const` | `0xb8` | `0x90` | **`-0x28`** |
| `__TEXT.__swift5_capture` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x1c` | **`-0x20`** |
| `__TEXT.__swift_as_ret` | `0x3c` | `0x1c` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `—` | `0x1c` | **`+0x1c`** |
| `__DATA.__common` | `0x30` | `0x18` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x14` | `0x24` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x6` | `—` | **`-0x6`** |
| `__TEXT.__objc_classname` | `0x3d` | `0x41` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x1` | `—` | **`-0x1`** |
| `__TEXT.__swift5_typeref` | `0x139` | `0x13a` | **`+0x1`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-3600.43.6.1.1
+3600.49.3.0.0

-  - /System/Library/PrivateFrameworks/DeepThought.framework/DeepThought

+  - /System/Library/PrivateFrameworks/LighthouseBitacoraFramework.framework/LighthouseBitacoraFramework
+  - /System/Library/PrivateFrameworks/MLRuntime.framework/MLRuntime

-  - /System/Library/PrivateFrameworks/ODDAnalytics.framework/ODDAnalytics
-  - /System/Library/PrivateFrameworks/PoirotAnalytics.framework/PoirotAnalytics
-  - /System/Library/PrivateFrameworks/PoirotBlocks.framework/PoirotBlocks
+  - /System/Library/PrivateFrameworks/ODDIFramework.framework/ODDIFramework
+  - /System/Library/PrivateFrameworks/lighthouse_runtime.framework/lighthouse_runtime

-  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 75
-  Symbols:   49
-  CStrings:  5
+  Functions: 84
+  Symbols:   91
+  CStrings:  8
Symbols:
+ __os_log_impl
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_stdlib_bridgeErrorToNSError
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_release_x19
+ _objc_release_x20
+ _objc_release_x26
+ _objc_release_x27
+ _objc_release_x28
+ _objc_release_x8
+ _objc_retain_x23
+ _objc_retain_x25
+ _os_log_type_enabled
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_dynamicCast
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getObjectType
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_release_x20
+ _swift_release_x22
+ _swift_slowDealloc
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_task_create
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Configuration: %s"
+ "Context: %@"
+ "Handling result %s"
+ "ODDFeatureDigestsExtensionConfig()"
+ "Task failed with untyped error: %s"
+ "Unexpected error: %@"
+ "_TtC26ODDFeatureDigestsExtension30ODDFeatureDigestsWorkerFactory"
+ "com.apple.siri.metrics"
- "_TtC26ODDFeatureDigestsExtension26ODDFeatureDigestsExtension"
- "com.apple.ODDFeatureDigestsExtension"
- "com.apple.ODDFeatureDigestsExtension.LLMSiriDigest"
- "com.apple.ODDFeatureDigestsExtension_LLMSiriDigest_IncludeCurrentDate"
- "inner"
```
