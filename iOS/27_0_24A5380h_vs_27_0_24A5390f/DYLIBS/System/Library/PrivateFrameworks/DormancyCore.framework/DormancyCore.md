## DormancyCore

> `/System/Library/PrivateFrameworks/DormancyCore.framework/DormancyCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b4d8` | `0x2b800` | **`+0x328`** |
| `__AUTH_CONST.__const` | `0x2638` | `0x26c8` | **`+0x90`** |
| `__TEXT.__const` | `0x3d8c` | `0x3ddc` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x930` | `0x950` | **`+0x20`** |
| `__TEXT.__cstring` | `0x842` | `0x862` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x741` | `0x761` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xd6c` | `0xd88` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0xd08` | `0xd24` | **`+0x1c`** |
| `__TEXT.__oslogstring` | `0xaed` | `0xadd` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xc20` | `0xc30` | **`+0x10`** |
| `__AUTH.__data` | `0x750` | `0x758` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0x850` | `0x858` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xe0d` | `0xe13` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x114` | `0x118` | **`+0x4`** |

### Other Changes

```diff

-27.0.54.0.0
+27.0.57.0.0

-  Functions: 1209
-  Symbols:   588
-  CStrings:  118
+  Functions: 1212
+  Symbols:   590
+  CStrings:  119
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ _symbolic _____ 12DormancyCore19DeviceConfigurationO
CStrings:
+ "Requested to ignoring call at `%s"
+ "com.apple.demo-settings"
- "app_dormancy feature flag not enabled. ignoring call at `%s"
```
