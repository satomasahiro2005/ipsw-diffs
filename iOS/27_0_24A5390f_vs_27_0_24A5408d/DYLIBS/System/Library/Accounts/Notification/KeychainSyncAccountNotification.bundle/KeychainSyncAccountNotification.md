## KeychainSyncAccountNotification

> `/System/Library/Accounts/Notification/KeychainSyncAccountNotification.bundle/KeychainSyncAccountNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2170` | `0x2354` | **`+0x1e4`** |
| `__TEXT.__oslogstring` | `0x642` | `0x68e` | **`+0x4c`** |
| `__AUTH_CONST.__const` | `0x160` | `0x180` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x208` | `0x228` | **`+0x20`** |
| `__TEXT.__cstring` | `0x242` | `0x254` | **`+0x12`** |
| `__DATA.__bss` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xe0` | **`+0x8`** |

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

-  Functions: 39
-  Symbols:   89
-  CStrings:  69
+  Functions: 43
+  Symbols:   92
+  CStrings:  72
Symbols:
+ __SecTrustUseBestEffortTimeClearOverride
+ __SecTrustUseBestEffortTimeEnabled
+ __SecTrustUseBestEffortTimeSetOverride
CStrings:
+ "BestEffortTime usage overridden to %s"
+ "BestEffortTime usage override removed"
+ "UseBestEffortTime"
```
