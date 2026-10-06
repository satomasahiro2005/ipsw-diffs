## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/SystemStatusServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fc7c` | `0x1fbec` | **`-0x90`** |
| `__TEXT.__gcc_except_tab` | `0x328` | `0x2a4` | **`-0x84`** |
| `__AUTH_CONST.__cfstring` | `0x1780` | `0x1760` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1d90` | `0x1da8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1cde` | `0x1cdc` | **`-0x2`** |

### Other Changes

```diff

-288.1.3.100.0
+288.1.5.0.0

-  Functions: 741
-  Symbols:   1671
-  CStrings:  288
+  Functions: 742
+  Symbols:   1673
+  CStrings:  287
Symbols:
+ +[STTelephonyStateProvider _statusBarCarrierNameForOperatorName:statusBarImages:]
+ GCC_except_table140
+ GCC_except_table175
+ __OBJC_$_CLASS_METHODS_STTelephonyStateProvider
- GCC_except_table139
- GCC_except_table174
Functions:
~ -[STTelephonyStateProvider _internalQueue_setOperatorName:allowingFakeService:inSubscriptionContext:] : 1496 -> 764
+ +[STTelephonyStateProvider _statusBarCarrierNameForOperatorName:statusBarImages:]
CStrings:
- ":"
```
