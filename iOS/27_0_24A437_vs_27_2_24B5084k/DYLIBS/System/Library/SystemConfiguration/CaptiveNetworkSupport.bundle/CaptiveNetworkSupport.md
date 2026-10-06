## CaptiveNetworkSupport

> `/System/Library/SystemConfiguration/CaptiveNetworkSupport.bundle/CaptiveNetworkSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xb10` | `0xc40` | **`+0x130`** |
| `__TEXT.__cstring` | `0x2268` | `0x22f1` | **`+0x89`** |
| `__TEXT.__text` | `0x30010` | `0x30058` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x5c28` | `0x5c2a` | **`+0x2`** |

### Other Changes

```diff

-542.0.0.0.1
+545.40.1.0.0

-  Functions: 772
-  Symbols:   1496
-  CStrings:  1144
+  Functions: 773
+  Symbols:   1497
+  CStrings:  1153
Symbols:
+ _WISPrResultName
Functions:
~ _CaptiveHandleRedirect : 2684 -> 2720
+ _WISPrResultName
CStrings:
+ "%@: probe result '%s' (%d), assuming online"
+ "APIIsCaptive"
+ "AllowList"
+ "CaptiveNetworkSupport-545.40.1"
+ "InsecureTokenAuthServer"
+ "InternalError"
+ "TLSAbortError"
+ "TLSTrustError"
+ "TokenAuthFailure"
+ "TokenAuthUnsupported"
+ "UnknownState"
- "CaptiveNetworkSupport-542.0.0.0.1"
- "Unknown result value: %d, assuming online"
```
