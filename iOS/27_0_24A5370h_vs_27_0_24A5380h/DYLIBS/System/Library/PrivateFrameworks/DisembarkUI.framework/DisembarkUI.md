## DisembarkUI

> `/System/Library/PrivateFrameworks/DisembarkUI.framework/DisembarkUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f874` | `0x1f474` | **`-0x400`** |
| `__TEXT.__eh_frame` | `0x218` | `0x180` | **`-0x98`** |
| `__AUTH_CONST.__cfstring` | `0x1660` | `0x16a0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a50` | `0x1a68` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x808` | `0x7f0` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x28c8` | `0x28d8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x5e0` | `0x5d8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4c8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0x10` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0xc` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-279.0.0.0.0
+281.0.0.0.0

-  Functions: 947
-  Symbols:   1877
-  CStrings:  361
+  Functions: 946
+  Symbols:   1878
+  CStrings:  363
Symbols:
+ -[DKPartnerFinancingConfirmationController _exitTapped:]
CStrings:
+ "DKPartnerFinancingExitButton"
+ "Network Settings"
+ "No app managed features configuration found"
- "Device is eligible for app managed features but not enrolled; no configuration found"
```
