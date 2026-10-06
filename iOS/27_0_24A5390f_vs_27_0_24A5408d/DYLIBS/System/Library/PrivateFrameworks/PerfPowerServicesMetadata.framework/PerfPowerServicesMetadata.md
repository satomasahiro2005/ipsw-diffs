## PerfPowerServicesMetadata

> `/System/Library/PrivateFrameworks/PerfPowerServicesMetadata.framework/PerfPowerServicesMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eef0` | `0x3efe0` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x8cc0` | `0x8d20` | **`+0x60`** |
| `__TEXT.__cstring` | `0x4751` | `0x4768` | **`+0x17`** |
| `__TEXT.__const` | `0x110` | `0x108` | **`-0x8`** |

### Other Changes

```diff

-3486.0.81.502.4
+3486.2.4.0.0

-  CStrings:  1309
+  CStrings:  1312
Functions:
~ +[PPSSMCMetrics smcOLEDDisplayPowerMetrics] : 412 -> 576
~ +[PPSConfigMetrics cpuCoreConfigMetrics] : 476 -> 552
CStrings:
+ "PDEB"
+ "PDTP"
+ "numMcpuCores"
```
