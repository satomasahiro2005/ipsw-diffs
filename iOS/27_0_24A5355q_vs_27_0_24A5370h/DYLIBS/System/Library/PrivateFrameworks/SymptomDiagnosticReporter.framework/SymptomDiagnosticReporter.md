## SymptomDiagnosticReporter

> `/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x22e0` | `0x21e0` | **`-0x100`** |
| `__TEXT.__cstring` | `0x13db` | `0x133e` | **`-0x9d`** |
| `__DATA_CONST.__objc_arraydata` | `0x510` | `0x480` | **`-0x90`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3f0` | `0x390` | **`-0x60`** |
| `__AUTH_CONST.__objc_dictobj` | `0x4d8` | `0x488` | **`-0x50`** |
| `__TEXT.__text` | `0x81f8` | `0x8230` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x60` | `0x80` | **`+0x20`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2c0` | **`+0x10`** |

### Other Changes

```diff

-460.0.0.0.0
+464.0.0.0.0

-  Functions: 191
-  Symbols:   497
-  CStrings:  348
+  Functions: 193
+  Symbols:   501
+  CStrings:  340
Symbols:
+ ____remoteInterface_block_invoke
+ __remoteInterface.onceToken
+ __remoteInterface.sRemoteInterface
+ _objc_release_x1
Functions:
~ -[SDRDiagnosticReporter setupXPCInterface] : 468 -> 464
~ -[SDRDiagnosticReporter _payloadAugmentedWithSandboxExtensionTokensDict:] : 820 -> 816
+ ____remoteInterface_block_invoke
~ +[CaseDampeningExceptions isString:inExceptionList:] : 388 -> 384
~ +[CaseDampeningExceptions allowDampeningExceptionFor:] : 1920 -> 1896
+ -[SDRDiagnosticReporter setupXPCInterface].cold.1
CStrings:
- "Home Button"
- "On-Screen Affordance"
- "Raise To Speak"
- "SiriAssistant"
- "Voice"
- "client.request-failed"
- "kAFAssistantErrorDomain.1_Carry"
- "kAFAssistantErrorDomain.1_NonCarry"
```
