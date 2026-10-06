## CMPhoto

> `/System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e4d68` | `0x1e564c` | **`+0x8e4`** |
| `__AUTH_CONST.__objc_const` | `0x2f58` | `0x2f78` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2580` | `0x2590` | **`+0x10`** |
| `__TEXT.__const` | `0x136a4` | `0x13694` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1d40` | `0x1d48` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xbc0` | `0xbc8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x894` | `0x89c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4748` | `0x4750` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x10c` | `0x110` | **`+0x4`** |

### Other Changes

```diff

-486.0.0.0.1
+488.22.2.0.0

-  Functions: 7628
-  Symbols:   11869
+  Functions: 7636
+  Symbols:   11878
Symbols:
+ -[CMPhotoTiledLayer _gainMapHeadroomForAuxiliaryIndex:]
+ GCC_except_table30
+ _CGColorSpaceGetHeadroomInfo
+ _FigCFNumberCreateFloat32
+ _OBJC_IVAR_$_CMPhotoTiledLayer._contentHeadroom
+ _OUTLINED_FUNCTION_163
+ _OUTLINED_FUNCTION_164
+ __blackLevelRationalFromDouble
+ __computeDestinationBlackLevels
+ __ifdAddDNGBlackLevelTag
+ _kIOSurfaceContentHeadroom
- GCC_except_table29
- __addRawImageTags.blackLevelRepeatDim
```
