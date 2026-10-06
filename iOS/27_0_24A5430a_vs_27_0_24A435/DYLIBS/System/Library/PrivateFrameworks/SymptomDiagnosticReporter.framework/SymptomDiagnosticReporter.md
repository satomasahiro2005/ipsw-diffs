## SymptomDiagnosticReporter

> `/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x828c` | `0x83a0` | **`+0x114`** |
| `__AUTH_CONST.__cfstring` | `0x2200` | `0x22a0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x390` | `0x3c0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1342` | `0x1367` | **`+0x25`** |
| `__DATA_CONST.__objc_arraydata` | `0x480` | `0x490` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b8` | `0x4c0` | **`+0x8`** |

### Other Changes

```diff

-  CStrings:  341
+  CStrings:  346
Functions:
~ +[SDRDiagnosticReporter isABCEnabled] : 184 -> 204
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 1948 -> 2208
~ +[SDRDiagnosticReporter isABCEnabled].cold.1 : 116 -> 112
CStrings:
+ "4388"
+ "4399"
+ "7932"
+ "WiFi Watchdog"
+ "proxima"
```
