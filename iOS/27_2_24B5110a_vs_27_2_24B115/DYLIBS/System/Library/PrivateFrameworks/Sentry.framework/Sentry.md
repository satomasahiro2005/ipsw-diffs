## Sentry

> `/System/Library/PrivateFrameworks/Sentry.framework/Sentry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1020c` | `0x10310` | **`+0x104`** |
| `__TEXT.__cstring` | `0x14ec` | `0x150e` | **`+0x22`** |
| `__AUTH_CONST.__cfstring` | `0x1220` | `0x1240` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1d9e` | `0x1dbc` | **`+0x1e`** |
| `__TEXT.__gcc_except_tab` | `0x3a0` | `0x3b8` | **`+0x18`** |

### Other Changes

```diff

-  Functions: 459
+  Functions: 460

-  CStrings:  302
+  CStrings:  304
Functions:
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:] : 2656 -> 2864
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.5 : 96 -> 52
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.6 : 52 -> 96
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.10 : 100 -> 52
+ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.11
CStrings:
+ "App launch threshold enforced"
+ "ApplicationFirstFramePresentation"
```
