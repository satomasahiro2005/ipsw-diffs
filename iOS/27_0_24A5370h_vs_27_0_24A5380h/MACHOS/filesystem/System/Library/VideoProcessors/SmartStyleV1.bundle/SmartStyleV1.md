## SmartStyleV1

> `/System/Library/VideoProcessors/SmartStyleV1.bundle/SmartStyleV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16320` | `0x163e0` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x510d` | `0x5133` | **`+0x26`** |
| `__TEXT.__objc_stubs` | `0x2340` | `0x2360` | **`+0x20`** |
| `__TEXT.__const` | `0xb0` | `0xa0` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x2a15` | `0x2a09` | **`-0xc`** |
| `__TEXT.__objc_methtype` | `0x13c4` | `0x13cf` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0xc10` | `0xc18` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1d8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x175c` | `0x1764` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-753.0.0.122.3
+758.0.0.122.2

-  Functions: 561
-  Symbols:   1004
-  CStrings:  1156
+  Functions: 562
+  Symbols:   1006
+  CStrings:  1158
Symbols:
+ -[CMISmartStyleProcessorV1 _filteredSRLCurveParameterForCurrent:]
+ _objc_msgSend$_filteredSRLCurveParameterForCurrent:
Functions:
~ -[CMISmartStyleProcessorV1 process] : 9276 -> 9320
+ -[CMISmartStyleProcessorV1 _filteredSRLCurveParameterForCurrent:]
~ -[CMISmartStyleProcessorUtilitiesV1 createLinearThumbnailFromMetadata:postLTMThumbnailPixelBuffer:cameraInfo:applyGDC:cropToPreLTMBounds:toPixelBuffer:] : 3356 -> 3352
CStrings:
+ "<<<< CMISmartStyleProcessor >>>> %s: SRL masks missing; holding previous curve parameter %f across the gap"
+ "_filteredSRLCurveParameterForCurrent:"
+ "f20@0:8f16"
- "<<<< CMISmartStyleProcessor >>>> %s: Unexpected SRL state: after receiving valid masks curve parameter must stay valid"
```
