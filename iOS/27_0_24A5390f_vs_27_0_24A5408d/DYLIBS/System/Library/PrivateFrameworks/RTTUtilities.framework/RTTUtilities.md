## RTTUtilities

> `/System/Library/PrivateFrameworks/RTTUtilities.framework/RTTUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29c58` | `0x29cd8` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x383d` | `0x38b1` | **`+0x74`** |

### Other Changes

```diff

-536.0.0.0.0
+539.1.0.0.0

-  CStrings:  613
+  CStrings:  614
Functions:
~ -[RTTTelephonyUtilities currentConditionsSupportRTTForContext:] : 444 -> 572
CStrings:
+ "Current conditions don't support RTT locally but relay is supported, so allowing outgoing calls to be dialed as RTT"
```
