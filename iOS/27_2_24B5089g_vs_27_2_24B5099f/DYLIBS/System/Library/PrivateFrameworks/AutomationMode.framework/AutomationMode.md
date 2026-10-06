## AutomationMode

> `/System/Library/PrivateFrameworks/AutomationMode.framework/AutomationMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x2c0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x380` | `0x40e` | **`+0x8e`** |
| `__TEXT.__text` | `0x4050` | `0x40b8` | **`+0x68`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x40` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e0` | `0x2e8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x12c` | `0x134` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x3f0` | `0x3f8` | **`+0x8`** |

### Other Changes

```diff

-34.0.0.0.0
+35.0.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 120
-  Symbols:   288
-  CStrings:  58
+  Functions: 121
+  Symbols:   293
+  CStrings:  64
Symbols:
+ -[XAMWriter _reportCancelledAuthentication]
+ GCC_except_table38
+ GCC_except_table43
+ GCC_except_table46
+ GCC_except_table50
+ GCC_except_table53
+ GCC_except_table56
+ _AnalyticsSendEvent
+ _OBJC_CLASS_$_NSConstantDictionary
+ ___kCFBooleanFalse
+ ___kCFBooleanTrue
- GCC_except_table37
- GCC_except_table42
- GCC_except_table45
- GCC_except_table49
- GCC_except_table52
- GCC_except_table55
Functions:
~ ___70-[XAMWriter _authenticateAndEnableAutomationModeWithProxy:completion:]_block_invoke : 44 -> 120
+ -[XAMWriter _reportCancelledAuthentication]
~ ___43-[XAMWriter enableAutomationModeWithError:]_block_invoke : 600 -> 608
CStrings:
+ "authenticationResult"
+ "com.apple.dt.automationmode.AutomationModeAuthenticationEvent"
+ "hasPriorApproval"
+ "i"
+ "lastApprovalAge"
+ "requestedAuthentication"
```
