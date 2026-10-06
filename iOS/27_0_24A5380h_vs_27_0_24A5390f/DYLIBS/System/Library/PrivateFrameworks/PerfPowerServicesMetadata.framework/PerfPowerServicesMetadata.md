## PerfPowerServicesMetadata

> `/System/Library/PrivateFrameworks/PerfPowerServicesMetadata.framework/PerfPowerServicesMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ec8c` | `0x3eef0` | **`+0x264`** |
| `__AUTH_CONST.__cfstring` | `0x8c60` | `0x8cc0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x18e6` | `0x1941` | **`+0x5b`** |
| `__TEXT.__cstring` | `0x4705` | `0x4751` | **`+0x4c`** |
| `__AUTH_CONST.__const` | `0x540` | `0x560` | **`+0x20`** |
| `__DATA.__bss` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x970` | `0x978` | **`+0x8`** |

### Other Changes

```diff

-3486.0.46.502.1
+3486.0.81.502.4

-  Functions: 1086
-  Symbols:   1731
-  CStrings:  1304
+  Functions: 1090
+  Symbols:   1734
+  CStrings:  1309
Symbols:
+ ___26+[PPSMetric isValidBuild:]_block_invoke
+ _isValidBuild:.onceToken
+ _isValidBuild:.regex
CStrings:
+ "Failed to compile build-validation regex: %@"
+ "Failed to enumerate metadata directory %@: %@"
+ "promptExpertLoadLatency"
+ "totalExpertsNeedingNANDLoad"
+ "totalExpertsPurgedCount"
```
