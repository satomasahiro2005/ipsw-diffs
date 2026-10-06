## NanoContactsBridgeSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/NanoContactsBridgeSetup.bundle/NanoContactsBridgeSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3ec` | `0xeae8` | **`+0x16fc`** |
| `__TEXT.__auth_stubs` | `0x470` | `0x790` | **`+0x320`** |
| `__DATA_CONST.__auth_got` | `0x248` | `0x3d8` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x23d1` | `0x24c2` | **`+0xf1`** |
| `__DATA.__data` | `0x308` | `0x3e0` | **`+0xd8`** |
| `__DATA.__objc_const` | `0x2738` | `0x2810` | **`+0xd8`** |
| `__DATA.__objc_data` | `0x500` | `0x5b0` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x4b0` | `0x558` | **`+0xa8`** |
| `__TEXT.__const` | `0xdc` | `0x184` | **`+0xa8`** |
| `__TEXT.__constg_swiftt` | `—` | `0x7c` | **`+0x7c`** |
| `__TEXT.__objc_classname` | `0x340` | `0x3b7` | **`+0x77`** |
| `__TEXT.__unwind_info` | `0x400` | `0x470` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x2200` | `0x2260` | **`+0x60`** |
| `__DATA.__bss` | `0xb0` | `0xf0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2014` | `0x2053` | **`+0x3f`** |
| `__TEXT.__objc_methlist` | `0xeac` | `0xee4` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x2c84` | `0x2cb8` | **`+0x34`** |
| `__DATA.__common` | `—` | `0x30` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x210` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x20` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x9f8` | `0xa10` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__swift5_types` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-422.1.0.0.0
+423.0.0.0.0

+  - /System/Library/Frameworks/DeveloperToolsSupport.framework/DeveloperToolsSupport

+  - /System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/ScreenTimeSettingsServices

-  Functions: 356
-  Symbols:   183
-  CStrings:  784
+  - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftCompression.dylib
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreAudio.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftCoreLocation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftQuartzCore.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 391
+  Symbols:   231
+  CStrings:  797
Symbols:
+ _OBJC_CLASS_$_NCABScreenTimeSettingsShim
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$_NCABScreenTimeSettingsShim
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ ___chkstk_darwin
+ __os_feature_enabled_impl
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftsimd
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_opt_self
+ _objc_retainAutoreleasedReturnValue
+ _swift_allocObject
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_deallocClassInstance
+ _swift_deletedMethodError
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getErrorValue
+ _swift_getObjCClassFromMetadata
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_release_x25
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRetain
CStrings:
+ "%{public}s - enabled Screen Time via ScreenTimeSettings for family member: %@"
+ "%{public}s - falling back to legacy Screen Time for family member: %@"
+ "NCABScreenTimeSettingsShim"
+ "No DSID"
+ "ScreenTimeSettings"
+ "ScreenTimeSettings apply failed: %s"
+ "User not migrated"
+ "_TtC23NanoContactsBridgeSetupP33_779125AF218078EFD07999906C70A14F19ResourceBundleClass"
+ "altDSID"
+ "bundleForClass:"
+ "com.apple.NanoContacts"
+ "eureka"
+ "tryEnableScreenTimeForDSID:"
```
