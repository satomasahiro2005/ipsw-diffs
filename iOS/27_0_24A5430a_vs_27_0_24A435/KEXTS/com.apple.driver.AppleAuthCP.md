## com.apple.driver.AppleAuthCP

> `com.apple.driver.AppleAuthCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1a454` | `0x1b0c0` | **`+0xc6c`** |
| `__TEXT.__cstring` | `0x2b50` | `0x2cc2` | **`+0x172`** |

### Other Changes

```diff

-  Functions: 638
+  Functions: 639

-  CStrings:  457
+  CStrings:  463
CStrings:
+ "%s:%s No signature found for the associated challenge. Removing stored info and requesting new signature \n"
+ "%s:%s Received challenge different than what we have stored. Removing stored info and requesting new signature\n"
+ "%s:%s invalid data received for CMD=0x%x\n"
+ "%s:%s no dictionary received for CMD=0x%x\n"
+ "%s:%s processing deferred CMD=0x%x \n"
+ "_processDeferredCommandGated"
```
