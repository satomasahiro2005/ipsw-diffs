## ClockKitUI

> `/System/Library/PrivateFrameworks/ClockKitUI.framework/ClockKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37dac` | `0x38684` | **`+0x8d8`** |
| `__TEXT.__oslogstring` | `0xf1a` | `0x11d8` | **`+0x2be`** |
| `__AUTH_CONST.__cfstring` | `0x11a0` | `0x11e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1354` | `0x1394` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x6e8` | `0x708` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xb90` | `0xbb0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a70` | `0x2a90` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x484c` | `0x4864` | **`+0x18`** |
| `__DATA.__bss` | `0x518` | `0x528` | **`+0x10`** |
| `__TEXT.__const` | `0x80d6` | `0x80e6` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1120` | `0x1128` | **`+0x8`** |

### Other Changes

```diff

-2483.480.0.4.0
+2483.493.1.0.0

-  Functions: 1801
-  Symbols:   3377
-  CStrings:  286
+  Functions: 1809
+  Symbols:   3383
+  CStrings:  296
Symbols:
+ -[CLKUIMetalBinaryArchive newComputePipelineStateForDevice:withDescriptor:]
+ -[CLKUIMetalBinaryArchive newTileRenderPipelineStateForDevice:withDescriptor:]
+ ____use20FPSAnimation_block_invoke
+ __use20FPSAnimation
+ __use20FPSAnimation.__use20FPS
+ __use20FPSAnimation.onceToken
CStrings:
+ "Compute Pipeline"
+ "NanoTimeKit"
+ "Tile Pipeline"
+ "[%@] Error creating a MTLComputePipelineState with a MTLBinaryArchive; state=(%@) shader=(%@) device=(%@); error=%@"
+ "[%@] Error creating a MTLComputePipelineState without a MTLBinaryArchive; state=(%@) shader=(%@) device=(%@); error=%@"
+ "[%@] Error creating a tile MTLRenderPipelineState with a MTLBinaryArchive; state=(%@) shader=(%@) device=(%@); error=%@"
+ "[%@] Error creating a tile MTLRenderPipelineState without a MTLBinaryArchive; state=(%@) shader=(%@) device=(%@); error=%@"
+ "[%@] Requesting new MTLComputePipelineState and binary archives are enabled but the archive is nil; name=(%@)"
+ "[%@] Requesting new tile MTLRenderPipelineState and binary archives are enabled but the archive is nil; name=(%@)"
+ "hands_20fps_animation"
```
