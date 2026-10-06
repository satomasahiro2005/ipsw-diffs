## com.apple.security.sandbox

> `com.apple.security.sandbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1ed021` | `0x1ee609` | **`+0x15e8`** |
| `__TEXT.__cstring` | `0x6f50` | `0x6f21` | **`-0x2f`** |
| `__TEXT.__os_log` | `0x1d58` | `0x1d7e` | **`+0x26`** |
| `__TEXT_EXEC.__auth_stubs` | `0x1090` | `0x1080` | **`-0x10`** |
| `__TEXT_EXEC.__text` | `0x38ee0` | `0x38ef0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x848` | `0x840` | **`-0x8`** |
| `__DATA.__bss` | `0x15300` | `0x152fc` | **`-0x4`** |

### Other Changes

```diff

-3051.0.30.0.0
-  Functions: 659
+3051.0.42.0.2
+  Functions: 658
CStrings:
+ "mask size (%zu) exceeds maximum (%zu)"
- "\"mask size (%zu) exceeds maximum (%zu)\" @%s:%d"
```
