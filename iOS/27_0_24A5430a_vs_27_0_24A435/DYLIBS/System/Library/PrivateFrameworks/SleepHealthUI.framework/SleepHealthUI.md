## SleepHealthUI

> `/System/Library/PrivateFrameworks/SleepHealthUI.framework/SleepHealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a5b1c` | `0x1a5de4` | **`+0x2c8`** |
| `__TEXT.__cstring` | `0x60b1` | `0x6101` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2e98` | `0x2eb8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1ca0` | `0x1cb8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5798` | `0x57b0` | **`+0x18`** |
| `__DATA.__data` | `0x4460` | `0x4470` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 9332
-  Symbols:   3086
-  CStrings:  918
+  Functions: 9336
+  Symbols:   3089
+  CStrings:  922
Symbols:
+ ___DaytimeMetrics_isAvailable
+ ___VitalsEnhancements_isAvailable
+ __os_feature_enabled_impl
CStrings:
+ "DaytimeMetrics"
+ "Health"
+ "VitalsEnhancements"
+ "todaysDaytimeVitals"
```
