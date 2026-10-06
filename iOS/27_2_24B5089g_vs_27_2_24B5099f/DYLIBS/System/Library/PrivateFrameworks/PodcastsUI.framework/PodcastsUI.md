## PodcastsUI

> `/System/Library/PrivateFrameworks/PodcastsUI.framework/PodcastsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13a0e8` | `0x13f0ec` | **`+0x5004`** |
| `__TEXT.__eh_frame` | `0x6c4c` | `0x6f8c` | **`+0x340`** |
| `__TEXT.__cstring` | `0x4716` | `0x4886` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0x5268` | `0x5368` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x7b18` | `0x7c10` | **`+0xf8`** |
| `__TEXT.__swift5_typeref` | `0x6604` | `0x66d2` | **`+0xce`** |
| `__AUTH.__data` | `0x5c0` | `0x680` | **`+0xc0`** |
| `__TEXT.__const` | `0xa6e0` | `0xa7a0` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0xb38` | `0xbe8` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x4088` | `0x4138` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x4834` | `0x48cc` | **`+0x98`** |
| `__DATA.__bss` | `0x68d0` | `0x6950` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x13e8` | `0x1460` | **`+0x78`** |
| `__DATA.__data` | `0x2260` | `0x22c0` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x2dc4` | `0x2e20` | **`+0x5c`** |
| `__AUTH_CONST.__const` | `0x7ff0` | `0x8040` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x3638` | `0x3680` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x26c0` | `0x2708` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1fd0` | `0x2010` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x474` | `0x4ac` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0x30` | `0x60` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x46e8` | `0x46b8` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1ccf` | `0x1cef` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x240` | `0x254` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `0x58` | `0x68` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x35fd` | `0x360d` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1f8` | `0x208` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1480` | `0x148c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x290` | `0x298` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x178` | `0x180` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x370` | `0x378` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x5c4` | `0x5c8` | **`+0x4`** |

### Other Changes

```diff

-4027.200.26.0.0
+4027.200.32.0.0

-  Functions: 6993
-  Symbols:   4968
-  CStrings:  856
+  Functions: 7050
+  Symbols:   4998
+  CStrings:  866
Symbols:
+ +[UIImage(IMAdditions) imageWithSolidColor:size:scale:]
+ -[UIImage(IMAdditions) im_imageDrawnAtSize:scale:traitCollection:]
+ -[UIImage(IMAdditions) im_imageFittingSize:scale:]
+ _OBJC_CLASS_$_UIGraphicsImageRenderer
+ _OBJC_CLASS_$_UIGraphicsImageRendererFormat
+ _OBJC_CLASS_$_UIImageAsset
+ _OBJC_CLASS_$__TtC10PodcastsUI14JSLoggerObject
+ _OBJC_METACLASS_$__TtC10PodcastsUI14JSLoggerObject
+ __DATA__TtC10PodcastsUI14JSLoggerObject
+ __INSTANCE_METHODS__TtC10PodcastsUI14JSLoggerObject
+ __METACLASS_DATA__TtC10PodcastsUI14JSLoggerObject
+ __PROTOCOLS__TtC10PodcastsUI14JSLoggerObject
+ __PROTOCOL_INSTANCE_METHODS__TtP10PodcastsUIP33_073169F0C459D372D438D3DD063ACE8414JSLoggerExport_
+ __PROTOCOL_METHOD_TYPES__TtP10PodcastsUIP33_073169F0C459D372D438D3DD063ACE8414JSLoggerExport_
+ __PROTOCOL_PROTOCOLS__TtP10PodcastsUIP33_073169F0C459D372D438D3DD063ACE8414JSLoggerExport_
+ __PROTOCOL__TtP10PodcastsUIP33_073169F0C459D372D438D3DD063ACE8414JSLoggerExport_
+ ___55+[UIImage(IMAdditions) imageWithSolidColor:size:scale:]_block_invoke
+ ___66-[UIImage(IMAdditions) im_imageDrawnAtSize:scale:traitCollection:]_block_invoke
+ ___66-[UIImage(IMAdditions) im_imageDrawnAtSize:scale:traitCollection:]_block_invoke_2
+ ___block_descriptor_56_e8_32s_e40_v16?0"UIGraphicsImageRendererContext"8ls32l8
+ ___block_descriptor_56_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_64_e8_32s40s_e40_v16?0"UIGraphicsImageRendererContext"8ls32l8s40l8
+ _swift_getObjCClassFromObject
+ _symbolic $s10PodcastsUI14JSLoggerExport33_073169F0C459D372D438D3DD063ACE84LLP
+ _symbolic SccySo5NSURLC______pG s5ErrorP
+ _symbolic _____ 10PodcastsUI14JSLoggerObjectC
+ _symbolic _____ 10PodcastsUI15JSPackageLoaderC14BagBundleEvent33_18B63FEF83672E4DD18B4210AD627E6ALLO
+ _symbolic _____Sg 10PodcastsUI15JSPackageLoaderC14BagBundleEvent33_18B63FEF83672E4DD18B4210AD627E6ALLO
+ _symbolic ____________pt 10Foundation3URLV 9JetEngine0C18PackResourceBundleP
+ _symbolic _____y___________pG s6ResultOsRi_zRi0_zrlE 10Foundation3URLV s5ErrorP
+ _symbolic _____y___________p_G Scg8IteratorV 10PodcastsUI15JSPackageLoaderC14BagBundleEvent33_18B63FEF83672E4DD18B4210AD627E6ALLO s5ErrorP
+ _symbolic _____y______p______pG s6ResultOsRi_zRi0_zrlE 9JetEngine0B18PackResourceBundleP s5ErrorP
+ _symbolic _____y______p______pGSg s6ResultOsRi_zRi0_zrlE 9JetEngine0B18PackResourceBundleP s5ErrorP
- +[UIImage(IMAdditions) imageWithSolidColor:atSize:]
- _UIGraphicsBeginImageContext
- _symbolic _____XMT 10PodcastsUI15JSPackageLoaderC
CStrings:
+ "%{public}s"
+ ", re-fetching JS package"
+ "Bag URL changed to "
+ "Failed to load JS package URL from bag: "
+ "Failed to re-fetch JS package, keeping initial package: "
+ "Fetched JS package from bag URL "
+ "Fetching JS package from bag URL "
+ "Loaded JS package URL from bag in "
+ "q"
+ "v16@?0@\"UIGraphicsImageRendererContext\"8"
```
