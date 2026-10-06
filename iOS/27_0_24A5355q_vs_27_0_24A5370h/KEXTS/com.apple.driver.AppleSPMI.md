## com.apple.driver.AppleSPMI

> `com.apple.driver.AppleSPMI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x350` | **`+0x350`** |
| `__TEXT_EXEC.__text` | `0xa968` | `0xaaa4` | **`+0x13c`** |
| `__TEXT.__cstring` | `0x1e80` | `0x1efc` | **`+0x7c`** |
| `__TEXT.__os_log` | `0xb71` | `0xbc5` | **`+0x54`** |

### Other Changes

```diff

-140.0.0.502.1
-  Functions: 210
+143.0.0.0.0
+  Functions: 213

-  CStrings:  278
+  CStrings:  282
CStrings:
+ "BAD"
+ "[%s]:%s:%d:[error]   [%d] = 0x%02X  parity=%s\n"
+ "[%s]:%s:%d:[error] parity error: parity_rcv=0x%04X parity_exp=0x%04X\n"
+ "ok"
```
