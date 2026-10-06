## CoreServicesAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/CoreServicesAppReplacementExtension.appex/CoreServicesAppReplacementExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14d8` | `0x1f90` | **`+0xab8`** |
| `__TEXT.__auth_stubs` | `0x3d0` | `0x4b0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x72` | `0xf2` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x1f0` | `0x260` | **`+0x70`** |
| `__DATA_CONST.__const` | `0xd0` | `0xf8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xd8` | `0x100` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x20` | `0x38` | **`+0x18`** |
| `__DATA.__data` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x9c` | `0xaa` | **`+0xe`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-469.1.6.0.0
+469.1.7.0.0

+  - /System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination

-  Functions: 32
-  Symbols:   81
-  CStrings:  64
+  Functions: 44
+  Symbols:   93
+  CStrings:  66
Symbols:
+ _OBJC_CLASS_$_IXDataReplacementRequest
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_release_x8
+ _objc_retain_x28
+ _swift_bridgeObjectRetain
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_unknownObjectRetain
- _objc_release_x27
- _objc_retain_x21
CStrings:
+ "CoreServicesAppReplacementMigration initialized. Request class %s"
+ "migrated CoreServices goop from %@ to %@"
```
