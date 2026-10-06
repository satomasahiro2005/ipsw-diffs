## com.apple.driver.AppleOLYHAL

> `com.apple.driver.AppleOLYHAL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4f86` | `0x4ff0` | **`+0x6a`** |
| `__TEXT_EXEC.__text` | `0x1d8c0` | `0x1d904` | **`+0x44`** |

### Other Changes

```diff

-530.9.0.0.0
-  Functions: 587
+530.9.4.1.0
+  Functions: 588

-  CStrings:  535
+  CStrings:  536
CStrings:
+ "\"AppleOLYHAL Panic: AppleBCMWLAN dext init failure unrecoverable after %u chip resets\" @%s:%d"
+ "Init-failure chip reset limit (%u) reached; WiFi unrecoverable, panicking\n"
- "Init-failure chip reset limit (%u) reached; leaving WiFi down\n"
```
