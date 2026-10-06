## com.apple.driver.AppleOLYHAL

> `com.apple.driver.AppleOLYHAL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x700` | **`+0x700`** |
| `__TEXT_EXEC.__text` | `0x1c79c` | `0x1c8b4` | **`+0x118`** |
| `__TEXT.__cstring` | `0x483e` | `0x4860` | **`+0x22`** |

### Other Changes

```diff

-530.4.0.0.0
-  Functions: 570
+530.5.0.0.0
+  Functions: 569
CStrings:
+ "%s::%s: Deferred dext recovery already pending; coalescing repeat crash\n"
- "\"%s:%u:\" \"!fDextRecoveryPaused\" @%s:%d"
```
