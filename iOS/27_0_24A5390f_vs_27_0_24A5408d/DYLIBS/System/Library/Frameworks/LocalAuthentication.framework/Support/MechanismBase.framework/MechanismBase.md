## MechanismBase

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismBase.framework/MechanismBase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19f28` | `0x1a174` | **`+0x24c`** |
| `__TEXT.__oslogstring` | `0x14ec` | `0x153f` | **`+0x53`** |
| `__TEXT.__objc_methlist` | `0x1dc8` | `0x1de0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1198` | `0x11a0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x788` | `0x790` | **`+0x8`** |

### Other Changes

```diff

-2319.0.46.0.0
+2319.0.63.0.0

-  Functions: 629
-  Symbols:   1357
-  CStrings:  262
+  Functions: 633
+  Symbols:   1360
+  CStrings:  263
Symbols:
+ -[MechanismBase canRecoverFromError:]
+ -[MechanismBaseComposite canRecoverFromError:]
+ GCC_except_table57
+ GCC_except_table80
+ _OUTLINED_FUNCTION_2
- GCC_except_table56
- GCC_except_table79
Functions:
+ -[MechanismBaseComposite canRecoverFromError:]
+ -[MechanismBase canRecoverFromError:]
~ -[MechanismBase subMechanismRequestsRestart:reconnectRemoteUI:] : 108 -> 152
+ _OUTLINED_FUNCTION_2
~ -[MechanismBase isTCCAllowedWithAuditTokenData:optionAuditTokenData:forcePrompt:auditTokenUsage:error:].cold.1 : 60 -> 56
~ -[MechanismBase tccPreflightWithAuditTokenData:auditTokenUsage:].cold.1 : 76 -> 72
~ -[MechanismBase externalizedContext].cold.1 : 60 -> 56
+ -[MechanismBase subMechanismRequestsRestart:reconnectRemoteUI:].cold.1
CStrings:
+ "%{public}@ dropping restart request from %{public}@: isRunning but not a composite"
```
