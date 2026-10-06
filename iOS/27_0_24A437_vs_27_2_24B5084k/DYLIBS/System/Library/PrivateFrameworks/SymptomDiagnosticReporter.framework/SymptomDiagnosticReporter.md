## SymptomDiagnosticReporter

> `/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83a0` | `0x82a4` | **`-0xfc`** |
| `__AUTH_CONST.__cfstring` | `0x22a0` | `0x2240` | **`-0x60`** |
| `__AUTH_CONST.__objc_dictobj` | `0x488` | `0x4d8` | **`+0x50`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3c0` | `0x390` | **`-0x30`** |
| `__TEXT.__cstring` | `0x1367` | `0x1343` | **`-0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c0` | `0x4b8` | **`-0x8`** |

### Other Changes

```diff

-469.0.0.0.0
+469.40.3.0.0

-  CStrings:  346
+  CStrings:  343
Functions:
~ +[SDRDiagnosticReporter isABCEnabled] : 204 -> 184
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 2208 -> 1972
~ +[SDRDiagnosticReporter isABCEnabled].cold.1 : 112 -> 116
CStrings:
+ "Lazuli"
+ "RCSGroupForking"
+ "Telephony"
- "4388"
- "4399"
- "7932"
- "WiFi Watchdog"
- "proxima"
- "smsType: Emergency rat: Unknown"
```
