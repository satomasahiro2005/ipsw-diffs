## DeviceRecovery

> `/System/Library/PrivateFrameworks/DeviceRecovery.framework/DeviceRecovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0f0` | `0x104ec` | **`+0x13fc`** |
| `__AUTH_CONST.__auth_got` | `0x0` | `0x3d0` | **`+0x3d0`** |
| `__AUTH.__objc_data` | `0xa0` | `0x1a0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `—` | `0xd8` | **`+0xd8`** |
| `__AUTH_CONST.__objc_const` | `0x820` | `0x8e8` | **`+0xc8`** |
| `__TEXT.__constg_swiftt` | `—` | `0x78` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x700` | `0x768` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x410` | `0x468` | **`+0x58`** |
| `__TEXT.__const` | `0xa0` | `0xe2` | **`+0x42`** |
| `__DATA_CONST.__const` | `0x4e0` | `0x520` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x98` | `0xd8` | **`+0x40`** |
| `__TEXT.__cstring` | `0x273a` | `0x2779` | **`+0x3f`** |
| `__DATA_CONST.__objc_selrefs` | `0x500` | `0x538` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x34` | **`+0x34`** |
| `__AUTH.__data` | `—` | `0x28` | **`+0x28`** |
| `__DATA.__data` | `0x188` | `0x1b0` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_types` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_imageinfo`

### Other Changes

```diff

-150.0.2.0.0
+150.40.7.0.0

-  Functions: 498
-  Symbols:   493
-  CStrings:  311
+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  Functions: 525
+  Symbols:   544
+  CStrings:  313
Symbols:
+ _OBJC_CLASS_$__TtC14DeviceRecovery34DeviceRecoveryFileStreamJSONWriter
+ _OBJC_METACLASS_$__TtC14DeviceRecovery34DeviceRecoveryFileStreamJSONWriter
+ __DATA__TtC14DeviceRecovery34DeviceRecoveryFileStreamJSONWriter
+ __INSTANCE_METHODS__TtC14DeviceRecovery34DeviceRecoveryFileStreamJSONWriter
+ __IVARS__TtC14DeviceRecovery34DeviceRecoveryFileStreamJSONWriter
+ __METACLASS_DATA__TtC14DeviceRecovery34DeviceRecoveryFileStreamJSONWriter
+ __PROPERTIES__TtC14DeviceRecovery34DeviceRecoveryFileStreamJSONWriter
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_project_boxed_opaque_existential_1
+ ___swift_reflection_version
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftAppleArchive_$_DeviceRecovery
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_DeviceRecovery
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_DeviceRecovery
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_DeviceRecovery
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_DeviceRecovery
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_DeviceRecovery
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_DeviceRecovery
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_DeviceRecovery
+ __swift_stdlib_reportUnimplementedInitializer
+ _memcpy
+ _objc_autorelease
+ _objc_opt_self
+ _swift_allocObject
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_deletedMethodError
+ _swift_dynamicCast
+ _swift_errorRelease
+ _swift_getTypeByMangledNameInContext2
+ _swift_getWitnessTable
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_release_x23
+ _swift_retain
+ _swift_retain_x22
+ _swift_retain_x23
+ _symbolic Si
+ _symbolic So12NSFileHandleC
+ _symbolic So8NSObjectC
+ _symbolic _____ 10Foundation11JSONEncoderC
+ _symbolic _____ 14DeviceRecovery0aB20FileStreamJSONWriterC
+ _symbolic ______p 10Foundation15ContiguousBytesP
CStrings:
+ "DeviceRecovery.DeviceRecoveryFileStreamJSONWriter"
+ "init()"
```
