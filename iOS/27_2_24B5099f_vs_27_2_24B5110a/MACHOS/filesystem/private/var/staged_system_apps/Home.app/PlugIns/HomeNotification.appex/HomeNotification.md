## HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x3cf1` | `0x3d81` | **`+0x90`** |
| `__TEXT.__text` | `0x26754` | `0x267a0` | **`+0x4c`** |
| `__TEXT.__objc_methlist` | `0xf44` | `0xf6c` | **`+0x28`** |
| `__DATA.__objc_const` | `0x1728` | `0x1740` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xfd0` | `0xfe8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x10b8` | `0x10c8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x898` | `0x8a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1269.2.3.0.1
+1269.2.5.1.4

+  - /usr/lib/swift/libswiftGLKit.dylib

+  - /usr/lib/swift/libswiftSceneKit.dylib

-  Functions: 664
-  Symbols:   334
-  CStrings:  964
+  Functions: 665
+  Symbols:   336
+  CStrings:  967
Symbols:
+ __swift_FORCE_LOAD_$_swiftGLKit
+ __swift_FORCE_LOAD_$_swiftSceneKit
CStrings:
+ "accessoryDidUpdateSupportsAppleTVSiriSettings:"
+ "accessoryDidUpdateSupportsTopCapPlusAndMinus:"
+ "accessoryDidUpdateSupportsTopCapTouchAndHold:"
```
