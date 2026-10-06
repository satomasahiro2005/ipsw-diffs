## RawCamera

> `/System/Library/CoreServices/RawCamera.bundle/RawCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x226ff4` | `0x229a2c` | **`+0x2a38`** |
| `__TEXT.__gcc_except_tab` | `0x30edc` | `0x31504` | **`+0x628`** |
| `__AUTH_CONST.__cfstring` | `0x1a6a0` | `0x1ab80` | **`+0x4e0`** |
| `__TEXT.__cstring` | `0x11f61` | `0x12301` | **`+0x3a0`** |
| `__AUTH_CONST.__objc_const` | `0x69b0` | `0x6c40` | **`+0x290`** |
| `__TEXT.__const` | `0x17f14` | `0x18184` | **`+0x270`** |
| `__AUTH_CONST.__const` | `0x3c3e0` | `0x3c588` | **`+0x1a8`** |
| `__TEXT.__unwind_info` | `0xc570` | `0xc638` | **`+0xc8`** |
| `__AUTH.__data` | `0x6e8` | `0x7a8` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x2b80` | `0x2c10` | **`+0x90`** |
| `__DATA.__data` | `0x20e18` | `0x20e70` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x13d8` | `0x1380` | **`-0x58`** |
| `__AUTH.__objc_data` | `0x4b0` | `0x500` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x2370` | `0x23c0` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x13ec` | `0x1438` | **`+0x4c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1648` | `0x1690` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x48` | `0x8` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x9d8` | `0xa14` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x1260` | `0x1298` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x283c` | `0x2873` | **`+0x37`** |
| `__AUTH_CONST.__objc_intobj` | `0x3ab0` | `0x3ae0` | **`+0x30`** |
| `__DATA.__bss` | `0x7290` | `0x72b0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x5b4` | `0x5cc` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x5b3` | `0x5c7` | **`+0x14`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x4a0` | `0x4b0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x228` | `0x238` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x238` | `0x248` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xd4` | `0xd8` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1805.0.0.0.0
+1810.0.0.0.1

-  Functions: 7697
-  Symbols:   974
-  CStrings:  4167
+  Functions: 7739
+  Symbols:   982
+  CStrings:  4210
Symbols:
+ _MPSSetBinaryArchives
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_MTLBinaryArchiveDescriptor
+ _atexit_b
+ _dispatch_apply
+ _objc_retain_x7
+ _strcpy
+ _swift_initStackObject
+ _swift_release_x12
- _objc_retainAutoreleasedReturnValue
CStrings:
+ "%{public}s oneInTile: output clear failed"
+ "54"
+ "88"
+ "AGC"
+ "AWBComboBGain"
+ "AWBComboGGain"
+ "AWBComboRGain"
+ "CIFF:CanonColorInfo2"
+ "GlobalShutterFlag"
+ "LuxLevel"
+ "MLdemosaicV9OneInTileClear"
+ "MLdemosaicV9Tile_%d_%d"
+ "RAWLinearize"
+ "RCMPSModelWrapper: Failed to open binary archive - %@"
+ "RCMPSModelWrapper: Failed to serialize archive - %@"
+ "RCMPSModelWrapper: Harvest will accumulate into existing archive at %@"
+ "RCMPSModelWrapper: Harvesting MPSGraph shaders to %@"
+ "RCMPSModelWrapper: Loading MPSGraph binary archive from %@"
+ "RCMPSModelWrapper: MPSSetBinaryArchives returned %@"
+ "RCMPSModelWrapper: Serialized MPSGraph binary archive to %@"
+ "RC_HarvestMPSGraphShaders"
+ "SensorID"
+ "applyWithTiledExtent:inputs:arguments:error:"
+ "baselineExposureFromTag"
+ "deRGBE_v7"
+ "hasBaselineExposureTag"
+ "ispDGain"
+ "kCGImageSourceNoiseModelOffset"
+ "mpsgraph"
+ "mpsgraph.metallib"
+ "noiseModelOffsetAmount"
+ "oneInTile"
+ "quadraReflectPad"
+ "rawcamera_mpsgraph_harvest"
+ "rsp_RE_GB"
+ "sensorDGain"
+ "super wide"
+ "telephoto"
+ "tileOutsetX"
+ "tileOutsetY"
+ "tileStrideX"
+ "tileStrideY"
+ "ultra wide"
+ "v16@?0Q8"
+ "xtransReflectPad"
+ "{ExifAux}"
+ "{MakerApple}"
- "imageByInsertingTiledIntermediate"
- "rsp_GY_MC"
- "tileOutset"
- "tileStride"
```
