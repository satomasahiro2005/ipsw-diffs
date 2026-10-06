## RawCamera

> `/System/Library/CoreServices/RawCamera.bundle/RawCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x500` | `0x12c0` | **`+0xdc0`** |
| `__DATA_DIRTY.__objc_data` | `0xe60` | `0xf0` | **`-0xd70`** |
| `__DATA_CONST.__got` | `0x0` | `0xac8` | **`+0xac8`** |
| `__TEXT.__text` | `0x229a2c` | `0x229210` | **`-0x81c`** |
| `__AUTH_CONST.__objc_const` | `0x6c40` | `0x6d28` | **`+0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x1ab80` | `0x1ac60` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x31504` | `0x31568` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x23c0` | `0x2424` | **`+0x64`** |
| `__DATA_CONST.__objc_selrefs` | `0x1690` | `0x16e8` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x1380` | `0x13b8` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x2873` | `0x283b` | **`-0x38`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x4b0` | `0x4e0` | **`+0x30`** |
| `__DATA.__bss` | `0x72b0` | `0x72e0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xc638` | `0xc668` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x3c588` | `0x3c5a8` | **`+0x20`** |
| `__TEXT.__const` | `0x18184` | `0x18164` | **`-0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x3ae0` | `0x3af8` | **`+0x18`** |
| `__DATA.__data` | `0x20e70` | `0x20e60` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x3b20` | `0x3b10` | **`-0x10`** |
| `__TEXT.__cstring` | `0x12301` | `0x122f1` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1298` | `0x12a0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x5c7` | `0x5bf` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5cc` | `0x5d0` | **`+0x4`** |

### Other Changes

```diff

-1810.0.0.0.1
+1814.0.0.0.0

-  Functions: 7739
+  Functions: 7740

-  CStrings:  4210
+  CStrings:  4212
Symbols:
+ _kCIImageFlipped
+ _xpc_copy_entitlement_for_self
- _kCIContextWorkingColorSpace
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%{public}s EspressoWrapper build failed"
+ "%{public}s Failed to load the model."
+ "%{public}s Unsupported CFA pattern 0x%X"
+ "%{public}s failed cachedWrapperForPath"
+ "%{public}s ⚠️ MobileAsset framework: SKIPPED (Darwin-notification restricted process, e.g. BlastDoor)"
+ "+[RAWDemosaicProcessorV9 getModelForCFAPattern:useQuarterRes:useAltModel:]"
+ "@\"NSString\"16@?0@\"NSString\"8"
+ "CIEspressoWrapper"
+ "CIImageSurfaceFormat"
+ "MLdemosaicClear"
+ "MLdemosaicTile_%d_%d"
+ "RAWDespeckleV9"
+ "UseAltModel"
+ "addBackBlur"
+ "addBackLimit"
+ "addBackOffset"
+ "com.apple.private.darwin-notification.introspect"
+ "kernelMakeAddBack"
+ "modelPathBayer"
+ "modelPathQuadra"
+ "modelPathQuarterResBayer"
+ "modelPathQuarterResQuadra"
+ "modelPathQuarterResXTrans"
+ "modelPathXTrans"
+ "planarToInterleaved3"
+ "reflectPad"
+ "tileGroupSize"
+ "tileOffsetX"
+ "tileOffsetY"
+ "tileSizeH"
+ "tileSizeW"
- "\n"
- "%{public}s Failed to create cached wrapper"
- "%{public}s One of the arguments we depend on was nil"
- "%{public}s V9 model override for '%s' ignored — only .mil paths are supported (got: %s)"
- "%{public}s unexpected xtrans pattern %d 0x%x\n"
- "%{public}s unsupported bayer pattern %d 0x%x\n"
- "+[RAWDemosaicProcessorV9 getModelPathForCFAPattern:useQuarterRes:]_block_invoke"
- "-[RAWDemosaicFilterV9 phaseForBayer]"
- "-[RAWDemosaicFilterV9 phaseForQuadra]"
- "-[RAWDemosaicFilterV9 phaseForXtrans]"
- "@\"NSString\"24@?0@\"NSString\"8@\"NSString\"16"
- "MLdemosaicV9OneInTileClear"
- "MLdemosaicV9Tile_%d_%d"
- "NEWEST_ADDBACK"
- "RawFutureProcessor"
- "V9 Espresso model override for '%s': %s"
- "applyAddBackChannel3"
- "bayerReflectPad"
- "com.apple.rawcamera.demosaicV9"
- "inputAddBackVers"
- "kernelNoisePlanarize is nil"
- "kernelPlanarize is nil"
- "makeAddBackChannel"
- "oneInTile"
- "quadraReflectPad"
- "tileSize"
- "v3b"
- "vNext"
- "xtransReflectPad"
```
