## EnhancedLogging

> `/System/Library/PrivateFrameworks/EnhancedLogging.framework/EnhancedLogging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d2e8` | `0x3dda4` | **`+0xabc`** |
| `__DATA.__bss` | `0x6180` | `0x6500` | **`+0x380`** |
| `__AUTH.__objc_data` | `0x440` | `0x120` | **`-0x320`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x320` | **`+0x320`** |
| `__AUTH.__data` | `0x3f0` | `0x138` | **`-0x2b8`** |
| `__DATA_DIRTY.__data` | `—` | `0x2b0` | **`+0x2b0`** |
| `__TEXT.__const` | `0x3b04` | `0x3c94` | **`+0x190`** |
| `__AUTH_CONST.__const` | `0x5298` | `0x5320` | **`+0x88`** |
| `__TEXT.__eh_frame` | `0x1308` | `0x1378` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x110c` | `0x1146` | **`+0x3a`** |
| `__DATA.__data` | `0xc18` | `0xc50` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x1690` | `0x16c0` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x840` | `0x864` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__cstring` | `0xcab` | `0xccb` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xe30` | `0xe4c` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x30c` | `0x328` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0xcb0` | `0xcc8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1188` | `0x11a0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x940` | `0x950` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d0` | `0x6e0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x6c` | `0x70` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xec` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-236.0.0.0.0
+240.0.0.502.1

-  Functions: 2052
-  Symbols:   892
-  CStrings:  150
+  Functions: 2072
+  Symbols:   902
+  CStrings:  151
Symbols:
+ -[ELTimberLorryUploadConfiguration logFileProcessingConfigurations]
+ -[ELTimberLorryUploadConfiguration sessionFileProcessingConfigurations]
+ -[ELTimberLorryUploadConfiguration setLogFileProcessingConfigurations:]
+ -[ELTimberLorryUploadConfiguration setSessionFileProcessingConfigurations:]
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._logFileProcessingConfigurations
+ _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._sessionFileProcessingConfigurations
+ ___swift_memcpy16_8
+ ___swift_memcpy50_8
+ _associated conformance 15EnhancedLogging12FileProgressV10CodingKeys33_07BE1CB8A976BC5B1879E8604B885527LLOSHAASQ
+ _associated conformance 15EnhancedLogging12FileProgressV10CodingKeys33_07BE1CB8A976BC5B1879E8604B885527LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 15EnhancedLogging12FileProgressV10CodingKeys33_07BE1CB8A976BC5B1879E8604B885527LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 15EnhancedLogging12FileProgressV10CodingKeys33_07BE1CB8A976BC5B1879E8604B885527LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 15EnhancedLogging12FileProgressV10CodingKeys33_07BE1CB8A976BC5B1879E8604B885527LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 15EnhancedLogging12FileProgressV10CodingKeys33_07BE1CB8A976BC5B1879E8604B885527LLO
- -[ELTimberLorryUploadConfiguration processingConfigurations]
- -[ELTimberLorryUploadConfiguration setProcessingConfigurations:]
- _OBJC_IVAR_$_ELTimberLorryUploadConfiguration._processingConfigurations
- ___swift_memcpy42_8
CStrings:
+ "logFileProcessingConfigurations"
+ "sessionFileProcessingConfigurations"
- "processingConfigurations"
```
