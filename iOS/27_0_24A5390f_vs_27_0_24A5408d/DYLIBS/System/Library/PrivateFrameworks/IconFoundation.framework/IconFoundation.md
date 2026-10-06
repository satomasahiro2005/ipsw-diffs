## IconFoundation

> `/System/Library/PrivateFrameworks/IconFoundation.framework/IconFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39540` | `0x39ad0` | **`+0x590`** |
| `__AUTH_CONST.__objc_const` | `0x4cc8` | `0x4e08` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x30ac` | `0x3164` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x410` | `0x460` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ef0` | `0x1f40` | **`+0x50`** |
| `__TEXT.__cstring` | `0x12cb1` | `0x12ce1` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xf08` | `0xf38` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x7528` | `0x7550` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0xc2c` | `0xc46` | **`+0x1a`** |
| `__AUTH_CONST.__auth_got` | `0x8d8` | `0x8e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x33c` | `0x348` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x110` | `0x118` | **`+0x8`** |

### Other Changes

```diff

-788.0.0.0.0
+792.100.0.0.0

-  Functions: 1533
-  Symbols:   2530
-  CStrings:  2888
+  Functions: 1548
+  Symbols:   2558
+  CStrings:  2890
Symbols:
+ -[IFBundle _platformWithLaunchServicesUsageAllowed:]
+ -[IFBundle computedPlatformWithLS]
+ -[IFBundle computedPlatformWithoutLS]
+ -[IFBundle init]
+ -[IFBundle setComputedPlatformWithLS:]
+ -[IFBundle setComputedPlatformWithoutLS:]
+ -[IFImageInspector dealloc]
+ -[IFImageInspector hasNoAlpha]
+ -[IFImageInspector image]
+ -[IFImageInspector initWithCGImage:]
+ -[IFImageInspector isCenterPixelTransparent]
+ -[IFImageInspector isSampleTransparentAtX:y:imageWidth:imageHeight:]
+ -[IFImageInspector isTransparentUsingSampleCount:]
+ -[IFSymbol resolvedName]
+ GCC_except_table40
+ _CGImageGetAlphaInfo
+ _CGImageRetain
+ _OBJC_CLASS_$_IFImageInspector
+ _OBJC_IVAR_$_IFBundle._computedPlatformWithLS
+ _OBJC_IVAR_$_IFBundle._computedPlatformWithoutLS
+ _OBJC_IVAR_$_IFImageInspector._image
+ _OBJC_METACLASS_$_IFImageInspector
+ __OBJC_$_INSTANCE_METHODS_IFImageInspector
+ __OBJC_$_INSTANCE_VARIABLES_IFImageInspector
+ __OBJC_$_PROP_LIST_IFImageInspector
+ __OBJC_CLASS_RO_$_IFImageInspector
+ __OBJC_METACLASS_RO_$_IFImageInspector
+ ___31-[IFSymbol imageForDescriptor:]_block_invoke
+ ___block_descriptor_40_e8_32s_e54_"CUINamedVectorGlyph"24?0"CUICatalog"8"NSString"16ls32l8
- GCC_except_table39
CStrings:
+ "%@ Resolved name %@ -> %@"
+ "@\"CUINamedVectorGlyph\"24@?0@\"CUICatalog\"8@\"NSString\"16"
+ "A"
- "!"
```
