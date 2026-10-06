## OSAnalyticsPrivate

> `/System/Library/PrivateFrameworks/OSAnalyticsPrivate.framework/OSAnalyticsPrivate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1adec` | `0x1b130` | **`+0x344`** |
| `__AUTH_CONST.__cfstring` | `0x2520` | `0x25e0` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x28d0` | `0x2960` | **`+0x90`** |
| `__TEXT.__cstring` | `0x15fe` | `0x166e` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x293c` | `0x29ac` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x48` | `0x98` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1050` | `0x1090` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x168` | `0x190` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x470` | `0x448` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xdf8` | `0xe10` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x438` | `0x440` | **`+0x8`** |

### Other Changes

```diff

-1056.40.5.0.0
+1056.40.8.0.0

-  Functions: 390
-  Symbols:   888
-  CStrings:  592
+  Functions: 394
+  Symbols:   896
+  CStrings:  599
Symbols:
+ +[PCCUtilities diagnosticPipelineLogs]
+ +[PCCUtilities diagnosticPipelineRoot]
+ +[PCCUtilities isDiagnosticPipelineLog:]
+ +[PCCUtilities isSysdiagnose:]
+ +[PCCUtilities sysdiagnoseRoot]
+ _OBJC_CLASS_$_PCCUtilities
+ _OBJC_METACLASS_$_PCCUtilities
+ __OBJC_$_CLASS_METHODS_PCCUtilities
+ __OBJC_CLASS_RO_$_PCCUtilities
+ __OBJC_METACLASS_RO_$_PCCUtilities
- -[PCCProxiedDevice isOnDeviceLog:]
- ___block_descriptor_49_e8_32s40s_e15_v16?0"NSURL"8ls32l8s40l8
CStrings:
+ "/private/var/mobile/Library/Logs/DiagnosticPipeline"
+ "Adding xattr to incoming file %@: %@"
+ "DiagnosticPipeline"
+ "Forcing preservation of sysdiagnose or diagnostic pipeline log: %{public}@"
+ "Not including diagnostic pipeline logs in log list: DiagnosticRequest framework unavailable on current platform"
+ "gz"
+ "memgraph"
+ "reportType"
+ "sysdiagnose"
- "Adding xattr %@: %@"
- "Not including diagnostic pipeline logs in log list: DRGetAllLogFileURLs unavailable on current platform"
```
