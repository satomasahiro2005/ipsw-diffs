## ASEProcessing

> `/System/Library/PrivateFrameworks/ASEProcessing.framework/ASEProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8fe8` | `0x8e9c` | **`-0x14c`** |
| `__DATA_CONST.__const` | `0x228` | `0x2a8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x170` | `0x178` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-1.58.0.0.0
+1.59.0.0.0

-  Functions: 122
-  Symbols:   673
+  Functions: 123
+  Symbols:   674
Symbols:
+ _getWeightedBlendConfig
Functions:
~ _calculate_control_setting_V3 : 1672 -> 1212
+ _getWeightedBlendConfig
CStrings:
+ " [1.59.0] \n"
+ " [1.59.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d\n"
+ " [1.59.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d, fps=%f\n"
+ " [1.59.0]  %30s: %-12d\n"
+ " [1.59.0] %s : bad argument, retVal=%ld, input=%p, aseMeasurementOutput=%p, completionCallback=%p\n"
+ " [1.59.0] %s : config=%p"
+ " [1.59.0] %s : input=%p, aseMeasurementOutput=%p, aseFrameProcessingControl=%p"
+ " [1.59.0] %s : instance=%p, productType=%u, destinationWidth=%d, destinationHeight=%d, inputType=%s"
+ " [1.59.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d"
+ " [1.59.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d\n"
+ " [1.59.0] %s: Frame #%llu:\n"
+ " [1.59.0] ++ %s: ASEApiVer=%d\n"
- " [1.58.0] \n"
- " [1.58.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d\n"
- " [1.58.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d, fps=%f\n"
- " [1.58.0]  %30s: %-12d\n"
- " [1.58.0] %s : bad argument, retVal=%ld, input=%p, aseMeasurementOutput=%p, completionCallback=%p\n"
- " [1.58.0] %s : config=%p"
- " [1.58.0] %s : input=%p, aseMeasurementOutput=%p, aseFrameProcessingControl=%p"
- " [1.58.0] %s : instance=%p, productType=%u, destinationWidth=%d, destinationHeight=%d, inputType=%s"
- " [1.58.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d"
- " [1.58.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d\n"
- " [1.58.0] %s: Frame #%llu:\n"
- " [1.58.0] ++ %s: ASEApiVer=%d\n"
```
