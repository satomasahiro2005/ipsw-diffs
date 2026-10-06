## AutoBugCaptureCore

> `/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77da0` | `0x77ba0` | **`-0x200`** |
| `__AUTH_CONST.__cfstring` | `0x6c80` | `0x6b80` | **`-0x100`** |
| `__AUTH_CONST.__objc_dictobj` | `0x640` | `0x5a0` | **`-0xa0`** |
| `__DATA_CONST.__objc_arraydata` | `0x630` | `0x5a8` | **`-0x88`** |
| `__TEXT.__cstring` | `0x5255` | `0x51dc` | **`-0x79`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x468` | `0x3f0` | **`-0x78`** |
| `__AUTH_CONST.__objc_const` | `0xc8f0` | `0xc8f8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3748` | `0x3750` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5fcc` | `0x5fd4` | **`+0x8`** |

### Other Changes

```diff

-469.0.0.0.0
+469.40.3.0.0

-  CStrings:  2288
+  CStrings:  2280
Functions:
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 2208 -> 1972
~ -[SystemProperties init] : 1428 -> 1432
~ -[DiagnosticsController addSpecialProjectsDiagnosticActions:] : 288 -> 8
CStrings:
+ "Lazuli"
+ "RCSGroupForking"
- "4388"
- "4399"
- "7932"
- "Proxima"
- "Thread"
- "WiFi Watchdog"
- "com.apple.DiagnosticExtensions.ConnectivityDE"
- "proxima"
- "proxima-diags"
- "smsType: Emergency rat: Unknown"
```
