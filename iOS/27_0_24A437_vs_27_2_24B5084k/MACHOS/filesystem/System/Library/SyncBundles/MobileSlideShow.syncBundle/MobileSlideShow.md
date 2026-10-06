## MobileSlideShow

> `/System/Library/SyncBundles/MobileSlideShow.syncBundle/MobileSlideShow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14a58` | `0x14734` | **`-0x324`** |
| `__TEXT.__objc_stubs` | `0x3340` | `0x3260` | **`-0xe0`** |
| `__TEXT.__objc_methname` | `0x3508` | `0x348f` | **`-0x79`** |
| `__TEXT.__auth_stubs` | `0x6b0` | `0x680` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x11d8` | `0x11a8` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0xff0` | `0xfc8` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0xf60` | `0xf40` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x6fa` | `0x6db` | **`-0x1f`** |
| `__DATA_CONST.__auth_got` | `0x368` | `0x350` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x430` | `0x420` | **`-0x10`** |
| `__TEXT.__cstring` | `0xd49` | `0xd3c` | **`-0xd`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 355
-  Symbols:   252
-  CStrings:  1037
+  Functions: 351
+  Symbols:   249
+  CStrings:  1029
Symbols:
- _CGImageSourceCopyPropertiesAtIndex
- _CGImageSourceCreateWithURL
- _CGImageSourceGetType
Functions:
~ sub_13a0 : 356 -> 204
- sub_1504
- sub_5540
- sub_55bc
- sub_57d8
CStrings:
- "@32@0:8r^v16Q24"
- "B32@0:8@16^@24"
- "RKFileUTType"
- "attributesOfItemAtPath:error:"
- "initWithPhotoBase64String:"
- "lastPathComponent"
- "numberBytes"
- "readPropertiesFromAssetURL:error:"
```
