## CoreAIRuntime

> `/System/Library/SubFrameworks/CoreAIRuntime.framework/CoreAIRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5283fc` | `0x541170` | **`+0x18d74`** |
| `__TEXT.__unwind_info` | `0x5e20` | `0x58c8` | **`-0x558`** |
| `__TEXT.__const` | `0xde10` | `0xdf60` | **`+0x150`** |
| `__TEXT.__eh_frame` | `0x12410` | `0x122e0` | **`-0x130`** |
| `__TEXT.__cstring` | `0xbfd1` | `0xc001` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x14f8` | `0x1508` | **`+0x10`** |

### Other Changes

```diff

-3600.75.3.0.0
+3600.79.1.0.0

-  Functions: 7990
-  Symbols:   334
-  CStrings:  1016
+  Functions: 7650
+  Symbols:   336
+  CStrings:  1017
Symbols:
+ _objc_retain_x13
+ _objc_retain_x2
+ _objc_retain_x3
- _objc_retain_x4
CStrings:
+ "storage.offset exceeds backing allocation size"
```
