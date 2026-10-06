## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/PhotosUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42e50` | `0x432a0` | **`+0x450`** |
| `__DATA.__data` | `0x1af8` | `0x1bf8` | **`+0x100`** |
| `__AUTH.__data` | `0x6a8` | `0x738` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x6f48` | `0x6fb8` | **`+0x70`** |
| `__TEXT.__const` | `0x2fb8` | `0x3018` | **`+0x60`** |
| `__TEXT.__cstring` | `0x4c64` | `0x4cc4` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x3e64` | `0x3ec4` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2120` | `0x2160` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xbea` | `0xc28` | **`+0x3e`** |
| `__TEXT.__swift5_fieldmd` | `0xc0c` | `0xc40` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0xb41` | `0xb71` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0xa18` | `0xa40` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0xd64` | `0xd8c` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x218` | `0x238` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1968` | `0x1980` | **`+0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0xf0` | `0x100` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x618` | `0x620` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x11c` | `0x120` | **`+0x4`** |

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  Functions: 2994
-  Symbols:   2926
-  CStrings:  557
+  Functions: 3007
+  Symbols:   2945
+  CStrings:  559
Symbols:
+ +[PHPickerFilter _textureStyleabilityFilter]
+ GCC_except_table865
+ GCC_except_table875
+ GCC_except_table878
+ GCC_except_table880
+ GCC_except_table959
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PVSProvenanceClient
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PVSProvenanceServer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PVSProvenanceClient
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PVSProvenanceServer
+ __OBJC_$_PROTOCOL_REFS_PVSProvenanceClient
+ __OBJC_$_PROTOCOL_REFS_PVSProvenanceServer
+ __OBJC_LABEL_PROTOCOL_$_PVSProvenanceClient
+ __OBJC_LABEL_PROTOCOL_$_PVSProvenanceServer
+ __OBJC_PROTOCOL_$_PVSProvenanceClient
+ __OBJC_PROTOCOL_$_PVSProvenanceServer
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_getTupleTypeMetadata2
+ _symbolic SS15localIdentifier______15photoLibraryURLt 10Foundation3URLV
+ _symbolic _____ 8PhotosUI24PVSProvenanceImageSourceO
+ _symbolic ______SSSgt 10Foundation3URLV
- GCC_except_table864
- GCC_except_table874
- GCC_except_table877
- GCC_except_table879
- GCC_except_table958
CStrings:
+ "com.apple.PhotosViewService.provenance"
+ "localIdentifier photoLibraryURL "
```
