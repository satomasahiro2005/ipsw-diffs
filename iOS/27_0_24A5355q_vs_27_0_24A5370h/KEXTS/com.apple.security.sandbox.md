## com.apple.security.sandbox

> `com.apple.security.sandbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1e8669` | `0x1eab69` | **`+0x2500`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x1090` | **`+0x1090`** |
| `__TEXT_EXEC.__text` | `0x38100` | `0x38f4c` | **`+0xe4c`** |
| `__TEXT.__os_log` | `0x1d00` | `0x1d58` | **`+0x58`** |
| `__DATA_CONST.__kalloc_type` | `0xbc0` | `0xc00` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x3938` | `0x3928` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xb0` | `0xc0` | **`+0x10`** |
| `__DATA.__bss` | `0x152f8` | `0x15300` | **`+0x8`** |
| `__TEXT.__cstring` | `0x6f48` | `0x6f50` | **`+0x8`** |

### Other Changes

```diff

-3033.0.0.0.1
-  Functions: 653
+3051.0.18.0.3
+  Functions: 659

-  CStrings:  1305
+  CStrings:  1309
CStrings:
+ "%s (%s)"
+ "CoreAnalyticsHub"
+ "Sandbox: hook..execve() killing %s[pid=%d, uid=%d]: %s"
+ "Sandbox: hook..execve() killing %s[pid=%d, uid=%d]: (err=%d) %s"
+ "failed to allocate IOKit matching dictionary for %s"
+ "failed to attach core analytics service"
+ "null"
- "Sandbox: hook..execve() killing %s[pid=%d, uid=%d]: %s%s"
- "Sandbox: hook..execve() killing %s[pid=%d, uid=%d]: (err=%d) %s%s"
- "vm_remap_new_external"
```
