## AssetsLibrary

> `/System/Library/Frameworks/AssetsLibrary.framework/AssetsLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa27c` | `0x9c50` | **`-0x62c`** |
| `__AUTH_CONST.__cfstring` | `0x700` | `0x680` | **`-0x80`** |
| `__TEXT.__cstring` | `0x86c` | `0x7fc` | **`-0x70`** |
| `__DATA.__data` | `0x120` | `0xc0` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xa80` | `0xa38` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0xae4` | `0xaa4` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x4ec` | `0x4b4` | **`-0x38`** |
| `__DATA_CONST.__const` | `0x8f0` | `0x8c8` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0xe78` | `0xe60` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x590` | `0x578` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x180` | `0x170` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x10` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-916.40.110.0.0
+916.45.110.0.0

-  Functions: 306
-  Symbols:   720
-  CStrings:  84
+  Functions: 304
+  Symbols:   709
+  CStrings:  79
Symbols:
+ GCC_except_table202
+ GCC_except_table223
+ GCC_except_table228
+ GCC_except_table237
+ GCC_except_table238
+ GCC_except_table248
+ GCC_except_table253
+ GCC_except_table276
+ GCC_except_table284
+ GCC_except_table285
+ GCC_except_table289
- -[ALAssetsLibraryPrivate photoLibraryDidChange:]
- GCC_except_table197
- GCC_except_table204
- GCC_except_table225
- GCC_except_table232
- GCC_except_table241
- GCC_except_table242
- GCC_except_table250
- GCC_except_table255
- GCC_except_table278
- GCC_except_table286
- GCC_except_table287
- GCC_except_table291
- _OBJC_CLASS_$_NSMutableSet
- _PLGenericChangeNotification
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_PLDerivedAlbumOrigin
- __OBJC_$_PROTOCOL_METHOD_TYPES_PLDerivedAlbumOrigin
- __OBJC_LABEL_PROTOCOL_$_PLDerivedAlbumOrigin
- __OBJC_PROTOCOL_$_PLDerivedAlbumOrigin
- __OBJC_PROTOCOL_REFERENCE_$_PLDerivedAlbumOrigin
- ___48-[ALAssetsLibraryPrivate photoLibraryDidChange:]_block_invoke
- ___block_descriptor_40_e8_32o_e39_v16?0"NSObject<PLIndexMappingCache>"8ls32l8
CStrings:
- "deletedAssetGroups"
- "insertedAssetGroups"
- "updatedAssetGroups"
- "updatedAssets"
- "v16@?0@\"NSObject<PLIndexMappingCache>\"8"
```
