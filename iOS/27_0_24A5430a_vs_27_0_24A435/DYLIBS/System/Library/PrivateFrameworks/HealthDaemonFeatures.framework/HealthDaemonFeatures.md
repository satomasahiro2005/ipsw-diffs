## HealthDaemonFeatures

> `/System/Library/PrivateFrameworks/HealthDaemonFeatures.framework/HealthDaemonFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c6c` | `0xa1d4` | **`+0x568`** |
| `__TEXT.__oslogstring` | `0x415` | `0x465` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x4b0` | `0x4e0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x374` | `0x384` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1f8` | `0x200` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 175
-  Symbols:   413
-  CStrings:  46
+  Functions: 178
+  Symbols:   415
+  CStrings:  49
Symbols:
+ ___VitalsEnhancements_isAvailable
+ __os_feature_enabled_impl
CStrings:
+ "Health"
+ "VitalsEnhancements"
+ "[%{public}s] Updating Vitals compatibility version to %s-%{public}s."
```
