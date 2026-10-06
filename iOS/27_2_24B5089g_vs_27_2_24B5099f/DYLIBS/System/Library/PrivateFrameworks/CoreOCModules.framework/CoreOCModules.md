## CoreOCModules

> `/System/Library/PrivateFrameworks/CoreOCModules.framework/CoreOCModules`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72fa4` | `0x75874` | **`+0x28d0`** |
| `__TEXT.__oslogstring` | `0x6db2` | `0x6f6b` | **`+0x1b9`** |
| `__DATA.__data` | `0xc0` | `—` | **`-0xc0`** |
| `__DATA_DIRTY.__data` | `—` | `0xc0` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x283c` | `0x28f8` | **`+0xbc`** |
| `__TEXT.__unwind_info` | `0xe38` | `0xe88` | **`+0x50`** |
| `__DATA.__bss` | `0x548` | `0x568` | **`+0x20`** |
| `__TEXT.__cstring` | `0x48a4` | `0x48b5` | **`+0x11`** |
| `__AUTH_CONST.__auth_got` | `0x888` | `0x890` | **`+0x8`** |

### Other Changes

```diff

-11.3.6.0.0
+11.3.7.0.0

-  Functions: 861
-  Symbols:   624
-  CStrings:  792
+  Functions: 862
+  Symbols:   625
+  CStrings:  810
Symbols:
+ __os_signpost_emit_with_name_impl
+ _os_signpost_enabled
- _kdebug_trace
CStrings:
+ "BBoxSegmentation"
+ "BoundingBoxCompute"
+ "BoundingBoxFeatureComputing"
+ "BoundingBoxFitting"
+ "BoundingBoxKNNSearch"
+ "BoundingBoxRegionGrowing"
+ "CoveragePerCamera"
+ "ExplicitFeedbackProcessPointCloud"
+ "PointsOfInterest"
+ "VoxelHashingCreateResults"
+ "VoxelHashingFullPipeline"
+ "VoxelHashingMeshCopy"
+ "VoxelHashingPointCloudDensification"
+ "VoxelHashingPointCloudProcessing"
+ "VoxelHashingSurfaceSampling"
+ "VoxelHashingTSDFDepthRendering"
+ "VoxelHashingVoxelBlockCleanup"
+ "VoxelHashingVoxelIntegration"
```
