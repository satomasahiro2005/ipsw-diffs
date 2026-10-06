## com.apple.driver.ApplePMGR

> `com.apple.driver.ApplePMGR`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x60f88` | `0x61f44` | **`+0xfbc`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x820` | **`+0x820`** |
| `__TEXT.__cstring` | `0xfe42` | `0xfec7` | **`+0x85`** |
| `__DATA_CONST.__const` | `0xb9d8` | `0xb9f8` | **`+0x20`** |

### Other Changes

```diff

-1966.0.0.0.0
-  Functions: 2853
+1976.0.0.0.0
+  Functions: 2854

-  CStrings:  1799
+  CStrings:  1801
CStrings:
+ "\"ApplePMGR: %s:%u \" \"Die %u, Deadline: 0x%llx, AbsTime: 0x%llx PMP Failed to Come Online within %llu ticks\" @%s:%d"
+ "timeout-panic-pmp"
```
