## com.apple.driver.AppleSSE

> `com.apple.driver.AppleSSE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x280` | **`+0x280`** |
| `__TEXT_EXEC.__text` | `0x7f5c` | `0x815c` | **`+0x200`** |
| `__TEXT.__cstring` | `0x16db` | `0x16fc` | **`+0x21`** |

### Other Changes

```diff

-325.0.0.0.0
-  Functions: 131
+327.0.0.0.0
+  Functions: 132

-  CStrings:  122
+  CStrings:  123
CStrings:
+ "*outputBufferLength >= totalSize"
```
