## Sentry

> `/System/Library/PrivateFrameworks/Sentry.framework/Sentry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10000` | `0x10104` | **`+0x104`** |
| `__TEXT.__cstring` | `0x14aa` | `0x14cc` | **`+0x22`** |
| `__AUTH_CONST.__cfstring` | `0x1220` | `0x1240` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1d9e` | `0x1dbc` | **`+0x1e`** |
| `__TEXT.__gcc_except_tab` | `0x394` | `0x3ac` | **`+0x18`** |

### Other Changes

```diff

-  Functions: 456
+  Functions: 457

-  CStrings:  301
+  CStrings:  303
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
