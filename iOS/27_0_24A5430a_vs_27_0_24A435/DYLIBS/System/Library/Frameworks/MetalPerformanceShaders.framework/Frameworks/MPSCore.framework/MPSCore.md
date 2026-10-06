## MPSCore

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x962b8` | `0x96a4c` | **`+0x794`** |
| `__TEXT.__cstring` | `0xa62c` | `0xa812` | **`+0x1e6`** |
| `__AUTH_CONST.__cfstring` | `0x37e0` | `0x3900` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x58c0` | `0x5990` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x5f30` | `0x5ff0` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x5230` | `0x52c8` | **`+0x98`** |
| `__TEXT.__const` | `0x2924` | `0x2974` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x13d8` | `0x1410` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x4db0` | `0x4dd8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1e38` | `0x1e60` | **`+0x28`** |
| `__DATA.__bss` | `0x1c` | `0x30` | **`+0x14`** |
| `__DATA_DIRTY.__objc_ivar` | `0x54` | `0x64` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x27f4` | `0x27fc` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1726
+  Functions: 1732

-  CStrings:  879
+  CStrings:  893
CStrings:
+ "Error: unhandled forward progress usage above"
+ "MPSParallelScan.simdYieldTime"
+ "MPSParallelScan.useConstantSIMDYield"
+ "MPSParallelScan.useExponentialSIMDYield"
+ "MPSParallelScan.useTameBackOff"
+ "MPS_SINGLE_PASS_SCAN_SIMD_YIELD_TIME"
+ "MPS_SINGLE_PASS_SCAN_USE_CONSTANT_SIMD_YIELD"
+ "MPS_SINGLE_PASS_SCAN_USE_EXPONENTIAL_SIMD_YIELD"
+ "MPS_SINGLE_PASS_SCAN_USE_TAME_BACKOFF"
+ "MPS_USE_SFE_API"
+ "SIMDGroup Parallel Forward Progress is not supported on this device"
+ "agx_forward_progress_mode"
+ "simdgroup_parallel"
+ "weak"
```
