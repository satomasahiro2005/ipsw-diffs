## PhotoFoundation

> `/System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dce8` | `0x1f7b8` | **`+0x1ad0`** |
| `__DATA.__bss` | `0xfb0` | `0x15d0` | **`+0x620`** |
| `__TEXT.__const` | `0x1788` | `0x1ae8` | **`+0x360`** |
| `__AUTH_CONST.__const` | `0x1430` | `0x1560` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x800` | `0x908` | **`+0x108`** |
| `__TEXT.__swift5_reflstr` | `0x759` | `0x859` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x644` | `0x720` | **`+0xdc`** |
| `__AUTH_CONST.__auth_got` | `0xb60` | `0xc20` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0xb08` | `0xbc0` | **`+0xb8`** |
| `__AUTH.__data` | `0x3d8` | `0x470` | **`+0x98`** |
| `__DATA.__data` | `0x9e0` | `0xa70` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x6e4` | `0x772` | **`+0x8e`** |
| `__TEXT.__constg_swiftt` | `0x768` | `0x7e8` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1120` | `0x1191` | **`+0x71`** |
| `__AUTH_CONST.__cfstring` | `0xd40` | `0xd80` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x340` | `0x380` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0xf0` | `0x120` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0xbc` | `0xec` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x7c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x840` | `0x848` | **`+0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

+  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 1206
-  Symbols:   1250
-  CStrings:  247
+  Functions: 1291
+  Symbols:   1288
+  CStrings:  253
Symbols:
+ GCC_except_table196
+ GCC_except_table310
+ _NSURLVolumeIsInternalKey
+ _NSURLVolumeIsLocalKey
+ _NSURLVolumeIsRootFileSystemKey
+ _PFIsPhotoBooth
+ _PFIsPhotoBooth.isPhotoBooth
+ _PFIsPhotoBooth.onceToken
+ _PFIsPhotosPosterProvider
+ _PFIsPhotosPosterProvider.isPhotosPosterProvider
+ _PFIsPhotosPosterProvider.onceToken
+ ___PFIsPhotoBooth_block_invoke
+ ___PFIsPhotosPosterProvider_block_invoke
+ ___unnamed_13
+ ___unnamed_20
+ _associated conformance 15PhotoFoundation14Float16StorageVSHAASQ
+ _associated conformance So16NSURLResourceKeyaSHSCSQ
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _bzero
+ _getattrlist
+ _statfs
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_getSingletonMetadata
+ _swift_getTupleTypeMetadata3
+ _swift_storeEnumTagMultiPayload
+ _symbolic Sb
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 15PhotoFoundation14Float16StorageV
+ _symbolic _____ 15PhotoFoundation15FileSystemErrorO
+ _symbolic _____ 15PhotoFoundation22FileSystemCapabilitiesV
+ _symbolic _____ So16NSURLResourceKeya
+ _symbolic _____ s6UInt16V
+ _symbolic _____7syscall______5errno_____3urlt s12StaticStringV s5Int32V 10Foundation3URLV
+ _symbolic ______p s5ErrorP
+ _symbolic _____y_____G s11_SetStorageC So16NSURLResourceKeya
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So16NSURLResourceKeya
+ _type_layout_string 15PhotoFoundation14Float16StorageV
+ _type_layout_string 15PhotoFoundation22FileSystemCapabilitiesV
+ _type_layout_string So16NSURLResourceKeya
- GCC_except_table192
- GCC_except_table302
- ___unnamed_12
- ___unnamed_19
- _type_layout_string So19NSKeyValueChangeKeya
CStrings:
+ "Photo Booth"
+ "PhotosPosterProvider"
+ "getattrlist"
+ "invalid file system path: "
+ "statfs"
+ "syscall errno url "
```
