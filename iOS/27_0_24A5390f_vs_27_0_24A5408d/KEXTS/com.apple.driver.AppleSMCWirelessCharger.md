## com.apple.driver.AppleSMCWirelessCharger

> `com.apple.driver.AppleSMCWirelessCharger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x110e4` | `0x113c4` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x37ce` | `0x3848` | **`+0x7a`** |

### Other Changes

```diff

-155.0.5.0.0
+155.0.10.0.0

-  CStrings:  464
+  CStrings:  468
Functions:
~ sub_fffffff0096a2344 -> sub_fffffff00968db24 : 5532 -> 5760
~ sub_fffffff0096af674 -> sub_fffffff00969af38 : 1456 -> 1760
~ sub_fffffff0096b1e60 -> sub_fffffff00969d854 : 2132 -> 2332
~ sub_fffffff0096b26b4 -> sub_fffffff00969e170 : 112 -> 116
CStrings:
+ "%s: Failed to set WAEQ to %d (ret=%d)\n"
+ "chg-disable-inductive-fw-reload-on-crash"
+ "chg-esp-dis-coex-mask"
+ "chg-esp-keyfob-risk"
```
