## com.apple.driver.AppleMobileDispH17P-DCP

> `com.apple.driver.AppleMobileDispH17P-DCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x244d0` | `0x24768` | **`+0x298`** |
| `__TEXT.__cstring` | `0x6b10` | `0x6b6d` | **`+0x5d`** |
| `__DATA_CONST.__const` | `0x4f88` | `0x4fa0` | **`+0x18`** |
| `__TEXT_EXEC.__auth_stubs` | `0xe50` | `0xe40` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x728` | `0x720` | **`-0x8`** |

### Other Changes

```diff

-700.50.72.0.0
-  Functions: 1440
+700.50.80.0.0
+  Functions: 1443

-  CStrings:  563
+  CStrings:  568
CStrings:
+ "%s"
+ "%s: max_user_reachable_brightness 0x%x"
+ "DCPEXT"
+ "lMaxReachable"
+ "max_user_reachable_brightness"
```
