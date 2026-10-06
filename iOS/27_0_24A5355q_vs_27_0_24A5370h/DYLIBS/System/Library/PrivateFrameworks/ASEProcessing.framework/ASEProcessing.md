## ASEProcessing

> `/System/Library/PrivateFrameworks/ASEProcessing.framework/ASEProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f30` | `0x8ff8` | **`+0xc8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-1.57.0.0.0
+1.58.0.0.0
Functions:
~ -[ASEProcessingT0 processFrameWithInput:Measurement:Output:] : 576 -> 580
~ -[ASEProcessingT0 processFrameWithInput:Measurement:outputData:] : 600 -> 604
~ ___62-[ASEProcessingT0 processFrameWithInput:Measurement:callback:]_block_invoke : 284 -> 288
~ -[ASEProcessingT1 processFrameWithInput:Measurement:outputData:] : 592 -> 596
~ _calcPiecewiseCurveSlope : 144 -> 168
~ _copyPieceWiseCurve : 212 -> 224
~ _copyArray : 156 -> 164
~ _interpolateTwoPieceWiseCurves : 328 -> 340
~ _interpolatePieceWiseCurves : 152 -> 176
~ _interpolateTwoArrays : 224 -> 228
~ _interpolateArray : 148 -> 172
~ _process_measurement : 1144 -> 1184
~ _calculate_control_setting_V2 : 9544 -> 9564
~ _calculate_control_setting_V1 : 2648 -> 2664
CStrings:
+ " [1.58.0] \n"
+ " [1.58.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d\n"
+ " [1.58.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d, fps=%f\n"
+ " [1.58.0]  %30s: %-12d\n"
+ " [1.58.0] %s : bad argument, retVal=%ld, input=%p, aseMeasurementOutput=%p, completionCallback=%p\n"
+ " [1.58.0] %s : config=%p"
+ " [1.58.0] %s : input=%p, aseMeasurementOutput=%p, aseFrameProcessingControl=%p"
+ " [1.58.0] %s : instance=%p, productType=%u, destinationWidth=%d, destinationHeight=%d, inputType=%s"
+ " [1.58.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d"
+ " [1.58.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d\n"
+ " [1.58.0] %s: Frame #%llu:\n"
+ " [1.58.0] ++ %s: ASEApiVer=%d\n"
- " [1.57.0] \n"
- " [1.57.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d\n"
- " [1.57.0]     %s: src={ %dw x %dh }, dest={ %dw x %dh }, aseFunctionOnYesOffNo=%d, fps=%f\n"
- " [1.57.0]  %30s: %-12d\n"
- " [1.57.0] %s : bad argument, retVal=%ld, input=%p, aseMeasurementOutput=%p, completionCallback=%p\n"
- " [1.57.0] %s : config=%p"
- " [1.57.0] %s : input=%p, aseMeasurementOutput=%p, aseFrameProcessingControl=%p"
- " [1.57.0] %s : instance=%p, productType=%u, destinationWidth=%d, destinationHeight=%d, inputType=%s"
- " [1.57.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d"
- " [1.57.0] %s : unknownProcessingType=%d, strength=%f, wxh=%dx%d\n"
- " [1.57.0] %s: Frame #%llu:\n"
- " [1.57.0] ++ %s: ASEApiVer=%d\n"
```
