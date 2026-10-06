## FramePacing

> `/System/Library/PrivateFrameworks/FramePacing.framework/FramePacing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x263ac` | `0x26ad0` | **`+0x724`** |
| `__TEXT.__cstring` | `0x2fae` | `0x30aa` | **`+0xfc`** |
| `__AUTH_CONST.__objc_const` | `0x2ff0` | `0x2fa8` | **`-0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xc58` | `0xc90` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x1320` | `0x1340` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x580` | `0x5a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x158` | `0x170` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xb88` | `0xb70` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0x268` | `0x278` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1588` | `0x1578` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xb48` | `0xb38` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x330` | `0x328` | **`-0x8`** |

### Other Changes

```diff

-5.0.19.0.0
+5.0.22.0.0

-  Symbols:   1440
-  CStrings:  586
+  Symbols:   1442
+  CStrings:  598
Symbols:
+ -[FPMTLMetricsMTLLayerTracking _pruneStaleDrawableStates]
+ GCC_except_table100
+ GCC_except_table113
+ GCC_except_table119
+ GCC_except_table199
+ GCC_except_table33
+ GCC_except_table40
+ GCC_except_table51
+ GCC_except_table59
+ GCC_except_table66
+ _OBJC_CLASS_$_NSFileManager
+ ____FPMTLMetricsCommandBufferLogFile_block_invoke
+ ___stdoutp
+ _fopen
+ _fprintf
+ _fwrite
+ _setlinebuf
- -[FPMTLMetricsServiceInternal metalGetEncoderCounterOffset:encoderTraceId:]
- GCC_except_table102
- GCC_except_table114
- GCC_except_table121
- GCC_except_table200
- GCC_except_table29
- GCC_except_table37
- GCC_except_table46
- GCC_except_table55
- GCC_except_table60
- GCC_except_table67
- _FPMTLMetricsGPUTimeTrackerGetEncoderCounterOffset
- _OBJC_IVAR_$_FPMTLMetricsMTLLayerTracking._currentDrawableStateIndex
- _OBJC_IVAR_$_FPMTLMetricsMTLLayerTracking._drawableIDToStateIndex
- __ZNSt3__112__hash_tableINS_17__hash_value_typeIymEENS_22__unordered_map_hasherIyNS_4pairIKymEENS_4hashIyEENS_8equal_toIyEEEENS_21__unordered_map_equalIyS6_SA_S8_EENS_9allocatorIS6_EEE4findIyEENS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEERKT_
CStrings:
+ "%zu,%s,%zu,%llu,%llu,%llu\n"
+ "%zu,cb,%zu,%llu,%llu,%llu\n"
+ "MTL_METRICS_LOG_TIMING_FILE"
+ "[MetalMetrics] MTL_METRICS_LOG_TIMING_FILE: failed to open '%s': %s"
+ "as"
+ "blit"
+ "com.apple.InCallService"
+ "compute"
+ "fragment"
+ "frame,kind,index,gpu_begin_ns,gpu_end_ns,gpu_duration_ns\n"
+ "ml"
+ "vertex"
+ "w"
- "com.apple.dock"
```
