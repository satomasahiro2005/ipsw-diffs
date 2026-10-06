## AppProtectionAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/AppProtectionAppReplacementExtension.appex/AppProtectionAppReplacementExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x138c` | `0x1c64` | **`+0x8d8`** |
| `__TEXT.__auth_stubs` | `0x3c0` | `0x490` | **`+0xd0`** |
| `__DATA_CONST.__auth_got` | `0x1e8` | `0x250` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0xa4` | `0xf4` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xe0` | `0x108` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xf0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x20` | `0x38` | **`+0x18`** |
| `__DATA.__data` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x48` | `0x58` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x96` | `0xa4` | **`+0xe`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-55.1.1.0.0
+55.1.2.100.0

+  - /System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination

-  Functions: 30
-  Symbols:   83
-  CStrings:  63
+  Functions: 42
+  Symbols:   95
+  CStrings:  64
Symbols:
+ _OBJC_CLASS_$_IXDataReplacementRequest
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ _malloc_size
+ _memcpy
+ _memmove
+ _swift_bridgeObjectRetain
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_unknownObjectRetain
CStrings:
+ "AppProtectionAppReplacementMigration initialized. Request class %s"
```
