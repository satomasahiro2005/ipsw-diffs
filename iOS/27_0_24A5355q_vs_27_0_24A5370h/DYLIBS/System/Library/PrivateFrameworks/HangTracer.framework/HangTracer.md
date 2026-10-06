## HangTracer

> `/System/Library/PrivateFrameworks/HangTracer.framework/HangTracer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x5980` | `0x5a40` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x4346` | `0x43cf` | **`+0x89`** |
| `__TEXT.__text` | `0x16d6c` | `0x16cfc` | **`-0x70`** |
| `__DATA_CONST.__const` | `0x1738` | `0x1768` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x598` | `0x5a8` | **`+0x10`** |

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0

-  Symbols:   1267
-  CStrings:  973
+  Symbols:   1269
+  CStrings:  979
Symbols:
+ _kHTExtendedAttributePerformance
+ _kHTPrefsTerminationsApplicationsTracked
CStrings:
+ "HangTracerEnableTerminationsApplicationsTracked"
+ "Resources"
+ "Security Bounds Safety"
+ "hangtracer.performance"
+ "resources"
+ "security bounds safety"
```
