## com.apple.security.sandbox

> `com.apple.security.sandbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1eecb1` | `0x1f1651` | **`+0x29a0`** |
| `__TEXT_EXEC.__text` | `0x398a4` | `0x39a60` | **`+0x1bc`** |
| `__DATA.__bss` | `0x152fc` | `0x1531c` | **`+0x20`** |
| `__TEXT.__os_log` | `0x1d7e` | `0x1d8e` | **`+0x10`** |

### Other Changes

```diff

-3051.0.52.0.0
-  Functions: 659
+3051.40.70.0.0
+  Functions: 658
CStrings:
+ "failed to register disk image backing store for %s: %d"
+ "failed to register sync root for %s: %d"
+ "failed to unregister disk image backing store for %s: %d"
+ "failed to unregister sync root for %s: %d"
- "failed to register disk image backing store for %s"
- "failed to register sync root for %s"
- "failed to unregister disk image backing store for %s"
- "failed to unregister sync root for %s"
```
