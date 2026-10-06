## AlchemistBase

> `/System/Library/PrivateFrameworks/AlchemistBase.framework/AlchemistBase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32608` | `0x2d634` | **`-0x4fd4`** |
| `__AUTH_CONST.__objc_const` | `0x4270` | `0x5268` | **`+0xff8`** |
| `__DATA.__bss` | `0x3020` | `0x3280` | **`+0x260`** |
| `__TEXT.__eh_frame` | `0x11f8` | `0x13e0` | **`+0x1e8`** |
| `__TEXT.__const` | `0x2500` | `0x2678` | **`+0x178`** |
| `__TEXT.__swift5_reflstr` | `0x852` | `0x992` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0x1930` | `0x1a68` | **`+0x138`** |
| `__DATA_CONST.__objc_selrefs` | `0x9b8` | `0x880` | **`-0x138`** |
| `__AUTH.__data` | `0xd8` | `0x1b0` | **`+0xd8`** |
| `__DATA_DIRTY.__data` | `0xae8` | `0xa30` | **`-0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0xac4` | `0xb74` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0xa00` | `0x978` | **`-0x88`** |
| `__TEXT.__swift5_typeref` | `0x8f6` | `0x898` | **`-0x5e`** |
| `__TEXT.__constg_swiftt` | `0xb8c` | `0xbe0` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0xc49` | `0xc89` | **`+0x40`** |
| `__DATA.__data` | `0x880` | `0x850` | **`-0x30`** |
| `__TEXT.__cstring` | `0xbe0` | `0xc10` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x150` | `0x168` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xf0` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x188` | `0x19c` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x878` | `0x888` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xe0` | `0xec` | **`+0xc`** |
| `__DATA.__common` | `0x40` | `0x48` | **`+0x8`** |

### Other Changes

```diff

-32.0.0.0.3
+32.0.1.0.0

-  - /System/Library/Frameworks/MetalPerformanceShadersGraph.framework/MetalPerformanceShadersGraph

-  Functions: 804
-  Symbols:   604
-  CStrings:  145
+  Functions: 800
+  Symbols:   598
+  CStrings:  146
Symbols:
+ __DATA__TtC13AlchemistBase16PanoDepthKernels
+ __IVARS__TtC13AlchemistBase16PanoDepthKernels
+ __METACLASS_DATA__TtC13AlchemistBase16PanoDepthKernels
+ _associated conformance 13AlchemistBase15MetalDepthErrorOSHAASQ
+ _expf
+ _swift_deallocPartialClassInstance
+ _symbolic SaySiG
+ _symbolic _____ 13AlchemistBase15MetalDepthErrorO
+ _symbolic _____ 13AlchemistBase16PanoDepthKernelsC
+ _symbolic _____ 13AlchemistBase9GPUTensorV
+ _symbolic _____ So20MLMultiArrayDataTypeV
+ _symbolic ______p So9MTLBufferP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13AlchemistBase9GPUTensorV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5Int32V
+ _type_layout_string 13AlchemistBase9GPUTensorV
- _OBJC_CLASS_$_MPSGraph
- _OBJC_CLASS_$_MPSGraphDevice
- _OBJC_CLASS_$_MPSGraphPooling2DOpDescriptor
- _OBJC_CLASS_$_MPSGraphTensor
- _OBJC_CLASS_$_MPSGraphTensorData
- _OBJC_CLASS_$_NSLock
- __DATA__TtC13AlchemistBase19MPSTensorOperations
- __IVARS__TtC13AlchemistBase19MPSTensorOperations
- __METACLASS_DATA__TtC13AlchemistBase19MPSTensorOperations
- _logf
- _swift_getKeyPath
- _swift_readAtKeyPath
- _swift_retain_x28
- _swift_setAtReferenceWritableKeyPath
- _symbolic So14MPSGraphTensorC_So0aB4DataCt
- _symbolic So6NSLockC
- _symbolic _____ 13AlchemistBase19MPSTensorOperationsC
- _symbolic ______pSg So9MTLBufferP
- _symbolic _____ySi5start_Si6lengthtSgG s23_ContiguousArrayStorageC
- _symbolic _____ySo14MPSGraphTensorCSo0aB4DataCG s18_DictionaryStorageC
- _symbolic _____ySo14MPSGraphTensorC_So0aB4DataCtG s23_ContiguousArrayStorageC
CStrings:
+ "Active ROI aspect ratio is less than lowest enumerated aspect ratio (%f, %f)"
+ "Internal erorr: no enumerated aspect ratios for the tiling mode"
+ "Metal depth kernels unavailable."
+ "PanoDepthKernels: default.metallib not found in "
+ "PanoDepthKernels: init failed — "
+ "PanoDepthKernels: missing kernel "
+ "adjustDeltaOrder"
+ "adjustDisparityOrder"
+ "depthToDisparity"
+ "disparityToDepth"
+ "sliceDepthWindow"
- "AlchemistBase/MPSGraphUtils.swift"
- "Cannot find an aspect ratio for pano image with aspect ratio %f"
- "Failed to create Metal device and command queue"
- "MPS doesn't support float64, fallback to float32"
- "_src_mean_tgt_mean"
- "adjusted_disparity"
- "disparity_pooled"
- "is_desc_broadcast"
- "is_desc_squeezed"
- "normalized_sigmoid"
```
