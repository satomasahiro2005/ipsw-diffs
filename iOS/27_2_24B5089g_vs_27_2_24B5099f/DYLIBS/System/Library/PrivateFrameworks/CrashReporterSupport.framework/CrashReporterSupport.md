## CrashReporterSupport

> `/System/Library/PrivateFrameworks/CrashReporterSupport.framework/CrashReporterSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60ac` | `0x61c0` | **`+0x114`** |
| `__AUTH_CONST.__cfstring` | `0x14c0` | `0x1540` | **`+0x80`** |
| `__TEXT.__cstring` | `0xe65` | `0xe7e` | **`+0x19`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x30` | `0x48` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x58` | `0x70` | **`+0x18`** |

### Other Changes

```diff

-14280.0.0.0.0
+14281.0.0.0.0

-  CStrings:  250
+  CStrings:  254
Symbols:
+ ___block_descriptor_64_e8_32s40s48s56s_e15_v16?0"NSURL"8ls32l8s40l8s48l8s56l8
- ___block_descriptor_56_e8_32s40s48s_e15_v16?0"NSURL"8ls32l8s40l8s48l8
Functions:
~ _OSAGetSubmittableLogsWithMetadata : 336 -> 428
~ ___OSAGetSubmittableLogsWithMetadata_block_invoke : 476 -> 660
CStrings:
+ "log"
+ "proxy"
+ "reportType"
+ "txt"
```
