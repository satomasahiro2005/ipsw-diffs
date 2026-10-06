## Portrait

> `/System/Library/PrivateFrameworks/Portrait.framework/Portrait`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x88a44` | `0x88b78` | **`+0x134`** |
| `__TEXT.__oslogstring` | `0x4b3b` | `0x4b9a` | **`+0x5f`** |
| `__DATA.__bss` | `0x234` | `0x23c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e90` | `0x1e98` | **`+0x8`** |

### Other Changes

```diff

-560.22.1.0.0
+560.22.2.0.0

-  Functions: 3717
-  Symbols:   6459
-  CStrings:  1384
+  Functions: 3718
+  Symbols:   6461
+  CStrings:  1385
Symbols:
+ ___56+[PTTuningParameters hwModelIDFromFigModelSpecificName:]_block_invoke
+ _hwModelIDFromFigModelSpecificName:.onceToken
Functions:
~ +[PTTuningParameters hwModelIDFromFigModelSpecificName:] : 80 -> 232
+ ___56+[PTTuningParameters hwModelIDFromFigModelSpecificName:]_block_invoke
- _OUTLINED_FUNCTION_2
~ ___60+[PTTuningParameters noiseScaleFactorForHwModelID:sensorID:]_block_invoke.cold.1 : 96 -> 104
+ ___56+[PTTuningParameters hwModelIDFromFigModelSpecificName:]_block_invoke.cold.1
CStrings:
+ "Unknown figModelSpecificName %s - device specific tuning parameters will fall back to defaults"
```
