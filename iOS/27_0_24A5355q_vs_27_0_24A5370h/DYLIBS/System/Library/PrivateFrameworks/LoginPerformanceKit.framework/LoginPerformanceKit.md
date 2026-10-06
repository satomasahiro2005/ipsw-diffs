## LoginPerformanceKit

> `/System/Library/PrivateFrameworks/LoginPerformanceKit.framework/LoginPerformanceKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c30` | `0x4c18` | **`-0x18`** |

### Other Changes

```diff

-3030.0.0.0.0
+3031.0.0.0.0
Functions:
~ -[LPKPerfResultEntry _reCalculateValuesIfNeeded] : 484 -> 480
~ +[LPKPerfResultAnalyzer analyzePerformanceTestResult:type:count:] : 1164 -> 1156
~ ___65+[LPKPerfResultAnalyzer analyzePerformanceTestResult:type:count:]_block_invoke : 840 -> 832
~ +[LPKPerformanceTestIntermediary _generateSharedipadTraceHelperCommand] : 388 -> 384
```
