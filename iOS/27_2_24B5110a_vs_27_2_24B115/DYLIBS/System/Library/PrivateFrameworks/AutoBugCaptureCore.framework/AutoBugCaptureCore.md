## AutoBugCaptureCore

> `/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77ba0` | `0x77df8` | **`+0x258`** |
| `__AUTH_CONST.__cfstring` | `0x6b80` | `0x6ca0` | **`+0x120`** |
| `__AUTH_CONST.__objc_dictobj` | `0x5a0` | `0x690` | **`+0xf0`** |
| `__DATA_CONST.__objc_arraydata` | `0x5a8` | `0x640` | **`+0x98`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3f0` | `0x468` | **`+0x78`** |
| `__TEXT.__cstring` | `0x51dc` | `0x524c` | **`+0x70`** |

### Other Changes

```diff

-  CStrings:  2280
+  CStrings:  2289
Functions:
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 1972 -> 2296
~ -[SystemProperties init] : 1432 -> 1428
~ -[DiagnosticsController addSpecialProjectsDiagnosticActions:] : 8 -> 288
CStrings:
+ "4388"
+ "4399"
+ "7932"
+ "Proxima"
+ "Thread"
+ "WiFi Watchdog"
+ "com.apple.DiagnosticExtensions.ConnectivityDE"
+ "proxima"
+ "proxima-diags"
```
