## StorageContainersPrivate

> `/System/Library/PrivateFrameworks/StorageContainersPrivate.framework/StorageContainersPrivate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa08` | `0xd6d4` | **`+0x2ccc`** |
| `__AUTH.__data` | `—` | `0x120` | **`+0x120`** |
| `__AUTH_CONST.__auth_got` | `0x4d0` | `0x5d8` | **`+0x108`** |
| `__AUTH_CONST.__const` | `0xea8` | `0xe18` | **`-0x90`** |
| `__DATA.__bss` | `0x1300` | `0x1380` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x520` | **`+0x70`** |
| `__TEXT.__cstring` | `0x51f` | `0x57f` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x728` | `0x780` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x5f0` | `0x648` | **`+0x58`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__DATA.__data` | `0x278` | `0x2c8` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x467` | `0x4b5` | **`+0x4e`** |
| `__AUTH_CONST.__objc_const` | `0x4e0` | `0x498` | **`-0x48`** |
| `__TEXT.__const` | `0x12a8` | `0x12f0` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x52c` | `0x56c` | **`+0x40`** |
| `__DATA.__common` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x454` | `0x47a` | **`+0x26`** |
| `__TEXT.__swift5_proto` | `0xc8` | `0xcc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x64` | `0x68` | **`+0x4`** |

### Other Changes

```diff

-833.0.8.0.1
+833.40.14.0.0

+  - /usr/lib/swift/libswiftDarwin.dylib

-  Functions: 422
-  Symbols:   306
-  CStrings:  29
+  Functions: 458
+  Symbols:   325
+  CStrings:  31
Symbols:
+ _CC_SHA256
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_project_boxed_opaque_existential_1
+ _container_get_instance_uuid
+ _container_query_set_instance_uuid
+ _mbr_uid_to_uuid
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_dynamicCast
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_updateClassMetadata2
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 24StorageContainersPrivate9ContainerC10AttributesV8InstanceO
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic ______AAt 24StorageContainersPrivate9ContainerC10AttributesV8InstanceO
+ _symbolic ______p 10Foundation15ContiguousBytesP
- ___swift_memcpy18_4
- _type_layout_string 24StorageContainersPrivate9ContainerC10AttributesV
CStrings:
+ "Existing container has mismatching instance UUID."
+ "The provided UID was invalid."
```
