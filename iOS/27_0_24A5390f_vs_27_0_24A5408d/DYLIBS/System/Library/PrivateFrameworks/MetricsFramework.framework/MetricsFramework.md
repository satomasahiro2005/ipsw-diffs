## MetricsFramework

> `/System/Library/PrivateFrameworks/MetricsFramework.framework/MetricsFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b068` | `0x10c834` | **`+0x17cc`** |
| `__TEXT.__oslogstring` | `0x6a7c` | `0x6c2c` | **`+0x1b0`** |
| `__TEXT.__cstring` | `0x80a0` | `0x8130` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x85e8` | `0x8650` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x3a90` | `0x3ad0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xfb8` | `0xfe8` | **`+0x30`** |
| `__DATA.__data` | `0x20c8` | `0x20f0` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x50c` | `0x52c` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x4df8` | `0x4e10` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2ee2` | `0x2ef8` | **`+0x16`** |
| `__TEXT.__const` | `0xd110` | `0xd120` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x5858` | `0x5868` | **`+0x10`** |

### Other Changes

```diff

-3600.49.12.1.1
+3600.49.21.11.1

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 4870
-  Symbols:   1783
-  CStrings:  1691
+  Functions: 4889
+  Symbols:   1788
+  CStrings:  1700
Symbols:
+ _MGGetStringAnswer
+ ___swift_memcpy216_8
+ ___swift_memcpy897_8
+ _getpwuid
+ _getuid
+ _symbolic SDySSSdG
+ _symbolic _____ySSSdG s18_DictionaryStorageC
- ___swift_memcpy200_8
- ___swift_memcpy881_8
CStrings:
+ "#ExtensionsUtils: Unable to fetch current BuildVersion from MobileGestalt"
+ "/Library/Application Support/com.apple.appleintelligencereporting.processing"
+ "BuildHistory.json"
+ "BuildHistoryProvider currentBuildVersion=%s"
+ "BuildHistoryProvider failed to read %{public}s due to %@"
+ "BuildHistoryProvider failed to resolve user home directory"
+ "BuildHistoryProvider loaded %ld build(s)"
+ "Skipping asset request metrics execution for current date; AssetMetricsWorker.includeCurrentDateForAggregation: %{bool}d"
+ "buildInstallTimestamp"
```
