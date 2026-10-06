## AutoBugCaptureCore

> `/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77b88` | `0x77da0` | **`+0x218`** |
| `__AUTH_CONST.__cfstring` | `0x6b60` | `0x6c80` | **`+0x120`** |
| `__AUTH_CONST.__objc_dictobj` | `0x550` | `0x640` | **`+0xf0`** |
| `__DATA_CONST.__objc_arraydata` | `0x598` | `0x630` | **`+0x98`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3f0` | `0x468` | **`+0x78`** |
| `__TEXT.__cstring` | `0x51e5` | `0x5255` | **`+0x70`** |

### Other Changes

```diff

-  CStrings:  2279
+  CStrings:  2288
Functions:
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 1948 -> 2208
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
