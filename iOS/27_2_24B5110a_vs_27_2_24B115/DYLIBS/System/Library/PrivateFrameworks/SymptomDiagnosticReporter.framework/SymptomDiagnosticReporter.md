## SymptomDiagnosticReporter

> `/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82a4` | `0x83f8` | **`+0x154`** |
| `__AUTH_CONST.__cfstring` | `0x2240` | `0x22e0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x390` | `0x3c0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1343` | `0x1368` | **`+0x25`** |
| `__DATA_CONST.__objc_arraydata` | `0x490` | `0x4a0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b8` | `0x4c0` | **`+0x8`** |

### Other Changes

```diff

-  CStrings:  343
+  CStrings:  348
Functions:
~ +[SDRDiagnosticReporter isABCEnabled] : 184 -> 204
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 1972 -> 2296
~ +[SDRDiagnosticReporter isABCEnabled].cold.1 : 116 -> 112
CStrings:
+ "4388"
+ "4399"
+ "7932"
+ "WiFi Watchdog"
+ "proxima"
```
