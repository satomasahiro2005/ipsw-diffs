## com.apple.driver.ApplePearlSEPDriver

> `com.apple.driver.ApplePearlSEPDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3f288` | `0x3f444` | **`+0x1bc`** |
| `__TEXT.__os_log` | `0x4ce4` | `0x4d27` | **`+0x43`** |
| `__TEXT.__cstring` | `0xaf3f` | `0xaf58` | **`+0x19`** |
| `__DATA_CONST.__const` | `0x2420` | `0x2428` | **`+0x8`** |

### Other Changes

```diff

-979.0.0.0.2
-  Functions: 715
+980.0.0.0.10
+  Functions: 717

-  CStrings:  1716
+  CStrings:  1718
CStrings:
+ "%s <- cancelOptionsMask:0x%02x, failedAttempt:%d, lock:%d\n"
+ "%s <- request:%u, flags:0x%x data:%p timeout:%u\n"
+ "commandHoldMatchSpecific"
- "%s <- request:%u, flags:0x%x timeout:%u\n"
```
