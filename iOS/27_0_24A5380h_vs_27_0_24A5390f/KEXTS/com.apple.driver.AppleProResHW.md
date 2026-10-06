## com.apple.driver.AppleProResHW

> `com.apple.driver.AppleProResHW`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x502e0` | `0x541e8` | **`+0x3f08`** |
| `__DATA_CONST.__const` | `0xba28` | `0xbfe0` | **`+0x5b8`** |
| `__TEXT.__os_log` | `0x9d00` | `0x9d48` | **`+0x48`** |

### Other Changes

```diff

-600.38.0.0.0
-  Functions: 2818
+600.45.0.0.0
+  Functions: 3015

-  CStrings:  563
+  CStrings:  564
CStrings:
+ "ERROR AppleProResHW (0x%x): %d: %s(): Could not allocate spare buffer.\n"
```
