## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67dc0` | `0x67fec` | **`+0x22c`** |
| `__AUTH_CONST.__objc_const` | `0x14110` | `0x141b0` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4a40` | `0x4a80` | **`+0x40`** |
| `__TEXT.__cstring` | `0x464d` | `0x467e` | **`+0x31`** |
| `__AUTH_CONST.__objc_intobj` | `0x558` | `0x588` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6a44` | `0x6a74` | **`+0x30`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x108` | `0x120` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xb0` | `0xc8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3230` | `0x3248` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a40` | `0x1a38` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 2637
-  Symbols:   5013
-  CStrings:  1096
+  Functions: 2640
+  Symbols:   5021
+  CStrings:  1099
Symbols:
+ -[ISDefaults isForceHomeAccessoryDeviceEnabled]
+ -[ISDeviceInfo isHomeAccessoryDevice]
+ -[ISHomeAccessoryAppRecipe iconSpecification]
+ _OBJC_CLASS_$_ISHomeAccessoryAppRecipe
+ _OBJC_METACLASS_$_ISHomeAccessoryAppRecipe
+ __OBJC_$_INSTANCE_METHODS_ISHomeAccessoryAppRecipe
+ __OBJC_CLASS_RO_$_ISHomeAccessoryAppRecipe
+ __OBJC_METACLASS_RO_$_ISHomeAccessoryAppRecipe
Functions:
~ ___55-[CUICatalog(IconServicesAdditions) idiomsForPlatform:]_block_invoke : 168 -> 220
~ +[ISRecipeInfo appRecipeForPlatform:descriptor:preferRichRecipe:] : 340 -> 460
~ -[ISPlatformInfo supportsRequestingIconStacksForPlatform:] : 240 -> 300
+ ___55-[CUICatalog(IconServicesAdditions) idiomsForPlatform:]_block_invoke.85
~ -[ISPlatformInfo supportsRequestingMultisizedImagesForPlatform:] : 156 -> 224
~ -[ISImageDescriptor continuousCornerRadius] : 272 -> 296
+ -[ISHomeAccessoryAppRecipe iconSpecification]
~ ___38+[ISSymbol _variantOptionsToKeyPieces]_block_invoke : 840 -> 888
+ -[ISDefaults simulateTintableAppearance]
~ -[ISCompositingDescriptor CUINamedImageDeviceClass] : 312 -> 356
~ -[ISCompositingDescriptor encapsulationShape] : 368 -> 416
~ -[ISDeviceInfo homeScreenIconSize] : 432 -> 484
+ -[ISDeviceInfo screenClass]
- ___55-[CUICatalog(IconServicesAdditions) idiomsForPlatform:]_block_invoke.82
CStrings:
+ "22:36:40"
+ "force_accessory"
+ "homeaccessory"
+ "homeaccessory_wall"
- "20:38:04"
```
