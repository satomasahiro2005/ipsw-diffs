## com.apple.driver.ApplePearlSEPDriver

> `com.apple.driver.ApplePearlSEPDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__os_log` | `0x4d27` | `0x4d0d` | **`-0x1a`** |
| `__TEXT_EXEC.__text` | `0x3f46c` | `0x3f478` | **`+0xc`** |

### Other Changes

```diff

-980.0.18.0.0
-  Functions: 719
+980.0.26.0.0
+  Functions: 720
CStrings:
+ "%s <- lock:%d\n"
- "%s <- cancelOptionsMask:0x%02x, lock:%d\n"
```
