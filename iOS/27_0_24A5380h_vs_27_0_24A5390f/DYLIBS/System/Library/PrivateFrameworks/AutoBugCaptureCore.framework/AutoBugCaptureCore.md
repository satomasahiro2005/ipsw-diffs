## AutoBugCaptureCore

> `/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77aec` | `0x77b88` | **`+0x9c`** |
| `__AUTH_CONST.__cfstring` | `0x6b40` | `0x6b60` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3740` | `0x3748` | **`+0x8`** |
| `__TEXT.__cstring` | `0x51e1` | `0x51e5` | **`+0x4`** |

### Other Changes

```diff

-467.0.0.0.0
+469.0.0.0.0

-  CStrings:  2278
+  CStrings:  2279
Functions:
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 1896 -> 1948
~ -[DiagnosticCaseManager initWithWorkspace:liaison:] : 616 -> 720
CStrings:
+ "int"
```
