## HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26508` | `0x26758` | **`+0x250`** |
| `__TEXT.__objc_methname` | `0x3c81` | `0x3cf1` | **`+0x70`** |
| `__TEXT.__const` | `0x8c8` | `0x8f8` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x844` | `0x874` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x270` | `0x29c` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x1098` | `0x10b8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1730` | `0x1750` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xf24` | `0xf44` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xb62` | `0xb82` | **`+0x20`** |
| `__DATA.__objc_const` | `0x1710` | `0x1728` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xfb8` | `0xfd0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xba8` | `0xbb8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x358` | `0x368` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x224` | `0x234` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1a4` | `0x1a8` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x34` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__cstring` | `0x17de` | `0x17e0` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1241.1.7.1.3
+1263.1.0.1.2

-  - /usr/lib/swift/libswiftCallKit.dylib

-  CStrings:  960
+  CStrings:  964
Symbols:
+ _swift_conformsToProtocol2
- __swift_FORCE_LOAD_$_swiftCallKit
CStrings:
+ "accessory:didUpdateMatterNodeID:"
+ "accessoryDidUpdateSupportsRTAPATAudio:"
+ "accessoryDidUpdateSupportsRegulatoryErase:"
+ "v32@0:8@\"HMAccessory\"16@\"NSNumber\"24"
```
