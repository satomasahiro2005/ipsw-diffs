## NanoContactsBridgeSettingsOther

> `/System/Library/NanoPreferenceBundles/Applications/NanoContactsBridgeSettingsOther.bundle/NanoContactsBridgeSettingsOther`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49f4` | `0x5db4` | **`+0x13c0`** |
| `__TEXT.__auth_stubs` | `0x310` | `0x5e0` | **`+0x2d0`** |
| `__DATA_CONST.__auth_got` | `0x198` | `0x300` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0xe67` | `0xf52` | **`+0xeb`** |
| `__DATA.__objc_data` | `0x140` | `0x1f0` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x200` | `0x2a8` | **`+0xa8`** |
| `__TEXT.__const` | `0x94` | `0xfa` | **`+0x66`** |
| `__TEXT.__objc_stubs` | `0xe20` | `0xe80` | **`+0x60`** |
| `__DATA.__objc_const` | `0x738` | `0x780` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x188` | `0x1d0` | **`+0x48`** |
| `__DATA.__data` | `0xc0` | `0x100` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x49c` | `0x4d4` | **`+0x38`** |
| `__TEXT.__cstring` | `0xd81` | `0xdb7` | **`+0x36`** |
| `__TEXT.__swift5_typeref` | `—` | `0x31` | **`+0x31`** |
| `__DATA_CONST.__got` | `0xf8` | `0x128` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0xa7` | `0xcb` | **`+0x24`** |
| `__TEXT.__objc_methname` | `0x15d7` | `0x15fb` | **`+0x24`** |
| `__DATA.__bss` | `0x60` | `0x80` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4c0` | `0x4d0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__swift5_types` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-422.1.0.0.0
+423.0.0.0.0

+  - /System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/ScreenTimeSettingsServices

-  Functions: 118
-  Symbols:   107
-  CStrings:  364
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
+  Functions: 142
+  Symbols:   149
+  CStrings:  375
Symbols:
+ _OBJC_CLASS_$_NCABScreenTimeSettingsShim
+ _OBJC_METACLASS_$_NCABScreenTimeSettingsShim
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
+ _swift_allocObject
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getErrorValue
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
+ "altDSID"
+ "com.apple.NanoContacts"
+ "eureka"
+ "tryEnableScreenTimeForDSID:"
```
