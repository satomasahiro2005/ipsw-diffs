## FedStatsPlugin

> `/System/Library/PrivateFrameworks/FedStatsPlugin.framework/FedStatsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x318b4` | `0x319e8` | **`+0x134`** |
| `__AUTH_CONST.__const` | `0xb58` | `0xb80` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xda0` | `0xd80` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x8e2` | `0x8c2` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x630` | `0x618` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xb88` | `0xb98` | **`+0x10`** |
| `__TEXT.__const` | `0xf78` | `0xf68` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x66c` | `0x660` | **`-0xc`** |
| `__AUTH.__data` | `0xd70` | `0xd68` | **`-0x8`** |
| `__DATA.__data` | `0x598` | `0x5a0` | **`+0x8`** |

### Other Changes

```diff

-26.0.0.0.0
+31.0.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 521
+  Functions: 524
Symbols:
+ _AnalyticsSendEventLazy
+ _swift_release_x11
- _symbolic _____ 15PriMLFoundation8TaskTypeO
- _symbolic _____ 8Morpheus0A7ProgramC
```
