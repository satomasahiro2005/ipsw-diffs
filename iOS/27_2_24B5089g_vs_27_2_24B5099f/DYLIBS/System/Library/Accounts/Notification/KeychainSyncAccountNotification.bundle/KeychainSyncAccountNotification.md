## KeychainSyncAccountNotification

> `/System/Library/Accounts/Notification/KeychainSyncAccountNotification.bundle/KeychainSyncAccountNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2354` | `0x26ec` | **`+0x398`** |
| `__TEXT.__oslogstring` | `0x68e` | `0x740` | **`+0xb2`** |
| `__AUTH_CONST.__const` | `0x180` | `0x1c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x228` | `0x268` | **`+0x40`** |
| `__TEXT.__cstring` | `0x254` | `0x285` | **`+0x31`** |
| `__DATA.__bss` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe0` | `0xf0` | **`+0x10`** |
| `__TEXT.__const` | `0xa0` | `0x98` | **`-0x8`** |

### Other Changes

```diff

-62460.40.56.502.1
+62460.40.74.0.0

-  Functions: 43
-  Symbols:   92
-  CStrings:  72
+  Functions: 51
+  Symbols:   98
+  CStrings:  78
Symbols:
+ __SecTrustUseSSRFLiteralEnforcement
+ __SecTrustUseSSRFLiteralEnforcementClearOverride
+ __SecTrustUseSSRFLiteralEnforcementSetOverride
+ __SecTrustUseSSRFPortEnforcement
+ __SecTrustUseSSRFPortEnforcementClearOverride
+ __SecTrustUseSSRFPortEnforcementSetOverride
CStrings:
+ "SSRFLiteralEnforcement usage overridden to %s"
+ "SSRFLiteralEnforcement usage override removed"
+ "SSRFPortEnforcement usage overridden to %s"
+ "SSRFPortEnforcement usage override removed"
+ "UseSSRFLiteralEnforcement"
+ "UseSSRFPortEnforcement"
```
