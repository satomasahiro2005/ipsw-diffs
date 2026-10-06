## MetricMeasurement

> `/System/Library/PrivateFrameworks/MetricMeasurement.framework/MetricMeasurement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d41c` | `0x1da90` | **`+0x674`** |
| `__TEXT.__oslogstring` | `0x9d5` | `0xb07` | **`+0x132`** |
| `__AUTH_CONST.__cfstring` | `0x2800` | `0x28a0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x268f` | `0x2718` | **`+0x89`** |
| `__AUTH_CONST.__objc_const` | `0x59d8` | `0x5a08` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1558` | `0x1578` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x28c4` | `0x28e4` | **`+0x20`** |
| `__TEXT.__const` | `0x268` | `0x278` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x9a0` | `0x9a8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x170` | `0x174` | **`+0x4`** |

### Other Changes

```diff

-353.0.0.0.0
+356.0.0.0.0

-  Functions: 871
-  Symbols:   1663
-  CStrings:  396
+  Functions: 874
+  Symbols:   1667
+  CStrings:  402
Symbols:
+ +[MXMOSSignpostSampleTag animationNormalizedPerAppNonFirstFrameGlitchTimeRatioAdjusted]
+ -[MXMOSSignpostProbe _addAnimationNormalizedGlitchTimeRatioToData:fromSignpostAnimationInterval:]
+ GCC_except_table34
+ GCC_except_table50
+ GCC_except_table52
+ _OBJC_IVAR_$_MXMOSSignpostProbe._accumulatedAnimationIntervals
+ ___97-[MXMOSSignpostProbe _addAnimationNormalizedGlitchTimeRatioToData:fromSignpostAnimationInterval:]_block_invoke
- GCC_except_table33
- GCC_except_table49
- GCC_except_table51
CStrings:
+ "NSProcessInfoInteractionTracking"
+ "Normalized HTR: %lu overlapping intervals, %lu after union, %.4f seconds animation time."
+ "Normalized HTR: No overlapping NSProcessInfoInteractionTracking intervals found for this signpost window."
+ "Normalized Hitch Time Ratio ('%@'): %.4f ms/s (adjusted hitch time: %.4f ms, total animation duration: %.4f s)"
+ "com.apple.Foundation"
+ "os_signpost.animation.hitch.normalized.per_app.non_first_frame.time.ratio.adjusted"
```
