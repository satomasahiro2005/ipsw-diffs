## RawCamera

> `/System/Library/CoreServices/RawCamera.bundle/RawCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x229210` | `0x22acb0` | **`+0x1aa0`** |
| `__TEXT.__const` | `0x18164` | `0x18504` | **`+0x3a0`** |
| `__TEXT.__gcc_except_tab` | `0x31568` | `0x31838` | **`+0x2d0`** |
| `__AUTH_CONST.__cfstring` | `0x1ac60` | `0x1ae00` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x122f1` | `0x12401` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x6d28` | `0x6dc8` | **`+0xa0`** |
| `__AUTH_CONST.__objc_intobj` | `0x3af8` | `0x3b58` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x283b` | `0x2880` | **`+0x45`** |
| `__DATA_CONST.__objc_arraydata` | `0x3b10` | `0x3b50` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xc668` | `0xc698` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2c10` | `0x2c30` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x5d0` | `0x5e4` | **`+0x14`** |
| `__DATA.__data` | `0x20e60` | `0x20e68` | **`+0x8`** |

### Other Changes

```diff

-1814.0.0.0.0
+1817.0.0.0.0

-  Functions: 7740
+  Functions: 7749

-  CStrings:  4212
+  CStrings:  4225
CStrings:
+ "%{public}s inputInferenceDevice 'MPSGraph' requires RawCamera built with RAWCAMERA_ENABLE_MPSGRAPH=YES; the MPSGraph backend is not compiled in. Falling back to ANE."
+ "%{public}s model build failed"
+ "+[RAWDemosaicProcessorV9 getModelForCFAPattern:useQuarterRes:useAltModel:useMPSGraph:]"
+ "MPSGraph"
+ "deFujiEXR_v8"
+ "deSuperCCDSR_v8"
+ "inputFujiEXROutputSize"
+ "inputFujiEXRRawCrop"
+ "inputSuperCCDSRLayout"
+ "inputSuperCCDSROutputSize"
+ "inputSuperCCDSRRawCrop"
+ "kCGImageSourceEnableCache"
+ "rsp_FujiEXRCMOS_BG_GR"
+ "rsp_FujiEXRCMOS_GB_RG"
+ "rsp_FujiEXRCMOS_GR_BG"
+ "rsp_FujiEXRCMOS_RG_GB"
- "%{public}s EspressoWrapper build failed"
- "+[RAWDemosaicProcessorV9 getModelForCFAPattern:useQuarterRes:useAltModel:]"
- "DNGLosslessJpegUnpacker: destination pointer out of reasonable range at row %d, col %d"
```
