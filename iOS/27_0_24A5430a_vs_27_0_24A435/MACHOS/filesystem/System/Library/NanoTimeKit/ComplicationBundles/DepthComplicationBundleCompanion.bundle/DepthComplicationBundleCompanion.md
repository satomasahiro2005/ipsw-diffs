## DepthComplicationBundleCompanion

> `/System/Library/NanoTimeKit/ComplicationBundles/DepthComplicationBundleCompanion.bundle/DepthComplicationBundleCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x308c0` | `0x30a0c` | **`+0x14c`** |
| `__TEXT.__auth_stubs` | `0x1650` | `0x16e0` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0xb30` | `0xb78` | **`+0x48`** |
| `__DATA_CONST.__const` | `0xb40` | `0xb80` | **`+0x40`** |
| `__TEXT.__cstring` | `0xdf5` | `0xe25` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x73c` | `0x75c` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1d3b` | `0x1d5b` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1300` | `0x1320` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x6c0` | `0x6d8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x410` | `0x428` | **`+0x18`** |
| `__DATA.__bss` | `0x280` | `0x290` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x700` | `0x710` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

+  - /System/Library/Frameworks/CoreText.framework/CoreText

-  Functions: 606
-  Symbols:   249
-  CStrings:  513
+  Functions: 610
+  Symbols:   263
+  CStrings:  519
Symbols:
+ _CFDataCreateWithBytesNoCopy
+ _CFRelease
+ _CTFontManagerCreateFontDescriptorFromData
+ _OBJC_CLASS_$_NSCache
+ __NSConcreteGlobalBlock
+ ___CFConstantStringClassReference
+ _abort
+ _dispatch_once
+ _getsectiondata
+ _kCFAllocatorDefault
+ _kCFAllocatorNull
+ _objc_alloc_init
+ _objc_claimAutoreleasedReturnValue
+ _objc_release_x1
CStrings:
+ "__ClipperFont"
+ "__FONT_DATA"
+ "deviceIsZeus"
+ "objectForKey:"
+ "zeus"
+ "zeusFontDescriptor"
```
