## NanoBooksBridgeSettings

> `/System/Library/NanoPreferenceBundles/Applications/NanoBooksBridgeSettings.bundle/NanoBooksBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b9c` | `0x11cf8` | **`+0x115c`** |
| `__TEXT.__auth_stubs` | `0x500` | `0x6e0` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `—` | `0x190` | **`+0x190`** |
| `__DATA_CONST.__const` | `0x6f8` | `0x858` | **`+0x160`** |
| `__DATA.__objc_const` | `0x1ec0` | `0x1fc0` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0x290` | `0x380` | **`+0xf0`** |
| `__DATA.__data` | `0x3c8` | `0x4a8` | **`+0xe0`** |
| `__DATA.__objc_data` | `0x640` | `0x708` | **`+0xc8`** |
| `__TEXT.__const` | `0xa8` | `0x164` | **`+0xbc`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x550` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `—` | `0x98` | **`+0x98`** |
| `__TEXT.__objc_classname` | `0x397` | `0x417` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `—` | `0x5c` | **`+0x5c`** |
| `__TEXT.__swift5_typeref` | `—` | `0x4e` | **`+0x4e`** |
| `__TEXT.__objc_methlist` | `0x12bc` | `0x12ec` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__objc_methname` | `0x41e2` | `0x4206` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0xaa0` | `0xa80` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0xa05` | `0xa22` | **`+0x1d`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x410` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__cstring` | `0xc9c` | `0xc94` | **`-0x8`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-6629.0.0.0.0
+6636.0.0.0.0

+  - /System/Library/PrivateFrameworks/Dormancy.framework/Dormancy

-  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

-  Functions: 430
-  Symbols:   289
-  CStrings:  1036
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_Concurrency.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 465
+  Symbols:   323
+  CStrings:  1040
Symbols:
+ _OBJC_CLASS_$_PDRRegistry
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ __Block_copy
+ __Block_release
+ ___chkstk_darwin
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swiftos
+ _objc_opt_self
+ _swift_allocObject
+ _swift_bridgeObjectRelease
+ _swift_deallocClassInstance
+ _swift_deallocObject
+ _swift_deletedAsyncMethodErrorTu
+ _swift_deletedMethodError
+ _swift_getObjectType
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_release
+ _swift_release_x21
+ _swift_release_x25
+ _swift_release_x8
+ _swift_retain_x21
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_updateClassMetadata2
- _OBJC_CLASS_$_NRPairedDeviceRegistry
CStrings:
+ "NBInteractionDonationManager"
+ "_TtC23NanoBooksBridgeSettingsP33_6C65E0ADEEC03E3F2B90E7CD1DCED4A819ResourceBundleClass"
+ "com.apple.NanoBooks"
+ "donateSettingsInteractionWithCompletionHandler:"
+ "v24@0:8@?<v@?>16"
+ "wrapped"
- "4649745e-094c-4f84-80dd-f7ab46f54792"
- "initWithUUIDString:"
```
